---
api_specs:
- filename: openssf-osv-openapi.yml
  format: yaml
  label: OSV (Open Source Vulnerabilities) API
  slug: osv-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/openapi/openssf-osv-openapi.yml
- filename: openssf-scorecard-openapi.yml
  format: yaml
  label: OpenSSF Scorecard API
  slug: scorecard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/openapi/openssf-scorecard-openapi.yml
class_count: 7
classes:
- id
- modified
- published
- summary
- details
- name
- url
context_file: json-ld/openssf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/json-ld/openssf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openssf from OpenSSF.
layout: jsonld
name: Openssf Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Vulnerability
  uri: https://openssf.org/ns#Vulnerability
- prefix: Package
  uri: https://openssf.org/ns#Package
- prefix: ScorecardResult
  uri: https://openssf.org/ns#ScorecardResult
- prefix: ScorecardCheck
  uri: https://openssf.org/ns#ScorecardCheck
- prefix: withdrawn
  uri: https://openssf.org/ns#withdrawn
- prefix: aliases
  uri: https://openssf.org/ns#aliases
- prefix: related
  uri: https://openssf.org/ns#related
- prefix: severity
  uri: https://openssf.org/ns#severity
- prefix: affected
  uri: https://openssf.org/ns#affected
- prefix: package
  uri: https://openssf.org/ns#package
- prefix: ecosystem
  uri: https://openssf.org/ns#ecosystem
- prefix: purl
  uri: https://openssf.org/ns#purl
- prefix: ranges
  uri: https://openssf.org/ns#ranges
- prefix: versions
  uri: https://openssf.org/ns#versions
- prefix: references
  uri: https://openssf.org/ns#references
- prefix: score
  uri: https://openssf.org/ns#score
- prefix: checks
  uri: https://openssf.org/ns#checks
- prefix: scorecard
  uri: https://openssf.org/ns#scorecard
- prefix: repo
  uri: https://openssf.org/ns#repository
- prefix: commit
  uri: https://openssf.org/ns#commit
- prefix: documentation
  uri: https://openssf.org/ns#documentation
properties: []
property_count: 0
provider_name: OpenSSF
provider_slug: openssf
slug: openssf-context
source_filename: openssf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://openssf.org/ns#\",\n    \"schema\": \"https://schema.org/\",\n    \"Vulnerability\": \"https://openssf.org/ns#Vulnerability\",\n    \"Package\": \"https://openssf.org/ns#Package\",\n    \"ScorecardResult\": \"https://openssf.org/ns#ScorecardResult\",\n    \"ScorecardCheck\": \"https://openssf.org/ns#ScorecardCheck\",\n    \"id\": \"@id\",\n    \"modified\": \"schema:dateModified\",\n    \"published\": \"schema:datePublished\",\n    \"withdrawn\": \"https://openssf.org/ns#withdrawn\",\n    \"summary\": \"schema:headline\",\n    \"details\": \"schema:description\",\n    \"aliases\": \"https://openssf.org/ns#aliases\",\n    \"related\": \"https://openssf.org/ns#related\",\n    \"severity\": \"https://openssf.org/ns#severity\",\n    \"affected\": \"https://openssf.org/ns#affected\",\n    \"package\": \"https://openssf.org/ns#package\",\n    \"ecosystem\": \"https://openssf.org/ns#ecosystem\",\n    \"name\": \"schema:name\",\n    \"\
  purl\": \"https://openssf.org/ns#purl\",\n    \"ranges\": \"https://openssf.org/ns#ranges\",\n    \"versions\": \"https://openssf.org/ns#versions\",\n    \"references\": \"https://openssf.org/ns#references\",\n    \"score\": \"https://openssf.org/ns#score\",\n    \"checks\": \"https://openssf.org/ns#checks\",\n    \"scorecard\": \"https://openssf.org/ns#scorecard\",\n    \"repo\": \"https://openssf.org/ns#repository\",\n    \"commit\": \"https://openssf.org/ns#commit\",\n    \"documentation\": \"https://openssf.org/ns#documentation\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/json-ld/openssf-context.jsonld
tags:
- Linux Foundation
- Open Source
- Security
- Supply Chain
- Vulnerabilities
- JSON-LD
- Linked Data
- Semantic Web
---
