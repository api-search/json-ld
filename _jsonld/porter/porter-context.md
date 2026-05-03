---
api_specs:
- filename: porter-bundle-openapi.yml
  format: yaml
  label: Porter Bundle API
  slug: porter-bundle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/openapi/porter-bundle-openapi.yml
class_count: 0
classes: []
context_file: json-ld/porter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/json-ld/porter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Porter from Porter.
layout: jsonld
name: Porter Context
namespaces:
- prefix: porter
  uri: https://porter.sh/vocabulary#
- prefix: cnab
  uri: https://cnab.io/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: Bundle
  type: ''
- container: ''
  name: Installation
  type: ''
- container: ''
  name: Run
  type: ''
- container: ''
  name: CredentialSet
  type: ''
- container: ''
  name: ParameterSet
  type: ''
- container: ''
  name: Parameter
  type: ''
- container: ''
  name: Credential
  type: ''
- container: ''
  name: Output
  type: ''
- container: ''
  name: Mixin
  type: ''
property_count: 9
provider_name: Porter
provider_slug: porter
slug: porter-context
source_filename: porter-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"porter\": \"https://porter.sh/vocabulary#\",\n    \"cnab\": \"https://cnab.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"Bundle\": {\n      \"@id\": \"cnab:Bundle\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"description\": \"schema:description\",\n        \"registry\": {\n          \"@id\": \"porter:registry\",\n          \"@type\": \"@id\"\n        },\n        \"reference\": {\n          \"@id\": \"porter:ociReference\",\n          \"@type\": \"@id\"\n        },\n        \"maintainers\": {\n          \"@id\": \"schema:maintainer\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": \"porter:labels\",\n        \"parameters\": {\n          \"@id\": \"porter:parameters\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"credentials\": {\n          \"@id\": \"porter:credentials\",\n          \"@container\": \"@set\"\n        },\n        \"outputs\": {\n          \"@id\": \"porter:outputs\",\n          \"@container\": \"@set\"\n        },\n        \"dependencies\": \"porter:dependencies\"\n      }\n    },\n\n    \"Installation\": {\n      \"@id\": \"porter:Installation\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"namespace\": \"porter:namespace\",\n        \"bundle\": {\n          \"@id\": \"porter:bundleReference\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"porter:installationStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"porter:labels\",\n       \
  \ \"credentialSets\": {\n          \"@id\": \"porter:credentialSets\",\n          \"@container\": \"@set\"\n        },\n        \"parameterSets\": {\n          \"@id\": \"porter:parameterSets\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Run\": {\n      \"@id\": \"porter:Run\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"installation\": {\n          \"@id\": \"porter:installation\",\n          \"@type\": \"@id\"\n        },\n        \"bundle\": {\n          \"@id\": \"porter:bundleReference\",\n          \"@type\": \"@id\"\n        },\n        \"action\": \"porter:bundleAction\",\n        \"result\": \"porter:runResult\",\n        \"startedAt\": {\n          \"@id\": \"prov:startedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"prov:endedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CredentialSet\": {\n      \"@id\": \"porter:CredentialSet\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"porter:namespace\",\n        \"credentials\": {\n          \"@id\": \"porter:credentialMappings\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": \"porter:labels\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ParameterSet\": {\n      \"@id\": \"porter:ParameterSet\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"porter:namespace\",\n        \"parameters\": {\n          \"@id\": \"porter:parameterMappings\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": \"porter:labels\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Parameter\": {\n      \"@id\": \"porter:Parameter\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"schema:DataType\",\n        \"required\": \"porter:isRequired\",\n        \"sensitive\": \"porter:isSensitive\",\n        \"default\": \"schema:defaultValue\"\n      }\n    },\n\n    \"Credential\": {\n      \"@id\": \"porter:Credential\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"required\": \"porter:isRequired\"\n      }\n    },\n\n    \"Output\": {\n      \"@id\": \"porter:Output\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"schema:DataType\",\n        \"sensitive\": \"porter:isSensitive\",\n        \"value\": \"rdf:value\"\
  \n      }\n    },\n\n    \"Mixin\": {\n      \"@id\": \"porter:Mixin\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/json-ld/porter-context.jsonld
tags:
- Cloud Native
- CNAB
- DevOps
- Kubernetes
- Package Manager
- JSON-LD
- Linked Data
- Semantic Web
---
