---
api_specs:
- filename: stanley-black-and-decker-tool-connect-api-openapi.yml
  format: yaml
  label: DEWALT Tool Connect API
  slug: dewalt-tool-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stanley-black-and-decker/refs/heads/main/openapi/stanley-black-and-decker-tool-connect-api-openapi.yml
class_count: 35
classes:
- Tool
- Battery
- Asset
- Jobsite
- User
- id
- name
- description
- model
- serialNumber
- brand
- type
- status
- jobsiteId
- firmwareVersion
- purchaseDate
- warrantyExpiry
- lastSeen
- assignedUserId
- chargeStatus
- health
- chargeCycles
- voltage
- capacity
- pairedToolId
- address
- toolCount
- batteryCount
- userCount
- tools
- batteries
- users
- registeredAt
- role
- jobsiteIds
context_file: json-ld/stanley-black-and-decker-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stanley-black-and-decker/refs/heads/main/json-ld/stanley-black-and-decker-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stanley Black And Decker from Stanley Black & Decker.
layout: jsonld
name: Stanley Black And Decker Context
namespaces:
- prefix: sbd
  uri: https://api.dewalt.com/vocab#
- prefix: iot
  uri: https://www.w3.org/ns/sosa/
properties:
- container: ''
  name: totalRuntime
  type: decimal
- container: ''
  name: chargeLevel
  type: integer
- container: ''
  name: temperature
  type: decimal
property_count: 3
provider_name: Stanley Black & Decker
provider_slug: stanley-black-and-decker
slug: stanley-black-and-decker-context
source_filename: stanley-black-and-decker-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sbd\": \"https://api.dewalt.com/vocab#\",\n    \"iot\": \"https://www.w3.org/ns/sosa/\",\n    \"Tool\": \"sbd:ConnectedTool\",\n    \"Battery\": \"sbd:Battery\",\n    \"Asset\": \"sbd:Asset\",\n    \"Jobsite\": \"sbd:Jobsite\",\n    \"User\": \"Person\",\n    \"id\": \"@id\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"model\": \"model\",\n    \"serialNumber\": \"serialNumber\",\n    \"brand\": \"brand\",\n    \"type\": \"@type\",\n    \"status\": \"sbd:connectivityStatus\",\n    \"jobsiteId\": \"sbd:assignedJobsite\",\n    \"firmwareVersion\": \"softwareVersion\",\n    \"purchaseDate\": \"purchaseDate\",\n    \"warrantyExpiry\": \"sbd:warrantyExpiry\",\n    \"lastSeen\": \"sbd:lastConnected\",\n    \"totalRuntime\": {\n      \"@id\": \"sbd:totalRuntime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"assignedUserId\": \"sbd:assignedUser\",\n    \"chargeLevel\": {\n      \"@id\"\
  : \"sbd:chargeLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"chargeStatus\": \"sbd:chargeStatus\",\n    \"health\": \"sbd:batteryHealth\",\n    \"chargeCycles\": \"sbd:chargeCycles\",\n    \"temperature\": {\n      \"@id\": \"iot:hasSimpleResult\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"voltage\": \"sbd:voltage\",\n    \"capacity\": \"sbd:batteryCapacity\",\n    \"pairedToolId\": \"sbd:pairedTool\",\n    \"address\": \"address\",\n    \"toolCount\": \"sbd:toolCount\",\n    \"batteryCount\": \"sbd:batteryCount\",\n    \"userCount\": \"sbd:userCount\",\n    \"tools\": \"sbd:tools\",\n    \"batteries\": \"sbd:batteries\",\n    \"users\": \"sbd:users\",\n    \"registeredAt\": \"dateCreated\",\n    \"role\": \"jobTitle\",\n    \"jobsiteIds\": \"sbd:assignedJobsites\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stanley-black-and-decker/refs/heads/main/json-ld/stanley-black-and-decker-context.jsonld
tags:
- Tools
- Hardware
- Manufacturing
- IoT
- Connected Tools
- JSON-LD
- Linked Data
- Semantic Web
---
