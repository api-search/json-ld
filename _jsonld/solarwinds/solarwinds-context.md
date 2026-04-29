---
api_specs:
- filename: solarwinds-orion-openapi.yml
  format: yaml
  label: SolarWinds Orion API
  slug: solarwinds-orion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-orion-openapi.yml
- filename: solarwinds-service-desk-openapi.yml
  format: yaml
  label: SolarWinds Service Desk API
  slug: solarwinds-service-desk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-service-desk-openapi.yml
- filename: solarwinds-pingdom-openapi.yml
  format: yaml
  label: SolarWinds Pingdom API
  slug: solarwinds-pingdom-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-pingdom-openapi.yml
- filename: solarwinds-loggly-openapi.yml
  format: yaml
  label: SolarWinds Loggly API
  slug: solarwinds-loggly-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-loggly-openapi.yml
- filename: solarwinds-papertrail-openapi.yml
  format: yaml
  label: SolarWinds Papertrail API
  slug: solarwinds-papertrail-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-papertrail-openapi.yml
class_count: 0
classes: []
context_file: json-ld/solarwinds-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/json-ld/solarwinds-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solarwinds from SolarWinds.
layout: jsonld
name: Solarwinds Context
namespaces:
- prefix: sw
  uri: https://solarwinds.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: MonitoredNode
  type: ''
- container: ''
  name: Alert
  type: ''
- container: ''
  name: Incident
  type: ''
- container: ''
  name: UptimeCheck
  type: ''
- container: ''
  name: LogEvent
  type: ''
property_count: 5
provider_name: SolarWinds
provider_slug: solarwinds
slug: solarwinds-context
source_filename: solarwinds-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sw\": \"https://solarwinds.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"MonitoredNode\": {\n      \"@id\": \"sw:MonitoredNode\",\n      \"@context\": {\n        \"nodeId\": \"sw:nodeId\",\n        \"caption\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ipAddress\": {\n          \"@id\": \"sw:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"sw:status\",\n        \"statusDescription\": \"sw:statusDescription\",\n        \"machineType\": \"sw:machineType\",\n        \"vendor\": {\n          \"@id\": \"schema:manufacturer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contact\": {\n        \
  \  \"@id\": \"schema:contactPoint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cpuLoad\": \"sw:cpuLoad\",\n        \"memoryUsed\": \"sw:memoryUsed\",\n        \"responseTime\": \"sw:responseTime\",\n        \"packetLoss\": \"sw:packetLoss\",\n        \"lastBoot\": {\n          \"@id\": \"sw:lastBoot\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"uri\": {\n          \"@id\": \"sw:entityUri\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"sw:Alert\",\n      \"@context\": {\n        \"alertId\": \"sw:alertId\",\n        \"alertName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": \"sw:severity\",\n        \"triggeredAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resetAt\": {\n          \"@id\": \"sw:resetAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"acknowledged\"\
  : \"sw:acknowledged\",\n        \"message\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entityType\": \"sw:entityType\",\n        \"entityUri\": {\n          \"@id\": \"sw:entityUri\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Incident\": {\n      \"@id\": \"sw:Incident\",\n      \"@context\": {\n        \"incidentId\": \"sw:incidentId\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"sw:state\",\n        \"priority\": \"sw:priority\",\n        \"assignee\": {\n          \"@id\": \"sw:assignee\",\n          \"@type\": \"@id\"\n        },\n        \"requester\": {\n          \"@id\": \"sw:requester\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"UptimeCheck\": {\n      \"@id\": \"sw:UptimeCheck\",\n      \"@context\": {\n        \"checkId\": \"sw:checkId\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hostname\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"checkType\": \"sw:checkType\",\n        \"status\": \"sw:status\",\n        \"resolution\": \"sw:resolution\",\n        \"lastResponseTime\": \"sw:lastResponseTime\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"LogEvent\": {\n      \"@id\": \"sw:LogEvent\"\
  ,\n      \"@context\": {\n        \"eventId\": \"sw:eventId\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"message\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hostname\": \"sw:hostname\",\n        \"program\": \"sw:program\",\n        \"severity\": \"sw:severity\",\n        \"facility\": \"sw:facility\",\n        \"sourceIp\": \"sw:sourceIp\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/json-ld/solarwinds-context.jsonld
tags:
- Application Monitoring
- Database Monitoring
- Infrastructure
- IP Address Management
- IT Management
- ITSM
- Log Management
- Network Monitoring
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
