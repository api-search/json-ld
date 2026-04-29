---
class_count: 9
classes:
- ApiStats
- AtpReport
- AtpReportList
- ReleaseNote
- ReleaseNotesList
- ThreatHistoryEntry
- ThreatHistoryList
- ThreatList
- ThreatSignature
context_file: json-ld/palo-alto-threat-vault-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-threat-vault-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Threat Vault Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Threat Vault Api Context
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
  name: apiKey
  type: string
- container: set
  name: behaviors
  type: reference
- container: set
  name: connections
  type: reference
- container: ''
  name: count
  type: integer
- container: ''
  name: createTime
  type: dateTime
- container: set
  name: cve
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: defaultAction
  type: string
- container: ''
  name: deprecatedSignatures
  type: integer
- container: ''
  name: description
  type: string
- container: set
  name: dnsQueries
  type: string
- container: ''
  name: dstIp
  type: string
- container: ''
  name: dstPort
  type: integer
- container: ''
  name: endpointUsage
  type: reference
- container: ''
  name: fileType
  type: string
- container: ''
  name: firstReleaseTime
  type: dateTime
- container: set
  name: httpRequests
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: latestReleaseTime
  type: dateTime
- container: ''
  name: latestReleaseVersion
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: maxVersion
  type: string
- container: ''
  name: minVersion
  type: string
- container: ''
  name: modifiedSignatures
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: network
  type: reference
- container: ''
  name: newSignatures
  type: integer
- container: ''
  name: notes
  type: string
- container: ''
  name: offset
  type: integer
- container: ''
  name: oriReleaseVersion
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: quota
  type: integer
- container: ''
  name: releaseDate
  type: date
- container: ''
  name: releaseTime
  type: dateTime
- container: ''
  name: remaining
  type: integer
- container: ''
  name: report
  type: reference
- container: ''
  name: resetTime
  type: dateTime
- container: ''
  name: severity
  type: string
- container: ''
  name: sha256
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: subtype
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: total
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: used
  type: integer
- container: ''
  name: verdict
  type: string
- container: ''
  name: version
  type: string
- container: set
  name: zingbox
  type: reference
property_count: 50
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-threat-vault-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiStats\": \"pan:ApiStats\",\n    \"AtpReport\": \"pan:AtpReport\",\n    \"AtpReportList\": \"pan:AtpReportList\",\n    \"ReleaseNote\": \"pan:ReleaseNote\",\n    \"ReleaseNotesList\": \"pan:ReleaseNotesList\",\n    \"ThreatHistoryEntry\": \"pan:ThreatHistoryEntry\",\n    \"ThreatHistoryList\": \"pan:ThreatHistoryList\",\n    \"ThreatList\": \"pan:ThreatList\",\n    \"ThreatSignature\": \"pan:ThreatSignature\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiKey\": {\n      \"@id\": \"pan:api_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"behaviors\": {\n      \"@id\": \"pan:behaviors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"connections\": {\n\
  \      \"@id\": \"pan:connections\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createTime\": {\n      \"@id\": \"pan:create_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"cve\": {\n      \"@id\": \"pan:cve\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@type\": \"@id\"\n    },\n    \"defaultAction\": {\n      \"@id\": \"pan:default_action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deprecatedSignatures\": {\n      \"@id\": \"pan:deprecated_signatures\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsQueries\": {\n      \"@id\": \"pan:dns_queries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dstIp\": {\n      \"@id\":\
  \ \"pan:dst_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dstPort\": {\n      \"@id\": \"pan:dst_port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endpointUsage\": {\n      \"@id\": \"pan:endpoint_usage\",\n      \"@type\": \"@id\"\n    },\n    \"fileType\": {\n      \"@id\": \"pan:file_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstReleaseTime\": {\n      \"@id\": \"pan:first_release_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"httpRequests\": {\n      \"@id\": \"pan:http_requests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestReleaseTime\": {\n      \"@id\": \"pan:latest_release_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"latestReleaseVersion\": {\n      \"@id\": \"pan:latest_release_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"pan:limit\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"maxVersion\": {\n      \"@id\": \"pan:max_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minVersion\": {\n      \"@id\": \"pan:min_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifiedSignatures\": {\n      \"@id\": \"pan:modified_signatures\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"pan:network\",\n      \"@type\": \"@id\"\n    },\n    \"newSignatures\": {\n      \"@id\": \"pan:new_signatures\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notes\": {\n      \"@id\": \"pan:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"pan:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"oriReleaseVersion\": {\n      \"@id\": \"pan:ori_release_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"pan:protocol\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"quota\": {\n      \"@id\": \"pan:quota\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"releaseDate\": {\n      \"@id\": \"pan:release_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"releaseTime\": {\n      \"@id\": \"pan:release_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"remaining\": {\n      \"@id\": \"pan:remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"report\": {\n      \"@id\": \"pan:report\",\n      \"@type\": \"@id\"\n    },\n    \"resetTime\": {\n      \"@id\": \"pan:reset_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sha256\": {\n      \"@id\": \"pan:sha256\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"pan:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtype\": {\n  \
  \    \"@id\": \"pan:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"pan:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"total\": {\n      \"@id\": \"pan:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"used\": {\n      \"@id\": \"pan:used\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"verdict\": {\n      \"@id\": \"pan:verdict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zingbox\": {\n      \"@id\": \"pan:zingbox\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-threat-vault-api-context.jsonld
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
