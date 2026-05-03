---
api_specs:
- filename: vantiv-cnp-openapi.yml
  format: yaml
  label: Vantiv CNP API
  slug: cnp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-cnp-openapi.yml
- filename: vantiv-express-openapi.yml
  format: yaml
  label: Vantiv Express API
  slug: express-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-express-openapi.yml
- filename: vantiv-chargeback-openapi.yml
  format: yaml
  label: Vantiv Chargeback API
  slug: chargeback-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-chargeback-openapi.yml
class_count: 17
classes:
- merchantId
- id
- cnpTxnId
- response
- message
- authCode
- orderSource
- cardType
- expDate
- litleToken
- addressLine1
- city
- state
- zip
- country
- caseId
- reasonCode
context_file: json-ld/vantiv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/json-ld/vantiv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vantiv from Vantiv.
layout: jsonld
name: Vantiv Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: vantiv
  uri: https://payments.vantivcnp.com/vap/
properties:
- container: ''
  name: Transaction
  type: reference
- container: ''
  name: Authorization
  type: reference
- container: ''
  name: Sale
  type: reference
- container: ''
  name: Chargeback
  type: reference
- container: ''
  name: orderId
  type: string
- container: ''
  name: amount
  type: integer
- container: ''
  name: postDate
  type: date
- container: ''
  name: responseTime
  type: dateTime
- container: ''
  name: card
  type: reference
- container: ''
  name: billToAddress
  type: schema:PostalAddress
- container: ''
  name: disputeDate
  type: date
- container: ''
  name: replyByDate
  type: date
- container: ''
  name: financialImpact
  type: boolean
property_count: 13
provider_name: Vantiv
provider_slug: vantiv
slug: vantiv-context
source_filename: vantiv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"vantiv\": \"https://payments.vantivcnp.com/vap/\",\n\n    \"Transaction\": {\n      \"@id\": \"schema:PayAction\",\n      \"@type\": \"@id\"\n    },\n    \"Authorization\": {\n      \"@id\": \"vantiv:Authorization\",\n      \"@type\": \"@id\"\n    },\n    \"Sale\": {\n      \"@id\": \"schema:PayAction\",\n      \"@type\": \"@id\"\n    },\n    \"Chargeback\": {\n      \"@id\": \"vantiv:Chargeback\",\n      \"@type\": \"@id\"\n    },\n\n    \"merchantId\": \"vantiv:merchantId\",\n    \"id\": \"@id\",\n    \"orderId\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cnpTxnId\": \"vantiv:cnpTxnId\",\n    \"response\": \"vantiv:responseCode\",\n    \"message\": \"schema:description\",\n    \"authCode\"\
  : \"vantiv:authorizationCode\",\n    \"postDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"responseTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"orderSource\": \"vantiv:orderSource\",\n\n    \"card\": {\n      \"@id\": \"schema:paymentMethod\",\n      \"@type\": \"@id\"\n    },\n    \"cardType\": \"schema:paymentMethodId\",\n    \"expDate\": \"vantiv:expirationDate\",\n    \"litleToken\": \"vantiv:paymentToken\",\n\n    \"billToAddress\": {\n      \"@id\": \"schema:billingAddress\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"addressLine1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"caseId\": \"vantiv:chargebackCaseId\",\n    \"reasonCode\": \"vantiv:chargebackReasonCode\",\n    \"disputeDate\": {\n      \"@id\": \"vantiv:disputeDate\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"replyByDate\": {\n      \"@id\": \"vantiv:replyByDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"financialImpact\": {\n      \"@id\": \"vantiv:financialImpact\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/json-ld/vantiv-context.jsonld
tags:
- Payments
- Payment Processing
- eCommerce
- Finance
- FinTech
- JSON-LD
- Linked Data
- Semantic Web
---
