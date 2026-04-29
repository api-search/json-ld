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
- SparqlErrorResponse
- SparqlQueryStatusDetail
- SparqlQueryStatusList
- SparqlRequestBody
- SparqlSelectResponse
context_file: json-ld/amazon-neptune-sparql-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-sparql-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Sparql from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Sparql Context
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
- container: set
  name: bindings
  type: reference
- container: ''
  name: boolean
  type: boolean
- container: ''
  name: cancelled
  type: boolean
- container: ''
  name: code
  type: string
- container: ''
  name: detailedMessage
  type: string
- container: ''
  name: elapsed
  type: integer
- container: ''
  name: head
  type: reference
- container: set
  name: link
  type: string
- container: set
  name: queries
  type: string
- container: ''
  name: query
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
  name: results
  type: reference
- container: ''
  name: runningQueryCount
  type: integer
- container: ''
  name: update
  type: string
- container: ''
  name: using-graph-uri
  type: string
- container: ''
  name: using-named-graph-uri
  type: string
- container: set
  name: vars
  type: string
- container: ''
  name: waited
  type: integer
property_count: 22
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-sparql-context
source_filename: amazon-neptune-sparql-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SparqlErrorResponse\": \"neptune:SparqlErrorResponse\",\n    \"SparqlQueryStatusDetail\": \"neptune:SparqlQueryStatusDetail\",\n    \"SparqlQueryStatusList\": \"neptune:SparqlQueryStatusList\",\n    \"SparqlRequestBody\": \"neptune:SparqlRequestBody\",\n    \"SparqlSelectResponse\": \"neptune:SparqlSelectResponse\",\n    \"acceptedQueryCount\": {\n      \"@id\": \"neptune:acceptedQueryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bindings\": {\n      \"@id\": \"neptune:bindings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"boolean\": {\n      \"@id\": \"neptune:boolean\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cancelled\": {\n      \"@id\": \"neptune:cancelled\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"code\": {\n      \"@id\": \"neptune:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detailedMessage\": {\n      \"@id\": \"neptune:detailedMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elapsed\": {\n      \"@id\": \"neptune:elapsed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"head\": {\n      \"@id\": \"neptune:head\",\n      \"@type\": \"@id\"\n    },\n    \"link\": {\n      \"@id\": \"neptune:link\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queries\": {\n      \"@id\": \"neptune:queries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"neptune:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryEvalStats\": {\n      \"@id\": \"neptune:queryEvalStats\",\n      \"@type\": \"@id\"\n    },\n    \"queryId\": {\n      \"@id\": \"neptune:queryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryString\": {\n     \
  \ \"@id\": \"neptune:queryString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"neptune:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"neptune:results\",\n      \"@type\": \"@id\"\n    },\n    \"runningQueryCount\": {\n      \"@id\": \"neptune:runningQueryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"update\": {\n      \"@id\": \"neptune:update\",\n      \"@type\": \"xsd:string\"\n    },\n    \"using-graph-uri\": {\n      \"@id\": \"neptune:using-graph-uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"using-named-graph-uri\": {\n      \"@id\": \"neptune:using-named-graph-uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vars\": {\n      \"@id\": \"neptune:vars\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waited\": {\n      \"@id\": \"neptune:waited\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-sparql-context.jsonld
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
