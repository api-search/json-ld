---
class_count: 6
classes:
- Alert
- AssetReport
- Device
- DeviceTag
- PolicyRecommendation
- Vulnerability
context_file: json-ld/palo-alto-iot-security-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-iot-security-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Iot Security Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Iot Security Api Context
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
  name: affectedDeviceCount
  type: integer
- container: set
  name: applications
  type: string
- container: ''
  name: byCategory
  type: reference
- container: ''
  name: byRiskLevel
  type: reference
- container: set
  name: bySite
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: confidence
  type: float
- container: ''
  name: confidenceScore
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: critical
  type: integer
- container: ''
  name: cve
  type: string
- container: ''
  name: cvssScore
  type: float
- container: ''
  name: description
  type: string
- container: ''
  name: destinationZone
  type: string
- container: ''
  name: details
  type: reference
- container: ''
  name: deviceCount
  type: integer
- container: ''
  name: deviceIp
  type: string
- container: ''
  name: deviceProfile
  type: string
- container: ''
  name: deviceid
  type: string
- container: ''
  name: firstDetected
  type: dateTime
- container: ''
  name: firstSeen
  type: dateTime
- container: ''
  name: high
  type: integer
- container: ''
  name: hostname
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: ip
  type: string
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: low
  type: integer
- container: ''
  name: mac
  type: string
- container: ''
  name: medium
  type: integer
- container: ''
  name: model
  type: string
- container: ''
  name: monitored
  type: string
- container: ''
  name: monitoredDevices
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: profile
  type: string
- container: ''
  name: remediation
  type: string
- container: ''
  name: reportTime
  type: dateTime
- container: ''
  name: resolved
  type: string
- container: ''
  name: resolvedReason
  type: string
- container: ''
  name: riskScore
  type: integer
- container: set
  name: services
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: site
  type: string
- container: ''
  name: sourceZone
  type: string
- container: ''
  name: subnet
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: set
  name: topProfiles
  type: reference
- container: ''
  name: totalDevices
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: vendor
  type: string
- container: ''
  name: vulnerabilityName
  type: string
property_count: 54
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-iot-security-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alert\": \"pan:Alert\",\n    \"AssetReport\": \"pan:AssetReport\",\n    \"Device\": \"pan:Device\",\n    \"DeviceTag\": \"pan:DeviceTag\",\n    \"PolicyRecommendation\": \"pan:PolicyRecommendation\",\n    \"Vulnerability\": \"pan:Vulnerability\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedDeviceCount\": {\n      \"@id\": \"pan:affected_device_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"applications\": {\n      \"@id\": \"pan:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"byCategory\": {\n      \"@id\": \"pan:by_category\",\n      \"@type\": \"@id\"\n    },\n    \"byRiskLevel\": {\n      \"@id\": \"pan:by_risk_level\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"bySite\": {\n      \"@id\": \"pan:by_site\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confidence\": {\n      \"@id\": \"pan:confidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"confidenceScore\": {\n      \"@id\": \"pan:confidence_score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"critical\": {\n      \"@id\": \"pan:critical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cve\": {\n      \"@id\": \"pan:cve\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvssScore\": {\n      \"@id\": \"pan:cvss_score\",\n      \"@type\": \"xsd:float\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationZone\": {\n      \"@id\": \"\
  pan:destination_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"pan:details\",\n      \"@type\": \"@id\"\n    },\n    \"deviceCount\": {\n      \"@id\": \"pan:device_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deviceIp\": {\n      \"@id\": \"pan:device_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceProfile\": {\n      \"@id\": \"pan:device_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceid\": {\n      \"@id\": \"pan:deviceid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstDetected\": {\n      \"@id\": \"pan:first_detected\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firstSeen\": {\n      \"@id\": \"pan:first_seen\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"high\": {\n      \"@id\": \"pan:high\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostname\": {\n      \"@id\": \"pan:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"ip\": {\n      \"@id\": \"pan:ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"pan:last_seen\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"low\": {\n      \"@id\": \"pan:low\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mac\": {\n      \"@id\": \"pan:mac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medium\": {\n      \"@id\": \"pan:medium\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"model\": {\n      \"@id\": \"pan:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitored\": {\n      \"@id\": \"pan:monitored\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoredDevices\": {\n      \"@id\": \"pan:monitored_devices\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os\": {\n      \"@id\": \"pan:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\"\
  : \"pan:os_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"pan:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"pan:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportTime\": {\n      \"@id\": \"pan:report_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resolved\": {\n      \"@id\": \"pan:resolved\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedReason\": {\n      \"@id\": \"pan:resolved_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskScore\": {\n      \"@id\": \"pan:risk_score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"services\": {\n      \"@id\": \"pan:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"site\": {\n      \"@id\": \"pan:site\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceZone\"\
  : {\n      \"@id\": \"pan:source_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnet\": {\n      \"@id\": \"pan:subnet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"topProfiles\": {\n      \"@id\": \"pan:top_profiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"totalDevices\": {\n      \"@id\": \"pan:total_devices\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendor\": {\n      \"@id\": \"pan:vendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilityName\": {\n      \"@id\": \"pan:vulnerability_name\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-iot-security-api-context.jsonld
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
