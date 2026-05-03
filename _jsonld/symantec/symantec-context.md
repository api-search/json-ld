---
api_specs:
- filename: symantec-sepm-api-openapi.yml
  format: yaml
  label: Symantec Endpoint Protection Manager API
  slug: sepm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/openapi/symantec-sepm-api-openapi.yml
class_count: 15
classes:
- Computer
- Group
- Administrator
- Policy
- id
- uniqueId
- computerName
- operatingSystem
- ipAddresses
- agentVersion
- infected
- onlineStatus
- groupName
- numOfPhysicalComputers
- fullPathName
context_file: json-ld/symantec-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/json-ld/symantec-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Symantec from Symantec.
layout: jsonld
name: Symantec Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: symantec
  uri: https://www.broadcom.com/vocab/symantec#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: lastScanTime
  type: integer
property_count: 1
provider_name: Symantec
provider_slug: symantec
slug: symantec-context
source_filename: symantec-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"symantec\": \"https://www.broadcom.com/vocab/symantec#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Computer\": \"symantec:ManagedEndpoint\",\n    \"Group\": \"symantec:ComputerGroup\",\n    \"Administrator\": \"symantec:SEPMAdministrator\",\n    \"Policy\": \"symantec:SecurityPolicy\",\n\n    \"id\": \"@id\",\n    \"uniqueId\": \"symantec:uniqueId\",\n    \"computerName\": \"schema:name\",\n    \"operatingSystem\": \"schema:operatingSystem\",\n    \"ipAddresses\": \"schema:ipAddress\",\n    \"agentVersion\": \"schema:softwareVersion\",\n    \"infected\": \"symantec:isInfected\",\n    \"onlineStatus\": \"symantec:onlineStatus\",\n    \"lastScanTime\": {\n      \"@id\": \"symantec:lastScanTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupName\": \"symantec:groupName\",\n    \"numOfPhysicalComputers\": \"symantec:computerCount\",\n    \"fullPathName\"\
  : \"symantec:fullPath\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/json-ld/symantec-context.jsonld
tags:
- Broadcom
- Cybersecurity
- DLP
- EDR
- Endpoint Protection
- Endpoint Security
- Security
- Symantec
- JSON-LD
- Linked Data
- Semantic Web
---
