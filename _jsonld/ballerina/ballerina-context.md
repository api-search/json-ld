---
api_specs:
- filename: ballerina-central-api.yml
  format: yaml
  label: Ballerina
  slug: ballerina
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ballerina/refs/heads/main/openapi/ballerina-central-api.yml
class_count: 10
classes:
- Connector
- ConnectorSearchResponse
- ConnectorSummary
- Module
- Organization
- Package
- PackageDocs
- PackageSearchResponse
- PackageSummary
- PackageVersion
context_file: json-ld/ballerina-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ballerina/refs/heads/main/json-ld/ballerina-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ballerina from Ballerina.
layout: jsonld
name: Ballerina Context
namespaces:
- prefix: ballerina
  uri: https://central.ballerina.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: authors
  type: string
- container: ''
  name: ballerinaVersion
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: connectors
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: createdDate
  type: dateTime
- container: set
  name: dependencies
  type: string
- container: ''
  name: description
  type: ''
- container: set
  name: functions
  type: string
- container: set
  name: keywords
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: moduleName
  type: string
- container: set
  name: modules
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: offset
  type: integer
- container: ''
  name: organization
  type: string
- container: ''
  name: packageCount
  type: integer
- container: ''
  name: packageName
  type: string
- container: set
  name: packages
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: pullCount
  type: integer
- container: ''
  name: readme
  type: string
- container: ''
  name: repositoryURL
  type: reference
- container: ''
  name: version
  type: ''
- container: set
  name: versions
  type: string
- container: ''
  name: website
  type: reference
property_count: 27
provider_name: Ballerina
provider_slug: ballerina
slug: ballerina-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ballerina\": \"https://central.ballerina.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Connector\": \"ballerina:Connector\",\n    \"ConnectorSearchResponse\": \"ballerina:ConnectorSearchResponse\",\n    \"ConnectorSummary\": \"ballerina:ConnectorSummary\",\n    \"Module\": \"ballerina:Module\",\n    \"Organization\": \"ballerina:Organization\",\n    \"Package\": \"ballerina:Package\",\n    \"PackageDocs\": \"ballerina:PackageDocs\",\n    \"PackageSearchResponse\": \"ballerina:PackageSearchResponse\",\n    \"PackageSummary\": \"ballerina:PackageSummary\",\n    \"PackageVersion\": \"ballerina:PackageVersion\",\n    \"authors\": {\n      \"@id\": \"ballerina:authors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ballerinaVersion\": {\n      \"@id\": \"ballerina:ballerinaVersion\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"category\": {\n      \"@id\": \"ballerina:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectors\": {\n      \"@id\": \"ballerina:connectors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"ballerina:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdDate\": {\n      \"@id\": \"ballerina:createdDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dependencies\": {\n      \"@id\": \"ballerina:dependencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"functions\": {\n      \"@id\": \"ballerina:functions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"ballerina:keywords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"ballerina:license\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"ballerina:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"moduleName\": {\n      \"@id\": \"ballerina:moduleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modules\": {\n      \"@id\": \"ballerina:modules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"offset\": {\n      \"@id\": \"ballerina:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"organization\": {\n      \"@id\": \"ballerina:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageCount\": {\n      \"@id\": \"ballerina:packageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"packageName\": {\n      \"@id\": \"ballerina:packageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packages\": {\n      \"@id\": \"ballerina:packages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  platform\": {\n      \"@id\": \"ballerina:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pullCount\": {\n      \"@id\": \"ballerina:pullCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"readme\": {\n      \"@id\": \"ballerina:readme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryURL\": {\n      \"@id\": \"ballerina:repositoryURL\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"versions\": {\n      \"@id\": \"ballerina:versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"website\": {\n      \"@id\": \"ballerina:website\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ballerina/refs/heads/main/json-ld/ballerina-context.jsonld
tags:
- Integrations
- Orchestrations
- Open Source
- Programming Language
- JSON-LD
- Linked Data
- Semantic Web
---
