---
api_specs:
- filename: client-server
  format: yaml
  label: Synapse Client-Server API
  slug: synapse-client-server-api
  spec_type: OpenAPI
  url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server
- filename: server-server
  format: yaml
  label: Synapse Server-Server API
  slug: synapse-server-server-api
  spec_type: OpenAPI
  url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server
- filename: synapse-admin-api-openapi.yml
  format: yaml
  label: Synapse Admin API
  slug: synapse-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/openapi/synapse-admin-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/synapse-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/json-ld/synapse-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Synapse from Synapse.
layout: jsonld
name: Synapse Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: matrix
  uri: https://matrix.org/vocab#
- prefix: synapse
  uri: https://github.com/element-hq/synapse/vocab#
properties:
- container: ''
  name: HomeServer
  type: reference
- container: ''
  name: MatrixUser
  type: reference
- container: ''
  name: MatrixRoom
  type: reference
- container: ''
  name: MatrixEvent
  type: reference
- container: ''
  name: MatrixMessage
  type: reference
- container: ''
  name: MatrixSpace
  type: reference
- container: ''
  name: ApplicationService
  type: reference
- container: ''
  name: RegistrationToken
  type: reference
- container: ''
  name: AdminApi
  type: reference
- container: ''
  name: userId
  type: string
- container: ''
  name: roomId
  type: string
- container: ''
  name: eventId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: avatarUrl
  type: reference
- container: ''
  name: isAdmin
  type: boolean
- container: ''
  name: isDeactivated
  type: boolean
- container: ''
  name: isGuest
  type: boolean
- container: ''
  name: isFederatable
  type: boolean
- container: ''
  name: isPublic
  type: boolean
- container: ''
  name: isEncrypted
  type: boolean
- container: ''
  name: joinRules
  type: string
- container: ''
  name: historyVisibility
  type: string
- container: ''
  name: memberCount
  type: integer
- container: ''
  name: localMemberCount
  type: integer
- container: ''
  name: roomVersion
  type: string
- container: ''
  name: serverVersion
  type: string
- container: ''
  name: serverName
  type: string
- container: ''
  name: creationTimestamp
  type: integer
- container: ''
  name: accessToken
  type: string
- container: ''
  name: usesAllowed
  type: integer
- container: ''
  name: expiryTime
  type: integer
property_count: 31
provider_name: Synapse
provider_slug: synapse
slug: synapse-context
source_filename: synapse-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"matrix\": \"https://matrix.org/vocab#\",\n    \"synapse\": \"https://github.com/element-hq/synapse/vocab#\",\n\n    \"HomeServer\": {\n      \"@id\": \"matrix:HomeServer\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" }\n    },\n    \"MatrixUser\": {\n      \"@id\": \"matrix:MatrixUser\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Person\" }\n    },\n    \"MatrixRoom\": {\n      \"@id\": \"matrix:MatrixRoom\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:ConversationThread\" }\n    },\n    \"MatrixEvent\": {\n      \"@id\": \"matrix:MatrixEvent\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Event\" }\n    },\n    \"MatrixMessage\": {\n      \"@id\": \"matrix:MatrixMessage\",\n      \"@type\"\
  : \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Message\" }\n    },\n    \"MatrixSpace\": {\n      \"@id\": \"matrix:MatrixSpace\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"matrix:MatrixRoom\" }\n    },\n    \"ApplicationService\": {\n      \"@id\": \"matrix:ApplicationService\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" }\n    },\n    \"RegistrationToken\": {\n      \"@id\": \"synapse:RegistrationToken\",\n      \"@type\": \"@id\"\n    },\n    \"AdminApi\": {\n      \"@id\": \"synapse:AdminApi\",\n      \"@type\": \"@id\"\n    },\n\n    \"userId\": { \"@id\": \"matrix:userId\", \"@type\": \"xsd:string\" },\n    \"roomId\": { \"@id\": \"matrix:roomId\", \"@type\": \"xsd:string\" },\n    \"eventId\": { \"@id\": \"matrix:eventId\", \"@type\": \"xsd:string\" },\n    \"displayName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"avatarUrl\": { \"@id\": \"schema:image\", \"@type\"\
  : \"@id\" },\n    \"isAdmin\": { \"@id\": \"synapse:isAdmin\", \"@type\": \"xsd:boolean\" },\n    \"isDeactivated\": { \"@id\": \"synapse:isDeactivated\", \"@type\": \"xsd:boolean\" },\n    \"isGuest\": { \"@id\": \"synapse:isGuest\", \"@type\": \"xsd:boolean\" },\n    \"isFederatable\": { \"@id\": \"matrix:isFederatable\", \"@type\": \"xsd:boolean\" },\n    \"isPublic\": { \"@id\": \"matrix:isPublic\", \"@type\": \"xsd:boolean\" },\n    \"isEncrypted\": { \"@id\": \"matrix:isEncrypted\", \"@type\": \"xsd:boolean\" },\n    \"joinRules\": { \"@id\": \"matrix:joinRules\", \"@type\": \"xsd:string\" },\n    \"historyVisibility\": { \"@id\": \"matrix:historyVisibility\", \"@type\": \"xsd:string\" },\n    \"memberCount\": { \"@id\": \"matrix:memberCount\", \"@type\": \"xsd:integer\" },\n    \"localMemberCount\": { \"@id\": \"synapse:localMemberCount\", \"@type\": \"xsd:integer\" },\n    \"roomVersion\": { \"@id\": \"matrix:roomVersion\", \"@type\": \"xsd:string\" },\n    \"serverVersion\": {\
  \ \"@id\": \"synapse:serverVersion\", \"@type\": \"xsd:string\" },\n    \"serverName\": { \"@id\": \"matrix:serverName\", \"@type\": \"xsd:string\" },\n    \"creationTimestamp\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" },\n    \"accessToken\": { \"@id\": \"synapse:accessToken\", \"@type\": \"xsd:string\" },\n    \"usesAllowed\": { \"@id\": \"synapse:usesAllowed\", \"@type\": \"xsd:integer\" },\n    \"expiryTime\": { \"@id\": \"synapse:expiryTime\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/json-ld/synapse-context.jsonld
tags:
- Chat
- Collaboration
- Decentralized
- Federation
- Matrix
- Messaging
- Open-Source
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
