---
class_count: 0
classes: []
context_file: json-ld/google-voice.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-voice/refs/heads/main/json-ld/google-voice.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Voice from Google Voice.
layout: jsonld
name: Google Voice Context
namespaces:
- prefix: gvoice
  uri: https://voice.google.com/about#
- prefix: Person
  uri: https://schema.org/Person
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: primaryEmail
  type: string
- container: ''
  name: givenName
  type: string
- container: ''
  name: familyName
  type: string
- container: ''
  name: telephone
  type: string
- container: ''
  name: building
  type: string
- container: ''
  name: address
  type: https://schema.org/PostalAddress
- container: ''
  name: voicemail
  type: string
- container: ''
  name: callForwarding
  type: '@json'
- container: ''
  name: doNotDisturb
  type: boolean
property_count: 9
provider_name: Google Voice
provider_slug: google-voice
slug: google-voice
source_filename: google-voice.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gvoice\": \"https://voice.google.com/about#\",\n    \"Person\": \"https://schema.org/Person\",\n    \"primaryEmail\": {\n      \"@id\": \"https://schema.org/email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"givenName\": {\n      \"@id\": \"https://schema.org/givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"familyName\": {\n      \"@id\": \"https://schema.org/familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephone\": {\n      \"@id\": \"https://schema.org/telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"building\": {\n      \"@id\": \"gvoice:building\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"https://schema.org/address\",\n      \"@type\": \"https://schema.org/PostalAddress\"\n    },\n    \"voicemail\": {\n      \"@id\": \"gvoice:voicemail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callForwarding\": {\n      \"@id\"\
  : \"gvoice:callForwarding\",\n      \"@type\": \"@json\"\n    },\n    \"doNotDisturb\": {\n      \"@id\": \"gvoice:doNotDisturb\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-voice/refs/heads/main/json-ld/google-voice.jsonld
tags:
- Google Voice
- Messaging
- Phone
- Telecommunications
- Voice
- Voicemail
- VoIP
- JSON-LD
- Linked Data
- Semantic Web
---
