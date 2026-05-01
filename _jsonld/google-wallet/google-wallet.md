---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Wallet API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-wallet/refs/heads/main/openapi/openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-wallet.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-wallet/refs/heads/main/json-ld/google-wallet.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Wallet from Google Wallet.
layout: jsonld
name: Google Wallet Context
namespaces:
- prefix: gwallet
  uri: https://developers.google.com/wallet/reference/rest/v1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: GenericClass
  type: ''
- container: ''
  name: GenericObject
  type: ''
- container: ''
  name: EventTicketClass
  type: ''
- container: ''
  name: LoyaltyClass
  type: ''
- container: ''
  name: classId
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: barcode
  type: '@json'
- container: ''
  name: issuerName
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: programName
  type: string
- container: ''
  name: saveUri
  type: reference
property_count: 11
provider_name: Google Wallet
provider_slug: google-wallet
slug: google-wallet
source_filename: google-wallet.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gwallet\": \"https://developers.google.com/wallet/reference/rest/v1/\",\n    \"GenericClass\": {\n      \"@id\": \"gwallet:genericclass\"\n    },\n    \"GenericObject\": {\n      \"@id\": \"gwallet:genericobject\"\n    },\n    \"EventTicketClass\": {\n      \"@id\": \"gwallet:eventticketclass\"\n    },\n    \"LoyaltyClass\": {\n      \"@id\": \"gwallet:loyaltyclass\"\n    },\n    \"classId\": {\n      \"@id\": \"gwallet:classId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"gwallet:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"barcode\": {\n      \"@id\": \"gwallet:barcode\",\n      \"@type\": \"@json\"\n    },\n    \"issuerName\": {\n      \"@id\": \"https://schema.org/name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"https://schema.org/name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programName\": {\n      \"@id\"\
  : \"gwallet:programName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saveUri\": {\n      \"@id\": \"gwallet:saveUri\",\n      \"@type\": \"@id\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-wallet/refs/heads/main/json-ld/google-wallet.jsonld
tags:
- Digital Wallet
- Google Wallet
- Loyalty Cards
- Mobile Payments
- Passes
- Tickets
- JSON-LD
- Linked Data
- Semantic Web
---
