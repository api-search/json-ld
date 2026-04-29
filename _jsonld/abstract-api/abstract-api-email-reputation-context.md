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
class_count: 7
classes:
- BreachInfo
- Deliverability
- DomainInfo
- EmailQuality
- EmailReputationResponse
- RiskInfo
- SenderInfo
context_file: json-ld/abstract-api-email-reputation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-email-reputation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Email Reputation from Abstract API.
layout: jsonld
name: Abstract Api Email Reputation Context
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
  name: totalBreaches
  type: integer
- container: ''
  name: dateFirstBreached
  type: date
- container: ''
  name: dateLastBreached
  type: date
- container: set
  name: breachedDomains
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusDetail
  type: string
- container: ''
  name: isFormatValid
  type: boolean
- container: ''
  name: isSmtpValid
  type: boolean
- container: ''
  name: isMxValid
  type: boolean
- container: set
  name: mxRecords
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: domainAge
  type: integer
- container: ''
  name: isLiveSite
  type: boolean
- container: ''
  name: registrar
  type: string
- container: ''
  name: registrarUrl
  type: reference
- container: ''
  name: dateRegistered
  type: date
- container: ''
  name: dateLastRenewed
  type: date
- container: ''
  name: dateExpires
  type: date
- container: ''
  name: isRiskyTld
  type: boolean
- container: ''
  name: score
  type: decimal
- container: ''
  name: isFreeEmail
  type: boolean
- container: ''
  name: isUsernameSuspicious
  type: boolean
- container: ''
  name: isDisposable
  type: boolean
- container: ''
  name: isCatchall
  type: boolean
- container: ''
  name: isSubaddress
  type: boolean
- container: ''
  name: isRole
  type: boolean
- container: ''
  name: isDmarcEnforced
  type: boolean
- container: ''
  name: isSpfStrict
  type: boolean
- container: ''
  name: minimumAge
  type: integer
- container: ''
  name: email
  type: ''
- container: ''
  name: deliverability
  type: string
- container: ''
  name: quality
  type: string
- container: ''
  name: sender
  type: string
- container: ''
  name: risk
  type: string
- container: ''
  name: breaches
  type: string
- container: ''
  name: addressRiskStatus
  type: string
- container: ''
  name: domainRiskStatus
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: emailProviderName
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: organizationType
  type: string
property_count: 42
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-email-reputation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BreachInfo\": \"abstract:BreachInfo\",\n    \"Deliverability\": \"abstract:Deliverability\",\n    \"DomainInfo\": \"abstract:DomainInfo\",\n    \"EmailQuality\": \"abstract:EmailQuality\",\n    \"EmailReputationResponse\": \"abstract:EmailReputationResponse\",\n    \"RiskInfo\": \"abstract:RiskInfo\",\n    \"SenderInfo\": \"abstract:SenderInfo\",\n    \"totalBreaches\": {\n      \"@id\": \"abstract:total_breaches\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dateFirstBreached\": {\n      \"@id\": \"abstract:date_first_breached\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dateLastBreached\": {\n      \"@id\": \"abstract:date_last_breached\",\n      \"@type\": \"xsd:date\"\n    },\n    \"breachedDomains\": {\n      \"\
  @id\": \"abstract:breached_domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"abstract:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusDetail\": {\n      \"@id\": \"abstract:status_detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFormatValid\": {\n      \"@id\": \"abstract:is_format_valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSmtpValid\": {\n      \"@id\": \"abstract:is_smtp_valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isMxValid\": {\n      \"@id\": \"abstract:is_mx_valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"mxRecords\": {\n      \"@id\": \"abstract:mx_records\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"abstract:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainAge\": {\n      \"@id\": \"abstract:domain_age\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isLiveSite\"\
  : {\n      \"@id\": \"abstract:is_live_site\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"registrar\": {\n      \"@id\": \"abstract:registrar\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrarUrl\": {\n      \"@id\": \"abstract:registrar_url\",\n      \"@type\": \"@id\"\n    },\n    \"dateRegistered\": {\n      \"@id\": \"abstract:date_registered\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dateLastRenewed\": {\n      \"@id\": \"abstract:date_last_renewed\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dateExpires\": {\n      \"@id\": \"abstract:date_expires\",\n      \"@type\": \"xsd:date\"\n    },\n    \"isRiskyTld\": {\n      \"@id\": \"abstract:is_risky_tld\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"score\": {\n      \"@id\": \"abstract:score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isFreeEmail\": {\n      \"@id\": \"abstract:is_free_email\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUsernameSuspicious\": {\n      \"@id\": \"abstract:is_username_suspicious\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDisposable\": {\n      \"@id\": \"abstract:is_disposable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isCatchall\": {\n      \"@id\": \"abstract:is_catchall\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSubaddress\": {\n      \"@id\": \"abstract:is_subaddress\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isRole\": {\n      \"@id\": \"abstract:is_role\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDmarcEnforced\": {\n      \"@id\": \"abstract:is_dmarc_enforced\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSpfStrict\": {\n      \"@id\": \"abstract:is_spf_strict\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"minimumAge\": {\n      \"@id\": \"abstract:minimum_age\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"deliverability\": {\n      \"@id\": \"abstract:deliverability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality\": {\n\
  \      \"@id\": \"abstract:quality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sender\": {\n      \"@id\": \"abstract:sender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"risk\": {\n      \"@id\": \"abstract:risk\",\n      \"@type\": \"xsd:string\"\n    },\n    \"breaches\": {\n      \"@id\": \"abstract:breaches\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressRiskStatus\": {\n      \"@id\": \"abstract:address_risk_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainRiskStatus\": {\n      \"@id\": \"abstract:domain_risk_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"abstract:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"abstract:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailProviderName\": {\n      \"@id\": \"abstract:email_provider_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationName\": {\n      \"@id\": \"abstract:organization_name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationType\": {\n      \"@id\": \"abstract:organization_type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-email-reputation-context.jsonld
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
