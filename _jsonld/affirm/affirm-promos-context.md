---
api_specs:
- filename: affirm-direct-api-openapi.yml
  format: yaml
  label: Affirm Direct API
  slug: direct-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-direct-api-openapi.yml
- filename: affirm-checkout-openapi.yml
  format: yaml
  label: Affirm Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-checkout-openapi.yml
- filename: affirm-transactions-openapi.yml
  format: yaml
  label: Affirm Transactions API
  slug: transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-transactions-openapi.yml
- filename: affirm-promos-openapi.yml
  format: yaml
  label: Affirm Promos API
  slug: promos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-promos-openapi.yml
- filename: affirm-disputes-openapi.yml
  format: yaml
  label: Affirm Disputes API
  slug: disputes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-disputes-openapi.yml
class_count: 6
classes:
- PromoConfig
- FinancingTerm
- PromoResponse
- PromoContent
- description
- OfferContent
context_file: json-ld/affirm-promos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-promos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Affirm Promos from affirm.
layout: jsonld
name: Affirm Promos Context
namespaces:
- prefix: affirm
  uri: https://affirm.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: promoPrequalEnabled
  type: boolean
- container: ''
  name: merchantName
  type: string
- container: ''
  name: merchantAri
  type: string
- container: ''
  name: userAri
  type: string
- container: ''
  name: toastEnabled
  type: boolean
- container: set
  name: enabledIntegrations
  type: string
- container: ''
  name: images
  type: reference
- container: ''
  name: hero
  type: reference
- container: ''
  name: hero2x
  type: reference
- container: ''
  name: logo
  type: reference
- container: ''
  name: logo2x
  type: reference
- container: ''
  name: amount
  type: integer
- container: ''
  name: loanType
  type: string
- container: ''
  name: apr
  type: decimal
- container: ''
  name: installmentAmount
  type: integer
- container: ''
  name: installmentCount
  type: integer
- container: ''
  name: interestAmount
  type: integer
- container: ''
  name: totalAmount
  type: integer
- container: ''
  name: promo
  type: string
- container: ''
  name: offer
  type: string
- container: ''
  name: ala
  type: string
- container: ''
  name: htmlAla
  type: string
- container: ''
  name: headline
  type: string
- container: ''
  name: tagline
  type: string
- container: ''
  name: button
  type: string
- container: ''
  name: htmlFooter
  type: string
- container: ''
  name: config
  type: string
- container: ''
  name: minimumLoanAmount
  type: decimal
- container: ''
  name: maximumLoanAmount
  type: decimal
- container: set
  name: terms
  type: string
property_count: 30
provider_name: affirm
provider_slug: affirm
slug: affirm-promos-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"affirm\": \"https://affirm.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PromoConfig\": \"affirm:PromoConfig\",\n    \"promoPrequalEnabled\": {\n      \"@id\": \"affirm:promo_prequal_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantName\": {\n      \"@id\": \"affirm:merchant_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAri\": {\n      \"@id\": \"affirm:merchant_ari\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAri\": {\n      \"@id\": \"affirm:user_ari\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toastEnabled\": {\n      \"@id\": \"affirm:toast_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabledIntegrations\": {\n      \"@id\": \"affirm:enabled_integrations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"images\": {\n      \"@id\": \"affirm:images\",\n      \"@type\": \"@id\"\n    },\n    \"hero\": {\n      \"@id\": \"affirm:hero\",\n      \"@type\": \"@id\"\n    },\n    \"hero2x\": {\n      \"@id\": \"affirm:hero2x\",\n      \"@type\": \"@id\"\n    },\n    \"logo\": {\n      \"@id\": \"affirm:logo\",\n      \"@type\": \"@id\"\n    },\n    \"logo2x\": {\n      \"@id\": \"affirm:logo2x\",\n      \"@type\": \"@id\"\n    },\n    \"FinancingTerm\": \"affirm:FinancingTerm\",\n    \"amount\": {\n      \"@id\": \"affirm:amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"loanType\": {\n      \"@id\": \"affirm:loan_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apr\": {\n      \"@id\": \"affirm:apr\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"installmentAmount\": {\n      \"@id\": \"affirm:installment_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"installmentCount\": {\n      \"@id\": \"affirm:installment_count\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"interestAmount\": {\n      \"@id\": \"affirm:interest_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"affirm:total_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PromoResponse\": \"affirm:PromoResponse\",\n    \"promo\": {\n      \"@id\": \"affirm:promo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offer\": {\n      \"@id\": \"affirm:offer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PromoContent\": \"affirm:PromoContent\",\n    \"ala\": {\n      \"@id\": \"affirm:ala\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htmlAla\": {\n      \"@id\": \"affirm:html_ala\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headline\": {\n      \"@id\": \"affirm:headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagline\": {\n      \"@id\": \"affirm:tagline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"button\": {\n      \"@id\": \"affirm:button\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htmlFooter\"\
  : {\n      \"@id\": \"affirm:html_footer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"config\": {\n      \"@id\": \"affirm:config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OfferContent\": \"affirm:OfferContent\",\n    \"minimumLoanAmount\": {\n      \"@id\": \"affirm:minimum_loan_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maximumLoanAmount\": {\n      \"@id\": \"affirm:maximum_loan_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"terms\": {\n      \"@id\": \"affirm:terms\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-promos-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
