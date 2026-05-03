---
api_specs:
- filename: rainbow-application-openapi.yml
  format: yaml
  label: Rainbow Application Portal API
  slug: rainbow-application-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/openapi/rainbow-application-openapi.yml
- filename: rainbow-messaging-openapi.yml
  format: yaml
  label: Rainbow Messaging API
  slug: rainbow-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/openapi/rainbow-messaging-openapi.yml
- filename: rainbow-contacts-openapi.yml
  format: yaml
  label: Rainbow Contacts API
  slug: rainbow-contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/openapi/rainbow-contacts-openapi.yml
class_count: 18
classes:
- Message
- Conversation
- Bubble
- Contact
- UserProfile
- Presence
- Application
- id
- displayName
- firstName
- lastName
- company
- jobTitle
- content
- type
- status
- name
- topic
context_file: json-ld/rainbow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/json-ld/rainbow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rainbow from Rainbow.
layout: jsonld
name: Rainbow Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rainbow
  uri: https://openrainbow.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: list
  name: emails
  type: ''
- container: list
  name: phoneNumbers
  type: ''
- container: ''
  name: from
  type: reference
- container: ''
  name: to
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: presence
  type: reference
- container: ''
  name: owner
  type: reference
- container: list
  name: users
  type: ''
property_count: 10
provider_name: Rainbow
provider_slug: rainbow
slug: rainbow-context
source_filename: rainbow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rainbow\": \"https://openrainbow.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Message\": \"rainbow:Message\",\n    \"Conversation\": \"rainbow:Conversation\",\n    \"Bubble\": \"rainbow:Bubble\",\n    \"Contact\": \"schema:Person\",\n    \"UserProfile\": \"schema:Person\",\n    \"Presence\": \"rainbow:Presence\",\n    \"Application\": \"rainbow:Application\",\n\n    \"id\": \"@id\",\n    \"displayName\": \"schema:name\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"emails\": {\n      \"@id\": \"schema:email\",\n      \"@container\": \"@list\"\n    },\n    \"phoneNumbers\": {\n      \"@id\": \"schema:telephone\",\n      \"@container\": \"@list\"\n    },\n    \"company\": \"schema:memberOf\",\n    \"jobTitle\": \"schema:jobTitle\",\n    \"content\": \"schema:text\",\n    \"from\": {\n      \"@id\": \"schema:sender\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"to\": {\n      \"@id\": \"schema:recipient\",\n      \"@type\": \"@id\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": \"rainbow:messageType\",\n    \"status\": \"rainbow:deliveryStatus\",\n    \"presence\": {\n      \"@id\": \"rainbow:presenceStatus\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"topic\": \"schema:about\",\n    \"owner\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"users\": {\n      \"@id\": \"schema:member\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/json-ld/rainbow-context.jsonld
tags:
- Communications
- CPaaS
- Chat
- Voice
- Video
- Telephony
- Messaging
- Collaboration
- Unified Communications
- JSON-LD
- Linked Data
- Semantic Web
---
