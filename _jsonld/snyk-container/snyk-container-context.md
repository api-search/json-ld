---
api_specs:
- filename: snyk-container-openapi.yml
  format: yaml
  label: Snyk Container
  slug: snyk-container
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snyk-container/refs/heads/main/openapi/snyk-container-openapi.yml
class_count: 26
classes:
- ContainerProject
- VulnerabilityIssue
- Severity
- Remedy
- Target
- SBOM
- Organization
- name
- description
- created
- updated
- status
- severity
- imageTag
- imageDigest
- registry
- projectType
- recurringFrequency
- packageUrl
- sbomFormat
- remedyType
- upgradePackage
- containerRegistryImage
- kubernetesMonitor
- helmRelease
- dockerfileFromScm
context_file: json-ld/snyk-container-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snyk-container/refs/heads/main/json-ld/snyk-container-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snyk Container from Snyk Container.
layout: jsonld
name: Snyk Container Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: snyk
  uri: https://snyk.io/ontology/
- prefix: cve
  uri: https://cve.mitre.org/
- prefix: cvss
  uri: https://www.first.org/cvss/
- prefix: k8s
  uri: https://kubernetes.io/
- prefix: oci
  uri: https://opencontainers.org/
- prefix: spdx
  uri: https://spdx.org/
- prefix: cyclonedx
  uri: https://cyclonedx.org/
properties:
- container: ''
  name: ContainerImage
  type: reference
- container: ''
  name: cveId
  type: reference
property_count: 2
provider_name: Snyk Container
provider_slug: snyk-container
slug: snyk-container-context
source_filename: snyk-container-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"snyk\": \"https://snyk.io/ontology/\",\n    \"cve\": \"https://cve.mitre.org/\",\n    \"cvss\": \"https://www.first.org/cvss/\",\n    \"k8s\": \"https://kubernetes.io/\",\n    \"oci\": \"https://opencontainers.org/\",\n    \"spdx\": \"https://spdx.org/\",\n    \"cyclonedx\": \"https://cyclonedx.org/\",\n\n    \"ContainerProject\": \"snyk:ContainerProject\",\n    \"ContainerImage\": {\n      \"@id\": \"oci:Image\",\n      \"@type\": \"@id\"\n    },\n    \"VulnerabilityIssue\": \"snyk:VulnerabilityIssue\",\n    \"Severity\": \"snyk:Severity\",\n    \"Remedy\": \"snyk:Remedy\",\n    \"Target\": \"snyk:Target\",\n    \"SBOM\": \"snyk:SBOM\",\n    \"Organization\": \"schema:Organization\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": \"schema:dateCreated\",\n    \"updated\": \"schema:dateModified\",\n    \"status\": \"schema:status\"\
  ,\n    \"severity\": \"cvss:severity\",\n    \"cveId\": {\n      \"@id\": \"cve:identifier\",\n      \"@type\": \"@id\"\n    },\n    \"imageTag\": \"oci:imageTag\",\n    \"imageDigest\": \"oci:imageDigest\",\n    \"registry\": \"oci:registry\",\n    \"projectType\": \"snyk:projectType\",\n    \"recurringFrequency\": \"snyk:recurringFrequency\",\n    \"packageUrl\": \"schema:url\",\n    \"sbomFormat\": \"snyk:sbomFormat\",\n    \"remedyType\": \"snyk:remedyType\",\n    \"upgradePackage\": \"snyk:upgradePackage\",\n\n    \"containerRegistryImage\": \"snyk:ContainerRegistryImageType\",\n    \"kubernetesMonitor\": \"k8s:monitor\",\n    \"helmRelease\": \"k8s:helmRelease\",\n    \"dockerfileFromScm\": \"snyk:DockerfileFromScm\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snyk-container/refs/heads/main/json-ld/snyk-container-context.jsonld
tags:
- Container Images
- Containers
- Kubernetes
- Security
- Vulnerability Management
- DevSecOps
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
