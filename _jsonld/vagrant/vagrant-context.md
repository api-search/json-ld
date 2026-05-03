---
api_specs:
- filename: vagrant-cloud-api-openapi.yml
  format: yaml
  label: Vagrant Cloud API
  slug: vagrant-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-cloud-api-openapi.yml
- filename: vagrant-hcp-vagrant-box-registry-openapi.yml
  format: yaml
  label: HCP Vagrant Box Registry API
  slug: vagrant-hcp-box-registry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-hcp-vagrant-box-registry-openapi.yml
class_count: 0
classes: []
context_file: json-ld/vagrant-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-ld/vagrant-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vagrant from Vagrant.
layout: jsonld
name: Vagrant Context
namespaces:
- prefix: vagrant
  uri: https://app.vagrantup.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Box
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: Provider
  type: ''
- container: ''
  name: Registry
  type: ''
property_count: 4
provider_name: Vagrant
provider_slug: vagrant
slug: vagrant-context
source_filename: vagrant-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vagrant\": \"https://app.vagrantup.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Box\": {\n      \"@id\": \"vagrant:Box\",\n      \"@context\": {\n        \"tag\": \"vagrant:tag\",\n        \"username\": \"schema:author\",\n        \"name\": \"schema:name\",\n        \"private\": \"vagrant:isPrivate\",\n        \"downloads\": \"schema:interactionCount\",\n        \"shortDescription\": \"schema:abstract\",\n        \"description\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"versions\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        },\n       \
  \ \"currentVersion\": {\n          \"@id\": \"vagrant:currentVersion\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Version\": {\n      \"@id\": \"vagrant:Version\",\n      \"@context\": {\n        \"version\": \"schema:version\",\n        \"status\": \"vagrant:releaseStatus\",\n        \"description\": \"schema:description\",\n        \"downloads\": \"schema:interactionCount\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"providers\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Provider\": {\n      \"@id\": \"vagrant:Provider\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"hosted\": \"vagrant:isHosted\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:downloadUrl\",\n          \"@type\": \"@id\"\n        },\n        \"checksumType\": \"vagrant:checksumType\",\n        \"checksum\": \"vagrant:checksum\",\n        \"architecture\": \"vagrant:architecture\",\n        \"defaultArchitecture\": \"vagrant:isDefaultArchitecture\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Registry\": {\n      \"@id\": \"vagrant:Registry\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-ld/vagrant-context.jsonld
tags:
- DevOps
- Virtualization
- Development Environments
- Boxes
- Cloud
- HashiCorp
- Infrastructure
- JSON-LD
- Linked Data
- Semantic Web
---
