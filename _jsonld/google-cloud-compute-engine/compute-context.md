---
api_specs:
- filename: compute-openapi.yml
  format: yaml
  label: Google Compute Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-compute-engine/refs/heads/main/openapi/compute-openapi.yml
class_count: 11
classes:
- Instance
- Disk
- Network
- Firewall
- name
- description
- id
- status
- zone
- machineType
- selfLink
context_file: json-ld/compute-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-compute-engine/refs/heads/main/json-ld/compute-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Compute from Google Cloud Compute Engine.
layout: jsonld
name: Compute Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gcp
  uri: https://cloud.google.com/schema#
properties:
- container: ''
  name: creationTimestamp
  type: dateTime
- container: ''
  name: sizeGb
  type: string
- container: ''
  name: priority
  type: integer
property_count: 3
provider_name: Google Cloud Compute Engine
provider_slug: google-cloud-compute-engine
slug: compute-context
source_filename: compute-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/compute/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"Instance\": \"gcp:ComputeInstance\",\n    \"Disk\": \"gcp:ComputeDisk\",\n    \"Network\": \"gcp:ComputeNetwork\",\n    \"Firewall\": \"gcp:ComputeFirewall\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"schema:identifier\",\n    \"status\": \"gcp:status\",\n    \"zone\": \"gcp:zone\",\n    \"machineType\": \"gcp:machineType\",\n    \"selfLink\": \"schema:url\",\n    \"creationTimestamp\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sizeGb\": {\n      \"@id\": \"gcp:sizeGb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"gcp:priority\",\n      \"@type\": \"xsd:integer\"\
  \n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-compute-engine/refs/heads/main/json-ld/compute-context.jsonld
tags:
- Compute
- Google Cloud
- IaaS
- Infrastructure
- Virtual Machines
- JSON-LD
- Linked Data
- Semantic Web
---
