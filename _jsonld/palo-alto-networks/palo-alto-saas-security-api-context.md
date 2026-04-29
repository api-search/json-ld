---
class_count: 6
classes:
- Application
- Asset
- Incident
- LogForwardingSettings
- User
- UserActivity
context_file: json-ld/palo-alto-saas-security-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-saas-security-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Saas Security Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Saas Security Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountType
  type: string
- container: ''
  name: action
  type: string
- container: set
  name: affectedAssets
  type: string
- container: set
  name: affectedUsers
  type: string
- container: ''
  name: appId
  type: string
- container: ''
  name: appName
  type: string
- container: ''
  name: assetCount
  type: integer
- container: ''
  name: assetId
  type: string
- container: ''
  name: assigneeId
  type: string
- container: ''
  name: connectedAt
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: set
  name: destinations
  type: reference
- container: ''
  name: displayName
  type: string
- container: set
  name: dlpViolations
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: exposure
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: incidentCount
  type: integer
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: lastActivity
  type: dateTime
- container: ''
  name: lastScannedAt
  type: dateTime
- container: set
  name: logTypes
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: policyName
  type: string
- container: ''
  name: riskLevel
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: sizeBytes
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: userId
  type: string
property_count: 36
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-saas-security-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Application\": \"pan:Application\",\n    \"Asset\": \"pan:Asset\",\n    \"Incident\": \"pan:Incident\",\n    \"LogForwardingSettings\": \"pan:LogForwardingSettings\",\n    \"User\": \"pan:User\",\n    \"UserActivity\": \"pan:UserActivity\",\n    \"accountType\": {\n      \"@id\": \"pan:account_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedAssets\": {\n      \"@id\": \"pan:affected_assets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedUsers\": {\n      \"@id\": \"pan:affected_users\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\"\
  : \"pan:app_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appName\": {\n      \"@id\": \"pan:app_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetCount\": {\n      \"@id\": \"pan:asset_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"assetId\": {\n      \"@id\": \"pan:asset_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assigneeId\": {\n      \"@id\": \"pan:assignee_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectedAt\": {\n      \"@id\": \"pan:connected_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinations\": {\n      \"@id\": \"pan:destinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"displayName\": {\n      \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"dlpViolations\": {\n      \"@id\": \"pan:dlp_violations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exposure\": {\n      \"@id\": \"pan:exposure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentCount\": {\n      \"@id\": \"pan:incident_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"pan:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastActivity\": {\n      \"@id\": \"pan:last_activity\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScannedAt\": {\n      \"@id\": \"pan:last_scanned_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logTypes\": {\n      \"@id\": \"pan:log_types\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"pan:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n      \"@id\": \"pan:policy_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskLevel\": {\n      \"@id\": \"pan:risk_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeBytes\": {\n      \"@id\": \"pan:size_bytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userId\": {\n      \"@id\": \"pan:user_id\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-saas-security-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
