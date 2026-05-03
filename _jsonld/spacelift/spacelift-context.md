---
class_count: 10
classes:
- Stack
- Run
- Policy
- Context
- WorkerPool
- Module
- Blueprint
- id
- name
- description
context_file: json-ld/spacelift-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-ld/spacelift-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spacelift from Spacelift.
layout: jsonld
name: Spacelift Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spacelift
  uri: https://spacelift.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: labels
  type: ''
- container: ''
  name: repository
  type: ''
- container: ''
  name: branch
  type: ''
- container: ''
  name: projectRoot
  type: ''
- container: ''
  name: provider
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: space
  type: ''
- container: ''
  name: workerPool
  type: ''
- container: ''
  name: driftDetection
  type: boolean
- container: ''
  name: autoApply
  type: boolean
- container: ''
  name: administrative
  type: boolean
- container: ''
  name: lockedAt
  type: dateTime
- container: ''
  name: lockedBy
  type: ''
- container: ''
  name: vendorConfig
  type: ''
property_count: 15
provider_name: Spacelift
provider_slug: spacelift
slug: spacelift-context
source_filename: spacelift-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spacelift\": \"https://spacelift.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Stack\": \"spacelift:Stack\",\n    \"Run\": \"spacelift:Run\",\n    \"Policy\": \"spacelift:Policy\",\n    \"Context\": \"spacelift:Context\",\n    \"WorkerPool\": \"spacelift:WorkerPool\",\n    \"Module\": \"spacelift:Module\",\n    \"Blueprint\": \"spacelift:Blueprint\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"labels\": {\n      \"@id\": \"schema:keywords\"\n    },\n    \"repository\": {\n      \"@id\": \"spacelift:repository\"\n    },\n    \"branch\": {\n      \"@id\": \"spacelift:branch\"\n    },\n    \"projectRoot\": {\n      \"@id\": \"spacelift:projectRoot\"\n    },\n    \"provider\": {\n      \"@id\"\
  : \"spacelift:vcsProvider\"\n    },\n    \"state\": {\n      \"@id\": \"spacelift:state\"\n    },\n    \"space\": {\n      \"@id\": \"spacelift:space\"\n    },\n    \"workerPool\": {\n      \"@id\": \"spacelift:workerPool\"\n    },\n    \"driftDetection\": {\n      \"@id\": \"spacelift:driftDetection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"autoApply\": {\n      \"@id\": \"spacelift:autoApply\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"administrative\": {\n      \"@id\": \"spacelift:administrative\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lockedAt\": {\n      \"@id\": \"spacelift:lockedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lockedBy\": {\n      \"@id\": \"spacelift:lockedBy\"\n    },\n    \"vendorConfig\": {\n      \"@id\": \"spacelift:vendorConfig\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-ld/spacelift-context.jsonld
tags:
- Infrastructure as Code
- FinOps
- DevOps
- Platform Engineering
- Terraform
- GitOps
- JSON-LD
- Linked Data
- Semantic Web
---
