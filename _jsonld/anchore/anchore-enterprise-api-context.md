---
api_specs:
- filename: anchore-enterprise-api.yaml
  format: yaml
  label: Anchore Enterprise API
  slug: anchore-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/anchore/refs/heads/main/openapi/anchore-enterprise-api.yaml
class_count: 0
classes: []
context_file: json-ld/anchore-enterprise-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/anchore/refs/heads/main/json-ld/anchore-enterprise-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Anchore Enterprise Api from Anchore.
layout: jsonld
name: Anchore Enterprise Api Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: anchore
  uri: https://raw.githubusercontent.com/api-evangelist/anchore/refs/heads/main/vocabulary/
properties:
- container: ''
  name: imageDigest
  type: string
- container: ''
  name: analysisStatus
  type: string
- container: ''
  name: imageStatus
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: vuln
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: package
  type: string
- container: ''
  name: packageVersion
  type: string
- container: ''
  name: fix
  type: string
- container: set
  name: components
  type: ''
- container: ''
  name: bomFormat
  type: string
- container: ''
  name: purl
  type: reference
- container: set
  name: licenses
  type: ''
property_count: 14
provider_name: Anchore
provider_slug: anchore
slug: anchore-enterprise-api-context
source_filename: anchore-enterprise-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"anchore\": \"https://raw.githubusercontent.com/api-evangelist/anchore/refs/heads/main/vocabulary/\",\n    \"imageDigest\": {\n      \"@id\": \"anchore:imageDigest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analysisStatus\": {\n      \"@id\": \"anchore:analysisStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageStatus\": {\n      \"@id\": \"anchore:imageStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"vuln\": {\n      \"@id\": \"anchore:vulnerabilityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"anchore:severity\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"package\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageVersion\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fix\": {\n      \"@id\": \"anchore:fixedVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"components\": {\n      \"@id\": \"anchore:components\",\n      \"@container\": \"@set\"\n    },\n    \"bomFormat\": {\n      \"@id\": \"anchore:bomFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purl\": {\n      \"@id\": \"anchore:packageUrl\",\n      \"@type\": \"@id\"\n    },\n    \"licenses\": {\n      \"@id\": \"schema:license\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/anchore/refs/heads/main/json-ld/anchore-enterprise-api-context.jsonld
tags:
- Container Security
- Containers
- SBOM
- Software Supply Chain
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
