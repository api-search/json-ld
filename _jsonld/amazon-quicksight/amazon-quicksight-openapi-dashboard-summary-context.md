---
api_specs:
- filename: amazon-quicksight-openapi.yml
  format: yaml
  label: Amazon QuickSight API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/openapi/amazon-quicksight-openapi.yml
class_count: 1
classes:
- DashboardSummary
context_file: json-ld/amazon-quicksight-openapi-dashboard-summary-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/json-ld/amazon-quicksight-openapi-dashboard-summary-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Quicksight Openapi Dashboard Summary from Amazon QuickSight.
layout: jsonld
name: Amazon Quicksight Openapi Dashboard Summary Context
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
  name: DashboardId
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
  name: PublishedVersionNumber
  type: integer
- container: ''
  name: LastPublishedTime
  type: dateTime
property_count: 7
provider_name: Amazon QuickSight
provider_slug: amazon-quicksight
slug: amazon-quicksight-openapi-dashboard-summary-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DashboardSummary\": \"aws:DashboardSummary\",\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DashboardId\": {\n      \"@id\": \"aws:DashboardId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedTime\": {\n      \"@id\": \"aws:CreatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastUpdatedTime\": {\n      \"@id\": \"aws:LastUpdatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PublishedVersionNumber\": {\n      \"@id\": \"aws:PublishedVersionNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"LastPublishedTime\": {\n      \"@id\": \"aws:LastPublishedTime\",\n    \
  \  \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/json-ld/amazon-quicksight-openapi-dashboard-summary-context.jsonld
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
