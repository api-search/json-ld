---
class_count: 0
classes: []
context_file: json-ld/bny-mellon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bank-of-new-york-mellon/refs/heads/main/json-ld/bny-mellon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bny Mellon from BNY Mellon.
layout: jsonld
name: Bny Mellon Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bnyapi
  uri: https://api-evangelist.github.io/bank-of-new-york-mellon/vocab#
properties:
- container: ''
  name: Account
  type: ''
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
  name: status
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: AccountListResponse
  type: ''
- container: ''
  name: accounts
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: Balance
  type: ''
- container: ''
  name: balanceType
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: asOfDateTime
  type: string
- container: ''
  name: openingBalance
  type: decimal
- container: ''
  name: closingBalance
  type: decimal
- container: ''
  name: BalanceResponse
  type: ''
- container: ''
  name: balances
  type: string
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: transactionId
  type: string
- container: ''
  name: debitCredit
  type: string
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
  name: bookingDate
  type: string
- container: ''
  name: TransactionListResponse
  type: ''
- container: ''
  name: transactions
  type: string
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: PaymentRequest
  type: ''
- container: ''
  name: paymentType
  type: string
- container: ''
  name: debitAccountId
  type: string
- container: ''
  name: creditorName
  type: string
- container: ''
  name: creditorAccountNumber
  type: string
- container: ''
  name: creditorBankCode
  type: string
- container: ''
  name: creditorSwiftCode
  type: string
- container: ''
  name: remittanceInfo
  type: string
- container: ''
  name: clientReference
  type: string
- container: ''
  name: PaymentResponse
  type: ''
- container: ''
  name: paymentId
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: PaymentListResponse
  type: ''
- container: ''
  name: payments
  type: string
- container: ''
  name: FundsTransferRequest
  type: ''
- container: ''
  name: creditAccountId
  type: string
- container: ''
  name: memo
  type: string
- container: ''
  name: FundsTransferResponse
  type: ''
- container: ''
  name: transferId
  type: string
- container: ''
  name: ErrorResponse
  type: ''
- container: ''
  name: errorCode
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: details
  type: string
property_count: 54
provider_name: BNY Mellon
provider_slug: bank-of-new-york-mellon
slug: bny-mellon-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"bnyapi\": \"https://api-evangelist.github.io/bank-of-new-york-mellon/vocab#\",\n    \"Account\": {\n      \"@id\": \"bnyapi:Account\"\n    },\n    \"accountId\": {\n      \"@id\": \"bnyapi:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"bnyapi:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"bnyapi:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"bnyapi:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"bnyapi:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bnyapi:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"bnyapi:bankCode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"AccountListResponse\": {\n      \"@id\": \"bnyapi:AccountListResponse\"\n    },\n    \"accounts\": {\n      \"@id\": \"bnyapi:accounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"bnyapi:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Balance\": {\n      \"@id\": \"bnyapi:Balance\"\n    },\n    \"balanceType\": {\n      \"@id\": \"bnyapi:balanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"bnyapi:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"asOfDateTime\": {\n      \"@id\": \"bnyapi:asOfDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openingBalance\": {\n      \"@id\": \"bnyapi:openingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"closingBalance\": {\n      \"@id\": \"bnyapi:closingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"BalanceResponse\": {\n      \"@id\": \"bnyapi:BalanceResponse\"\n    },\n    \"balances\": {\n    \
  \  \"@id\": \"bnyapi:balances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Transaction\": {\n      \"@id\": \"bnyapi:Transaction\"\n    },\n    \"transactionId\": {\n      \"@id\": \"bnyapi:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debitCredit\": {\n      \"@id\": \"bnyapi:debitCredit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"bnyapi:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceNumber\": {\n      \"@id\": \"bnyapi:referenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueDate\": {\n      \"@id\": \"bnyapi:valueDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingDate\": {\n      \"@id\": \"bnyapi:bookingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactionListResponse\": {\n      \"@id\": \"bnyapi:TransactionListResponse\"\n    },\n    \"transactions\": {\n      \"@id\": \"bnyapi:transactions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageSize\"\
  : {\n      \"@id\": \"bnyapi:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PaymentRequest\": {\n      \"@id\": \"bnyapi:PaymentRequest\"\n    },\n    \"paymentType\": {\n      \"@id\": \"bnyapi:paymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debitAccountId\": {\n      \"@id\": \"bnyapi:debitAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditorName\": {\n      \"@id\": \"bnyapi:creditorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditorAccountNumber\": {\n      \"@id\": \"bnyapi:creditorAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditorBankCode\": {\n      \"@id\": \"bnyapi:creditorBankCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditorSwiftCode\": {\n      \"@id\": \"bnyapi:creditorSwiftCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remittanceInfo\": {\n      \"@id\": \"bnyapi:remittanceInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientReference\": {\n      \"@id\": \"bnyapi:clientReference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentResponse\": {\n      \"@id\": \"bnyapi:PaymentResponse\"\n    },\n    \"paymentId\": {\n      \"@id\": \"bnyapi:paymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"bnyapi:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"bnyapi:statusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentListResponse\": {\n      \"@id\": \"bnyapi:PaymentListResponse\"\n    },\n    \"payments\": {\n      \"@id\": \"bnyapi:payments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FundsTransferRequest\": {\n      \"@id\": \"bnyapi:FundsTransferRequest\"\n    },\n    \"creditAccountId\": {\n      \"@id\": \"bnyapi:creditAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memo\": {\n      \"@id\": \"bnyapi:memo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FundsTransferResponse\": {\n      \"@id\": \"bnyapi:FundsTransferResponse\"\n   \
  \ },\n    \"transferId\": {\n      \"@id\": \"bnyapi:transferId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"bnyapi:ErrorResponse\"\n    },\n    \"errorCode\": {\n      \"@id\": \"bnyapi:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bnyapi:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"bnyapi:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"bnyapi:details\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bank-of-new-york-mellon/refs/heads/main/json-ld/bny-mellon-context.jsonld
tags:
- Asset Servicing
- Banking
- Institutional Banking
- Payments
- Treasury
- Wire Transfers
- JSON-LD
- Linked Data
- Semantic Web
---
