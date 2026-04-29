---
class_count: 1
classes:
- WebScrapingResponse
context_file: json-ld/abstract-api-web-scraping-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-web-scraping-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Web Scraping from Abstract API.
layout: jsonld
name: Abstract Api Web Scraping Context
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
  name: body
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: statusCode
  type: integer
property_count: 3
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-web-scraping-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WebScrapingResponse\": \"abstract:WebScrapingResponse\",\n    \"body\": {\n      \"@id\": \"abstract:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"statusCode\": {\n      \"@id\": \"abstract:status_code\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-web-scraping-context.jsonld
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
