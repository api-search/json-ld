---
class_count: 5
classes:
- ApiCallLog
- AttackDetection
- LoggingRule
- SecurityEvent
- DataLeak
context_file: json-ld/resurface-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/json-ld/resurface-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Resurface from Resurface.
layout: jsonld
name: Resurface Context
namespaces:
- prefix: resurface
  uri: https://resurface.io/ns/
- prefix: security
  uri: https://w3id.org/security#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: requestMethod
  type: string
- container: ''
  name: requestUrl
  type: string
- container: ''
  name: requestBody
  type: string
- container: ''
  name: responseCode
  type: integer
- container: ''
  name: responseBody
  type: string
- container: ''
  name: intervalMillis
  type: long
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: hostField
  type: string
- container: ''
  name: threatType
  type: string
- container: ''
  name: severity
  type: string
property_count: 10
provider_name: Resurface
provider_slug: resurface
slug: resurface-context
source_filename: resurface-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"resurface\": \"https://resurface.io/ns/\",\n    \"security\": \"https://w3id.org/security#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ApiCallLog\": \"resurface:ApiCallLog\",\n    \"AttackDetection\": \"resurface:AttackDetection\",\n    \"LoggingRule\": \"resurface:LoggingRule\",\n    \"SecurityEvent\": \"schema:Event\",\n    \"DataLeak\": \"resurface:DataLeak\",\n\n    \"requestMethod\": {\n      \"@id\": \"resurface:requestMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestUrl\": {\n      \"@id\": \"resurface:requestUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestBody\": {\n      \"@id\": \"resurface:requestBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseCode\": {\n      \"@id\": \"resurface:responseCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"responseBody\": {\n      \"@id\": \"\
  resurface:responseBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"intervalMillis\": {\n      \"@id\": \"resurface:intervalMillis\",\n      \"@type\": \"xsd:long\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"hostField\": {\n      \"@id\": \"resurface:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatType\": {\n      \"@id\": \"resurface:threatType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"resurface:severity\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/json-ld/resurface-context.jsonld
tags:
- API Analytics
- API Compliance
- API Logging
- API Observability
- API Security
- Data Leak Prevention
- Runtime Security
- SIEM
- Threat Detection
- JSON-LD
- Linked Data
- Semantic Web
---
