---
class_count: 1
classes:
- DonationRequest
context_file: json-ld/adyen-payments-donation-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-donation-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Donation Request from Adyen.
layout: jsonld
name: Adyen Payments Donation Request Context
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
  name: donationAccount
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: modificationAmount
  type: string
- container: ''
  name: originalReference
  type: string
- container: ''
  name: platformChargebackLogic
  type: string
- container: ''
  name: reference
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-donation-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DonationRequest\": \"adyen:DonationRequest\",\n    \"donationAccount\": {\n      \"@id\": \"adyen:donationAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationAmount\": {\n      \"@id\": \"adyen:modificationAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalReference\": {\n      \"@id\": \"adyen:originalReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformChargebackLogic\": {\n      \"@id\": \"adyen:platformChargebackLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-donation-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
