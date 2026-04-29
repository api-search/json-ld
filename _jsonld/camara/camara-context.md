---
class_count: 0
classes: []
context_file: json-ld/camara-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/json-ld/camara-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Camara from CAMARA.
layout: jsonld
name: Camara Context
namespaces:
- prefix: camara
  uri: https://camaraproject.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: Session
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: Area
  type: ''
- container: ''
  name: LocationVerificationResult
  type: ''
- container: ''
  name: NumberVerificationResult
  type: ''
- container: ''
  name: SimSwapCheck
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Consent
  type: ''
- container: ''
  name: EdgeZone
  type: ''
property_count: 9
provider_name: CAMARA
provider_slug: camara
slug: camara-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"camara\": \"https://camaraproject.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n\n    \"Session\": {\n      \"@id\": \"camara:Session\",\n      \"@context\": {\n        \"sessionId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"device\": {\n          \"@id\": \"camara:device\",\n          \"@type\": \"@id\"\n        },\n        \"qosProfile\": \"camara:qosProfile\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startedAt\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"status\": \"camara:sessionStatus\"\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"camara:Device\",\n      \"@context\": {\n        \"phoneNumber\": \"schema:telephone\",\n        \"networkAccessIdentifier\": \"camara:networkAccessIdentifier\",\n        \"ipv4Address\": \"camara:ipv4Address\",\n        \"ipv6Address\": \"camara:ipv6Address\"\n      }\n    },\n\n    \"Area\": {\n      \"@id\": \"camara:Area\",\n      \"@context\": {\n        \"areaType\": \"camara:areaType\",\n        \"center\": {\n          \"@id\": \"schema:geo\",\n          \"@type\": \"@id\"\n        },\n        \"radius\": {\n          \"@id\": \"camara:radius\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"LocationVerificationResult\": {\n      \"@id\": \"camara:LocationVerificationResult\",\n      \"@context\": {\n        \"verificationResult\": \"camara:verificationResult\",\n        \"lastLocationTime\": {\n          \"@id\": \"camara:lastLocationTime\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"NumberVerificationResult\": {\n      \"@id\": \"camara:NumberVerificationResult\",\n      \"@context\": {\n        \"devicePhoneNumberVerified\": {\n          \"@id\": \"camara:devicePhoneNumberVerified\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"SimSwapCheck\": {\n      \"@id\": \"camara:SimSwapCheck\",\n      \"@context\": {\n        \"swapped\": {\n          \"@id\": \"camara:swapped\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"latestSimChange\": {\n          \"@id\": \"camara:latestSimChange\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"maxAge\": {\n          \"@id\": \"camara:maxAge\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"camara:Subscription\",\n      \"@context\": {\n        \"subscriptionId\": \"schema:identifier\",\n        \"webhookUrl\": {\n          \"@id\"\
  : \"camara:webhookUrl\",\n          \"@type\": \"@id\"\n        },\n        \"eventType\": \"camara:eventType\",\n        \"expiresAt\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Consent\": {\n      \"@id\": \"camara:Consent\",\n      \"@context\": {\n        \"subject\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"@id\"\n        },\n        \"scope\": \"schema:scope\",\n        \"grantedAt\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EdgeZone\": {\n      \"@id\": \"camara:EdgeZone\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"edgeCloudProvider\": \"camara:edgeCloudProvider\",\n        \"edgeResourceName\": \"camara:edgeResourceName\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/json-ld/camara-context.jsonld
tags:
- Telecom
- Network APIs
- Standards
- Linux Foundation
- Open Gateway
- GSMA
- Connectivity
- 5G
- JSON-LD
- Linked Data
- Semantic Web
---
