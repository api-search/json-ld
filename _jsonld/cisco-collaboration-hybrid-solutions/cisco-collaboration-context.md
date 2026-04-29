---
class_count: 0
classes: []
context_file: json-ld/cisco-collaboration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/json-ld/cisco-collaboration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Collaboration from Cisco Collaboration Hybrid Solutions.
layout: jsonld
name: Cisco Collaboration Context
namespaces:
- prefix: webex
  uri: https://webexapis.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: Meeting
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: HybridConnector
  type: ''
property_count: 7
provider_name: Cisco Collaboration Hybrid Solutions
provider_slug: cisco-collaboration-hybrid-solutions
slug: cisco-collaboration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"webex\": \"https://webexapis.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"webex:Organization\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"webex:Person\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"emails\": \"schema:email\",\n        \"orgId\": \"schema:memberOf\",\n        \"roles\": \"webex:roles\",\n        \"licenses\": \"webex:licenses\",\n        \"status\": \"webex:status\"\n      }\n    },\n\n    \"Meeting\": {\n      \"@id\": \"webex:Meeting\",\n      \"@context\": {\n       \
  \ \"id\": \"webex:id\",\n        \"title\": \"schema:name\",\n        \"agenda\": \"schema:description\",\n        \"start\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timezone\": \"schema:timezone\",\n        \"hostUserId\": \"webex:host_user_id\",\n        \"siteUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"webex:Space\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"title\": \"schema:name\",\n        \"type\": \"webex:room_type\",\n        \"isLocked\": \"webex:is_locked\",\n        \"lastActivity\": {\n          \"@id\": \"webex:last_activity\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"webex:Message\",\n      \"@context\": {\n      \
  \  \"id\": \"webex:id\",\n        \"roomId\": \"webex:room_id\",\n        \"personId\": \"webex:person_id\",\n        \"text\": \"schema:text\",\n        \"markdown\": \"webex:markdown\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"webex:Device\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"displayName\": \"schema:name\",\n        \"product\": \"schema:model\",\n        \"type\": \"webex:device_type\",\n        \"ip\": \"webex:ip\",\n        \"mac\": \"webex:mac\",\n        \"connectionStatus\": \"webex:connection_status\",\n        \"softwareVersion\": \"schema:softwareVersion\"\n      }\n    },\n\n    \"HybridConnector\": {\n      \"@id\": \"webex:HybridConnector\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"name\": \"schema:name\",\n        \"type\": \"webex:connector_type\",\n        \"clusterId\": \"webex:cluster_id\"\
  ,\n        \"status\": \"webex:status\",\n        \"version\": \"schema:softwareVersion\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/json-ld/cisco-collaboration-context.jsonld
tags:
- Calling
- Collaboration
- Hybrid Cloud
- Meetings
- Messaging
- Unified Communications
- Webex
- JSON-LD
- Linked Data
- Semantic Web
---
