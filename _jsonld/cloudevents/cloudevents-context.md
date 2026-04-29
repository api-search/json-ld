---
api_specs:
- filename: cloudevents-http-asyncapi.yml
  format: yaml
  label: CloudEvents Specification
  slug: cloudevents-spec
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/asyncapi/cloudevents-http-asyncapi.yml
- filename: cloudevents-subscriptions-openapi.yml
  format: yaml
  label: CloudEvents Subscriptions API
  slug: cloudevents-subscriptions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/openapi/cloudevents-subscriptions-openapi.yml
class_count: 4
classes:
- CloudEvent
- Subscription
- Filter
- ProtocolSettings
context_file: json-ld/cloudevents-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/json-ld/cloudevents-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudevents from CloudEvents.
layout: jsonld
name: Cloudevents Context
namespaces:
- prefix: ce
  uri: https://cloudevents.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: specversion
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: source
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: datacontenttype
  type: string
- container: ''
  name: dataschema
  type: reference
- container: ''
  name: subject
  type: string
- container: ''
  name: time
  type: dateTime
- container: ''
  name: data
  type: ''
- container: ''
  name: data_base64
  type: base64Binary
- container: ''
  name: sink
  type: reference
- container: ''
  name: protocol
  type: string
- container: ''
  name: protocolSettings
  type: ''
- container: set
  name: filters
  type: ''
- container: set
  name: types
  type: ''
- container: ''
  name: config
  type: ''
- container: ''
  name: dialect
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: contentMode
  type: string
- container: ''
  name: traceparent
  type: string
- container: ''
  name: tracestate
  type: string
- container: ''
  name: partitionkey
  type: string
- container: ''
  name: sampledrate
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: version
  type: string
property_count: 27
provider_name: CloudEvents
provider_slug: cloudevents
slug: cloudevents-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ce\": \"https://cloudevents.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"CloudEvent\": \"ce:CloudEvent\",\n    \"Subscription\": \"ce:Subscription\",\n    \"Filter\": \"ce:Filter\",\n    \"ProtocolSettings\": \"ce:ProtocolSettings\",\n\n    \"specversion\": {\n      \"@id\": \"ce:specversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"dcterms:source\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"ce:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datacontenttype\": {\n      \"@id\": \"ce:dataContentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataschema\": {\n      \"@id\": \"ce:dataSchema\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"subject\": {\n      \"@id\": \"dcterms:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": {\n      \"@id\": \"ce:data\"\n    },\n    \"data_base64\": {\n      \"@id\": \"ce:dataBinary\",\n      \"@type\": \"xsd:base64Binary\"\n    },\n\n    \"sink\": {\n      \"@id\": \"ce:sink\",\n      \"@type\": \"@id\"\n    },\n    \"protocol\": {\n      \"@id\": \"ce:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolSettings\": {\n      \"@id\": \"ce:protocolSettings\"\n    },\n    \"filters\": {\n      \"@id\": \"ce:filters\",\n      \"@container\": \"@set\"\n    },\n    \"types\": {\n      \"@id\": \"ce:eventTypes\",\n      \"@container\": \"@set\"\n    },\n    \"config\": {\n      \"@id\": \"ce:config\"\n    },\n\n    \"dialect\": {\n      \"@id\": \"ce:filterDialect\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\"\
  : {\n      \"@id\": \"ce:filterExpression\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"contentMode\": {\n      \"@id\": \"ce:contentMode\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"traceparent\": {\n      \"@id\": \"ce:traceparent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tracestate\": {\n      \"@id\": \"ce:tracestate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitionkey\": {\n      \"@id\": \"ce:partitionKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sampledrate\": {\n      \"@id\": \"ce:sampledRate\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/json-ld/cloudevents-context.jsonld
tags:
- Cloud Native
- Events
- Graduated
- Interoperability
- Messaging
- Specification
- JSON-LD
- Linked Data
- Semantic Web
---
