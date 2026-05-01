---
api_specs:
- filename: dtn-weather-conditions-openapi.yml
  format: yaml
  label: DTN Weather Conditions API
  slug: dtn-weather-conditions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/openapi/dtn-weather-conditions-openapi.yml
class_count: 2
classes:
- stationId
- stationName
context_file: json-ld/dtn-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/json-ld/dtn-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dtn from dtn.
layout: jsonld
name: Dtn Context
namespaces:
- prefix: dtn
  uri: https://point-observation.weather.mg/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
properties:
- container: ''
  name: WeatherObservation
  type: schema:Observation
- container: ''
  name: Station
  type: schema:Place
- container: ''
  name: WeatherForecast
  type: schema:Forecast
- container: ''
  name: observedAt
  type: dateTime
- container: ''
  name: location
  type: ''
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: elevationInMeter
  type: double
- container: ''
  name: airTemperatureInCelsius
  type: schema:QuantitativeValue
- container: ''
  name: relativeHumidityInPercent
  type: schema:QuantitativeValue
- container: ''
  name: windSpeedInMeterPerSecond
  type: schema:QuantitativeValue
- container: ''
  name: windDirectionInDegree
  type: schema:QuantitativeValue
- container: ''
  name: precipitationAmountInMillimeter
  type: schema:QuantitativeValue
- container: ''
  name: pressureInHectopascal
  type: schema:QuantitativeValue
- container: ''
  name: dewPointInCelsius
  type: ''
- container: ''
  name: feelsLikeTemperatureInCelsius
  type: ''
- container: ''
  name: uvIndex
  type: integer
- container: ''
  name: weatherSymbol
  type: integer
- container: ''
  name: validAt
  type: dateTime
- container: ''
  name: validOn
  type: date
property_count: 20
provider_name: dtn
provider_slug: dtn
slug: dtn-context
source_filename: dtn-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dtn\": \"https://point-observation.weather.mg/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n\n    \"WeatherObservation\": {\n      \"@id\": \"sosa:Observation\",\n      \"@type\": \"schema:Observation\"\n    },\n    \"Station\": {\n      \"@id\": \"sosa:Platform\",\n      \"@type\": \"schema:Place\"\n    },\n    \"WeatherForecast\": {\n      \"@id\": \"dtn:WeatherForecast\",\n      \"@type\": \"schema:Forecast\"\n    },\n\n    \"stationId\": \"@id\",\n    \"stationName\": \"schema:name\",\n    \"observedAt\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"location\": {\n      \"@id\": \"schema:geo\"\n    },\n \
  \   \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n    \"elevationInMeter\": {\n      \"@id\": \"geo:alt\",\n      \"@type\": \"xsd:double\"\n    },\n    \"airTemperatureInCelsius\": {\n      \"@id\": \"schema:temperature\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"relativeHumidityInPercent\": {\n      \"@id\": \"schema:humidity\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"windSpeedInMeterPerSecond\": {\n      \"@id\": \"schema:windSpeed\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"windDirectionInDegree\": {\n      \"@id\": \"schema:windDirection\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"precipitationAmountInMillimeter\": {\n      \"@id\": \"dtn:precipitation\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"pressureInHectopascal\": {\n      \"@id\": \"dtn:atmosphericPressure\"\
  ,\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"dewPointInCelsius\": {\n      \"@id\": \"dtn:dewPoint\"\n    },\n    \"feelsLikeTemperatureInCelsius\": {\n      \"@id\": \"dtn:apparentTemperature\"\n    },\n    \"uvIndex\": {\n      \"@id\": \"dtn:uvIndex\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weatherSymbol\": {\n      \"@id\": \"dtn:wmoWeatherCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"validAt\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"validOn\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/json-ld/dtn-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
