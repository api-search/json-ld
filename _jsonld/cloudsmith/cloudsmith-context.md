---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Cloudsmith API (v1)
  slug: v1
  spec_type: OpenAPI
  url: https://api.cloudsmith.io/?format=openapi
class_count: 0
classes: []
context_file: json-ld/cloudsmith-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudsmith/refs/heads/main/json-ld/cloudsmith-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudsmith from Cloudsmith.
layout: jsonld
name: Cloudsmith Context
namespaces:
- prefix: cloudsmith
  uri: https://api.cloudsmith.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: spdx
  uri: http://spdx.org/rdf/terms#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Repository
  type: ''
- container: ''
  name: Package
  type: ''
- container: ''
  name: File
  type: ''
- container: ''
  name: Entitlement
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: AuditEvent
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: Distro
  type: ''
property_count: 9
provider_name: Cloudsmith
provider_slug: cloudsmith
slug: cloudsmith-context
source_filename: cloudsmith-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudsmith\": \"https://api.cloudsmith.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"spdx\": \"http://spdx.org/rdf/terms#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"cloudsmith:Organization\",\n      \"@context\": {\n        \"slug\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"country\": \"schema:addressCountry\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Repository\": {\n      \"@id\": \"cloudsmith:Repository\",\n      \"@context\": {\n        \"slug\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"namespace\": \"cloudsmith:namespace\",\n        \"repositoryType\": \"cloudsmith:repository_type\",\n        \"storageRegion\": \"cloudsmith:storage_region\",\n\
  \        \"indexFiles\": \"cloudsmith:index_files\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"cloudsmith:Package\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\",\n        \"format\": \"cloudsmith:format\",\n        \"filename\": \"cloudsmith:filename\",\n        \"size\": \"schema:contentSize\",\n        \"checksumSha256\": \"spdx:checksum\",\n        \"downloadCount\": \"cloudsmith:downloads\",\n        \"uploadedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"File\": {\n      \"@id\": \"cloudsmith:File\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"filename\": \"cloudsmith:filename\",\n        \"size\": \"schema:contentSize\",\n  \
  \      \"checksumSha256\": \"spdx:checksum\"\n      }\n    },\n\n    \"Entitlement\": {\n      \"@id\": \"cloudsmith:Entitlement\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"token\": \"cloudsmith:token\",\n        \"isActive\": \"cloudsmith:is_active\",\n        \"limitDateRangeFrom\": \"cloudsmith:limit_date_from\",\n        \"limitDateRangeTo\": \"cloudsmith:limit_date_to\",\n        \"limitNumDownloads\": \"cloudsmith:limit_num_downloads\"\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"cloudsmith:Webhook\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"targetUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"cloudsmith:events\",\n          \"@container\": \"@set\"\n        },\n        \"isActive\": \"cloudsmith:is_active\"\n      }\n    },\n\n    \"AuditEvent\": {\n      \"@id\": \"\
  cloudsmith:AuditEvent\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"actor\": \"schema:agent\",\n        \"event\": \"schema:action\",\n        \"objectKind\": \"cloudsmith:object_kind\",\n        \"objectIdentifier\": \"cloudsmith:object_identifier\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"cloudsmith:Vulnerability\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"cveId\": \"cloudsmith:cve_id\",\n        \"severity\": \"cloudsmith:severity\",\n        \"score\": \"cloudsmith:score\",\n        \"package\": \"cloudsmith:package_id\"\n      }\n    },\n\n    \"Distro\": {\n      \"@id\": \"cloudsmith:Distro\",\n      \"@context\": {\n        \"slug\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"format\": \"cloudsmith:format\",\n        \"versions\": {\n\
  \          \"@id\": \"cloudsmith:versions\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudsmith/refs/heads/main/json-ld/cloudsmith-context.jsonld
tags:
- Artifact Management
- DevOps
- DevSecOps
- Distribution
- Package Management
- Registry
- Repository
- Software Supply Chain
- Universal
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
