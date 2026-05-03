---
api_specs:
- filename: hcp-terraform-openapi.yml
  format: yaml
  label: HCP Terraform API
  slug: hcp-terraform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/hcp-terraform-openapi.yml
- filename: terraform-registry-openapi.yml
  format: yaml
  label: Terraform Registry API
  slug: terraform-registry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/terraform-registry-openapi.yml
class_count: 33
classes:
- Workspace
- Run
- StateVersion
- Organization
- Team
- Policy
- Project
- Module
- workspaceName
- executionMode
- autoApply
- locked
- terraformVersion
- runStatus
- isDestroy
- hasChanges
- resourceAdditions
- resourceChanges
- resourceDestructions
- stateSerial
- hostedStateDownloadUrl
- enforcementLevel
- policyKind
- moduleNamespace
- moduleProvider
- moduleVerified
- organizationName
- description
- createdAt
- updatedAt
- email
- source
- downloads
context_file: json-ld/terraform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/json-ld/terraform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Terraform from Terraform.
layout: jsonld
name: Terraform Context
namespaces:
- prefix: terraform
  uri: https://developer.hashicorp.com/terraform/vocab#
- prefix: hcp
  uri: https://app.terraform.io/vocab#
properties: []
property_count: 0
provider_name: Terraform
provider_slug: terraform
slug: terraform-context
source_filename: terraform-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"terraform\": \"https://developer.hashicorp.com/terraform/vocab#\",\n    \"hcp\": \"https://app.terraform.io/vocab#\",\n    \"Workspace\": \"terraform:Workspace\",\n    \"Run\": \"terraform:Run\",\n    \"StateVersion\": \"terraform:StateVersion\",\n    \"Organization\": \"terraform:Organization\",\n    \"Team\": \"terraform:Team\",\n    \"Policy\": \"terraform:Policy\",\n    \"Project\": \"terraform:Project\",\n    \"Module\": \"terraform:Module\",\n    \"workspaceName\": \"terraform:workspaceName\",\n    \"executionMode\": \"terraform:executionMode\",\n    \"autoApply\": \"terraform:autoApply\",\n    \"locked\": \"terraform:locked\",\n    \"terraformVersion\": \"terraform:terraformVersion\",\n    \"runStatus\": \"terraform:runStatus\",\n    \"isDestroy\": \"terraform:isDestroy\",\n    \"hasChanges\": \"terraform:hasChanges\",\n    \"resourceAdditions\": \"terraform:resourceAdditions\",\n    \"resourceChanges\"\
  : \"terraform:resourceChanges\",\n    \"resourceDestructions\": \"terraform:resourceDestructions\",\n    \"stateSerial\": \"terraform:stateSerial\",\n    \"hostedStateDownloadUrl\": \"terraform:hostedStateDownloadUrl\",\n    \"enforcementLevel\": \"terraform:enforcementLevel\",\n    \"policyKind\": \"terraform:policyKind\",\n    \"moduleNamespace\": \"terraform:moduleNamespace\",\n    \"moduleProvider\": \"terraform:moduleProvider\",\n    \"moduleVerified\": \"terraform:moduleVerified\",\n    \"organizationName\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"email\": \"schema:email\",\n    \"source\": \"schema:url\",\n    \"downloads\": \"schema:downloadCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/json-ld/terraform-context.jsonld
tags:
- Infrastructure As Code
- Cloud Infrastructure
- DevOps
- Open Source
- HashiCorp
- JSON-LD
- Linked Data
- Semantic Web
---
