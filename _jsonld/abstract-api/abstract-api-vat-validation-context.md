---
class_count: 3
classes:
- VATCalculateResponse
- VATRatesResponse
- VATValidationResponse
context_file: json-ld/abstract-api-vat-validation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-vat-validation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Vat Validation from Abstract API.
layout: jsonld
name: Abstract Api Vat Validation Context
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
  name: amountExclVat
  type: decimal
- container: ''
  name: vatAmount
  type: decimal
- container: ''
  name: amountInclVat
  type: decimal
- container: ''
  name: vatCategory
  type: string
- container: ''
  name: vatRate
  type: decimal
- container: ''
  name: countryCode
  type: string
- container: ''
  name: countryName
  type: string
- container: ''
  name: standardRate
  type: decimal
- container: set
  name: reducedRates
  type: decimal
- container: ''
  name: superReducedRate
  type: decimal
- container: ''
  name: parkingRate
  type: decimal
- container: ''
  name: vatNumber
  type: string
- container: ''
  name: valid
  type: boolean
- container: ''
  name: company
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: address
  type: string
- container: ''
  name: country
  type: reference
- container: ''
  name: code
  type: string
property_count: 18
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-vat-validation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VATCalculateResponse\": \"abstract:VATCalculateResponse\",\n    \"VATRatesResponse\": \"abstract:VATRatesResponse\",\n    \"VATValidationResponse\": \"abstract:VATValidationResponse\",\n    \"amountExclVat\": {\n      \"@id\": \"abstract:amount_excl_vat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vatAmount\": {\n      \"@id\": \"abstract:vat_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"amountInclVat\": {\n      \"@id\": \"abstract:amount_incl_vat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vatCategory\": {\n      \"@id\": \"abstract:vat_category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vatRate\": {\n      \"@id\": \"abstract:vat_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"countryCode\"\
  : {\n      \"@id\": \"abstract:country_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryName\": {\n      \"@id\": \"abstract:country_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardRate\": {\n      \"@id\": \"abstract:standard_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"reducedRates\": {\n      \"@id\": \"abstract:reduced_rates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"superReducedRate\": {\n      \"@id\": \"abstract:super_reduced_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"parkingRate\": {\n      \"@id\": \"abstract:parking_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vatNumber\": {\n      \"@id\": \"abstract:vat_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valid\": {\n      \"@id\": \"abstract:valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"company\": {\n      \"@id\": \"abstract:company\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\"\
  : \"schema:name\"\n    },\n    \"address\": {\n      \"@id\": \"abstract:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"@id\"\n    },\n    \"code\": {\n      \"@id\": \"abstract:code\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-vat-validation-context.jsonld
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
