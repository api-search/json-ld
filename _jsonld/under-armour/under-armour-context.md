---
api_specs:
- filename: mapmyfitness-openapi.yml
  format: yaml
  label: MapMyFitness API
  slug: mapmyfitness-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/openapi/mapmyfitness-openapi.yml
class_count: 15
classes:
- Workout
- Route
- User
- Device
- name
- description
- username
- email
- first_name
- last_name
- time_zone
- city
- state
- country
- postal_code
context_file: json-ld/under-armour-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/json-ld/under-armour-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Under Armour from Under Armour.
layout: jsonld
name: Under Armour Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ua
  uri: https://github.com/api-evangelist/under-armour/blob/main/json-ld/under-armour-context.jsonld#
properties:
- container: ''
  name: start_datetime
  type: dateTime
- container: ''
  name: start_locale_timezone
  type: string
- container: ''
  name: aggregates
  type: reference
- container: ''
  name: distance_total
  type: decimal
- container: ''
  name: steps_total
  type: integer
- container: ''
  name: active_time_total
  type: decimal
- container: ''
  name: metabolic_energy_total
  type: decimal
- container: ''
  name: heartrate_avg
  type: decimal
- container: ''
  name: heartrate_max
  type: decimal
- container: ''
  name: speed_avg
  type: decimal
- container: ''
  name: activity_type
  type: reference
- container: ''
  name: birthdate
  type: date
- container: ''
  name: height
  type: decimal
- container: ''
  name: weight
  type: decimal
- container: ''
  name: date_joined
  type: dateTime
- container: ''
  name: distance
  type: decimal
- container: ''
  name: callback_url
  type: reference
- container: ''
  name: event_type
  type: string
property_count: 18
provider_name: Under Armour
provider_slug: under-armour
slug: under-armour-context
source_filename: under-armour-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ua\": \"https://github.com/api-evangelist/under-armour/blob/main/json-ld/under-armour-context.jsonld#\",\n\n    \"Workout\": \"schema:ExerciseAction\",\n    \"Route\": \"schema:ExercisePlan\",\n    \"User\": \"schema:Person\",\n    \"Device\": \"schema:Product\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"start_datetime\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"start_locale_timezone\": {\n      \"@id\": \"schema:eventSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregates\": {\n      \"@id\": \"ua:aggregates\",\n      \"@type\": \"@id\"\n    },\n    \"distance_total\": {\n      \"@id\": \"schema:distance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"steps_total\": {\n      \"@id\": \"schema:numberOfSteps\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"active_time_total\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"metabolic_energy_total\": {\n      \"@id\": \"schema:energy\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"heartrate_avg\": {\n      \"@id\": \"ua:averageHeartRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"heartrate_max\": {\n      \"@id\": \"ua:maxHeartRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"speed_avg\": {\n      \"@id\": \"ua:averageSpeed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"activity_type\": {\n      \"@id\": \"schema:exerciseType\",\n      \"@type\": \"@id\"\n    },\n    \"username\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"birthdate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"height\": {\n      \"@id\": \"schema:height\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"time_zone\": \"schema:homeLocation\",\n    \"date_joined\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"distance\": {\n      \"@id\": \"schema:distance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"postal_code\": \"schema:postalCode\",\n    \"callback_url\": {\n      \"@id\": \"ua:callbackUrl\",\n      \"@type\": \"@id\"\n    },\n    \"event_type\": {\n      \"@id\": \"ua:eventType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/json-ld/under-armour-context.jsonld
tags:
- Fitness
- Health
- Wearables
- Connected Fitness
- Sports
- Fortune 1000
- JSON-LD
- Linked Data
- Semantic Web
---
