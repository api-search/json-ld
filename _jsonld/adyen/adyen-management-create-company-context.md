---
class_count: 7
classes:
- CreateCompanyUserRequest
- CreateCompanyUserResponse
- CreateCompanyWebhookRequest
- email
- name
- description
- url
context_file: json-ld/adyen-management-create-company-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-create-company-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Create Company from Adyen.
layout: jsonld
name: Adyen Management Create Company Context
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
- container: set
  name: accountGroups
  type: string
- container: set
  name: associatedMerchantAccounts
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
- container: ''
  name: Links
  type: string
- container: ''
  name: active
  type: boolean
- container: set
  name: apps
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: acceptsExpiredCertificate
  type: boolean
- container: ''
  name: acceptsSelfSignedCertificate
  type: boolean
- container: ''
  name: acceptsUntrustedRootCertificate
  type: boolean
- container: ''
  name: additionalSettings
  type: string
- container: ''
  name: communicationFormat
  type: string
- container: ''
  name: encryptionProtocol
  type: string
- container: ''
  name: filterMerchantAccountType
  type: string
- container: set
  name: filterMerchantAccounts
  type: string
- container: ''
  name: networkType
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: populateSoapActionHeader
  type: boolean
- container: ''
  name: type
  type: string
property_count: 21
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-create-company-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateCompanyUserRequest\": \"adyen:CreateCompanyUserRequest\",\n    \"CreateCompanyUserResponse\": \"adyen:CreateCompanyUserResponse\",\n    \"CreateCompanyWebhookRequest\": \"adyen:CreateCompanyWebhookRequest\",\n    \"accountGroups\": {\n      \"@id\": \"adyen:accountGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedMerchantAccounts\": {\n      \"@id\": \"adyen:associatedMerchantAccounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"name\": \"schema:name\",\n    \"roles\": {\n      \"@id\": \"adyen:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZoneCode\": {\n\
  \      \"@id\": \"adyen:timeZoneCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"adyen:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Links\": {\n      \"@id\": \"adyen:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"adyen:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"apps\": {\n      \"@id\": \"adyen:apps\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acceptsExpiredCertificate\": {\n      \"@id\": \"adyen:acceptsExpiredCertificate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"acceptsSelfSignedCertificate\": {\n      \"@id\": \"adyen:acceptsSelfSignedCertificate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"acceptsUntrustedRootCertificate\": {\n      \"@id\": \"adyen:acceptsUntrustedRootCertificate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  additionalSettings\": {\n      \"@id\": \"adyen:additionalSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"communicationFormat\": {\n      \"@id\": \"adyen:communicationFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"encryptionProtocol\": {\n      \"@id\": \"adyen:encryptionProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterMerchantAccountType\": {\n      \"@id\": \"adyen:filterMerchantAccountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterMerchantAccounts\": {\n      \"@id\": \"adyen:filterMerchantAccounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkType\": {\n      \"@id\": \"adyen:networkType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"adyen:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"populateSoapActionHeader\": {\n      \"@id\": \"adyen:populateSoapActionHeader\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-create-company-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
