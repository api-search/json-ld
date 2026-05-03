---
api_specs:
- filename: tripadvisor-content-api-openapi.yml
  format: yaml
  label: Tripadvisor Content API
  slug: content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/openapi/tripadvisor-content-api-openapi.yml
- filename: tripadvisor-hotel-availability-check-api-openapi.yml
  format: yaml
  label: Tripadvisor Hotel Availability Check API
  slug: hotel-availability-check-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/openapi/tripadvisor-hotel-availability-check-api-openapi.yml
- filename: tripadvisor-hotel-availability-check-api-openapi.yml
  format: yaml
  label: Tripadvisor Hotel Inventory API
  slug: hotel-inventory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/openapi/tripadvisor-hotel-availability-check-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/tripadvisor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/json-ld/tripadvisor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tripadvisor from Tripadvisor.
layout: jsonld
name: Tripadvisor Context
namespaces:
- prefix: ta
  uri: https://developer-tripadvisor.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Location
  type: ''
- container: ''
  name: Hotel
  type: ''
- container: ''
  name: Review
  type: ''
- container: ''
  name: Photo
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: Award
  type: ''
- container: ''
  name: User
  type: ''
property_count: 7
provider_name: Tripadvisor
provider_slug: tripadvisor
slug: tripadvisor-context
source_filename: tripadvisor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ta\": \"https://developer-tripadvisor.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"location_id\": \"ta:locationId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"web_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"website\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"@id\"\n        },\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"phone\": \"schema:telephone\",\n        \"rating\": {\n          \"@id\": \"schema:aggregateRating\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"num_reviews\": {\n          \"@id\": \"schema:reviewCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"price_level\": \"schema:priceRange\",\n        \"timezone\": \"ta:timezone\",\n        \"photo_count\": {\n          \"@id\": \"ta:photoCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"address_obj\": \"schema:address\",\n        \"category\": \"schema:additionalType\",\n        \"cuisine\": {\n          \"@id\": \"schema:servesCuisine\",\n          \"@container\": \"@set\"\n        },\n        \"hours\": \"schema:openingHoursSpecification\",\n        \"awards\": {\n          \"@id\": \"ta:awards\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Hotel\": {\n      \"@id\": \"schema:Hotel\",\n      \"@context\": {\n        \"ta_id\": \"ta:tripadvisorId\",\n        \"partner_id\": \"ta:partnerId\",\n        \"name\": \"schema:name\",\n        \"street\": \"schema:streetAddress\"\
  ,\n        \"city\": \"schema:addressLocality\",\n        \"postal\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n\n    \"Review\": {\n      \"@id\": \"schema:Review\",\n      \"@context\": {\n        \"id\": \"ta:reviewId\",\n        \"title\": \"schema:headline\",\n        \"text\": \"schema:reviewBody\",\n        \"rating\": {\n          \"@id\": \"schema:reviewRating\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"published_date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"travel_date\": {\n          \"@id\": \"ta:travelDate\",\n          \"@type\": \"xsd:gYearMonth\"\n        },\n        \"trip_type\": \"ta:tripType\",\n        \"lang\": \"schema:inLanguage\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"helpful_votes\": {\n          \"@id\": \"schema:upvoteCount\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"user\": \"schema:author\"\n      }\n    },\n\n    \"Photo\": {\n      \"@id\": \"schema:ImageObject\",\n      \"@context\": {\n        \"id\": \"ta:photoId\",\n        \"caption\": \"schema:caption\",\n        \"published_date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"images\": \"schema:image\",\n        \"album\": \"ta:album\",\n        \"user\": \"schema:author\"\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"street1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"postalcode\": \"schema:postalCode\",\n        \"address_string\": \"schema:name\"\n      }\n    },\n\n    \"Award\": {\n      \"@id\": \"ta:Award\",\n      \"@context\": {\n        \"award_type\": \"ta:awardType\",\n        \"year\": {\n\
  \          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:gYear\"\n        },\n        \"display_name\": \"schema:name\",\n        \"images\": \"schema:image\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"username\": \"schema:name\",\n        \"avatar\": \"schema:image\",\n        \"user_location\": \"schema:homeLocation\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/json-ld/tripadvisor-context.jsonld
tags:
- Attractions
- Hotels
- Hospitality
- Restaurants
- Reviews
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
