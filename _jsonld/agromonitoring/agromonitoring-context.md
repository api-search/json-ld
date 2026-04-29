---
api_specs:
- filename: agromonitoring-openapi.yml
  format: yaml
  label: Agromonitoring
  slug: agromonitoring
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/openapi/agromonitoring-openapi.yml
class_count: 33
classes:
- Polygon
- SatelliteImage
- NdviRecord
- WeatherData
- SoilData
- UvIndexData
- id
- name
- geo_json
- coordinates
- resolution
- coverage
- cloud_coverage
- ndvi
- evi
- evi2
- nri
- dswi
- lswi
- temp
- feels_like
- temp_min
- temp_max
- pressure
- humidity
- wind_speed
- wind_deg
- clouds
- description
- t0
- t10
- moisture
- uvi
context_file: json-ld/agromonitoring-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/json-ld/agromonitoring-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agromonitoring from Agromonitoring.
layout: jsonld
name: Agromonitoring Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: agro
  uri: https://api.agromonitoring.com/vocab/
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: valid_time_start
  type: dateTime
- container: ''
  name: valid_time_end
  type: dateTime
- container: ''
  name: image_time
  type: dateTime
- container: ''
  name: dt
  type: dateTime
property_count: 6
provider_name: Agromonitoring
provider_slug: agromonitoring
slug: agromonitoring-context
source_filename: agromonitoring-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"agro\": \"https://api.agromonitoring.com/vocab/\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n\n    \"Polygon\": \"agro:Polygon\",\n    \"SatelliteImage\": \"agro:SatelliteImage\",\n    \"NdviRecord\": \"agro:NdviRecord\",\n    \"WeatherData\": \"agro:WeatherData\",\n    \"SoilData\": \"agro:SoilData\",\n    \"UvIndexData\": \"agro:UvIndexData\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"created_at\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updated_at\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"geo_json\": \"geo:hasGeometry\",\n    \"coordinates\": \"geo:coordinates\",\n\n    \"valid_time_start\": {\"@id\": \"agro:validTimeStart\", \"@type\": \"xsd:dateTime\"},\n    \"valid_time_end\": {\"@id\": \"agro:validTimeEnd\", \"@type\": \"xsd:dateTime\"\
  },\n    \"resolution\": \"agro:resolution\",\n    \"coverage\": \"agro:coverage\",\n    \"image_time\": {\"@id\": \"agro:imageTime\", \"@type\": \"xsd:dateTime\"},\n    \"cloud_coverage\": \"agro:cloudCoverage\",\n\n    \"ndvi\": \"agro:ndvi\",\n    \"evi\": \"agro:evi\",\n    \"evi2\": \"agro:evi2\",\n    \"nri\": \"agro:nri\",\n    \"dswi\": \"agro:dswi\",\n    \"lswi\": \"agro:lswi\",\n    \"dt\": {\"@id\": \"agro:timestamp\", \"@type\": \"xsd:dateTime\"},\n\n    \"temp\": \"schema:temperature\",\n    \"feels_like\": \"agro:feelsLike\",\n    \"temp_min\": \"agro:tempMin\",\n    \"temp_max\": \"agro:tempMax\",\n    \"pressure\": \"agro:pressure\",\n    \"humidity\": \"agro:humidity\",\n    \"wind_speed\": \"agro:windSpeed\",\n    \"wind_deg\": \"agro:windDirection\",\n    \"clouds\": \"agro:cloudCover\",\n    \"description\": \"schema:description\",\n\n    \"t0\": \"agro:soilTempSurface\",\n    \"t10\": \"agro:soilTemp10cm\",\n    \"moisture\": \"agro:soilMoisture\",\n\n    \"uvi\":\
  \ \"agro:uvIndex\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/json-ld/agromonitoring-context.jsonld
tags:
- Agriculture
- Satellite Imagery
- Vegetation Indices
- Weather
- Precision Agriculture
- Remote Sensing
- JSON-LD
- Linked Data
- Semantic Web
---
