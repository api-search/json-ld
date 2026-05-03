---
api_specs:
- filename: webex-messaging-openapi.json
  format: json
  label: Webex Messaging
  slug: messaging
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-messaging-openapi.json
- filename: webex-meeting-openapi.json
  format: json
  label: Webex Meetings
  slug: meetings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-meeting-openapi.json
- filename: webex-admin-openapi.json
  format: json
  label: Webex Admin
  slug: admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-admin-openapi.json
- filename: webex-cloud-calling-openapi.json
  format: json
  label: Webex Cloud Calling
  slug: cloud-calling
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-cloud-calling-openapi.json
- filename: webex-contact-center-openapi.json
  format: json
  label: Webex Contact Center
  slug: contact-center
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-contact-center-openapi.json
- filename: webex-device-openapi.json
  format: json
  label: Webex Devices
  slug: devices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-device-openapi.json
- filename: webex-broadworks-openapi.json
  format: json
  label: Webex Broadworks Calling
  slug: broadworks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-broadworks-openapi.json
- filename: webex-ucm-openapi.json
  format: json
  label: Webex for UCM
  slug: ucm
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-ucm-openapi.json
- filename: webex-wholesale-openapi.json
  format: json
  label: Webex Wholesale
  slug: wholesale
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-wholesale-openapi.json
class_count: 5
classes:
- AcdObjectDevice
- AcdObject
- AdminBatchStartJobObjectLocationCustomizations
- AudioCodecPriorityObjectDevice
- AudioCodecPriorityObject
context_file: json-ld/webex-messaging-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/json-ld/webex-messaging-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Webex Messaging from Webex.
layout: jsonld
name: Webex Messaging Context
namespaces:
- prefix: wx
  uri: https://developer.webex.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: displayCallqueueAgentSoftkeys
  type: string
- container: ''
  name: locationId
  type: string
- container: ''
  name: locationCustomizationsEnabled
  type: boolean
- container: ''
  name: customizations
  type: string
- container: ''
  name: selection
  type: string
- container: ''
  name: primary
  type: string
- container: ''
  name: secondary
  type: string
- container: ''
  name: tertiary
  type: string
property_count: 9
provider_name: Webex
provider_slug: webex
slug: webex-messaging-context
source_filename: webex-messaging-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wx\": \"https://developer.webex.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcdObjectDevice\": \"wx:AcdObjectDevice\",\n    \"enabled\": {\n      \"@id\": \"wx:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"displayCallqueueAgentSoftkeys\": {\n      \"@id\": \"wx:displayCallqueueAgentSoftkeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcdObject\": \"wx:AcdObject\",\n    \"AdminBatchStartJobObjectLocationCustomizations\": \"wx:AdminBatchStartJobObjectLocationCustomizations\",\n    \"locationId\": {\n      \"@id\": \"wx:locationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationCustomizationsEnabled\": {\n      \"@id\": \"wx:locationCustomizationsEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"customizations\": {\n      \"@id\": \"wx:customizations\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"AudioCodecPriorityObjectDevice\": \"wx:AudioCodecPriorityObjectDevice\",\n    \"selection\": {\n      \"@id\": \"wx:selection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primary\": {\n      \"@id\": \"wx:primary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secondary\": {\n      \"@id\": \"wx:secondary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tertiary\": {\n      \"@id\": \"wx:tertiary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AudioCodecPriorityObject\": \"wx:AudioCodecPriorityObject\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/json-ld/webex-messaging-context.jsonld
tags:
- Calling
- Collaboration
- Communication
- Enterprise
- Messaging
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
