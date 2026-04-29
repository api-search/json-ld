---
class_count: 5
classes:
- AuthLogPayload
- ThreatLogPayload
- TrafficLogPayload
- UrlLogPayload
- WildfireLogPayload
context_file: json-ld/palo-alto-strata-logging-forwarding-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-strata-logging-forwarding-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Strata Logging Forwarding from Palo Alto Networks.
layout: jsonld
name: Palo Alto Strata Logging Forwarding Context
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
  name: app
  type: string
- container: ''
  name: authMethod
  type: string
- container: ''
  name: authProfile
  type: string
- container: ''
  name: authResult
  type: string
- container: ''
  name: authSource
  type: string
- container: ''
  name: bytesReceived
  type: integer
- container: ''
  name: bytesSent
  type: integer
- container: ''
  name: contentType
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: dport
  type: integer
- container: ''
  name: dst
  type: string
- container: ''
  name: dstUser
  type: string
- container: ''
  name: dstZone
  type: string
- container: ''
  name: fileHash
  type: string
- container: ''
  name: fileSize
  type: integer
- container: ''
  name: filename
  type: string
- container: ''
  name: filetype
  type: string
- container: ''
  name: httpMethod
  type: string
- container: ''
  name: logForwardingProfile
  type: string
- container: ''
  name: mfaResult
  type: string
- container: ''
  name: mfaVendor
  type: string
- container: ''
  name: natDport
  type: integer
- container: ''
  name: natDst
  type: string
- container: ''
  name: natSport
  type: integer
- container: ''
  name: natSrc
  type: string
- container: ''
  name: outputFormat
  type: string
- container: ''
  name: packetsReceived
  type: integer
- container: ''
  name: packetsSent
  type: integer
- container: ''
  name: proto
  type: string
- container: ''
  name: receiveTime
  type: dateTime
- container: ''
  name: reportUrl
  type: reference
- container: ''
  name: ruleName
  type: string
- container: ''
  name: serial
  type: string
- container: ''
  name: sessionDuration
  type: integer
- container: ''
  name: sessionId
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: sport
  type: integer
- container: ''
  name: src
  type: string
- container: ''
  name: srcUser
  type: string
- container: ''
  name: srcZone
  type: string
- container: ''
  name: subtype
  type: string
- container: ''
  name: threatId
  type: string
- container: ''
  name: threatName
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: string
- container: ''
  name: urlCategory
  type: string
- container: ''
  name: urlOrFilename
  type: string
- container: ''
  name: verdict
  type: string
- container: ''
  name: vsys
  type: string
property_count: 51
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-strata-logging-forwarding-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthLogPayload\": \"pan:AuthLogPayload\",\n    \"ThreatLogPayload\": \"pan:ThreatLogPayload\",\n    \"TrafficLogPayload\": \"pan:TrafficLogPayload\",\n    \"UrlLogPayload\": \"pan:UrlLogPayload\",\n    \"WildfireLogPayload\": \"pan:WildfireLogPayload\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"app\": {\n      \"@id\": \"pan:app\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authMethod\": {\n      \"@id\": \"pan:auth_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authProfile\": {\n      \"@id\": \"pan:auth_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authResult\": {\n      \"@id\": \"pan:auth_result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authSource\"\
  : {\n      \"@id\": \"pan:auth_source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bytesReceived\": {\n      \"@id\": \"pan:bytes_received\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bytesSent\": {\n      \"@id\": \"pan:bytes_sent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contentType\": {\n      \"@id\": \"pan:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n      \"@id\": \"pan:device_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"pan:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dport\": {\n      \"@id\": \"pan:dport\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dst\": {\n      \"@id\": \"pan:dst\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dstUser\": {\n      \"@id\": \"pan:dst_user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dstZone\": {\n      \"@id\": \"pan:dst_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileHash\": {\n      \"@id\": \"pan:file_hash\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSize\": {\n      \"@id\": \"pan:file_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filename\": {\n      \"@id\": \"pan:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filetype\": {\n      \"@id\": \"pan:filetype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpMethod\": {\n      \"@id\": \"pan:http_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logForwardingProfile\": {\n      \"@id\": \"pan:log_forwarding_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mfaResult\": {\n      \"@id\": \"pan:mfa_result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mfaVendor\": {\n      \"@id\": \"pan:mfa_vendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"natDport\": {\n      \"@id\": \"pan:nat_dport\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"natDst\": {\n      \"@id\": \"pan:nat_dst\",\n      \"@type\": \"xsd:string\"\n    },\n    \"natSport\": {\n      \"@id\": \"pan:nat_sport\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"natSrc\": {\n      \"@id\": \"pan:nat_src\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputFormat\": {\n      \"@id\": \"pan:output_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packetsReceived\": {\n      \"@id\": \"pan:packets_received\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"packetsSent\": {\n      \"@id\": \"pan:packets_sent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"proto\": {\n      \"@id\": \"pan:proto\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receiveTime\": {\n      \"@id\": \"pan:receive_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reportUrl\": {\n      \"@id\": \"pan:report_url\",\n      \"@type\": \"@id\"\n    },\n    \"ruleName\": {\n      \"@id\": \"pan:rule_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serial\": {\n      \"@id\": \"pan:serial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionDuration\": {\n      \"@id\": \"pan:session_duration\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"sessionId\": {\n      \"@id\": \"pan:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sport\": {\n      \"@id\": \"pan:sport\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"src\": {\n      \"@id\": \"pan:src\",\n      \"@type\": \"xsd:string\"\n    },\n    \"srcUser\": {\n      \"@id\": \"pan:src_user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"srcZone\": {\n      \"@id\": \"pan:src_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtype\": {\n      \"@id\": \"pan:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatId\": {\n      \"@id\": \"pan:threat_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatName\": {\n      \"@id\": \"pan:threat_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\":\
  \ {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urlCategory\": {\n      \"@id\": \"pan:url_category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urlOrFilename\": {\n      \"@id\": \"pan:url_or_filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verdict\": {\n      \"@id\": \"pan:verdict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vsys\": {\n      \"@id\": \"pan:vsys\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-strata-logging-forwarding-context.jsonld
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
