---
api_specs:
- filename: tmdb-api.json
  format: json
  label: The Movie Database API
  slug: the-movie-database
  spec_type: OpenAPI
  url: https://developer.themoviedb.org/openapi/tmdb-api.json
class_count: 0
classes: []
context_file: json-ld/the-movie-database-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/json-ld/the-movie-database-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Movie Database from The Movie Database.
layout: jsonld
name: The Movie Database Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tmdb
  uri: https://api.themoviedb.org/3/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Movie
  type: ''
- container: ''
  name: TVSeries
  type: ''
- container: ''
  name: TVSeason
  type: ''
- container: ''
  name: TVEpisode
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: id
  type: integer
- container: ''
  name: title
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: overview
  type: ''
- container: ''
  name: tagline
  type: ''
- container: ''
  name: release_date
  type: date
- container: ''
  name: first_air_date
  type: date
- container: ''
  name: last_air_date
  type: date
- container: ''
  name: runtime
  type: ''
- container: ''
  name: homepage
  type: reference
- container: ''
  name: imdb_id
  type: reference
- container: ''
  name: vote_average
  type: decimal
- container: ''
  name: vote_count
  type: integer
- container: ''
  name: popularity
  type: decimal
- container: ''
  name: adult
  type: boolean
- container: ''
  name: budget
  type: integer
- container: ''
  name: revenue
  type: integer
- container: ''
  name: poster_path
  type: ''
- container: ''
  name: backdrop_path
  type: ''
- container: set
  name: genres
  type: ''
- container: ''
  name: original_language
  type: ''
- container: set
  name: production_companies
  type: ''
- container: set
  name: keywords
  type: ''
- container: set
  name: recommendations
  type: ''
- container: set
  name: credits
  type: ''
- container: set
  name: seasons
  type: ''
- container: ''
  name: number_of_seasons
  type: integer
- container: ''
  name: number_of_episodes
  type: integer
property_count: 33
provider_name: The Movie Database
provider_slug: the-movie-database
slug: the-movie-database-context
source_filename: the-movie-database-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tmdb\": \"https://api.themoviedb.org/3/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Movie\": {\n      \"@id\": \"schema:Movie\"\n    },\n    \"TVSeries\": {\n      \"@id\": \"schema:TVSeries\"\n    },\n    \"TVSeason\": {\n      \"@id\": \"schema:TVSeason\"\n    },\n    \"TVEpisode\": {\n      \"@id\": \"schema:TVEpisode\"\n    },\n    \"Person\": {\n      \"@id\": \"schema:Person\"\n    },\n\n    \"id\": {\n      \"@id\": \"tmdb:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"overview\": {\n      \"@id\": \"schema:description\"\n    },\n    \"tagline\": {\n      \"@id\": \"schema:slogan\"\n    },\n    \"release_date\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\
  \n    },\n    \"first_air_date\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"last_air_date\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"runtime\": {\n      \"@id\": \"schema:duration\"\n    },\n    \"homepage\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"imdb_id\": {\n      \"@id\": \"schema:sameAs\",\n      \"@type\": \"@id\"\n    },\n    \"vote_average\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vote_count\": {\n      \"@id\": \"schema:ratingCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"popularity\": {\n      \"@id\": \"tmdb:popularity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"adult\": {\n      \"@id\": \"schema:isFamilyFriendly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"budget\": {\n      \"@id\": \"tmdb:budget\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"revenue\": {\n      \"@id\"\
  : \"tmdb:revenue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"poster_path\": {\n      \"@id\": \"schema:image\"\n    },\n    \"backdrop_path\": {\n      \"@id\": \"schema:image\"\n    },\n    \"genres\": {\n      \"@id\": \"schema:genre\",\n      \"@container\": \"@set\"\n    },\n    \"original_language\": {\n      \"@id\": \"schema:inLanguage\"\n    },\n    \"production_companies\": {\n      \"@id\": \"schema:productionCompany\",\n      \"@container\": \"@set\"\n    },\n    \"keywords\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"recommendations\": {\n      \"@id\": \"schema:significantLink\",\n      \"@container\": \"@set\"\n    },\n    \"credits\": {\n      \"@id\": \"schema:actor\",\n      \"@container\": \"@set\"\n    },\n    \"seasons\": {\n      \"@id\": \"schema:containsSeason\",\n      \"@container\": \"@set\"\n    },\n    \"number_of_seasons\": {\n      \"@id\": \"schema:numberOfSeasons\",\n      \"@type\": \"xsd:integer\"\n \
  \   },\n    \"number_of_episodes\": {\n      \"@id\": \"schema:numberOfEpisodes\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/json-ld/the-movie-database-context.jsonld
tags:
- Entertainment
- Movies
- Television
- JSON-LD
- Linked Data
- Semantic Web
---
