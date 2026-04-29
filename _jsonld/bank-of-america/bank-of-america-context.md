---
api_specs:
- filename: bank-of-america-cashpro-api-openapi.yml
  format: yaml
  label: Bank of America CashPro API
  slug: cashpro-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/openapi/bank-of-america-cashpro-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/bank-of-america-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/json-ld/bank-of-america-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bank Of America from Bank of America.
layout: jsonld
name: Bank Of America Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bofaapi
  uri: https://api-evangelist.github.io/bank-of-america/vocab#
properties:
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: routingNumber
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: openDate
  type: string
- container: ''
  name: Account
  type: ''
- container: ''
  name: accounts
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: AccountListResponse
  type: ''
- container: ''
  name: ledgerBalance
  type: decimal
- container: ''
  name: availableBalance
  type: decimal
- container: ''
  name: collectedBalance
  type: decimal
- container: ''
  name: asOfDate
  type: string
- container: ''
  name: Balance
  type: ''
- container: ''
  name: balances
  type: string
- container: ''
  name: BalanceResponse
  type: ''
- container: ''
  name: transactionId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: description
  type: string
- container: ''
  name: referenceNumber
  type: string
- container: ''
  name: valueDate
  type: string
- container: ''
  name: postDate
  type: string
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: transactions
  type: string
- container: ''
  name: TransactionListResponse
  type: ''
- container: ''
  name: paymentType
  type: string
- container: ''
  name: debitAccountId
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: memo
  type: string
- container: ''
  name: beneficiary
  type: string
- container: ''
  name: PaymentRequest
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: bankName
  type: string
- container: ''
  name: bankAddress
  type: string
- container: ''
  name: swiftCode
  type: string
- container: ''
  name: Beneficiary
  type: ''
- container: ''
  name: paymentId
  type: string
- container: ''
  name: clientReferenceId
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: PaymentResponse
  type: ''
- container: ''
  name: payments
  type: string
- container: ''
  name: PaymentListResponse
  type: ''
- container: ''
  name: statementId
  type: string
- container: ''
  name: statementDate
  type: string
- container: ''
  name: openingBalance
  type: decimal
- container: ''
  name: closingBalance
  type: decimal
- container: ''
  name: totalCredits
  type: decimal
- container: ''
  name: totalDebits
  type: decimal
- container: ''
  name: transactionCount
  type: integer
- container: ''
  name: Statement
  type: ''
- container: ''
  name: statements
  type: string
- container: ''
  name: StatementListResponse
  type: ''
- container: ''
  name: errorCode
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: ErrorResponse
  type: ''
property_count: 65
provider_name: Bank of America
provider_slug: bank-of-america
slug: bank-of-america-context
source_filename: bank-of-america-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"bofaapi\": \"https://api-evangelist.github.io/bank-of-america/vocab#\",\n    \"accountId\": {\n      \"@id\": \"bofaapi:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"bofaapi:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"bofaapi:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"bofaapi:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"bofaapi:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingNumber\": {\n      \"@id\": \"bofaapi:routingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bofaapi:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openDate\": {\n      \"@id\": \"\
  bofaapi:openDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Account\": {\n      \"@id\": \"bofaapi:Account\"\n    },\n    \"accounts\": {\n      \"@id\": \"bofaapi:accounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"bofaapi:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"bofaapi:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"bofaapi:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AccountListResponse\": {\n      \"@id\": \"bofaapi:AccountListResponse\"\n    },\n    \"ledgerBalance\": {\n      \"@id\": \"bofaapi:ledgerBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availableBalance\": {\n      \"@id\": \"bofaapi:availableBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"collectedBalance\": {\n      \"@id\": \"bofaapi:collectedBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"asOfDate\": {\n      \"@id\": \"\
  bofaapi:asOfDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Balance\": {\n      \"@id\": \"bofaapi:Balance\"\n    },\n    \"balances\": {\n      \"@id\": \"bofaapi:balances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BalanceResponse\": {\n      \"@id\": \"bofaapi:BalanceResponse\"\n    },\n    \"transactionId\": {\n      \"@id\": \"bofaapi:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bofaapi:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"bofaapi:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"description\": {\n      \"@id\": \"bofaapi:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceNumber\": {\n      \"@id\": \"bofaapi:referenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueDate\": {\n      \"@id\": \"bofaapi:valueDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postDate\": {\n      \"@id\": \"bofaapi:postDate\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"Transaction\": {\n      \"@id\": \"bofaapi:Transaction\"\n    },\n    \"transactions\": {\n      \"@id\": \"bofaapi:transactions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactionListResponse\": {\n      \"@id\": \"bofaapi:TransactionListResponse\"\n    },\n    \"paymentType\": {\n      \"@id\": \"bofaapi:paymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debitAccountId\": {\n      \"@id\": \"bofaapi:debitAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"bofaapi:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memo\": {\n      \"@id\": \"bofaapi:memo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiary\": {\n      \"@id\": \"bofaapi:beneficiary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentRequest\": {\n      \"@id\": \"bofaapi:PaymentRequest\"\n    },\n    \"name\": {\n      \"@id\": \"bofaapi:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankName\"\
  : {\n      \"@id\": \"bofaapi:bankName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAddress\": {\n      \"@id\": \"bofaapi:bankAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swiftCode\": {\n      \"@id\": \"bofaapi:swiftCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Beneficiary\": {\n      \"@id\": \"bofaapi:Beneficiary\"\n    },\n    \"paymentId\": {\n      \"@id\": \"bofaapi:paymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientReferenceId\": {\n      \"@id\": \"bofaapi:clientReferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"bofaapi:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"bofaapi:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"bofaapi:statusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentResponse\": {\n      \"@id\": \"bofaapi:PaymentResponse\"\n    },\n    \"payments\": {\n\
  \      \"@id\": \"bofaapi:payments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentListResponse\": {\n      \"@id\": \"bofaapi:PaymentListResponse\"\n    },\n    \"statementId\": {\n      \"@id\": \"bofaapi:statementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statementDate\": {\n      \"@id\": \"bofaapi:statementDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openingBalance\": {\n      \"@id\": \"bofaapi:openingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"closingBalance\": {\n      \"@id\": \"bofaapi:closingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalCredits\": {\n      \"@id\": \"bofaapi:totalCredits\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalDebits\": {\n      \"@id\": \"bofaapi:totalDebits\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionCount\": {\n      \"@id\": \"bofaapi:transactionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Statement\": {\n      \"@id\": \"bofaapi:Statement\"\
  \n    },\n    \"statements\": {\n      \"@id\": \"bofaapi:statements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatementListResponse\": {\n      \"@id\": \"bofaapi:StatementListResponse\"\n    },\n    \"errorCode\": {\n      \"@id\": \"bofaapi:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bofaapi:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"bofaapi:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"bofaapi:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"bofaapi:ErrorResponse\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/json-ld/bank-of-america-context.jsonld
tags:
- Banking
- Corporate Banking
- Finance
- Payments
- Treasury
- CashPro
- JSON-LD
- Linked Data
- Semantic Web
---
