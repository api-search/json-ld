---
class_count: 4
classes:
- CloseAccountHolderRequest
- CloseAccountHolderResponse
- CloseAccountRequest
- CloseAccountResponse
context_file: json-ld/adyen-accounts-close-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-close-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Close Account from Adyen.
layout: jsonld
name: Adyen Accounts Close Account Context
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
  name: accountHolderCode
  type: string
- container: ''
  name: accountHolderStatus
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
- container: ''
  name: accountCode
  type: string
- container: ''
  name: status
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-close-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CloseAccountHolderRequest\": \"adyen:CloseAccountHolderRequest\",\n    \"CloseAccountHolderResponse\": \"adyen:CloseAccountHolderResponse\",\n    \"CloseAccountRequest\": \"adyen:CloseAccountRequest\",\n    \"CloseAccountResponse\": \"adyen:CloseAccountResponse\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderStatus\": {\n      \"@id\": \"adyen:accountHolderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-close-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
