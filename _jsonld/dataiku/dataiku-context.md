---
api_specs:
- filename: index.html
  format: yaml
  label: Dataiku Public API
  slug: dataiku-public-api
  spec_type: OpenAPI
  url: https://doc.dataiku.com/dss/latest/publicapi/rest/index.html
- filename: dataiku-api-node-admin-openapi.yml
  format: yaml
  label: Dataiku API Node Administration API
  slug: dataiku-api-node-administration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/openapi/dataiku-api-node-admin-openapi.yml
- filename: dataiku-govern-api-openapi.yml
  format: yaml
  label: Dataiku Govern API
  slug: dataiku-govern-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/openapi/dataiku-govern-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/dataiku-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/json-ld/dataiku-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dataiku from Dataiku.
layout: jsonld
name: Dataiku Context
namespaces:
- prefix: dataiku
  uri: https://doc.dataiku.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Recipe
  type: ''
- container: ''
  name: SavedModel
  type: ''
- container: ''
  name: Scenario
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: ManagedFolder
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: CodeEnv
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: Blueprint
  type: ''
- container: ''
  name: GovernArtifact
  type: ''
- container: ''
  name: APINodeService
  type: ''
property_count: 14
provider_name: Dataiku
provider_slug: dataiku
slug: dataiku-context
source_filename: dataiku-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dataiku\": \"https://doc.dataiku.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"dataiku:Project\",\n      \"@context\": {\n        \"projectKey\": \"dataiku:projectKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"owner\": \"dataiku:owner\",\n        \"projectStatus\": \"dataiku:projectStatus\",\n        \"tags\": \"schema:keywords\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"dataiku:Dataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"\
  dataiku:datasetType\",\n        \"managed\": {\n          \"@id\": \"dataiku:managed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"formatType\": \"dataiku:formatType\",\n        \"projectKey\": \"dataiku:projectKey\",\n        \"connection\": \"dataiku:connection\"\n      }\n    },\n\n    \"Recipe\": {\n      \"@id\": \"dataiku:Recipe\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"dataiku:recipeType\",\n        \"projectKey\": \"dataiku:projectKey\"\n      }\n    },\n\n    \"SavedModel\": {\n      \"@id\": \"dataiku:SavedModel\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"dataiku:modelType\",\n        \"projectKey\": \"dataiku:projectKey\",\n        \"activeVersion\": \"dataiku:activeVersion\"\n      }\n    },\n\n    \"Scenario\": {\n      \"@id\": \"dataiku:Scenario\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"dataiku:scenarioType\",\n        \"projectKey\"\
  : \"dataiku:projectKey\",\n        \"active\": {\n          \"@id\": \"dataiku:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"dataiku:Job\",\n      \"@context\": {\n        \"state\": \"dataiku:jobState\",\n        \"initiator\": \"dataiku:initiator\",\n        \"projectKey\": \"dataiku:projectKey\",\n        \"startTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"dataiku:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ManagedFolder\": {\n      \"@id\": \"dataiku:ManagedFolder\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"dataiku:folderType\",\n        \"projectKey\": \"dataiku:projectKey\"\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"dataiku:Connection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"\
  dataiku:connectionType\",\n        \"allowWrite\": {\n          \"@id\": \"dataiku:allowWrite\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"allowManagedDatasets\": {\n          \"@id\": \"dataiku:allowManagedDatasets\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CodeEnv\": {\n      \"@id\": \"dataiku:CodeEnv\",\n      \"@context\": {\n        \"envName\": \"schema:name\",\n        \"envLang\": \"dataiku:envLang\",\n        \"deploymentMode\": \"dataiku:deploymentMode\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"dataiku:User\",\n      \"@context\": {\n        \"login\": \"dataiku:login\",\n        \"displayName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"userProfile\": \"dataiku:userProfile\",\n        \"enabled\": {\n          \"@id\": \"dataiku:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Plugin\": {\n      \"@id\": \"dataiku:Plugin\",\n      \"@context\": {\n\
  \        \"label\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"author\": \"schema:author\",\n        \"installedOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Blueprint\": {\n      \"@id\": \"dataiku:Blueprint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"artifactCount\": {\n          \"@id\": \"dataiku:artifactCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"GovernArtifact\": {\n      \"@id\": \"dataiku:GovernArtifact\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"blueprintId\": \"dataiku:blueprintId\",\n        \"status\": \"dataiku:artifactStatus\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": \"dataiku:createdBy\"\
  \n      }\n    },\n\n    \"APINodeService\": {\n      \"@id\": \"dataiku:APINodeService\",\n      \"@context\": {\n        \"serviceId\": \"dataiku:serviceId\",\n        \"enabled\": {\n          \"@id\": \"dataiku:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"activeGeneration\": \"dataiku:activeGeneration\",\n        \"generationCount\": {\n          \"@id\": \"dataiku:generationCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/json-ld/dataiku-context.jsonld
tags:
- Analytics
- Artificial Intelligence
- Data Platform
- Data Science
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
