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
