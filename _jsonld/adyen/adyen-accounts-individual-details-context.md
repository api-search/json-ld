---
class_count: 2
classes:
- IndividualDetails
- name
context_file: json-ld/adyen-accounts-individual-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-individual-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Individual Details from Adyen.
layout: jsonld
name: Adyen Accounts Individual Details Context
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
  name: personalData
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-individual-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IndividualDetails\": \"adyen:IndividualDetails\",\n    \"name\": \"schema:name\",\n    \"personalData\": {\n      \"@id\": \"adyen:personalData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-individual-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
