---
class_count: 4
classes:
- LoyaltyAccountID
- LoyaltyAccountReq
- LoyaltyAccount
- LoyaltyAccountStatus
context_file: json-ld/adyen-terminal-loyalty-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Account from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Account Context
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
  name: EntryMode
  type: string
- container: ''
  name: IdentificationType
  type: string
- container: ''
  name: IdentificationSupport
  type: string
- container: ''
  name: LoyaltyID
  type: string
- container: ''
  name: CardAcquisitionReference
  type: string
- container: ''
  name: LoyaltyBrand
  type: string
- container: ''
  name: CurrentBalance
  type: decimal
- container: ''
  name: LoyaltyUnit
  type: string
- container: ''
  name: Currency
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyAccountID\": \"adyen:LoyaltyAccountID\",\n    \"LoyaltyAccountReq\": \"adyen:LoyaltyAccountReq\",\n    \"LoyaltyAccount\": \"adyen:LoyaltyAccount\",\n    \"LoyaltyAccountStatus\": \"adyen:LoyaltyAccountStatus\",\n    \"EntryMode\": {\n      \"@id\": \"adyen:EntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentificationType\": {\n      \"@id\": \"adyen:IdentificationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentificationSupport\": {\n      \"@id\": \"adyen:IdentificationSupport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyID\": {\n      \"@id\": \"adyen:LoyaltyID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardAcquisitionReference\": {\n      \"@id\": \"adyen:CardAcquisitionReference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyBrand\": {\n      \"@id\": \"adyen:LoyaltyBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentBalance\": {\n      \"@id\": \"adyen:CurrentBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LoyaltyUnit\": {\n      \"@id\": \"adyen:LoyaltyUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Currency\": {\n      \"@id\": \"adyen:Currency\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
