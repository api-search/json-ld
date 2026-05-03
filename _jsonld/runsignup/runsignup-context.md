---
api_specs:
- filename: runsignup-openapi.yml
  format: yaml
  label: RunSignup API
  slug: runsignup
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/openapi/runsignup-openapi.yml
class_count: 0
classes: []
context_file: json-ld/runsignup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/json-ld/runsignup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Runsignup from RunSignup.
layout: jsonld
name: Runsignup Context
namespaces:
- prefix: runsignup
  uri: https://runsignup.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sport
  uri: https://schema.org/SportsEvent
properties:
- container: ''
  name: Race
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Participant
  type: ''
- container: ''
  name: Result
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Division
  type: ''
- container: ''
  name: Donation
  type: ''
property_count: 7
provider_name: RunSignup
provider_slug: runsignup
slug: runsignup-context
source_filename: runsignup-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"runsignup\": \"https://runsignup.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sport\": \"https://schema.org/SportsEvent\",\n\n    \"Race\": {\n      \"@id\": \"schema:SportsEvent\",\n      \"@context\": {\n        \"race_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"city\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"schema:Place\"\n        },\n        \"state\": \"runsignup:stateCode\",\n        \"country_code\": \"runsignup:countryCode\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"external_race_url\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"@id\"\n        },\n        \"logo_url\": {\n          \"@id\": \"schema:image\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"next_date\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"is_registration_open\": \"runsignup:registrationOpen\",\n        \"events\": \"schema:subEvent\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"schema:SportsEvent\",\n      \"@context\": {\n        \"event_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"start_time\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"distance\": \"schema:distance\",\n        \"distance_unit\": \"runsignup:distanceUnit\",\n        \"max_participants\": \"runsignup:maximumAttendeeCapacity\",\n        \"registration_opens\": {\n          \"@id\": \"runsignup:registrationOpens\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"registration_closes\": {\n          \"@id\": \"runsignup:registrationCloses\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Participant\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"registration_id\": \"schema:identifier\",\n        \"user_id\": \"runsignup:userId\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"dob\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"gender\": \"schema:gender\",\n        \"bib_num\": \"runsignup:bibNumber\",\n        \"chip_num\": \"runsignup:chipNumber\",\n        \"registration_date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Result\": {\n      \"@id\": \"runsignup:RaceResult\",\n      \"@context\": {\n        \"result_id\": \"schema:identifier\",\n        \"registration_id\": \"runsignup:registration\",\n        \"bib_num\": \"runsignup:bibNumber\",\n        \"clock_time\": \"runsignup:clockTime\"\
  ,\n        \"chip_time\": \"runsignup:chipTime\",\n        \"place_overall\": \"runsignup:overallPlace\",\n        \"place_gender\": \"runsignup:genderPlace\",\n        \"place_division\": \"runsignup:divisionPlace\",\n        \"pace\": \"runsignup:pace\"\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"schema:SportsTeam\",\n      \"@context\": {\n        \"team_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"member_count\": \"runsignup:memberCount\",\n        \"captain_user_id\": \"schema:member\"\n      }\n    },\n\n    \"Division\": {\n      \"@id\": \"runsignup:RaceDivision\",\n      \"@context\": {\n        \"division_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"gender\": \"schema:gender\",\n        \"age_min\": \"runsignup:minimumAge\",\n        \"age_max\": \"runsignup:maximumAge\"\n      }\n    },\n\n    \"Donation\": {\n      \"@id\": \"schema:MonetaryGrant\",\n      \"@context\": {\n        \"donation_id\": \"schema:identifier\"\
  ,\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"schema:MonetaryAmount\"\n        },\n        \"donation_date\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/json-ld/runsignup-context.jsonld
tags:
- Race Registration
- Event Management
- Running
- Sports
- Fitness
- Timing
- Fundraising
- JSON-LD
- Linked Data
- Semantic Web
---
