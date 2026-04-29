---
class_count: 7
classes:
- TransactionRuleEntityKey
- TransactionRuleInfo
- TransactionRuleInterval
- TransactionRuleResponse
- TransactionRuleRestrictions
- TransactionRule
- description
context_file: json-ld/adyen-configuration-transaction-rule-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-transaction-rule-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Transaction Rule from Adyen.
layout: jsonld
name: Adyen Configuration Transaction Rule Context
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
  name: entityReference
  type: string
- container: ''
  name: entityType
  type: string
- container: ''
  name: aggregationLevel
  type: string
- container: ''
  name: endDate
  type: string
- container: ''
  name: entityKey
  type: string
- container: ''
  name: interval
  type: string
- container: ''
  name: outcomeType
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: requestType
  type: string
- container: ''
  name: ruleRestrictions
  type: string
- container: ''
  name: score
  type: integer
- container: ''
  name: startDate
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: dayOfMonth
  type: integer
- container: ''
  name: dayOfWeek
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: timeOfDay
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: transactionRule
  type: string
- container: ''
  name: activeNetworkTokens
  type: string
- container: ''
  name: brandVariants
  type: string
- container: ''
  name: counterpartyBank
  type: string
- container: ''
  name: countries
  type: string
- container: ''
  name: differentCurrencies
  type: string
- container: ''
  name: entryModes
  type: string
- container: ''
  name: internationalTransaction
  type: string
- container: ''
  name: matchingTransactions
  type: string
- container: ''
  name: mccs
  type: string
- container: ''
  name: merchantNames
  type: string
- container: ''
  name: merchants
  type: string
- container: ''
  name: processingTypes
  type: string
- container: ''
  name: sameAmountRestriction
  type: string
- container: ''
  name: sameCounterpartyRestriction
  type: string
- container: ''
  name: totalAmount
  type: string
- container: ''
  name: id
  type: string
property_count: 36
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-transaction-rule-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TransactionRuleEntityKey\": \"adyen:TransactionRuleEntityKey\",\n    \"TransactionRuleInfo\": \"adyen:TransactionRuleInfo\",\n    \"TransactionRuleInterval\": \"adyen:TransactionRuleInterval\",\n    \"TransactionRuleResponse\": \"adyen:TransactionRuleResponse\",\n    \"TransactionRuleRestrictions\": \"adyen:TransactionRuleRestrictions\",\n    \"TransactionRule\": \"adyen:TransactionRule\",\n    \"entityReference\": {\n      \"@id\": \"adyen:entityReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityType\": {\n      \"@id\": \"adyen:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregationLevel\": {\n      \"@id\": \"adyen:aggregationLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\"\
  : \"schema:description\",\n    \"endDate\": {\n      \"@id\": \"adyen:endDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityKey\": {\n      \"@id\": \"adyen:entityKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interval\": {\n      \"@id\": \"adyen:interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outcomeType\": {\n      \"@id\": \"adyen:outcomeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestType\": {\n      \"@id\": \"adyen:requestType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleRestrictions\": {\n      \"@id\": \"adyen:ruleRestrictions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"adyen:score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startDate\": {\n      \"@id\": \"adyen:startDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayOfMonth\": {\n      \"@id\": \"adyen:dayOfMonth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dayOfWeek\": {\n      \"@id\": \"adyen:dayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"adyen:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeOfDay\": {\n      \"@id\": \"adyen:timeOfDay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"adyen:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionRule\": {\n      \"@id\": \"adyen:transactionRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeNetworkTokens\": {\n      \"@id\": \"adyen:activeNetworkTokens\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brandVariants\": {\n      \"@id\": \"adyen:brandVariants\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterpartyBank\": {\n      \"@id\": \"\
  adyen:counterpartyBank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countries\": {\n      \"@id\": \"adyen:countries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"differentCurrencies\": {\n      \"@id\": \"adyen:differentCurrencies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entryModes\": {\n      \"@id\": \"adyen:entryModes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internationalTransaction\": {\n      \"@id\": \"adyen:internationalTransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchingTransactions\": {\n      \"@id\": \"adyen:matchingTransactions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mccs\": {\n      \"@id\": \"adyen:mccs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantNames\": {\n      \"@id\": \"adyen:merchantNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchants\": {\n      \"@id\": \"adyen:merchants\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingTypes\": {\n      \"@id\": \"adyen:processingTypes\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sameAmountRestriction\": {\n      \"@id\": \"adyen:sameAmountRestriction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sameCounterpartyRestriction\": {\n      \"@id\": \"adyen:sameCounterpartyRestriction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"adyen:totalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-transaction-rule-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
