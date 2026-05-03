---
api_specs:
- filename: saas-alerts-openapi.yml
  format: yaml
  label: SaaS Alerts API
  slug: saas-alerts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/openapi/saas-alerts-openapi.yml
class_count: 4
classes:
- eventId
- alertStatus
- customerName
- details
context_file: json-ld/saas-alerts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/json-ld/saas-alerts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Saas Alerts from SaaS Alerts.
layout: jsonld
name: Saas Alerts Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: saasalerts
  uri: https://api.saasalerts.com/terms/
properties:
- container: ''
  name: SecurityEvent
  type: reference
- container: ''
  name: SecurityAlert
  type: reference
- container: ''
  name: eventType
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: application
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: sourceIp
  type: string
- container: ''
  name: resolved
  type: boolean
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: resolvedAt
  type: dateTime
- container: ''
  name: relatedEvents
  type: reference
property_count: 12
provider_name: SaaS Alerts
provider_slug: saas-alerts
slug: saas-alerts-context
source_filename: saas-alerts-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"saasalerts\": \"https://api.saasalerts.com/terms/\",\n\n    \"SecurityEvent\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"SecurityAlert\": {\n      \"@id\": \"schema:Action\",\n      \"@type\": \"@id\"\n    },\n    \"eventId\": \"dcterms:identifier\",\n    \"eventType\": {\n      \"@id\": \"schema:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertStatus\": \"schema:status\",\n    \"timestamp\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"customerName\": \"schema:name\",\n    \"userId\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceIp\": {\n      \"@id\": \"schema:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolved\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resolvedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"details\": \"schema:additionalProperty\",\n    \"relatedEvents\": {\n      \"@id\": \"schema:relatedLink\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/json-ld/saas-alerts-context.jsonld
tags:
- MSP
- SaaS Security
- Security Monitoring
- Threat Detection
- Microsoft 365
- Google Workspace
- MSSP
- JSON-LD
- Linked Data
- Semantic Web
---
