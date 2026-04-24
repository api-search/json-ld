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
