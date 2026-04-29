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
class_count: 8
classes:
- ASNInfo
- CompanyBasic
- CurrencyInfo
- FlagInfo
- IPIntelligenceResponse
- IPSecurityFlags
- LocationInfo
- TimezoneInfo
context_file: json-ld/abstract-api-ip-intelligence-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-ip-intelligence-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Ip Intelligence from Abstract API.
layout: jsonld
name: Abstract Api Ip Intelligence Context
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
  name: asn
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: domain
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: isoCode
  type: string
- container: ''
  name: symbol
  type: string
- container: ''
  name: emoji
  type: string
- container: ''
  name: unicode
  type: string
- container: ''
  name: png
  type: reference
- container: ''
  name: svg
  type: reference
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: security
  type: string
- container: ''
  name: company
  type: string
- container: set
  name: domains
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: flag
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: isVpn
  type: boolean
- container: ''
  name: isProxy
  type: boolean
- container: ''
  name: isTor
  type: boolean
- container: ''
  name: isHosting
  type: boolean
- container: ''
  name: isRelay
  type: boolean
- container: ''
  name: isMobile
  type: boolean
- container: ''
  name: isAbuse
  type: boolean
- container: ''
  name: city
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: abbreviation
  type: string
- container: ''
  name: utcOffset
  type: integer
- container: ''
  name: localTime
  type: string
- container: ''
  name: isDst
  type: boolean
property_count: 35
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-ip-intelligence-context
source_filename: abstract-api-ip-intelligence-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ASNInfo\": \"abstract:ASNInfo\",\n    \"CompanyBasic\": \"abstract:CompanyBasic\",\n    \"CurrencyInfo\": \"abstract:CurrencyInfo\",\n    \"FlagInfo\": \"abstract:FlagInfo\",\n    \"IPIntelligenceResponse\": \"abstract:IPIntelligenceResponse\",\n    \"IPSecurityFlags\": \"abstract:IPSecurityFlags\",\n    \"LocationInfo\": \"abstract:LocationInfo\",\n    \"TimezoneInfo\": \"abstract:TimezoneInfo\",\n    \"asn\": {\n      \"@id\": \"abstract:asn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"domain\": {\n      \"@id\": \"abstract:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"abstract:type\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"isoCode\": {\n      \"@id\": \"abstract:iso_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"symbol\": {\n      \"@id\": \"abstract:symbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emoji\": {\n      \"@id\": \"abstract:emoji\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unicode\": {\n      \"@id\": \"abstract:unicode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"png\": {\n      \"@id\": \"abstract:png\",\n      \"@type\": \"@id\"\n    },\n    \"svg\": {\n      \"@id\": \"abstract:svg\",\n      \"@type\": \"@id\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"abstract:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"security\": {\n      \"@id\": \"abstract:security\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"abstract:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domains\": {\n      \"@id\": \"abstract:domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"location\": {\n      \"@id\": \"abstract:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"abstract:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flag\": {\n      \"@id\": \"abstract:flag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"abstract:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isVpn\": {\n      \"@id\": \"abstract:is_vpn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isProxy\": {\n      \"@id\": \"abstract:is_proxy\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isTor\": {\n      \"@id\": \"abstract:is_tor\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isHosting\": {\n      \"@id\": \"abstract:is_hosting\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isRelay\": {\n      \"@id\": \"abstract:is_relay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isMobile\": {\n      \"@id\": \"abstract:is_mobile\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"isAbuse\": {\n      \"@id\": \"abstract:is_abuse\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"city\": {\n      \"@id\": \"abstract:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"abstract:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"abstract:country_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"abstract:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"abstract:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"abbreviation\": {\n      \"@id\": \"abstract:abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utcOffset\": {\n      \"@id\": \"abstract:utc_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"localTime\": {\n      \"@id\": \"abstract:local_time\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"isDst\": {\n      \"@id\": \"abstract:is_dst\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-ip-intelligence-context.jsonld
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
