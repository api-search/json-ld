---
api_specs:
- filename: gong-calls-openapi.yml
  format: yaml
  label: Gong Calls API
  slug: gong-calls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-calls-openapi.yml
- filename: gong-users-openapi.yml
  format: yaml
  label: Gong Users API
  slug: gong-users-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-users-openapi.yml
- filename: gong-stats-openapi.yml
  format: yaml
  label: Gong Stats API
  slug: gong-stats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-stats-openapi.yml
- filename: gong-crm-openapi.yml
  format: yaml
  label: Gong CRM API
  slug: gong-crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-crm-openapi.yml
- filename: gong-engage-openapi.yml
  format: yaml
  label: Gong Engage API
  slug: gong-engage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-engage-openapi.yml
- filename: gong-settings-openapi.yml
  format: yaml
  label: Gong Settings API
  slug: gong-settings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-settings-openapi.yml
- filename: gong-library-openapi.yml
  format: yaml
  label: Gong Library API
  slug: gong-library-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-library-openapi.yml
- filename: gong-permissions-openapi.yml
  format: yaml
  label: Gong Permissions API
  slug: gong-permissions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-permissions-openapi.yml
- filename: gong-data-privacy-openapi.yml
  format: yaml
  label: Gong Data Privacy API
  slug: gong-data-privacy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-data-privacy-openapi.yml
- filename: gong-auditing-openapi.yml
  format: yaml
  label: Gong Auditing API
  slug: gong-auditing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-auditing-openapi.yml
- filename: gong-meetings-openapi.yml
  format: yaml
  label: Gong Meetings API
  slug: gong-meetings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-meetings-openapi.yml
- filename: gong-engagement-openapi.yml
  format: yaml
  label: Gong Engagement API
  slug: gong-engagement-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/openapi/gong-engagement-openapi.yml
class_count: 0
classes: []
context_file: json-ld/gong-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/json-ld/gong-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gong from Gong.
layout: jsonld
name: Gong Context
namespaces:
- prefix: gong
  uri: https://api.gong.io/v2/
- prefix: schema
  uri: https://schema.org/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
properties:
- container: ''
  name: Call
  type: ''
- container: ''
  name: CallParty
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Meeting
  type: ''
- container: ''
  name: MeetingAttendee
  type: ''
- container: ''
  name: Flow
  type: ''
- container: ''
  name: Prospect
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Scorecard
  type: ''
- container: ''
  name: Transcript
  type: ''
- container: ''
  name: AuditLogEntry
  type: ''
- container: ''
  name: PermissionProfile
  type: ''
- container: ''
  name: LibraryFolder
  type: ''
property_count: 13
provider_name: Gong
provider_slug: gong
slug: gong-context
source_filename: gong-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gong\": \"https://api.gong.io/v2/\",\n    \"schema\": \"https://schema.org/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n\n    \"Call\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"scheduled\": \"schema:startDate\",\n        \"started\": \"schema:startDate\",\n        \"duration\": \"schema:duration\",\n        \"direction\": \"gong:callDirection\",\n        \"scope\": \"gong:callScope\",\n        \"media\": \"schema:encodingFormat\",\n        \"language\": \"schema:inLanguage\",\n        \"workspaceId\": \"gong:workspaceId\",\n        \"primaryUserId\": \"schema:organizer\",\n        \"parties\": \"schema:attendee\"\n\
  \      }\n    },\n\n    \"CallParty\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"emailAddress\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"title\": \"schema:jobTitle\",\n        \"userId\": \"schema:identifier\",\n        \"speakerId\": \"gong:speakerId\",\n        \"affiliation\": \"schema:affiliation\",\n        \"phoneNumber\": \"schema:telephone\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"emailAddress\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"title\": \"schema:jobTitle\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"extension\": \"vcard:hasExtension\",\n        \"personalMeetingUrls\": \"schema:url\",\n        \"managerId\": \"schema:worksFor\",\n        \"meetingConsentPageUrl\": \"schema:url\"\
  ,\n        \"active\": \"schema:activeStatus\",\n        \"created\": \"dcterms:created\",\n        \"avatarUrl\": \"schema:image\",\n        \"trustedEmailAddress\": \"schema:email\"\n      }\n    },\n\n    \"Meeting\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"scheduledStart\": \"schema:startDate\",\n        \"scheduledEnd\": \"schema:endDate\",\n        \"organizerEmail\": \"schema:organizer\",\n        \"meetingUrl\": \"schema:url\",\n        \"description\": \"schema:description\",\n        \"meetingProvider\": \"gong:meetingProvider\",\n        \"externalMeetingId\": \"schema:identifier\",\n        \"attendees\": \"schema:attendee\"\n      }\n    },\n\n    \"MeetingAttendee\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"emailAddress\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"responseStatus\": \"schema:rsvpResponse\"\n      }\n\
  \    },\n\n    \"Flow\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"ownerEmail\": \"schema:creator\",\n        \"folderId\": \"schema:isPartOf\",\n        \"status\": \"schema:actionStatus\",\n        \"stepsCount\": \"gong:stepsCount\",\n        \"prospectsCount\": \"gong:prospectsCount\",\n        \"workspaceId\": \"gong:workspaceId\",\n        \"created\": \"dcterms:created\",\n        \"modified\": \"dcterms:modified\"\n      }\n    },\n\n    \"Prospect\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"emailAddress\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"company\": \"schema:worksFor\",\n        \"title\": \"schema:jobTitle\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"linkedInUrl\": \"schema:sameAs\"\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"\
  schema:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Scorecard\": {\n      \"@id\": \"schema:Rating\",\n      \"@context\": {\n        \"scorecardId\": \"schema:identifier\",\n        \"scorecardName\": \"schema:name\",\n        \"enabled\": \"gong:enabled\",\n        \"workspaceId\": \"gong:workspaceId\",\n        \"created\": \"dcterms:created\",\n        \"updated\": \"dcterms:modified\",\n        \"questions\": \"schema:hasPart\"\n      }\n    },\n\n    \"Transcript\": {\n      \"@id\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"callId\": \"schema:isPartOf\",\n        \"transcript\": \"schema:text\"\n      }\n    },\n\n    \"AuditLogEntry\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"logType\": \"dcterms:type\",\n        \"timestamp\": \"schema:dateCreated\"\
  ,\n        \"userId\": \"schema:agent\",\n        \"userEmail\": \"schema:agent\",\n        \"action\": \"schema:name\",\n        \"resourceType\": \"schema:object\",\n        \"resourceId\": \"schema:identifier\",\n        \"ipAddress\": \"gong:ipAddress\"\n      }\n    },\n\n    \"PermissionProfile\": {\n      \"@id\": \"schema:Role\",\n      \"@context\": {\n        \"profileId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"workspaceId\": \"gong:workspaceId\",\n        \"userCount\": \"gong:userCount\"\n      }\n    },\n\n    \"LibraryFolder\": {\n      \"@id\": \"schema:Collection\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"parentFolderId\": \"schema:isPartOf\",\n        \"callCount\": \"schema:size\",\n        \"createdBy\": \"schema:creator\",\n        \"created\": \"dcterms:created\"\n \
  \     }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gong/refs/heads/main/json-ld/gong-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
