---
class_count: 0
classes: []
context_file: json-ld/cloud-foundry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloud-foundry/refs/heads/main/json-ld/cloud-foundry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloud Foundry from Cloud Foundry.
layout: jsonld
name: Cloud Foundry Context
namespaces:
- prefix: cf
  uri: https://v3-apidocs.cloudfoundry.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: App
  type: ''
- container: ''
  name: Process
  type: ''
- container: ''
  name: Build
  type: ''
- container: ''
  name: Droplet
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Domain
  type: ''
- container: ''
  name: ServiceInstance
  type: ''
- container: ''
  name: ServiceBroker
  type: ''
- container: ''
  name: Task
  type: ''
property_count: 11
provider_name: Cloud Foundry
provider_slug: cloud-foundry
slug: cloud-foundry-context
source_filename: cloud-foundry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cf\": \"https://v3-apidocs.cloudfoundry.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"cf:Organization\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"suspended\": \"cf:suspended\"\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"cf:Space\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"organizationGuid\": \"cf:organization_guid\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"App\": {\n      \"@id\": \"cf:App\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"state\": \"cf:state\",\n        \"lifecycle\": \"cf:lifecycle\",\n        \"spaceGuid\": \"cf:space_guid\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Process\": {\n      \"@id\": \"cf:Process\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"type\": \"cf:process_type\",\n        \"instances\": \"cf:instances\",\n        \"memoryInMb\": \"cf:memory_in_mb\",\n        \"diskInMb\": \"cf:disk_in_mb\",\n        \"command\": \"cf:command\"\n      }\n    },\n\n    \"Build\": {\n      \"@id\": \"cf:Build\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"state\": \"cf:state\"\
  ,\n        \"packageGuid\": \"cf:package_guid\",\n        \"dropletGuid\": \"cf:droplet_guid\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Droplet\": {\n      \"@id\": \"cf:Droplet\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"state\": \"cf:state\",\n        \"buildpacks\": {\n          \"@id\": \"cf:buildpacks\",\n          \"@container\": \"@set\"\n        },\n        \"stack\": \"cf:stack\"\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"cf:Route\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"host\": \"cf:host\",\n        \"path\": \"schema:urlTemplate\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"domainGuid\": \"cf:domain_guid\",\n        \"spaceGuid\": \"cf:space_guid\"\n      }\n    },\n\n    \"Domain\": {\n      \"@id\": \"cf:Domain\",\n      \"@context\": {\n    \
  \    \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"internal\": \"cf:internal\"\n      }\n    },\n\n    \"ServiceInstance\": {\n      \"@id\": \"cf:ServiceInstance\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"type\": \"cf:type\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ServiceBroker\": {\n      \"@id\": \"cf:ServiceBroker\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"cf:Task\",\n      \"@context\": {\n        \"guid\": \"cf:guid\",\n        \"name\": \"schema:name\",\n        \"command\": \"cf:command\",\n        \"state\": \"cf:state\",\n        \"memoryInMb\": \"cf:memory_in_mb\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloud-foundry/refs/heads/main/json-ld/cloud-foundry-context.jsonld
tags:
- Cloud Foundry Foundation
- Containers
- Multi-Cloud
- Open Source
- PaaS
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
