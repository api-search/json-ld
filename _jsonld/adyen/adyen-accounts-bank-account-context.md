---
class_count: 1
classes:
- BankAccountDetail
context_file: json-ld/adyen-accounts-bank-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-bank-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Bank Account from Adyen.
layout: jsonld
name: Adyen Accounts Bank Account Context
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
  name: accountNumber
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: bankAccountName
  type: string
- container: ''
  name: bankAccountReference
  type: string
- container: ''
  name: bankAccountUUID
  type: string
- container: ''
  name: bankBicSwift
  type: string
- container: ''
  name: bankCity
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: bankName
  type: string
- container: ''
  name: branchCode
  type: string
- container: ''
  name: checkCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: ownerCity
  type: string
- container: ''
  name: ownerCountryCode
  type: string
- container: ''
  name: ownerDateOfBirth
  type: string
- container: ''
  name: ownerHouseNumberOrName
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: ownerNationality
  type: string
- container: ''
  name: ownerPostalCode
  type: string
- container: ''
  name: ownerState
  type: string
- container: ''
  name: ownerStreet
  type: string
- container: ''
  name: primaryAccount
  type: boolean
- container: ''
  name: taxId
  type: string
- container: ''
  name: urlForVerification
  type: string
property_count: 26
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-bank-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BankAccountDetail\": \"adyen:BankAccountDetail\",\n    \"accountNumber\": {\n      \"@id\": \"adyen:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"adyen:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountName\": {\n      \"@id\": \"adyen:bankAccountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountReference\": {\n      \"@id\": \"adyen:bankAccountReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUID\": {\n      \"@id\": \"adyen:bankAccountUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankBicSwift\": {\n      \"@id\": \"adyen:bankBicSwift\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCity\": {\n   \
  \   \"@id\": \"adyen:bankCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"adyen:bankCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankName\": {\n      \"@id\": \"adyen:bankName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branchCode\": {\n      \"@id\": \"adyen:branchCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkCode\": {\n      \"@id\": \"adyen:checkCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"adyen:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"adyen:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerCity\": {\n      \"@id\": \"adyen:ownerCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerCountryCode\": {\n      \"@id\": \"adyen:ownerCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerDateOfBirth\"\
  : {\n      \"@id\": \"adyen:ownerDateOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerHouseNumberOrName\": {\n      \"@id\": \"adyen:ownerHouseNumberOrName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerName\": {\n      \"@id\": \"adyen:ownerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerNationality\": {\n      \"@id\": \"adyen:ownerNationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerPostalCode\": {\n      \"@id\": \"adyen:ownerPostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerState\": {\n      \"@id\": \"adyen:ownerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerStreet\": {\n      \"@id\": \"adyen:ownerStreet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryAccount\": {\n      \"@id\": \"adyen:primaryAccount\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taxId\": {\n      \"@id\": \"adyen:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urlForVerification\": {\n      \"@id\": \"\
  adyen:urlForVerification\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-bank-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
