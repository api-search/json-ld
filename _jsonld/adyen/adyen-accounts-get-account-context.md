---
class_count: 4
classes:
- GetAccountHolderRequest
- GetAccountHolderResponse
- GetAccountHolderStatusResponse
- description
context_file: json-ld/adyen-accounts-get-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-get-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Get Account from Adyen.
layout: jsonld
name: Adyen Accounts Get Account Context
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
  name: showDetails
  type: boolean
- container: ''
  name: accountHolderDetails
  type: string
- container: ''
  name: accountHolderStatus
  type: string
- container: set
  name: accounts
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: legalEntity
  type: string
- container: ''
  name: migrationData
  type: string
- container: ''
  name: primaryCurrency
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: systemUpToDateTime
  type: dateTime
- container: ''
  name: verification
  type: string
- container: ''
  name: verificationProfile
  type: string
property_count: 15
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-get-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetAccountHolderRequest\": \"adyen:GetAccountHolderRequest\",\n    \"GetAccountHolderResponse\": \"adyen:GetAccountHolderResponse\",\n    \"GetAccountHolderStatusResponse\": \"adyen:GetAccountHolderStatusResponse\",\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showDetails\": {\n      \"@id\": \"adyen:showDetails\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"accountHolderDetails\": {\n      \"@id\": \"adyen:accountHolderDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderStatus\": {\n      \"@id\": \"adyen:accountHolderStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"accounts\": {\n      \"@id\": \"adyen:accounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntity\": {\n      \"@id\": \"adyen:legalEntity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationData\": {\n      \"@id\": \"adyen:migrationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryCurrency\": {\n      \"@id\": \"adyen:primaryCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemUpToDateTime\": {\n      \"@id\": \"adyen:systemUpToDateTime\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"verification\": {\n      \"@id\": \"adyen:verification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationProfile\": {\n      \"@id\": \"adyen:verificationProfile\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-get-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
