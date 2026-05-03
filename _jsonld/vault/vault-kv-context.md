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
class_count: 10
classes:
- KvConfigRequest
- KvConfigResponse
- SecretDataRequest
- SecretDataResponse
- SecretMetadataRequest
- SecretMetadataResponse
- SecretVersionMetadata
- SecretWriteResponse
- VersionsRequest
- version
context_file: json-ld/vault-kv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/json-ld/vault-kv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vault Kv from HashiCorp Vault.
layout: jsonld
name: Vault Kv Context
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
  name: maxVersions
  type: integer
- container: ''
  name: casRequired
  type: boolean
- container: ''
  name: deleteVersionAfter
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: options
  type: reference
- container: ''
  name: cas
  type: integer
- container: ''
  name: metadata
  type: string
- container: ''
  name: customMetadata
  type: reference
- container: ''
  name: currentVersion
  type: integer
- container: ''
  name: oldestVersion
  type: integer
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: updatedTime
  type: dateTime
- container: ''
  name: versions
  type: reference
- container: ''
  name: deletionTime
  type: string
- container: ''
  name: destroyed
  type: boolean
property_count: 15
provider_name: HashiCorp Vault
provider_slug: vault
slug: vault-kv-context
source_filename: vault-kv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vault\": \"https://www.vaultproject.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KvConfigRequest\": \"vault:KvConfigRequest\",\n    \"KvConfigResponse\": \"vault:KvConfigResponse\",\n    \"SecretDataRequest\": \"vault:SecretDataRequest\",\n    \"SecretDataResponse\": \"vault:SecretDataResponse\",\n    \"SecretMetadataRequest\": \"vault:SecretMetadataRequest\",\n    \"SecretMetadataResponse\": \"vault:SecretMetadataResponse\",\n    \"SecretVersionMetadata\": \"vault:SecretVersionMetadata\",\n    \"SecretWriteResponse\": \"vault:SecretWriteResponse\",\n    \"VersionsRequest\": \"vault:VersionsRequest\",\n    \"maxVersions\": {\n      \"@id\": \"vault:max_versions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"casRequired\": {\n      \"@id\": \"vault:cas_required\",\n      \"@type\": \"xsd:boolean\"\n \
  \   },\n    \"deleteVersionAfter\": {\n      \"@id\": \"vault:delete_version_after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"vault:data\",\n      \"@type\": \"@id\"\n    },\n    \"options\": {\n      \"@id\": \"vault:options\",\n      \"@type\": \"@id\"\n    },\n    \"cas\": {\n      \"@id\": \"vault:cas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metadata\": {\n      \"@id\": \"vault:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customMetadata\": {\n      \"@id\": \"vault:custom_metadata\",\n      \"@type\": \"@id\"\n    },\n    \"currentVersion\": {\n      \"@id\": \"vault:current_version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"oldestVersion\": {\n      \"@id\": \"vault:oldest_version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdTime\": {\n      \"@id\": \"vault:created_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedTime\": {\n      \"@id\": \"vault:updated_time\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"versions\": {\n      \"@id\": \"vault:versions\",\n      \"@type\": \"@id\"\n    },\n    \"deletionTime\": {\n      \"@id\": \"vault:deletion_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destroyed\": {\n      \"@id\": \"vault:destroyed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"version\": \"schema:version\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/json-ld/vault-kv-context.jsonld
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
