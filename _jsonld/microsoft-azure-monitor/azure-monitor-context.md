---
api_specs:
- filename: metrics_API.json
  format: json
  label: Azure Monitor Metrics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metrics_API.json
- filename: metricDefinitions_API.json
  format: json
  label: Azure Monitor Metric Definitions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metricDefinitions_API.json
- filename: azure-monitor-metrics-batch-openapi.yml
  format: yaml
  label: Azure Monitor Metrics Batch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/openapi/azure-monitor-metrics-batch-openapi.yml
- filename: OperationalInsights.json
  format: json
  label: Azure Monitor Logs API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/operationalinsights/data-plane/Microsoft.OperationalInsights/stable/2022-10-27/OperationalInsights.json
- filename: azure-monitor-logs-ingestion-openapi.yml
  format: yaml
  label: Azure Monitor Logs Ingestion API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/openapi/azure-monitor-logs-ingestion-openapi.yml
- filename: alertRules_API.json
  format: json
  label: Azure Monitor Alerts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- filename: scheduledQueryRule_API.json
  format: json
  label: Azure Monitor Scheduled Query Rules API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-08-01/scheduledQueryRule_API.json
- filename: actionGroups_API.json
  format: json
  label: Azure Monitor Action Groups API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-06-01/actionGroups_API.json
- filename: autoscale_API.json
  format: json
  label: Azure Monitor Autoscale API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoscale_API.json
- filename: AppInsights.json
  format: json
  label: Azure Application Insights API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/applicationinsights/data-plane/Microsoft.Insights/stable/v1/AppInsights.json
- filename: diagnosticsSettings_API.json
  format: json
  label: Azure Monitor Diagnostic Settings API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-05-01-preview/diagnosticsSettings_API.json
- filename: activityLogs_API.json
  format: json
  label: Azure Monitor Activity Log API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- filename: dataCollectionRules_API.json
  format: json
  label: Azure Monitor Data Collection Rules API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionRules_API.json
- filename: dataCollectionEndpoints_API.json
  format: json
  label: Azure Monitor Data Collection Endpoints API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionEndpoints_API.json
- filename: azure-monitor-private-link-scopes-openapi.yml
  format: yaml
  label: Azure Monitor Private Link Scopes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/openapi/azure-monitor-private-link-scopes-openapi.yml
class_count: 0
classes: []
context_file: json-ld/azure-monitor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/json-ld/azure-monitor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Monitor from Azure Monitor.
layout: jsonld
name: Azure Monitor Context
namespaces:
- prefix: azure
  uri: https://schema.azure.com/monitor/
- prefix: monitoring
  uri: https://www.w3.org/ns/ssn/
- prefix: sosa
  uri: https://www.w3.org/ns/sosa/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Metric
  type: ''
- container: ''
  name: MetricDefinition
  type: ''
- container: ''
  name: AlertRule
  type: ''
- container: ''
  name: ScheduledQueryRule
  type: ''
- container: ''
  name: ActionGroup
  type: ''
- container: ''
  name: AutoscaleSetting
  type: ''
- container: ''
  name: LogQuery
  type: ''
- container: ''
  name: DiagnosticSetting
  type: ''
- container: ''
  name: ActivityLogEvent
  type: ''
- container: ''
  name: DataCollectionRule
  type: ''
- container: ''
  name: DataCollectionEndpoint
  type: ''
- container: ''
  name: PrivateLinkScope
  type: ''
- container: ''
  name: ApplicationInsightsEvent
  type: ''
property_count: 13
provider_name: Azure Monitor
provider_slug: microsoft-azure-monitor
slug: azure-monitor-context
source_filename: azure-monitor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"azure\": \"https://schema.azure.com/monitor/\",\n    \"monitoring\": \"https://www.w3.org/ns/ssn/\",\n    \"sosa\": \"https://www.w3.org/ns/sosa/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Metric\": {\n      \"@id\": \"azure:Metric\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": \"@type\",\n        \"name\": \"schema:name\",\n        \"displayDescription\": \"schema:description\",\n        \"unit\": {\n          \"@id\": \"sosa:hasUnit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timeseries\": {\n          \"@id\": \"azure:timeseries\",\n          \"@container\": \"@list\"\n        },\n        \"timeStamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"average\": {\n         \
  \ \"@id\": \"azure:averageValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"minimum\": {\n          \"@id\": \"schema:minValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"maximum\": {\n          \"@id\": \"schema:maxValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"total\": {\n          \"@id\": \"azure:totalValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"count\": {\n          \"@id\": \"azure:sampleCount\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"MetricDefinition\": {\n      \"@id\": \"azure:MetricDefinition\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"displayDescription\": \"schema:description\",\n        \"namespace\": \"azure:metricNamespace\",\n        \"category\": \"schema:category\",\n        \"metricClass\": \"azure:metricClass\",\n        \"unit\": {\n          \"@id\": \"sosa:hasUnit\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"primaryAggregationType\": \"azure:primaryAggregationType\",\n        \"supportedAggregationTypes\": {\n          \"@id\": \"azure:supportedAggregationTypes\",\n          \"@container\": \"@set\"\n        },\n        \"metricAvailabilities\": {\n          \"@id\": \"azure:metricAvailabilities\",\n          \"@container\": \"@list\"\n        },\n        \"dimensions\": {\n          \"@id\": \"azure:dimensions\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"AlertRule\": {\n      \"@id\": \"azure:AlertRule\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"isEnabled\": {\n          \"@id\": \"azure:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"condition\": \"azure:ruleCondition\",\n        \"actions\": {\n          \"@id\": \"schema:potentialAction\",\n          \"@container\": \"@list\"\n        },\n\
  \        \"lastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"location\": \"schema:location\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"ScheduledQueryRule\": {\n      \"@id\": \"azure:ScheduledQueryRule\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"displayName\": \"schema:alternateName\",\n        \"enabled\": {\n          \"@id\": \"azure:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"severity\": {\n          \"@id\": \"azure:severity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"evaluationFrequency\": {\n          \"@id\": \"azure:evaluationFrequency\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"windowSize\": {\n          \"@id\": \"azure:windowSize\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"scopes\"\
  : {\n          \"@id\": \"azure:scopes\",\n          \"@container\": \"@set\"\n        },\n        \"criteria\": \"azure:scheduledQueryRuleCriteria\",\n        \"actions\": {\n          \"@id\": \"schema:potentialAction\",\n          \"@container\": \"@list\"\n        },\n        \"location\": \"schema:location\"\n      }\n    },\n\n    \"ActionGroup\": {\n      \"@id\": \"azure:ActionGroup\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"groupShortName\": \"schema:alternateName\",\n        \"enabled\": {\n          \"@id\": \"azure:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"emailReceivers\": {\n          \"@id\": \"azure:emailReceivers\",\n          \"@container\": \"@list\"\n        },\n        \"smsReceivers\": {\n          \"@id\": \"azure:smsReceivers\",\n          \"@container\": \"@list\"\n        },\n        \"webhookReceivers\": {\n          \"@id\": \"azure:webhookReceivers\",\n          \"@container\"\
  : \"@list\"\n        },\n        \"location\": \"schema:location\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"AutoscaleSetting\": {\n      \"@id\": \"azure:AutoscaleSetting\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"enabled\": {\n          \"@id\": \"azure:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"targetResourceUri\": {\n          \"@id\": \"azure:targetResource\",\n          \"@type\": \"@id\"\n        },\n        \"targetResourceLocation\": \"schema:location\",\n        \"profiles\": {\n          \"@id\": \"azure:autoscaleProfiles\",\n          \"@container\": \"@list\"\n        },\n        \"notifications\": {\n          \"@id\": \"azure:notifications\",\n          \"@container\": \"@list\"\n        },\n        \"location\": \"schema:location\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"LogQuery\": {\n      \"@id\": \"azure:LogQuery\",\n      \"@context\"\
  : {\n        \"query\": {\n          \"@id\": \"azure:kqlQuery\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timespan\": {\n          \"@id\": \"azure:queryTimespan\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"workspaces\": {\n          \"@id\": \"azure:targetWorkspaces\",\n          \"@container\": \"@set\"\n        },\n        \"tables\": {\n          \"@id\": \"azure:resultTables\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"DiagnosticSetting\": {\n      \"@id\": \"azure:DiagnosticSetting\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"storageAccountId\": {\n          \"@id\": \"azure:storageDestination\",\n          \"@type\": \"@id\"\n        },\n        \"workspaceId\": {\n          \"@id\": \"azure:logAnalyticsDestination\",\n          \"@type\": \"@id\"\n        },\n        \"eventHubAuthorizationRuleId\": {\n          \"@id\": \"azure:eventHubDestination\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"eventHubName\": \"azure:eventHubName\",\n        \"metrics\": {\n          \"@id\": \"azure:metricSettings\",\n          \"@container\": \"@list\"\n        },\n        \"logs\": {\n          \"@id\": \"azure:logSettings\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ActivityLogEvent\": {\n      \"@id\": \"azure:ActivityLogEvent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"caller\": \"schema:agent\",\n        \"description\": \"schema:description\",\n        \"eventTimestamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"level\": \"azure:eventLevel\",\n        \"operationName\": \"schema:name\",\n        \"resourceId\": {\n          \"@id\": \"azure:resourceId\",\n          \"@type\": \"@id\"\n        },\n        \"resourceGroupName\": \"azure:resourceGroup\",\n        \"status\": \"azure:operationStatus\",\n        \"subscriptionId\"\
  : \"azure:subscriptionId\",\n        \"correlationId\": \"azure:correlationId\"\n      }\n    },\n\n    \"DataCollectionRule\": {\n      \"@id\": \"azure:DataCollectionRule\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"dataCollectionEndpointId\": {\n          \"@id\": \"azure:dataCollectionEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"dataSources\": \"azure:dataSources\",\n        \"destinations\": \"azure:destinations\",\n        \"dataFlows\": {\n          \"@id\": \"azure:dataFlows\",\n          \"@container\": \"@list\"\n        },\n        \"location\": \"schema:location\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"DataCollectionEndpoint\": {\n      \"@id\": \"azure:DataCollectionEndpoint\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"configurationAccess\"\
  : \"azure:configurationAccessEndpoint\",\n        \"logsIngestion\": \"azure:logsIngestionEndpoint\",\n        \"metricsIngestion\": \"azure:metricsIngestionEndpoint\",\n        \"networkAcls\": \"azure:networkAccessControl\",\n        \"location\": \"schema:location\"\n      }\n    },\n\n    \"PrivateLinkScope\": {\n      \"@id\": \"azure:PrivateLinkScope\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"accessModeSettings\": \"azure:accessModeSettings\",\n        \"privateEndpointConnections\": {\n          \"@id\": \"azure:privateEndpointConnections\",\n          \"@container\": \"@list\"\n        },\n        \"location\": \"schema:location\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"ApplicationInsightsEvent\": {\n      \"@id\": \"azure:ApplicationInsightsEvent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": \"@type\",\n        \"timestamp\": {\n          \"@id\": \"schema:dateCreated\",\n\
  \          \"@type\": \"xsd:dateTime\"\n        },\n        \"customDimensions\": \"azure:customDimensions\",\n        \"customMeasurements\": \"azure:customMeasurements\",\n        \"operation\": \"azure:operation\",\n        \"session\": \"azure:session\",\n        \"user\": \"schema:agent\",\n        \"cloud\": \"azure:cloudContext\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/json-ld/azure-monitor-context.jsonld
tags:
- Application Insights
- Cloud
- Logs
- Metrics
- Monitoring
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
