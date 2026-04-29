---
class_count: 11
classes:
- EventProperty
- EventPropertyListResponse
- CategoryListResponse
- SuccessResponse
- EventType
- EventTypeListResponse
- Category
- UserPropertyListResponse
- UserProperty
- description
- name
context_file: json-ld/amplitude-taxonomy-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-taxonomy-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Taxonomy Api from Amplitude.
layout: jsonld
name: Amplitude Taxonomy Api Context
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
  name: eventProperty
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: isRequired
  type: boolean
- container: set
  name: data
  type: reference
- container: ''
  name: id
  type: integer
- container: ''
  name: success
  type: boolean
- container: ''
  name: category
  type: string
- container: ''
  name: userProperty
  type: string
property_count: 9
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-taxonomy-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EventProperty\": \"amplitude:EventProperty\",\n    \"EventPropertyListResponse\": \"amplitude:EventPropertyListResponse\",\n    \"CategoryListResponse\": \"amplitude:CategoryListResponse\",\n    \"SuccessResponse\": \"amplitude:SuccessResponse\",\n    \"EventType\": \"amplitude:EventType\",\n    \"EventTypeListResponse\": \"amplitude:EventTypeListResponse\",\n    \"Category\": \"amplitude:Category\",\n    \"UserPropertyListResponse\": \"amplitude:UserPropertyListResponse\",\n    \"UserProperty\": \"amplitude:UserProperty\",\n    \"eventProperty\": {\n      \"@id\": \"amplitude:event_property\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"amplitude:event_type\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"description\": \"schema:description\",\n    \"type\": {\n      \"@id\": \"amplitude:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isRequired\": {\n      \"@id\": \"amplitude:is_required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"data\": {\n      \"@id\": \"amplitude:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"amplitude:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"success\": {\n      \"@id\": \"amplitude:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"category\": {\n      \"@id\": \"amplitude:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProperty\": {\n      \"@id\": \"amplitude:user_property\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-taxonomy-api-context.jsonld
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
