---
api_specs:
- filename: amazon-cloudwatch-openapi.yml
  format: yaml
  label: Amazon CloudWatch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/openapi/amazon-cloudwatch-openapi.yml
class_count: 10
classes:
- GetMetricDataResponse
- GetMetricStatisticsResponse
- ListMetricsResponse
- DescribeAlarmsResponse
- PutDashboardResponse
- GetDashboardResponse
- ListDashboardsResponse
- Metric
- Alarm
- Dashboard
context_file: json-ld/amazon-cloudwatch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/json-ld/amazon-cloudwatch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloudwatch from Amazon CloudWatch.
layout: jsonld
name: Amazon Cloudwatch Context
namespaces:
- prefix: cloudwatch
  uri: https://aws.amazon.com/cloudwatch/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: metricDataResults
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: label
  type: string
- container: set
  name: datapoints
  type: string
- container: set
  name: metrics
  type: string
- container: set
  name: metricAlarms
  type: string
- container: set
  name: dashboardValidationMessages
  type: string
- container: ''
  name: dashboardArn
  type: string
- container: ''
  name: dashboardBody
  type: string
- container: ''
  name: dashboardName
  type: string
- container: set
  name: dashboardEntries
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: metricName
  type: string
- container: set
  name: dimensions
  type: string
- container: ''
  name: alarmName
  type: string
- container: ''
  name: alarmArn
  type: string
- container: ''
  name: alarmDescription
  type: string
- container: ''
  name: stateValue
  type: string
- container: ''
  name: stateReason
  type: string
- container: ''
  name: stateUpdatedTimestamp
  type: dateTime
- container: ''
  name: statistic
  type: string
- container: ''
  name: period
  type: integer
- container: ''
  name: evaluationPeriods
  type: integer
- container: ''
  name: threshold
  type: decimal
- container: ''
  name: comparisonOperator
  type: string
- container: ''
  name: treatMissingData
  type: string
- container: ''
  name: actionsEnabled
  type: boolean
- container: set
  name: alarmActions
  type: string
- container: set
  name: okActions
  type: string
- container: set
  name: insufficientDataActions
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: size
  type: integer
property_count: 32
provider_name: Amazon CloudWatch
provider_slug: amazon-cloudwatch
slug: amazon-cloudwatch-context
source_filename: amazon-cloudwatch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudwatch\": \"https://aws.amazon.com/cloudwatch/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetMetricDataResponse\": \"cloudwatch:GetMetricDataResponse\",\n    \"metricDataResults\": {\n      \"@id\": \"cloudwatch:metric_data_results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"cloudwatch:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMetricStatisticsResponse\": \"cloudwatch:GetMetricStatisticsResponse\",\n    \"label\": {\n      \"@id\": \"cloudwatch:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datapoints\": {\n      \"@id\": \"cloudwatch:datapoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListMetricsResponse\": \"cloudwatch:ListMetricsResponse\",\n    \"metrics\"\
  : {\n      \"@id\": \"cloudwatch:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeAlarmsResponse\": \"cloudwatch:DescribeAlarmsResponse\",\n    \"metricAlarms\": {\n      \"@id\": \"cloudwatch:metric_alarms\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutDashboardResponse\": \"cloudwatch:PutDashboardResponse\",\n    \"dashboardValidationMessages\": {\n      \"@id\": \"cloudwatch:dashboard_validation_messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetDashboardResponse\": \"cloudwatch:GetDashboardResponse\",\n    \"dashboardArn\": {\n      \"@id\": \"cloudwatch:dashboard_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardBody\": {\n      \"@id\": \"cloudwatch:dashboard_body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardName\": {\n      \"@id\": \"cloudwatch:dashboard_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListDashboardsResponse\"\
  : \"cloudwatch:ListDashboardsResponse\",\n    \"dashboardEntries\": {\n      \"@id\": \"cloudwatch:dashboard_entries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metric\": \"cloudwatch:Metric\",\n    \"namespace\": {\n      \"@id\": \"cloudwatch:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricName\": {\n      \"@id\": \"cloudwatch:metric_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"cloudwatch:dimensions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Alarm\": \"cloudwatch:Alarm\",\n    \"alarmName\": {\n      \"@id\": \"cloudwatch:alarm_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmArn\": {\n      \"@id\": \"cloudwatch:alarm_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmDescription\": {\n      \"@id\": \"cloudwatch:alarm_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateValue\": {\n      \"@id\": \"cloudwatch:state_value\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"stateReason\": {\n      \"@id\": \"cloudwatch:state_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateUpdatedTimestamp\": {\n      \"@id\": \"cloudwatch:state_updated_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"statistic\": {\n      \"@id\": \"cloudwatch:statistic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"cloudwatch:period\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"evaluationPeriods\": {\n      \"@id\": \"cloudwatch:evaluation_periods\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"threshold\": {\n      \"@id\": \"cloudwatch:threshold\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"comparisonOperator\": {\n      \"@id\": \"cloudwatch:comparison_operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"treatMissingData\": {\n      \"@id\": \"cloudwatch:treat_missing_data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionsEnabled\": {\n      \"\
  @id\": \"cloudwatch:actions_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"alarmActions\": {\n      \"@id\": \"cloudwatch:alarm_actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"okActions\": {\n      \"@id\": \"cloudwatch:ok_actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insufficientDataActions\": {\n      \"@id\": \"cloudwatch:insufficient_data_actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Dashboard\": \"cloudwatch:Dashboard\",\n    \"lastModified\": {\n      \"@id\": \"cloudwatch:last_modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"size\": {\n      \"@id\": \"cloudwatch:size\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/json-ld/amazon-cloudwatch-context.jsonld
tags:
- AWS
- CloudWatch
- Monitoring
- Observability
- Metrics
- Logs
- JSON-LD
- Linked Data
- Semantic Web
---
