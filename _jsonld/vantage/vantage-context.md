---
api_specs:
- filename: vantage-cost-management-api-openapi.yml
  format: yaml
  label: Vantage Cost Management API
  slug: cost-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/openapi/vantage-cost-management-api-openapi.yml
- filename: vantage-cloud-pricing-api-openapi.yml
  format: yaml
  label: Vantage Cloud Pricing API
  slug: cloud-pricing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/openapi/vantage-cloud-pricing-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/vantage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/json-ld/vantage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vantage from Vantage.
layout: jsonld
name: Vantage Context
namespaces:
- prefix: vantage
  uri: https://docs.vantage.sh/
properties:
- container: ''
  name: CostReport
  type: ''
- container: ''
  name: Cost
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Dashboard
  type: ''
- container: ''
  name: SavedFilter
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: AccessGrant
  type: ''
- container: ''
  name: BudgetAlert
  type: ''
- container: ''
  name: AnomalyAlert
  type: ''
- container: ''
  name: Recommendation
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Integration
  type: ''
- container: ''
  name: ManagedAccount
  type: ''
- container: ''
  name: BusinessMetric
  type: ''
- container: ''
  name: ResourceReport
  type: ''
- container: ''
  name: Resource
  type: ''
- container: ''
  name: NetworkFlowReport
  type: ''
- container: ''
  name: FinancialCommitmentReport
  type: ''
- container: ''
  name: KubernetesEfficiencyReport
  type: ''
- container: ''
  name: CostProvider
  type: ''
- container: ''
  name: Provider
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Price
  type: ''
property_count: 25
provider_name: Vantage
provider_slug: vantage
slug: vantage-context
source_filename: vantage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vantage\": \"https://docs.vantage.sh/\",\n    \"CostReport\": {\n      \"@id\": \"vantage:cost_reports\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"filter\": \"https://schema.org/query\",\n        \"groupings\": \"https://schema.org/category\",\n        \"folder_token\": {\n          \"@id\": \"vantage:folders\",\n          \"@type\": \"@id\"\n        },\n        \"saved_filter_tokens\": {\n          \"@id\": \"vantage:saved_filters\",\n          \"@type\": \"@id\"\n        },\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Cost\": {\n      \"@id\": \"vantage:cost_reports\",\n      \"@context\": {\n        \"date\": \"https://schema.org/date\",\n        \"amount\"\
  : \"https://schema.org/price\",\n        \"currency\": \"https://schema.org/priceCurrency\",\n        \"provider\": \"https://schema.org/provider\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"account_id\": \"https://schema.org/identifier\",\n        \"region\": \"https://schema.org/areaServed\",\n        \"category\": \"https://schema.org/category\",\n        \"subcategory\": \"https://schema.org/category\"\n      }\n    },\n    \"Folder\": {\n      \"@id\": \"vantage:folders\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"parent_folder_token\": {\n          \"@id\": \"vantage:folders\",\n          \"@type\": \"@id\"\n        },\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Dashboard\": {\n      \"@id\": \"vantage:dashboards\"\
  ,\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"widget_tokens\": \"https://schema.org/hasPart\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"SavedFilter\": {\n      \"@id\": \"vantage:saved_filters\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"filter\": \"https://schema.org/query\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Workspace\": {\n      \"@id\": \"vantage:workspaces\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\"\
  ,\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Team\": {\n      \"@id\": \"vantage:teams\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"user_tokens\": \"https://schema.org/member\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"AccessGrant\": {\n      \"@id\": \"vantage:access_grants\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"team_token\": {\n          \"@id\": \"vantage:teams\",\n          \"@type\": \"@id\"\n        },\n        \"resource_token\": \"https://schema.org/object\",\n        \"access\": \"https://schema.org/permissionType\",\n        \"created_at\": \"https://schema.org/dateCreated\"\
  \n      }\n    },\n    \"BudgetAlert\": {\n      \"@id\": \"vantage:budget_alerts\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"cost_report_token\": {\n          \"@id\": \"vantage:cost_reports\",\n          \"@type\": \"@id\"\n        },\n        \"budget\": \"https://schema.org/price\",\n        \"period\": \"https://schema.org/billingPeriod\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"AnomalyAlert\": {\n      \"@id\": \"vantage:anomaly_alerts\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"cost_report_token\": {\n          \"@id\": \"vantage:cost_reports\",\n          \"@type\": \"@id\"\n        },\n        \"threshold\": \"https://schema.org/value\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Recommendation\": {\n      \"@id\": \"vantage:recommendations\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\"\
  ,\n        \"type\": \"https://schema.org/category\",\n        \"description\": \"https://schema.org/description\",\n        \"estimated_savings\": \"https://schema.org/price\",\n        \"provider\": \"https://schema.org/provider\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"resource_id\": \"https://schema.org/identifier\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Segment\": {\n      \"@id\": \"vantage:segments\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"filter\": \"https://schema.org/query\",\n        \"priority\": \"https://schema.org/position\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Integration\": {\n      \"@id\": \"vantage:integrations\",\n      \"@context\"\
  : {\n        \"token\": \"https://schema.org/identifier\",\n        \"provider\": \"https://schema.org/provider\",\n        \"status\": \"https://schema.org/status\",\n        \"account_identifier\": \"https://schema.org/identifier\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"ManagedAccount\": {\n      \"@id\": \"vantage:managed_accounts\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"account_identifier\": \"https://schema.org/identifier\",\n        \"provider\": \"https://schema.org/provider\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"BusinessMetric\": {\n      \"@id\": \"vantage:business_metrics\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"values\": \"https://schema.org/value\",\n        \"created_at\": \"https://schema.org/dateCreated\"\
  \n      }\n    },\n    \"ResourceReport\": {\n      \"@id\": \"vantage:resource_reports\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"filter\": \"https://schema.org/query\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Resource\": {\n      \"@id\": \"vantage:resources\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"provider\": \"https://schema.org/provider\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"account_id\": \"https://schema.org/identifier\",\n        \"region\": \"https://schema.org/areaServed\",\n        \"cost\": \"https://schema.org/price\",\n        \"metadata\": \"https://schema.org/additionalProperty\"\n    \
  \  }\n    },\n    \"NetworkFlowReport\": {\n      \"@id\": \"vantage:network_flow_reports\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"FinancialCommitmentReport\": {\n      \"@id\": \"vantage:financial_commitment_reports\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"workspace_token\": {\n          \"@id\": \"vantage:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"KubernetesEfficiencyReport\": {\n      \"@id\": \"vantage:kubernetes\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"\
  cluster_name\": \"https://schema.org/name\",\n        \"namespace\": \"https://schema.org/identifier\",\n        \"idle_cost\": \"https://schema.org/price\",\n        \"total_cost\": \"https://schema.org/price\",\n        \"efficiency\": \"https://schema.org/value\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"CostProvider\": {\n      \"@id\": \"vantage:cost_providers\",\n      \"@context\": {\n        \"token\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\"\n      }\n    },\n    \"Provider\": {\n      \"@id\": \"vantage:providers\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"services_count\": \"https://schema.org/value\"\n      }\n    },\n    \"Service\": {\n      \"@id\": \"vantage:services\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"name\": \"https://schema.org/name\",\n        \"provider_id\": {\n          \"@id\": \"vantage:providers\",\n          \"@type\": \"@id\"\n        },\n        \"products_count\": \"https://schema.org/value\"\n      }\n    },\n    \"Product\": {\n      \"@id\": \"vantage:products\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"provider_id\": {\n          \"@id\": \"vantage:providers\",\n          \"@type\": \"@id\"\n        },\n        \"service_id\": {\n          \"@id\": \"vantage:services\",\n          \"@type\": \"@id\"\n        },\n        \"details\": \"https://schema.org/additionalProperty\",\n        \"prices\": \"https://schema.org/offers\"\n      }\n    },\n    \"Price\": {\n      \"@id\": \"vantage:prices\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"unit\": \"https://schema.org/unitText\",\n        \"price\": \"https://schema.org/price\"\
  ,\n        \"currency\": \"https://schema.org/priceCurrency\",\n        \"region\": \"https://schema.org/areaServed\",\n        \"description\": \"https://schema.org/description\",\n        \"product_id\": {\n          \"@id\": \"vantage:products\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/json-ld/vantage-context.jsonld
tags:
- Budgets
- Cloud Pricing
- Cost Management
- Costs
- FinOps
- JSON-LD
- Linked Data
- Semantic Web
---
