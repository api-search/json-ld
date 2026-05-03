---
api_specs:
- filename: pact_broker.json
  format: json
  label: Pact Broker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/pact-foundation/pact_broker/master/lib/pact_broker/api/pact_broker.json
class_count: 3
classes:
- TestFirstContract
- MockServer
- TestFirstSpecification
context_file: json-ld/test-first-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-first/refs/heads/main/json-ld/test-first-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test First from Test First.
layout: jsonld
name: Test First Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: testfirst
  uri: https://api-evangelist.github.io/test-first/schema/
properties:
- container: ''
  name: author
  type: string
- container: ''
  name: baseUrl
  type: reference
- container: ''
  name: body
  type: ''
- container: ''
  name: component
  type: string
- container: ''
  name: consumer
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: createdAt
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: dynamic
  type: boolean
- container: ''
  name: format
  type: string
- container: ''
  name: given
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: id
  type: ''
- container: set
  name: interactions
  type: ''
- container: ''
  name: metadata
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: pactSpecification
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: providerState
  type: string
- container: ''
  name: proxyEnabled
  type: boolean
- container: ''
  name: request
  type: ''
- container: ''
  name: response
  type: ''
- container: ''
  name: responseBody
  type: ''
- container: set
  name: routes
  type: ''
- container: set
  name: scenarios
  type: ''
- container: ''
  name: specFormat
  type: string
- container: ''
  name: specSource
  type: reference
- container: ''
  name: status
  type: integer
- container: ''
  name: statusCode
  type: integer
- container: set
  name: tags
  type: string
- container: ''
  name: then
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: when
  type: string
property_count: 37
provider_name: Test First
provider_slug: test-first
slug: test-first-context
source_filename: test-first-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"testfirst\": \"https://api-evangelist.github.io/test-first/schema/\",\n    \"TestFirstContract\": \"testfirst:TestFirstContract\",\n    \"MockServer\": \"testfirst:MockServer\",\n    \"TestFirstSpecification\": \"testfirst:TestFirstSpecification\",\n    \"author\": {\n      \"@id\": \"testfirst:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"testfirst:base_url\",\n      \"@type\": \"@id\"\n    },\n    \"body\": {\n      \"@id\": \"testfirst:body\"\n    },\n    \"component\": {\n      \"@id\": \"testfirst:component\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumer\": {\n      \"@id\": \"testfirst:consumer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"testfirst:content_type\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"testfirst:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"dynamic\": {\n      \"@id\": \"testfirst:dynamic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"format\": {\n      \"@id\": \"testfirst:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"given\": {\n      \"@id\": \"testfirst:given\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"testfirst:headers\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n    \"interactions\": {\n      \"@id\": \"testfirst:interactions\",\n      \"@container\": \"@set\"\n    },\n    \"metadata\": {\n      \"@id\": \"testfirst:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"method\": {\n      \"@id\": \"testfirst:method\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"pactSpecification\": {\n      \"@id\": \"testfirst:pact_specification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"testfirst:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"testfirst:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerState\": {\n      \"@id\": \"testfirst:provider_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"proxyEnabled\": {\n      \"@id\": \"testfirst:proxy_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"request\": {\n      \"@id\": \"testfirst:request\"\n    },\n    \"response\": {\n      \"@id\": \"testfirst:response\"\n    },\n    \"responseBody\": {\n      \"@id\": \"testfirst:response_body\"\n    },\n    \"routes\": {\n      \"@id\": \"testfirst:routes\",\n      \"@container\": \"@set\"\n    },\n    \"scenarios\": {\n      \"@id\": \"testfirst:scenarios\",\n      \"@container\"\
  : \"@set\"\n    },\n    \"specFormat\": {\n      \"@id\": \"testfirst:spec_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specSource\": {\n      \"@id\": \"testfirst:spec_source\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"testfirst:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"statusCode\": {\n      \"@id\": \"testfirst:status_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tags\": {\n      \"@id\": \"testfirst:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"then\": {\n      \"@id\": \"testfirst:then\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"testfirst:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"when\": {\n      \"@id\": \"testfirst:when\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-first/refs/heads/main/json-ld/test-first-context.jsonld
tags:
- Behavior-Driven Development
- Best Practices
- Methodology
- Software Design
- Software Development
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
