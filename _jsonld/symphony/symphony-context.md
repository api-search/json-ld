---
api_specs:
- filename: symphony-pod-api-openapi.yml
  format: yaml
  label: Symphony Pod API
  slug: symphony-pod-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/symphony-pod-api-openapi.yml
- filename: agent-openapi-original.yml
  format: yaml
  label: Symphony Agent API
  slug: symphony-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/agent-openapi-original.yml
- filename: authenticator-openapi-original.yml
  format: yaml
  label: Symphony Authenticator API
  slug: symphony-authenticator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/authenticator-openapi-original.yml
- filename: login-openapi-original.yml
  format: yaml
  label: Symphony Login API
  slug: symphony-login-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/login-openapi-original.yml
- filename: profile-manager-openapi-original.yml
  format: yaml
  label: Symphony Profile Manager API
  slug: symphony-profile-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/profile-manager-openapi-original.yml
- filename: community-connect-openapi-original.yml
  format: yaml
  label: Symphony Community Connect API
  slug: symphony-community-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/community-connect-openapi-original.yml
class_count: 0
classes: []
context_file: json-ld/symphony-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/json-ld/symphony-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Symphony from Symphony.
layout: jsonld
name: Symphony Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: symphony
  uri: https://symphony.com/vocab#
properties:
- container: ''
  name: Message
  type: reference
- container: ''
  name: Room
  type: reference
- container: ''
  name: Stream
  type: reference
- container: ''
  name: Datafeed
  type: reference
- container: ''
  name: Signal
  type: reference
- container: ''
  name: DlpPolicy
  type: reference
- container: ''
  name: Bot
  type: reference
- container: ''
  name: ExtensionApp
  type: reference
- container: ''
  name: messageId
  type: string
- container: ''
  name: streamId
  type: string
- container: ''
  name: streamType
  type: string
- container: ''
  name: roomName
  type: string
- container: ''
  name: roomDescription
  type: string
- container: ''
  name: messageContent
  type: string
- container: ''
  name: messageTimestamp
  type: integer
- container: ''
  name: userId
  type: integer
- container: ''
  name: displayName
  type: string
- container: ''
  name: sessionToken
  type: string
- container: ''
  name: keyManagerToken
  type: string
- container: ''
  name: datafeedId
  type: string
- container: ''
  name: signalQuery
  type: string
- container: ''
  name: isPublic
  type: boolean
- container: ''
  name: isExternal
  type: boolean
- container: ''
  name: memberCount
  type: integer
- container: ''
  name: creationDate
  type: integer
property_count: 25
provider_name: Symphony
provider_slug: symphony
slug: symphony-context
source_filename: symphony-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"symphony\": \"https://symphony.com/vocab#\",\n\n    \"Message\": {\n      \"@id\": \"symphony:Message\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Message\" }\n    },\n    \"Room\": {\n      \"@id\": \"symphony:Room\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:ConversationThread\" }\n    },\n    \"Stream\": {\n      \"@id\": \"symphony:Stream\",\n      \"@type\": \"@id\"\n    },\n    \"Datafeed\": {\n      \"@id\": \"symphony:Datafeed\",\n      \"@type\": \"@id\",\n      \"skos:definition\": \"Real-time event stream for bot message consumption\"\n    },\n    \"Signal\": {\n      \"@id\": \"symphony:Signal\",\n      \"@type\": \"@id\",\n      \"skos:definition\": \"Keyword-based alert trigger for content monitoring\"\n    },\n    \"DlpPolicy\": {\n      \"@id\": \"\
  symphony:DlpPolicy\",\n      \"@type\": \"@id\",\n      \"skos:definition\": \"Data Loss Prevention policy enforced on messages and streams\"\n    },\n    \"Bot\": {\n      \"@id\": \"symphony:Bot\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" }\n    },\n    \"ExtensionApp\": {\n      \"@id\": \"symphony:ExtensionApp\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" }\n    },\n\n    \"messageId\": { \"@id\": \"symphony:messageId\", \"@type\": \"xsd:string\" },\n    \"streamId\": { \"@id\": \"symphony:streamId\", \"@type\": \"xsd:string\" },\n    \"streamType\": { \"@id\": \"symphony:streamType\", \"@type\": \"xsd:string\" },\n    \"roomName\": { \"@id\": \"symphony:roomName\", \"@type\": \"xsd:string\" },\n    \"roomDescription\": { \"@id\": \"symphony:roomDescription\", \"@type\": \"xsd:string\" },\n    \"messageContent\": { \"@id\": \"symphony:messageContent\", \"@type\": \"xsd:string\"\
  \ },\n    \"messageTimestamp\": { \"@id\": \"symphony:messageTimestamp\", \"@type\": \"xsd:integer\" },\n    \"userId\": { \"@id\": \"symphony:userId\", \"@type\": \"xsd:integer\" },\n    \"displayName\": { \"@id\": \"symphony:displayName\", \"@type\": \"xsd:string\" },\n    \"sessionToken\": { \"@id\": \"symphony:sessionToken\", \"@type\": \"xsd:string\" },\n    \"keyManagerToken\": { \"@id\": \"symphony:keyManagerToken\", \"@type\": \"xsd:string\" },\n    \"datafeedId\": { \"@id\": \"symphony:datafeedId\", \"@type\": \"xsd:string\" },\n    \"signalQuery\": { \"@id\": \"symphony:signalQuery\", \"@type\": \"xsd:string\" },\n    \"isPublic\": { \"@id\": \"symphony:isPublic\", \"@type\": \"xsd:boolean\" },\n    \"isExternal\": { \"@id\": \"symphony:isExternal\", \"@type\": \"xsd:boolean\" },\n    \"memberCount\": { \"@id\": \"symphony:memberCount\", \"@type\": \"xsd:integer\" },\n    \"creationDate\": { \"@id\": \"symphony:creationDate\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/json-ld/symphony-context.jsonld
tags:
- Collaboration
- Communication
- Financial Services
- Messaging
- Secure Communication
- JSON-LD
- Linked Data
- Semantic Web
---
