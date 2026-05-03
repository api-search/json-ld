---
api_specs:
- filename: the-open-movie-database-openapi.yml
  format: yaml
  label: The Open Movie Database API
  slug: the-open-movie-database
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/openapi/the-open-movie-database-openapi.yml
class_count: 30
classes:
- Movie
- TVSeries
- TVEpisode
- Person
- Organization
- Rating
- Title
- Year
- Rated
- Runtime
- Genre
- Plot
- Language
- Country
- Awards
- Ratings
- Source
- Value
- Metascore
- imdbRating
- imdbVotes
- imdbID
- Type
- DVD
- BoxOffice
- totalSeasons
- seriesID
- Season
- Episode
- Response
context_file: json-ld/the-open-movie-database-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/json-ld/the-open-movie-database-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Open Movie Database from The Open Movie Database.
layout: jsonld
name: The Open Movie Database Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: omdb
  uri: https://omdbapi.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Released
  type: string
- container: ''
  name: Director
  type: schema:Person
- container: ''
  name: Writer
  type: schema:Person
- container: ''
  name: Actors
  type: schema:Person
- container: ''
  name: Poster
  type: reference
- container: ''
  name: Production
  type: schema:Organization
- container: ''
  name: Website
  type: reference
property_count: 7
provider_name: The Open Movie Database
provider_slug: the-open-movie-database
slug: the-open-movie-database-context
source_filename: the-open-movie-database-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"omdb\": \"https://omdbapi.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Movie\": \"schema:Movie\",\n    \"TVSeries\": \"schema:TVSeries\",\n    \"TVEpisode\": \"schema:TVEpisode\",\n    \"Person\": \"schema:Person\",\n    \"Organization\": \"schema:Organization\",\n    \"Rating\": \"schema:Rating\",\n\n    \"Title\": \"schema:name\",\n    \"Year\": \"schema:datePublished\",\n    \"Rated\": \"omdb:contentRating\",\n    \"Released\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:string\" },\n    \"Runtime\": \"schema:duration\",\n    \"Genre\": \"schema:genre\",\n    \"Director\": { \"@id\": \"schema:director\", \"@type\": \"schema:Person\" },\n    \"Writer\": { \"@id\": \"schema:author\", \"@type\": \"schema:Person\" },\n    \"Actors\": { \"@id\": \"schema:actor\", \"@type\": \"schema:Person\" },\n    \"Plot\": \"schema:description\",\n   \
  \ \"Language\": \"schema:inLanguage\",\n    \"Country\": \"schema:countryOfOrigin\",\n    \"Awards\": \"omdb:awards\",\n    \"Poster\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"Ratings\": \"schema:aggregateRating\",\n    \"Source\": \"schema:author\",\n    \"Value\": \"schema:ratingValue\",\n    \"Metascore\": \"omdb:metascore\",\n    \"imdbRating\": \"omdb:imdbRating\",\n    \"imdbVotes\": \"omdb:imdbVotes\",\n    \"imdbID\": \"schema:sameAs\",\n    \"Type\": \"schema:additionalType\",\n    \"DVD\": \"omdb:dvdReleaseDate\",\n    \"BoxOffice\": \"omdb:boxOffice\",\n    \"Production\": { \"@id\": \"schema:productionCompany\", \"@type\": \"schema:Organization\" },\n    \"Website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"totalSeasons\": \"schema:numberOfSeasons\",\n    \"seriesID\": \"omdb:seriesID\",\n    \"Season\": \"schema:seasonNumber\",\n    \"Episode\": \"schema:episodeNumber\",\n    \"Response\": \"omdb:response\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/json-ld/the-open-movie-database-context.jsonld
tags:
- Entertainment
- Movies
- Television
- IMDb
- Metadata
- JSON-LD
- Linked Data
- Semantic Web
---
