---
class_count: 12
classes:
- imageId
- name
- version
- source
- format
- size
- createdAt
- sha256
- instanceId
- status
- startedAt
- stoppedAt
context_file: json-ld/apptainer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apptainer/refs/heads/main/json-ld/apptainer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apptainer from Apptainer.
layout: jsonld
name: Apptainer Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: apptainer
  uri: https://apptainer.org/vocab#
properties: []
property_count: 0
provider_name: Apptainer
provider_slug: apptainer
slug: apptainer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"apptainer\": \"https://apptainer.org/vocab#\",\n    \"imageId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"version\": \"schema:version\",\n    \"source\": \"schema:url\",\n    \"format\": \"schema:encodingFormat\",\n    \"size\": \"schema:contentSize\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"sha256\": \"apptainer:sha256\",\n    \"instanceId\": \"schema:identifier\",\n    \"status\": \"apptainer:status\",\n    \"startedAt\": \"schema:startDate\",\n    \"stoppedAt\": \"schema:endDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apptainer/refs/heads/main/json-ld/apptainer-context.jsonld
tags:
- Containers
- HPC
- Scientific Computing
- Open Source
- Linux Foundation
- JSON-LD
- Linked Data
- Semantic Web
---
