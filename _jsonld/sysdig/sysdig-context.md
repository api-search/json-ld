---
api_specs:
- filename: sysdig-monitor-openapi.yml
  format: yaml
  label: Sysdig Monitor
  slug: sysdig-monitor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-monitor-openapi.yml
- filename: sysdig-secure-openapi.yml
  format: yaml
  label: Sysdig Secure
  slug: sysdig-secure
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-secure-openapi.yml
class_count: 31
classes:
- Alert
- Dashboard
- Event
- Policy
- FalcoRule
- Vulnerability
- ComplianceTask
- ScannedImage
- Team
- NotificationChannel
- name
- description
- severity
- enabled
- condition
- type
- tags
- imageId
- fullTag
- registry
- repository
- analysisStatus
- vulnCount
- cvss
- package
- fixVersion
- timestamp
- scope
- filter
- teamId
- url
context_file: json-ld/sysdig-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/json-ld/sysdig-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sysdig from Sysdig.
layout: jsonld
name: Sysdig Context
namespaces:
- prefix: sysdig
  uri: https://sysdig.com/vocabulary/
properties: []
property_count: 0
provider_name: Sysdig
provider_slug: sysdig
slug: sysdig-context
source_filename: sysdig-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sysdig\": \"https://sysdig.com/vocabulary/\",\n    \"Alert\": \"sysdig:Alert\",\n    \"Dashboard\": \"sysdig:Dashboard\",\n    \"Event\": \"sysdig:Event\",\n    \"Policy\": \"sysdig:Policy\",\n    \"FalcoRule\": \"sysdig:FalcoRule\",\n    \"Vulnerability\": \"sysdig:Vulnerability\",\n    \"ComplianceTask\": \"sysdig:ComplianceTask\",\n    \"ScannedImage\": \"sysdig:ScannedImage\",\n    \"Team\": \"sysdig:Team\",\n    \"NotificationChannel\": \"sysdig:NotificationChannel\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"severity\": \"sysdig:severity\",\n    \"enabled\": \"sysdig:enabled\",\n    \"condition\": \"sysdig:condition\",\n    \"type\": \"schema:additionalType\",\n    \"tags\": \"schema:keywords\",\n    \"imageId\": \"sysdig:imageId\",\n    \"fullTag\": \"sysdig:fullTag\",\n    \"registry\": \"sysdig:registry\",\n    \"repository\": \"sysdig:repository\",\n  \
  \  \"analysisStatus\": \"sysdig:analysisStatus\",\n    \"vulnCount\": \"sysdig:vulnCount\",\n    \"cvss\": \"sysdig:cvss\",\n    \"package\": \"schema:softwareVersion\",\n    \"fixVersion\": \"sysdig:fixVersion\",\n    \"timestamp\": \"schema:dateModified\",\n    \"scope\": \"sysdig:scope\",\n    \"filter\": \"sysdig:filter\",\n    \"teamId\": \"sysdig:teamId\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/json-ld/sysdig-context.jsonld
tags:
- Cloud Security
- Containers
- Kubernetes
- Runtime Security
- Security
- Vulnerability Management
- Monitoring
- Observability
- CSPM
- Compliance
- JSON-LD
- Linked Data
- Semantic Web
---
