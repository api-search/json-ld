---
api_specs:
- filename: scalr-user-openapi.yml
  format: yaml
  label: Scalr User API
  slug: scalr-user-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-user-openapi.yml
- filename: scalr-account-openapi.yml
  format: yaml
  label: Scalr Account API
  slug: scalr-account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-account-openapi.yml
- filename: scalr-global-openapi.yml
  format: yaml
  label: Scalr Global API
  slug: scalr-global-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-global-openapi.yml
class_count: 1
classes:
- id
context_file: json-ld/scalr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-ld/scalr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalr from Scalr.
layout: jsonld
name: Scalr Context
namespaces:
- prefix: scalr
  uri: https://scalr.com/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ScalrWorkspace
  type: schema:SoftwareApplication
- container: ''
  name: ScalrRun
  type: schema:Action
- container: ''
  name: ScalrEnvironment
  type: schema:Project
- container: ''
  name: ScalrAccount
  type: schema:Organization
- container: ''
  name: ScalrVariable
  type: schema:PropertyValue
- container: ''
  name: ScalrPolicy
  type: schema:DigitalDocument
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: workspace
  type: reference
- container: ''
  name: environment
  type: reference
- container: ''
  name: account
  type: reference
- container: ''
  name: terraform_version
  type: string
- container: ''
  name: auto_apply
  type: boolean
- container: ''
  name: is_destroy
  type: boolean
- container: ''
  name: plan_only
  type: boolean
- container: ''
  name: message
  type: string
- container: ''
  name: trigger_reason
  type: string
- container: ''
  name: cost_estimate
  type: schema:MonetaryAmount
- container: ''
  name: proposed_monthly_cost
  type: string
- container: ''
  name: prior_monthly_cost
  type: string
- container: ''
  name: delta_monthly_cost
  type: string
- container: ''
  name: vcs_provider
  type: schema:SoftwareApplication
- container: ''
  name: execution_mode
  type: string
- container: list
  name: tags
  type: ''
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 27
provider_name: Scalr
provider_slug: scalr
slug: scalr-context
source_filename: scalr-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"scalr\": \"https://scalr.com/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ScalrWorkspace\": {\n      \"@id\": \"scalr:Workspace\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ScalrRun\": {\n      \"@id\": \"scalr:Run\",\n      \"@type\": \"schema:Action\"\n    },\n    \"ScalrEnvironment\": {\n      \"@id\": \"scalr:Environment\",\n      \"@type\": \"schema:Project\"\n    },\n    \"ScalrAccount\": {\n      \"@id\": \"scalr:Account\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"ScalrVariable\": {\n      \"@id\": \"scalr:Variable\",\n      \"@type\": \"schema:PropertyValue\"\n    },\n    \"ScalrPolicy\": {\n      \"@id\": \"scalr:Policy\",\n      \"@type\": \"schema:DigitalDocument\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\"\
  : {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspace\": {\n      \"@id\": \"scalr:workspace\",\n      \"@type\": \"@id\"\n    },\n    \"environment\": {\n      \"@id\": \"scalr:environment\",\n      \"@type\": \"@id\"\n    },\n    \"account\": {\n      \"@id\": \"scalr:account\",\n      \"@type\": \"@id\"\n    },\n    \"terraform_version\": {\n      \"@id\": \"scalr:terraformVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auto_apply\": {\n      \"@id\": \"scalr:autoApply\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_destroy\": {\n      \"@id\": \"scalr:isDestroy\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"plan_only\": {\n      \"@id\": \"scalr:planOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trigger_reason\"\
  : {\n      \"@id\": \"scalr:triggerReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cost_estimate\": {\n      \"@id\": \"scalr:costEstimate\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"proposed_monthly_cost\": {\n      \"@id\": \"scalr:proposedMonthlyCost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prior_monthly_cost\": {\n      \"@id\": \"scalr:priorMonthlyCost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delta_monthly_cost\": {\n      \"@id\": \"scalr:deltaMonthlyCost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vcs_provider\": {\n      \"@id\": \"scalr:vcsProvider\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"execution_mode\": {\n      \"@id\": \"scalr:executionMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\"\
  : {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-ld/scalr-context.jsonld
tags:
- FinOps
- GitOps
- Infrastructure as Code
- Kubernetes
- OPA
- OpenTofu
- Policy
- Terraform
- JSON-LD
- Linked Data
- Semantic Web
---
