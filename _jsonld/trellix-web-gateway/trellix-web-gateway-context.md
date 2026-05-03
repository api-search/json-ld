---
api_specs:
- filename: openapi.json
  format: json
  label: Trellix Web Gateway REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.trellix.com/api/web-gateway/openapi.json
- filename: trellix-web-gateway-reporting-openapi.yml
  format: yaml
  label: Trellix Web Gateway Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/openapi/trellix-web-gateway-reporting-openapi.yml
- filename: trellix-web-gateway-policy-openapi.yml
  format: yaml
  label: Trellix Web Gateway Policy API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/openapi/trellix-web-gateway-policy-openapi.yml
class_count: 0
classes: []
context_file: json-ld/trellix-web-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/json-ld/trellix-web-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trellix Web Gateway from Trellix Web Gateway.
layout: jsonld
name: Trellix Web Gateway Context
namespaces:
- prefix: trellix
  uri: https://docs.trellix.com/schemas/web-gateway/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Appliance
  type: ''
- container: ''
  name: RuleSet
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: SecurityEvent
  type: ''
- container: ''
  name: TrafficLogEntry
  type: ''
- container: ''
  name: UrlCategory
  type: ''
- container: ''
  name: CustomList
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: SslCertificate
  type: ''
property_count: 9
provider_name: Trellix Web Gateway
provider_slug: trellix-web-gateway
slug: trellix-web-gateway-context
source_filename: trellix-web-gateway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"trellix\": \"https://docs.trellix.com/schemas/web-gateway/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Appliance\": {\n      \"@id\": \"trellix:Appliance\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"hostname\": \"trellix:hostname\",\n        \"version\": \"schema:softwareVersion\",\n        \"role\": \"trellix:applianceRole\",\n        \"status\": \"trellix:operationalStatus\",\n        \"lastSync\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RuleSet\": {\n      \"@id\": \"trellix:RuleSet\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"trellix:ruleSetType\",\n        \"enabled\": {\n          \"@id\": \"trellix:enabled\",\n  \
  \        \"@type\": \"xsd:boolean\"\n        },\n        \"order\": {\n          \"@id\": \"trellix:processingOrder\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ruleCount\": {\n          \"@id\": \"trellix:ruleCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Rule\": {\n      \"@id\": \"trellix:Rule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": {\n          \"@id\": \"trellix:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"condition\": \"trellix:ruleCondition\",\n        \"action\": \"trellix:ruleAction\"\n      }\n    },\n\n    \"SecurityEvent\": {\n      \"@id\": \"trellix:SecurityEvent\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"severity\": \"trellix:severity\",\n        \"eventType\": \"trellix:eventType\",\n \
  \       \"sourceIp\": \"trellix:sourceIp\",\n        \"user\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"threatName\": \"trellix:threatName\",\n        \"action\": \"trellix:actionTaken\",\n        \"ruleName\": \"trellix:ruleName\"\n      }\n    },\n\n    \"TrafficLogEntry\": {\n      \"@id\": \"trellix:TrafficLogEntry\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sourceIp\": \"trellix:sourceIp\",\n        \"user\": \"schema:name\",\n        \"method\": \"trellix:httpMethod\",\n        \"url\": \"schema:url\",\n        \"statusCode\": {\n          \"@id\": \"trellix:httpStatusCode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"action\": \"trellix:actionTaken\",\n        \"category\": \"trellix:urlCategory\",\n        \"bytesIn\": {\n          \"@id\": \"trellix:bytesIn\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bytesOut\"\
  : {\n          \"@id\": \"trellix:bytesOut\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"duration\": {\n          \"@id\": \"trellix:durationMs\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"UrlCategory\": {\n      \"@id\": \"trellix:UrlCategory\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"parentCategory\": \"trellix:parentCategory\"\n      }\n    },\n\n    \"CustomList\": {\n      \"@id\": \"trellix:CustomList\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"trellix:listType\",\n        \"entryCount\": {\n          \"@id\": \"trellix:entryCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"trellix:Report\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"trellix:reportType\",\n       \
  \ \"status\": \"trellix:reportStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SslCertificate\": {\n      \"@id\": \"trellix:SslCertificate\",\n      \"@context\": {\n        \"subject\": \"trellix:certificateSubject\",\n        \"issuer\": \"trellix:certificateIssuer\",\n        \"validFrom\": {\n          \"@id\": \"trellix:validFrom\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"validTo\": {\n          \"@id\": \"trellix:validTo\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"serialNumber\": \"trellix:serialNumber\",\n        \"fingerprint\": \"trellix:fingerprint\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/json-ld/trellix-web-gateway-context.jsonld
tags:
- Cybersecurity
- Data Loss Prevention
- Enterprise Security
- Malware Protection
- Network Security
- Threat Protection
- URL Filtering
- Web Gateway
- JSON-LD
- Linked Data
- Semantic Web
---
