---
class_count: 8
classes:
- Alert
- Asset
- AuditLog
- Endpoint
- Filter
- Incident
- SortOrder
- value
context_file: json-ld/palo-alto-cortex-xsiam-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xsiam-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cortex Xsiam Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cortex Xsiam Api Context
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
  name: action
  type: string
- container: ''
  name: actorEmail
  type: string
- container: ''
  name: actorPrimaryUsername
  type: string
- container: ''
  name: actorType
  type: string
- container: ''
  name: alertCount
  type: integer
- container: ''
  name: alertId
  type: string
- container: ''
  name: alertType
  type: string
- container: ''
  name: assetId
  type: string
- container: ''
  name: assetName
  type: string
- container: ''
  name: assetType
  type: string
- container: ''
  name: assignedUserMail
  type: string
- container: ''
  name: assignedUserPrettyName
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: contentVersion
  type: string
- container: ''
  name: creationTime
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: detectionTime
  type: integer
- container: ''
  name: detectionTimestamp
  type: integer
- container: ''
  name: domain
  type: string
- container: ''
  name: endpointId
  type: string
- container: ''
  name: endpointName
  type: string
- container: ''
  name: endpointStatus
  type: string
- container: ''
  name: endpointType
  type: string
- container: ''
  name: endpointVersion
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: firstSeen
  type: integer
- container: ''
  name: hostName
  type: string
- container: ''
  name: incidentId
  type: string
- container: ''
  name: incidentName
  type: string
- container: ''
  name: ip
  type: string
- container: set
  name: ipAddresses
  type: string
- container: ''
  name: isIsolated
  type: string
- container: ''
  name: keyword
  type: string
- container: ''
  name: lastSeen
  type: integer
- container: set
  name: mitreTacticsIdsAndNames
  type: string
- container: set
  name: mitreTechniquesIdsAndNames
  type: string
- container: ''
  name: modificationTime
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: osType
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: resolutionStatus
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: riskScore
  type: decimal
- container: ''
  name: scanStatus
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: source
  type: string
- container: set
  name: sources
  type: string
- container: ''
  name: starred
  type: boolean
- container: ''
  name: status
  type: string
- container: ''
  name: subType
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: userName
  type: string
- container: set
  name: users
  type: string
- container: ''
  name: xdrUrl
  type: string
property_count: 57
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cortex-xsiam-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alert\": \"pan:Alert\",\n    \"Asset\": \"pan:Asset\",\n    \"AuditLog\": \"pan:AuditLog\",\n    \"Endpoint\": \"pan:Endpoint\",\n    \"Filter\": \"pan:Filter\",\n    \"Incident\": \"pan:Incident\",\n    \"SortOrder\": \"pan:SortOrder\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorEmail\": {\n      \"@id\": \"pan:actor_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorPrimaryUsername\": {\n      \"@id\": \"pan:actor_primary_username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorType\": {\n      \"@id\": \"pan:actor_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertCount\": {\n      \"@id\": \"pan:alert_count\",\n      \"@type\": \"xsd:integer\"\n \
  \   },\n    \"alertId\": {\n      \"@id\": \"pan:alert_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertType\": {\n      \"@id\": \"pan:alert_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetId\": {\n      \"@id\": \"pan:asset_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetName\": {\n      \"@id\": \"pan:asset_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetType\": {\n      \"@id\": \"pan:asset_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedUserMail\": {\n      \"@id\": \"pan:assigned_user_mail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedUserPrettyName\": {\n      \"@id\": \"pan:assigned_user_pretty_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentVersion\": {\n      \"@id\": \"pan:content_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectionTime\": {\n      \"@id\": \"pan:detection_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"detectionTimestamp\": {\n      \"@id\": \"pan:detection_timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"domain\": {\n      \"@id\": \"pan:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointId\": {\n      \"@id\": \"pan:endpoint_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointName\": {\n      \"@id\": \"pan:endpoint_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointStatus\": {\n      \"@id\": \"pan:endpoint_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointType\": {\n      \"@id\": \"pan:endpoint_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointVersion\": {\n      \"@id\": \"pan:endpoint_version\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"field\": {\n      \"@id\": \"pan:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstSeen\": {\n      \"@id\": \"pan:first_seen\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostName\": {\n      \"@id\": \"pan:host_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentId\": {\n      \"@id\": \"pan:incident_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentName\": {\n      \"@id\": \"pan:incident_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip\": {\n      \"@id\": \"pan:ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddresses\": {\n      \"@id\": \"pan:ip_addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isIsolated\": {\n      \"@id\": \"pan:is_isolated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyword\": {\n      \"@id\": \"pan:keyword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"pan:last_seen\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"mitreTacticsIdsAndNames\": {\n      \"@id\": \"pan:mitre_tactics_ids_and_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mitreTechniquesIdsAndNames\": {\n      \"@id\": \"pan:mitre_techniques_ids_and_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"pan:operating_system\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"pan:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osType\": {\n      \"@id\": \"pan:os_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"pan:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolutionStatus\": {\n      \"@id\": \"pan:resolution_status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"pan:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskScore\": {\n      \"@id\": \"pan:risk_score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"scanStatus\": {\n      \"@id\": \"pan:scan_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pan:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"pan:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"starred\": {\n      \"@id\": \"pan:starred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"pan:sub_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userName\": {\n      \"@id\": \"pan:user_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"pan:users\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": \"pan:value\",\n    \"xdrUrl\": {\n      \"@id\": \"pan:xdr_url\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xsiam-api-context.jsonld
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
