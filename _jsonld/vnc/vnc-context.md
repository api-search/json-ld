---
api_specs:
- filename: vnc-cloud-openapi.yml
  format: yaml
  label: VNC Cloud API
  slug: vnc-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vnc/refs/heads/main/openapi/vnc-cloud-openapi.yml
class_count: 13
classes:
- cloudAddress
- cloudPassword
- allowedActions
- groups
- accessControl
- ReadinessStatus
- RemoteAccess
- SoftwareApplication
- ComputerNetwork
- name
- description
- identifier
- url
context_file: json-ld/vnc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vnc/refs/heads/main/json-ld/vnc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vnc from VNC.
layout: jsonld
name: Vnc Context
namespaces:
- prefix: vnc
  uri: https://www.realvnc.com/ns/
properties:
- container: ''
  name: VNCCloudAddress
  type: reference
property_count: 1
provider_name: VNC
provider_slug: vnc
slug: vnc-context
source_filename: vnc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vnc\": \"https://www.realvnc.com/ns/\",\n    \"cloudAddress\": \"vnc:cloudAddress\",\n    \"cloudPassword\": \"vnc:cloudPassword\",\n    \"allowedActions\": \"vnc:allowedActions\",\n    \"groups\": \"vnc:groups\",\n    \"accessControl\": \"vnc:accessControl\",\n    \"ReadinessStatus\": \"vnc:ReadinessStatus\",\n    \"RemoteAccess\": \"vnc:RemoteAccess\",\n    \"VNCCloudAddress\": {\n      \"@id\": \"vnc:VNCCloudAddress\",\n      \"@type\": \"@id\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"ComputerNetwork\": \"schema:ComputerNetwork\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"identifier\": \"schema:identifier\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vnc/refs/heads/main/json-ld/vnc-context.jsonld
tags:
- Remote Desktop
- Remote Access
- VNC
- Networking
- Screen Sharing
- JSON-LD
- Linked Data
- Semantic Web
---
