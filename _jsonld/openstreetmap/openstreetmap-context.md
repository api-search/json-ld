---
api_specs:
- filename: openstreetmap-main-openapi.yml
  format: yaml
  label: OpenStreetMap Main Editing API v0.6
  slug: main-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml
- filename: openstreetmap-nominatim-openapi.yml
  format: yaml
  label: OpenStreetMap Nominatim Geocoding API
  slug: nominatim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml
class_count: 21
classes:
- Node
- id
- user
- Way
- Relation
- role
- Changeset
- display_name
- osm_type
- osm_id
- class
- Address
- house_number
- road
- city
- state
- postcode
- country
- country_code
- Note
- place_id
context_file: json-ld/openstreetmap-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openstreetmap from OpenStreetMap.
layout: jsonld
name: Openstreetmap Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: osm
  uri: https://www.openstreetmap.org/ontology/
- prefix: geojson
  uri: https://purl.org/geojson/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: lat
  type: decimal
- container: ''
  name: lon
  type: decimal
- container: index
  name: tags
  type: ''
- container: ''
  name: version
  type: integer
- container: ''
  name: changeset
  type: integer
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: uid
  type: integer
- container: ''
  name: visible
  type: boolean
- container: list
  name: nodes
  type: ''
- container: set
  name: members
  type: ''
- container: ''
  name: Nominatim
  type: ''
- container: ''
  name: importance
  type: decimal
- container: ''
  name: boundingbox
  type: schema:GeoShape
property_count: 13
provider_name: OpenStreetMap
provider_slug: openstreetmap
slug: openstreetmap-context
source_filename: openstreetmap-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"osm\": \"https://www.openstreetmap.org/ontology/\",\n    \"geojson\": \"https://purl.org/geojson/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Node\": \"schema:Place\",\n    \"id\": \"schema:identifier\",\n    \"lat\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lon\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@container\": \"@index\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"changeset\": {\n      \"@id\": \"osm:changeset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"user\": \"schema:author\"\
  ,\n    \"uid\": {\n      \"@id\": \"osm:userId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"visible\": {\n      \"@id\": \"schema:activeStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Way\": \"schema:GeoShape\",\n    \"nodes\": {\n      \"@id\": \"osm:nodeRefs\",\n      \"@container\": \"@list\"\n    },\n    \"Relation\": \"schema:Collection\",\n    \"members\": {\n      \"@id\": \"schema:hasPart\",\n      \"@container\": \"@set\"\n    },\n    \"role\": \"schema:roleName\",\n    \"Changeset\": \"schema:UpdateAction\",\n    \"Nominatim\": {\n      \"@id\": \"schema:SearchResultsPage\"\n    },\n    \"display_name\": \"schema:name\",\n    \"osm_type\": \"osm:elementType\",\n    \"osm_id\": \"osm:elementId\",\n    \"class\": \"osm:osmClass\",\n    \"importance\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Address\": \"schema:PostalAddress\",\n    \"house_number\": \"schema:streetAddress\",\n    \"road\": \"schema:streetAddress\"\
  ,\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postcode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"country_code\": \"schema:addressCountry\",\n    \"Note\": \"schema:Comment\",\n    \"place_id\": \"schema:identifier\",\n    \"boundingbox\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"schema:GeoShape\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld
tags:
- Geospatial
- Mapping
- Open Data
- Geocoding
- Editing
- JSON-LD
- Linked Data
- Semantic Web
---
