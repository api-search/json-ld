---
api_specs:
- filename: common-sense-media-reviews-api-openapi.yml
  format: yaml
  label: Common Sense Media Reviews API
  slug: common-sense-media-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/openapi/common-sense-media-reviews-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/common-sense-media-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/json-ld/common-sense-media-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Common Sense Media from Common Sense Media.
layout: jsonld
name: Common Sense Media Context
namespaces:
- prefix: csm
  uri: https://commonsensemedia.org/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Review
  type: ''
- container: ''
  name: Movie
  type: ''
- container: ''
  name: TVShow
  type: ''
- container: ''
  name: Book
  type: ''
- container: ''
  name: Game
  type: ''
- container: ''
  name: App
  type: ''
- container: ''
  name: Podcast
  type: ''
- container: ''
  name: ContentGridItem
  type: ''
property_count: 8
provider_name: Common Sense Media
provider_slug: common-sense-media
slug: common-sense-media-context
source_filename: common-sense-media-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"csm\": \"https://commonsensemedia.org/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Review\": {\n      \"@id\": \"schema:Review\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"url\": \"schema:url\",\n        \"title\": \"schema:name\",\n        \"mediaType\": \"csm:mediaType\",\n        \"ageRating\": \"csm:ageRating\",\n        \"ageRatingGroup\": \"csm:ageRatingGroup\",\n        \"stars\": {\n          \"@id\": \"schema:reviewRating\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"oneLiner\": \"schema:headline\",\n        \"parentsNeedToKnow\": \"csm:parentsNeedToKnow\",\n        \"description\": \"schema:reviewBody\",\n        \"anyGood\": \"csm:anyGood\",\n        \"talkingPoints\": \"csm:talkingPoints\",\n        \"contentGrid\": \"csm:contentGrid\",\n        \"updated\": {\n          \"@id\": \"schema:dateModified\",\n \
  \         \"@type\": \"xsd:dateTime\"\n        },\n        \"langcode\": \"schema:inLanguage\"\n      }\n    },\n\n    \"Movie\": {\n      \"@id\": \"schema:Movie\",\n      \"@context\": {\n        \"cast\": \"schema:actor\",\n        \"directors\": \"schema:director\",\n        \"studios\": \"schema:productionCompany\",\n        \"genres\": \"schema:genre\",\n        \"rating\": \"schema:contentRating\",\n        \"length\": \"schema:duration\"\n      }\n    },\n\n    \"TVShow\": {\n      \"@id\": \"schema:TVSeries\",\n      \"@context\": {\n        \"cast\": \"schema:actor\",\n        \"networks\": \"schema:productionCompany\",\n        \"genres\": \"schema:genre\",\n        \"rating\": \"schema:contentRating\"\n      }\n    },\n\n    \"Book\": {\n      \"@id\": \"schema:Book\",\n      \"@context\": {\n        \"authors\": \"schema:author\",\n        \"illustrators\": \"schema:illustrator\",\n        \"publishers\": \"schema:publisher\",\n        \"genres\": \"schema:genre\",\n     \
  \   \"length\": \"schema:numberOfPages\"\n      }\n    },\n\n    \"Game\": {\n      \"@id\": \"schema:VideoGame\",\n      \"@context\": {\n        \"developers\": \"schema:gamePlatform\",\n        \"genres\": \"schema:genre\",\n        \"rating\": \"schema:contentRating\"\n      }\n    },\n\n    \"App\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"developers\": \"schema:author\",\n        \"genres\": \"schema:applicationCategory\"\n      }\n    },\n\n    \"Podcast\": {\n      \"@id\": \"schema:PodcastSeries\",\n      \"@context\": {\n        \"hosts\": \"schema:author\",\n        \"publishers\": \"schema:publisher\",\n        \"genres\": \"schema:genre\"\n      }\n    },\n\n    \"ContentGridItem\": {\n      \"@id\": \"csm:ContentGridItem\",\n      \"@context\": {\n        \"rating\": \"csm:gridRating\",\n        \"label\": \"schema:name\",\n        \"text\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/json-ld/common-sense-media-context.jsonld
tags:
- Apps
- Books
- Media
- Movies
- Non-Profit
- Podcasts
- Ratings
- Reviews
- Television
- Video Games
- YouTube
- JSON-LD
- Linked Data
- Semantic Web
---
