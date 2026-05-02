---
api_specs:
- filename: hotjar-rest-api-openapi.yml
  format: yaml
  label: Hotjar REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/openapi/hotjar-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/hotjar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/json-ld/hotjar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hotjar from hotjar.
layout: jsonld
name: Hotjar Context
namespaces:
- prefix: hotjar
  uri: https://api.hotjar.io/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Survey
  type: ''
- container: ''
  name: SurveyQuestion
  type: ''
- container: ''
  name: SurveyResponse
  type: ''
- container: ''
  name: SurveyAnswer
  type: ''
- container: ''
  name: Site
  type: ''
- container: ''
  name: UserAttribute
  type: ''
- container: ''
  name: Event
  type: ''
property_count: 7
provider_name: hotjar
provider_slug: hotjar
slug: hotjar-context
source_filename: hotjar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hotjar\": \"https://api.hotjar.io/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Survey\": {\n      \"@id\": \"hotjar:Survey\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"hotjar:surveyType\",\n        \"is_enabled\": \"hotjar:isEnabled\",\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"responses_url\": {\n          \"@id\": \"hotjar:responsesUrl\",\n          \"@type\": \"@id\"\n        },\n        \"sentiment_analysis_enabled\": \"hotjar:sentimentAnalysisEnabled\",\n        \"questions\": {\n          \"@id\": \"hotjar:questions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\
  \n    \"SurveyQuestion\": {\n      \"@id\": \"hotjar:SurveyQuestion\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"type\": \"hotjar:questionType\",\n        \"is_required\": \"hotjar:isRequired\",\n        \"choices\": {\n          \"@id\": \"hotjar:choices\",\n          \"@container\": \"@set\"\n        },\n        \"image_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"SurveyResponse\": {\n      \"@id\": \"hotjar:SurveyResponse\",\n      \"@context\": {\n        \"answers\": {\n          \"@id\": \"hotjar:answers\",\n          \"@container\": \"@set\"\n        },\n        \"comment\": \"schema:comment\",\n        \"tags\": {\n          \"@id\": \"hotjar:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SurveyAnswer\": {\n      \"@id\": \"hotjar:SurveyAnswer\",\n      \"@context\": {\n        \"question_id\": \"hotjar:questionId\",\n        \"answer\": \"schema:text\"\
  \n      }\n    },\n\n    \"Site\": {\n      \"@id\": \"hotjar:Site\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"UserAttribute\": {\n      \"@id\": \"hotjar:UserAttribute\",\n      \"@context\": {\n        \"user_id\": \"schema:identifier\",\n        \"attributes\": \"hotjar:attributes\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"hotjar:Event\",\n      \"@context\": {\n        \"action_name\": \"schema:name\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/json-ld/hotjar-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
