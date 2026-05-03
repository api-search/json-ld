---
api_specs:
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CVE API
  slug: nvd-cve
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CVE Change History API
  slug: nvd-cve-history
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CPE API
  slug: nvd-cpe
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CPE Match Criteria API
  slug: nvd-cpe-match
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD Source API
  slug: nvd-source
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
class_count: 8
classes:
- CVE
- id
- vulnStatus
- value
- lang
- CVSSMetric
- baseSeverity
- CPE
context_file: json-ld/nvd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nvd from NVD.
layout: jsonld
name: Nvd Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: nvd
  uri: https://nvd.nist.gov/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: sourceIdentifier
  type: string
- container: ''
  name: published
  type: dateTime
- container: ''
  name: lastModified
  type: dateTime
- container: set
  name: descriptions
  type: ''
- container: set
  name: references
  type: ''
- container: ''
  name: url
  type: anyURI
- container: ''
  name: baseScore
  type: decimal
- container: ''
  name: vectorString
  type: string
- container: set
  name: weaknesses
  type: ''
- container: set
  name: configurations
  type: ''
- container: ''
  name: cisaExploitAdd
  type: date
- container: ''
  name: cisaActionDue
  type: date
- container: ''
  name: cisaRequiredAction
  type: string
- container: ''
  name: cpeName
  type: string
property_count: 14
provider_name: NVD
provider_slug: nvd
slug: nvd-context
source_filename: nvd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"nvd\": \"https://nvd.nist.gov/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"CVE\": \"schema:TechArticle\",\n    \"id\": \"schema:identifier\",\n    \"sourceIdentifier\": {\n      \"@id\": \"schema:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"published\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"vulnStatus\": \"schema:status\",\n    \"descriptions\": {\n      \"@id\": \"schema:description\",\n      \"@container\": \"@set\"\n    },\n    \"value\": \"schema:text\",\n    \"lang\": \"schema:inLanguage\",\n    \"references\": {\n      \"@id\": \"schema:citation\",\n      \"@container\": \"@set\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n\
  \    },\n    \"CVSSMetric\": \"schema:Rating\",\n    \"baseScore\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"baseSeverity\": \"schema:ratingValue\",\n    \"vectorString\": {\n      \"@id\": \"nvd:cvssVector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weaknesses\": {\n      \"@id\": \"nvd:weakness\",\n      \"@container\": \"@set\"\n    },\n    \"configurations\": {\n      \"@id\": \"nvd:affectedConfiguration\",\n      \"@container\": \"@set\"\n    },\n    \"cisaExploitAdd\": {\n      \"@id\": \"nvd:kevAddDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"cisaActionDue\": {\n      \"@id\": \"nvd:kevActionDueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"cisaRequiredAction\": {\n      \"@id\": \"nvd:kevRequiredAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CPE\": \"schema:SoftwareApplication\",\n    \"cpeName\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld
tags:
- Security
- CVE
- CPE
- Vulnerability
- CVSS
- JSON-LD
- Linked Data
- Semantic Web
---
