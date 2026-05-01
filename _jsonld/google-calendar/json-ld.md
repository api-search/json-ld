---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Calendar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-calendar/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-calendar/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Calendar.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: gcal
  uri: https://www.googleapis.com/calendar/v3/
- prefix: goog
  uri: https://developers.google.com/workspace/calendar/api/v3/reference/
properties:
- container: ''
  name: Calendar
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: EventAttendee
  type: ''
- container: ''
  name: AclRule
  type: ''
property_count: 4
provider_name: Google Calendar
provider_slug: google-calendar
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcal\": \"https://www.googleapis.com/calendar/v3/\",\n    \"goog\": \"https://developers.google.com/workspace/calendar/api/v3/reference/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"Calendar\": {\n      \"@id\": \"goog:calendars\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"summary\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"location\": \"schema:location\",\n        \"timeZone\": \"schema:timezone\"\n      }\n    },\n    \"Event\": {\n      \"@id\": \"goog:events\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"summary\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"location\": \"schema:location\",\n        \"start\": \"schema:startDate\",\n        \"end\": \"schema:endDate\"\
  ,\n        \"created\": \"schema:dateCreated\",\n        \"updated\": \"schema:dateModified\",\n        \"status\": \"schema:eventStatus\",\n        \"htmlLink\": \"schema:url\",\n        \"attendees\": \"schema:attendee\",\n        \"organizer\": \"schema:organizer\",\n        \"recurrence\": \"schema:repeatFrequency\"\n      }\n    },\n    \"EventAttendee\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"displayName\": \"schema:name\",\n        \"responseStatus\": \"schema:rsvpResponse\"\n      }\n    },\n    \"AclRule\": {\n      \"@id\": \"goog:acl\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"role\": \"schema:roleName\",\n        \"scope\": \"schema:audience\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Calendar API\",\n  \"description\": \"The Google Calendar API provides RESTful access to Google Calendar data for managing calendars, events, and settings.\",\n  \"\
  url\": \"https://developers.google.com/workspace/calendar/api/guides/overview\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-calendar/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Availability
- Calendar
- Events
- Google
- Google Workspace
- Scheduling
- JSON-LD
- Linked Data
- Semantic Web
---
