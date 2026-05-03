---
api_specs:
- filename: telefonie-voice-openapi.yml
  format: yaml
  label: Telefonie Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-voice-openapi.yml
- filename: telefonie-sms-openapi.yml
  format: yaml
  label: Telefonie SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-sms-openapi.yml
- filename: telefonie-numbers-openapi.yml
  format: yaml
  label: Telefonie Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-numbers-openapi.yml
- filename: telefonie-recording-openapi.yml
  format: yaml
  label: Telefonie Call Recording API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-recording-openapi.yml
class_count: 5
classes:
- Call
- Message
- PhoneNumber
- Conference
- Recording
context_file: json-ld/telefonie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/json-ld/telefonie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telefonie from Telefonie.
layout: jsonld
name: Telefonie Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: telefonie
  uri: https://developers.telefonie.com/schema/
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
  name: date_sent
  type: dateTime
- container: ''
  name: error_code
  type: integer
- container: ''
  name: error_message
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: media_url
  type: anyURI
property_count: 21
provider_name: Telefonie
provider_slug: telefonie
slug: telefonie-context
source_filename: telefonie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"telefonie\": \"https://developers.telefonie.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Call\": \"telefonie:Call\",\n    \"Message\": \"telefonie:Message\",\n    \"PhoneNumber\": \"schema:ContactPoint\",\n    \"Conference\": \"telefonie:Conference\",\n    \"Recording\": \"telefonie:Recording\",\n\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"telefonie:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"telefonie:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"schema:sender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"schema:recipient\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start_time\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"end_time\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price_unit\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recording_url\": {\n      \"@id\": \"telefonie:recordingUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"phone_number\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country_code\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"friendly_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date_created\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"date_sent\": {\n      \"@id\": \"telefonie:dateSent\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"error_code\": {\n      \"@id\": \"telefonie:errorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error_message\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"telefonie:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"media_url\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"xsd:anyURI\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/json-ld/telefonie-context.jsonld
tags:
- Call Recording
- CPaaS
- Messaging
- Number Provisioning
- SMS
- Telecommunications
- Telephony
- Voice
- VoIP
- JSON-LD
- Linked Data
- Semantic Web
---
