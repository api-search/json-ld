---
api_specs:
- filename: abstract-api-email-reputation.yaml
  format: yaml
  label: Email Reputation API
  slug: email-reputation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-email-reputation.yaml
- filename: abstract-api-phone-intelligence.yaml
  format: yaml
  label: Phone Intelligence API
  slug: phone-intelligence
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-phone-intelligence.yaml
- filename: abstract-api-ip-geolocation.yaml
  format: yaml
  label: IP Geolocation API
  slug: ip-geolocation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-ip-geolocation.yaml
- filename: abstract-api-ip-intelligence.yaml
  format: yaml
  label: IP Intelligence API
  slug: ip-intelligence
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-ip-intelligence.yaml
- filename: abstract-api-company-enrichment.yaml
  format: yaml
  label: Company Enrichment API
  slug: company-enrichment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-company-enrichment.yaml
- filename: abstract-api-exchange-rates.yaml
  format: yaml
  label: Exchange Rates API
  slug: exchange-rates
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-exchange-rates.yaml
- filename: abstract-api-public-holidays.yaml
  format: yaml
  label: Public Holidays API
  slug: public-holidays
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-public-holidays.yaml
- filename: abstract-api-timezones.yaml
  format: yaml
  label: Timezone API
  slug: timezones
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-timezones.yaml
- filename: abstract-api-vat-validation.yaml
  format: yaml
  label: VAT Validation API
  slug: vat-validation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-vat-validation.yaml
- filename: abstract-api-iban-validation.yaml
  format: yaml
  label: IBAN Validation API
  slug: iban-validation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-iban-validation.yaml
- filename: abstract-api-website-screenshot.yaml
  format: yaml
  label: Website Screenshot API
  slug: website-screenshot
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-website-screenshot.yaml
- filename: abstract-api-image-processing.yaml
  format: yaml
  label: Image Processing API
  slug: image-processing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-image-processing.yaml
- filename: abstract-api-web-scraping.yaml
  format: yaml
  label: Web Scraping API
  slug: web-scraping
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-web-scraping.yaml
- filename: abstract-api-avatars.yaml
  format: yaml
  label: Avatars API
  slug: avatars
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-avatars.yaml
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
