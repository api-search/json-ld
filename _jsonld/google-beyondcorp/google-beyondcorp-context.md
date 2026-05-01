---
api_specs:
- filename: beyondcorp-api-openapi.yml
  format: yaml
  label: BeyondCorp API
  slug: beyondcorp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-beyondcorp/refs/heads/main/openapi/beyondcorp-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-beyondcorp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-beyondcorp/refs/heads/main/json-ld/google-beyondcorp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Beyondcorp from Google BeyondCorp.
layout: jsonld
name: Google Beyondcorp Context
namespaces:
- prefix: bc
  uri: https://cloud.google.com/beyondcorp/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: AppConnector
  type: ''
- container: ''
  name: AppConnection
  type: ''
- container: ''
  name: SecurityGateway
  type: ''
- container: ''
  name: ApplicationEndpoint
  type: ''
property_count: 4
provider_name: Google BeyondCorp
provider_slug: google-beyondcorp
slug: google-beyondcorp-context
source_filename: google-beyondcorp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bc\": \"https://cloud.google.com/beyondcorp/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"AppConnector\": {\n      \"@id\": \"bc:AppConnector\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"uid\": \"bc:uid\",\n        \"state\": \"bc:connectorState\",\n        \"principalInfo\": \"bc:principalInfo\",\n        \"resourceInfo\": \"bc:resourceInfo\",\n        \"labels\": \"bc:labels\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AppConnection\": {\n      \"@id\": \"bc:AppConnection\",\n      \"@context\": {\n        \"name\"\
  : \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"uid\": \"bc:uid\",\n        \"type\": \"bc:connectionType\",\n        \"state\": \"bc:connectionState\",\n        \"applicationEndpoint\": \"bc:applicationEndpoint\",\n        \"connectors\": {\n          \"@id\": \"bc:connectors\",\n          \"@type\": \"@id\"\n        },\n        \"gateway\": \"bc:gateway\",\n        \"labels\": \"bc:labels\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SecurityGateway\": {\n      \"@id\": \"bc:SecurityGateway\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"state\": \"bc:gatewayState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"\
  xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApplicationEndpoint\": {\n      \"@id\": \"bc:ApplicationEndpoint\",\n      \"@context\": {\n        \"host\": \"schema:hostname\",\n        \"port\": \"bc:port\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-beyondcorp/refs/heads/main/json-ld/google-beyondcorp-context.jsonld
tags:
- Access Control
- Enterprise Security
- Identity
- Security
- VPN Alternative
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
