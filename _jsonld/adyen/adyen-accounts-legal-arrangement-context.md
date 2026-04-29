---
class_count: 5
classes:
- LegalArrangementDetail
- LegalArrangementEntityDetail
- LegalArrangementRequest
- name
- email
context_file: json-ld/adyen-accounts-legal-arrangement-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-legal-arrangement-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Legal Arrangement from Adyen.
layout: jsonld
name: Adyen Accounts Legal Arrangement Context
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
  name: address
  type: string
- container: ''
  name: legalArrangementCode
  type: string
- container: set
  name: legalArrangementEntities
  type: string
- container: ''
  name: legalArrangementReference
  type: string
- container: ''
  name: legalForm
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: ''
  name: taxNumber
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: businessDetails
  type: string
- container: ''
  name: fullPhoneNumber
  type: string
- container: ''
  name: individualDetails
  type: string
- container: ''
  name: legalArrangementEntityCode
  type: string
- container: ''
  name: legalArrangementEntityReference
  type: string
- container: set
  name: legalArrangementMembers
  type: string
- container: ''
  name: legalEntityType
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: webAddress
  type: string
- container: set
  name: legalArrangementEntityCodes
  type: string
property_count: 18
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-legal-arrangement-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LegalArrangementDetail\": \"adyen:LegalArrangementDetail\",\n    \"LegalArrangementEntityDetail\": \"adyen:LegalArrangementEntityDetail\",\n    \"LegalArrangementRequest\": \"adyen:LegalArrangementRequest\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementCode\": {\n      \"@id\": \"adyen:legalArrangementCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntities\": {\n      \"@id\": \"adyen:legalArrangementEntities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementReference\": {\n      \"@id\": \"adyen:legalArrangementReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalForm\"\
  : {\n      \"@id\": \"adyen:legalForm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"registrationNumber\": {\n      \"@id\": \"adyen:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxNumber\": {\n      \"@id\": \"adyen:taxNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessDetails\": {\n      \"@id\": \"adyen:businessDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"fullPhoneNumber\": {\n      \"@id\": \"adyen:fullPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"individualDetails\": {\n      \"@id\": \"adyen:individualDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityCode\": {\n      \"@id\": \"adyen:legalArrangementEntityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityReference\": {\n      \"@id\": \"adyen:legalArrangementEntityReference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementMembers\": {\n      \"@id\": \"adyen:legalArrangementMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntityType\": {\n      \"@id\": \"adyen:legalEntityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webAddress\": {\n      \"@id\": \"adyen:webAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityCodes\": {\n      \"@id\": \"adyen:legalArrangementEntityCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-legal-arrangement-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
