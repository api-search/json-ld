---
class_count: 63
classes:
- Organization
- SecurityAdvisory
- ThreatSignature
- SecurityPolicy
- SecurityAlert
- SecurityIncident
- MalwareAnalysis
- CloudResource
- NetworkDevice
- IoTDevice
- Vulnerability
- ComplianceViolation
- AttackSurfaceAsset
- AISecurityScan
- name
- description
- datePublished
- dateModified
- severity
- status
- category
- cvssScore
- affectedProduct
- fixedVersion
- signatureId
- signatureType
- threatName
- action
- verdict
- sha256
- md5
- filetype
- malwareFamily
- alertId
- incidentId
- assignedTo
- alertCount
- detectionSource
- sourceAddress
- destinationAddress
- sourceZone
- destinationZone
- application
- ruleAction
- cloudType
- resourceId
- resourceType
- region
- accountId
- complianceStandard
- deviceIp
- deviceMac
- deviceProfile
- riskScore
- assetType
- ipRanges
- domain
- certificate
- exposureLevel
- prompt
- modelResponse
- aiThreatType
- confidence
context_file: json-ld/palo-alto-networks-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-networks-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Networks Security from Palo Alto Networks.
layout: jsonld
name: Palo Alto Networks Security Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: stix
  uri: https://docs.oasis-open.org/cti/stix/v2.1/
- prefix: cve
  uri: https://cve.mitre.org/cgi-bin/cvename.cgi?name=
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: cveId
  type: reference
- container: ''
  name: relatedThreat
  type: reference
- container: ''
  name: mitigatedBy
  type: reference
- container: ''
  name: detectedBy
  type: reference
- container: ''
  name: affectsResource
  type: reference
property_count: 6
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-networks-security-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"stix\": \"https://docs.oasis-open.org/cti/stix/v2.1/\",\n    \"cve\": \"https://cve.mitre.org/cgi-bin/cvename.cgi?name=\",\n\n    \"Organization\": \"schema:Organization\",\n    \"SecurityAdvisory\": \"pan:SecurityAdvisory\",\n    \"ThreatSignature\": \"pan:ThreatSignature\",\n    \"SecurityPolicy\": \"pan:SecurityPolicy\",\n    \"SecurityAlert\": \"pan:SecurityAlert\",\n    \"SecurityIncident\": \"pan:SecurityIncident\",\n    \"MalwareAnalysis\": \"pan:MalwareAnalysis\",\n    \"CloudResource\": \"pan:CloudResource\",\n    \"NetworkDevice\": \"pan:NetworkDevice\",\n    \"IoTDevice\": \"pan:IoTDevice\",\n    \"Vulnerability\": \"pan:Vulnerability\",\n    \"ComplianceViolation\": \"pan:ComplianceViolation\",\n    \"AttackSurfaceAsset\": \"pan:AttackSurfaceAsset\",\n    \"AISecurityScan\": \"pan:AISecurityScan\",\n\n    \"name\": \"schema:name\"\
  ,\n    \"description\": \"schema:description\",\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"datePublished\": \"schema:datePublished\",\n    \"dateModified\": \"schema:dateModified\",\n    \"severity\": \"pan:severity\",\n    \"status\": \"pan:status\",\n    \"category\": \"pan:category\",\n\n    \"cveId\": {\"@id\": \"pan:cveId\", \"@type\": \"@id\"},\n    \"cvssScore\": \"pan:cvssScore\",\n    \"affectedProduct\": \"pan:affectedProduct\",\n    \"fixedVersion\": \"pan:fixedVersion\",\n\n    \"signatureId\": \"pan:signatureId\",\n    \"signatureType\": \"pan:signatureType\",\n    \"threatName\": \"pan:threatName\",\n    \"action\": \"pan:action\",\n\n    \"verdict\": \"pan:verdict\",\n    \"sha256\": \"pan:sha256\",\n    \"md5\": \"pan:md5\",\n    \"filetype\": \"pan:filetype\",\n    \"malwareFamily\": \"pan:malwareFamily\",\n\n    \"alertId\": \"pan:alertId\",\n    \"incidentId\": \"pan:incidentId\",\n    \"assignedTo\": \"pan:assignedTo\",\n    \"alertCount\":\
  \ \"pan:alertCount\",\n    \"detectionSource\": \"pan:detectionSource\",\n\n    \"sourceAddress\": \"pan:sourceAddress\",\n    \"destinationAddress\": \"pan:destinationAddress\",\n    \"sourceZone\": \"pan:sourceZone\",\n    \"destinationZone\": \"pan:destinationZone\",\n    \"application\": \"pan:application\",\n    \"ruleAction\": \"pan:ruleAction\",\n\n    \"cloudType\": \"pan:cloudType\",\n    \"resourceId\": \"pan:resourceId\",\n    \"resourceType\": \"pan:resourceType\",\n    \"region\": \"pan:region\",\n    \"accountId\": \"pan:accountId\",\n    \"complianceStandard\": \"pan:complianceStandard\",\n\n    \"deviceIp\": \"pan:deviceIp\",\n    \"deviceMac\": \"pan:deviceMac\",\n    \"deviceProfile\": \"pan:deviceProfile\",\n    \"riskScore\": \"pan:riskScore\",\n\n    \"assetType\": \"pan:assetType\",\n    \"ipRanges\": \"pan:ipRanges\",\n    \"domain\": \"pan:domain\",\n    \"certificate\": \"pan:certificate\",\n    \"exposureLevel\": \"pan:exposureLevel\",\n\n    \"prompt\": \"pan:prompt\"\
  ,\n    \"modelResponse\": \"pan:modelResponse\",\n    \"aiThreatType\": \"pan:aiThreatType\",\n    \"confidence\": \"pan:confidence\",\n\n    \"relatedThreat\": {\"@id\": \"pan:relatedThreat\", \"@type\": \"@id\"},\n    \"mitigatedBy\": {\"@id\": \"pan:mitigatedBy\", \"@type\": \"@id\"},\n    \"detectedBy\": {\"@id\": \"pan:detectedBy\", \"@type\": \"@id\"},\n    \"affectsResource\": {\"@id\": \"pan:affectsResource\", \"@type\": \"@id\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-networks-security-context.jsonld
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
