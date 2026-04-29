---
api_specs:
- filename: crossref-openapi.yml
  format: yaml
  label: Crossref REST API
  slug: crossref-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/openapi/crossref-openapi.yml
class_count: 36
classes:
- Work
- Member
- Journal
- Funder
- Prefix
- Type
- License
- ISBN
- title
- container-title
- publisher
- publisher-location
- abstract
- subject
- type
- given
- family
- issued
- published
- published-print
- published-online
- created
- deposited
- indexed
- volume
- issue
- page
- article-number
- is-referenced-by-count
- references-count
- score
- link
- relation
- agency
- member
- prefix
context_file: json-ld/crossref-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/json-ld/crossref-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Crossref from Crossref.
layout: jsonld
name: Crossref Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dc
  uri: http://purl.org/dc/terms/
- prefix: prism
  uri: http://prismstandard.org/namespaces/basic/2.0/
- prefix: fabio
  uri: http://purl.org/spar/fabio/
- prefix: frbr
  uri: http://purl.org/vocab/frbr/core#
properties:
- container: ''
  name: DOI
  type: reference
- container: ''
  name: ISSN
  type: ''
- container: ''
  name: URL
  type: reference
- container: list
  name: author
  type: ''
- container: list
  name: editor
  type: ''
- container: list
  name: translator
  type: ''
- container: ''
  name: ORCID
  type: reference
- container: set
  name: affiliation
  type: ''
- container: ''
  name: ROR
  type: reference
- container: set
  name: reference
  type: ''
- container: set
  name: funder
  type: ''
- container: set
  name: license
  type: ''
property_count: 12
provider_name: Crossref
provider_slug: crossref
slug: crossref-context
source_filename: crossref-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api.crossref.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dc\": \"http://purl.org/dc/terms/\",\n    \"prism\": \"http://prismstandard.org/namespaces/basic/2.0/\",\n    \"fabio\": \"http://purl.org/spar/fabio/\",\n    \"frbr\": \"http://purl.org/vocab/frbr/core#\",\n\n    \"Work\": \"fabio:Expression\",\n    \"Member\": \"schema:Organization\",\n    \"Journal\": \"fabio:Journal\",\n    \"Funder\": \"schema:Organization\",\n    \"Prefix\": \"schema:Thing\",\n    \"Type\": \"schema:Thing\",\n    \"License\": \"schema:CreativeWork\",\n\n    \"DOI\": {\n      \"@id\": \"prism:doi\",\n      \"@type\": \"@id\"\n    },\n    \"ISSN\": {\n      \"@id\": \"prism:issn\"\n    },\n    \"ISBN\": \"schema:isbn\",\n    \"title\": \"dc:title\",\n    \"container-title\": \"prism:publicationName\",\n    \"publisher\": \"schema:publisher\",\n    \"publisher-location\": \"schema:address\",\n    \"abstract\": \"dc:abstract\",\n  \
  \  \"subject\": \"dc:subject\",\n    \"type\": \"dc:type\",\n    \"URL\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"author\": {\n      \"@id\": \"dc:creator\",\n      \"@container\": \"@list\"\n    },\n    \"editor\": {\n      \"@id\": \"schema:editor\",\n      \"@container\": \"@list\"\n    },\n    \"translator\": {\n      \"@id\": \"schema:translator\",\n      \"@container\": \"@list\"\n    },\n    \"given\": \"schema:givenName\",\n    \"family\": \"schema:familyName\",\n    \"ORCID\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"@id\"\n    },\n    \"affiliation\": {\n      \"@id\": \"schema:affiliation\",\n      \"@container\": \"@set\"\n    },\n    \"ROR\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"@id\"\n    },\n\n    \"issued\": \"dc:issued\",\n    \"published\": \"schema:datePublished\",\n    \"published-print\": \"prism:publicationDate\",\n    \"published-online\": \"schema:datePublished\",\n    \"created\":\
  \ \"dc:created\",\n    \"deposited\": \"dc:dateSubmitted\",\n    \"indexed\": \"dc:date\",\n\n    \"volume\": \"prism:volume\",\n    \"issue\": \"prism:number\",\n    \"page\": \"prism:pageRange\",\n    \"article-number\": \"schema:position\",\n\n    \"reference\": {\n      \"@id\": \"dc:references\",\n      \"@container\": \"@set\"\n    },\n    \"is-referenced-by-count\": \"schema:citation\",\n    \"references-count\": \"schema:citation\",\n    \"score\": \"schema:ratingValue\",\n\n    \"funder\": {\n      \"@id\": \"schema:funder\",\n      \"@container\": \"@set\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@container\": \"@set\"\n    },\n    \"link\": \"schema:url\",\n    \"relation\": \"dc:relation\",\n\n    \"agency\": \"schema:Organization\",\n    \"member\": \"schema:Organization\",\n    \"prefix\": \"schema:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/json-ld/crossref-context.jsonld
tags:
- Citations
- DOI
- Funders
- Identifiers
- Journals
- Licenses
- Members
- Metadata
- Open Access
- ORCID
- Prefixes
- Publishers
- Reference Linking
- ROR
- Scholarly
- JSON-LD
- Linked Data
- Semantic Web
---
