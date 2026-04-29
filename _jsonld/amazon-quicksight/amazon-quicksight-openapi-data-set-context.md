---
class_count: 1
classes:
- DataSetSummary
context_file: json-ld/amazon-quicksight-openapi-data-set-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/json-ld/amazon-quicksight-openapi-data-set-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Quicksight Openapi Data Set from Amazon QuickSight.
layout: jsonld
name: Amazon Quicksight Openapi Data Set Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Arn
  type: string
- container: ''
  name: DataSetId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: CreatedTime
  type: dateTime
- container: ''
  name: LastUpdatedTime
  type: dateTime
- container: ''
  name: ImportMode
  type: string
property_count: 6
provider_name: Amazon QuickSight
provider_slug: amazon-quicksight
slug: amazon-quicksight-openapi-data-set-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataSetSummary\": \"aws:DataSetSummary\",\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataSetId\": {\n      \"@id\": \"aws:DataSetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedTime\": {\n      \"@id\": \"aws:CreatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastUpdatedTime\": {\n      \"@id\": \"aws:LastUpdatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ImportMode\": {\n      \"@id\": \"aws:ImportMode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/json-ld/amazon-quicksight-openapi-data-set-context.jsonld
tags:
- Analytics
- AWS
- BI
- Business Intelligence
- Dashboards
- Machine Learning
- Reporting
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
