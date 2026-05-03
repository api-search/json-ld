---
api_specs:
- filename: vault-kv-openapi.yml
  format: yaml
  label: HashiCorp Vault KV Secrets Engine API
  slug: vault-kv
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/openapi/vault-kv-openapi.yml
- filename: vault-sys-openapi.yml
  format: yaml
  label: HashiCorp Vault System Backend API
  slug: vault-sys
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/openapi/vault-sys-openapi.yml
class_count: 17
classes:
- AuthMethodConfig
- AuthMethodsResponse
- EnableAuthMethodRequest
- EnableMountRequest
- HealthResponse
- LeaseIdRequest
- LeaseRenewResponse
- LeaseResponse
- MountConfig
- MountsResponse
- PoliciesListResponse
- PolicyRequest
- PolicyResponse
- RenewLeaseRequest
- description
- version
- name
context_file: json-ld/vault-sys-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/json-ld/vault-sys-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vault Sys from HashiCorp Vault.
layout: jsonld
name: Vault Sys Context
namespaces:
- prefix: vault
  uri: https://www.vaultproject.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: accessor
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: options
  type: reference
- container: ''
  name: initialized
  type: boolean
- container: ''
  name: sealed
  type: boolean
- container: ''
  name: standby
  type: boolean
- container: ''
  name: clusterName
  type: string
- container: ''
  name: clusterId
  type: string
- container: ''
  name: leaseId
  type: string
- container: ''
  name: renewable
  type: boolean
- container: ''
  name: leaseDuration
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: issueTime
  type: dateTime
- container: ''
  name: expireTime
  type: dateTime
- container: ''
  name: ttl
  type: integer
- container: set
  name: policies
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: increment
  type: integer
property_count: 19
provider_name: HashiCorp Vault
provider_slug: vault
slug: vault-sys-context
source_filename: vault-sys-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vault\": \"https://www.vaultproject.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthMethodConfig\": \"vault:AuthMethodConfig\",\n    \"AuthMethodsResponse\": \"vault:AuthMethodsResponse\",\n    \"EnableAuthMethodRequest\": \"vault:EnableAuthMethodRequest\",\n    \"EnableMountRequest\": \"vault:EnableMountRequest\",\n    \"HealthResponse\": \"vault:HealthResponse\",\n    \"LeaseIdRequest\": \"vault:LeaseIdRequest\",\n    \"LeaseRenewResponse\": \"vault:LeaseRenewResponse\",\n    \"LeaseResponse\": \"vault:LeaseResponse\",\n    \"MountConfig\": \"vault:MountConfig\",\n    \"MountsResponse\": \"vault:MountsResponse\",\n    \"PoliciesListResponse\": \"vault:PoliciesListResponse\",\n    \"PolicyRequest\": \"vault:PolicyRequest\",\n    \"PolicyResponse\": \"vault:PolicyResponse\",\n    \"RenewLeaseRequest\": \"\
  vault:RenewLeaseRequest\",\n    \"type\": {\n      \"@id\": \"vault:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"accessor\": {\n      \"@id\": \"vault:accessor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"vault:data\",\n      \"@type\": \"@id\"\n    },\n    \"options\": {\n      \"@id\": \"vault:options\",\n      \"@type\": \"@id\"\n    },\n    \"initialized\": {\n      \"@id\": \"vault:initialized\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sealed\": {\n      \"@id\": \"vault:sealed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"standby\": {\n      \"@id\": \"vault:standby\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"version\": \"schema:version\",\n    \"clusterName\": {\n      \"@id\": \"vault:cluster_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterId\": {\n      \"@id\": \"vault:cluster_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"leaseId\": {\n    \
  \  \"@id\": \"vault:lease_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renewable\": {\n      \"@id\": \"vault:renewable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"leaseDuration\": {\n      \"@id\": \"vault:lease_duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"vault:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issueTime\": {\n      \"@id\": \"vault:issue_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expireTime\": {\n      \"@id\": \"vault:expire_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ttl\": {\n      \"@id\": \"vault:ttl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"policies\": {\n      \"@id\": \"vault:policies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"vault:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"increment\": {\n      \"@id\": \"vault:increment\",\n      \"@type\"\
  : \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/json-ld/vault-sys-context.jsonld
tags:
- DevOps
- Encryption
- Open Source
- PKI
- Secrets Management
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
