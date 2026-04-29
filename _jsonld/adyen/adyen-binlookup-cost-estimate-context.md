---
class_count: 3
classes:
- CostEstimateAssumptions
- CostEstimateRequest
- CostEstimateResponse
context_file: json-ld/adyen-binlookup-cost-estimate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-cost-estimate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Binlookup Cost Estimate from Adyen.
layout: jsonld
name: Adyen Binlookup Cost Estimate Context
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
  name: assume3DSecureAuthenticated
  type: boolean
- container: ''
  name: assumeLevel3Data
  type: boolean
- container: ''
  name: installments
  type: integer
- container: ''
  name: amount
  type: string
- container: ''
  name: assumptions
  type: string
- container: ''
  name: cardNumber
  type: string
- container: ''
  name: encryptedCardNumber
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: merchantDetails
  type: string
- container: ''
  name: recurring
  type: string
- container: ''
  name: selectedRecurringDetailReference
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: cardBin
  type: string
- container: ''
  name: costEstimateAmount
  type: string
- container: ''
  name: costEstimateReference
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: surchargeType
  type: string
property_count: 18
provider_name: Adyen
provider_slug: adyen
slug: adyen-binlookup-cost-estimate-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CostEstimateAssumptions\": \"adyen:CostEstimateAssumptions\",\n    \"CostEstimateRequest\": \"adyen:CostEstimateRequest\",\n    \"CostEstimateResponse\": \"adyen:CostEstimateResponse\",\n    \"assume3DSecureAuthenticated\": {\n      \"@id\": \"adyen:assume3DSecureAuthenticated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"assumeLevel3Data\": {\n      \"@id\": \"adyen:assumeLevel3Data\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"installments\": {\n      \"@id\": \"adyen:installments\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assumptions\": {\n      \"@id\": \"adyen:assumptions\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"cardNumber\": {\n      \"@id\": \"adyen:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedCardNumber\": {\n      \"@id\": \"adyen:encryptedCardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantDetails\": {\n      \"@id\": \"adyen:merchantDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"adyen:recurring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedRecurringDetailReference\": {\n      \"@id\": \"adyen:selectedRecurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardBin\": {\n      \"@id\": \"adyen:cardBin\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"costEstimateAmount\": {\n      \"@id\": \"adyen:costEstimateAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"costEstimateReference\": {\n      \"@id\": \"adyen:costEstimateReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surchargeType\": {\n      \"@id\": \"adyen:surchargeType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-cost-estimate-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
