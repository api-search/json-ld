---
class_count: 18
classes:
- name
- description
- version
- env
- config
- tests
- steps
- url
- method
- headers
- body
- params
- captures
- check
- auth
- components
- schemas
- credentials
context_file: json-ld/step-ci-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/step-ci/refs/heads/main/json-ld/step-ci-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Step Ci from Step CI.
layout: jsonld
name: Step Ci Context
namespaces:
- prefix: stepci
  uri: https://stepci.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
properties:
- container: ''
  name: Workflow
  type: reference
- container: ''
  name: TestCase
  type: reference
- container: ''
  name: Step
  type: reference
property_count: 3
provider_name: Step CI
provider_slug: step-ci
slug: step-ci-context
source_filename: step-ci-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"stepci\": \"https://stepci.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"Workflow\": {\n      \"@id\": \"stepci:Workflow\",\n      \"@type\": \"@id\"\n    },\n    \"TestCase\": {\n      \"@id\": \"stepci:TestCase\",\n      \"@type\": \"@id\"\n    },\n    \"Step\": {\n      \"@id\": \"stepci:Step\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"env\": \"stepci:environment\",\n    \"config\": \"stepci:configuration\",\n    \"tests\": \"stepci:tests\",\n    \"steps\": \"stepci:steps\",\n    \"url\": \"schema:url\",\n    \"method\": \"stepci:httpMethod\",\n    \"headers\": \"stepci:headers\",\n    \"body\": \"stepci:requestBody\",\n    \"params\": \"stepci:queryParameters\",\n    \"captures\": \"stepci:captures\",\n    \"check\": \"stepci:assertions\"\
  ,\n    \"auth\": \"stepci:authentication\",\n    \"components\": \"stepci:components\",\n    \"schemas\": \"stepci:schemas\",\n    \"credentials\": \"stepci:credentials\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/step-ci/refs/heads/main/json-ld/step-ci-context.jsonld
tags:
- API Testing
- Functional Testing
- Testing
- CI/CD
- Quality Assurance
- Automation
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
