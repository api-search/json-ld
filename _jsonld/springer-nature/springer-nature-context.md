---
api_specs:
- filename: springer-nature-meta-openapi.yml
  format: yaml
  label: Springer Nature Meta API
  slug: springer-nature-meta-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/springer-nature/refs/heads/main/openapi/springer-nature-meta-openapi.yml
- filename: springer-nature-openaccess-openapi.yml
  format: yaml
  label: Springer Nature Open Access API
  slug: springer-nature-openaccess-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/springer-nature/refs/heads/main/openapi/springer-nature-openaccess-openapi.yml
class_count: 21
classes:
- name
- description
- url
- ScholarlyArticle
- Book
- Chapter
- Journal
- Person
- Organization
- title
- creator
- publisher
- subject
- description_dc
- identifier
- date
- rights
- language
- familyName
- givenName
- affiliation
context_file: json-ld/springer-nature-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/springer-nature/refs/heads/main/json-ld/springer-nature-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Springer Nature from Springer Nature.
layout: jsonld
name: Springer Nature Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: bibo
  uri: http://purl.org/ontology/bibo/
- prefix: dc
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: springer
  uri: https://api.springernature.com/vocab/
properties:
- container: ''
  name: abstract
  type: ''
- container: ''
  name: doi
  type: ''
- container: ''
  name: issn
  type: ''
- container: ''
  name: eissn
  type: ''
- container: ''
  name: isbn
  type: ''
- container: ''
  name: volume
  type: ''
- container: ''
  name: issue
  type: ''
- container: ''
  name: pageStart
  type: ''
- container: ''
  name: pageEnd
  type: ''
- container: ''
  name: publicationDate
  type: ''
- container: ''
  name: onlineDate
  type: ''
- container: ''
  name: openAccess
  type: ''
- container: ''
  name: license
  type: ''
- container: ''
  name: keyword
  type: ''
- container: ''
  name: ORCID
  type: ''
property_count: 15
provider_name: Springer Nature
provider_slug: springer-nature
slug: springer-nature-context
source_filename: springer-nature-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"bibo\": \"http://purl.org/ontology/bibo/\",\n    \"dc\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"springer\": \"https://api.springernature.com/vocab/\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"ScholarlyArticle\": \"schema:ScholarlyArticle\",\n    \"Book\": \"schema:Book\",\n    \"Chapter\": \"bibo:Chapter\",\n    \"Journal\": \"bibo:Journal\",\n    \"Person\": \"schema:Person\",\n    \"Organization\": \"schema:Organization\",\n\n    \"title\": \"dc:title\",\n    \"creator\": \"dc:creator\",\n    \"publisher\": \"dc:publisher\",\n    \"subject\": \"dc:subject\",\n    \"description_dc\": \"dc:description\",\n    \"identifier\": \"dc:identifier\",\n    \"date\": \"dc:date\",\n    \"rights\": \"dc:rights\",\n    \"language\": \"dc:language\",\n    \"abstract\": { \"\
  @id\": \"dc:abstract\" },\n\n    \"doi\": { \"@id\": \"bibo:doi\" },\n    \"issn\": { \"@id\": \"bibo:issn\" },\n    \"eissn\": { \"@id\": \"springer:eissn\" },\n    \"isbn\": { \"@id\": \"bibo:isbn\" },\n    \"volume\": { \"@id\": \"bibo:volume\" },\n    \"issue\": { \"@id\": \"bibo:issue\" },\n    \"pageStart\": { \"@id\": \"schema:pageStart\" },\n    \"pageEnd\": { \"@id\": \"schema:pageEnd\" },\n    \"publicationDate\": { \"@id\": \"dc:date\" },\n    \"onlineDate\": { \"@id\": \"schema:datePublished\" },\n\n    \"openAccess\": { \"@id\": \"schema:isAccessibleForFree\" },\n    \"license\": { \"@id\": \"schema:license\" },\n    \"keyword\": { \"@id\": \"schema:keywords\" },\n\n    \"ORCID\": { \"@id\": \"https://orcid.org/\" },\n    \"familyName\": \"schema:familyName\",\n    \"givenName\": \"schema:givenName\",\n    \"affiliation\": \"schema:affiliation\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/springer-nature/refs/heads/main/json-ld/springer-nature-context.jsonld
tags:
- Academic Publishing
- Open Access
- Research
- Scholarly Content
- Scientific Publishing
- JSON-LD
- Linked Data
- Semantic Web
---
