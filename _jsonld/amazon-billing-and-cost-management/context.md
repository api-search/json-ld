---
api_specs:
- filename: aws-cost-explorer-api-openapi.yml
  format: yaml
  label: AWS Cost Explorer API
  slug: aws-cost-explorer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/openapi/aws-cost-explorer-api-openapi.yml
- filename: aws-budgets-api-openapi.yml
  format: yaml
  label: AWS Budgets API
  slug: aws-budgets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/openapi/aws-budgets-api-openapi.yml
class_count: 19
classes:
- Budget
- BudgetName
- BudgetType
- BudgetLimit
- TimeUnit
- TimePeriod
- CalculatedSpend
- ActualSpend
- ForecastedSpend
- AnomalyMonitor
- MonitorArn
- MonitorName
- MonitorType
- CostCategory
- CostCategoryArn
- Amount
- Unit
- name
- description
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Amazon Billing And Cost Management.
layout: jsonld
name: context Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: aws-billing
  uri: https://aws.amazon.com/billing/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 2
provider_name: Amazon Billing And Cost Management
provider_slug: amazon-billing-and-cost-management
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"aws-billing\": \"https://aws.amazon.com/billing/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Budget\": \"aws-billing:Budget\",\n    \"BudgetName\": \"aws-billing:budgetName\",\n    \"BudgetType\": \"aws-billing:budgetType\",\n    \"BudgetLimit\": \"aws-billing:budgetLimit\",\n    \"TimeUnit\": \"aws-billing:timeUnit\",\n    \"TimePeriod\": \"aws-billing:timePeriod\",\n    \"CalculatedSpend\": \"aws-billing:calculatedSpend\",\n    \"ActualSpend\": \"aws-billing:actualSpend\",\n    \"ForecastedSpend\": \"aws-billing:forecastedSpend\",\n\n    \"AnomalyMonitor\": \"aws-billing:AnomalyMonitor\",\n    \"MonitorArn\": \"aws-billing:monitorArn\",\n    \"MonitorName\": \"aws-billing:monitorName\",\n    \"MonitorType\": \"aws-billing:monitorType\",\n\n    \"CostCategory\": \"aws-billing:CostCategory\",\n    \"CostCategoryArn\": \"aws-billing:costCategoryArn\",\n\n\
  \    \"Amount\": \"schema:price\",\n    \"Unit\": \"schema:priceCurrency\",\n\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/json-ld/context.jsonld
tags:
- Billing
- Cost Management
- Cost Explorer
- Budgets
- Cost Optimization
- FinOps
- Amazon Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
