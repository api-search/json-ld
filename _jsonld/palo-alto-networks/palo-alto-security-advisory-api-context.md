---
class_count: 3
classes:
- Advisory
- AffectedProduct
- Product
context_file: json-ld/palo-alto-security-advisory-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-security-advisory-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Security Advisory Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Security Advisory Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: advisoryCount
  type: integer
- container: ''
  name: advisoryId
  type: string
- container: set
  name: affectedProducts
  type: reference
- container: ''
  name: cveId
  type: string
- container: ''
  name: cvssScore
  type: decimal
- container: ''
  name: cvssVector
  type: string
- container: ''
  name: cwe
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: exploitStatus
  type: string
- container: set
  name: fixedVersions
  type: string
- container: ''
  name: lastModifiedDate
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: product
  type: string
- container: ''
  name: publishedDate
  type: dateTime
- container: set
  name: references
  type: reference
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: version
  type: string
- container: set
  name: versions
  type: reference
- container: ''
  name: workarounds
  type: string
property_count: 22
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-security-advisory-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Advisory\": \"pan:Advisory\",\n    \"AffectedProduct\": \"pan:AffectedProduct\",\n    \"Product\": \"pan:Product\",\n    \"advisoryCount\": {\n      \"@id\": \"pan:advisory_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"advisoryId\": {\n      \"@id\": \"pan:advisory_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedProducts\": {\n      \"@id\": \"pan:affected_products\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"cveId\": {\n      \"@id\": \"pan:cve_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvssScore\": {\n      \"@id\": \"pan:cvss_score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cvssVector\": {\n      \"@id\": \"pan:cvss_vector\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"cwe\": {\n      \"@id\": \"pan:cwe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exploitStatus\": {\n      \"@id\": \"pan:exploit_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixedVersions\": {\n      \"@id\": \"pan:fixed_versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedDate\": {\n      \"@id\": \"pan:last_modified_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"pan:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishedDate\": {\n      \"@id\": \"pan:published_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"references\": {\n      \"@id\": \"pan:references\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"severity\"\
  : {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"pan:versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"workarounds\": {\n      \"@id\": \"pan:workarounds\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-security-advisory-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
