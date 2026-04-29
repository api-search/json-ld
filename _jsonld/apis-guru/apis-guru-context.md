---
class_count: 5
classes:
- ApiVersion
- Metrics
- APIs
- API
- updated
context_file: json-ld/apis-guru-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-ld/apis-guru-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apis Guru from APIs.guru.
layout: jsonld
name: Apis Guru Context
namespaces:
- prefix: pan
  uri: https://apis.guru/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: added
  type: dateTime
- container: ''
  name: externalDocs
  type: reference
- container: ''
  name: info
  type: reference
- container: ''
  name: link
  type: reference
- container: ''
  name: openapiVer
  type: string
- container: ''
  name: swaggerUrl
  type: reference
- container: ''
  name: swaggerYamlUrl
  type: reference
- container: set
  name: datasets
  type: string
- container: ''
  name: fixedPct
  type: integer
- container: ''
  name: fixes
  type: integer
- container: ''
  name: invalid
  type: integer
- container: ''
  name: issues
  type: integer
- container: ''
  name: numAPIs
  type: integer
- container: ''
  name: numDrivers
  type: integer
- container: ''
  name: numEndpoints
  type: integer
- container: ''
  name: numProviders
  type: integer
- container: ''
  name: numSpecs
  type: integer
- container: ''
  name: stars
  type: integer
- container: ''
  name: thisWeek
  type: reference
- container: ''
  name: unofficial
  type: integer
- container: ''
  name: unreachable
  type: integer
- container: ''
  name: preferred
  type: string
- container: ''
  name: versions
  type: reference
property_count: 23
provider_name: APIs.guru
provider_slug: apis-guru
slug: apis-guru-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://apis.guru/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiVersion\": \"pan:ApiVersion\",\n    \"Metrics\": \"pan:Metrics\",\n    \"APIs\": \"pan:APIs\",\n    \"API\": \"pan:API\",\n    \"added\": {\n      \"@id\": \"pan:added\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"externalDocs\": {\n      \"@id\": \"pan:externalDocs\",\n      \"@type\": \"@id\"\n    },\n    \"info\": {\n      \"@id\": \"pan:info\",\n      \"@type\": \"@id\"\n    },\n    \"link\": {\n      \"@id\": \"pan:link\",\n      \"@type\": \"@id\"\n    },\n    \"openapiVer\": {\n      \"@id\": \"pan:openapiVer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swaggerUrl\": {\n      \"@id\": \"pan:swaggerUrl\",\n      \"@type\": \"@id\"\n    },\n    \"swaggerYamlUrl\": {\n      \"@id\": \"pan:swaggerYamlUrl\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"updated\": \"schema:dateModified\",\n    \"datasets\": {\n      \"@id\": \"pan:datasets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixedPct\": {\n      \"@id\": \"pan:fixedPct\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fixes\": {\n      \"@id\": \"pan:fixes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"invalid\": {\n      \"@id\": \"pan:invalid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"issues\": {\n      \"@id\": \"pan:issues\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numAPIs\": {\n      \"@id\": \"pan:numAPIs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numDrivers\": {\n      \"@id\": \"pan:numDrivers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numEndpoints\": {\n      \"@id\": \"pan:numEndpoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numProviders\": {\n      \"@id\": \"pan:numProviders\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numSpecs\": {\n     \
  \ \"@id\": \"pan:numSpecs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stars\": {\n      \"@id\": \"pan:stars\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"thisWeek\": {\n      \"@id\": \"pan:thisWeek\",\n      \"@type\": \"@id\"\n    },\n    \"unofficial\": {\n      \"@id\": \"pan:unofficial\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unreachable\": {\n      \"@id\": \"pan:unreachable\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"preferred\": {\n      \"@id\": \"pan:preferred\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"pan:versions\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-ld/apis-guru-context.jsonld
tags:
- API Catalog
- API Directory
- API Discovery
- Community
- GraphQL
- Open Source
- OpenAPI
- JSON-LD
- Linked Data
- Semantic Web
---
