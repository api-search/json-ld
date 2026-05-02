---
api_specs:
- filename: montran-global-payments-hub-openapi.yml
  format: yaml
  label: Montran Global Payments Hub
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/openapi/montran-global-payments-hub-openapi.yml
- filename: montran-instant-payments-gateway-openapi.yml
  format: yaml
  label: Montran Instant Payments Gateway
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/openapi/montran-instant-payments-gateway-openapi.yml
- filename: montran-payments-connectivity-openapi.yml
  format: yaml
  label: Montran Payments Connectivity
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/openapi/montran-payments-connectivity-openapi.yml
- filename: montran-corporate-payments-portal-openapi.yml
  format: yaml
  label: Montran Corporate Payments Portal
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/openapi/montran-corporate-payments-portal-openapi.yml
- filename: montran-virtual-accounts-openapi.yml
  format: yaml
  label: Montran Virtual Accounts
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/openapi/montran-virtual-accounts-openapi.yml
- filename: montran-sanctions-screening-openapi.yml
  format: yaml
  label: Montran Sanctions Screening
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/openapi/montran-sanctions-screening-openapi.yml
class_count: 1
classes:
- iso20022
context_file: json-ld/montran-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/json-ld/montran-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Montran from Montran.
layout: jsonld
name: Montran Context
namespaces:
- prefix: montran
  uri: https://www.montran.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: fibo-fnd
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: fibo-fbc
  uri: https://spec.edmcouncil.org/fibo/ontology/FBC/
- prefix: fibo-sec
  uri: https://spec.edmcouncil.org/fibo/ontology/SEC/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Payment
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: FinancialInstitution
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: ScreeningResult
  type: ''
- container: ''
  name: VirtualAccount
  type: ''
- container: ''
  name: ClearingBatch
  type: ''
- container: ''
  name: Message
  type: ''
property_count: 8
provider_name: Montran
provider_slug: montran
slug: montran-context
source_filename: montran-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"montran\": \"https://www.montran.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"fibo-fnd\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"fibo-fbc\": \"https://spec.edmcouncil.org/fibo/ontology/FBC/\",\n    \"fibo-sec\": \"https://spec.edmcouncil.org/fibo/ontology/SEC/\",\n    \"iso20022\": \"urn:iso:std:iso:20022:tech:xsd:\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Payment\": {\n      \"@id\": \"montran:Payment\",\n      \"@context\": {\n        \"paymentId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"messageId\": {\n          \"@id\": \"montran:messageId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endToEndId\": {\n          \"@id\": \"montran:endToEndId\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"transactionId\": {\n          \"@id\": \"montran:transactionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentType\": {\n          \"@id\": \"montran:paymentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"montran:paymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"debtorName\": {\n          \"@id\": \"montran:debtorName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creditorName\": {\n          \"@id\": \"montran:creditorName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"remittanceInformation\": {\n          \"@id\": \"montran:remittanceInformation\",\n          \"@type\": \"xsd:string\"\n \
  \       },\n        \"clearingSystem\": {\n          \"@id\": \"montran:clearingSystem\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestedExecutionDate\": {\n          \"@id\": \"montran:requestedExecutionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"settlementDate\": {\n          \"@id\": \"montran:settlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"fibo-fbc:Account\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountType\": {\n          \"@id\": \"montran:accountType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"iban\"\
  : {\n          \"@id\": \"fibo-fbc:IBAN\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountNumber\": {\n          \"@id\": \"fibo-fbc:accountNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"montran:accountStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"FinancialInstitution\": {\n      \"@id\": \"fibo-fbc:FinancialInstitution\",\n      \"@context\": {\n        \"bic\": {\n          \"@id\": \"fibo-fbc:BIC\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"lei\": {\n          \"@id\": \"fibo-fbc:LEI\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clearingSystemMemberId\": {\n          \"@id\": \"montran:clearingSystemMemberId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"montran:Transaction\",\n      \"@context\": {\n        \"transactionId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creditDebitIndicator\": {\n          \"@id\": \"montran:creditDebitIndicator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bookingDate\"\
  : {\n          \"@id\": \"montran:bookingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"valueDate\": {\n          \"@id\": \"montran:valueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"remittanceInformation\": {\n          \"@id\": \"montran:remittanceInformation\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ScreeningResult\": {\n      \"@id\": \"montran:ScreeningResult\",\n      \"@context\": {\n        \"screeningId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"result\": {\n          \"@id\": \"montran:screeningResult\",\n          \"@type\": \"xsd:string\"\n        },\n        \"matchCount\": {\n          \"@id\": \"montran:matchCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"screenedAt\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VirtualAccount\": {\n      \"\
  @id\": \"montran:VirtualAccount\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"virtualIban\": {\n          \"@id\": \"montran:virtualIban\",\n          \"@type\": \"xsd:string\"\n        },\n        \"physicalAccountId\": {\n          \"@id\": \"montran:physicalAccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"purpose\": {\n          \"@id\": \"montran:accountPurpose\",\n          \"@type\": \"xsd:string\"\n        },\n        \"balance\": {\n          \"@id\": \"montran:balance\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"ClearingBatch\": {\n      \"@id\": \"montran:ClearingBatch\",\n      \"@context\": {\n        \"batchId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clearingSystem\": {\n          \"@id\": \"montran:clearingSystem\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"numberOfTransactions\": {\n          \"@id\": \"montran:numberOfTransactions\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"montran:totalAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"settlementDate\": {\n          \"@id\": \"montran:settlementDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"montran:Message\",\n      \"@context\": {\n        \"messageId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"format\": {\n          \"@id\": \"dcterms:format\",\n          \"@type\": \"xsd:string\"\n        },\n        \"messageType\": {\n          \"@id\": \"montran:messageType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"direction\": {\n          \"@id\": \"montran:direction\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/montran/refs/heads/main/json-ld/montran-context.jsonld
tags:
- Banking
- Central Banking
- Financial Services
- ISO 20022
- Market Infrastructure
- Messaging
- Payments
- Real-Time Payments
- SWIFT
- JSON-LD
- Linked Data
- Semantic Web
---
