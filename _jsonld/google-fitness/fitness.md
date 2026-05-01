---
api_specs:
- filename: fitness.yml
  format: yaml
  label: Google Fit REST API v1
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-fitness/refs/heads/main/openapi/fitness.yml
class_count: 12
classes:
- Session
- DataSource
- DataPoint
- id
- name
- description
- activityType
- activeTimeMillis
- application
- device
- manufacturer
- model
context_file: json-ld/fitness.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-fitness/refs/heads/main/json-ld/fitness.jsonld
description: JSON-LD context defining the semantic vocabulary for Fitness from Google Fit REST.
layout: jsonld
name: Fitness Context
namespaces:
- prefix: gfit
  uri: https://www.googleapis.com/fitness/v1/
properties:
- container: ''
  name: startTimeMillis
  type: schema:DateTime
- container: ''
  name: endTimeMillis
  type: schema:DateTime
property_count: 2
provider_name: Google Fit REST
provider_slug: google-fitness
slug: fitness
source_filename: fitness.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gfit\": \"https://www.googleapis.com/fitness/v1/\",\n    \"Session\": \"schema:ExerciseAction\",\n    \"DataSource\": \"gfit:DataSource\",\n    \"DataPoint\": \"gfit:DataPoint\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"startTimeMillis\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"endTimeMillis\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"activityType\": \"schema:exerciseType\",\n    \"activeTimeMillis\": \"schema:duration\",\n    \"application\": \"schema:softwareApplication\",\n    \"device\": \"schema:device\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"model\": \"schema:model\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-fitness/refs/heads/main/json-ld/fitness.jsonld
tags:
- Activity Tracking
- Fitness
- Google
- Health
- Sessions
- Wearables
- Wellness
- JSON-LD
- Linked Data
- Semantic Web
---
