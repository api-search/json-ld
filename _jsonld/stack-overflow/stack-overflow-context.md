---
api_specs:
- filename: stack-overflow-openapi.yml
  format: yaml
  label: Stack Overflow API
  slug: stack-overflow-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/openapi/stack-overflow-openapi.yml
- filename: stack-overflow-for-teams-openapi.yml
  format: yaml
  label: Stack Overflow for Teams API v3
  slug: stack-overflow-for-teams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/openapi/stack-overflow-for-teams-openapi.yml
class_count: 27
classes:
- StackOverflow
- Question
- Answer
- Comment
- Article
- User
- Tag
- Badge
- UserGroup
- Team
- SME
- question_id
- title
- body
- score
- view_count
- answer_count
- accepted_answer_id
- owner
- tags
- user_id
- display_name
- reputation
- email
- team
- is_accepted
- bounty_amount
context_file: json-ld/stack-overflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/json-ld/stack-overflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stack Overflow from Stack Overflow.
layout: jsonld
name: Stack Overflow Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: so
  uri: https://api.stackexchange.com/2.3/
properties:
- container: ''
  name: creation_date
  type: schema:DateTime
- container: ''
  name: last_activity_date
  type: schema:DateTime
- container: ''
  name: link
  type: reference
- container: ''
  name: profile_image
  type: reference
property_count: 4
provider_name: Stack Overflow
provider_slug: stack-overflow
slug: stack-overflow-context
source_filename: stack-overflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"so\": \"https://api.stackexchange.com/2.3/\",\n\n    \"StackOverflow\": \"schema:WebSite\",\n    \"Question\": \"schema:Question\",\n    \"Answer\": \"schema:Answer\",\n    \"Comment\": \"sioc:Post\",\n    \"Article\": \"schema:Article\",\n    \"User\": \"foaf:Person\",\n    \"Tag\": \"schema:DefinedTerm\",\n    \"Badge\": \"schema:Certification\",\n    \"UserGroup\": \"schema:Organization\",\n    \"Team\": \"schema:Team\",\n    \"SME\": \"so:SubjectMatterExpert\",\n\n    \"question_id\": \"schema:identifier\",\n    \"title\": \"schema:name\",\n    \"body\": \"schema:text\",\n    \"score\": \"schema:reviewCount\",\n    \"view_count\": \"schema:interactionCount\",\n    \"answer_count\": \"schema:answerCount\",\n    \"accepted_answer_id\": \"schema:acceptedAnswer\",\n    \"creation_date\": {\n\
  \      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"last_activity_date\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"owner\": \"schema:author\",\n    \"tags\": \"schema:keywords\",\n    \"link\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"user_id\": \"schema:identifier\",\n    \"display_name\": \"foaf:name\",\n    \"reputation\": \"so:reputation\",\n    \"profile_image\": {\n      \"@id\": \"foaf:img\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n\n    \"team\": \"schema:identifier\",\n    \"is_accepted\": \"so:isAccepted\",\n    \"bounty_amount\": \"so:bountyAmount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/json-ld/stack-overflow-context.jsonld
tags:
- Answers
- Code
- Developer Community
- Developer Tools
- Knowledge Base
- Programming
- Q&A
- Questions
- Stack Overflow
- JSON-LD
- Linked Data
- Semantic Web
---
