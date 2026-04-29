---
class_count: 2
classes:
- PhoneCountry
- PhoneIntelligenceResponse
context_file: json-ld/abstract-api-phone-intelligence-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-phone-intelligence-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Phone Intelligence from Abstract API.
layout: jsonld
name: Abstract Api Phone Intelligence Context
namespaces:
- prefix: abstract
  uri: https://abstractapi.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: code
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: prefix
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: valid
  type: boolean
- container: ''
  name: country
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: isVoip
  type: boolean
- container: ''
  name: riskScore
  type: integer
property_count: 11
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-phone-intelligence-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PhoneCountry\": \"abstract:PhoneCountry\",\n    \"PhoneIntelligenceResponse\": \"abstract:PhoneIntelligenceResponse\",\n    \"code\": {\n      \"@id\": \"abstract:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"prefix\": {\n      \"@id\": \"abstract:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"abstract:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valid\": {\n      \"@id\": \"abstract:valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"abstract:location\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"abstract:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"abstract:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isVoip\": {\n      \"@id\": \"abstract:is_voip\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"riskScore\": {\n      \"@id\": \"abstract:risk_score\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-phone-intelligence-context.jsonld
tags:
- Avatars
- Company Enrichment
- Contacts
- Currencies
- Email Validation
- Exchange Rates
- IBAN Validation
- Image Processing
- IP Geolocation
- IP Intelligence
- Phone Validation
- Public Holidays
- Screenshots
- Timezones
- VAT Validation
- Web Scraping
- JSON-LD
- Linked Data
- Semantic Web
---
