---
class_count: 1
classes:
- IBANValidationResponse
context_file: json-ld/abstract-api-iban-validation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-iban-validation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Iban Validation from Abstract API.
layout: jsonld
name: Abstract Api Iban Validation Context
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
  name: iban
  type: string
- container: ''
  name: isValid
  type: boolean
- container: ''
  name: country
  type: reference
- container: ''
  name: code
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: bank
  type: reference
- container: ''
  name: bankName
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: bic
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: checkDigits
  type: string
- container: ''
  name: sepaMember
  type: boolean
property_count: 12
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-iban-validation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IBANValidationResponse\": \"abstract:IBANValidationResponse\",\n    \"iban\": {\n      \"@id\": \"abstract:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isValid\": {\n      \"@id\": \"abstract:is_valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"@id\"\n    },\n    \"code\": {\n      \"@id\": \"abstract:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"bank\": {\n      \"@id\": \"abstract:bank\",\n      \"@type\": \"@id\"\n    },\n    \"bankName\": {\n      \"@id\": \"abstract:bank_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"abstract:bank_code\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"bic\": {\n      \"@id\": \"abstract:bic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"abstract:account_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkDigits\": {\n      \"@id\": \"abstract:check_digits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sepaMember\": {\n      \"@id\": \"abstract:sepa_member\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-iban-validation-context.jsonld
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
