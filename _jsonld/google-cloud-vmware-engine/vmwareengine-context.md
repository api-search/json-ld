---
api_specs:
- filename: vmwareengine-openapi.yml
  format: yaml
  label: Google Cloud VMware Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-vmware-engine/refs/heads/main/openapi/vmwareengine-openapi.yml
class_count: 8
classes:
- PrivateCloud
- Cluster
- NetworkPolicy
- name
- description
- state
- managementCidr
- vmwareEngineNetwork
context_file: json-ld/vmwareengine-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-vmware-engine/refs/heads/main/json-ld/vmwareengine-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vmwareengine from Google Cloud VMware Engine.
layout: jsonld
name: Vmwareengine Context
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
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: nodeCount
  type: integer
property_count: 3
provider_name: Google Cloud VMware Engine
provider_slug: google-cloud-vmware-engine
slug: vmwareengine-context
source_filename: vmwareengine-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/vmware-engine/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"PrivateCloud\": \"gcp:VMwareEnginePrivateCloud\",\n    \"Cluster\": \"gcp:VMwareEngineCluster\",\n    \"NetworkPolicy\": \"gcp:VMwareEngineNetworkPolicy\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"state\": \"gcp:state\",\n    \"managementCidr\": \"gcp:managementCidr\",\n    \"vmwareEngineNetwork\": \"gcp:vmwareEngineNetwork\",\n    \"createTime\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nodeCount\": {\n      \"@id\": \"gcp:nodeCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-vmware-engine/refs/heads/main/json-ld/vmwareengine-context.jsonld
tags:
- Compute
- Google Cloud
- Migration
- Private Cloud
- Virtualization
- VMware
- JSON-LD
- Linked Data
- Semantic Web
---
