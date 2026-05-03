---
api_specs:
- filename: scotiabank-tranxact-openapi.yml
  format: yaml
  label: Scotia TranXact APIs
  slug: scotia-tranxact
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/openapi/scotiabank-tranxact-openapi.yml
class_count: 0
classes: []
context_file: json-ld/scotiabank-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/json-ld/scotiabank-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scotiabank from Scotiabank.
layout: jsonld
name: Scotiabank Context
namespaces:
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FBC/
- prefix: scotiabank
  uri: https://api-evangelist.github.io/scotiabank/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: BankAccount
  type: rdfs:Class
- container: ''
  name: WirePayment
  type: rdfs:Class
- container: ''
  name: EFTPayment
  type: rdfs:Class
- container: ''
  name: RealtimePayment
  type: rdfs:Class
- container: ''
  name: Transaction
  type: rdfs:Class
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: creditDebitIndicator
  type: string
- container: ''
  name: uetr
  type: string
- container: ''
  name: paymentStatus
  type: string
- container: ''
  name: valueDate
  type: date
- container: ''
  name: openingBalance
  type: decimal
- container: ''
  name: closingBalance
  type: decimal
- container: ''
  name: availableBalance
  type: decimal
property_count: 16
provider_name: Scotiabank
provider_slug: scotiabank
slug: scotiabank-context
source_filename: scotiabank-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FBC/\",\n    \"scotiabank\": \"https://api-evangelist.github.io/scotiabank/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"BankAccount\": {\n      \"@id\": \"fibo:BankAccount\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A Scotiabank deposit account\"\n    },\n    \"WirePayment\": {\n      \"@id\": \"fibo:WireTransfer\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"An international or domestic wire transfer\"\n    },\n    \"EFTPayment\": {\n      \"@id\": \"scotiabank:EFTPayment\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"An Electronic Funds Transfer payment\"\n    },\n    \"RealtimePayment\": {\n      \"@id\": \"scotiabank:RealtimePayment\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A real-time INTERAC e-Transfer payment\"\n    },\n    \"Transaction\": {\n \
  \     \"@id\": \"schema:PayAction\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A banking transaction record\"\n    },\n\n    \"accountNumber\": {\n      \"@id\": \"fibo:hasAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionDate\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"creditDebitIndicator\": {\n      \"@id\": \"fibo:creditDebitIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uetr\": {\n      \"@id\": \"scotiabank:uetr\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Unique End-to-End Transaction Reference for SWIFT GPI payments\"\n    },\n    \"paymentStatus\": {\n      \"@id\": \"schema:paymentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueDate\": {\n      \"@id\"\
  : \"fibo:hasValueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"openingBalance\": {\n      \"@id\": \"scotiabank:openingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"closingBalance\": {\n      \"@id\": \"scotiabank:closingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availableBalance\": {\n      \"@id\": \"fibo:hasAvailableBalance\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/json-ld/scotiabank-context.jsonld
tags:
- Banking
- Finance
- Payments
- Canada
- Open Banking
- JSON-LD
- Linked Data
- Semantic Web
---
