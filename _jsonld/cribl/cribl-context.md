---
api_specs:
- filename: cribl-cloud-api-openapi.yml
  format: yaml
  label: Cribl Cloud API
  slug: cribl-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-cloud-api-openapi.yml
- filename: cribl-stream-api-openapi.yml
  format: yaml
  label: Cribl Stream API
  slug: cribl-stream-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-stream-api-openapi.yml
- filename: cribl-edge-api-openapi.yml
  format: yaml
  label: Cribl Edge API
  slug: cribl-edge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-edge-api-openapi.yml
- filename: cribl-search-api-openapi.yml
  format: yaml
  label: Cribl Search API
  slug: cribl-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-search-api-openapi.yml
- filename: cribl-lake-api-openapi.yml
  format: yaml
  label: Cribl Lake API
  slug: cribl-lake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-lake-api-openapi.yml
- filename: cribl-as-code-api-openapi.yml
  format: yaml
  label: Cribl As Code API
  slug: cribl-as-code-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-as-code-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cribl-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/json-ld/cribl-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cribl from Cribl.
layout: jsonld
name: Cribl Context
namespaces:
- prefix: cribl
  uri: https://schemas.cribl.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: PipelineFunction
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Source
  type: ''
- container: ''
  name: Destination
  type: ''
- container: ''
  name: WorkerGroup
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: LakeDataset
  type: ''
- container: ''
  name: SearchJob
  type: ''
- container: ''
  name: Pack
  type: ''
property_count: 11
provider_name: Cribl
provider_slug: cribl
slug: cribl-context
source_filename: cribl-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cribl\": \"https://schemas.cribl.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Pipeline\": {\n      \"@id\": \"cribl:Pipeline\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"functions\": {\n          \"@id\": \"cribl:hasFunctions\",\n          \"@container\": \"@list\"\n        },\n        \"output\": {\n          \"@id\": \"cribl:outputDestination\"\n        },\n        \"streamtags\": {\n          \"@id\": \"cribl:streamtags\",\n          \"@container\": \"@set\"\n        },\n        \"asyncFuncTimeout\": {\n          \"@id\": \"cribl:asyncFuncTimeout\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"PipelineFunction\": {\n      \"@id\": \"cribl:PipelineFunction\",\n      \"@context\": {\n        \"\
  id\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"filter\": \"cribl:filterExpression\",\n        \"disabled\": {\n          \"@id\": \"cribl:isDisabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"cribl:Route\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"filter\": \"cribl:filterExpression\",\n        \"pipeline\": {\n          \"@id\": \"cribl:routesPipeline\"\n        },\n        \"output\": {\n          \"@id\": \"cribl:routesDestination\"\n        },\n        \"final\": {\n          \"@id\": \"cribl:isFinalRoute\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"disabled\": {\n          \"@id\": \"cribl:isDisabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Source\": {\n      \"@id\": \"cribl:Source\",\n      \"@context\"\
  : {\n        \"id\": \"schema:identifier\",\n        \"type\": \"cribl:sourceType\",\n        \"description\": \"schema:description\",\n        \"host\": {\n          \"@id\": \"cribl:hostAddress\"\n        },\n        \"port\": {\n          \"@id\": \"cribl:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"disabled\": {\n          \"@id\": \"cribl:isDisabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"pipeline\": {\n          \"@id\": \"cribl:routesPipeline\"\n        },\n        \"streamtags\": {\n          \"@id\": \"cribl:streamtags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Destination\": {\n      \"@id\": \"cribl:Destination\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"type\": \"cribl:destinationType\",\n        \"description\": \"schema:description\",\n        \"host\": {\n          \"@id\": \"cribl:hostAddress\"\n        },\n        \"port\": {\n          \"@id\": \"cribl:portNumber\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"disabled\": {\n          \"@id\": \"cribl:isDisabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"streamtags\": {\n          \"@id\": \"cribl:streamtags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"WorkerGroup\": {\n      \"@id\": \"cribl:WorkerGroup\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"isFleet\": {\n          \"@id\": \"cribl:isEdgeFleet\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"workerCount\": {\n          \"@id\": \"cribl:nodeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"configVersion\": \"cribl:configurationVersion\"\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"cribl:Node\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"hostname\": \"cribl:hostname\",\n        \"group\"\
  : {\n          \"@id\": \"cribl:belongsToGroup\"\n        },\n        \"version\": \"schema:softwareVersion\",\n        \"status\": \"cribl:operationalStatus\",\n        \"os\": \"schema:operatingSystem\",\n        \"cpuUsage\": {\n          \"@id\": \"cribl:cpuUtilization\",\n          \"@type\": \"xsd:float\"\n        },\n        \"memUsage\": {\n          \"@id\": \"cribl:memoryUtilization\",\n          \"@type\": \"xsd:float\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"cribl:Workspace\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"organizationId\": \"cribl:belongsToOrganization\",\n        \"status\": \"cribl:operationalStatus\",\n        \"region\": \"cribl:cloudRegion\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n    \
  \      \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LakeDataset\": {\n      \"@id\": \"cribl:LakeDataset\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"retentionDays\": {\n          \"@id\": \"cribl:retentionPeriodDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"format\": \"cribl:storageFormat\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SearchJob\": {\n      \"@id\": \"cribl:SearchJob\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"query\": \"cribl:searchQuery\",\n     \
  \   \"status\": \"cribl:operationalStatus\",\n        \"dataset\": \"cribl:searchesDataset\",\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numResults\": {\n          \"@id\": \"cribl:resultCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Pack\": {\n      \"@id\": \"cribl:Pack\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"source\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        },\n        \"version\": \"schema:softwareVersion\",\n        \"author\": \"schema:author\",\n        \"description\": \"schema:description\",\n        \"displayName\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/json-ld/cribl-context.jsonld
tags:
- Configuration
- Data Lake
- Data Pipelines
- Data Routing
- Edge Computing
- Infrastructure as Code
- Observability
- Search
- Security Data
- Stream Processing
- Telemetry
- JSON-LD
- Linked Data
- Semantic Web
---
