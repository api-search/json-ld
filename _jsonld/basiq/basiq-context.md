---
class_count: 8
classes:
- User
- Connection
- Account
- Transaction
- IncomeVerification
- ExpenseReport
- TokenResponse
- ErrorResponse
context_file: json-ld/basiq-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/json-ld/basiq-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Basiq from Basiq.
layout: jsonld
name: Basiq Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: basiq
  uri: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/json-ld/
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: mobile
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: institution
  type: string
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: accountNo
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: balance
  type: decimal
- container: ''
  name: availableFunds
  type: decimal
- container: ''
  name: accountType
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: direction
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: postDate
  type: date
- container: ''
  name: userId
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: incomeStreams
  type: string
- container: ''
  name: categories
  type: string
- container: ''
  name: access_token
  type: string
- container: ''
  name: token_type
  type: string
- container: ''
  name: expires_in
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: detail
  type: string
property_count: 32
provider_name: Basiq
provider_slug: basiq
slug: basiq-context
tags:
- Australia
- Banking
- CDR
- Financial Data
- Fintech
- Open Banking
- Transactions
- JSON-LD
- Linked Data
- Semantic Web
---
