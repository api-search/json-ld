---
class_count: 3
classes:
- GraphQLError
- GraphQLRequest
- GraphQLResponse
context_file: json-ld/pluralsight-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pluralsight/refs/heads/main/json-ld/pluralsight-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pluralsight from Pluralsight.
layout: jsonld
name: Pluralsight Context
namespaces:
- prefix: ps
  uri: https://developer.pluralsight.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: data
  type: reference
- container: set
  name: errors
  type: string
- container: set
  name: locations
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: operationName
  type: string
- container: set
  name: path
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: variables
  type: reference
property_count: 8
provider_name: Pluralsight
provider_slug: pluralsight
slug: pluralsight-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ps\": \"https://developer.pluralsight.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GraphQLError\": \"ps:GraphQLError\",\n    \"GraphQLRequest\": \"ps:GraphQLRequest\",\n    \"GraphQLResponse\": \"ps:GraphQLResponse\",\n    \"data\": {\n      \"@id\": \"ps:data\",\n      \"@type\": \"@id\"\n    },\n    \"errors\": {\n      \"@id\": \"ps:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"ps:locations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"ps:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationName\": {\n      \"@id\": \"ps:operationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"ps:path\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"query\": {\n      \"@id\": \"ps:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variables\": {\n      \"@id\": \"ps:variables\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pluralsight/refs/heads/main/json-ld/pluralsight-context.jsonld
tags:
- Courses
- Education
- Engineering Metrics
- Learning
- Skills Assessment
- Technology
- Video Training
- JSON-LD
- Linked Data
- Semantic Web
---
