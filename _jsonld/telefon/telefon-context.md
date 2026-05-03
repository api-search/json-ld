---
api_specs:
- filename: telefon-voice-openapi.yml
  format: yaml
  label: Telefon Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-voice-openapi.yml
- filename: telefon-sms-openapi.yml
  format: yaml
  label: Telefon SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-sms-openapi.yml
- filename: telefon-numbers-openapi.yml
  format: yaml
  label: Telefon Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-numbers-openapi.yml
- filename: telefon-recording-openapi.yml
  format: yaml
  label: Telefon Call Recording API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-recording-openapi.yml
class_count: 6
classes:
- Call
- Message
- Recording
- Transcription
- Conference
- PhoneNumber
context_file: json-ld/telefon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/json-ld/telefon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telefon from Telefon.
layout: jsonld
name: Telefon Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: telefon
  uri: https://developers.telefon.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: start_time
  type: dateTime
- container: ''
  name: end_time
  type: dateTime
- container: ''
  name: price
  type: string
- container: ''
  name: price_unit
  type: string
- container: ''
  name: recording_url
  type: anyURI
- container: ''
  name: media_url
  type: anyURI
- container: ''
  name: phone_number
  type: string
- container: ''
  name: country_code
  type: string
- container: ''
  name: friendly_name
  type: string
- container: ''
  name: date_created
  type: dateTime
- container: ''
  name: transcript_text
  type: string
- container: ''
  name: language_code
  type: string
- container: ''
  name: confidence
  type: decimal
property_count: 20
provider_name: Telefon
provider_slug: telefon
slug: telefon-context
source_filename: telefon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"telefon\": \"https://developers.telefon.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Call\": \"telefon:Call\",\n    \"Message\": \"telefon:Message\",\n    \"Recording\": \"telefon:Recording\",\n    \"Transcription\": \"telefon:Transcription\",\n    \"Conference\": \"telefon:Conference\",\n    \"PhoneNumber\": \"schema:ContactPoint\",\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"telefon:status\", \"@type\": \"xsd:string\" },\n    \"direction\": { \"@id\": \"telefon:direction\", \"@type\": \"xsd:string\" },\n    \"from\": { \"@id\": \"schema:sender\", \"@type\": \"xsd:string\" },\n    \"to\": { \"@id\": \"schema:recipient\", \"@type\": \"xsd:string\" },\n    \"body\": { \"@id\": \"schema:text\", \"@type\": \"xsd:string\" },\n    \"duration\": { \"@id\": \"schema:duration\", \"@type\": \"xsd:integer\"\
  \ },\n    \"start_time\": { \"@id\": \"schema:startTime\", \"@type\": \"xsd:dateTime\" },\n    \"end_time\": { \"@id\": \"schema:endTime\", \"@type\": \"xsd:dateTime\" },\n    \"price\": { \"@id\": \"schema:price\", \"@type\": \"xsd:string\" },\n    \"price_unit\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n    \"recording_url\": { \"@id\": \"telefon:recordingUrl\", \"@type\": \"xsd:anyURI\" },\n    \"media_url\": { \"@id\": \"schema:contentUrl\", \"@type\": \"xsd:anyURI\" },\n    \"phone_number\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"country_code\": { \"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\" },\n    \"friendly_name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"date_created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"transcript_text\": { \"@id\": \"schema:text\", \"@type\": \"xsd:string\" },\n    \"language_code\": { \"@id\": \"schema:inLanguage\", \"@type\"\
  : \"xsd:string\" },\n    \"confidence\": { \"@id\": \"telefon:confidence\", \"@type\": \"xsd:decimal\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/json-ld/telefon-context.jsonld
tags:
- Call Recording
- Communications
- CPaaS
- Global Coverage
- Messaging
- Number Provisioning
- SMS
- Telephony
- Voice
- VoIP
- JSON-LD
- Linked Data
- Semantic Web
---
