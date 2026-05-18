---
class_count: 0
classes: []
context_file: json-ld/cloud-native-buildpacks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloud-native-buildpacks/refs/heads/main/json-ld/cloud-native-buildpacks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloud Native Buildpacks from Cloud Native Buildpacks.
layout: jsonld
name: Cloud Native Buildpacks Context
namespaces:
- prefix: cnb
  uri: https://buildpacks.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Buildpack
  type: ''
- container: ''
  name: Builder
  type: ''
- container: ''
  name: Stack
  type: ''
- container: ''
  name: BuildPlan
  type: ''
- container: ''
  name: Layer
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: LifecyclePhase
  type: ''
property_count: 7
provider_name: Cloud Native Buildpacks
provider_slug: cloud-native-buildpacks
slug: cloud-native-buildpacks-context
source_filename: cloud-native-buildpacks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cnb\": \"https://buildpacks.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Buildpack\": {\n      \"@id\": \"cnb:Buildpack\",\n      \"@context\": {\n        \"id\": \"cnb:id\",\n        \"version\": \"schema:softwareVersion\",\n        \"name\": \"schema:name\",\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"apiVersion\": \"cnb:api_version\",\n        \"stacks\": {\n          \"@id\": \"cnb:stacks\",\n          \"@container\": \"@set\"\n        },\n        \"license\": \"schema:license\"\n      }\n    },\n\n    \"Builder\": {\n      \"@id\": \"cnb:Builder\",\n      \"@context\": {\n        \"id\": \"cnb:id\",\n        \"name\": \"schema:name\",\n        \"image\": \"cnb:image\",\n        \"stack\": \"cnb:stack\",\n        \"buildpacks\": {\n \
  \         \"@id\": \"cnb:buildpacks\",\n          \"@container\": \"@set\"\n        },\n        \"lifecycle\": \"cnb:lifecycle\"\n      }\n    },\n\n    \"Stack\": {\n      \"@id\": \"cnb:Stack\",\n      \"@context\": {\n        \"id\": \"cnb:id\",\n        \"buildImage\": \"cnb:build_image\",\n        \"runImage\": \"cnb:run_image\"\n      }\n    },\n\n    \"BuildPlan\": {\n      \"@id\": \"cnb:BuildPlan\",\n      \"@context\": {\n        \"provides\": {\n          \"@id\": \"cnb:provides\",\n          \"@container\": \"@set\"\n        },\n        \"requires\": {\n          \"@id\": \"cnb:requires\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Layer\": {\n      \"@id\": \"cnb:Layer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"build\": \"cnb:build\",\n        \"launch\": \"cnb:launch\",\n        \"cache\": \"cnb:cache\",\n        \"metadata\": \"cnb:metadata\"\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"cnb:Image\",\n\
  \      \"@context\": {\n        \"reference\": \"cnb:reference\",\n        \"digest\": \"cnb:digest\",\n        \"labels\": \"cnb:labels\"\n      }\n    },\n\n    \"LifecyclePhase\": {\n      \"@id\": \"cnb:LifecyclePhase\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloud-native-buildpacks/refs/heads/main/json-ld/cloud-native-buildpacks-context.jsonld
tags:
- Buildpacks
- CNCF
- Containers
- Images
- OCI
- Open Source
- Platform
- Reproducible Builds
- JSON-LD
- Linked Data
- Semantic Web
---
