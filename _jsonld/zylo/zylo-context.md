---
api_specs:
- filename: zylo-enterprise-openapi.yml
  format: yaml
  label: Zylo Enterprise API
  slug: enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zylo/refs/heads/main/openapi/zylo-enterprise-openapi.yml
class_count: 2
classes:
- id
- type
context_file: json-ld/zylo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zylo/refs/heads/main/json-ld/zylo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zylo from Zylo.
layout: jsonld
name: Zylo Context
namespaces:
- prefix: zylo
  uri: https://developer.zylo.com/reference/
properties:
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: ExportJob
  type: ''
- container: ''
  name: ImportJob
  type: ''
property_count: 4
provider_name: Zylo
provider_slug: zylo
slug: zylo-context
source_filename: zylo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"zylo\": \"https://developer.zylo.com/reference/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Subscription\": {\n      \"@id\": \"zylo:Subscription\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"applicationId\": \"zylo:applicationId\",\n        \"applicationName\": \"zylo:applicationName\",\n        \"status\": \"schema:status\",\n        \"owner\": \"schema:owner\",\n        \"renewalDate\": {\n          \"@id\": \"zylo:renewalDate\",\n          \"@type\": \"schema:Date\"\n        },\n        \"annualCost\": {\n          \"@id\": \"zylo:annualCost\",\n          \"@type\": \"schema:MonetaryAmount\"\n        },\n        \"licenseCount\": {\n          \"@id\": \"zylo:licenseCount\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"usedLicenseCount\": {\n          \"@id\": \"zylo:usedLicenseCount\",\n          \"@type\": \"schema:Integer\"\n        },\n  \
  \      \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"customFields\": \"zylo:customFields\"\n      }\n    },\n    \"Application\": {\n      \"@id\": \"zylo:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"category\": \"schema:category\",\n        \"owner\": \"schema:owner\",\n        \"status\": \"schema:status\",\n        \"trueUp\": \"zylo:trueUp\",\n        \"totalSpend\": {\n          \"@id\": \"zylo:totalSpend\",\n          \"@type\": \"schema:MonetaryAmount\"\n        },\n        \"subscriptionCount\": {\n          \"@id\": \"zylo:subscriptionCount\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"updatedAt\"\
  : {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"customFields\": \"zylo:customFields\"\n      }\n    },\n    \"ExportJob\": {\n      \"@id\": \"zylo:ExportJob\",\n      \"@context\": {\n        \"status\": \"schema:status\",\n        \"downloadUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"zylo:completedAt\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"error\": \"zylo:error\"\n      }\n    },\n    \"ImportJob\": {\n      \"@id\": \"zylo:ImportJob\",\n      \"@context\": {\n        \"subscriptionId\": \"zylo:subscriptionId\",\n        \"status\": \"schema:status\",\n        \"fileName\": \"schema:name\",\n        \"recordsProcessed\": {\n          \"@id\": \"zylo:recordsProcessed\",\n\
  \          \"@type\": \"schema:Integer\"\n        },\n        \"recordsFailed\": {\n          \"@id\": \"zylo:recordsFailed\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"zylo:completedAt\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"error\": \"zylo:error\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zylo/refs/heads/main/json-ld/zylo-context.jsonld
tags:
- Budgets
- SaaS Management
- Spend
- JSON-LD
- Linked Data
- Semantic Web
---
