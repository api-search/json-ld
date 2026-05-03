---
class_count: 0
classes: []
context_file: json-ld/cloudera-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudera/refs/heads/main/json-ld/cloudera-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudera from Cloudera.
layout: jsonld
name: Cloudera Context
namespaces:
- prefix: cloudera
  uri: https://api.cloudera.com/ns/
- prefix: cdp
  uri: https://cloudera.com/cdp/
- prefix: cm
  uri: https://cloudera.github.io/cm_api/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Datalake
  type: ''
- container: ''
  name: Datahub
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Host
  type: ''
property_count: 7
provider_name: Cloudera
provider_slug: cloudera
slug: cloudera-context
source_filename: cloudera-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudera\": \"https://api.cloudera.com/ns/\",\n    \"cdp\": \"https://cloudera.com/cdp/\",\n    \"cm\": \"https://cloudera.github.io/cm_api/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Environment\": {\n      \"@id\": \"cdp:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"crn\": \"cdp:crn\",\n        \"status\": \"cdp:status\",\n        \"cloudPlatform\": \"cdp:cloud_platform\",\n        \"region\": \"cdp:region\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Datalake\": {\n      \"@id\": \"cdp:Datalake\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"crn\": \"cdp:crn\",\n        \"environmentName\": \"cdp:environment_name\",\n        \"status\": \"cdp:status\"\
  \n      }\n    },\n\n    \"Datahub\": {\n      \"@id\": \"cdp:Datahub\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"crn\": \"cdp:crn\",\n        \"environmentName\": \"cdp:environment_name\",\n        \"status\": \"cdp:status\",\n        \"clusterTemplate\": \"cdp:cluster_template\"\n      }\n    },\n\n    \"Cluster\": {\n      \"@id\": \"cm:Cluster\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"version\": \"cm:version\",\n        \"fullVersion\": \"cm:full_version\",\n        \"maintenanceMode\": \"cm:maintenance_mode\"\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"cm:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"serviceState\": \"cm:service_state\",\n        \"healthSummary\": \"cm:health_summary\"\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"cm:Role\",\n      \"@context\": {\n   \
  \     \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"hostRef\": \"cm:host_ref\",\n        \"roleState\": \"cm:role_state\"\n      }\n    },\n\n    \"Host\": {\n      \"@id\": \"cm:Host\",\n      \"@context\": {\n        \"hostId\": \"cm:host_id\",\n        \"ipAddress\": \"cm:ip_address\",\n        \"hostname\": \"schema:hostname\",\n        \"rackId\": \"cm:rack_id\",\n        \"totalPhysMemBytes\": \"cm:total_phys_mem_bytes\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudera/refs/heads/main/json-ld/cloudera-context.jsonld
tags:
- Big Data
- Data Engineering
- Data Lakehouse
- Data Platform
- Data Warehouse
- Hadoop
- Hybrid Cloud
- Machine Learning
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
