---
api_specs:
- filename: helm-chart-repository-openapi.yml
  format: yaml
  label: Helm Chart Repository API
  slug: chart-repository-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/helm/refs/heads/main/openapi/helm-chart-repository-openapi.yml
class_count: 0
classes: []
context_file: json-ld/helm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/helm/refs/heads/main/json-ld/helm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Helm from Helm.
layout: jsonld
name: Helm Context
namespaces:
- prefix: helm
  uri: https://helm.sh/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: spdx
  uri: http://spdx.org/rdf/terms#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
properties:
- container: ''
  name: Chart
  type: ''
- container: ''
  name: ChartRepository
  type: ''
- container: ''
  name: ChartVersion
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: Maintainer
  type: ''
- container: ''
  name: Dependency
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: license
  type: string
property_count: 11
provider_name: Helm
provider_slug: helm
slug: helm-context
source_filename: helm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://helm.sh/schemas/\",\n    \"helm\": \"https://helm.sh/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"spdx\": \"http://spdx.org/rdf/terms#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n\n    \"Chart\": {\n      \"@id\": \"helm:Chart\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appVersion\": {\n          \"@id\": \"helm:appVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiVersion\": {\n          \"@id\": \"helm:apiVersion\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"kubeVersion\": {\n          \"@id\": \"helm:kubeVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"helm:chartType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"keywords\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"home\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"sources\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"icon\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"deprecated\": {\n          \"@id\": \"helm:deprecated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"maintainers\": {\n          \"@id\": \"schema:maintainer\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"dependencies\": {\n          \"@id\": \"helm:dependencies\",\n          \"@container\": \"@set\"\n        },\n        \"annotations\": {\n          \"@id\": \"helm:annotations\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"ChartRepository\": {\n      \"@id\": \"helm:ChartRepository\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"generated\": {\n          \"@id\": \"prov:generatedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"entries\": {\n          \"@id\": \"helm:entries\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"ChartVersion\": {\n      \"@id\": \"helm:ChartVersion\",\n      \"@context\": {\n        \"urls\": {\n          \"@id\": \"schema:downloadUrl\"\
  ,\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"digest\": {\n          \"@id\": \"spdx:checksum\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"helm:Release\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namespace\": {\n          \"@id\": \"helm:namespace\",\n          \"@type\": \"xsd:string\"\n        },\n        \"revision\": {\n          \"@id\": \"helm:revision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"helm:releaseStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstDeployed\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastDeployed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"notes\": {\n          \"@id\": \"helm:releaseNotes\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Plugin\": {\n      \"@id\": \"helm:Plugin\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"helm:pluginUsage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"command\": {\n          \"@id\": \"helm:pluginCommand\",\n          \"@type\": \"xsd:string\"\n      \
  \  }\n      }\n    },\n\n    \"Maintainer\": {\n      \"@id\": \"foaf:Person\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"foaf:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"foaf:mbox\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"foaf:homepage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Dependency\": {\n      \"@id\": \"helm:Dependency\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"repository\": {\n          \"@id\": \"helm:repository\",\n          \"@type\": \"@id\"\n        },\n        \"condition\": {\n          \"@id\": \"helm:condition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alias\": {\n       \
  \   \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"spdx:licenseDeclared\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/helm/refs/heads/main/json-ld/helm-context.jsonld
tags:
- Charts
- Cloud Native
- Container Orchestration
- DevOps
- Kubernetes
- Package Manager
- JSON-LD
- Linked Data
- Semantic Web
---
