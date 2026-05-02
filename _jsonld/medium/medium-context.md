---
api_specs:
- filename: medium-rest-api-openapi.yml
  format: yaml
  label: Medium REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/openapi/medium-rest-api-openapi.yml
- filename: medium-oauth2-openapi.yml
  format: yaml
  label: Medium OAuth2 API
  slug: oauth2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/openapi/medium-oauth2-openapi.yml
class_count: 0
classes: []
context_file: json-ld/medium-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/json-ld/medium-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Medium from medium.
layout: jsonld
name: Medium Context
namespaces:
- prefix: medium
  uri: https://api.medium.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Publication
  type: ''
- container: ''
  name: Post
  type: ''
- container: ''
  name: Contributor
  type: ''
- container: ''
  name: Image
  type: ''
property_count: 5
provider_name: medium
provider_slug: medium
slug: medium-context
source_filename: medium-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"medium\": \"https://api.medium.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"medium:userId\",\n        \"username\": \"schema:alternateName\",\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Publication\": {\n      \"@id\": \"schema:Periodical\",\n      \"@context\": {\n        \"id\": \"medium:publicationId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"imageUrl\"\
  : {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"contributors\": {\n          \"@id\": \"schema:contributor\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Post\": {\n      \"@id\": \"schema:BlogPosting\",\n      \"@context\": {\n        \"id\": \"medium:postId\",\n        \"title\": \"schema:headline\",\n        \"content\": \"schema:articleBody\",\n        \"authorId\": \"schema:author\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"canonicalUrl\": {\n          \"@id\": \"schema:mainEntityOfPage\",\n          \"@type\": \"@id\"\n        },\n        \"publishStatus\": \"schema:creativeWorkStatus\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"license\": \"dcterms:license\"\
  ,\n        \"licenseUrl\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"publicationId\": \"schema:isPartOf\"\n      }\n    },\n\n    \"Contributor\": {\n      \"@id\": \"schema:Role\",\n      \"@context\": {\n        \"userId\": \"schema:contributor\",\n        \"publicationId\": \"schema:isPartOf\",\n        \"role\": \"schema:roleName\"\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"schema:ImageObject\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"md5\": \"medium:md5\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/json-ld/medium-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
