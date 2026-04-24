---
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
