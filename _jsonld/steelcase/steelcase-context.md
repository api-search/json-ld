---
api_specs:
- filename: steelcase-roomwizard-api-openapi.yml
  format: yaml
  label: Steelcase RoomWizard API
  slug: roomwizard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/openapi/steelcase-roomwizard-api-openapi.yml
class_count: 28
classes:
- id
- type
- Booking
- Room
- ConnectorStatus
- booking_id
- room_id
- room_name
- subject
- organizer
- start_time
- end_time
- attendee_count
- status
- calendar_source
- notes
- created_at
- name
- building
- floor
- capacity
- is_available
- equipment
- email_address
- roomwizard_id
- is_available_now
- next_available
- busy_slots
context_file: json-ld/steelcase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/json-ld/steelcase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Steelcase from Steelcase.
layout: jsonld
name: Steelcase Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: steelcase
  uri: https://www.steelcase.com/vocab/
properties: []
property_count: 0
provider_name: Steelcase
provider_slug: steelcase
slug: steelcase-context
source_filename: steelcase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"steelcase\": \"https://www.steelcase.com/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Booking\": \"schema:Event\",\n    \"Room\": \"schema:Place\",\n    \"ConnectorStatus\": \"steelcase:ConnectorStatus\",\n    \"booking_id\": \"steelcase:bookingId\",\n    \"room_id\": \"steelcase:roomId\",\n    \"room_name\": \"schema:name\",\n    \"subject\": \"schema:name\",\n    \"organizer\": \"schema:organizer\",\n    \"start_time\": \"schema:startDate\",\n    \"end_time\": \"schema:endDate\",\n    \"attendee_count\": \"schema:maximumAttendeeCapacity\",\n    \"status\": \"schema:eventStatus\",\n    \"calendar_source\": \"steelcase:calendarSource\",\n    \"notes\": \"schema:description\",\n    \"created_at\": \"schema:dateCreated\",\n    \"name\": \"schema:name\",\n    \"building\": \"schema:containedInPlace\",\n    \"floor\": \"steelcase:floor\",\n    \"capacity\": \"schema:maximumAttendeeCapacity\"\
  ,\n    \"is_available\": \"schema:available\",\n    \"equipment\": \"schema:amenityFeature\",\n    \"email_address\": \"schema:email\",\n    \"roomwizard_id\": \"steelcase:roomwizardId\",\n    \"is_available_now\": \"steelcase:isAvailableNow\",\n    \"next_available\": \"steelcase:nextAvailable\",\n    \"busy_slots\": \"steelcase:busySlots\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/json-ld/steelcase-context.jsonld
tags:
- Office Furniture
- Workplace
- Room Scheduling
- Facilities Management
- IoT
- Smart Office
- JSON-LD
- Linked Data
- Semantic Web
---
