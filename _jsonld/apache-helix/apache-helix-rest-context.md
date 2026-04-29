---
api_specs:
- filename: apache-helix-rest-openapi.yml
  format: yaml
  label: Apache Helix REST API
  slug: apache-helix-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/openapi/apache-helix-rest-openapi.yml
class_count: 16
classes:
- id
- controller
- paused
- disabledInstances
- liveInstances
- hostName
- port
- enabled
- tags
- stateModelDefRef
- numPartitions
- replicas
- rebalanceMode
- instanceStateMap
- mapFields
- name
context_file: json-ld/apache-helix-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/json-ld/apache-helix-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Helix Rest from Apache Helix.
layout: jsonld
name: Apache Helix Rest Context
namespaces:
- prefix: helix
  uri: https://helix.apache.org/vocab#
properties: []
property_count: 0
provider_name: Apache Helix
provider_slug: apache-helix
slug: apache-helix-rest-context
source_filename: apache-helix-rest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"helix\": \"https://helix.apache.org/vocab#\",\n    \"id\": \"schema:identifier\",\n    \"controller\": \"helix:controller\",\n    \"paused\": \"helix:paused\",\n    \"disabledInstances\": \"helix:disabledInstances\",\n    \"liveInstances\": \"helix:liveInstances\",\n    \"hostName\": \"schema:hostName\",\n    \"port\": \"schema:portNumber\",\n    \"enabled\": \"helix:enabled\",\n    \"tags\": \"schema:keywords\",\n    \"stateModelDefRef\": \"helix:stateModelDefRef\",\n    \"numPartitions\": \"helix:numPartitions\",\n    \"replicas\": \"helix:replicas\",\n    \"rebalanceMode\": \"helix:rebalanceMode\",\n    \"instanceStateMap\": \"helix:instanceStateMap\",\n    \"mapFields\": \"helix:mapFields\",\n    \"name\": \"schema:name\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/json-ld/apache-helix-rest-context.jsonld
tags:
- Apache
- Cluster Management
- Distributed Systems
- Open Source
- Partitioning
- Replication
- JSON-LD
- Linked Data
- Semantic Web
---
