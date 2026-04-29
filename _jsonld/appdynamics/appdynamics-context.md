---
api_specs:
- filename: appdynamics-controller-rest-api-openapi.yml
  format: yaml
  label: AppDynamics Controller REST API
  slug: controller-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-controller-rest-api-openapi.yml
- filename: appdynamics-metric-and-snapshot-api-openapi.yml
  format: yaml
  label: AppDynamics Metric and Snapshot API
  slug: metric-and-snapshot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-metric-and-snapshot-api-openapi.yml
- filename: appdynamics-alert-and-respond-api-openapi.yml
  format: yaml
  label: AppDynamics Alert and Respond API
  slug: alert-and-respond-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-alert-and-respond-api-openapi.yml
- filename: appdynamics-configuration-api-openapi.yml
  format: yaml
  label: AppDynamics Configuration API
  slug: configuration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-configuration-api-openapi.yml
- filename: appdynamics-analytics-events-api-openapi.yml
  format: yaml
  label: AppDynamics Analytics Events API
  slug: analytics-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-analytics-events-api-openapi.yml
- filename: appdynamics-database-agent-api-openapi.yml
  format: yaml
  label: AppDynamics Database Agent API
  slug: database-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-database-agent-api-openapi.yml
- filename: appdynamics-machine-agent-api-openapi.yml
  format: yaml
  label: AppDynamics Machine Agent API
  slug: machine-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-machine-agent-api-openapi.yml
- filename: appdynamics-cloud-observability-api-openapi.yml
  format: yaml
  label: Cisco Cloud Observability API
  slug: cloud-observability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-cloud-observability-api-openapi.yml
- filename: appdynamics-authentication-api-openapi.yml
  format: yaml
  label: AppDynamics OAuth Authentication API
  slug: authentication-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-authentication-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/appdynamics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/json-ld/appdynamics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appdynamics from AppDynamics.
layout: jsonld
name: Appdynamics Context
namespaces:
- prefix: appd
  uri: https://appdynamics.com/ontology/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Application
  type: ''
- container: ''
  name: Tier
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: BusinessTransaction
  type: ''
- container: ''
  name: Backend
  type: ''
- container: ''
  name: HealthRule
  type: ''
- container: ''
  name: MetricData
  type: ''
- container: ''
  name: RequestSnapshot
  type: ''
- container: ''
  name: DatabaseCollector
  type: ''
- container: ''
  name: CloudConnection
  type: ''
- container: ''
  name: AnalyticsEvent
  type: ''
property_count: 11
provider_name: AppDynamics
provider_slug: appdynamics
slug: appdynamics-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"appd\": \"https://appdynamics.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Application\": {\n      \"@id\": \"appd:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"applicationId\": \"appd:applicationId\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Tier\": {\n      \"@id\": \"appd:Tier\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"tierId\": \"appd:tierId\",\n        \"agentType\": \"appd:agentType\",\n        \"numberOfNodes\": \"appd:numberOfNodes\",\n        \"application\": {\n          \"@id\": \"appd:belongsToApplication\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Node\": {\n     \
  \ \"@id\": \"appd:Node\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"nodeId\": \"appd:nodeId\",\n        \"tier\": {\n          \"@id\": \"appd:belongsToTier\",\n          \"@type\": \"@id\"\n        },\n        \"machineId\": \"appd:machineId\",\n        \"machineName\": \"appd:machineName\",\n        \"machineOSType\": \"schema:operatingSystem\",\n        \"agentType\": \"appd:agentType\",\n        \"appAgentVersion\": \"schema:softwareVersion\",\n        \"ipAddress\": \"appd:ipAddress\"\n      }\n    },\n\n    \"BusinessTransaction\": {\n      \"@id\": \"appd:BusinessTransaction\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"transactionId\": \"appd:transactionId\",\n        \"entryPointType\": \"appd:entryPointType\",\n        \"tier\": {\n          \"@id\": \"appd:detectedInTier\",\n          \"@type\": \"@id\"\n        },\n        \"isBackground\": \"appd:isBackground\"\n      }\n    },\n\n    \"Backend\": {\n      \"@id\": \"\
  appd:Backend\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"backendId\": \"appd:backendId\",\n        \"exitPointType\": \"appd:exitPointType\",\n        \"properties\": \"appd:connectionProperties\"\n      }\n    },\n\n    \"HealthRule\": {\n      \"@id\": \"appd:HealthRule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"healthRuleId\": \"appd:healthRuleId\",\n        \"enabled\": \"appd:enabled\",\n        \"affectedEntityType\": \"appd:affectedEntityType\",\n        \"evaluationMinutes\": \"appd:evaluationMinutes\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MetricData\": {\n      \"@id\": \"appd:MetricData\",\n      \"@context\": {\n        \"metricName\": \"schema:name\",\n        \"metricPath\": \"appd:metricPath\"\
  ,\n        \"metricId\": \"appd:metricId\",\n        \"frequency\": \"appd:frequency\",\n        \"values\": {\n          \"@id\": \"appd:metricValues\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RequestSnapshot\": {\n      \"@id\": \"appd:RequestSnapshot\",\n      \"@context\": {\n        \"snapshotId\": \"appd:snapshotId\",\n        \"requestGUID\": \"appd:requestGUID\",\n        \"summary\": \"schema:description\",\n        \"userExperience\": \"appd:userExperience\",\n        \"timeTakenInMilliSecs\": \"appd:timeTakenInMilliSecs\",\n        \"serverStartTime\": {\n          \"@id\": \"appd:serverStartTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"businessTransaction\": {\n          \"@id\": \"appd:belongsToTransaction\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"DatabaseCollector\": {\n      \"@id\": \"appd:DatabaseCollector\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"collectorId\": \"appd:collectorId\",\n        \"databaseType\": \"appd:databaseType\",\n        \"hostname\": \"appd:hostname\",\n        \"port\": \"appd:port\",\n        \"databaseName\": \"appd:databaseName\",\n        \"enabled\": \"appd:enabled\",\n        \"agentName\": \"appd:agentName\"\n      }\n    },\n\n    \"CloudConnection\": {\n      \"@id\": \"appd:CloudConnection\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"connectionId\": \"appd:connectionId\",\n        \"cloudProvider\": \"appd:cloudProvider\",\n        \"state\": \"appd:connectionState\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AnalyticsEvent\"\
  : {\n      \"@id\": \"appd:AnalyticsEvent\",\n      \"@context\": {\n        \"schemaName\": \"schema:name\",\n        \"eventTime\": {\n          \"@id\": \"appd:eventTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/json-ld/appdynamics-context.jsonld
tags:
- APM
- Application Performance Monitoring
- Cisco
- Cloud Observability
- DevOps
- Monitoring
- Observability
- OpenTelemetry
- JSON-LD
- Linked Data
- Semantic Web
---
