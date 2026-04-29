---
class_count: 8
classes:
- BrowserDeployment
- BrowserDeploymentRequest
- BrowserPolicy
- BrowserPolicyRequest
- BrowserSession
- BrowserUser
- ManagedDevice
- UsageReport
context_file: json-ld/palo-alto-prisma-access-browser-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-access-browser-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Access Browser Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Access Browser Api Context
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
  name: activeSessions
  type: integer
- container: ''
  name: activeUsers
  type: integer
- container: set
  name: blockedCategories
  type: string
- container: ''
  name: browserVersion
  type: string
- container: ''
  name: complianceStatus
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: set
  name: dataPoints
  type: reference
- container: ''
  name: dataTransferredGb
  type: float
- container: ''
  name: deploymentId
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: deviceCount
  type: integer
- container: ''
  name: deviceId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: dlpEnabled
  type: boolean
- container: ''
  name: dlpEvents
  type: integer
- container: ''
  name: downloadControl
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: end
  type: date
- container: ''
  name: endedAt
  type: dateTime
- container: ''
  name: extensionPolicy
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: lastActiveAt
  type: dateTime
- container: ''
  name: lastSeenAt
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: period
  type: reference
- container: ''
  name: platform
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: sessions
  type: integer
- container: ''
  name: start
  type: date
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: threatsBlocked
  type: integer
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: totalSessions
  type: integer
- container: ''
  name: updateChannel
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: userId
  type: string
- container: ''
  name: webFiltering
  type: reference
property_count: 41
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-access-browser-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BrowserDeployment\": \"pan:BrowserDeployment\",\n    \"BrowserDeploymentRequest\": \"pan:BrowserDeploymentRequest\",\n    \"BrowserPolicy\": \"pan:BrowserPolicy\",\n    \"BrowserPolicyRequest\": \"pan:BrowserPolicyRequest\",\n    \"BrowserSession\": \"pan:BrowserSession\",\n    \"BrowserUser\": \"pan:BrowserUser\",\n    \"ManagedDevice\": \"pan:ManagedDevice\",\n    \"UsageReport\": \"pan:UsageReport\",\n    \"activeSessions\": {\n      \"@id\": \"pan:active_sessions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activeUsers\": {\n      \"@id\": \"pan:active_users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"blockedCategories\": {\n      \"@id\": \"pan:blocked_categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"browserVersion\": {\n      \"@id\": \"pan:browser_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complianceStatus\": {\n      \"@id\": \"pan:compliance_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataPoints\": {\n      \"@id\": \"pan:data_points\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"dataTransferredGb\": {\n      \"@id\": \"pan:data_transferred_gb\",\n      \"@type\": \"xsd:float\"\n    },\n    \"deploymentId\": {\n      \"@id\": \"pan:deployment_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceCount\": {\n      \"@id\": \"pan:device_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deviceId\": {\n      \"@id\": \"pan:device_id\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"displayName\": {\n      \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dlpEnabled\": {\n      \"@id\": \"pan:dlp_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dlpEvents\": {\n      \"@id\": \"pan:dlp_events\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"downloadControl\": {\n      \"@id\": \"pan:download_control\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"end\": {\n      \"@id\": \"pan:end\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endedAt\": {\n      \"@id\": \"pan:ended_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"extensionPolicy\": {\n      \"@id\": \"pan:extension_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"pan:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  ipAddress\": {\n      \"@id\": \"pan:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastActiveAt\": {\n      \"@id\": \"pan:last_active_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastSeenAt\": {\n      \"@id\": \"pan:last_seen_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"pan:period\",\n      \"@type\": \"@id\"\n    },\n    \"platform\": {\n      \"@id\": \"pan:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n      \"@id\": \"pan:policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"pan:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessions\": {\n      \"@id\": \"pan:sessions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"pan:start\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startedAt\": {\n      \"@id\": \"pan:started_at\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatsBlocked\": {\n      \"@id\": \"pan:threats_blocked\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalSessions\": {\n      \"@id\": \"pan:total_sessions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updateChannel\": {\n      \"@id\": \"pan:update_channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userId\": {\n      \"@id\": \"pan:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webFiltering\": {\n      \"@id\": \"pan:web_filtering\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-access-browser-api-context.jsonld
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
