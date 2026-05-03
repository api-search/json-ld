---
api_specs:
- filename: stack-exchange-openapi.yml
  format: yaml
  label: Stack Exchange API
  slug: stack-exchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/openapi/stack-exchange-openapi.yml
class_count: 32
classes:
- QAForum
- StackExchangeSite
- Question
- Answer
- Comment
- User
- Tag
- Badge
- question_id
- title
- body
- score
- view_count
- answer_count
- accepted_answer_id
- is_answered
- owner
- tags
- user_id
- display_name
- reputation
- tag_name
- count
- has_synonyms
- badge_id
- award_count
- rank
- StackOverflow
- ServerFault
- SuperUser
- comment_id
- post_id
context_file: json-ld/stack-exchange-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/json-ld/stack-exchange-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stack Exchange from Stack Exchange.
layout: jsonld
name: Stack Exchange Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: se
  uri: https://api.stackexchange.com/2.3/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
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
provider_name: Stack Exchange
provider_slug: stack-exchange
slug: stack-exchange-context
source_filename: stack-exchange-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"se\": \"https://api.stackexchange.com/2.3/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n\n    \"QAForum\": \"schema:QAPage\",\n    \"StackExchangeSite\": \"schema:WebSite\",\n    \"Question\": \"schema:Question\",\n    \"Answer\": \"schema:Answer\",\n    \"Comment\": \"sioc:Post\",\n    \"User\": \"foaf:Person\",\n    \"Tag\": \"schema:DefinedTerm\",\n    \"Badge\": \"schema:Certification\",\n\n    \"question_id\": \"schema:identifier\",\n    \"title\": \"schema:name\",\n    \"body\": \"schema:text\",\n    \"score\": \"schema:reviewCount\",\n    \"view_count\": \"schema:interactionCount\",\n    \"answer_count\": \"schema:answerCount\",\n    \"accepted_answer_id\": \"schema:acceptedAnswer\",\n    \"is_answered\": \"schema:answerCount\",\n    \"creation_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\
  \n    },\n    \"last_activity_date\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"owner\": \"schema:author\",\n    \"tags\": \"schema:keywords\",\n    \"link\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"user_id\": \"schema:identifier\",\n    \"display_name\": \"foaf:name\",\n    \"reputation\": \"se:reputation\",\n    \"profile_image\": {\n      \"@id\": \"foaf:img\",\n      \"@type\": \"@id\"\n    },\n\n    \"tag_name\": \"schema:name\",\n    \"count\": \"schema:commentCount\",\n    \"has_synonyms\": \"se:hasSynonyms\",\n\n    \"badge_id\": \"schema:identifier\",\n    \"award_count\": \"schema:reviewCount\",\n    \"rank\": \"schema:educationalLevel\",\n\n    \"StackOverflow\": \"se:stackoverflow\",\n    \"ServerFault\": \"se:serverfault\",\n    \"SuperUser\": \"se:superuser\",\n\n    \"comment_id\": \"schema:identifier\",\n    \"post_id\": \"se:postId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/json-ld/stack-exchange-context.jsonld
tags:
- Answers
- Code
- Community
- Developer Tools
- Knowledge Base
- Q&A
- Questions
- Stack Exchange
- JSON-LD
- Linked Data
- Semantic Web
---
