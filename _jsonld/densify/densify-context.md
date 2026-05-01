---
api_specs:
- filename: dev
  format: yaml
  label: Densify Public Cloud API
  slug: public-cloud-api
  spec_type: Postman
  url: https://www.densify.com/dev
class_count: 0
classes: []
context_file: json-ld/densify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/densify/refs/heads/main/json-ld/densify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Densify from Densify.
layout: jsonld
name: Densify Context
namespaces:
- prefix: densify
  uri: https://www.densify.com/docs-api/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: System
  type: ''
- container: ''
  name: Recommendation
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: ContainerRecommendation
  type: ''
- container: ''
  name: Token
  type: ''
property_count: 6
provider_name: Densify
provider_slug: densify
slug: densify-context
source_filename: densify-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"densify\": \"https://www.densify.com/docs-api/\",\n    \"Account\": {\n      \"@id\": \"densify:WebHelp_Densify_API_Cloud/Content/API_Guide/Accounts.htm\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"accountId\": \"https://schema.org/identifier\",\n        \"provider\": \"https://schema.org/provider\",\n        \"region\": \"https://schema.org/areaServed\"\n      }\n    },\n    \"System\": {\n      \"@id\": \"densify:WebHelp_Densify_API_Cloud/Content/API_Guide/Systems.htm\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"instanceId\": \"https://schema.org/identifier\",\n        \"instanceType\": \"https://schema.org/category\",\n        \"currentSize\": \"https://schema.org/size\",\n        \"recommendedSize\": \"https://schema.org/suggestedAnswer\"\n      }\n    },\n    \"Recommendation\": {\n      \"@id\": \"densify:WebHelp_Densify_API_Cloud/Content/API_Guide/Recommendations.htm\"\
  ,\n      \"@context\": {\n        \"system\": \"https://schema.org/about\",\n        \"currentCost\": \"https://schema.org/price\",\n        \"recommendedCost\": \"https://schema.org/lowPrice\",\n        \"savings\": \"https://schema.org/discount\",\n        \"confidence\": \"https://schema.org/ratingValue\"\n      }\n    },\n    \"Cluster\": {\n      \"@id\": \"densify:WebHelp_Densify_API/Content/Clusters.htm\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"provider\": \"https://schema.org/provider\",\n        \"region\": \"https://schema.org/areaServed\",\n        \"version\": \"https://schema.org/softwareVersion\"\n      }\n    },\n    \"ContainerRecommendation\": {\n      \"@id\": \"densify:WebHelp_Densify_API/Content/Recommendations.htm\",\n      \"@context\": {\n        \"cluster\": \"https://schema.org/isPartOf\",\n        \"namespace\": \"https://schema.org/category\",\n        \"controller\": \"https://schema.org/owner\",\n        \"container\"\
  : \"https://schema.org/about\",\n        \"cpuRequest\": \"https://schema.org/value\",\n        \"memoryRequest\": \"https://schema.org/value\"\n      }\n    },\n    \"Token\": {\n      \"@id\": \"densify:WebHelp_Densify_API_Cloud/Content/API_Guide/Authorize.htm\",\n      \"@context\": {\n        \"value\": \"https://schema.org/accessCode\",\n        \"expiresAt\": \"https://schema.org/expires\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/densify/refs/heads/main/json-ld/densify-context.jsonld
tags:
- Cloud Cost
- Container Optimization
- FinOps
- Kubernetes
- Machine Learning
- Recommendations
- Right-Sizing
- JSON-LD
- Linked Data
- Semantic Web
---
