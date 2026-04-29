---
class_count: 3
classes:
- PayoutAccountHolderRequest
- PayoutAccountHolderResponse
- description
context_file: json-ld/adyen-funds-payout-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-payout-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Funds Payout Account from Adyen.
layout: jsonld
name: Adyen Funds Payout Account Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountCode
  type: string
- container: ''
  name: accountHolderCode
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: bankAccountUUID
  type: string
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: payoutMethodCode
  type: string
- container: ''
  name: payoutSpeed
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-funds-payout-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayoutAccountHolderRequest\": \"adyen:PayoutAccountHolderRequest\",\n    \"PayoutAccountHolderResponse\": \"adyen:PayoutAccountHolderResponse\",\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUID\": {\n      \"@id\": \"adyen:bankAccountUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  payoutMethodCode\": {\n      \"@id\": \"adyen:payoutMethodCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutSpeed\": {\n      \"@id\": \"adyen:payoutSpeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-payout-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
