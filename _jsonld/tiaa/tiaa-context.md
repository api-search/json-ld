---
api_specs:
- filename: tiaa-fdx-openapi.yml
  format: yaml
  label: TIAA Financial Data Exchange API
  slug: tiaa-fdx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/openapi/tiaa-fdx-openapi.yml
- filename: tiaa-sia-openapi.yml
  format: yaml
  label: TIAA Secure Income Account API
  slug: tiaa-sia-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/openapi/tiaa-sia-openapi.yml
class_count: 16
classes:
- accountId
- accountType
- displayName
- accountNumber
- balanceAsOf
- status
- transactionId
- transactionType
- positionId
- symbol
- participantId
- planId
- projectedRetirementAge
- Account
- Transaction
- Customer
context_file: json-ld/tiaa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/json-ld/tiaa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tiaa from TIAA.
layout: jsonld
name: Tiaa Context
namespaces:
- prefix: tiaa
  uri: https://developer.tiaa.org/ontology/
- prefix: fdx
  uri: https://financialdataexchange.org/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: currentBalance
  type: decimal
- container: ''
  name: currency
  type: '@vocab'
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionDate
  type: dateTime
- container: ''
  name: postedDate
  type: dateTime
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: marketValue
  type: decimal
- container: ''
  name: costBasis
  type: decimal
- container: ''
  name: enrollmentDate
  type: date
- container: ''
  name: vestingPercentage
  type: decimal
- container: ''
  name: monthlyIncomeProjection
  type: decimal
- container: ''
  name: annualIncomeProjection
  type: decimal
- container: ''
  name: RetirementAccount
  type: reference
- container: ''
  name: Plan
  type: reference
- container: ''
  name: Participant
  type: reference
property_count: 15
provider_name: TIAA
provider_slug: tiaa
slug: tiaa-context
source_filename: tiaa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tiaa\": \"https://developer.tiaa.org/ontology/\",\n    \"fdx\": \"https://financialdataexchange.org/ontology/\",\n\n    \"accountId\": \"tiaa:accountId\",\n    \"accountType\": \"tiaa:accountType\",\n    \"displayName\": \"name\",\n    \"accountNumber\": \"tiaa:accountNumber\",\n    \"balanceAsOf\": \"tiaa:balanceAsOf\",\n    \"currentBalance\": {\n      \"@id\": \"tiaa:currentBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"tiaa:currency\",\n      \"@type\": \"@vocab\"\n    },\n    \"status\": \"tiaa:status\",\n\n    \"transactionId\": \"tiaa:transactionId\",\n    \"transactionType\": \"tiaa:transactionType\",\n    \"amount\": {\n      \"@id\": \"tiaa:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionDate\": {\n      \"@id\": \"tiaa:transactionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"postedDate\": {\n      \"@id\": \"tiaa:postedDate\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"positionId\": \"tiaa:positionId\",\n    \"symbol\": \"tiaa:symbol\",\n    \"quantity\": {\n      \"@id\": \"tiaa:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"marketValue\": {\n      \"@id\": \"tiaa:marketValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"costBasis\": {\n      \"@id\": \"tiaa:costBasis\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"participantId\": \"tiaa:participantId\",\n    \"planId\": \"tiaa:planId\",\n    \"enrollmentDate\": {\n      \"@id\": \"tiaa:enrollmentDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"vestingPercentage\": {\n      \"@id\": \"tiaa:vestingPercentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"monthlyIncomeProjection\": {\n      \"@id\": \"tiaa:monthlyIncomeProjection\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"annualIncomeProjection\": {\n      \"@id\": \"tiaa:annualIncomeProjection\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"projectedRetirementAge\"\
  : \"tiaa:projectedRetirementAge\",\n\n    \"Account\": \"BankAccount\",\n    \"RetirementAccount\": {\n      \"@id\": \"tiaa:RetirementAccount\",\n      \"@type\": \"@id\"\n    },\n    \"Transaction\": \"MoneyTransfer\",\n    \"Customer\": \"Person\",\n    \"Plan\": {\n      \"@id\": \"tiaa:Plan\",\n      \"@type\": \"@id\"\n    },\n    \"Participant\": {\n      \"@id\": \"tiaa:Participant\",\n      \"@type\": \"@id\"\n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/json-ld/tiaa-context.jsonld
tags:
- Finance
- Financial Data
- Fintech
- Insurance
- Investment Management
- Retirement
- Wealth Management
- JSON-LD
- Linked Data
- Semantic Web
---
