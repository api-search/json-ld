---
api_specs:
- filename: atandt-wireless-apis.yaml
  format: yaml
  label: AT&T Wireless APIs
  slug: att-wireless-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-wireless-apis.yaml
- filename: atandt-network-apis.yaml
  format: yaml
  label: AT&T 5G Network APIs
  slug: att-network-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-network-apis.yaml
- filename: atandt-enterprise-connectivity-apis.yaml
  format: yaml
  label: AT&T Enterprise Connectivity APIs
  slug: att-enterprise-connectivity-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-enterprise-connectivity-apis.yaml
class_count: 0
classes: []
context_file: json-ld/wireless-apis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/json-ld/wireless-apis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wireless Apis from AT&T.
layout: jsonld
name: Wireless Apis Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: grant_type
  uri: https://api.att.com/vocab/grant_type
- prefix: client_id
  uri: https://api.att.com/vocab/client_id
- prefix: client_secret
  uri: https://api.att.com/vocab/client_secret
- prefix: scope
  uri: https://api.att.com/vocab/scope
- prefix: code
  uri: https://api.att.com/vocab/code
- prefix: refresh_token
  uri: https://api.att.com/vocab/refresh_token
- prefix: access_token
  uri: https://api.att.com/vocab/access_token
- prefix: token_type
  uri: https://api.att.com/vocab/token_type
- prefix: outboundSMSRequest
  uri: https://api.att.com/vocab/outboundSMSRequest
- prefix: outboundSMSResponse
  uri: https://api.att.com/vocab/outboundSMSResponse
- prefix: address
  uri: https://api.att.com/vocab/address
- prefix: deliveryStatus
  uri: https://api.att.com/vocab/deliveryStatus
- prefix: messageId
  uri: https://api.att.com/vocab/messageId
- prefix: message
  uri: https://api.att.com/vocab/message
- prefix: senderAddress
  uri: https://api.att.com/vocab/senderAddress
- prefix: destinationAddress
  uri: https://api.att.com/vocab/destinationAddress
properties:
- container: ''
  name: expires_in
  type: integer
- container: ''
  name: dateTime
  type: dateTime
property_count: 2
provider_name: AT&T
provider_slug: atandt
slug: wireless-apis-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://api.att.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"grant_type\": \"https://api.att.com/vocab/grant_type\",\n    \"client_id\": \"https://api.att.com/vocab/client_id\",\n    \"client_secret\": \"https://api.att.com/vocab/client_secret\",\n    \"scope\": \"https://api.att.com/vocab/scope\",\n    \"code\": \"https://api.att.com/vocab/code\",\n    \"refresh_token\": \"https://api.att.com/vocab/refresh_token\",\n    \"access_token\": \"https://api.att.com/vocab/access_token\",\n    \"token_type\": \"https://api.att.com/vocab/token_type\",\n    \"expires_in\": {\n      \"@id\": \"https://api.att.com/vocab/expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"outboundSMSRequest\": \"https://api.att.com/vocab/outboundSMSRequest\",\n    \"outboundSMSResponse\": \"https://api.att.com/vocab/outboundSMSResponse\",\n    \"address\": \"https://api.att.com/vocab/address\",\n   \
  \ \"deliveryStatus\": \"https://api.att.com/vocab/deliveryStatus\",\n    \"messageId\": \"https://api.att.com/vocab/messageId\",\n    \"message\": \"https://api.att.com/vocab/message\",\n    \"senderAddress\": \"https://api.att.com/vocab/senderAddress\",\n    \"destinationAddress\": \"https://api.att.com/vocab/destinationAddress\",\n    \"dateTime\": {\n      \"@id\": \"https://api.att.com/vocab/dateTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/json-ld/wireless-apis-context.jsonld
tags:
- Telecommunications
- Fortune 100
- Wireless
- Wireline
- Broadband
- Enterprise
- 5G
- Network
- JSON-LD
- Linked Data
- Semantic Web
---
