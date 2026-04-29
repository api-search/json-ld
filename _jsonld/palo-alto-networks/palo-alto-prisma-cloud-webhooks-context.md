---
class_count: 1
classes:
- AlertPayload
context_file: json-ld/palo-alto-prisma-cloud-webhooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-webhooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Cloud Webhooks from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Cloud Webhooks Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountId
  type: string
- container: ''
  name: alertId
  type: string
- container: ''
  name: alertStatus
  type: string
- container: ''
  name: cloudType
  type: string
- container: ''
  name: notificationType
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyName
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: timestamp
  type: dateTime
property_count: 11
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-cloud-webhooks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlertPayload\": \"pan:AlertPayload\",\n    \"accountId\": {\n      \"@id\": \"pan:account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertId\": {\n      \"@id\": \"pan:alert_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertStatus\": {\n      \"@id\": \"pan:alert_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudType\": {\n      \"@id\": \"pan:cloud_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationType\": {\n      \"@id\": \"pan:notification_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n      \"@id\": \"pan:policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n      \"@id\": \"pan:policy_name\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"resourceId\": {\n      \"@id\": \"pan:resource_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-webhooks-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
