---
class_count: 1
classes:
- Holiday
context_file: json-ld/abstract-api-public-holidays-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-public-holidays-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Public Holidays from Abstract API.
layout: jsonld
name: Abstract Api Public Holidays Context
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
  name: name
  type: ''
- container: ''
  name: nameLocal
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: description
  type: ''
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
  name: date
  type: string
- container: ''
  name: dateYear
  type: string
- container: ''
  name: dateMonth
  type: string
- container: ''
  name: dateDay
  type: string
- container: ''
  name: weekDay
  type: string
property_count: 12
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-public-holidays-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Holiday\": \"abstract:Holiday\",\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"nameLocal\": {\n      \"@id\": \"abstract:name_local\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"abstract:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"abstract:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"abstract:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"abstract:date\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"dateYear\": {\n      \"@id\": \"abstract:date_year\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateMonth\": {\n      \"@id\": \"abstract:date_month\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateDay\": {\n      \"@id\": \"abstract:date_day\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weekDay\": {\n      \"@id\": \"abstract:week_day\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-public-holidays-context.jsonld
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
