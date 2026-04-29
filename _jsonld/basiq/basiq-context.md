---
api_specs:
- filename: basiq-api-openapi.yml
  format: yaml
  label: Basiq API
  slug: basiq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/openapi/basiq-api-openapi.yml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"basiq\": \"https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/json-ld/\",\n    \"User\": \"schema:Person\",\n    \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"email\": {\"@id\": \"schema:email\", \"@type\": \"xsd:string\"},\n    \"mobile\": {\"@id\": \"schema:telephone\", \"@type\": \"xsd:string\"},\n    \"firstName\": {\"@id\": \"schema:givenName\", \"@type\": \"xsd:string\"},\n    \"lastName\": {\"@id\": \"schema:familyName\", \"@type\": \"xsd:string\"},\n    \"createdDate\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"Connection\": \"basiq:Connection\",\n    \"status\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"institution\": {\"@id\": \"schema:Organization\", \"@type\"\
  : \"xsd:string\"},\n    \"lastUpdated\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"Account\": \"fibo:FinancialAccount\",\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"accountNo\": {\"@id\": \"schema:accountId\", \"@type\": \"xsd:string\"},\n    \"currency\": {\"@id\": \"schema:currency\", \"@type\": \"xsd:string\"},\n    \"balance\": {\"@id\": \"schema:amount\", \"@type\": \"xsd:decimal\"},\n    \"availableFunds\": {\"@id\": \"basiq:availableFunds\", \"@type\": \"xsd:decimal\"},\n    \"accountType\": {\"@id\": \"basiq:accountType\", \"@type\": \"xsd:string\"},\n    \"Transaction\": \"schema:MoneyTransfer\",\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"amount\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n    \"direction\": {\"@id\": \"basiq:direction\", \"@type\": \"xsd:string\"},\n    \"class\": {\"@id\": \"schema:category\", \"@type\": \"xsd:string\"},\n    \"transactionDate\"\
  : {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n    \"postDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:date\"},\n    \"IncomeVerification\": \"basiq:IncomeVerification\",\n    \"userId\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"summary\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"incomeStreams\": {\"@id\": \"basiq:incomeStreams\", \"@type\": \"xsd:string\"},\n    \"ExpenseReport\": \"basiq:ExpenseReport\",\n    \"categories\": {\"@id\": \"schema:category\", \"@type\": \"xsd:string\"},\n    \"TokenResponse\": \"basiq:TokenResponse\",\n    \"access_token\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"token_type\": {\"@id\": \"basiq:tokenType\", \"@type\": \"xsd:string\"},\n    \"expires_in\": {\"@id\": \"basiq:expiresIn\", \"@type\": \"xsd:integer\"},\n    \"ErrorResponse\": \"basiq:ErrorResponse\",\n    \"type\": {\"@id\": \"schema:additionalType\", \"@type\": \"xsd:string\"},\n    \"title\"\
  : {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"detail\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/json-ld/basiq-context.jsonld
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
