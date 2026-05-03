---
class_count: 22
classes:
- Threat
- Detection
- Alert
- Device
- Event
- Tag
- Group
- id
- name
- description
- type
- severity
- status
- hostName
- filePath
- hash
- processName
- ipAddress
- macAddress
- osName
- osVersion
- agentVersion
context_file: json-ld/trellix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trellix/refs/heads/main/json-ld/trellix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trellix from Trellix.
layout: jsonld
name: Trellix Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: trellix
  uri: https://www.trellix.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: detectedAt
  type: dateTime
- container: ''
  name: hostId
  type: reference
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: groupId
  type: reference
- container: set
  name: tags
  type: ''
- container: ''
  name: hostCount
  type: integer
- container: set
  name: devices
  type: ''
- container: set
  name: events
  type: ''
property_count: 8
provider_name: Trellix
provider_slug: trellix
slug: trellix-context
source_filename: trellix-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"trellix\": \"https://www.trellix.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Threat\": \"trellix:Threat\",\n    \"Detection\": \"trellix:Detection\",\n    \"Alert\": \"trellix:Alert\",\n    \"Device\": \"schema:ComputerOrdered\",\n    \"Event\": \"schema:Event\",\n    \"Tag\": \"schema:DefinedTerm\",\n    \"Group\": \"schema:Organization\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"severity\": \"trellix:severity\",\n    \"status\": \"trellix:status\",\n    \"detectedAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"hostId\": { \"@id\": \"trellix:hostId\", \"@type\": \"@id\" },\n    \"hostName\": \"trellix:hostName\",\n    \"filePath\": \"trellix:filePath\",\n    \"hash\": \"trellix:hash\",\n    \"processName\": \"\
  trellix:processName\",\n    \"ipAddress\": \"schema:networkAddress\",\n    \"macAddress\": \"schema:value\",\n    \"osName\": \"schema:operatingSystem\",\n    \"osVersion\": \"trellix:osVersion\",\n    \"agentVersion\": \"trellix:agentVersion\",\n    \"lastSeen\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"groupId\": { \"@id\": \"trellix:groupId\", \"@type\": \"@id\" },\n    \"tags\": { \"@id\": \"schema:keywords\", \"@container\": \"@set\" },\n    \"hostCount\": { \"@id\": \"trellix:hostCount\", \"@type\": \"xsd:integer\" },\n    \"devices\": { \"@id\": \"trellix:devices\", \"@container\": \"@set\" },\n    \"events\": { \"@id\": \"trellix:events\", \"@container\": \"@set\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trellix/refs/heads/main/json-ld/trellix-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Endpoint Security
- Threat Detection
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
