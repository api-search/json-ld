---
class_count: 3
classes:
- AccountHolderDetails
- AccountHolderStatus
- email
context_file: json-ld/adyen-accounts-account-holder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-account-holder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Account Holder from Adyen.
layout: jsonld
name: Adyen Accounts Account Holder Context
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
  name: address
  type: string
- container: set
  name: bankAccountDetails
  type: string
- container: ''
  name: bankAggregatorDataReference
  type: string
- container: ''
  name: businessDetails
  type: string
- container: ''
  name: fullPhoneNumber
  type: string
- container: ''
  name: individualDetails
  type: string
- container: ''
  name: lastReviewDate
  type: string
- container: set
  name: legalArrangements
  type: string
- container: ''
  name: merchantCategoryCode
  type: string
- container: ''
  name: metadata
  type: reference
- container: set
  name: payoutMethods
  type: string
- container: ''
  name: principalBusinessAddress
  type: string
- container: set
  name: storeDetails
  type: string
- container: ''
  name: webAddress
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: payoutState
  type: string
- container: ''
  name: processingState
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
property_count: 19
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-account-holder-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountHolderDetails\": \"adyen:AccountHolderDetails\",\n    \"AccountHolderStatus\": \"adyen:AccountHolderStatus\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountDetails\": {\n      \"@id\": \"adyen:bankAccountDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAggregatorDataReference\": {\n      \"@id\": \"adyen:bankAggregatorDataReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessDetails\": {\n      \"@id\": \"adyen:businessDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"fullPhoneNumber\": {\n      \"@id\": \"adyen:fullPhoneNumber\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"individualDetails\": {\n      \"@id\": \"adyen:individualDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastReviewDate\": {\n      \"@id\": \"adyen:lastReviewDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangements\": {\n      \"@id\": \"adyen:legalArrangements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantCategoryCode\": {\n      \"@id\": \"adyen:merchantCategoryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"payoutMethods\": {\n      \"@id\": \"adyen:payoutMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalBusinessAddress\": {\n      \"@id\": \"adyen:principalBusinessAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeDetails\": {\n      \"@id\": \"adyen:storeDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"webAddress\": {\n      \"@id\": \"adyen:webAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"adyen:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutState\": {\n      \"@id\": \"adyen:payoutState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingState\": {\n      \"@id\": \"adyen:processingState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"adyen:statusReason\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-account-holder-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
