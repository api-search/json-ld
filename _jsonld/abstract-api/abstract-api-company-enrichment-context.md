---
class_count: 1
classes:
- CompanyEnrichmentResponse
context_file: json-ld/abstract-api-company-enrichment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-company-enrichment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Company Enrichment from Abstract API.
layout: jsonld
name: Abstract Api Company Enrichment Context
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
  name: domain
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: locality
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: linkedinUrl
  type: reference
- container: ''
  name: logo
  type: reference
- container: ''
  name: yearFounded
  type: integer
- container: ''
  name: industry
  type: string
- container: ''
  name: employeesCount
  type: integer
- container: ''
  name: description
  type: ''
property_count: 11
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-company-enrichment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CompanyEnrichmentResponse\": \"abstract:CompanyEnrichmentResponse\",\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"domain\": {\n      \"@id\": \"abstract:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locality\": {\n      \"@id\": \"abstract:locality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"abstract:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linkedinUrl\": {\n      \"@id\": \"abstract:linkedin_url\",\n      \"@type\": \"@id\"\n    },\n    \"logo\": {\n      \"@id\": \"abstract:logo\",\n      \"@type\": \"@id\"\n    },\n    \"yearFounded\": {\n   \
  \   \"@id\": \"abstract:year_founded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"industry\": {\n      \"@id\": \"abstract:industry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employeesCount\": {\n      \"@id\": \"abstract:employees_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-company-enrichment-context.jsonld
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
