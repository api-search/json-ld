---
api_specs:
- filename: new-york-times-archive-openapi-original.yml
  format: yaml
  label: The New York Times Archive API
  slug: archive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-archive-openapi-original.yml
- filename: new-york-times-article-search-openapi-original.yml
  format: yaml
  label: The New York Times Article Search API
  slug: article-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-article-search-openapi-original.yml
- filename: new-york-times-books-openapi-original.yml
  format: yaml
  label: The New York Times Books API
  slug: books-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-books-openapi-original.yml
- filename: new-york-times-most-popular-openapi-original.yml
  format: yaml
  label: The New York Times Most Popular API
  slug: most-popular
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-most-popular-openapi-original.yml
- filename: new-york-times-movie-review-openapi-original.yml
  format: yaml
  label: The New York Times Movie Reviews API
  slug: movie-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-movie-review-openapi-original.yml
- filename: new-york-times-semantic-openapi-original.yml
  format: yaml
  label: The New York Times Semantic API
  slug: semantic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-semantic-openapi-original.yml
- filename: new-york-times-times-tags-openapi-original.yml
  format: yaml
  label: The New York Times TimesTags API
  slug: timestags-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-times-tags-openapi-original.yml
- filename: new-york-times-times-newswire-openapi-original.yml
  format: yaml
  label: The New York Times Times Newswire API
  slug: times-newswire-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-times-newswire-openapi-original.yml
- filename: new-york-times-top-stories-openapi-original.yml
  format: yaml
  label: The New York Times Top Stories API
  slug: top-stories
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-top-stories-openapi-original.yml
class_count: 40
classes:
- Article
- Book
- Review
- Person
- Organization
- Place
- abstract
- headline
- lead_paragraph
- snippet
- source
- section_name
- subsection_name
- word_count
- byline
- news_desk
- document_type
- type_of_material
- print_page
- _id
- keywords
- multimedia
- title
- author
- publisher
- description
- isbn10
- isbn13
- price
- contributor
- concept_name
- concept_type
- concept_status
- concept_uri
- is_times_tag
- vernacular
- review_text
- critics_pick
- opening_date
- reviewer
context_file: json-ld/the-new-york-times-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/json-ld/the-new-york-times-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The New York Times from The New York Times.
layout: jsonld
name: The New York Times Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: nyt
  uri: https://developer.nytimes.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: web_url
  type: reference
- container: ''
  name: pub_date
  type: dateTime
property_count: 2
provider_name: The New York Times
provider_slug: the-new-york-times
slug: the-new-york-times-context
source_filename: the-new-york-times-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"nyt\": \"https://developer.nytimes.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Article\": \"schema:NewsArticle\",\n    \"Book\": \"schema:Book\",\n    \"Review\": \"schema:Review\",\n    \"Person\": \"schema:Person\",\n    \"Organization\": \"schema:Organization\",\n    \"Place\": \"schema:Place\",\n\n    \"web_url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"abstract\": \"schema:abstract\",\n    \"headline\": \"schema:headline\",\n    \"lead_paragraph\": \"schema:articleBody\",\n    \"snippet\": \"schema:description\",\n    \"pub_date\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n    \"source\": \"schema:publisher\",\n    \"section_name\": \"schema:articleSection\",\n    \"subsection_name\": \"nyt:subsection\",\n    \"word_count\": \"schema:wordCount\",\n    \"byline\": \"schema:author\",\n    \"news_desk\"\
  : \"nyt:newsDesk\",\n    \"document_type\": \"schema:additionalType\",\n    \"type_of_material\": \"nyt:typeOfMaterial\",\n    \"print_page\": \"nyt:printPage\",\n    \"_id\": \"schema:identifier\",\n    \"keywords\": \"schema:keywords\",\n    \"multimedia\": \"schema:image\",\n\n    \"title\": \"schema:name\",\n    \"author\": \"schema:author\",\n    \"publisher\": \"schema:publisher\",\n    \"description\": \"schema:description\",\n    \"isbn10\": \"schema:isbn\",\n    \"isbn13\": \"schema:isbn\",\n    \"price\": \"schema:price\",\n    \"contributor\": \"schema:contributor\",\n\n    \"concept_name\": \"schema:name\",\n    \"concept_type\": \"nyt:conceptType\",\n    \"concept_status\": \"schema:status\",\n    \"concept_uri\": \"schema:url\",\n    \"is_times_tag\": \"nyt:isTimesTag\",\n    \"vernacular\": \"schema:alternateName\",\n\n    \"review_text\": \"schema:reviewBody\",\n    \"critics_pick\": \"nyt:criticsPick\",\n    \"opening_date\": \"schema:startDate\",\n    \"reviewer\": \"\
  schema:author\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/json-ld/the-new-york-times-context.jsonld
tags:
- Articles
- Books
- Movies
- News
- Media
- Publishing
- Journalism
- JSON-LD
- Linked Data
- Semantic Web
---
