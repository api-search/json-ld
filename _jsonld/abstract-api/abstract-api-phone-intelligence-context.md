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
