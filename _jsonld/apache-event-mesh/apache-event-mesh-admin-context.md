---
class_count: 5
classes:
- CloudEvent
- Client
- ApiResponse
- Subscription
- url
context_file: json-ld/apache-event-mesh-admin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/json-ld/apache-event-mesh-admin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Event Mesh Admin from Apache EventMesh.
layout: jsonld
name: Apache Event Mesh Admin Context
namespaces:
- prefix: eventmesh
  uri: https://eventmesh.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
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
  type: string
- container: ''
  name: data_base64
  type: string
- container: ''
  name: env
  type: string
- container: ''
  name: idc
  type: string
- container: ''
  name: sys
  type: string
- container: ''
  name: ip
  type: string
- container: ''
  name: pid
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: group
  type: string
- container: set
  name: topics
  type: string
- container: ''
  name: retCode
  type: integer
- container: ''
  name: retMsg
  type: string
- container: ''
  name: topic
  type: string
property_count: 21
provider_name: Apache EventMesh
provider_slug: apache-event-mesh
slug: apache-event-mesh-admin-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"eventmesh\": \"https://eventmesh.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CloudEvent\": \"eventmesh:CloudEvent\",\n    \"specversion\": {\n      \"@id\": \"eventmesh:specversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"eventmesh:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"eventmesh:source\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"eventmesh:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datacontenttype\": {\n      \"@id\": \"eventmesh:datacontenttype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataschema\": {\n      \"@id\": \"eventmesh:dataschema\",\n      \"@type\": \"@id\"\n    },\n    \"subject\": {\n      \"@id\": \"eventmesh:subject\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"time\": {\n      \"@id\": \"eventmesh:time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": {\n      \"@id\": \"eventmesh:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data_base64\": {\n      \"@id\": \"eventmesh:data_base64\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Client\": \"eventmesh:Client\",\n    \"env\": {\n      \"@id\": \"eventmesh:env\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idc\": {\n      \"@id\": \"eventmesh:idc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sys\": {\n      \"@id\": \"eventmesh:sys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip\": {\n      \"@id\": \"eventmesh:ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pid\": {\n      \"@id\": \"eventmesh:pid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"eventmesh:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"eventmesh:group\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"topics\": {\n      \"@id\": \"eventmesh:topics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApiResponse\": \"eventmesh:ApiResponse\",\n    \"retCode\": {\n      \"@id\": \"eventmesh:retCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retMsg\": {\n      \"@id\": \"eventmesh:retMsg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subscription\": \"eventmesh:Subscription\",\n    \"topic\": {\n      \"@id\": \"eventmesh:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/json-ld/apache-event-mesh-admin-context.jsonld
tags:
- Apache
- CloudEvents
- Event-Driven
- Messaging
- Open Source
- Pub-Sub
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
