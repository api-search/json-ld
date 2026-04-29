---
api_specs:
- filename: new-relic-openapi.yml
  format: yaml
  label: New Relic REST API v2
  slug: new-relic-rest-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-openapi.yml
- filename: new-relic-metric-api-openapi.yml
  format: yaml
  label: New Relic Metric API
  slug: new-relic-metric-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-metric-api-openapi.yml
- filename: new-relic-event-api-openapi.yml
  format: yaml
  label: New Relic Event API
  slug: new-relic-event-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-event-api-openapi.yml
- filename: new-relic-log-api-openapi.yml
  format: yaml
  label: New Relic Log API
  slug: new-relic-log-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-log-api-openapi.yml
- filename: new-relic-trace-api-openapi.yml
  format: yaml
  label: New Relic Trace API
  slug: new-relic-trace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-trace-api-openapi.yml
class_count: 90
classes:
- AppSettingsBody
- AppSettingsResponse
- AppSummaryDataResponse
- AppSummaryResponse
- Application
- ApplicationBody
- name
- ApplicationHostLinksResponse
- ApplicationHostResponse
- ApplicationHostResponseType
- ApplicationInstanceLinksResponse
- ApplicationInstanceResponse
- ApplicationInstanceResponseType
- ApplicationLinksResponse
- ApplicationResponse
- ApplicationResponseType
- BrowserApplication
- BrowserApplicationBody
- BrowserApplicationResponse
- BrowserApplicationResponseType
- Channel
- ChannelBody
- ChannelLinksResponse
- ChannelResponse
- ChannelResponseType
- Condition
- ConditionBody
- ConditionResponse
- ConditionResponseType
- CrashSummaryResponse
- Deployment
- DeploymentBody
- description
- DeploymentLinksResponse
- DeploymentResponse
- DeploymentResponseType
- EndUserSummaryDataResponse
- EndUserSummaryResponse
- ExternalServiceCondition
- ExternalServiceConditionBody
- ExternalServiceConditionResponse
- ExternalServiceConditionResponseType
- IJKTermsType
- IncidentLinksResponse
- IncidentResponse
- IncidentResponseType
- KeyTransactionLinksResponse
- KeyTransactionResponse
- KeyTransactionResponseType
- Label
- LabelBody
- LabelLinksBody
- LabelLinksResponse
- LabelOriginsResponse
- LabelResponse
- LabelResponseType
- MetricDataResponse
- MetricDataResponseType
- MetricListResponse
- MetricParserResponse
- MetricParserResponseType
- MetricResponse
- MobileApplicationResponse
- MobileApplicationResponseType
- MobileSummaryDataResponse
- NrqlBody
- NrqlCondition
- NrqlConditionBody
- NrqlConditionResponse
- NrqlConditionResponseType
- NrqlResponse
- Policy
- PolicyBody
- PolicyChannelsResponse
- PolicyChannelsResponseType
- PolicyResponse
- PolicyResponseType
- RecentEventResponse
- RecentEventResponseType
- SyntheticsCondition
- SyntheticsConditionBody
- SyntheticsConditionResponse
- SyntheticsConditionResponseType
- TimesliceResponse
- UserDefinedConditionBody
- UserDefinedConditionResponse
- ViolationEntityResponse
- ViolationLinksResponse
- ViolationResponse
- ViolationResponseType
context_file: json-ld/new-relic-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Openapi from New Relic.
layout: jsonld
name: New Relic Openapi Context
namespaces:
- prefix: nr
  uri: https://docs.newrelic.com/docs/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: appApdexThreshold
  type: decimal
- container: ''
  name: enableRealUserMonitoring
  type: boolean
- container: ''
  name: endUserApdexThreshold
  type: decimal
- container: ''
  name: useServerSideConfig
  type: boolean
- container: ''
  name: apdexScore
  type: decimal
- container: ''
  name: errorRate
  type: decimal
- container: ''
  name: instanceCount
  type: integer
- container: ''
  name: responseTime
  type: decimal
- container: ''
  name: throughput
  type: decimal
- container: ''
  name: apdexTarget
  type: decimal
- container: ''
  name: concurrentInstanceCount
  type: integer
- container: ''
  name: hostCount
  type: integer
- container: ''
  name: application
  type: string
- container: ''
  name: settings
  type: string
- container: set
  name: applicationInstances
  type: string
- container: ''
  name: server
  type: integer
- container: set
  name: applicationHosts
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: applicationName
  type: string
- container: ''
  name: applicationSummary
  type: string
- container: ''
  name: endUserSummary
  type: string
- container: ''
  name: healthStatus
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: language
  type: integer
- container: ''
  name: links
  type: string
- container: ''
  name: applicationHost
  type: integer
- container: ''
  name: applicationInstance
  type: string
- container: ''
  name: port
  type: integer
- container: set
  name: servers
  type: string
- container: ''
  name: lastReportedAt
  type: string
- container: ''
  name: reporting
  type: boolean
- container: ''
  name: browserApplication
  type: string
- container: ''
  name: browserMonitoringKey
  type: string
- container: ''
  name: loaderScript
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: configuration
  type: reference
- container: ''
  name: type
  type: string
- container: set
  name: policyIds
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: conditionScope
  type: string
- container: ''
  name: enabled
  type: boolean
- container: set
  name: entities
  type: string
- container: ''
  name: gcMetric
  type: string
- container: ''
  name: metric
  type: string
- container: set
  name: terms
  type: string
- container: ''
  name: userDefined
  type: string
- container: ''
  name: violationCloseTimer
  type: integer
- container: ''
  name: runbookUrl
  type: string
- container: ''
  name: crashCount
  type: integer
- container: ''
  name: crashRate
  type: decimal
- container: ''
  name: supportsCrashData
  type: boolean
- container: ''
  name: unresolvedCrashCount
  type: integer
- container: ''
  name: deployment
  type: string
- container: ''
  name: changelog
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: externalServiceCondition
  type: string
- container: ''
  name: externalServiceUrl
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: threshold
  type: string
- container: ''
  name: timeFunction
  type: string
- container: ''
  name: policyId
  type: integer
- container: set
  name: violations
  type: string
- container: ''
  name: incident
  type: string
- container: ''
  name: closedAt
  type: integer
- container: ''
  name: incidentPreference
  type: integer
- container: ''
  name: openedAt
  type: integer
- container: ''
  name: keyTransaction
  type: string
- container: ''
  name: transactionName
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: applications
  type: string
- container: set
  name: agents
  type: string
- container: set
  name: apm
  type: string
- container: set
  name: synthetics
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: origins
  type: string
- container: ''
  name: metricData
  type: string
- container: ''
  name: from
  type: string
- container: set
  name: metrics
  type: string
- container: ''
  name: metricsFound
  type: string
- container: ''
  name: metricsNotFound
  type: string
- container: ''
  name: to
  type: string
- container: set
  name: values
  type: string
- container: set
  name: timeslices
  type: string
- container: ''
  name: crashSummary
  type: string
- container: ''
  name: mobileSummary
  type: string
- container: ''
  name: activeUsers
  type: integer
- container: ''
  name: callsPerSession
  type: decimal
- container: ''
  name: failedCallRate
  type: decimal
- container: ''
  name: interactionTime
  type: decimal
- container: ''
  name: launchCount
  type: integer
- container: ''
  name: remoteErrorRate
  type: decimal
- container: ''
  name: query
  type: string
- container: ''
  name: sinceValue
  type: string
- container: ''
  name: nrqlCondition
  type: string
- container: ''
  name: expectedGroups
  type: integer
- container: ''
  name: ignoreOverlap
  type: boolean
- container: ''
  name: nrql
  type: string
- container: ''
  name: valueFunction
  type: string
- container: ''
  name: policy
  type: string
- container: set
  name: channelIds
  type: string
- container: ''
  name: createdAt
  type: integer
- container: ''
  name: updatedAt
  type: integer
- container: ''
  name: recentEvent
  type: string
- container: ''
  name: entityGroupId
  type: integer
- container: ''
  name: entityId
  type: integer
- container: ''
  name: entityType
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: incidentId
  type: integer
- container: ''
  name: product
  type: string
- container: ''
  name: syntheticsCondition
  type: string
- container: ''
  name: monitorId
  type: string
- container: ''
  name: groupId
  type: integer
- container: ''
  name: conditionId
  type: integer
- container: ''
  name: violation
  type: string
- container: ''
  name: conditionName
  type: string
- container: ''
  name: entity
  type: string
- container: ''
  name: policyName
  type: string
property_count: 122
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-openapi-context
source_filename: new-relic-openapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nr\": \"https://docs.newrelic.com/docs/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AppSettingsBody\": \"nr:AppSettingsBody\",\n    \"appApdexThreshold\": {\n      \"@id\": \"nr:app_apdex_threshold\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"enableRealUserMonitoring\": {\n      \"@id\": \"nr:enable_real_user_monitoring\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endUserApdexThreshold\": {\n      \"@id\": \"nr:end_user_apdex_threshold\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"AppSettingsResponse\": \"nr:AppSettingsResponse\",\n    \"useServerSideConfig\": {\n      \"@id\": \"nr:use_server_side_config\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AppSummaryDataResponse\": \"nr:AppSummaryDataResponse\",\n    \"apdexScore\": {\n      \"@id\": \"nr:apdex_score\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"errorRate\": {\n      \"@id\": \"nr:error_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"instanceCount\": {\n      \"@id\": \"nr:instance_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"responseTime\": {\n      \"@id\": \"nr:response_time\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"throughput\": {\n      \"@id\": \"nr:throughput\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"AppSummaryResponse\": \"nr:AppSummaryResponse\",\n    \"apdexTarget\": {\n      \"@id\": \"nr:apdex_target\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"concurrentInstanceCount\": {\n      \"@id\": \"nr:concurrent_instance_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostCount\": {\n      \"@id\": \"nr:host_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Application\": \"nr:Application\",\n    \"application\": {\n      \"@id\": \"nr:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationBody\": \"nr:ApplicationBody\"\
  ,\n    \"name\": \"schema:name\",\n    \"settings\": {\n      \"@id\": \"nr:settings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationHostLinksResponse\": \"nr:ApplicationHostLinksResponse\",\n    \"applicationInstances\": {\n      \"@id\": \"nr:application_instances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"server\": {\n      \"@id\": \"nr:server\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ApplicationHostResponse\": \"nr:ApplicationHostResponse\",\n    \"applicationHosts\": {\n      \"@id\": \"nr:application_hosts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationHostResponseType\": \"nr:ApplicationHostResponseType\",\n    \"host\": {\n      \"@id\": \"nr:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationName\": {\n      \"@id\": \"nr:application_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationSummary\": {\n      \"@id\": \"nr:application_summary\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"endUserSummary\": {\n      \"@id\": \"nr:end_user_summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthStatus\": {\n      \"@id\": \"nr:health_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"nr:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"language\": {\n      \"@id\": \"nr:language\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"nr:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationInstanceLinksResponse\": \"nr:ApplicationInstanceLinksResponse\",\n    \"applicationHost\": {\n      \"@id\": \"nr:application_host\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ApplicationInstanceResponse\": \"nr:ApplicationInstanceResponse\",\n    \"applicationInstance\": {\n      \"@id\": \"nr:application_instance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationInstanceResponseType\": \"nr:ApplicationInstanceResponseType\",\n    \"\
  port\": {\n      \"@id\": \"nr:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ApplicationLinksResponse\": \"nr:ApplicationLinksResponse\",\n    \"servers\": {\n      \"@id\": \"nr:servers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationResponse\": \"nr:ApplicationResponse\",\n    \"ApplicationResponseType\": \"nr:ApplicationResponseType\",\n    \"lastReportedAt\": {\n      \"@id\": \"nr:last_reported_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reporting\": {\n      \"@id\": \"nr:reporting\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"BrowserApplication\": \"nr:BrowserApplication\",\n    \"browserApplication\": {\n      \"@id\": \"nr:browser_application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BrowserApplicationBody\": \"nr:BrowserApplicationBody\",\n    \"BrowserApplicationResponse\": \"nr:BrowserApplicationResponse\",\n    \"BrowserApplicationResponseType\": \"nr:BrowserApplicationResponseType\",\n    \"\
  browserMonitoringKey\": {\n      \"@id\": \"nr:browser_monitoring_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loaderScript\": {\n      \"@id\": \"nr:loader_script\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Channel\": \"nr:Channel\",\n    \"channel\": {\n      \"@id\": \"nr:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelBody\": \"nr:ChannelBody\",\n    \"configuration\": {\n      \"@id\": \"nr:configuration\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"nr:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelLinksResponse\": \"nr:ChannelLinksResponse\",\n    \"policyIds\": {\n      \"@id\": \"nr:policy_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelResponse\": \"nr:ChannelResponse\",\n    \"ChannelResponseType\": \"nr:ChannelResponseType\",\n    \"Condition\": \"nr:Condition\",\n    \"condition\": {\n      \"@id\": \"nr:condition\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"ConditionBody\": \"nr:ConditionBody\",\n    \"conditionScope\": {\n      \"@id\": \"nr:condition_scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"nr:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"entities\": {\n      \"@id\": \"nr:entities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gcMetric\": {\n      \"@id\": \"nr:gc_metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"nr:metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terms\": {\n      \"@id\": \"nr:terms\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userDefined\": {\n      \"@id\": \"nr:user_defined\",\n      \"@type\": \"xsd:string\"\n    },\n    \"violationCloseTimer\": {\n      \"@id\": \"nr:violation_close_timer\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ConditionResponse\": \"nr:ConditionResponse\",\n    \"ConditionResponseType\"\
  : \"nr:ConditionResponseType\",\n    \"runbookUrl\": {\n      \"@id\": \"nr:runbook_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CrashSummaryResponse\": \"nr:CrashSummaryResponse\",\n    \"crashCount\": {\n      \"@id\": \"nr:crash_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"crashRate\": {\n      \"@id\": \"nr:crash_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"supportsCrashData\": {\n      \"@id\": \"nr:supports_crash_data\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"unresolvedCrashCount\": {\n      \"@id\": \"nr:unresolved_crash_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Deployment\": \"nr:Deployment\",\n    \"deployment\": {\n      \"@id\": \"nr:deployment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeploymentBody\": \"nr:DeploymentBody\",\n    \"changelog\": {\n      \"@id\": \"nr:changelog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"revision\": {\n      \"@id\": \"\
  nr:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"nr:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeploymentLinksResponse\": \"nr:DeploymentLinksResponse\",\n    \"DeploymentResponse\": \"nr:DeploymentResponse\",\n    \"DeploymentResponseType\": \"nr:DeploymentResponseType\",\n    \"timestamp\": {\n      \"@id\": \"nr:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndUserSummaryDataResponse\": \"nr:EndUserSummaryDataResponse\",\n    \"EndUserSummaryResponse\": \"nr:EndUserSummaryResponse\",\n    \"ExternalServiceCondition\": \"nr:ExternalServiceCondition\",\n    \"externalServiceCondition\": {\n      \"@id\": \"nr:external_service_condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalServiceConditionBody\": \"nr:ExternalServiceConditionBody\",\n    \"externalServiceUrl\": {\n      \"@id\": \"nr:external_service_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalServiceConditionResponse\": \"nr:ExternalServiceConditionResponse\"\
  ,\n    \"ExternalServiceConditionResponseType\": \"nr:ExternalServiceConditionResponseType\",\n    \"IJKTermsType\": \"nr:IJKTermsType\",\n    \"duration\": {\n      \"@id\": \"nr:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"nr:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"nr:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threshold\": {\n      \"@id\": \"nr:threshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeFunction\": {\n      \"@id\": \"nr:time_function\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IncidentLinksResponse\": \"nr:IncidentLinksResponse\",\n    \"policyId\": {\n      \"@id\": \"nr:policy_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"violations\": {\n      \"@id\": \"nr:violations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IncidentResponse\": \"nr:IncidentResponse\",\n    \"incident\": {\n      \"@id\"\
  : \"nr:incident\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IncidentResponseType\": \"nr:IncidentResponseType\",\n    \"closedAt\": {\n      \"@id\": \"nr:closed_at\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"incidentPreference\": {\n      \"@id\": \"nr:incident_preference\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"openedAt\": {\n      \"@id\": \"nr:opened_at\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"KeyTransactionLinksResponse\": \"nr:KeyTransactionLinksResponse\",\n    \"KeyTransactionResponse\": \"nr:KeyTransactionResponse\",\n    \"keyTransaction\": {\n      \"@id\": \"nr:key_transaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyTransactionResponseType\": \"nr:KeyTransactionResponseType\",\n    \"transactionName\": {\n      \"@id\": \"nr:transaction_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Label\": \"nr:Label\",\n    \"label\": {\n      \"@id\": \"nr:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LabelBody\": \"\
  nr:LabelBody\",\n    \"category\": {\n      \"@id\": \"nr:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LabelLinksBody\": \"nr:LabelLinksBody\",\n    \"applications\": {\n      \"@id\": \"nr:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LabelLinksResponse\": \"nr:LabelLinksResponse\",\n    \"LabelOriginsResponse\": \"nr:LabelOriginsResponse\",\n    \"agents\": {\n      \"@id\": \"nr:agents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apm\": {\n      \"@id\": \"nr:apm\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"synthetics\": {\n      \"@id\": \"nr:synthetics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LabelResponse\": \"nr:LabelResponse\",\n    \"LabelResponseType\": \"nr:LabelResponseType\",\n    \"key\": {\n      \"@id\": \"nr:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origins\": {\n      \"\
  @id\": \"nr:origins\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricDataResponse\": \"nr:MetricDataResponse\",\n    \"metricData\": {\n      \"@id\": \"nr:metric_data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricDataResponseType\": \"nr:MetricDataResponseType\",\n    \"from\": {\n      \"@id\": \"nr:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"nr:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricsFound\": {\n      \"@id\": \"nr:metrics_found\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricsNotFound\": {\n      \"@id\": \"nr:metrics_not_found\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"nr:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricListResponse\": \"nr:MetricListResponse\",\n    \"MetricParserResponse\": \"nr:MetricParserResponse\",\n    \"MetricParserResponseType\": \"nr:MetricParserResponseType\",\n    \"values\": {\n\
  \      \"@id\": \"nr:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricResponse\": \"nr:MetricResponse\",\n    \"timeslices\": {\n      \"@id\": \"nr:timeslices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MobileApplicationResponse\": \"nr:MobileApplicationResponse\",\n    \"MobileApplicationResponseType\": \"nr:MobileApplicationResponseType\",\n    \"crashSummary\": {\n      \"@id\": \"nr:crash_summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mobileSummary\": {\n      \"@id\": \"nr:mobile_summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MobileSummaryDataResponse\": \"nr:MobileSummaryDataResponse\",\n    \"activeUsers\": {\n      \"@id\": \"nr:active_users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"callsPerSession\": {\n      \"@id\": \"nr:calls_per_session\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"failedCallRate\": {\n      \"@id\": \"nr:failed_call_rate\",\n  \
  \    \"@type\": \"xsd:decimal\"\n    },\n    \"interactionTime\": {\n      \"@id\": \"nr:interaction_time\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"launchCount\": {\n      \"@id\": \"nr:launch_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remoteErrorRate\": {\n      \"@id\": \"nr:remote_error_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"NrqlBody\": \"nr:NrqlBody\",\n    \"query\": {\n      \"@id\": \"nr:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sinceValue\": {\n      \"@id\": \"nr:since_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NrqlCondition\": \"nr:NrqlCondition\",\n    \"nrqlCondition\": {\n      \"@id\": \"nr:nrql_condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NrqlConditionBody\": \"nr:NrqlConditionBody\",\n    \"expectedGroups\": {\n      \"@id\": \"nr:expected_groups\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ignoreOverlap\": {\n      \"@id\": \"nr:ignore_overlap\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"nrql\": {\n      \"@id\": \"nr:nrql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueFunction\": {\n      \"@id\": \"nr:value_function\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NrqlConditionResponse\": \"nr:NrqlConditionResponse\",\n    \"NrqlConditionResponseType\": \"nr:NrqlConditionResponseType\",\n    \"NrqlResponse\": \"nr:NrqlResponse\",\n    \"Policy\": \"nr:Policy\",\n    \"policy\": {\n      \"@id\": \"nr:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyBody\": \"nr:PolicyBody\",\n    \"PolicyChannelsResponse\": \"nr:PolicyChannelsResponse\",\n    \"PolicyChannelsResponseType\": \"nr:PolicyChannelsResponseType\",\n    \"channelIds\": {\n      \"@id\": \"nr:channel_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyResponse\": \"nr:PolicyResponse\",\n    \"PolicyResponseType\": \"nr:PolicyResponseType\",\n    \"createdAt\": {\n      \"@id\": \"nr:created_at\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"updatedAt\": {\n      \"@id\": \"nr:updated_at\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RecentEventResponse\": \"nr:RecentEventResponse\",\n    \"recentEvent\": {\n      \"@id\": \"nr:recent_event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecentEventResponseType\": \"nr:RecentEventResponseType\",\n    \"entityGroupId\": {\n      \"@id\": \"nr:entity_group_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entityId\": {\n      \"@id\": \"nr:entity_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entityType\": {\n      \"@id\": \"nr:entity_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"nr:event_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentId\": {\n      \"@id\": \"nr:incident_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"product\": {\n      \"@id\": \"nr:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SyntheticsCondition\": \"nr:SyntheticsCondition\",\n    \"syntheticsCondition\"\
  : {\n      \"@id\": \"nr:synthetics_condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SyntheticsConditionBody\": \"nr:SyntheticsConditionBody\",\n    \"monitorId\": {\n      \"@id\": \"nr:monitor_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SyntheticsConditionResponse\": \"nr:SyntheticsConditionResponse\",\n    \"SyntheticsConditionResponseType\": \"nr:SyntheticsConditionResponseType\",\n    \"TimesliceResponse\": \"nr:TimesliceResponse\",\n    \"UserDefinedConditionBody\": \"nr:UserDefinedConditionBody\",\n    \"UserDefinedConditionResponse\": \"nr:UserDefinedConditionResponse\",\n    \"ViolationEntityResponse\": \"nr:ViolationEntityResponse\",\n    \"groupId\": {\n      \"@id\": \"nr:group_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ViolationLinksResponse\": \"nr:ViolationLinksResponse\",\n    \"conditionId\": {\n      \"@id\": \"nr:condition_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ViolationResponse\": \"nr:ViolationResponse\",\n    \"violation\"\
  : {\n      \"@id\": \"nr:violation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ViolationResponseType\": \"nr:ViolationResponseType\",\n    \"conditionName\": {\n      \"@id\": \"nr:condition_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entity\": {\n      \"@id\": \"nr:entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n      \"@id\": \"nr:policy_name\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-openapi-context.jsonld
tags:
- Analysis
- Analytics
- APM
- DevOps
- Infrastructure
- Monitoring
- Observability
- Performance
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
