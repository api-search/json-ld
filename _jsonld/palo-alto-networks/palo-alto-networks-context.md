---
class_count: 0
classes: []
context_file: json-ld/palo-alto-networks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-networks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Networks from Palo Alto Networks.
layout: jsonld
name: Palo Alto Networks Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sec
  uri: https://w3id.org/security#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: SecurityIncident
  type: reference
- container: ''
  name: FirewallPolicy
  type: reference
- container: ''
  name: ThreatSignature
  type: reference
- container: ''
  name: NetworkDevice
  type: reference
- container: ''
  name: VulnerabilityAssessment
  type: reference
- container: ''
  name: CloudAccount
  type: reference
- container: ''
  name: SecurityAlert
  type: reference
- container: ''
  name: DataLossEvent
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: datePublished
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: creator
  type: reference
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: incidentId
  type: string
- container: ''
  name: alertId
  type: string
- container: ''
  name: alertCount
  type: integer
- container: ''
  name: alertSources
  type: string
- container: ''
  name: assignedTo
  type: string
- container: ''
  name: detectionSource
  type: string
- container: ''
  name: resolutionComment
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyName
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: sourceZone
  type: string
- container: ''
  name: destinationZone
  type: string
- container: ''
  name: sourceAddress
  type: string
- container: ''
  name: destinationAddress
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: ruleAction
  type: string
- container: ''
  name: signatureId
  type: string
- container: ''
  name: signatureType
  type: string
- container: ''
  name: threatName
  type: string
- container: ''
  name: threatId
  type: string
- container: ''
  name: verdict
  type: string
- container: ''
  name: sha256
  type: string
- container: ''
  name: malwareFamily
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: deviceModel
  type: string
- container: ''
  name: deviceIp
  type: string
- container: ''
  name: softwareVersion
  type: string
- container: ''
  name: cveId
  type: string
- container: ''
  name: cvssScore
  type: decimal
- container: ''
  name: cvssVector
  type: string
- container: ''
  name: affectedProduct
  type: reference
- container: ''
  name: fixedVersion
  type: string
- container: ''
  name: exploitStatus
  type: string
- container: ''
  name: cloudType
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: complianceStandard
  type: string
- container: ''
  name: dataClassification
  type: string
- container: ''
  name: exposureType
  type: string
- container: ''
  name: dataStore
  type: string
- container: ''
  name: relatedIncident
  type: reference
- container: ''
  name: relatedAlert
  type: reference
- container: ''
  name: relatedPolicy
  type: reference
- container: ''
  name: affectsResource
  type: reference
- container: ''
  name: detectedBy
  type: reference
- container: ''
  name: mitigatedBy
  type: reference
- container: ''
  name: partOf
  type: reference
- container: ''
  name: enforcedBy
  type: reference
property_count: 72
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-networks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"SecurityIncident\": {\n      \"@id\": \"pan:SecurityIncident\",\n      \"@type\": \"@id\",\n      \"skos:closeMatch\": \"schema:Event\",\n      \"dcterms:description\": \"A correlated collection of security alerts representing a potential threat or attack campaign detected across endpoints, networks, or cloud environments.\"\n    },\n\n    \"FirewallPolicy\": {\n      \"@id\": \"pan:FirewallPolicy\",\n      \"@type\": \"@id\",\n      \"skos:closeMatch\": \"sec:Policy\",\n      \"dcterms:description\": \"A PAN-OS security policy rule defining traffic enforcement criteria including source\
  \ zones, destination zones, applications, services, and the enforcement action applied to matching sessions.\"\n    },\n\n    \"ThreatSignature\": {\n      \"@id\": \"pan:ThreatSignature\",\n      \"@type\": \"@id\",\n      \"skos:relatedMatch\": \"sec:Signature\",\n      \"dcterms:description\": \"A Palo Alto Networks threat prevention signature used to detect and block exploitation of known vulnerabilities, malware, spyware, command-and-control traffic, and other threat patterns.\"\n    },\n\n    \"NetworkDevice\": {\n      \"@id\": \"pan:NetworkDevice\",\n      \"@type\": \"@id\",\n      \"skos:exactMatch\": \"schema:Device\",\n      \"dcterms:description\": \"A Palo Alto Networks next-generation firewall, Prisma Access node, or other network security appliance managing and enforcing security policy on network traffic.\"\n    },\n\n    \"VulnerabilityAssessment\": {\n      \"@id\": \"pan:VulnerabilityAssessment\",\n      \"@type\": \"@id\",\n      \"skos:closeMatch\": \"schema:Report\"\
  ,\n      \"dcterms:description\": \"An assessment of a security vulnerability affecting Palo Alto Networks products, including CVSS scoring, affected version ranges, exploitation status, and available remediations as published by the Palo Alto Networks PSIRT.\"\n    },\n\n    \"CloudAccount\": {\n      \"@id\": \"pan:CloudAccount\",\n      \"@type\": \"@id\",\n      \"skos:closeMatch\": \"schema:Organization\",\n      \"dcterms:description\": \"A cloud service provider account, subscription, or project onboarded into Prisma Cloud for security posture monitoring. Represents an AWS account, Azure subscription, GCP project, OCI tenancy, or Alibaba Cloud account.\"\n    },\n\n    \"SecurityAlert\": {\n      \"@id\": \"pan:SecurityAlert\",\n      \"@type\": \"@id\",\n      \"skos:relatedMatch\": \"schema:AlertAction\",\n      \"dcterms:description\": \"A security event notification generated by Prisma Cloud for a policy violation, by Cortex XDR for a detection, or by other Palo Alto Networks\
  \ products indicating suspicious or malicious activity requiring investigation.\"\n    },\n\n    \"DataLossEvent\": {\n      \"@id\": \"pan:DataLossEvent\",\n      \"@type\": \"@id\",\n      \"skos:closeMatch\": \"schema:Event\",\n      \"dcterms:description\": \"An event indicating that sensitive data has been exposed, exfiltrated, or otherwise disclosed without authorization. Detected by Prisma Cloud data security policies or Cortex XDR data loss prevention capabilities.\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"dcterms:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"datePublished\": {\n      \"@id\": \"dcterms:issued\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\"\
  : {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateCreated\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creator\": {\n      \"@id\": \"dcterms:creator\",\n      \"@type\": \"@id\"\n    },\n\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"dcterms:type\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"incidentId\": {\n      \"@id\": \"pan:incidentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertId\": {\n      \"@id\": \"pan:alertId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertCount\": {\n      \"@id\": \"pan:alertCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"alertSources\": {\n      \"@id\": \"pan:alertSources\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedTo\": {\n      \"@id\": \"pan:assignedTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectionSource\": {\n      \"@id\": \"pan:detectionSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolutionComment\": {\n      \"@id\": \"pan:resolutionComment\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"policyId\": {\n      \"@id\": \"pan:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n      \"@id\": \"pan:policyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"pan:policyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceZone\": {\n      \"@id\": \"pan:sourceZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationZone\": {\n      \"@id\": \"pan:destinationZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAddress\": {\n      \"@id\": \"pan:sourceAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationAddress\"\
  : {\n      \"@id\": \"pan:destinationAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleAction\": {\n      \"@id\": \"pan:ruleAction\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"signatureId\": {\n      \"@id\": \"pan:signatureId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatureType\": {\n      \"@id\": \"pan:signatureType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatName\": {\n      \"@id\": \"pan:threatName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatId\": {\n      \"@id\": \"pan:threatId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verdict\": {\n      \"@id\": \"pan:verdict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sha256\": {\n      \"@id\": \"pan:sha256\",\n      \"@type\": \"xsd:string\"\n    },\n    \"malwareFamily\": {\n      \"@id\": \"pan:malwareFamily\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"serialNumber\"\
  : {\n      \"@id\": \"pan:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n      \"@id\": \"pan:deviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceModel\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceIp\": {\n      \"@id\": \"pan:deviceIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"softwareVersion\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"cveId\": {\n      \"@id\": \"pan:cveId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvssScore\": {\n      \"@id\": \"pan:cvssScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cvssVector\": {\n      \"@id\": \"pan:cvssVector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedProduct\": {\n      \"@id\": \"pan:affectedProduct\",\n      \"@type\": \"@id\"\n    },\n    \"fixedVersion\": {\n      \"@id\": \"pan:fixedVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exploitStatus\"\
  : {\n      \"@id\": \"pan:exploitStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"cloudType\": {\n      \"@id\": \"pan:cloudType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"pan:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"pan:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"pan:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complianceStandard\": {\n      \"@id\": \"pan:complianceStandard\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"dataClassification\": {\n      \"@id\": \"pan:dataClassification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exposureType\": {\n      \"@id\": \"pan:exposureType\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"dataStore\": {\n      \"@id\": \"pan:dataStore\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"relatedIncident\": {\n      \"@id\": \"pan:relatedIncident\",\n      \"@type\": \"@id\"\n    },\n    \"relatedAlert\": {\n      \"@id\": \"pan:relatedAlert\",\n      \"@type\": \"@id\"\n    },\n    \"relatedPolicy\": {\n      \"@id\": \"pan:relatedPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"affectsResource\": {\n      \"@id\": \"pan:affectsResource\",\n      \"@type\": \"@id\"\n    },\n    \"detectedBy\": {\n      \"@id\": \"pan:detectedBy\",\n      \"@type\": \"@id\"\n    },\n    \"mitigatedBy\": {\n      \"@id\": \"pan:mitigatedBy\",\n      \"@type\": \"@id\"\n    },\n    \"partOf\": {\n      \"@id\": \"dcterms:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"enforcedBy\": {\n      \"@id\": \"pan:enforcedBy\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-networks-context.jsonld
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
