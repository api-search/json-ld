---
api_specs:
- filename: amazon-cloudtrail-openapi.yml
  format: yaml
  label: Amazon CloudTrail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/openapi/amazon-cloudtrail-openapi.yml
class_count: 9
classes:
- CreateTrailRequest
- name
- CreateTrailResponse
- DescribeTrailsResponse
- LookupEventsRequest
- LookupEventsResponse
- CreateEventDataStoreRequest
- CreateEventDataStoreResponse
- ListEventDataStoresResponse
context_file: json-ld/amazon-cloudtrail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/json-ld/amazon-cloudtrail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloudtrail from Amazon CloudTrail.
layout: jsonld
name: Amazon Cloudtrail Context
namespaces:
- prefix: cloudtrail
  uri: https://aws.amazon.com/cloudtrail/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: s3BucketName
  type: string
- container: ''
  name: s3KeyPrefix
  type: string
- container: ''
  name: isMultiRegionTrail
  type: boolean
- container: ''
  name: enableLogFileValidation
  type: boolean
- container: ''
  name: cloudWatchLogsLogGroupArn
  type: string
- container: ''
  name: cloudWatchLogsRoleArn
  type: string
- container: ''
  name: trailARN
  type: string
- container: ''
  name: logFileValidationEnabled
  type: boolean
- container: set
  name: trailList
  type: string
- container: set
  name: lookupAttributes
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: maxResults
  type: integer
- container: ''
  name: nextToken
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: retentionPeriod
  type: integer
- container: ''
  name: multiRegionEnabled
  type: boolean
- container: ''
  name: eventDataStoreArn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdTimestamp
  type: dateTime
- container: set
  name: eventDataStores
  type: string
property_count: 21
provider_name: Amazon CloudTrail
provider_slug: amazon-cloudtrail
slug: amazon-cloudtrail-context
source_filename: amazon-cloudtrail-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudtrail\": \"https://aws.amazon.com/cloudtrail/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateTrailRequest\": \"cloudtrail:CreateTrailRequest\",\n    \"name\": \"schema:name\",\n    \"s3BucketName\": {\n      \"@id\": \"cloudtrail:s3_bucket_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3KeyPrefix\": {\n      \"@id\": \"cloudtrail:s3_key_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isMultiRegionTrail\": {\n      \"@id\": \"cloudtrail:is_multi_region_trail\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableLogFileValidation\": {\n      \"@id\": \"cloudtrail:enable_log_file_validation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cloudWatchLogsLogGroupArn\": {\n      \"@id\": \"cloudtrail:cloud_watch_logs_log_group_arn\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"cloudWatchLogsRoleArn\": {\n      \"@id\": \"cloudtrail:cloud_watch_logs_role_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTrailResponse\": \"cloudtrail:CreateTrailResponse\",\n    \"trailARN\": {\n      \"@id\": \"cloudtrail:trail_a_r_n\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logFileValidationEnabled\": {\n      \"@id\": \"cloudtrail:log_file_validation_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DescribeTrailsResponse\": \"cloudtrail:DescribeTrailsResponse\",\n    \"trailList\": {\n      \"@id\": \"cloudtrail:trail_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LookupEventsRequest\": \"cloudtrail:LookupEventsRequest\",\n    \"lookupAttributes\": {\n      \"@id\": \"cloudtrail:lookup_attributes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"cloudtrail:start_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n\
  \      \"@id\": \"cloudtrail:end_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"maxResults\": {\n      \"@id\": \"cloudtrail:max_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nextToken\": {\n      \"@id\": \"cloudtrail:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LookupEventsResponse\": \"cloudtrail:LookupEventsResponse\",\n    \"events\": {\n      \"@id\": \"cloudtrail:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateEventDataStoreRequest\": \"cloudtrail:CreateEventDataStoreRequest\",\n    \"retentionPeriod\": {\n      \"@id\": \"cloudtrail:retention_period\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"multiRegionEnabled\": {\n      \"@id\": \"cloudtrail:multi_region_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CreateEventDataStoreResponse\": \"cloudtrail:CreateEventDataStoreResponse\",\n    \"eventDataStoreArn\": {\n      \"@id\": \"cloudtrail:event_data_store_arn\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"cloudtrail:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTimestamp\": {\n      \"@id\": \"cloudtrail:created_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ListEventDataStoresResponse\": \"cloudtrail:ListEventDataStoresResponse\",\n    \"eventDataStores\": {\n      \"@id\": \"cloudtrail:event_data_stores\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/json-ld/amazon-cloudtrail-context.jsonld
tags:
- AWS
- CloudTrail
- Audit
- Compliance
- Governance
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
