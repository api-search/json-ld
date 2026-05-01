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
class_count: 5
classes:
- GremlinErrorResponse
- GremlinQueryRequest
- GremlinQueryResponse
- GremlinQueryStatusDetail
- GremlinQueryStatusList
context_file: json-ld/amazon-neptune-gremlin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-gremlin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Gremlin from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Gremlin Context
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
  name: acceptedQueryCount
  type: integer
- container: ''
  name: attributes
  type: reference
- container: ''
  name: cancelled
  type: boolean
- container: ''
  name: code
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: detailedMessage
  type: string
- container: ''
  name: elapsed
  type: integer
- container: ''
  name: gremlin
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: meta
  type: reference
- container: set
  name: queries
  type: string
- container: ''
  name: queryEvalStats
  type: reference
- container: ''
  name: queryId
  type: string
- container: ''
  name: queryString
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: result
  type: reference
- container: ''
  name: runningQueryCount
  type: integer
- container: ''
  name: status
  type: reference
- container: ''
  name: subqueries
  type: reference
- container: ''
  name: waited
  type: integer
property_count: 20
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-gremlin-context
source_filename: amazon-neptune-gremlin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GremlinErrorResponse\": \"neptune:GremlinErrorResponse\",\n    \"GremlinQueryRequest\": \"neptune:GremlinQueryRequest\",\n    \"GremlinQueryResponse\": \"neptune:GremlinQueryResponse\",\n    \"GremlinQueryStatusDetail\": \"neptune:GremlinQueryStatusDetail\",\n    \"GremlinQueryStatusList\": \"neptune:GremlinQueryStatusList\",\n    \"acceptedQueryCount\": {\n      \"@id\": \"neptune:acceptedQueryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attributes\": {\n      \"@id\": \"neptune:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"cancelled\": {\n      \"@id\": \"neptune:cancelled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"code\": {\n      \"@id\": \"neptune:code\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"data\": {\n      \"@id\": \"neptune:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detailedMessage\": {\n      \"@id\": \"neptune:detailedMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elapsed\": {\n      \"@id\": \"neptune:elapsed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gremlin\": {\n      \"@id\": \"neptune:gremlin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"neptune:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"neptune:meta\",\n      \"@type\": \"@id\"\n    },\n    \"queries\": {\n      \"@id\": \"neptune:queries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryEvalStats\": {\n      \"@id\": \"neptune:queryEvalStats\",\n      \"@type\": \"@id\"\n    },\n    \"queryId\": {\n      \"@id\": \"neptune:queryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryString\": {\n      \"@id\": \"neptune:queryString\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"neptune:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"neptune:result\",\n      \"@type\": \"@id\"\n    },\n    \"runningQueryCount\": {\n      \"@id\": \"neptune:runningQueryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"neptune:status\",\n      \"@type\": \"@id\"\n    },\n    \"subqueries\": {\n      \"@id\": \"neptune:subqueries\",\n      \"@type\": \"@id\"\n    },\n    \"waited\": {\n      \"@id\": \"neptune:waited\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-gremlin-context.jsonld
tags:
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
