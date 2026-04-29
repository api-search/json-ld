---
api_specs:
- filename: boomi-platform-rest-api-openapi.yml
  format: yaml
  label: Boomi Platform REST API
  slug: platform-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boomi/refs/heads/main/openapi/boomi-platform-rest-api-openapi.yml
- filename: boomi-datahub-api-openapi.yml
  format: yaml
  label: Boomi DataHub API
  slug: datahub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boomi/refs/heads/main/openapi/boomi-datahub-api-openapi.yml
- filename: boomi-event-streams-openapi.yml
  format: yaml
  label: Boomi Event Streams REST API
  slug: event-streams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boomi/refs/heads/main/openapi/boomi-event-streams-openapi.yml
class_count: 0
classes: []
context_file: json-ld/boomi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/boomi/refs/heads/main/json-ld/boomi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Boomi from Boomi.
layout: jsonld
name: Boomi Context
namespaces:
- prefix: boomi
  uri: https://api.boomi.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Process
  type: ''
- container: ''
  name: Atom
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: DeployedPackage
  type: ''
- container: ''
  name: ExecutionRecord
  type: ''
- container: ''
  name: AIAgent
  type: ''
- container: ''
  name: AgentTool
  type: ''
- container: ''
  name: Repository
  type: ''
- container: ''
  name: GoldenRecord
  type: ''
- container: ''
  name: EventMessage
  type: ''
- container: ''
  name: Connector
  type: ''
property_count: 11
provider_name: Boomi
provider_slug: boomi
slug: boomi-context
source_filename: boomi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"boomi\": \"https://api.boomi.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Process\": {\n      \"@id\": \"boomi:Process\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\"\n        },\n        \"folderId\": {\n          \"@id\": \"boomi:folderId\"\n        },\n        \"deleted\": {\n          \"@id\": \"schema:isBasedOn\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"currentVersion\": {\n          \"@id\": \"schema:version\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"schedules\": {\n          \"@id\": \"boomi:hasSchedule\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"deployments\": {\n          \"@id\": \"boomi:hasDeployment\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Atom\": {\n      \"@id\": \"boomi:Atom\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"status\": {\n          \"@id\": \"boomi:status\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\"\n        },\n        \"hostName\": {\n          \"@id\": \"schema:hostName\"\n        },\n        \"currentVersion\": {\n          \"@id\": \"schema:version\"\n        },\n        \"dateInstalled\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"boomi:Environment\"\
  ,\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"classification\": {\n          \"@id\": \"boomi:classification\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DeployedPackage\": {\n      \"@id\": \"boomi:DeployedPackage\",\n      \"@context\": {\n        \"deploymentId\": \"@id\",\n        \"environmentId\": {\n          \"@id\": \"boomi:deployedToEnvironment\",\n          \"@type\": \"@id\"\n        },\n        \"packageId\": {\n          \"@id\": \"boomi:packageId\",\n          \"@type\": \"@id\"\n        },\n        \"componentId\": {\n          \"@id\": \"boomi:componentId\",\n          \"@type\": \"@id\"\n        },\n        \"componentType\": {\n          \"@id\": \"schema:additionalType\"\n        },\n        \"packageVersion\": {\n          \"@id\": \"schema:version\"\n        },\n     \
  \   \"deployedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"active\": {\n          \"@id\": \"boomi:active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"notes\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    },\n\n    \"ExecutionRecord\": {\n      \"@id\": \"boomi:ExecutionRecord\",\n      \"@context\": {\n        \"executionId\": \"@id\",\n        \"processId\": {\n          \"@id\": \"boomi:executedProcess\",\n          \"@type\": \"@id\"\n        },\n        \"atomId\": {\n          \"@id\": \"boomi:ranOnAtom\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"boomi:executionStatus\"\n        },\n        \"executionTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n       \
  \ \"message\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    },\n\n    \"AIAgent\": {\n      \"@id\": \"boomi:AIAgent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"accountId\": {\n          \"@id\": \"boomi:accountId\"\n        },\n        \"providerType\": {\n          \"@id\": \"boomi:providerType\"\n        },\n        \"state\": {\n          \"@id\": \"boomi:state\"\n        },\n        \"tools\": {\n          \"@id\": \"boomi:hasTool\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"guardrails\": {\n          \"@id\": \"boomi:hasGuardrail\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AgentTool\": {\n      \"@id\": \"boomi:AgentTool\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\"\n        },\n        \"endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Repository\": {\n      \"@id\": \"boomi:DataHubRepository\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n  \
  \  \"GoldenRecord\": {\n      \"@id\": \"boomi:GoldenRecord\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"fields\": {\n          \"@id\": \"boomi:recordFields\"\n        },\n        \"sources\": {\n          \"@id\": \"boomi:hasSourceRecord\",\n          \"@container\": \"@set\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EventMessage\": {\n      \"@id\": \"boomi:EventMessage\",\n      \"@context\": {\n        \"messageId\": \"@id\",\n        \"payload\": {\n          \"@id\": \"schema:encodingFormat\"\n        },\n        \"properties\": {\n          \"@id\": \"boomi:messageProperties\"\n        },\n        \"topicId\": {\n          \"@id\": \"boomi:publishedToTopic\",\n          \"@type\": \"@id\"\n        },\n        \"timestamp\": {\n\
  \          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Connector\": {\n      \"@id\": \"boomi:Connector\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"version\": {\n          \"@id\": \"schema:version\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/boomi/refs/heads/main/json-ld/boomi-context.jsonld
tags:
- AI Agents
- Automation
- B2B
- Data Integration
- EDI
- Integrations
- Management
- MFT
- Platform
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
