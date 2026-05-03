---
api_specs:
- filename: openapi.json
  format: json
  label: RHEL 8 Subscription Management API
  slug: subscription-management-api
  spec_type: OpenAPI
  url: https://api.access.redhat.com/management/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Insights API
  slug: insights-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/insights/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Image Builder API
  slug: image-builder-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/image-builder/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Patch Management API
  slug: patch-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/patch/v3/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Vulnerability Management API
  slug: vulnerability-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/vulnerability/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Compliance API
  slug: compliance-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/compliance/v2/openapi.json
- filename: red-hat-enterprise-linux-8-security-data-openapi.yml
  format: yaml
  label: RHEL 8 Security Data API
  slug: security-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/openapi/red-hat-enterprise-linux-8-security-data-openapi.yml
- filename: openapi.json
  format: json
  label: RHEL 8 Host Inventory API
  slug: host-inventory-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/inventory/v1/openapi.json
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/red-hat-enterprise-linux-8-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/json-ld/red-hat-enterprise-linux-8-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Red Hat Enterprise Linux 8 from Red Hat Enterprise Linux 8.
layout: jsonld
name: Red Hat Enterprise Linux 8 Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: nvd
  uri: https://nvd.nist.gov/vuln/detail/
- prefix: rhel
  uri: https://access.redhat.com/security/
properties:
- container: ''
  name: CVE
  type: schema:Thing
- container: ''
  name: SecurityAdvisory
  type: schema:Article
- container: ''
  name: SoftwarePackage
  type: schema:SoftwareApplication
- container: ''
  name: CVE_id
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: cvss_score
  type: decimal
- container: ''
  name: cvss3_score
  type: decimal
- container: ''
  name: public_date
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: cwe
  type: string
- container: ''
  name: advisory_id
  type: string
- container: ''
  name: product_name
  type: string
- container: ''
  name: package_name
  type: string
- container: ''
  name: arch
  type: string
- container: ''
  name: errata
  type: schema:Article
- container: ''
  name: subscription
  type: schema:Offer
- container: ''
  name: system
  type: schema:ComputerLanguage
- container: ''
  name: hostId
  type: string
- container: ''
  name: organization
  type: schema:Organization
property_count: 19
provider_name: Red Hat Enterprise Linux 8
provider_slug: red-hat-enterprise-linux-8
slug: red-hat-enterprise-linux-8-context
source_filename: red-hat-enterprise-linux-8-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"nvd\": \"https://nvd.nist.gov/vuln/detail/\",\n    \"rhel\": \"https://access.redhat.com/security/\",\n    \"CVE\": {\n      \"@id\": \"schema:Thing\",\n      \"@type\": \"schema:Thing\"\n    },\n    \"SecurityAdvisory\": {\n      \"@id\": \"schema:Article\",\n      \"@type\": \"schema:Article\"\n    },\n    \"SoftwarePackage\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"CVE_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvss_score\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"cvss3_score\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"public_date\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"cwe\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advisory_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"package_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arch\": {\n      \"@id\": \"schema:processorRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errata\": {\n      \"@id\": \"schema:Article\",\n      \"@type\": \"schema:Article\"\n    },\n    \"subscription\": {\n      \"@id\": \"schema:Offer\",\n     \
  \ \"@type\": \"schema:Offer\"\n    },\n    \"system\": {\n      \"@id\": \"schema:ComputerLanguage\",\n      \"@type\": \"schema:ComputerLanguage\"\n    },\n    \"hostId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"schema:Organization\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/json-ld/red-hat-enterprise-linux-8-context.jsonld
tags:
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
- JSON-LD
- Linked Data
- Semantic Web
---
