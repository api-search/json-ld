---
api_specs:
- filename: calendly-scheduling-api-openapi.yml
  format: yaml
  label: Calendly Scheduling API
  slug: scheduling-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/openapi/calendly-scheduling-api-openapi.yml
- filename: calendly-webhook-api-asyncapi.yml
  format: yaml
  label: Calendly Webhook API
  slug: webhook-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/asyncapi/calendly-webhook-api-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/calendly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/json-ld/calendly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Calendly from Calendly.
layout: jsonld
name: Calendly Context
namespaces:
- prefix: calendly
  uri: https://api.calendly.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: EventType
  type: ''
- container: ''
  name: ScheduledEvent
  type: ''
- container: ''
  name: Invitee
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: OrganizationMembership
  type: ''
- container: ''
  name: WebhookSubscription
  type: ''
- container: ''
  name: RoutingForm
  type: ''
- container: ''
  name: AvailabilitySchedule
  type: ''
property_count: 9
provider_name: Calendly
provider_slug: calendly
slug: calendly-context
source_filename: calendly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"calendly\": \"https://api.calendly.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"calendly:User\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"slug\": \"calendly:slug\",\n        \"scheduling_url\": {\n          \"@id\": \"calendly:schedulingUrl\",\n          \"@type\": \"@id\"\n        },\n        \"timezone\": \"calendly:timezone\",\n        \"avatar_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"current_organization\": {\n          \"@id\": \"schema:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\":\
  \ \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EventType\": {\n      \"@id\": \"calendly:EventType\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description_plain\": \"schema:description\",\n        \"slug\": \"calendly:slug\",\n        \"scheduling_url\": {\n          \"@id\": \"calendly:schedulingUrl\",\n          \"@type\": \"@id\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"active\": \"calendly:active\",\n        \"kind\": \"calendly:kind\",\n        \"pooling_type\": \"calendly:poolingType\",\n        \"color\": \"calendly:color\",\n        \"secret\": \"calendly:secret\",\n        \"booking_method\": \"calendly:bookingMethod\",\n        \"custom_questions\": {\n          \"@id\": \"calendly:customQuestions\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ScheduledEvent\": {\n      \"@id\": \"calendly:ScheduledEvent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"schema:eventStatus\",\n        \"start_time\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end_time\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"event_type\": {\n          \"@id\": \"calendly:eventType\",\n          \"@type\": \"@id\"\n        },\n        \"location\": \"schema:location\",\n        \"event_memberships\": {\n          \"@id\": \"schema:organizer\",\n          \"@container\": \"@set\"\n        },\n        \"event_guests\": {\n          \"@id\": \"schema:attendee\",\n          \"@container\": \"@set\"\n        },\n\
  \        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Invitee\": {\n      \"@id\": \"calendly:Invitee\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"status\": \"calendly:inviteeStatus\",\n        \"timezone\": \"calendly:timezone\",\n        \"event\": {\n          \"@id\": \"schema:subjectOf\",\n          \"@type\": \"@id\"\n        },\n        \"cancel_url\": {\n          \"@id\": \"calendly:cancelUrl\",\n          \"@type\": \"@id\"\n        },\n        \"reschedule_url\": {\n          \"@id\": \"calendly:rescheduleUrl\",\n          \"@type\": \"@id\"\n        },\n        \"rescheduled\": \"calendly:rescheduled\",\n     \
  \   \"questions_and_answers\": {\n          \"@id\": \"calendly:questionsAndAnswers\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"calendly:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"OrganizationMembership\": {\n      \"@id\": \"calendly:OrganizationMembership\",\n      \"@context\": {\n        \"role\": \"schema:roleName\",\n        \"user\": {\n          \"@id\": \"schema:member\",\n          \"\
  @type\": \"@id\"\n        },\n        \"organization\": {\n          \"@id\": \"schema:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookSubscription\": {\n      \"@id\": \"calendly:WebhookSubscription\",\n      \"@context\": {\n        \"callback_url\": {\n          \"@id\": \"calendly:callbackUrl\",\n          \"@type\": \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"calendly:subscribedEvents\",\n          \"@container\": \"@set\"\n        },\n        \"scope\": \"calendly:scope\",\n        \"state\": \"calendly:state\",\n        \"organization\": {\n          \"@id\": \"schema:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"creator\": {\n          \"@id\": \"dcterms:creator\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RoutingForm\": {\n      \"@id\": \"calendly:RoutingForm\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"organization\": {\n          \"@id\": \"schema:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"questions\": {\n          \"@id\": \"calendly:questions\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AvailabilitySchedule\": {\n      \"@id\": \"calendly:AvailabilitySchedule\",\n   \
  \   \"@context\": {\n        \"name\": \"schema:name\",\n        \"timezone\": \"calendly:timezone\",\n        \"default\": \"calendly:isDefault\",\n        \"rules\": {\n          \"@id\": \"calendly:availabilityRules\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/json-ld/calendly-context.jsonld
tags:
- Appointments
- Automation
- Booking
- Calendars
- Meetings
- Scheduling
- JSON-LD
- Linked Data
- Semantic Web
---
