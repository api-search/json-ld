---
api_specs:
- filename: openapiSpec
  format: yaml
  label: Cisco Meraki Dashboard API
  slug: meraki-dashboard-api
  spec_type: OpenAPI
  url: https://api.meraki.com/api/v1/openapiSpec
- filename: openapi.yaml
  format: yaml
  label: Cisco Intersight API
  slug: intersight-api
  spec_type: OpenAPI
  url: https://intersight.com/apidocs/downloads/
class_count: 19
classes:
- Device
- Network
- Site
- Fabric
- Switch
- Router
- AccessPoint
- Server
- Tenant
- Organization
- name
- model
- serial
- firmware
- ipAddress
- macAddress
- status
- createdAt
- updatedAt
context_file: json-ld/cisco-hardware-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/json-ld/cisco-hardware-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Hardware from Cisco Hardware.
layout: jsonld
name: Cisco Hardware Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cisco
  uri: https://developer.cisco.com/vocab/
properties: []
property_count: 0
provider_name: Cisco Hardware
provider_slug: cisco-hardware
slug: cisco-hardware-context
source_filename: cisco-hardware-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/cisco-hardware/\",\n    \"schema\": \"https://schema.org/\",\n    \"cisco\": \"https://developer.cisco.com/vocab/\",\n    \"Device\": \"schema:Product\",\n    \"Network\": \"cisco:Network\",\n    \"Site\": \"cisco:Site\",\n    \"Fabric\": \"cisco:Fabric\",\n    \"Switch\": \"cisco:Switch\",\n    \"Router\": \"cisco:Router\",\n    \"AccessPoint\": \"cisco:AccessPoint\",\n    \"Server\": \"cisco:Server\",\n    \"Tenant\": \"cisco:Tenant\",\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"model\": \"cisco:model\",\n    \"serial\": \"cisco:serialNumber\",\n    \"firmware\": \"cisco:firmwareVersion\",\n    \"ipAddress\": \"cisco:ipAddress\",\n    \"macAddress\": \"cisco:macAddress\",\n    \"status\": \"cisco:status\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/json-ld/cisco-hardware-context.jsonld
tags:
- Hardware
- Infrastructure
- Networking
- Routers
- Switches
- JSON-LD
- Linked Data
- Semantic Web
---
