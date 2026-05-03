---
api_specs:
- filename: opsgenie-alert-openapi.yml
  format: yaml
  label: OpsGenie Alert API
  slug: opsgenie-alert
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-alert-openapi.yml
- filename: opsgenie-incident-openapi.yml
  format: yaml
  label: OpsGenie Incident API
  slug: opsgenie-incident
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-incident-openapi.yml
- filename: opsgenie-user-openapi.yml
  format: yaml
  label: OpsGenie User API
  slug: opsgenie-user
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-user-openapi.yml
- filename: opsgenie-team-openapi.yml
  format: yaml
  label: OpsGenie Team API
  slug: opsgenie-team
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-team-openapi.yml
- filename: opsgenie-schedule-openapi.yml
  format: yaml
  label: OpsGenie Schedule API
  slug: opsgenie-schedule
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-schedule-openapi.yml
- filename: opsgenie-escalation-openapi.yml
  format: yaml
  label: OpsGenie Escalation API
  slug: opsgenie-escalation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-escalation-openapi.yml
- filename: opsgenie-integration-openapi.yml
  format: yaml
  label: OpsGenie Integration API
  slug: opsgenie-integration
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-integration-openapi.yml
- filename: opsgenie-heartbeat-openapi.yml
  format: yaml
  label: OpsGenie Heartbeat API
  slug: opsgenie-heartbeat
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-heartbeat-openapi.yml
- filename: opsgenie-service-openapi.yml
  format: yaml
  label: OpsGenie Service API
  slug: opsgenie-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-service-openapi.yml
- filename: opsgenie-notification-rule-openapi.yml
  format: yaml
  label: OpsGenie Notification Rule API
  slug: opsgenie-notification-rule
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-notification-rule-openapi.yml
- filename: opsgenie-account-openapi.yml
  format: yaml
  label: OpsGenie Account API
  slug: opsgenie-account
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-account-openapi.yml
- filename: opsgenie-maintenance-openapi.yml
  format: yaml
  label: OpsGenie Maintenance API
  slug: opsgenie-maintenance
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-maintenance-openapi.yml
class_count: 0
classes: []
context_file: json-ld/opsgenie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/json-ld/opsgenie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Opsgenie from OpsGenie.
layout: jsonld
name: Opsgenie Context
namespaces:
- prefix: opsgenie
  uri: https://api.opsgenie.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Alert
  type: ''
- container: ''
  name: Incident
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: Escalation
  type: ''
- container: ''
  name: Heartbeat
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Integration
  type: ''
- container: ''
  name: Maintenance
  type: ''
property_count: 10
provider_name: OpsGenie
provider_slug: opsgenie
slug: opsgenie-context
source_filename: opsgenie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"opsgenie\": \"https://api.opsgenie.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Alert\": {\n      \"@id\": \"opsgenie:Alert\",\n      \"@context\": {\n        \"alertId\": \"opsgenie:alertId\",\n        \"tinyId\": \"opsgenie:tinyId\",\n        \"alias\": \"opsgenie:alias\",\n        \"message\": \"schema:description\",\n        \"description\": \"schema:text\",\n        \"status\": \"opsgenie:status\",\n        \"acknowledged\": \"opsgenie:acknowledged\",\n        \"isSeen\": \"opsgenie:isSeen\",\n        \"snoozed\": \"opsgenie:snoozed\",\n        \"snoozedUntil\": {\n          \"@id\": \"opsgenie:snoozedUntil\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": \"schema:keywords\",\n        \"count\": \"opsgenie:count\",\n        \"lastOccurredAt\": {\n          \"@id\": \"opsgenie:lastOccurredAt\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"source\": \"dcterms:source\",\n        \"owner\": \"opsgenie:owner\",\n        \"priority\": \"opsgenie:priority\",\n        \"entity\": \"opsgenie:entity\",\n        \"responders\": {\n          \"@id\": \"opsgenie:responders\",\n          \"@container\": \"@set\"\n        },\n        \"actions\": {\n          \"@id\": \"opsgenie:actions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Incident\": {\n      \"@id\": \"opsgenie:Incident\",\n      \"@context\": {\n        \"incidentId\": \"opsgenie:incidentId\",\n        \"tinyId\": \"opsgenie:tinyId\",\n        \"message\": \"schema:description\",\n        \"description\": \"schema:text\",\n        \"status\": \"opsgenie:status\"\
  ,\n        \"priority\": \"opsgenie:priority\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ownerTeam\": \"opsgenie:ownerTeam\",\n        \"responders\": {\n          \"@id\": \"opsgenie:responders\",\n          \"@container\": \"@set\"\n        },\n        \"impactedServices\": {\n          \"@id\": \"opsgenie:impactedServices\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"opsgenie:User\",\n      \"@context\": {\n        \"userId\": \"opsgenie:userId\",\n        \"username\": \"schema:email\",\n        \"fullName\": \"schema:name\",\n        \"role\": \"opsgenie:role\",\n        \"blocked\": \"opsgenie:blocked\",\n        \"verified\": \"opsgenie:verified\",\n        \"timeZone\": \"opsgenie:timeZone\"\
  ,\n        \"locale\": \"opsgenie:locale\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"opsgenie:Team\",\n      \"@context\": {\n        \"teamId\": \"opsgenie:teamId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"opsgenie:Schedule\",\n      \"@context\": {\n        \"scheduleId\": \"opsgenie:scheduleId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"timezone\": \"opsgenie:timezone\",\n        \"enabled\": \"opsgenie:enabled\",\n        \"ownerTeam\": \"opsgenie:ownerTeam\",\n        \"rotations\": {\n          \"@id\": \"opsgenie:rotations\",\n          \"@container\"\
  : \"@set\"\n        }\n      }\n    },\n\n    \"Escalation\": {\n      \"@id\": \"opsgenie:Escalation\",\n      \"@context\": {\n        \"escalationId\": \"opsgenie:escalationId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"ownerTeam\": \"opsgenie:ownerTeam\",\n        \"rules\": {\n          \"@id\": \"opsgenie:rules\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Heartbeat\": {\n      \"@id\": \"opsgenie:Heartbeat\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"interval\": \"opsgenie:interval\",\n        \"intervalUnit\": \"opsgenie:intervalUnit\",\n        \"enabled\": \"opsgenie:enabled\",\n        \"expired\": \"opsgenie:expired\",\n        \"lastPingTime\": {\n          \"@id\": \"opsgenie:lastPingTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ownerTeam\": \"opsgenie:ownerTeam\"\n      }\n    },\n\n  \
  \  \"Service\": {\n      \"@id\": \"opsgenie:Service\",\n      \"@context\": {\n        \"serviceId\": \"opsgenie:serviceId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"teamId\": \"opsgenie:teamId\",\n        \"visibility\": \"opsgenie:visibility\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"Integration\": {\n      \"@id\": \"opsgenie:Integration\",\n      \"@context\": {\n        \"integrationId\": \"opsgenie:integrationId\",\n        \"name\": \"schema:name\",\n        \"type\": \"opsgenie:integrationType\",\n        \"enabled\": \"opsgenie:enabled\",\n        \"ownerTeam\": \"opsgenie:ownerTeam\",\n        \"isGlobal\": \"opsgenie:isGlobal\",\n        \"apiKey\": \"opsgenie:apiKey\"\n      }\n    },\n\n    \"Maintenance\": {\n      \"@id\": \"opsgenie:Maintenance\",\n      \"@context\": {\n        \"maintenanceId\": \"opsgenie:maintenanceId\",\n        \"status\": \"opsgenie:status\",\n        \"description\"\
  : \"schema:description\",\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"rules\": {\n          \"@id\": \"opsgenie:rules\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/json-ld/opsgenie-context.jsonld
tags:
- Alerts
- Incident Management
- Monitoring
- On-Call
- Operations
- JSON-LD
- Linked Data
- Semantic Web
---
