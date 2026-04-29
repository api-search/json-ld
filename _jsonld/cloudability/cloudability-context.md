---
class_count: 0
classes: []
context_file: json-ld/cloudability-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudability/refs/heads/main/json-ld/cloudability-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudability from Cloudability.
layout: jsonld
name: Cloudability Context
namespaces:
- prefix: cloudability
  uri: https://api.cloudability.com/v3/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: finops
  uri: https://www.finops.org/framework/
properties:
- container: ''
  name: ReportResult
  type: ''
- container: ''
  name: BusinessMapping
  type: ''
- container: ''
  name: RightsizingRecommendation
  type: ''
- container: ''
  name: Anomaly
  type: ''
- container: ''
  name: VendorCredential
  type: ''
- container: ''
  name: View
  type: ''
- container: ''
  name: Budget
  type: ''
property_count: 7
provider_name: Cloudability
provider_slug: cloudability
slug: cloudability-context
source_filename: cloudability-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudability\": \"https://api.cloudability.com/v3/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"finops\": \"https://www.finops.org/framework/\",\n\n    \"ReportResult\": {\n      \"@id\": \"cloudability:ReportResult\",\n      \"@context\": {\n        \"metrics\": {\n          \"@id\": \"cloudability:metrics\",\n          \"@container\": \"@list\"\n        },\n        \"dimensions\": {\n          \"@id\": \"cloudability:dimensions\",\n          \"@container\": \"@list\"\n        },\n        \"startDate\": {\n          \"@id\": \"dcterms:temporal\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"cloudability:end_date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"results\": {\n          \"@id\": \"cloudability:results\",\n          \"@container\": \"@set\"\n\
  \        }\n      }\n    },\n\n    \"BusinessMapping\": {\n      \"@id\": \"cloudability:BusinessMapping\",\n      \"@context\": {\n        \"id\": \"cloudability:id\",\n        \"name\": \"schema:name\",\n        \"kind\": \"cloudability:kind\",\n        \"default_value\": \"cloudability:default_value\",\n        \"statements\": {\n          \"@id\": \"cloudability:statements\",\n          \"@container\": \"@list\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RightsizingRecommendation\": {\n      \"@id\": \"cloudability:RightsizingRecommendation\",\n      \"@context\": {\n        \"resourceId\": \"cloudability:resource_identifier\",\n        \"vendor\": \"cloudability:vendor\",\n        \"service\": \"cloudability:service\",\n        \"currentInstanceType\": \"\
  cloudability:current_instance_type\",\n        \"recommendedInstanceType\": \"cloudability:recommended_instance_type\",\n        \"estimatedMonthlySavings\": \"cloudability:estimated_savings\",\n        \"currency\": \"schema:priceCurrency\",\n        \"confidence\": \"cloudability:confidence\",\n        \"utilizationMetrics\": \"cloudability:utilization\"\n      }\n    },\n\n    \"Anomaly\": {\n      \"@id\": \"cloudability:Anomaly\",\n      \"@context\": {\n        \"id\": \"cloudability:id\",\n        \"dimensionType\": \"cloudability:dimension_type\",\n        \"dimensionValue\": \"cloudability:dimension_value\",\n        \"detectedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expectedCost\": \"cloudability:expected_cost\",\n        \"actualCost\": \"cloudability:actual_cost\",\n        \"delta\": \"cloudability:delta\",\n        \"status\": \"cloudability:status\",\n        \"severity\": \"cloudability:severity\"\n \
  \     }\n    },\n\n    \"VendorCredential\": {\n      \"@id\": \"cloudability:VendorCredential\",\n      \"@context\": {\n        \"id\": \"cloudability:id\",\n        \"vendor\": \"cloudability:vendor\",\n        \"accountIdentifier\": \"cloudability:account_identifier\",\n        \"verification\": \"cloudability:verification\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"View\": {\n      \"@id\": \"cloudability:View\",\n      \"@context\": {\n        \"id\": \"cloudability:id\",\n        \"title\": \"schema:name\",\n        \"filters\": {\n          \"@id\": \"cloudability:filters\",\n          \"@container\": \"@list\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Budget\": {\n      \"@id\": \"cloudability:Budget\",\n      \"@context\": {\n        \"id\": \"cloudability:id\",\n\
  \        \"name\": \"schema:name\",\n        \"amount\": \"cloudability:amount\",\n        \"currency\": \"schema:priceCurrency\",\n        \"period\": \"cloudability:period\",\n        \"alertThresholds\": {\n          \"@id\": \"cloudability:alert_thresholds\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudability/refs/heads/main/json-ld/cloudability-context.jsonld
tags:
- Cloud Cost Management
- Cost Optimization
- FinOps
- Multi-Cloud
- Recommendations
- Reporting
- JSON-LD
- Linked Data
- Semantic Web
---
