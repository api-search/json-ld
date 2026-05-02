---
api_specs:
- filename: kubecost-allocation-openapi.yml
  format: yaml
  label: Kubecost Allocation API
  slug: allocation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-allocation-openapi.yml
- filename: kubecost-assets-openapi.yml
  format: yaml
  label: Kubecost Assets API
  slug: assets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-assets-openapi.yml
- filename: kubecost-cloud-cost-openapi.yml
  format: yaml
  label: Kubecost Cloud Cost API
  slug: cloud-cost-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-cloud-cost-openapi.yml
- filename: kubecost-budget-openapi.yml
  format: yaml
  label: Kubecost Budget API
  slug: budget-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-budget-openapi.yml
- filename: kubecost-forecast-openapi.yml
  format: yaml
  label: Kubecost Forecast API
  slug: forecast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-forecast-openapi.yml
- filename: kubecost-savings-openapi.yml
  format: yaml
  label: Kubecost Savings API
  slug: savings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-savings-openapi.yml
class_count: 0
classes: []
context_file: json-ld/kubecost-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/json-ld/kubecost-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kubecost from Kubecost.
layout: jsonld
name: Kubecost Context
namespaces:
- prefix: kubecost
  uri: https://docs.kubecost.com/apis/
properties:
- container: ''
  name: Allocation
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Budget
  type: ''
- container: ''
  name: BudgetAction
  type: ''
- container: ''
  name: CloudCost
  type: ''
- container: ''
  name: Forecast
  type: ''
- container: ''
  name: SavingsRecommendation
  type: ''
property_count: 7
provider_name: Kubecost
provider_slug: kubecost
slug: kubecost-context
source_filename: kubecost-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"kubecost\": \"https://docs.kubecost.com/apis/\",\n    \"Allocation\": {\n      \"@id\": \"kubecost:monitoring-apis/api-allocation\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"cluster\": \"https://schema.org/memberOf\",\n        \"node\": \"https://schema.org/hasPart\",\n        \"namespace\": \"https://schema.org/category\",\n        \"controller\": \"https://schema.org/controlAction\",\n        \"controllerKind\": \"https://schema.org/additionalType\",\n        \"pod\": \"https://schema.org/hasPart\",\n        \"container\": \"https://schema.org/hasPart\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"annotations\": \"https://schema.org/description\",\n        \"services\": \"https://schema.org/serviceType\",\n        \"cpuCost\": \"https://schema.org/price\",\n        \"gpuCost\": \"https://schema.org/price\",\n        \"ramCost\": \"https://schema.org/price\"\
  ,\n        \"pvCost\": \"https://schema.org/price\",\n        \"networkCost\": \"https://schema.org/price\",\n        \"loadBalancerCost\": \"https://schema.org/price\",\n        \"totalCost\": \"https://schema.org/totalPrice\",\n        \"totalEfficiency\": \"https://schema.org/valueReference\",\n        \"start\": \"https://schema.org/startDate\",\n        \"end\": \"https://schema.org/endDate\"\n      }\n    },\n    \"Asset\": {\n      \"@id\": \"kubecost:monitoring-apis/assets-api\",\n      \"@context\": {\n        \"type\": \"https://schema.org/additionalType\",\n        \"cluster\": \"https://schema.org/memberOf\",\n        \"name\": \"https://schema.org/name\",\n        \"providerID\": \"https://schema.org/identifier\",\n        \"provider\": \"https://schema.org/provider\",\n        \"account\": \"https://schema.org/account\",\n        \"project\": \"https://schema.org/project\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"category\": \"https://schema.org/category\"\
  ,\n        \"labels\": \"https://schema.org/keywords\",\n        \"totalCost\": \"https://schema.org/totalPrice\",\n        \"adjustment\": \"https://schema.org/discount\",\n        \"start\": \"https://schema.org/startDate\",\n        \"end\": \"https://schema.org/endDate\"\n      }\n    },\n    \"Budget\": {\n      \"@id\": \"kubecost:governance-apis/budget-api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"amount\": \"https://schema.org/price\",\n        \"interval\": \"https://schema.org/repeatFrequency\",\n        \"aggregation\": \"https://schema.org/category\",\n        \"filter\": \"https://schema.org/query\",\n        \"actions\": \"https://schema.org/potentialAction\",\n        \"currentSpend\": \"https://schema.org/price\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"BudgetAction\": {\n \
  \     \"@id\": \"kubecost:governance-apis/budget-api#action\",\n      \"@context\": {\n        \"threshold\": \"https://schema.org/valueReference\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"target\": \"https://schema.org/recipient\"\n      }\n    },\n    \"CloudCost\": {\n      \"@id\": \"kubecost:monitoring-apis/cloud-cost-api\",\n      \"@context\": {\n        \"invoiceEntityID\": \"https://schema.org/identifier\",\n        \"accountID\": \"https://schema.org/account\",\n        \"provider\": \"https://schema.org/provider\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"listCost\": \"https://schema.org/price\",\n        \"netCost\": \"https://schema.org/totalPrice\",\n        \"amortizedNetCost\": \"https://schema.org/price\",\n        \"invoicedCost\": \"https://schema.org/price\",\n        \"start\": \"https://schema.org/startDate\",\n        \"end\": \"https://schema.org/endDate\"\
  \n      }\n    },\n    \"Forecast\": {\n      \"@id\": \"kubecost:governance-apis/forecast-api\",\n      \"@context\": {\n        \"totalCost\": \"https://schema.org/totalPrice\",\n        \"confidence\": \"https://schema.org/valueReference\",\n        \"forecastWindow\": \"https://schema.org/duration\",\n        \"start\": \"https://schema.org/startDate\",\n        \"end\": \"https://schema.org/endDate\"\n      }\n    },\n    \"SavingsRecommendation\": {\n      \"@id\": \"kubecost:savings-apis\",\n      \"@context\": {\n        \"clusterName\": \"https://schema.org/name\",\n        \"namespace\": \"https://schema.org/category\",\n        \"controllerKind\": \"https://schema.org/additionalType\",\n        \"controllerName\": \"https://schema.org/name\",\n        \"containerName\": \"https://schema.org/name\",\n        \"monthlySavings\": \"https://schema.org/discount\",\n        \"currentMonthlyRate\": \"https://schema.org/price\",\n        \"recommendedMonthlyRate\": \"https://schema.org/price\"\
  ,\n        \"currentNodeCount\": \"https://schema.org/amount\",\n        \"recommendedNodeCount\": \"https://schema.org/amount\",\n        \"currentNodeType\": \"https://schema.org/additionalType\",\n        \"recommendedNodeType\": \"https://schema.org/additionalType\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/json-ld/kubecost-context.jsonld
tags:
- Cloud Cost
- Cost Monitoring
- Kubernetes
- Optimization
- Spending
- JSON-LD
- Linked Data
- Semantic Web
---
