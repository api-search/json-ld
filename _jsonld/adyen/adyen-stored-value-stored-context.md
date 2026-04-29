---
class_count: 12
classes:
- StoredValueBalanceCheckRequest
- StoredValueBalanceCheckResponse
- StoredValueBalanceMergeRequest
- StoredValueBalanceMergeResponse
- StoredValueIssueRequest
- StoredValueIssueResponse
- StoredValueLoadRequest
- StoredValueLoadResponse
- StoredValueStatusChangeRequest
- StoredValueStatusChangeResponse
- StoredValueVoidRequest
- StoredValueVoidResponse
context_file: json-ld/adyen-stored-value-stored-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-stored-value-stored-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Stored Value Stored from Adyen.
layout: jsonld
name: Adyen Stored Value Stored Context
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
  name: amount
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: paymentMethod
  type: reference
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: store
  type: string
- container: ''
  name: currentBalance
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: refusalReason
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: thirdPartyRefusalReason
  type: string
- container: ''
  name: sourcePaymentMethod
  type: reference
- container: ''
  name: authCode
  type: string
- container: ''
  name: loadType
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: originalReference
  type: string
- container: ''
  name: tenderReference
  type: string
- container: ''
  name: uniqueTerminalId
  type: string
property_count: 20
provider_name: Adyen
provider_slug: adyen
slug: adyen-stored-value-stored-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoredValueBalanceCheckRequest\": \"adyen:StoredValueBalanceCheckRequest\",\n    \"StoredValueBalanceCheckResponse\": \"adyen:StoredValueBalanceCheckResponse\",\n    \"StoredValueBalanceMergeRequest\": \"adyen:StoredValueBalanceMergeRequest\",\n    \"StoredValueBalanceMergeResponse\": \"adyen:StoredValueBalanceMergeResponse\",\n    \"StoredValueIssueRequest\": \"adyen:StoredValueIssueRequest\",\n    \"StoredValueIssueResponse\": \"adyen:StoredValueIssueResponse\",\n    \"StoredValueLoadRequest\": \"adyen:StoredValueLoadRequest\",\n    \"StoredValueLoadResponse\": \"adyen:StoredValueLoadResponse\",\n    \"StoredValueStatusChangeRequest\": \"adyen:StoredValueStatusChangeRequest\",\n    \"StoredValueStatusChangeResponse\": \"adyen:StoredValueStatusChangeResponse\"\
  ,\n    \"StoredValueVoidRequest\": \"adyen:StoredValueVoidRequest\",\n    \"StoredValueVoidResponse\": \"adyen:StoredValueVoidResponse\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"@id\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"currentBalance\": {\n      \"@id\": \"adyen:currentBalance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refusalReason\": {\n      \"@id\": \"adyen:refusalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thirdPartyRefusalReason\": {\n      \"@id\": \"adyen:thirdPartyRefusalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePaymentMethod\": {\n      \"@id\": \"adyen:sourcePaymentMethod\",\n      \"@type\": \"@id\"\n    },\n    \"authCode\": {\n      \"@id\": \"adyen:authCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loadType\": {\n      \"@id\": \"adyen:loadType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalReference\": {\n      \"@id\"\
  : \"adyen:originalReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenderReference\": {\n      \"@id\": \"adyen:tenderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uniqueTerminalId\": {\n      \"@id\": \"adyen:uniqueTerminalId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-stored-value-stored-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
