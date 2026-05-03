---
api_specs:
- filename: secure-code-warrior-portal-openapi.yml
  format: yaml
  label: Secure Code Warrior Portal API
  slug: secure-code-warrior-portal-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/openapi/secure-code-warrior-portal-openapi.yml
class_count: 25
classes:
- User
- Team
- Assessment
- Course
- Tournament
- id
- email
- firstName
- lastName
- role
- createdAt
- lastActiveAt
- name
- description
- language
- difficulty
- rank
- points
- completions
- realm
- level
- quests_completed
- training_minutes
- assessment_minutes
- total_minutes
context_file: json-ld/secure-code-warrior-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/json-ld/secure-code-warrior-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Secure Code Warrior from Secure Code Warrior.
layout: jsonld
name: Secure Code Warrior Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: scw
  uri: https://securecodewarrior.com/vocab/
properties:
- container: set
  name: teams
  type: ''
- container: set
  name: tags
  type: ''
property_count: 2
provider_name: Secure Code Warrior
provider_slug: secure-code-warrior
slug: secure-code-warrior-context
source_filename: secure-code-warrior-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"scw\": \"https://securecodewarrior.com/vocab/\",\n    \"User\": \"schema:Person\",\n    \"Team\": \"schema:Organization\",\n    \"Assessment\": \"scw:Assessment\",\n    \"Course\": \"schema:Course\",\n    \"Tournament\": \"scw:Tournament\",\n    \"id\": \"@id\",\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"role\": \"schema:roleName\",\n    \"teams\": {\n      \"@id\": \"schema:memberOf\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"lastActiveAt\": \"scw:lastActiveAt\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"language\": \"schema:programmingLanguage\",\n    \"difficulty\"\
  : \"scw:difficulty\",\n    \"rank\": \"scw:rank\",\n    \"points\": \"scw:points\",\n    \"completions\": \"scw:completions\",\n    \"realm\": \"scw:realm\",\n    \"level\": \"scw:level\",\n    \"quests_completed\": \"scw:questsCompleted\",\n    \"training_minutes\": \"scw:trainingMinutes\",\n    \"assessment_minutes\": \"scw:assessmentMinutes\",\n    \"total_minutes\": \"scw:totalMinutes\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/json-ld/secure-code-warrior-context.jsonld
tags:
- Application Security
- Developer Training
- Security Education
- AppSec
- Secure Coding
- DevSecOps
- JSON-LD
- Linked Data
- Semantic Web
---
