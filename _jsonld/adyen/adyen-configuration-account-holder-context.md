---
class_count: 5
classes:
- AccountHolderCapability
- AccountHolderInfo
- AccountHolder
- AccountHolderUpdateRequest
- description
context_file: json-ld/adyen-configuration-account-holder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-account-holder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Account Holder from Adyen.
layout: jsonld
name: Adyen Configuration Account Holder Context
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
  name: allowed
  type: boolean
- container: ''
  name: allowedLevel
  type: string
- container: ''
  name: allowedSettings
  type: string
- container: ''
  name: enabled
  type: boolean
- container: set
  name: problems
  type: string
- container: ''
  name: requested
  type: boolean
- container: ''
  name: requestedLevel
  type: string
- container: ''
  name: requestedSettings
  type: string
- container: set
  name: transferInstruments
  type: string
- container: ''
  name: verificationStatus
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: contactDetails
  type: string
- container: ''
  name: legalEntityId
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: migratedAccountHolderCode
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: primaryBalanceAccount
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: verificationDeadlines
  type: string
property_count: 22
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-account-holder-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountHolderCapability\": \"adyen:AccountHolderCapability\",\n    \"AccountHolderInfo\": \"adyen:AccountHolderInfo\",\n    \"AccountHolder\": \"adyen:AccountHolder\",\n    \"AccountHolderUpdateRequest\": \"adyen:AccountHolderUpdateRequest\",\n    \"allowed\": {\n      \"@id\": \"adyen:allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowedLevel\": {\n      \"@id\": \"adyen:allowedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedSettings\": {\n      \"@id\": \"adyen:allowedSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"problems\": {\n      \"@id\": \"adyen:problems\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"requested\": {\n      \"@id\": \"adyen:requested\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requestedLevel\": {\n      \"@id\": \"adyen:requestedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedSettings\": {\n      \"@id\": \"adyen:requestedSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferInstruments\": {\n      \"@id\": \"adyen:transferInstruments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationStatus\": {\n      \"@id\": \"adyen:verificationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"adyen:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"contactDetails\": {\n      \"@id\": \"adyen:contactDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\"\
  ,\n    \"legalEntityId\": {\n      \"@id\": \"adyen:legalEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"migratedAccountHolderCode\": {\n      \"@id\": \"adyen:migratedAccountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"adyen:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryBalanceAccount\": {\n      \"@id\": \"adyen:primaryBalanceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationDeadlines\": {\n      \"@id\": \"adyen:verificationDeadlines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-account-holder-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
