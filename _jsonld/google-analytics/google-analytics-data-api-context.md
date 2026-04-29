---
api_specs:
- filename: google-analytics-data-api.yaml
  format: yaml
  label: Google Analytics Data API (GA4)
  slug: google-analytics-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-data-api.yaml
- filename: google-analytics-admin-api.yaml
  format: yaml
  label: Google Analytics Admin API
  slug: google-analytics-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-admin-api.yaml
- filename: google-analytics-measurement-protocol.yaml
  format: yaml
  label: Google Analytics Measurement Protocol (GA4)
  slug: google-analytics-measurement-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-measurement-protocol.yaml
- filename: google-analytics-user-deletion-api.yaml
  format: yaml
  label: Google Analytics User Deletion API
  slug: google-analytics-user-deletion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-user-deletion-api.yaml
- filename: google-analytics-reporting-api-v4.yaml
  format: yaml
  label: Google Analytics Reporting API v4 (Universal Analytics)
  slug: google-analytics-reporting-api-v4
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-reporting-api-v4.yaml
- filename: google-analytics-management-api-v3.yaml
  format: yaml
  label: Google Analytics Management API v3
  slug: google-analytics-management-api-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-management-api-v3.yaml
class_count: 10
classes:
- AudienceExport
- DateRange
- Dimension
- FilterExpression
- Metric
- OrderBy
- Pivot
- Row
- RunReportRequest
- RunReportResponse
context_file: json-ld/google-analytics-data-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-data-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Analytics Data Api from Google Analytics.
layout: jsonld
name: Google Analytics Data Api Context
namespaces:
- prefix: ga
  uri: https://developers.google.com/analytics/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accumulate
  type: boolean
- container: set
  name: activeMetricRestrictions
  type: string
- container: ''
  name: andGroup
  type: string
- container: ''
  name: audience
  type: string
- container: ''
  name: audienceDisplayName
  type: string
- container: ''
  name: beginCreatingTime
  type: dateTime
- container: ''
  name: betweenFilter
  type: string
- container: ''
  name: caseSensitive
  type: boolean
- container: ''
  name: cohortReportSettings
  type: reference
- container: ''
  name: cohortSpec
  type: reference
- container: set
  name: cohorts
  type: string
- container: ''
  name: cohortsRange
  type: reference
- container: ''
  name: concatenate
  type: reference
- container: ''
  name: concurrentRequests
  type: reference
- container: ''
  name: consumed
  type: integer
- container: ''
  name: creationQuotaTokensCharged
  type: integer
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: dataLossFromOtherRow
  type: boolean
- container: set
  name: dateRanges
  type: reference
- container: ''
  name: delimiter
  type: string
- container: ''
  name: desc
  type: boolean
- container: ''
  name: dimension
  type: reference
- container: ''
  name: dimensionExpression
  type: reference
- container: ''
  name: dimensionFilter
  type: reference
- container: set
  name: dimensionHeaders
  type: reference
- container: ''
  name: dimensionName
  type: string
- container: set
  name: dimensionNames
  type: string
- container: set
  name: dimensionValues
  type: reference
- container: set
  name: dimensions
  type: reference
- container: ''
  name: emptyReason
  type: string
- container: ''
  name: endDate
  type: string
- container: ''
  name: endOffset
  type: integer
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: expression
  type: string
- container: set
  name: expressions
  type: string
- container: ''
  name: fieldName
  type: string
- container: set
  name: fieldNames
  type: string
- container: ''
  name: filter
  type: string
- container: ''
  name: fromValue
  type: string
- container: ''
  name: granularity
  type: string
- container: ''
  name: inListFilter
  type: string
- container: ''
  name: invisible
  type: boolean
- container: ''
  name: keepEmptyRows
  type: boolean
- container: ''
  name: kind
  type: string
- container: ''
  name: limit
  type: string
- container: ''
  name: lowerCase
  type: reference
- container: ''
  name: matchType
  type: string
- container: set
  name: maximums
  type: reference
- container: ''
  name: metadata
  type: reference
- container: ''
  name: metric
  type: reference
- container: set
  name: metricAggregations
  type: string
- container: ''
  name: metricFilter
  type: reference
- container: set
  name: metricHeaders
  type: reference
- container: ''
  name: metricName
  type: string
- container: set
  name: metricValues
  type: reference
- container: set
  name: metrics
  type: reference
- container: set
  name: minimums
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: notExpression
  type: string
- container: ''
  name: numericFilter
  type: string
- container: ''
  name: offset
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: orGroup
  type: reference
- container: set
  name: orderBys
  type: reference
- container: ''
  name: orderType
  type: string
- container: ''
  name: percentageCompleted
  type: double
- container: ''
  name: pivot
  type: reference
- container: set
  name: pivotSelections
  type: string
- container: ''
  name: potentiallyThresholdedRequestsPerHour
  type: reference
- container: ''
  name: property
  type: string
- container: ''
  name: propertyQuota
  type: reference
- container: ''
  name: remaining
  type: integer
- container: ''
  name: returnPropertyQuota
  type: boolean
- container: ''
  name: rowCount
  type: integer
- container: set
  name: rows
  type: reference
- container: set
  name: samplingMetadatas
  type: string
- container: ''
  name: schemaRestrictionResponse
  type: reference
- container: ''
  name: serverErrorsPerProjectPerHour
  type: reference
- container: ''
  name: startDate
  type: string
- container: ''
  name: startOffset
  type: integer
- container: ''
  name: state
  type: string
- container: ''
  name: stringFilter
  type: string
- container: ''
  name: subjectToThresholding
  type: boolean
- container: ''
  name: timeZone
  type: string
- container: ''
  name: toValue
  type: string
- container: ''
  name: tokensPerDay
  type: reference
- container: ''
  name: tokensPerHour
  type: reference
- container: ''
  name: tokensPerProjectPerHour
  type: reference
- container: set
  name: totals
  type: reference
- container: ''
  name: upperCase
  type: reference
- container: ''
  name: value
  type: string
- container: set
  name: values
  type: string
property_count: 92
provider_name: Google Analytics
provider_slug: google-analytics
slug: google-analytics-data-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ga\": \"https://developers.google.com/analytics/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AudienceExport\": \"ga:AudienceExport\",\n    \"DateRange\": \"ga:DateRange\",\n    \"Dimension\": \"ga:Dimension\",\n    \"FilterExpression\": \"ga:FilterExpression\",\n    \"Metric\": \"ga:Metric\",\n    \"OrderBy\": \"ga:OrderBy\",\n    \"Pivot\": \"ga:Pivot\",\n    \"Row\": \"ga:Row\",\n    \"RunReportRequest\": \"ga:RunReportRequest\",\n    \"RunReportResponse\": \"ga:RunReportResponse\",\n    \"accumulate\": {\n      \"@id\": \"ga:accumulate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"activeMetricRestrictions\": {\n      \"@id\": \"ga:activeMetricRestrictions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"andGroup\": {\n      \"@id\": \"ga:andGroup\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"audience\": {\n      \"@id\": \"ga:audience\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audienceDisplayName\": {\n      \"@id\": \"ga:audienceDisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beginCreatingTime\": {\n      \"@id\": \"ga:beginCreatingTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"betweenFilter\": {\n      \"@id\": \"ga:betweenFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caseSensitive\": {\n      \"@id\": \"ga:caseSensitive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cohortReportSettings\": {\n      \"@id\": \"ga:cohortReportSettings\",\n      \"@type\": \"@id\"\n    },\n    \"cohortSpec\": {\n      \"@id\": \"ga:cohortSpec\",\n      \"@type\": \"@id\"\n    },\n    \"cohorts\": {\n      \"@id\": \"ga:cohorts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cohortsRange\": {\n      \"@id\": \"ga:cohortsRange\",\n      \"@type\": \"@id\"\n    },\n    \"concatenate\"\
  : {\n      \"@id\": \"ga:concatenate\",\n      \"@type\": \"@id\"\n    },\n    \"concurrentRequests\": {\n      \"@id\": \"ga:concurrentRequests\",\n      \"@type\": \"@id\"\n    },\n    \"consumed\": {\n      \"@id\": \"ga:consumed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"creationQuotaTokensCharged\": {\n      \"@id\": \"ga:creationQuotaTokensCharged\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"ga:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataLossFromOtherRow\": {\n      \"@id\": \"ga:dataLossFromOtherRow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dateRanges\": {\n      \"@id\": \"ga:dateRanges\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"delimiter\": {\n      \"@id\": \"ga:delimiter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"desc\": {\n      \"@id\": \"ga:desc\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dimension\": {\n      \"@id\": \"ga:dimension\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"dimensionExpression\": {\n      \"@id\": \"ga:dimensionExpression\",\n      \"@type\": \"@id\"\n    },\n    \"dimensionFilter\": {\n      \"@id\": \"ga:dimensionFilter\",\n      \"@type\": \"@id\"\n    },\n    \"dimensionHeaders\": {\n      \"@id\": \"ga:dimensionHeaders\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"dimensionName\": {\n      \"@id\": \"ga:dimensionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionNames\": {\n      \"@id\": \"ga:dimensionNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionValues\": {\n      \"@id\": \"ga:dimensionValues\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"dimensions\": {\n      \"@id\": \"ga:dimensions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"emptyReason\": {\n      \"@id\": \"ga:emptyReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDate\"\
  : {\n      \"@id\": \"ga:endDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endOffset\": {\n      \"@id\": \"ga:endOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"ga:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"ga:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expressions\": {\n      \"@id\": \"ga:expressions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldName\": {\n      \"@id\": \"ga:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldNames\": {\n      \"@id\": \"ga:fieldNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"ga:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromValue\": {\n      \"@id\": \"ga:fromValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"granularity\": {\n      \"@id\": \"ga:granularity\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"inListFilter\": {\n      \"@id\": \"ga:inListFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invisible\": {\n      \"@id\": \"ga:invisible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"keepEmptyRows\": {\n      \"@id\": \"ga:keepEmptyRows\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kind\": {\n      \"@id\": \"ga:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"ga:limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lowerCase\": {\n      \"@id\": \"ga:lowerCase\",\n      \"@type\": \"@id\"\n    },\n    \"matchType\": {\n      \"@id\": \"ga:matchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximums\": {\n      \"@id\": \"ga:maximums\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"metadata\": {\n      \"@id\": \"ga:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"metric\": {\n      \"@id\": \"ga:metric\",\n      \"@type\": \"@id\"\n    },\n    \"metricAggregations\"\
  : {\n      \"@id\": \"ga:metricAggregations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricFilter\": {\n      \"@id\": \"ga:metricFilter\",\n      \"@type\": \"@id\"\n    },\n    \"metricHeaders\": {\n      \"@id\": \"ga:metricHeaders\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"metricName\": {\n      \"@id\": \"ga:metricName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricValues\": {\n      \"@id\": \"ga:metricValues\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"metrics\": {\n      \"@id\": \"ga:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"minimums\": {\n      \"@id\": \"ga:minimums\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notExpression\": {\n      \"@id\": \"ga:notExpression\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"numericFilter\": {\n      \"@id\": \"ga:numericFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"ga:offset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"ga:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orGroup\": {\n      \"@id\": \"ga:orGroup\",\n      \"@type\": \"@id\"\n    },\n    \"orderBys\": {\n      \"@id\": \"ga:orderBys\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"orderType\": {\n      \"@id\": \"ga:orderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentageCompleted\": {\n      \"@id\": \"ga:percentageCompleted\",\n      \"@type\": \"xsd:double\"\n    },\n    \"pivot\": {\n      \"@id\": \"ga:pivot\",\n      \"@type\": \"@id\"\n    },\n    \"pivotSelections\": {\n      \"@id\": \"ga:pivotSelections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"potentiallyThresholdedRequestsPerHour\": {\n \
  \     \"@id\": \"ga:potentiallyThresholdedRequestsPerHour\",\n      \"@type\": \"@id\"\n    },\n    \"property\": {\n      \"@id\": \"ga:property\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyQuota\": {\n      \"@id\": \"ga:propertyQuota\",\n      \"@type\": \"@id\"\n    },\n    \"remaining\": {\n      \"@id\": \"ga:remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"returnPropertyQuota\": {\n      \"@id\": \"ga:returnPropertyQuota\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rowCount\": {\n      \"@id\": \"ga:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rows\": {\n      \"@id\": \"ga:rows\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"samplingMetadatas\": {\n      \"@id\": \"ga:samplingMetadatas\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaRestrictionResponse\": {\n      \"@id\": \"ga:schemaRestrictionResponse\",\n      \"@type\": \"@id\"\n    },\n    \"serverErrorsPerProjectPerHour\"\
  : {\n      \"@id\": \"ga:serverErrorsPerProjectPerHour\",\n      \"@type\": \"@id\"\n    },\n    \"startDate\": {\n      \"@id\": \"ga:startDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startOffset\": {\n      \"@id\": \"ga:startOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"state\": {\n      \"@id\": \"ga:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringFilter\": {\n      \"@id\": \"ga:stringFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectToThresholding\": {\n      \"@id\": \"ga:subjectToThresholding\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timeZone\": {\n      \"@id\": \"ga:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toValue\": {\n      \"@id\": \"ga:toValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokensPerDay\": {\n      \"@id\": \"ga:tokensPerDay\",\n      \"@type\": \"@id\"\n    },\n    \"tokensPerHour\": {\n      \"@id\": \"ga:tokensPerHour\",\n      \"@type\": \"@id\"\n    },\n    \"tokensPerProjectPerHour\"\
  : {\n      \"@id\": \"ga:tokensPerProjectPerHour\",\n      \"@type\": \"@id\"\n    },\n    \"totals\": {\n      \"@id\": \"ga:totals\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"upperCase\": {\n      \"@id\": \"ga:upperCase\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"ga:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"ga:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-data-api-context.jsonld
tags:
- Analytics
- Data
- Google
- Metrics
- Reporting
- Web Analytics
- Machine Learning
- Attribution
- JSON-LD
- Linked Data
- Semantic Web
---
