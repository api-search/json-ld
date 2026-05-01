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
- LoaderErrorResponse
- LoaderListResponse
- LoaderRequest
- LoaderStartResponse
- LoaderStatusResponse
context_file: json-ld/amazon-neptune-loader-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-loader-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Loader from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Loader Context
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
  name: allowEmptyStrings
  type: boolean
- container: ''
  name: baseUri
  type: string
- container: ''
  name: code
  type: string
- container: set
  name: dependencies
  type: string
- container: ''
  name: detailedMessage
  type: string
- container: ''
  name: failOnError
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: iamRoleArn
  type: string
- container: set
  name: loadIds
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: namedGraphUri
  type: string
- container: ''
  name: parallelism
  type: string
- container: ''
  name: parserConfiguration
  type: reference
- container: ''
  name: payload
  type: reference
- container: ''
  name: queueRequest
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: updateSingleCardinalityProperties
  type: string
- container: ''
  name: userProvidedEdgeIds
  type: string
property_count: 21
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-loader-context
source_filename: amazon-neptune-loader-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoaderErrorResponse\": \"neptune:LoaderErrorResponse\",\n    \"LoaderListResponse\": \"neptune:LoaderListResponse\",\n    \"LoaderRequest\": \"neptune:LoaderRequest\",\n    \"LoaderStartResponse\": \"neptune:LoaderStartResponse\",\n    \"LoaderStatusResponse\": \"neptune:LoaderStatusResponse\",\n    \"allowEmptyStrings\": {\n      \"@id\": \"neptune:allowEmptyStrings\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"baseUri\": {\n      \"@id\": \"neptune:baseUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"neptune:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependencies\": {\n      \"@id\": \"neptune:dependencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"detailedMessage\": {\n      \"@id\": \"neptune:detailedMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failOnError\": {\n      \"@id\": \"neptune:failOnError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"neptune:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamRoleArn\": {\n      \"@id\": \"neptune:iamRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loadIds\": {\n      \"@id\": \"neptune:loadIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"neptune:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namedGraphUri\": {\n      \"@id\": \"neptune:namedGraphUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parallelism\": {\n      \"@id\": \"neptune:parallelism\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parserConfiguration\": {\n      \"@id\": \"neptune:parserConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"payload\": {\n\
  \      \"@id\": \"neptune:payload\",\n      \"@type\": \"@id\"\n    },\n    \"queueRequest\": {\n      \"@id\": \"neptune:queueRequest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"neptune:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"neptune:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"neptune:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"neptune:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateSingleCardinalityProperties\": {\n      \"@id\": \"neptune:updateSingleCardinalityProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProvidedEdgeIds\": {\n      \"@id\": \"neptune:userProvidedEdgeIds\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-loader-context.jsonld
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
