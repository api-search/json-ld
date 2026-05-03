---
api_specs:
- filename: xweather-weather-api-openapi.yml
  format: yaml
  label: Xweather Weather API
  slug: xweather
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/xweather-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-ld/xweather-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Xweather from Xweather.
layout: jsonld
name: Xweather Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: unit
  uri: http://qudt.org/vocab/unit/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: xweather
  uri: https://github.com/api-evangelist/xweather/blob/main/json-ld/xweather-context.jsonld#
properties:
- container: ''
  name: Location
  type: reference
- container: ''
  name: Conditions
  type: reference
- container: ''
  name: Forecast
  type: reference
- container: ''
  name: Alert
  type: reference
- container: ''
  name: LightningStrike
  type: reference
- container: ''
  name: AirQuality
  type: reference
- container: ''
  name: Observation
  type: reference
- container: ''
  name: TropicalCyclone
  type: reference
- container: ''
  name: MaritimeConditions
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: city
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: country
  type: ''
- container: ''
  name: country_full
  type: ''
- container: ''
  name: loc
  type: reference
- container: ''
  name: lat
  type: decimal
- container: ''
  name: long
  type: decimal
- container: ''
  name: elevFT
  type: ''
- container: ''
  name: tempF
  type: decimal
- container: ''
  name: tempC
  type: decimal
- container: ''
  name: feelslikeF
  type: decimal
- container: ''
  name: feelslikeC
  type: decimal
- container: ''
  name: humidity
  type: integer
- container: ''
  name: dewpointF
  type: decimal
- container: ''
  name: dewpointC
  type: decimal
- container: ''
  name: pressureMB
  type: decimal
- container: ''
  name: windSpeedMPH
  type: decimal
- container: ''
  name: windSpeedKPH
  type: decimal
- container: ''
  name: windDirDEG
  type: integer
- container: ''
  name: windDir
  type: ''
- container: ''
  name: weather
  type: ''
- container: ''
  name: weatherShort
  type: ''
- container: ''
  name: icon
  type: ''
- container: ''
  name: visibilityMI
  type: decimal
- container: ''
  name: visibilityKM
  type: decimal
- container: ''
  name: uvi
  type: decimal
- container: ''
  name: precipMM
  type: decimal
- container: ''
  name: precipIN
  type: decimal
- container: ''
  name: snowDepthIN
  type: decimal
- container: ''
  name: cloudsCoded
  type: ''
- container: ''
  name: skyCover
  type: integer
- container: ''
  name: obTimestamp
  type: dateTime
- container: ''
  name: obDateTime
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: dateTimeISO
  type: dateTime
- container: ''
  name: details
  type: ''
- container: ''
  name: headline
  type: ''
- container: ''
  name: severity
  type: ''
- container: ''
  name: urgency
  type: ''
- container: ''
  name: certainty
  type: ''
- container: ''
  name: peakAmperage
  type: decimal
- container: ''
  name: polarity
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: aqi
  type: integer
- container: ''
  name: category
  type: ''
- container: ''
  name: primaryPollutant
  type: ''
- container: ''
  name: windspeedKnots
  type: decimal
- container: ''
  name: pressureMb
  type: decimal
- container: ''
  name: stormCategory
  type: ''
- container: ''
  name: stationId
  type: ''
- container: ''
  name: success
  type: boolean
- container: ''
  name: error
  type: ''
- container: ''
  name: response
  type: ''
- container: ''
  name: code
  type: ''
- container: ''
  name: message
  type: ''
property_count: 66
provider_name: Xweather
provider_slug: xweather
slug: xweather-context
source_filename: xweather-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"unit\": \"http://qudt.org/vocab/unit/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"xweather\": \"https://github.com/api-evangelist/xweather/blob/main/json-ld/xweather-context.jsonld#\",\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@type\": \"@id\"\n    },\n    \"Conditions\": {\n      \"@id\": \"xweather:Conditions\",\n      \"@type\": \"@id\"\n    },\n    \"Forecast\": {\n      \"@id\": \"schema:WeatherForecast\",\n      \"@type\": \"@id\"\n    },\n    \"Alert\": {\n      \"@id\": \"xweather:Alert\",\n      \"@type\": \"\
  @id\"\n    },\n    \"LightningStrike\": {\n      \"@id\": \"xweather:LightningStrike\",\n      \"@type\": \"@id\"\n    },\n    \"AirQuality\": {\n      \"@id\": \"xweather:AirQuality\",\n      \"@type\": \"@id\"\n    },\n    \"Observation\": {\n      \"@id\": \"schema:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"TropicalCyclone\": {\n      \"@id\": \"xweather:TropicalCyclone\",\n      \"@type\": \"@id\"\n    },\n    \"MaritimeConditions\": {\n      \"@id\": \"xweather:MaritimeConditions\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"city\": { \"@id\": \"schema:addressLocality\" },\n    \"state\": { \"@id\": \"schema:addressRegion\" },\n    \"country\": { \"@id\": \"schema:addressCountry\" },\n    \"country_full\": { \"@id\": \"xweather:countryFull\" },\n    \"loc\": {\n      \"@id\": \"geo:location\",\n      \"@type\": \"@id\"\n    },\n    \"lat\": { \"@id\": \"geo:lat\", \"\
  @type\": \"xsd:decimal\" },\n    \"long\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" },\n    \"elevFT\": { \"@id\": \"schema:elevation\" },\n    \"tempF\": { \"@id\": \"xweather:temperatureF\", \"@type\": \"xsd:decimal\" },\n    \"tempC\": { \"@id\": \"xweather:temperatureC\", \"@type\": \"xsd:decimal\" },\n    \"feelslikeF\": { \"@id\": \"xweather:apparentTemperatureF\", \"@type\": \"xsd:decimal\" },\n    \"feelslikeC\": { \"@id\": \"xweather:apparentTemperatureC\", \"@type\": \"xsd:decimal\" },\n    \"humidity\": { \"@id\": \"xweather:relativeHumidity\", \"@type\": \"xsd:integer\" },\n    \"dewpointF\": { \"@id\": \"xweather:dewpointF\", \"@type\": \"xsd:decimal\" },\n    \"dewpointC\": { \"@id\": \"xweather:dewpointC\", \"@type\": \"xsd:decimal\" },\n    \"pressureMB\": { \"@id\": \"xweather:pressureMillibars\", \"@type\": \"xsd:decimal\" },\n    \"windSpeedMPH\": { \"@id\": \"xweather:windSpeedMph\", \"@type\": \"xsd:decimal\" },\n    \"windSpeedKPH\": { \"@id\": \"xweather:windSpeedKph\"\
  , \"@type\": \"xsd:decimal\" },\n    \"windDirDEG\": { \"@id\": \"xweather:windDirectionDegrees\", \"@type\": \"xsd:integer\" },\n    \"windDir\": { \"@id\": \"xweather:windDirection\" },\n    \"weather\": { \"@id\": \"xweather:weatherCondition\" },\n    \"weatherShort\": { \"@id\": \"xweather:weatherConditionShort\" },\n    \"icon\": { \"@id\": \"xweather:iconName\" },\n    \"visibilityMI\": { \"@id\": \"xweather:visibilityMiles\", \"@type\": \"xsd:decimal\" },\n    \"visibilityKM\": { \"@id\": \"xweather:visibilityKilometers\", \"@type\": \"xsd:decimal\" },\n    \"uvi\": { \"@id\": \"xweather:uvIndex\", \"@type\": \"xsd:decimal\" },\n    \"precipMM\": { \"@id\": \"xweather:precipitationMillimeters\", \"@type\": \"xsd:decimal\" },\n    \"precipIN\": { \"@id\": \"xweather:precipitationInches\", \"@type\": \"xsd:decimal\" },\n    \"snowDepthIN\": { \"@id\": \"xweather:snowDepthInches\", \"@type\": \"xsd:decimal\" },\n    \"cloudsCoded\": { \"@id\": \"xweather:cloudsCoded\" },\n    \"skyCover\"\
  : { \"@id\": \"xweather:skyCoverPercent\", \"@type\": \"xsd:integer\" },\n    \"obTimestamp\": { \"@id\": \"dcterms:date\", \"@type\": \"xsd:dateTime\" },\n    \"obDateTime\": { \"@id\": \"xweather:observationDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"timestamp\": { \"@id\": \"dcterms:date\", \"@type\": \"xsd:dateTime\" },\n    \"dateTimeISO\": { \"@id\": \"schema:dateTime\", \"@type\": \"xsd:dateTime\" },\n\n    \"details\": { \"@id\": \"schema:description\" },\n    \"headline\": { \"@id\": \"schema:headline\" },\n    \"severity\": { \"@id\": \"xweather:severity\" },\n    \"urgency\": { \"@id\": \"xweather:urgency\" },\n    \"certainty\": { \"@id\": \"xweather:certainty\" },\n\n    \"peakAmperage\": { \"@id\": \"xweather:peakAmperage\", \"@type\": \"xsd:decimal\" },\n    \"polarity\": { \"@id\": \"xweather:polarity\" },\n    \"type\": { \"@id\": \"rdf:type\" },\n\n    \"aqi\": { \"@id\": \"xweather:airQualityIndex\", \"@type\": \"xsd:integer\" },\n    \"category\": { \"@id\": \"\
  schema:category\" },\n    \"primaryPollutant\": { \"@id\": \"xweather:primaryPollutant\" },\n\n    \"windspeedKnots\": { \"@id\": \"xweather:windSpeedKnots\", \"@type\": \"xsd:decimal\" },\n    \"pressureMb\": { \"@id\": \"xweather:pressureMillibars\", \"@type\": \"xsd:decimal\" },\n    \"stormCategory\": { \"@id\": \"xweather:stormCategory\" },\n\n    \"stationId\": { \"@id\": \"schema:identifier\" },\n\n    \"success\": { \"@id\": \"xweather:success\", \"@type\": \"xsd:boolean\" },\n    \"error\": { \"@id\": \"schema:error\" },\n    \"response\": { \"@id\": \"xweather:response\" },\n    \"code\": { \"@id\": \"schema:identifier\" },\n    \"message\": { \"@id\": \"schema:description\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-ld/xweather-context.jsonld
tags:
- Air Quality
- Company
- Data
- Forecasts
- Lightning
- Maritime
- Observations
- Severe Weather
- Weather
- JSON-LD
- Linked Data
- Semantic Web
---
