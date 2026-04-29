---
class_count: 3
classes:
- UnincorporatedPartnership
- description
- name
context_file: json-ld/adyen-legal-entity-unincorporated-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-unincorporated-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Unincorporated from Adyen.
layout: jsonld
name: Adyen Legal Entity Unincorporated Context
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
  name: countryOfGoverningLaw
  type: string
- container: ''
  name: dateOfIncorporation
  type: string
- container: ''
  name: doingBusinessAs
  type: string
- container: ''
  name: principalPlaceOfBusiness
  type: string
- container: ''
  name: registeredAddress
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: set
  name: taxInformation
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: vatAbsenceReason
  type: string
- container: ''
  name: vatNumber
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-unincorporated-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UnincorporatedPartnership\": \"adyen:UnincorporatedPartnership\",\n    \"countryOfGoverningLaw\": {\n      \"@id\": \"adyen:countryOfGoverningLaw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfIncorporation\": {\n      \"@id\": \"adyen:dateOfIncorporation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"doingBusinessAs\": {\n      \"@id\": \"adyen:doingBusinessAs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"principalPlaceOfBusiness\": {\n      \"@id\": \"adyen:principalPlaceOfBusiness\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registeredAddress\": {\n      \"@id\": \"adyen:registeredAddress\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"registrationNumber\": {\n      \"@id\": \"adyen:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxInformation\": {\n      \"@id\": \"adyen:taxInformation\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vatAbsenceReason\": {\n      \"@id\": \"adyen:vatAbsenceReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vatNumber\": {\n      \"@id\": \"adyen:vatNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-unincorporated-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
