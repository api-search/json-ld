---
api_specs:
- filename: trivy-server-openapi.yml
  format: yaml
  label: Trivy Server API
  slug: trivy-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/openapi/trivy-server-openapi.yml
class_count: 25
classes:
- VulnerabilityReport
- Vulnerability
- Misconfiguration
- Secret
- SbomReport
- ComplianceReport
- artifactName
- artifactType
- vulnerabilityId
- severity
- pkgName
- pkgVersion
- fixedVersion
- cvss
- scanTarget
- scanClass
- schemaVersion
- publishedDate
- references
- SoftwareApplication
- identifier
- name
- description
- url
- license
context_file: json-ld/trivy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/json-ld/trivy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trivy from Trivy.
layout: jsonld
name: Trivy Context
namespaces:
- prefix: trivy
  uri: https://trivy.dev/vocab#
- prefix: aqua
  uri: https://aquasecurity.github.io/vocab#
properties: []
property_count: 0
provider_name: Trivy
provider_slug: trivy
slug: trivy-context
source_filename: trivy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"trivy\": \"https://trivy.dev/vocab#\",\n    \"aqua\": \"https://aquasecurity.github.io/vocab#\",\n    \"VulnerabilityReport\": \"trivy:VulnerabilityReport\",\n    \"Vulnerability\": \"trivy:Vulnerability\",\n    \"Misconfiguration\": \"trivy:Misconfiguration\",\n    \"Secret\": \"trivy:Secret\",\n    \"SbomReport\": \"trivy:SbomReport\",\n    \"ComplianceReport\": \"trivy:ComplianceReport\",\n    \"artifactName\": \"trivy:artifactName\",\n    \"artifactType\": \"trivy:artifactType\",\n    \"vulnerabilityId\": \"trivy:vulnerabilityId\",\n    \"severity\": \"trivy:severity\",\n    \"pkgName\": \"trivy:pkgName\",\n    \"pkgVersion\": \"trivy:pkgVersion\",\n    \"fixedVersion\": \"trivy:fixedVersion\",\n    \"cvss\": \"trivy:cvss\",\n    \"scanTarget\": \"trivy:scanTarget\",\n    \"scanClass\": \"trivy:scanClass\",\n    \"schemaVersion\": \"schema:version\",\n    \"publishedDate\": \"schema:datePublished\",\n\
  \    \"references\": \"schema:citation\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"identifier\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"license\": \"schema:license\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/json-ld/trivy-context.jsonld
tags:
- Containers
- Kubernetes
- SBOM
- Security
- Vulnerability Scanning
- Open Source
- DevSecOps
- Cloud Security
- JSON-LD
- Linked Data
- Semantic Web
---
