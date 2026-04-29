---
api_specs:
- filename: cisa-kev-openapi.yml
  format: yaml
  label: CISA Known Exploited Vulnerabilities (KEV) Catalog
  slug: kev
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/openapi/cisa-kev-openapi.yml
class_count: 18
classes:
- KevVulnerability
- CVE
- CWE
- CybersecurityAdvisory
- AutomatedIndicatorSharing
- BindingOperationalDirective
- id
- type
- cveID
- vendorProject
- product
- vulnerabilityName
- dateAdded
- shortDescription
- requiredAction
- dueDate
- knownRansomwareCampaignUse
- cwes
context_file: json-ld/cisa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/json-ld/cisa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisa from Cybersecurity and Infrastructure Security Agency.
layout: jsonld
name: Cisa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cisa
  uri: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/vocabulary/cisa-vocabulary.yml#
properties: []
property_count: 0
provider_name: Cybersecurity and Infrastructure Security Agency
provider_slug: cybersecurity-and-infrastructure-security-agency
slug: cisa-context
source_filename: cisa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/vocabulary/cisa-vocabulary.yml#\",\n    \"schema\": \"https://schema.org/\",\n    \"cisa\": \"https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/vocabulary/cisa-vocabulary.yml#\",\n    \"KevVulnerability\": \"cisa:KevVulnerability\",\n    \"CVE\": \"cisa:CVE\",\n    \"CWE\": \"cisa:CWE\",\n    \"CybersecurityAdvisory\": \"cisa:CybersecurityAdvisory\",\n    \"AutomatedIndicatorSharing\": \"cisa:AutomatedIndicatorSharing\",\n    \"BindingOperationalDirective\": \"cisa:BindingOperationalDirective\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"cveID\": \"cisa:cveID\",\n    \"vendorProject\": \"cisa:vendorProject\",\n    \"product\": \"cisa:product\",\n    \"vulnerabilityName\": \"schema:name\",\n    \"dateAdded\": \"schema:dateCreated\"\
  ,\n    \"shortDescription\": \"schema:description\",\n    \"requiredAction\": \"cisa:requiredAction\",\n    \"dueDate\": \"schema:expires\",\n    \"knownRansomwareCampaignUse\": \"cisa:knownRansomwareCampaignUse\",\n    \"cwes\": \"cisa:cwes\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/json-ld/cisa-context.jsonld
tags:
- Advisories
- AIS
- Binding Operational Directive
- CSAF
- CVE
- CWE
- Cybersecurity
- Federal Government
- Government
- ICS-CERT
- Information Sharing
- KEV
- Known Exploited Vulnerabilities
- Risk Management
- Security
- STIX
- TAXII
- Threat Intelligence
- Vulnerability Management
- JSON-LD
- Linked Data
- Semantic Web
---
