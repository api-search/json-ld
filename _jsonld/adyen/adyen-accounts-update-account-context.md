---
class_count: 6
classes:
- UpdateAccountHolderRequest
- UpdateAccountHolderResponse
- UpdateAccountHolderStateRequest
- UpdateAccountRequest
- UpdateAccountResponse
- description
context_file: json-ld/adyen-accounts-update-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-update-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Update Account from Adyen.
layout: jsonld
name: Adyen Accounts Update Account Context
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
  name: accountHolderDetails
  type: string
- container: ''
  name: legalEntity
  type: string
- container: ''
  name: primaryCurrency
  type: string
- container: ''
  name: processingTier
  type: integer
- container: ''
  name: verificationProfile
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
  name: verification
  type: string
- container: ''
  name: disable
  type: boolean
- container: ''
  name: reason
  type: string
- container: ''
  name: stateType
  type: string
- container: ''
  name: accountCode
  type: string
- container: ''
  name: bankAccountUUID
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: payoutMethodCode
  type: string
- container: ''
  name: payoutSchedule
  type: string
- container: ''
  name: payoutSpeed
  type: string
property_count: 20
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-update-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateAccountHolderRequest\": \"adyen:UpdateAccountHolderRequest\",\n    \"UpdateAccountHolderResponse\": \"adyen:UpdateAccountHolderResponse\",\n    \"UpdateAccountHolderStateRequest\": \"adyen:UpdateAccountHolderStateRequest\",\n    \"UpdateAccountRequest\": \"adyen:UpdateAccountRequest\",\n    \"UpdateAccountResponse\": \"adyen:UpdateAccountResponse\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderDetails\": {\n      \"@id\": \"adyen:accountHolderDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"legalEntity\": {\n      \"@id\": \"adyen:legalEntity\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"primaryCurrency\": {\n      \"@id\": \"adyen:primaryCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingTier\": {\n      \"@id\": \"adyen:processingTier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"verificationProfile\": {\n      \"@id\": \"adyen:verificationProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderStatus\": {\n      \"@id\": \"adyen:accountHolderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verification\": {\n      \"@id\": \"adyen:verification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disable\": {\n      \"@id\": \"adyen:disable\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateType\": {\n      \"@id\": \"adyen:stateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUID\": {\n      \"@id\": \"adyen:bankAccountUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"payoutMethodCode\": {\n      \"@id\": \"adyen:payoutMethodCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutSchedule\": {\n      \"@id\": \"adyen:payoutSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutSpeed\": {\n      \"@id\": \"adyen:payoutSpeed\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-update-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
