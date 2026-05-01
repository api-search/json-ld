---
api_specs:
- filename: better-stack-openapi.yml
  format: yaml
  label: Better Stack API
  slug: better-stack
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/openapi/better-stack-openapi.yml
class_count: 43
classes:
- AvailabilityResponse
- HeartbeatAttributes
- HeartbeatCreateRequest
- HeartbeatListResponse
- HeartbeatObject
- HeartbeatSingleResponse
- HeartbeatUpdateRequest
- IncidentAttributes
- IncidentCreateRequest
- IncidentListResponse
- IncidentObject
- IncidentSingleResponse
- MonitorAttributes
- MonitorCreateRequest
- MonitorListResponse
- MonitorObject
- MonitorSingleResponse
- MonitorUpdateRequest
- Pagination
- PolicyAttributes
- PolicyCreateRequest
- PolicyListResponse
- PolicyObject
- PolicySingleResponse
- PolicyStep
- PolicyUpdateRequest
- ResponseTimesResponse
- StatusPageAttributes
- StatusPageCreateRequest
- StatusPageListResponse
- StatusPageObject
- StatusPageSingleResponse
- StatusPageUpdateRequest
- TeamMemberAttributes
- TeamMemberInviteRequest
- TeamMemberListResponse
- TeamMemberObject
- TeamMemberSingleResponse
- name
- url
- email
- createdAt
- updatedAt
context_file: json-ld/better-stack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/json-ld/better-stack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Better Stack from Better Stack.
layout: jsonld
name: Better Stack Context
namespaces:
- prefix: bs
  uri: https://betterstack.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: data
  type: reference
- container: ''
  name: availability
  type: decimal
- container: ''
  name: downtimeDuration
  type: integer
- container: ''
  name: numberOfIncidents
  type: integer
- container: ''
  name: longestIncidentDuration
  type: integer
- container: ''
  name: averageIncidentDuration
  type: integer
- container: ''
  name: period
  type: integer
- container: ''
  name: grace
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: call
  type: boolean
- container: ''
  name: sms
  type: boolean
- container: ''
  name: push
  type: boolean
- container: ''
  name: pausedAt
  type: dateTime
- container: ''
  name: pagination
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: httpMethod
  type: string
- container: ''
  name: cause
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: acknowledgedAt
  type: dateTime
- container: ''
  name: resolvedAt
  type: dateTime
- container: ''
  name: teamName
  type: string
- container: set
  name: regions
  type: string
- container: ''
  name: pronounceableName
  type: string
- container: ''
  name: monitorType
  type: string
- container: ''
  name: monitorGroupId
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: checkFrequency
  type: integer
- container: ''
  name: verifySsl
  type: boolean
- container: ''
  name: sslExpiration
  type: integer
- container: ''
  name: first
  type: reference
- container: ''
  name: last
  type: reference
- container: ''
  name: prev
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: repeatCount
  type: integer
- container: ''
  name: repeatDelay
  type: integer
- container: ''
  name: incidentToken
  type: string
- container: ''
  name: policyGroupId
  type: string
- container: set
  name: steps
  type: string
- container: ''
  name: companyName
  type: string
- container: ''
  name: companyWebsite
  type: reference
- container: ''
  name: subdomain
  type: string
- container: ''
  name: customDomain
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: theme
  type: string
- container: ''
  name: aggregateState
  type: string
- container: ''
  name: role
  type: string
property_count: 48
provider_name: Better Stack
provider_slug: better-stack
slug: better-stack-context
source_filename: better-stack-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bs\": \"https://betterstack.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AvailabilityResponse\": \"bs:AvailabilityResponse\",\n    \"HeartbeatAttributes\": \"bs:HeartbeatAttributes\",\n    \"HeartbeatCreateRequest\": \"bs:HeartbeatCreateRequest\",\n    \"HeartbeatListResponse\": \"bs:HeartbeatListResponse\",\n    \"HeartbeatObject\": \"bs:HeartbeatObject\",\n    \"HeartbeatSingleResponse\": \"bs:HeartbeatSingleResponse\",\n    \"HeartbeatUpdateRequest\": \"bs:HeartbeatUpdateRequest\",\n    \"IncidentAttributes\": \"bs:IncidentAttributes\",\n    \"IncidentCreateRequest\": \"bs:IncidentCreateRequest\",\n    \"IncidentListResponse\": \"bs:IncidentListResponse\",\n    \"IncidentObject\": \"bs:IncidentObject\",\n    \"IncidentSingleResponse\": \"bs:IncidentSingleResponse\",\n    \"MonitorAttributes\": \"bs:MonitorAttributes\"\
  ,\n    \"MonitorCreateRequest\": \"bs:MonitorCreateRequest\",\n    \"MonitorListResponse\": \"bs:MonitorListResponse\",\n    \"MonitorObject\": \"bs:MonitorObject\",\n    \"MonitorSingleResponse\": \"bs:MonitorSingleResponse\",\n    \"MonitorUpdateRequest\": \"bs:MonitorUpdateRequest\",\n    \"Pagination\": \"bs:Pagination\",\n    \"PolicyAttributes\": \"bs:PolicyAttributes\",\n    \"PolicyCreateRequest\": \"bs:PolicyCreateRequest\",\n    \"PolicyListResponse\": \"bs:PolicyListResponse\",\n    \"PolicyObject\": \"bs:PolicyObject\",\n    \"PolicySingleResponse\": \"bs:PolicySingleResponse\",\n    \"PolicyStep\": \"bs:PolicyStep\",\n    \"PolicyUpdateRequest\": \"bs:PolicyUpdateRequest\",\n    \"ResponseTimesResponse\": \"bs:ResponseTimesResponse\",\n    \"StatusPageAttributes\": \"bs:StatusPageAttributes\",\n    \"StatusPageCreateRequest\": \"bs:StatusPageCreateRequest\",\n    \"StatusPageListResponse\": \"bs:StatusPageListResponse\",\n    \"StatusPageObject\": \"bs:StatusPageObject\",\n\
  \    \"StatusPageSingleResponse\": \"bs:StatusPageSingleResponse\",\n    \"StatusPageUpdateRequest\": \"bs:StatusPageUpdateRequest\",\n    \"TeamMemberAttributes\": \"bs:TeamMemberAttributes\",\n    \"TeamMemberInviteRequest\": \"bs:TeamMemberInviteRequest\",\n    \"TeamMemberListResponse\": \"bs:TeamMemberListResponse\",\n    \"TeamMemberObject\": \"bs:TeamMemberObject\",\n    \"TeamMemberSingleResponse\": \"bs:TeamMemberSingleResponse\",\n    \"data\": {\n      \"@id\": \"bs:data\",\n      \"@type\": \"@id\"\n    },\n    \"availability\": {\n      \"@id\": \"bs:availability\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"downtimeDuration\": {\n      \"@id\": \"bs:downtime_duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberOfIncidents\": {\n      \"@id\": \"bs:number_of_incidents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"longestIncidentDuration\": {\n      \"@id\": \"bs:longest_incident_duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"averageIncidentDuration\"\
  : {\n      \"@id\": \"bs:average_incident_duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"url\": \"schema:url\",\n    \"period\": {\n      \"@id\": \"bs:period\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"grace\": {\n      \"@id\": \"bs:grace\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"bs:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"call\": {\n      \"@id\": \"bs:call\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sms\": {\n      \"@id\": \"bs:sms\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"email\": \"schema:email\",\n    \"push\": {\n      \"@id\": \"bs:push\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"pausedAt\": {\n      \"@id\": \"bs:paused_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"pagination\": {\n      \"@id\": \"bs:pagination\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"id\": {\n      \"@id\": \"bs:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bs:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"bs:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpMethod\": {\n      \"@id\": \"bs:http_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cause\": {\n      \"@id\": \"bs:cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"bs:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledgedAt\": {\n      \"@id\": \"bs:acknowledged_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resolvedAt\": {\n      \"@id\": \"bs:resolved_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"teamName\": {\n      \"@id\": \"bs:team_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regions\": {\n      \"@id\": \"bs:regions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"pronounceableName\": {\n      \"@id\": \"bs:pronounceable_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitorType\": {\n      \"@id\": \"bs:monitor_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitorGroupId\": {\n      \"@id\": \"bs:monitor_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n      \"@id\": \"bs:policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkFrequency\": {\n      \"@id\": \"bs:check_frequency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"verifySsl\": {\n      \"@id\": \"bs:verify_ssl\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sslExpiration\": {\n      \"@id\": \"bs:ssl_expiration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"first\": {\n      \"@id\": \"bs:first\",\n      \"@type\": \"@id\"\n    },\n    \"last\": {\n      \"@id\": \"bs:last\",\n      \"@type\": \"@id\"\n    },\n    \"prev\": {\n      \"@id\": \"bs:prev\",\n      \"@type\": \"@id\"\n    },\n    \"next\": {\n   \
  \   \"@id\": \"bs:next\",\n      \"@type\": \"@id\"\n    },\n    \"repeatCount\": {\n      \"@id\": \"bs:repeat_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"repeatDelay\": {\n      \"@id\": \"bs:repeat_delay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"incidentToken\": {\n      \"@id\": \"bs:incident_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyGroupId\": {\n      \"@id\": \"bs:policy_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"steps\": {\n      \"@id\": \"bs:steps\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyName\": {\n      \"@id\": \"bs:company_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyWebsite\": {\n      \"@id\": \"bs:company_website\",\n      \"@type\": \"@id\"\n    },\n    \"subdomain\": {\n      \"@id\": \"bs:subdomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customDomain\": {\n      \"@id\": \"bs:custom_domain\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"timezone\": {\n      \"@id\": \"bs:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"theme\": {\n      \"@id\": \"bs:theme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregateState\": {\n      \"@id\": \"bs:aggregate_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"bs:role\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/json-ld/better-stack-context.jsonld
tags:
- Incidents
- Logs
- Monitoring
- Platform
- Status
- Uptime
- Observability
- On-Call
- Heartbeats
- JSON-LD
- Linked Data
- Semantic Web
---
