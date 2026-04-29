---
api_specs:
- filename: amazon-neptune-management-openapi.yml
  format: yaml
  label: Amazon Neptune Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-management-openapi.yml
- filename: amazon-neptune-data-openapi.yml
  format: yaml
  label: Amazon Neptune Data API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-data-openapi.yml
- filename: amazon-neptune-gremlin-openapi.yml
  format: yaml
  label: Neptune Gremlin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-gremlin-openapi.yml
- filename: amazon-neptune-sparql-openapi.yml
  format: yaml
  label: Neptune SPARQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-sparql-openapi.yml
- filename: amazon-neptune-opencypher-openapi.yml
  format: yaml
  label: Neptune openCypher API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-opencypher-openapi.yml
- filename: amazon-neptune-streams-openapi.yml
  format: yaml
  label: Neptune Streams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-streams-openapi.yml
- filename: amazon-neptune-loader-openapi.yml
  format: yaml
  label: Neptune Loader API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-loader-openapi.yml
- filename: amazon-neptune-ml-openapi.yml
  format: yaml
  label: Neptune ML API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-ml-openapi.yml
- filename: amazon-neptune-analytics-openapi.yml
  format: yaml
  label: Neptune Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-analytics-openapi.yml
class_count: 6
classes:
- PropertyGraphData
- PropertyGraphStreamRecord
- PropertyGraphStreamResponse
- SparqlStreamRecord
- SparqlStreamResponse
- StreamEventId
context_file: json-ld/amazon-neptune-streams-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-streams-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Streams from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Streams Context
namespaces:
- prefix: neptune
  uri: https://neptune.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: commitNum
  type: integer
- container: ''
  name: commitTimestamp
  type: integer
- container: ''
  name: data
  type: reference
- container: ''
  name: dataType
  type: string
- container: ''
  name: eventId
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: isLastOp
  type: boolean
- container: ''
  name: key
  type: string
- container: ''
  name: lastEventId
  type: string
- container: ''
  name: lastTrxTimestamp
  type: integer
- container: ''
  name: op
  type: string
- container: ''
  name: opNum
  type: integer
- container: set
  name: records
  type: string
- container: ''
  name: stmt
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: totalRecords
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: reference
property_count: 20
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-streams-context
source_filename: amazon-neptune-streams-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PropertyGraphData\": \"neptune:PropertyGraphData\",\n    \"PropertyGraphStreamRecord\": \"neptune:PropertyGraphStreamRecord\",\n    \"PropertyGraphStreamResponse\": \"neptune:PropertyGraphStreamResponse\",\n    \"SparqlStreamRecord\": \"neptune:SparqlStreamRecord\",\n    \"SparqlStreamResponse\": \"neptune:SparqlStreamResponse\",\n    \"StreamEventId\": \"neptune:StreamEventId\",\n    \"commitNum\": {\n      \"@id\": \"neptune:commitNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commitTimestamp\": {\n      \"@id\": \"neptune:commitTimestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"neptune:data\",\n      \"@type\": \"@id\"\n    },\n    \"dataType\": {\n      \"@id\": \"neptune:dataType\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"eventId\": {\n      \"@id\": \"neptune:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"neptune:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"neptune:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"neptune:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isLastOp\": {\n      \"@id\": \"neptune:isLastOp\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"key\": {\n      \"@id\": \"neptune:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEventId\": {\n      \"@id\": \"neptune:lastEventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTrxTimestamp\": {\n      \"@id\": \"neptune:lastTrxTimestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"op\": {\n      \"@id\": \"neptune:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opNum\": {\n      \"@id\": \"neptune:opNum\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"records\": {\n      \"@id\": \"neptune:records\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stmt\": {\n      \"@id\": \"neptune:stmt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"neptune:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRecords\": {\n      \"@id\": \"neptune:totalRecords\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"neptune:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"neptune:value\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-streams-context.jsonld
tags:
- AWS
- Database
- Graph Database
- Gremlin
- Neptune
- Property Graph
- RDF
- SPARQL
- JSON-LD
- Linked Data
- Semantic Web
---
