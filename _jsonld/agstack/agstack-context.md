---
api_specs:
- filename: agstack-openagri-weather-service-openapi.yml
  format: yaml
  label: OpenAgri Weather Service
  slug: openagri-weather-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/openapi/agstack-openagri-weather-service-openapi.yml
- filename: agstack-openagri-farm-calendar-openapi.yml
  format: yaml
  label: OpenAgri Farm Calendar
  slug: openagri-farm-calendar
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/openapi/agstack-openagri-farm-calendar-openapi.yml
- filename: agstack-asset-registry-openapi.yml
  format: yaml
  label: AgStack Asset Registry
  slug: asset-registry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/openapi/agstack-asset-registry-openapi.yml
class_count: 30
classes:
- Asset
- FieldBoundary
- GeoId
- WeatherForecast
- FarmCalendar
- FarmOperation
- AgriculturalMachine
- Parcel
- id
- type
- geo_id
- boundary
- coordinates
- wkt
- centroid
- overlap_percentage
- humidity
- wind_speed
- cloud_coverage
- thi
- title
- description
- farm
- parcel
- activity_type
- product
- quantity
- unit
- operator
- notes
context_file: json-ld/agstack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/json-ld/agstack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agstack from AgStack Foundation.
layout: jsonld
name: Agstack Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: agstack
  uri: https://agstack.org/vocab/
- prefix: ocsm
  uri: https://openagri.eu/vocab/ocsm/
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: lat
  type: float
- container: ''
  name: lon
  type: float
- container: ''
  name: temperature
  type: float
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: date
  type: date
property_count: 6
provider_name: AgStack Foundation
provider_slug: agstack
slug: agstack-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"agstack\": \"https://agstack.org/vocab/\",\n    \"ocsm\": \"https://openagri.eu/vocab/ocsm/\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Asset\": \"agstack:Asset\",\n    \"FieldBoundary\": \"agstack:FieldBoundary\",\n    \"GeoId\": \"agstack:GeoId\",\n    \"WeatherForecast\": \"ocsm:WeatherForecast\",\n    \"FarmCalendar\": \"ocsm:FarmCalendar\",\n    \"FarmOperation\": \"ocsm:FarmOperation\",\n    \"AgriculturalMachine\": \"ocsm:AgriculturalMachine\",\n    \"Parcel\": \"ocsm:Parcel\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"geo_id\": \"agstack:geoId\",\n    \"boundary\": \"geo:hasGeometry\",\n    \"coordinates\": \"geo:coordinates\",\n    \"wkt\": \"geo:asWKT\",\n    \"centroid\": \"agstack:centroid\",\n    \"overlap_percentage\": \"agstack:overlapPercentage\"\
  ,\n\n    \"lat\": {\"@id\": \"schema:latitude\", \"@type\": \"xsd:float\"},\n    \"lon\": {\"@id\": \"schema:longitude\", \"@type\": \"xsd:float\"},\n    \"temperature\": {\"@id\": \"schema:temperature\", \"@type\": \"xsd:float\"},\n    \"humidity\": \"ocsm:humidity\",\n    \"wind_speed\": \"ocsm:windSpeed\",\n    \"cloud_coverage\": \"ocsm:cloudCoverage\",\n    \"thi\": \"agstack:temperatureHumidityIndex\",\n\n    \"title\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"created_at\": {\"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\"},\n    \"updated_at\": {\"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\"},\n    \"date\": {\"@id\": \"dcterms:date\", \"@type\": \"xsd:date\"},\n\n    \"farm\": \"ocsm:farm\",\n    \"parcel\": \"ocsm:parcel\",\n    \"activity_type\": \"ocsm:activityType\",\n    \"product\": \"ocsm:product\",\n    \"quantity\": \"schema:quantity\",\n    \"unit\": \"schema:unitCode\",\n    \"operator\": \"schema:agent\",\n    \"\
  notes\": \"ocsm:notes\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/json-ld/agstack-context.jsonld
tags:
- Agriculture
- Linux Foundation
- Open Source
- Geospatial
- Precision Agriculture
- Linked Data
- JSON-LD
- Linked Data
- Semantic Web
---
