---
api_specs:
- filename: strava-openapi.yml
  format: yaml
  label: Strava API
  slug: strava
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/openapi/strava-openapi.yml
class_count: 0
classes: []
context_file: json-ld/strava-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/json-ld/strava-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Strava from Strava.
layout: jsonld
name: Strava Context
namespaces:
- prefix: strava
  uri: https://www.strava.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sport
  uri: https://www.wikidata.org/entity/
properties:
- container: ''
  name: Activity
  type: ''
- container: ''
  name: Athlete
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Club
  type: ''
property_count: 5
provider_name: Strava
provider_slug: strava
slug: strava-context
source_filename: strava-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"strava\": \"https://www.strava.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sport\": \"https://www.wikidata.org/entity/\",\n\n    \"Activity\": {\n      \"@id\": \"strava:Activity\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"distance\": {\n          \"@id\": \"strava:distance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"moving_time\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"elapsed_time\": {\n          \"@id\": \"strava:elapsedTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_elevation_gain\": {\n          \"@id\": \"strava:elevationGain\",\n          \"@type\": \"xsd:decimal\"\n        },\n     \
  \   \"type\": {\n          \"@id\": \"schema:exerciseType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sport_type\": {\n          \"@id\": \"strava:sportType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_date\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"start_date_local\": {\n          \"@id\": \"strava:startDateLocal\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timezone\": {\n          \"@id\": \"strava:timezone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_latlng\": \"schema:startLocation\",\n        \"end_latlng\": \"schema:endLocation\",\n        \"kudos_count\": {\n          \"@id\": \"strava:kudosCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"comment_count\": {\n          \"@id\": \"strava:commentCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"trainer\": {\n          \"@id\": \"strava:trainer\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"commute\": {\n          \"@id\": \"strava:commute\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"manual\": {\n          \"@id\": \"strava:manual\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"private\": {\n          \"@id\": \"strava:private\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"average_speed\": {\n          \"@id\": \"strava:averageSpeed\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"average_heartrate\": {\n          \"@id\": \"strava:averageHeartRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"average_watts\": {\n          \"@id\": \"strava:averagePower\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"suffer_score\": {\n          \"@id\": \"strava:relativeEffort\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Athlete\": {\n      \"@id\": \"strava:Athlete\",\n      \"@context\": {\n\
  \        \"id\": \"@id\",\n        \"firstname\": \"schema:givenName\",\n        \"lastname\": \"schema:familyName\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"sex\": \"schema:gender\",\n        \"follower_count\": \"strava:followerCount\",\n        \"friend_count\": \"strava:friendCount\",\n        \"weight\": {\n          \"@id\": \"schema:weight\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"profile\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"strava:Segment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"distance\": \"strava:distance\",\n        \"average_grade\": \"strava:averageGrade\",\n        \"elevation_high\": \"strava:elevationHigh\",\n        \"elevation_low\": \"strava:elevationLow\",\n        \"city\"\
  : \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"effort_count\": \"strava:effortCount\",\n        \"athlete_count\": \"strava:athleteCount\",\n        \"star_count\": \"strava:starCount\"\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"strava:Route\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"distance\": \"strava:distance\",\n        \"elevation_gain\": \"strava:elevationGain\",\n        \"type\": \"strava:routeType\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Club\": {\n      \"@id\": \"strava:Club\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\"\
  ,\n        \"description\": \"schema:description\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"member_count\": \"schema:memberOf\",\n        \"sport_type\": \"schema:sport\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/json-ld/strava-context.jsonld
tags:
- Cycling
- Fitness
- Fitness Tracking
- Running
- Sports
- JSON-LD
- Linked Data
- Semantic Web
---
