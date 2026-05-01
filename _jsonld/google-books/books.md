---
api_specs:
- filename: books.yml
  format: yaml
  label: Google Books API V1
  slug: google-books
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-books/refs/heads/main/openapi/books.yml
class_count: 21
classes:
- Volume
- Bookshelf
- id
- title
- subtitle
- authors
- publisher
- publishedDate
- description
- pageCount
- categories
- averageRating
- ratingsCount
- language
- imageLinks
- thumbnail
- isbn
- saleability
- isEbook
- listPrice
- currencyCode
context_file: json-ld/books.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-books/refs/heads/main/json-ld/books.jsonld
description: JSON-LD context defining the semantic vocabulary for Books from Google Books.
layout: jsonld
name: Books Context
namespaces:
- prefix: gbooks
  uri: https://www.googleapis.com/books/v1/
properties:
- container: ''
  name: previewLink
  type: reference
property_count: 1
provider_name: Google Books
provider_slug: google-books
slug: books
source_filename: books.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gbooks\": \"https://www.googleapis.com/books/v1/\",\n    \"Volume\": \"schema:Book\",\n    \"Bookshelf\": \"schema:BookSeries\",\n    \"id\": \"schema:identifier\",\n    \"title\": \"schema:name\",\n    \"subtitle\": \"schema:alternativeHeadline\",\n    \"authors\": \"schema:author\",\n    \"publisher\": \"schema:publisher\",\n    \"publishedDate\": \"schema:datePublished\",\n    \"description\": \"schema:description\",\n    \"pageCount\": \"schema:numberOfPages\",\n    \"categories\": \"schema:genre\",\n    \"averageRating\": \"schema:aggregateRating\",\n    \"ratingsCount\": \"schema:ratingCount\",\n    \"language\": \"schema:inLanguage\",\n    \"imageLinks\": \"schema:image\",\n    \"thumbnail\": \"schema:thumbnailUrl\",\n    \"previewLink\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"isbn\": \"schema:isbn\",\n    \"saleability\": \"schema:availability\",\n    \"isEbook\"\
  : \"schema:bookFormat\",\n    \"listPrice\": \"schema:price\",\n    \"currencyCode\": \"schema:priceCurrency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-books/refs/heads/main/json-ld/books.jsonld
tags:
- Books
- eBooks
- Google
- Library
- Publishing
- Reading
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
