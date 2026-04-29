---
class_count: 1
classes:
- Cortex XDR Incident
context_file: json-ld/palo-alto-cortex-xdr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xdr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cortex Xdr from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cortex Xdr Context
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
  name: alertCount
  type: integer
- container: set
  name: alertSources
  type: string
- container: ''
  name: assignedUserMail
  type: string
- container: ''
  name: assignedUserPrettyName
  type: string
- container: ''
  name: creationTime
  type: integer
- container: ''
  name: description
  type: string
- container: set
  name: fileArtifacts
  type: ''
- container: ''
  name: fileName
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: fileSha256
  type: string
- container: ''
  name: fileSignatureStatus
  type: string
- container: ''
  name: highSeverityAlertCount
  type: integer
- container: ''
  name: hostCount
  type: integer
- container: ''
  name: incidentId
  type: string
- container: ''
  name: incidentName
  type: string
- container: ''
  name: isManual
  type: boolean
- container: ''
  name: lowSeverityAlertCount
  type: integer
- container: ''
  name: medSeverityAlertCount
  type: integer
- container: ''
  name: modificationTime
  type: integer
- container: set
  name: networkArtifacts
  type: ''
- container: ''
  name: networkCountry
  type: string
- container: ''
  name: networkDomain
  type: string
- container: ''
  name: networkRemoteIp
  type: string
- container: ''
  name: networkRemotePort
  type: integer
- container: ''
  name: notes
  type: string
- container: ''
  name: resolveComment
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: userCount
  type: integer
- container: ''
  name: wildfireVerdict
  type: string
- container: ''
  name: xdrUrl
  type: reference
property_count: 32
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cortex-xdr-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Cortex XDR Incident\": \"pan:Cortex XDR Incident\",\n    \"alertCount\": {\n      \"@id\": \"pan:alert_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"alertSources\": {\n      \"@id\": \"pan:alert_sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedUserMail\": {\n      \"@id\": \"pan:assigned_user_mail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedUserPrettyName\": {\n      \"@id\": \"pan:assigned_user_pretty_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"fileArtifacts\": {\n      \"@id\": \"pan:file_artifacts\",\n      \"@container\": \"@set\"\n    },\n    \"fileName\": {\n      \"@id\": \"pan:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"pan:file_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSha256\": {\n      \"@id\": \"pan:file_sha256\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSignatureStatus\": {\n      \"@id\": \"pan:file_signature_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"highSeverityAlertCount\": {\n      \"@id\": \"pan:high_severity_alert_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostCount\": {\n      \"@id\": \"pan:host_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"incidentId\": {\n      \"@id\": \"pan:incident_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentName\": {\n      \"@id\": \"pan:incident_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isManual\": {\n      \"@id\": \"pan:is_manual\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lowSeverityAlertCount\": {\n      \"@id\": \"pan:low_severity_alert_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medSeverityAlertCount\": {\n      \"@id\": \"pan:med_severity_alert_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modificationTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"networkArtifacts\": {\n      \"@id\": \"pan:network_artifacts\",\n      \"@container\": \"@set\"\n    },\n    \"networkCountry\": {\n      \"@id\": \"pan:network_country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkDomain\": {\n      \"@id\": \"pan:network_domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkRemoteIp\": {\n      \"@id\": \"pan:network_remote_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkRemotePort\": {\n      \"@id\": \"pan:network_remote_port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notes\": {\n      \"@id\": \"\
  pan:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolveComment\": {\n      \"@id\": \"pan:resolve_comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userCount\": {\n      \"@id\": \"pan:user_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"wildfireVerdict\": {\n      \"@id\": \"pan:wildfire_verdict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xdrUrl\": {\n      \"@id\": \"pan:xdr_url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xdr-context.jsonld
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
