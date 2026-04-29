---
api_specs:
- filename: ruckus-one-api-openapi.yml
  format: yaml
  label: RUCKUS One API
  slug: ruckus-one-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/openapi/ruckus-one-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/commscope-holding-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/json-ld/commscope-holding-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Commscope Holding from CommScope Holding.
layout: jsonld
name: Commscope Holding Context
namespaces:
- prefix: ruckus
  uri: https://ruckus.cloud/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Venue
  type: ''
- container: ''
  name: Network
  type: ''
- container: ''
  name: AccessPoint
  type: ''
- container: ''
  name: Switch
  type: ''
- container: ''
  name: Client
  type: ''
- container: ''
  name: MSPCustomer
  type: ''
- container: ''
  name: Activity
  type: ''
property_count: 7
provider_name: CommScope Holding
provider_slug: commscope-holding
slug: commscope-holding-context
source_filename: commscope-holding-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ruckus\": \"https://ruckus.cloud/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Venue\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\"\n      }\n    },\n\n    \"Network\": {\n      \"@id\": \"ruckus:WirelessNetwork\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"ssid\": \"ruckus:ssid\",\n        \"security\": \"ruckus:security\",\n        \"venueId\": \"ruckus:venueId\"\n      }\n    },\n\n    \"AccessPoint\": {\n      \"@id\": \"ruckus:AccessPoint\",\n      \"@context\": {\n        \"serialNumber\": \"@id\",\n        \"model\": \"schema:model\",\n        \"venueId\": \"ruckus:venueId\",\n        \"status\": \"ruckus:status\"\n      }\n    },\n\n    \"Switch\": {\n      \"@id\": \"ruckus:Switch\"\
  ,\n      \"@context\": {\n        \"serialNumber\": \"@id\",\n        \"model\": \"schema:model\",\n        \"venueId\": \"ruckus:venueId\",\n        \"status\": \"ruckus:status\"\n      }\n    },\n\n    \"Client\": {\n      \"@id\": \"ruckus:Client\",\n      \"@context\": {\n        \"mac\": \"@id\",\n        \"ip\": \"ruckus:ipAddress\",\n        \"username\": \"schema:identifier\",\n        \"ssid\": \"ruckus:ssid\",\n        \"apSerialNumber\": \"ruckus:apSerialNumber\",\n        \"connectedAt\": {\n          \"@id\": \"ruckus:connectedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MSPCustomer\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"tenantId\": \"ruckus:tenantId\"\n      }\n    },\n\n    \"Activity\": {\n      \"@id\": \"ruckus:Activity\",\n      \"@context\": {\n        \"requestId\": \"@id\",\n        \"status\": \"ruckus:status\",\n        \"startedAt\"\
  : {\n          \"@id\": \"ruckus:startedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"ruckus:endedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/json-ld/commscope-holding-context.jsonld
tags:
- Access Points
- Cabling
- Connectivity
- ICX Switches
- Infrastructure
- Networking
- RUCKUS
- Wi-Fi
- JSON-LD
- Linked Data
- Semantic Web
---
