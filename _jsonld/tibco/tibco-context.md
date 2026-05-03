---
api_specs:
- filename: openapi.json
  format: json
  label: TIBCO Cloud Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://integration.cloud.tibco.com/docs/api/openapi.json
- filename: io-docs
  format: yaml
  label: TIBCO Mashery API Management
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mashery.com/io-docs
- filename: tibco-businessevents-openapi.yml
  format: yaml
  label: TIBCO BusinessEvents API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/openapi/tibco-businessevents-openapi.yml
- filename: tibco-messaging-asyncapi.yml
  format: yaml
  label: TIBCO Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/asyncapi/tibco-messaging-asyncapi.yml
- filename: tibco-spotfire-openapi.yml
  format: yaml
  label: TIBCO Spotfire Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/openapi/tibco-spotfire-openapi.yml
class_count: 0
classes: []
context_file: json-ld/tibco-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/json-ld/tibco-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tibco from TIBCO.
layout: jsonld
name: Tibco Context
namespaces:
- prefix: tibco
  uri: https://developer.tibco.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: IntegrationApp
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Flow
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: ApiService
  type: ''
- container: ''
  name: ApiEndpoint
  type: ''
- container: ''
  name: Package
  type: ''
- container: ''
  name: Plan
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: Analysis
  type: ''
- container: ''
  name: DataSource
  type: ''
property_count: 13
provider_name: TIBCO
provider_slug: tibco
slug: tibco-context
source_filename: tibco-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tibco\": \"https://developer.tibco.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"IntegrationApp\": {\n      \"@id\": \"tibco:IntegrationApp\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"tibco:appType\",\n        \"status\": \"tibco:appStatus\",\n        \"version\": \"schema:version\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": \"dcterms:creator\"\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"tibco:Connection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\"\
  : \"tibco:connectorType\",\n        \"status\": \"tibco:connectionStatus\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Flow\": {\n      \"@id\": \"tibco:Flow\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"tibco:flowTriggerType\"\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"tibco:Deployment\",\n      \"@context\": {\n        \"appName\": \"schema:name\",\n        \"status\": \"tibco:deploymentStatus\",\n        \"instanceCount\": {\n          \"@id\": \"tibco:instanceCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdTime\": {\n          \"\
  @id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiService\": {\n      \"@id\": \"tibco:ApiService\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"qpsLimitOverall\": {\n          \"@id\": \"tibco:qpsLimitOverall\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiEndpoint\": {\n      \"@id\": \"tibco:ApiEndpoint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"requestAuthenticationType\": \"tibco:authType\",\n        \"requestProtocol\": \"tibco:protocol\",\n        \"requestPathAlias\": \"tibco:pathAlias\",\n        \"trafficManagerDomain\"\
  : \"tibco:trafficDomain\"\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"tibco:Package\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Plan\": {\n      \"@id\": \"tibco:Plan\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"maxNumKeysAllowed\": {\n          \"@id\": \"tibco:maxKeys\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"qpsLimitCeiling\": {\n          \"@id\": \"tibco:qpsLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rateLimitCeiling\": {\n          \"@id\": \"tibco:rateLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rateLimitPeriod\"\
  : \"tibco:ratePeriod\",\n        \"status\": \"tibco:planStatus\"\n      }\n    },\n\n    \"Rule\": {\n      \"@id\": \"tibco:Rule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"priority\": {\n          \"@id\": \"tibco:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"condition\": \"tibco:ruleCondition\",\n        \"action\": \"tibco:ruleAction\",\n        \"enabled\": {\n          \"@id\": \"tibco:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"tibco:Event\",\n      \"@context\": {\n        \"type\": \"tibco:eventType\",\n        \"status\": \"tibco:eventStatus\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"tibco:Agent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\"\
  : \"tibco:agentStatus\",\n        \"type\": \"tibco:agentType\",\n        \"rulesLoaded\": {\n          \"@id\": \"tibco:rulesLoaded\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventsProcessed\": {\n          \"@id\": \"tibco:eventsProcessed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Analysis\": {\n      \"@id\": \"tibco:Analysis\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"path\": \"tibco:libraryPath\",\n        \"version\": \"schema:version\",\n        \"createdBy\": \"dcterms:creator\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n \
  \   },\n\n    \"DataSource\": {\n      \"@id\": \"tibco:DataSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"tibco:dataSourceType\",\n        \"provider\": \"tibco:provider\",\n        \"status\": \"tibco:connectionStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/json-ld/tibco-context.jsonld
tags:
- Analytics
- API Management
- Cloud
- Enterprise Software
- Integration
- Messaging
- Real-Time Data
- JSON-LD
- Linked Data
- Semantic Web
---
