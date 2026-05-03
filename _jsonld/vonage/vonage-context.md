---
api_specs:
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage SMS API
  slug: vonage-sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Voice API
  slug: vonage-voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Messages API
  slug: vonage-messages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Verify API
  slug: vonage-verify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Numbers API
  slug: vonage-numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Application API
  slug: vonage-application-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
class_count: 0
classes: []
context_file: json-ld/vonage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/json-ld/vonage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vonage from Vonage.
layout: jsonld
name: Vonage Context
namespaces:
- prefix: vonage
  uri: https://developer.vonage.com/api/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: Message
  uri: https://schema.org/Message
- prefix: text
  uri: https://schema.org/text
- prefix: recipient
  uri: https://schema.org/recipient
- prefix: sender
  uri: https://schema.org/sender
- prefix: dateSent
  uri: https://schema.org/dateSent
- prefix: messageAttachmentObject
  uri: https://schema.org/messageAttachmentObject
- prefix: Call
  uri: https://schema.org/Thing
- prefix: Verification
  uri: https://schema.org/Thing
- prefix: PhoneNumber
  uri: https://schema.org/ContactPoint
- prefix: telephone
  uri: https://schema.org/telephone
- prefix: Application
  uri: https://schema.org/SoftwareApplication
- prefix: Organization
  uri: https://schema.org/Organization
properties:
- container: ''
  name: vonage:message_uuid
  type: string
- container: ''
  name: vonage:message_type
  type: string
- container: ''
  name: vonage:channel
  type: string
- container: ''
  name: vonage:client_ref
  type: string
- container: ''
  name: vonage:status
  type: string
- container: ''
  name: vonage:call_uuid
  type: string
- container: ''
  name: vonage:call_status
  type: string
- container: ''
  name: vonage:call_direction
  type: string
- container: ''
  name: vonage:call_duration
  type: decimal
- container: ''
  name: vonage:conversation_uuid
  type: string
- container: ''
  name: vonage:request_id
  type: string
- container: ''
  name: vonage:verify_status
  type: string
- container: ''
  name: vonage:msisdn
  type: string
- container: ''
  name: vonage:country
  type: string
- container: ''
  name: vonage:number_type
  type: string
- container: ''
  name: vonage:features
  type: '@vocab'
- container: ''
  name: vonage:app_id
  type: string
- container: ''
  name: vonage:capabilities
  type: '@vocab'
- container: ''
  name: vonage:api_key
  type: string
property_count: 19
provider_name: Vonage
provider_slug: vonage
slug: vonage-context
source_filename: vonage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vonage\": \"https://developer.vonage.com/api/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Message\": \"https://schema.org/Message\",\n    \"text\": \"https://schema.org/text\",\n    \"recipient\": \"https://schema.org/recipient\",\n    \"sender\": \"https://schema.org/sender\",\n    \"dateSent\": \"https://schema.org/dateSent\",\n    \"messageAttachmentObject\": \"https://schema.org/messageAttachmentObject\",\n\n    \"vonage:message_uuid\": {\"@type\": \"xsd:string\"},\n    \"vonage:message_type\": {\"@type\": \"xsd:string\"},\n    \"vonage:channel\": {\"@type\": \"xsd:string\"},\n    \"vonage:client_ref\": {\"@type\": \"xsd:string\"},\n    \"vonage:status\": {\"@type\": \"xsd:string\"},\n\n    \"Call\": \"https://schema.org/Thing\",\n    \"vonage:call_uuid\": {\"@type\": \"xsd:string\"},\n    \"vonage:call_status\": {\"@type\": \"xsd:string\"},\n    \"vonage:call_direction\": {\"@type\"\
  : \"xsd:string\"},\n    \"vonage:call_duration\": {\"@type\": \"xsd:decimal\"},\n    \"vonage:conversation_uuid\": {\"@type\": \"xsd:string\"},\n\n    \"Verification\": \"https://schema.org/Thing\",\n    \"vonage:request_id\": {\"@type\": \"xsd:string\"},\n    \"vonage:verify_status\": {\"@type\": \"xsd:string\"},\n\n    \"PhoneNumber\": \"https://schema.org/ContactPoint\",\n    \"telephone\": \"https://schema.org/telephone\",\n    \"vonage:msisdn\": {\"@type\": \"xsd:string\"},\n    \"vonage:country\": {\"@type\": \"xsd:string\"},\n    \"vonage:number_type\": {\"@type\": \"xsd:string\"},\n    \"vonage:features\": {\"@type\": \"@vocab\"},\n\n    \"Application\": \"https://schema.org/SoftwareApplication\",\n    \"vonage:app_id\": {\"@type\": \"xsd:string\"},\n    \"vonage:capabilities\": {\"@type\": \"@vocab\"},\n\n    \"Organization\": \"https://schema.org/Organization\",\n    \"vonage:api_key\": {\"@type\": \"xsd:string\"}\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://developer.vonage.com/\"\
  ,\n      \"@type\": \"Organization\",\n      \"name\": \"Vonage\",\n      \"description\": \"Cloud communications APIs provider (part of Ericsson)\",\n      \"url\": \"https://developer.vonage.com/\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/json-ld/vonage-context.jsonld
tags:
- Communication
- Messaging
- Telecommunications
- Video Conferencing
- Voice
- SMS
- Verification
- JSON-LD
- Linked Data
- Semantic Web
---
