---
class_count: 1
classes:
- ConvertTimeResponse
context_file: json-ld/abstract-api-timezones-convert-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-timezones-convert-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Timezones Convert from Abstract API.
layout: jsonld
name: Abstract Api Timezones Convert Context
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
  name: baseLocation
  type: string
- container: ''
  name: baseDatetime
  type: string
- container: ''
  name: baseTimezoneName
  type: string
- container: ''
  name: baseTimezoneAbbreviation
  type: string
- container: ''
  name: baseUtcOffset
  type: integer
- container: ''
  name: targetLocation
  type: string
- container: ''
  name: targetDatetime
  type: string
- container: ''
  name: targetTimezoneName
  type: string
- container: ''
  name: targetTimezoneAbbreviation
  type: string
- container: ''
  name: targetUtcOffset
  type: integer
property_count: 10
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-timezones-convert-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConvertTimeResponse\": \"abstract:ConvertTimeResponse\",\n    \"baseLocation\": {\n      \"@id\": \"abstract:base_location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseDatetime\": {\n      \"@id\": \"abstract:base_datetime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseTimezoneName\": {\n      \"@id\": \"abstract:base_timezone_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseTimezoneAbbreviation\": {\n      \"@id\": \"abstract:base_timezone_abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUtcOffset\": {\n      \"@id\": \"abstract:base_utc_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"targetLocation\": {\n      \"@id\": \"abstract:target_location\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"targetDatetime\": {\n      \"@id\": \"abstract:target_datetime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetTimezoneName\": {\n      \"@id\": \"abstract:target_timezone_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetTimezoneAbbreviation\": {\n      \"@id\": \"abstract:target_timezone_abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetUtcOffset\": {\n      \"@id\": \"abstract:target_utc_offset\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-timezones-convert-context.jsonld
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
