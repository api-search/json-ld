---
class_count: 3
classes:
- UserProfileResponse
- UserData
- Recommendation
context_file: json-ld/amplitude-user-profile-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-user-profile-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude User Profile Api from Amplitude.
layout: jsonld
name: Amplitude User Profile Api Context
namespaces:
- prefix: amplitude
  uri: https://amplitude.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: userData
  type: reference
- container: ''
  name: userId
  type: string
- container: ''
  name: userProperties
  type: reference
- container: ''
  name: computedProperties
  type: reference
- container: set
  name: cohortIds
  type: string
- container: set
  name: recommendations
  type: reference
- container: ''
  name: amplitudeId
  type: integer
- container: ''
  name: recId
  type: string
- container: set
  name: childIds
  type: string
- container: ''
  name: isControl
  type: boolean
- container: ''
  name: recommendationType
  type: string
- container: ''
  name: title
  type: string
property_count: 12
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-user-profile-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UserProfileResponse\": \"amplitude:UserProfileResponse\",\n    \"UserData\": \"amplitude:UserData\",\n    \"Recommendation\": \"amplitude:Recommendation\",\n    \"userData\": {\n      \"@id\": \"amplitude:userData\",\n      \"@type\": \"@id\"\n    },\n    \"userId\": {\n      \"@id\": \"amplitude:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProperties\": {\n      \"@id\": \"amplitude:user_properties\",\n      \"@type\": \"@id\"\n    },\n    \"computedProperties\": {\n      \"@id\": \"amplitude:computed_properties\",\n      \"@type\": \"@id\"\n    },\n    \"cohortIds\": {\n      \"@id\": \"amplitude:cohort_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendations\"\
  : {\n      \"@id\": \"amplitude:recommendations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"amplitudeId\": {\n      \"@id\": \"amplitude:amplitude_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recId\": {\n      \"@id\": \"amplitude:rec_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"childIds\": {\n      \"@id\": \"amplitude:child_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isControl\": {\n      \"@id\": \"amplitude:is_control\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"recommendationType\": {\n      \"@id\": \"amplitude:recommendation_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"amplitude:title\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-user-profile-api-context.jsonld
tags:
- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---
