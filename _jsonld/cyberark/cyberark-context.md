---
api_specs:
- filename: cyberark-conjur-openapi.yml
  format: yaml
  label: CyberArk Conjur Secrets Manager API
  slug: conjur
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/openapi/cyberark-conjur-openapi.yml
class_count: 29
classes:
- PrivilegedAccount
- Safe
- Platform
- ConjurResource
- ConjurVariable
- ConjurHost
- IdentityTenant
- AppRole
- EndpointAgent
- id
- type
- name
- address
- userName
- platformId
- safeName
- secretType
- secretManagement
- description
- olacEnabled
- managingCPM
- kind
- owner
- permissions
- annotations
- currentValue
- version
- apiKey
- layer
context_file: json-ld/cyberark-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/json-ld/cyberark-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cyberark from CyberArk.
layout: jsonld
name: Cyberark Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cyberark
  uri: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/vocabulary/cyberark-vocabulary.yml#
properties: []
property_count: 0
provider_name: CyberArk
provider_slug: cyberark
slug: cyberark-context
source_filename: cyberark-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/vocabulary/cyberark-vocabulary.yml#\",\n    \"schema\": \"https://schema.org/\",\n    \"cyberark\": \"https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/vocabulary/cyberark-vocabulary.yml#\",\n    \"PrivilegedAccount\": \"cyberark:PrivilegedAccount\",\n    \"Safe\": \"cyberark:Safe\",\n    \"Platform\": \"cyberark:Platform\",\n    \"ConjurResource\": \"cyberark:ConjurResource\",\n    \"ConjurVariable\": \"cyberark:ConjurVariable\",\n    \"ConjurHost\": \"cyberark:ConjurHost\",\n    \"IdentityTenant\": \"cyberark:IdentityTenant\",\n    \"AppRole\": \"cyberark:AppRole\",\n    \"EndpointAgent\": \"cyberark:EndpointAgent\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"address\": \"schema:address\",\n    \"userName\": \"cyberark:userName\",\n    \"platformId\": \"cyberark:platformId\"\
  ,\n    \"safeName\": \"cyberark:safeName\",\n    \"secretType\": \"cyberark:secretType\",\n    \"secretManagement\": \"cyberark:secretManagement\",\n    \"description\": \"schema:description\",\n    \"olacEnabled\": \"cyberark:olacEnabled\",\n    \"managingCPM\": \"cyberark:managingCPM\",\n    \"kind\": \"cyberark:kind\",\n    \"owner\": \"cyberark:owner\",\n    \"permissions\": \"cyberark:permissions\",\n    \"annotations\": \"cyberark:annotations\",\n    \"currentValue\": \"cyberark:currentValue\",\n    \"version\": \"schema:version\",\n    \"apiKey\": \"cyberark:apiKey\",\n    \"layer\": \"cyberark:layer\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/json-ld/cyberark-context.jsonld
tags:
- Authentication
- Cloud Security
- Conjur
- Credential Vault
- DevOps Secrets
- Endpoint Privilege Management
- Identity Security
- Machine Identity
- MFA
- OpenAPI
- PAM
- Privileged Access
- Privileged Access Management
- Secrets Management
- Session Management
- SSO
- Vault
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
