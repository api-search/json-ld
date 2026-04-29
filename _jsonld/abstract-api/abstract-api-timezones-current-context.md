---
class_count: 1
classes:
- CurrentTimeResponse
context_file: json-ld/abstract-api-timezones-current-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-timezones-current-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Timezones Current from Abstract API.
layout: jsonld
name: Abstract Api Timezones Current Context
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
  name: datetime
  type: string
- container: ''
  name: timezoneName
  type: string
- container: ''
  name: timezoneLocation
  type: string
- container: ''
  name: timezoneAbbreviation
  type: string
- container: ''
  name: gmtOffset
  type: integer
- container: ''
  name: isDst
  type: boolean
- container: ''
  name: requestedLocation
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
property_count: 9
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-timezones-current-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CurrentTimeResponse\": \"abstract:CurrentTimeResponse\",\n    \"datetime\": {\n      \"@id\": \"abstract:datetime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezoneName\": {\n      \"@id\": \"abstract:timezone_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezoneLocation\": {\n      \"@id\": \"abstract:timezone_location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezoneAbbreviation\": {\n      \"@id\": \"abstract:timezone_abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gmtOffset\": {\n      \"@id\": \"abstract:gmt_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isDst\": {\n      \"@id\": \"abstract:is_dst\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requestedLocation\"\
  : {\n      \"@id\": \"abstract:requested_location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"abstract:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"abstract:longitude\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-timezones-current-context.jsonld
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
