---
class_count: 3
classes:
- CompanyUser
- email
- name
context_file: json-ld/adyen-management-company-user-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-company-user-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Company User from Adyen.
layout: jsonld
name: Adyen Management Company User Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Links
  type: string
- container: set
  name: accountGroups
  type: string
- container: ''
  name: active
  type: boolean
- container: set
  name: apps
  type: string
- container: set
  name: associatedMerchantAccounts
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: roles
  type: string
- container: ''
  name: timeZoneCode
  type: string
- container: ''
  name: username
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-company-user-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CompanyUser\": \"adyen:CompanyUser\",\n    \"Links\": {\n      \"@id\": \"adyen:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountGroups\": {\n      \"@id\": \"adyen:accountGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"adyen:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"apps\": {\n      \"@id\": \"adyen:apps\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedMerchantAccounts\": {\n      \"@id\": \"adyen:associatedMerchantAccounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"roles\": {\n      \"@id\": \"adyen:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZoneCode\": {\n      \"@id\": \"adyen:timeZoneCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"adyen:username\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-company-user-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
