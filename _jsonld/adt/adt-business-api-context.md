---
class_count: 11
classes:
- User
- UserList
- CredentialList
- Credential
- EventReport
- SiteList
- Site
- CredentialInput
- name
- email
- address
context_file: json-ld/adt-business-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/json-ld/adt-business-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adt Business Api from ADT.
layout: jsonld
name: Adt Business Api Context
namespaces:
- prefix: adt
  uri: https://api.adt.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: role
  type: string
- container: set
  name: users
  type: string
- container: set
  name: credentials
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: validFrom
  type: dateTime
- container: ''
  name: validTo
  type: dateTime
- container: ''
  name: siteId
  type: string
- container: ''
  name: period
  type: reference
- container: ''
  name: summary
  type: reference
- container: set
  name: events
  type: string
- container: set
  name: sites
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: systemCount
  type: integer
- container: ''
  name: cardNumber
  type: string
property_count: 17
provider_name: ADT
provider_slug: adt
slug: adt-business-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adt\": \"https://api.adt.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"User\": \"adt:User\",\n    \"UserList\": \"adt:UserList\",\n    \"CredentialList\": \"adt:CredentialList\",\n    \"Credential\": \"adt:Credential\",\n    \"EventReport\": \"adt:EventReport\",\n    \"SiteList\": \"adt:SiteList\",\n    \"Site\": \"adt:Site\",\n    \"CredentialInput\": \"adt:CredentialInput\",\n    \"id\": {\n      \"@id\": \"adt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"role\": {\n      \"@id\": \"adt:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"adt:users\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credentials\": {\n      \"@id\": \"adt:credentials\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"adt:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adt:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validFrom\": {\n      \"@id\": \"adt:validFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"validTo\": {\n      \"@id\": \"adt:validTo\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"siteId\": {\n      \"@id\": \"adt:siteId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"adt:period\",\n      \"@type\": \"@id\"\n    },\n    \"summary\": {\n      \"@id\": \"adt:summary\",\n      \"@type\": \"@id\"\n    },\n    \"events\": {\n      \"@id\": \"adt:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sites\": {\n      \"@id\": \"adt:sites\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"adt:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"address\": \"schema:address\",\n    \"systemCount\": {\n      \"@id\": \"adt:systemCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cardNumber\": {\n      \"@id\": \"adt:cardNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/json-ld/adt-business-api-context.jsonld
tags:
- Access Control
- Automation
- Home Security
- IoT
- Monitoring
- Security
- Smart Home
- JSON-LD
- Linked Data
- Semantic Web
---
