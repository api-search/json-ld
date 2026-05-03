---
api_specs:
- filename: opensearch-security-openapi.yml
  format: yaml
  label: OpenSearch Security Plugin REST API
  slug: opensearch-security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/openapi/opensearch-security-openapi.yml
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/opensearch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/json-ld/opensearch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Opensearch from OpenSearch.
layout: jsonld
name: Opensearch Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Role
  uri: https://opensearch.org/ns#Role
- prefix: RoleMapping
  uri: https://opensearch.org/ns#RoleMapping
- prefix: ActionGroup
  uri: https://opensearch.org/ns#ActionGroup
- prefix: Tenant
  uri: https://opensearch.org/ns#Tenant
- prefix: InternalUser
  uri: https://opensearch.org/ns#InternalUser
- prefix: cluster_permissions
  uri: https://opensearch.org/ns#clusterPermissions
- prefix: index_permissions
  uri: https://opensearch.org/ns#indexPermissions
- prefix: tenant_permissions
  uri: https://opensearch.org/ns#tenantPermissions
- prefix: index_patterns
  uri: https://opensearch.org/ns#indexPatterns
- prefix: tenant_patterns
  uri: https://opensearch.org/ns#tenantPatterns
- prefix: allowed_actions
  uri: https://opensearch.org/ns#allowedActions
- prefix: backend_roles
  uri: https://opensearch.org/ns#backendRoles
- prefix: users
  uri: https://opensearch.org/ns#users
- prefix: hosts
  uri: https://opensearch.org/ns#hosts
- prefix: dls
  uri: https://opensearch.org/ns#documentLevelSecurity
- prefix: fls
  uri: https://opensearch.org/ns#fieldLevelSecurity
- prefix: masked_fields
  uri: https://opensearch.org/ns#maskedFields
properties: []
property_count: 0
provider_name: OpenSearch
provider_slug: opensearch
slug: opensearch-context
source_filename: opensearch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://opensearch.org/ns#\",\n    \"schema\": \"https://schema.org/\",\n    \"Role\": \"https://opensearch.org/ns#Role\",\n    \"RoleMapping\": \"https://opensearch.org/ns#RoleMapping\",\n    \"ActionGroup\": \"https://opensearch.org/ns#ActionGroup\",\n    \"Tenant\": \"https://opensearch.org/ns#Tenant\",\n    \"InternalUser\": \"https://opensearch.org/ns#InternalUser\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"cluster_permissions\": \"https://opensearch.org/ns#clusterPermissions\",\n    \"index_permissions\": \"https://opensearch.org/ns#indexPermissions\",\n    \"tenant_permissions\": \"https://opensearch.org/ns#tenantPermissions\",\n    \"index_patterns\": \"https://opensearch.org/ns#indexPatterns\",\n    \"tenant_patterns\": \"https://opensearch.org/ns#tenantPatterns\",\n    \"allowed_actions\": \"https://opensearch.org/ns#allowedActions\",\n    \"backend_roles\": \"\
  https://opensearch.org/ns#backendRoles\",\n    \"users\": \"https://opensearch.org/ns#users\",\n    \"hosts\": \"https://opensearch.org/ns#hosts\",\n    \"dls\": \"https://opensearch.org/ns#documentLevelSecurity\",\n    \"fls\": \"https://opensearch.org/ns#fieldLevelSecurity\",\n    \"masked_fields\": \"https://opensearch.org/ns#maskedFields\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/json-ld/opensearch-context.jsonld
tags:
- Search
- Analytics
- Observability
- Open Source
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
