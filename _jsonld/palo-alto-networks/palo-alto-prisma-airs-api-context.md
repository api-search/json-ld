---
class_count: 5
classes:
- AIProfile
- ContentScanResult
- ScanContent
- ScanRequest
- ScanResponse
context_file: json-ld/palo-alto-prisma-airs-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-airs-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Airs Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Airs Api Context
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
  name: aiProfile
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: set
  name: contents
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: set
  name: detectionCategories
  type: reference
- container: ''
  name: dlp
  type: boolean
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: injection
  type: boolean
- container: ''
  name: profileId
  type: string
- container: ''
  name: profileName
  type: string
- container: ''
  name: prompt
  type: string
- container: ''
  name: promptDetected
  type: reference
- container: ''
  name: reportId
  type: string
- container: ''
  name: response
  type: string
- container: ''
  name: responseDetected
  type: reference
- container: set
  name: results
  type: reference
- container: ''
  name: scanCategory
  type: string
- container: ''
  name: scanId
  type: string
- container: ''
  name: sensitivity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: toxicContent
  type: boolean
- container: ''
  name: trId
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: urlCats
  type: boolean
- container: ''
  name: verdict
  type: string
property_count: 28
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-airs-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AIProfile\": \"pan:AIProfile\",\n    \"ContentScanResult\": \"pan:ContentScanResult\",\n    \"ScanContent\": \"pan:ScanContent\",\n    \"ScanRequest\": \"pan:ScanRequest\",\n    \"ScanResponse\": \"pan:ScanResponse\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aiProfile\": {\n      \"@id\": \"pan:ai_profile\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"pan:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"contents\": {\n      \"@id\": \"pan:contents\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n\
  \      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectionCategories\": {\n      \"@id\": \"pan:detection_categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"dlp\": {\n      \"@id\": \"pan:dlp\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"injection\": {\n      \"@id\": \"pan:injection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"profileId\": {\n      \"@id\": \"pan:profile_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileName\": {\n      \"@id\": \"pan:profile_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prompt\": {\n      \"@id\": \"pan:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"promptDetected\": {\n      \"@id\": \"pan:prompt_detected\",\n      \"@type\": \"@id\"\
  \n    },\n    \"reportId\": {\n      \"@id\": \"pan:report_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"response\": {\n      \"@id\": \"pan:response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseDetected\": {\n      \"@id\": \"pan:response_detected\",\n      \"@type\": \"@id\"\n    },\n    \"results\": {\n      \"@id\": \"pan:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"scanCategory\": {\n      \"@id\": \"pan:scan_category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanId\": {\n      \"@id\": \"pan:scan_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensitivity\": {\n      \"@id\": \"pan:sensitivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toxicContent\": {\n      \"@id\": \"pan:toxic_content\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"trId\": {\n      \"@id\": \"pan:tr_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"urlCats\": {\n      \"@id\": \"pan:url_cats\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"verdict\": {\n      \"@id\": \"pan:verdict\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-airs-api-context.jsonld
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
