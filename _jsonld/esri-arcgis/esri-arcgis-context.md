---
api_specs:
- filename: esri-arcgis-platform-openapi.yml
  format: yaml
  label: ESRI ArcGIS Platform API
  slug: esri-arcgis-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/esri-arcgis/refs/heads/main/openapi/esri-arcgis-platform-openapi.yml
class_count: 33
classes:
- Feature
- FeatureService
- PortalItem
- placeId
- itemId
- username
- name
- title
- description
- thumbnail
- url
- email
- fullName
- firstName
- lastName
- created
- modified
- tags
- streetAddress
- locality
- region
- postcode
- country
- categoryId
- label
- telephone
- website
- score
- access
- numViews
- extent
- spatialReference
- wkid
context_file: json-ld/esri-arcgis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/esri-arcgis/refs/heads/main/json-ld/esri-arcgis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Esri Arcgis from ESRI ArcGIS.
layout: jsonld
name: Esri Arcgis Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: geonames
  uri: http://www.geonames.org/ontology#
- prefix: esri
  uri: https://developers.arcgis.com/rest/vocabulary/
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Place
  type: reference
- container: ''
  name: User
  type: reference
- container: ''
  name: Organization
  type: reference
- container: ''
  name: location
  type: schema:GeoCoordinates
- container: ''
  name: x
  type: decimal
- container: ''
  name: y
  type: decimal
- container: ''
  name: z
  type: decimal
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: categories
  type: reference
- container: ''
  name: distance
  type: decimal
property_count: 10
provider_name: ESRI ArcGIS
provider_slug: esri-arcgis
slug: esri-arcgis-context
source_filename: esri-arcgis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"geonames\": \"http://www.geonames.org/ontology#\",\n    \"esri\": \"https://developers.arcgis.com/rest/vocabulary/\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"Feature\": \"esri:Feature\",\n    \"FeatureService\": \"esri:FeatureService\",\n    \"PortalItem\": \"esri:PortalItem\",\n    \"Place\": {\n      \"@id\": \"schema:Place\",\n      \"@type\": \"@id\"\n    },\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n\n    \"placeId\": \"@id\",\n    \"itemId\": \"@id\",\n    \"username\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"thumbnail\": \"schema:image\",\n    \"url\": \"schema:url\"\
  ,\n    \"email\": \"schema:email\",\n    \"fullName\": \"schema:name\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\",\n    \"tags\": \"schema:keywords\",\n\n    \"location\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"schema:GeoCoordinates\"\n    },\n    \"x\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"y\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"z\": {\n      \"@id\": \"schema:elevation\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"streetAddress\": \"schema:streetAddress\",\n    \"locality\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"postcode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\"\
  ,\n\n    \"categories\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"@id\"\n    },\n    \"categoryId\": \"@id\",\n    \"label\": \"schema:name\",\n\n    \"telephone\": \"schema:telephone\",\n    \"website\": \"schema:url\",\n\n    \"distance\": {\n      \"@id\": \"schema:distance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"score\": \"esri:matchScore\",\n    \"access\": \"schema:accessibilityFeature\",\n    \"numViews\": \"schema:interactionCount\",\n\n    \"extent\": \"schema:spatialCoverage\",\n    \"spatialReference\": \"esri:spatialReference\",\n    \"wkid\": \"esri:wkid\",\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/esri-arcgis/refs/heads/main/json-ld/esri-arcgis-context.jsonld
tags:
- GIS
- Geospatial
- Mapping
- Location
- Spatial Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
