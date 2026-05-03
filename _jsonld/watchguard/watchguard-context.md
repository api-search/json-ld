---
api_specs:
- filename: watchguard-cloud-platform-openapi.yml
  format: yaml
  label: WatchGuard Cloud Platform API
  slug: watchguard-cloud-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/openapi/watchguard-cloud-platform-openapi.yml
- filename: watchguard-endpoint-security-openapi.yml
  format: yaml
  label: WatchGuard Endpoint Security Management API
  slug: watchguard-endpoint-security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/openapi/watchguard-endpoint-security-openapi.yml
class_count: 9
classes:
- Account
- Device
- Operator
- Activation
- AllocationRecord
- SecurityEvent
- RiskSummary
- License
- Configuration
context_file: json-ld/watchguard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/json-ld/watchguard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Watchguard from WatchGuard.
layout: jsonld
name: Watchguard Context
namespaces:
- prefix: wg
  uri: https://cloud.watchguard.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountType
  type: integer
- container: ''
  name: deviceId
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: protectionStatus
  type: string
- container: ''
  name: isolated
  type: boolean
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: agentVersion
  type: string
- container: ''
  name: activationKey
  type: string
- container: ''
  name: batchId
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: riskSeverity
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: role
  type: string
property_count: 19
provider_name: WatchGuard
provider_slug: watchguard
slug: watchguard-context
source_filename: watchguard-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wg\": \"https://cloud.watchguard.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"Account\": \"wg:Account\",\n    \"Device\": \"wg:EndpointDevice\",\n    \"Operator\": \"wg:Operator\",\n    \"Activation\": \"wg:Activation\",\n    \"AllocationRecord\": \"wg:AllocationRecord\",\n    \"SecurityEvent\": \"wg:SecurityEvent\",\n    \"RiskSummary\": \"wg:RiskSummary\",\n    \"License\": \"wg:License\",\n    \"Configuration\": \"wg:Configuration\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"wg:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"\
  @id\": \"wg:accountType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deviceId\": {\n      \"@id\": \"wg:deviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"wg:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"schema:ipAddressOfSubject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"schema:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protectionStatus\": {\n      \"@id\": \"wg:protectionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isolated\": {\n      \"@id\": \"wg:isolated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"agentVersion\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activationKey\": {\n      \"@id\": \"wg:activationKey\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"batchId\": {\n      \"@id\": \"wg:batchId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskSeverity\": {\n      \"@id\": \"wg:riskSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"wg:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/json-ld/watchguard-context.jsonld
tags:
- Cloud Security
- Endpoint Security
- Firewall
- MFA
- Network Security
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
