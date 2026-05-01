---
api_specs:
- filename: amazon-timestream-openapi.yml
  format: yaml
  label: Amazon Timestream API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/openapi/amazon-timestream-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-timestream-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/json-ld/amazon-timestream-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Timestream from Amazon Timestream.
layout: jsonld
name: Amazon Timestream Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/timestream/schemas/
- prefix: timestream
  uri: https://docs.aws.amazon.com/timestream/latest/developerguide/API_Reference.html#
properties:
- container: ''
  name: Database
  type: ''
- container: ''
  name: Table
  type: ''
- container: ''
  name: RetentionProperties
  type: ''
- container: ''
  name: Record
  type: ''
- container: ''
  name: Dimension
  type: ''
- container: ''
  name: QueryResult
  type: ''
property_count: 6
provider_name: Amazon Timestream
provider_slug: amazon-timestream
slug: amazon-timestream-context
source_filename: amazon-timestream-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/timestream/schemas/\",\n    \"timestream\": \"https://docs.aws.amazon.com/timestream/latest/developerguide/API_Reference.html#\",\n    \"Database\": {\n      \"@id\": \"aws:Database\",\n      \"@context\": {\n        \"DatabaseName\": \"schema:name\",\n        \"Arn\": \"aws:arn\",\n        \"TableCount\": \"schema:size\",\n        \"KmsKeyId\": \"aws:kmsKeyId\",\n        \"CreationTime\": \"schema:dateCreated\",\n        \"LastUpdatedTime\": \"schema:dateModified\"\n      }\n    },\n    \"Table\": {\n      \"@id\": \"aws:Table\",\n      \"@context\": {\n        \"TableName\": \"schema:name\",\n        \"DatabaseName\": \"schema:isPartOf\",\n        \"Arn\": \"aws:arn\",\n        \"TableStatus\": \"aws:tableStatus\",\n        \"RetentionProperties\": \"aws:RetentionProperties\",\n        \"CreationTime\": \"schema:dateCreated\",\n        \"LastUpdatedTime\": \"schema:dateModified\"\
  \n      }\n    },\n    \"RetentionProperties\": {\n      \"@id\": \"aws:RetentionProperties\",\n      \"@context\": {\n        \"MemoryStoreRetentionPeriodInHours\": \"aws:memoryStoreRetention\",\n        \"MagneticStoreRetentionPeriodInDays\": \"aws:magneticStoreRetention\"\n      }\n    },\n    \"Record\": {\n      \"@id\": \"aws:Record\",\n      \"@context\": {\n        \"Dimensions\": \"aws:dimensions\",\n        \"MeasureName\": \"schema:name\",\n        \"MeasureValue\": \"schema:value\",\n        \"MeasureValueType\": \"schema:additionalType\",\n        \"Time\": \"schema:dateCreated\",\n        \"TimeUnit\": \"aws:timeUnit\",\n        \"Version\": \"schema:version\"\n      }\n    },\n    \"Dimension\": {\n      \"@id\": \"aws:Dimension\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Value\": \"schema:value\",\n        \"DimensionValueType\": \"schema:additionalType\"\n      }\n    },\n    \"QueryResult\": {\n      \"@id\": \"aws:QueryResult\",\n      \"\
  @context\": {\n        \"QueryId\": \"schema:identifier\",\n        \"Rows\": \"aws:rows\",\n        \"ColumnInfo\": \"aws:columnInfo\",\n        \"QueryStatus\": \"aws:queryStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/json-ld/amazon-timestream-context.jsonld
tags:
- Database
- Iot
- Time Series
- JSON-LD
- Linked Data
- Semantic Web
---
