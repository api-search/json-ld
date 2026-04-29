---
class_count: 3
classes:
- Individual
- email
- name
context_file: json-ld/adyen-legal-entity-individual-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-individual-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Individual from Adyen.
layout: jsonld
name: Adyen Legal Entity Individual Context
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
  name: birthData
  type: string
- container: ''
  name: identificationData
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: residentialAddress
  type: string
- container: set
  name: taxInformation
  type: string
- container: ''
  name: webData
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-individual-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Individual\": \"adyen:Individual\",\n    \"birthData\": {\n      \"@id\": \"adyen:birthData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"identificationData\": {\n      \"@id\": \"adyen:identificationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nationality\": {\n      \"@id\": \"adyen:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"adyen:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"residentialAddress\": {\n      \"@id\": \"adyen:residentialAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxInformation\": {\n      \"@id\": \"adyen:taxInformation\",\n      \"@container\": \"@set\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"webData\": {\n      \"@id\": \"adyen:webData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-individual-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
