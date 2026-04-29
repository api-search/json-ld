---
class_count: 8
classes:
- Expense
- ExpenseListResponse
- InviteMemberRequest
- Member
- MemberListResponse
- OAuthTokenRequest
- OAuthTokenResponse
- UpdateMemberRequest
context_file: json-ld/abacus-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-ld/abacus-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abacus Api from Abacus.
layout: jsonld
name: Abacus Api Context
namespaces:
- prefix: abacus
  uri: https://api.abacus.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: expenses
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: perPage
  type: integer
- container: ''
  name: email
  type: ''
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: department
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: memberId
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: date
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: receiptUrl
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: grantType
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: set
  name: members
  type: ''
- container: ''
  name: accessToken
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: expiresIn
  type: integer
property_count: 27
provider_name: Abacus
provider_slug: abacus
slug: abacus-api-context
source_filename: abacus-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abacus\": \"https://api.abacus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Expense\": \"abacus:Expense\",\n    \"ExpenseListResponse\": \"abacus:ExpenseListResponse\",\n    \"InviteMemberRequest\": \"abacus:InviteMemberRequest\",\n    \"Member\": \"abacus:Member\",\n    \"MemberListResponse\": \"abacus:MemberListResponse\",\n    \"OAuthTokenRequest\": \"abacus:OAuthTokenRequest\",\n    \"OAuthTokenResponse\": \"abacus:OAuthTokenResponse\",\n    \"UpdateMemberRequest\": \"abacus:UpdateMemberRequest\",\n    \"expenses\": {\n      \"@id\": \"abacus:expenses\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\": \"abacus:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"abacus:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perPage\": {\n  \
  \    \"@id\": \"abacus:per_page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"firstName\": {\n      \"@id\": \"abacus:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"abacus:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"abacus:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department\": {\n      \"@id\": \"abacus:department\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"abacus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberId\": {\n      \"@id\": \"abacus:member_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"abacus:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"abacus:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"abacus:category\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"date\": {\n      \"@id\": \"abacus:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"abacus:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receiptUrl\": {\n      \"@id\": \"abacus:receipt_url\"\n    },\n    \"createdAt\": {\n      \"@id\": \"abacus:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"abacus:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"grantType\": {\n      \"@id\": \"abacus:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"abacus:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"abacus:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"members\": {\n      \"@id\": \"abacus:members\",\n      \"@container\": \"@set\"\n    },\n    \"accessToken\": {\n      \"@id\": \"abacus:access_token\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"abacus:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"abacus:expires_in\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-ld/abacus-api-context.jsonld
tags:
- Accounting
- Expense Management
- Finance
- Reimbursement
- JSON-LD
- Linked Data
- Semantic Web
---
