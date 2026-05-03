---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Weather.gov API Web Service
  slug: weather-gov-api-web-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/openapi/openapi.yml
class_count: 42
classes:
- AlertAtomEntry
- AlertAtomFeed
- AlertCap
- AlertCollection
- AlertJsonLd
- Alert
- AlertXMLParameter
- AstronomicalData
- CenterWeatherAdvisory
- GeoJsonFeatureCollection
- GeoJsonFeature
- GridpointHourlyForecastPeriod
- GridpointHourlyForecast
- GridpointQuantitativeValueLayer
- Gridpoint
- Gridpoint12hForecastPeriod
- Gridpoint12hForecast
- MetarPhenomenon
- NWSConnectDocumentMetadata
- ObservationCollectionJsonLd
- Observation
- ObservationStationCollectionJsonLd
- ObservationStation
- OfficeHeadlineCollection
- OfficeHeadline
- Office
- PaginationInfo
- Point
- QuantitativeValue
- RelativeLocation
- Sigmet
- TextProductCollection
- TextProductLocationCollection
- TextProduct
- TextProductTypeCollection
- ZoneCollectionJsonLd
- ZoneForecast
- Zone
- name
- identifier
- description
- email
context_file: json-ld/weather-gov-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/json-ld/weather-gov-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Weather Gov from Weather.gov.
layout: jsonld
name: Weather Gov Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: weather
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: updated
  type: string
- container: ''
  name: published
  type: string
- container: ''
  name: author
  type: reference
- container: ''
  name: summary
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: sent
  type: string
- container: ''
  name: effective
  type: string
- container: ''
  name: expires
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: msgType
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: urgency
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: certainty
  type: string
- container: ''
  name: areaDesc
  type: string
- container: ''
  name: polygon
  type: string
- container: set
  name: geocode
  type: string
- container: set
  name: parameter
  type: string
- container: ''
  name: generator
  type: string
- container: ''
  name: title
  type: string
- container: set
  name: entry
  type: string
- container: ''
  name: pagination
  type: string
- container: set
  name: affectedZones
  type: reference
- container: set
  name: references
  type: reference
- container: ''
  name: sender
  type: string
- container: ''
  name: onset
  type: string
- container: ''
  name: ends
  type: string
- container: ''
  name: messageType
  type: string
- container: ''
  name: senderName
  type: string
- container: ''
  name: headline
  type: string
- container: ''
  name: instruction
  type: string
- container: ''
  name: note
  type: string
- container: ''
  name: response
  type: string
- container: ''
  name: parameters
  type: reference
- container: ''
  name: scope
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: web
  type: string
- container: ''
  name: eventCode
  type: reference
- container: ''
  name: valueName
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: sunrise
  type: dateTime
- container: ''
  name: sunset
  type: dateTime
- container: ''
  name: transit
  type: dateTime
- container: ''
  name: civilTwilightBegin
  type: dateTime
- container: ''
  name: civilTwilightEnd
  type: dateTime
- container: ''
  name: nauticalTwilightBegin
  type: dateTime
- container: ''
  name: nauticalTwilightEnd
  type: dateTime
- container: ''
  name: astronomicalTwilightBegin
  type: dateTime
- container: ''
  name: astronomicalTwilightEnd
  type: dateTime
- container: ''
  name: issueTime
  type: dateTime
- container: ''
  name: cwsu
  type: string
- container: ''
  name: sequence
  type: integer
- container: ''
  name: start
  type: dateTime
- container: ''
  name: end
  type: dateTime
- container: ''
  name: observedProperty
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: features
  type: string
- container: ''
  name: geometry
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: number
  type: integer
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: isDaytime
  type: boolean
- container: ''
  name: temperature
  type: string
- container: ''
  name: temperatureUnit
  type: string
- container: ''
  name: temperatureTrend
  type: string
- container: ''
  name: probabilityOfPrecipitation
  type: string
- container: ''
  name: dewpoint
  type: string
- container: ''
  name: relativeHumidity
  type: string
- container: ''
  name: windSpeed
  type: string
- container: ''
  name: windGust
  type: string
- container: ''
  name: windDirection
  type: string
- container: ''
  name: icon
  type: reference
- container: ''
  name: shortForecast
  type: string
- container: ''
  name: detailedForecast
  type: string
- container: ''
  name: units
  type: string
- container: ''
  name: forecastGenerator
  type: string
- container: ''
  name: generatedAt
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: validTimes
  type: string
- container: ''
  name: elevation
  type: string
- container: set
  name: periods
  type: string
- container: ''
  name: uom
  type: string
- container: set
  name: values
  type: reference
- container: ''
  name: validTime
  type: string
- container: ''
  name: forecastOffice
  type: reference
- container: ''
  name: gridId
  type: string
- container: ''
  name: gridX
  type: integer
- container: ''
  name: gridY
  type: integer
- container: ''
  name: hazards
  type: reference
- container: ''
  name: intensity
  type: string
- container: ''
  name: modifier
  type: string
- container: ''
  name: rawString
  type: string
- container: ''
  name: inVicinity
  type: boolean
- container: ''
  name: priority
  type: boolean
- container: ''
  name: download
  type: reference
- container: ''
  name: station
  type: reference
- container: ''
  name: stationId
  type: string
- container: ''
  name: stationName
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: rawMessage
  type: string
- container: ''
  name: textDescription
  type: string
- container: set
  name: presentWeather
  type: string
- container: ''
  name: barometricPressure
  type: string
- container: ''
  name: seaLevelPressure
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: maxTemperatureLast24Hours
  type: string
- container: ''
  name: minTemperatureLast24Hours
  type: string
- container: ''
  name: precipitationLastHour
  type: string
- container: ''
  name: precipitationLast3Hours
  type: string
- container: ''
  name: precipitationLast6Hours
  type: string
- container: ''
  name: windChill
  type: string
- container: ''
  name: heatIndex
  type: string
- container: ''
  name: cloudLayers
  type: string
- container: set
  name: observationStations
  type: reference
- container: ''
  name: stationIdentifier
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: subProvider
  type: string
- container: ''
  name: forecast
  type: reference
- container: ''
  name: county
  type: reference
- container: ''
  name: fireWeatherZone
  type: reference
- container: ''
  name: distance
  type: string
- container: ''
  name: bearing
  type: string
- container: ''
  name: office
  type: reference
- container: ''
  name: important
  type: boolean
- container: ''
  name: issuanceTime
  type: dateTime
- container: ''
  name: link
  type: reference
- container: ''
  name: content
  type: string
- container: ''
  name: address
  type: reference
- container: ''
  name: streetAddress
  type: string
- container: ''
  name: addressLocality
  type: string
- container: ''
  name: addressRegion
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: telephone
  type: string
- container: ''
  name: faxNumber
  type: string
- container: ''
  name: sameAs
  type: reference
- container: ''
  name: nwsRegion
  type: string
- container: ''
  name: parentOrganization
  type: reference
- container: set
  name: responsibleCounties
  type: reference
- container: set
  name: responsibleForecastZones
  type: reference
- container: set
  name: responsibleFireZones
  type: reference
- container: set
  name: approvedObservationStations
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: cwa
  type: string
- container: ''
  name: forecastHourly
  type: reference
- container: ''
  name: forecastGridData
  type: reference
- container: ''
  name: relativeLocation
  type: string
- container: ''
  name: forecastZone
  type: reference
- container: ''
  name: radarStation
  type: string
- container: ''
  name: astronomicalData
  type: string
- container: ''
  name: nwr
  type: reference
- container: ''
  name: transmitter
  type: string
- container: ''
  name: sameCode
  type: string
- container: ''
  name: areaBroadcast
  type: string
- container: ''
  name: pointBroadcast
  type: string
- container: ''
  name: maxValue
  type: decimal
- container: ''
  name: minValue
  type: decimal
- container: ''
  name: unitCode
  type: string
- container: ''
  name: qualityControl
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: fir
  type: string
- container: ''
  name: atsu
  type: string
- container: ''
  name: phenomenon
  type: string
- container: ''
  name: locations
  type: reference
- container: ''
  name: wmoCollectiveId
  type: string
- container: ''
  name: issuingOffice
  type: string
- container: ''
  name: productCode
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: productText
  type: string
- container: ''
  name: zone
  type: reference
- container: ''
  name: effectiveDate
  type: dateTime
- container: ''
  name: expirationDate
  type: dateTime
- container: ''
  name: gridIdentifier
  type: string
- container: ''
  name: awipsLocationIdentifier
  type: string
- container: set
  name: forecastOffices
  type: reference
property_count: 181
provider_name: Weather.gov
provider_slug: weather-gov
slug: weather-gov-context
source_filename: weather-gov-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"weather\": {\n      \"@id\": \"weather:weather\",\n      \"@type\": \"@id\"\n    },\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlertAtomEntry\": \"weather:AlertAtomEntry\",\n    \"AlertAtomFeed\": \"weather:AlertAtomFeed\",\n    \"AlertCap\": \"weather:AlertCap\",\n    \"AlertCollection\": \"weather:AlertCollection\",\n    \"AlertJsonLd\": \"weather:AlertJsonLd\",\n    \"Alert\": \"weather:Alert\",\n    \"AlertXMLParameter\": \"weather:AlertXMLParameter\",\n    \"AstronomicalData\": \"weather:AstronomicalData\",\n    \"CenterWeatherAdvisory\": \"weather:CenterWeatherAdvisory\",\n    \"GeoJsonFeatureCollection\": \"weather:GeoJsonFeatureCollection\",\n    \"GeoJsonFeature\": \"weather:GeoJsonFeature\",\n    \"GridpointHourlyForecastPeriod\": \"weather:GridpointHourlyForecastPeriod\",\n    \"GridpointHourlyForecast\":\
  \ \"weather:GridpointHourlyForecast\",\n    \"GridpointQuantitativeValueLayer\": \"weather:GridpointQuantitativeValueLayer\",\n    \"Gridpoint\": \"weather:Gridpoint\",\n    \"Gridpoint12hForecastPeriod\": \"weather:Gridpoint12hForecastPeriod\",\n    \"Gridpoint12hForecast\": \"weather:Gridpoint12hForecast\",\n    \"MetarPhenomenon\": \"weather:MetarPhenomenon\",\n    \"NWSConnectDocumentMetadata\": \"weather:NWSConnectDocumentMetadata\",\n    \"ObservationCollectionJsonLd\": \"weather:ObservationCollectionJsonLd\",\n    \"Observation\": \"weather:Observation\",\n    \"ObservationStationCollectionJsonLd\": \"weather:ObservationStationCollectionJsonLd\",\n    \"ObservationStation\": \"weather:ObservationStation\",\n    \"OfficeHeadlineCollection\": \"weather:OfficeHeadlineCollection\",\n    \"OfficeHeadline\": \"weather:OfficeHeadline\",\n    \"Office\": \"weather:Office\",\n    \"PaginationInfo\": \"weather:PaginationInfo\",\n    \"Point\": \"weather:Point\",\n    \"QuantitativeValue\"\
  : \"weather:QuantitativeValue\",\n    \"RelativeLocation\": \"weather:RelativeLocation\",\n    \"Sigmet\": \"weather:Sigmet\",\n    \"TextProductCollection\": \"weather:TextProductCollection\",\n    \"TextProductLocationCollection\": \"weather:TextProductLocationCollection\",\n    \"TextProduct\": \"weather:TextProduct\",\n    \"TextProductTypeCollection\": \"weather:TextProductTypeCollection\",\n    \"ZoneCollectionJsonLd\": \"weather:ZoneCollectionJsonLd\",\n    \"ZoneForecast\": \"weather:ZoneForecast\",\n    \"Zone\": \"weather:Zone\",\n    \"id\": {\n      \"@id\": \"weather:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"weather:updated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"published\": {\n      \"@id\": \"weather:published\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"weather:author\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"summary\": {\n      \"@id\": \"weather:summary\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"weather:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sent\": {\n      \"@id\": \"weather:sent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effective\": {\n      \"@id\": \"weather:effective\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expires\": {\n      \"@id\": \"weather:expires\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"weather:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msgType\": {\n      \"@id\": \"weather:msgType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"weather:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urgency\": {\n      \"@id\": \"weather:urgency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"weather:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certainty\": {\n      \"@id\": \"weather:certainty\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"areaDesc\": {\n      \"@id\": \"weather:areaDesc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"polygon\": {\n      \"@id\": \"weather:polygon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geocode\": {\n      \"@id\": \"weather:geocode\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameter\": {\n      \"@id\": \"weather:parameter\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generator\": {\n      \"@id\": \"weather:generator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"weather:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entry\": {\n      \"@id\": \"weather:entry\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagination\": {\n      \"@id\": \"weather:pagination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@graph\": {\n      \"@id\": \"weather:@graph\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedZones\": {\n      \"@id\": \"weather:affectedZones\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"references\": {\n      \"@id\": \"weather:references\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"@id\": {\n      \"@id\": \"weather:@id\",\n      \"@type\": \"@id\"\n    },\n    \"identifier\": \"dcterms:identifier\",\n    \"sender\": {\n      \"@id\": \"weather:sender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onset\": {\n      \"@id\": \"weather:onset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ends\": {\n      \"@id\": \"weather:ends\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageType\": {\n      \"@id\": \"weather:messageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"senderName\": {\n      \"@id\": \"weather:senderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headline\": {\n      \"@id\": \"weather:headline\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"instruction\": {\n      \"@id\": \"weather:instruction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"note\": {\n      \"@id\": \"weather:note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"response\": {\n      \"@id\": \"weather:response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"weather:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"scope\": {\n      \"@id\": \"weather:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"weather:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"weather:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"web\": {\n      \"@id\": \"weather:web\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventCode\": {\n      \"@id\": \"weather:eventCode\",\n      \"@type\": \"@id\"\n    },\n    \"valueName\": {\n      \"@id\": \"weather:valueName\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"weather:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunrise\": {\n      \"@id\": \"weather:sunrise\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sunset\": {\n      \"@id\": \"weather:sunset\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"transit\": {\n      \"@id\": \"weather:transit\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"civilTwilightBegin\": {\n      \"@id\": \"weather:civilTwilightBegin\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"civilTwilightEnd\": {\n      \"@id\": \"weather:civilTwilightEnd\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nauticalTwilightBegin\": {\n      \"@id\": \"weather:nauticalTwilightBegin\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nauticalTwilightEnd\": {\n      \"@id\": \"weather:nauticalTwilightEnd\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"astronomicalTwilightBegin\": {\n      \"@id\": \"weather:astronomicalTwilightBegin\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"astronomicalTwilightEnd\": {\n      \"@id\": \"weather:astronomicalTwilightEnd\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"issueTime\": {\n      \"@id\": \"weather:issueTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"cwsu\": {\n      \"@id\": \"weather:cwsu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequence\": {\n      \"@id\": \"weather:sequence\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"weather:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"end\": {\n      \"@id\": \"weather:end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"observedProperty\": {\n      \"@id\": \"weather:observedProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"weather:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@context\": {\n      \"@id\": \"weather:@context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\"\
  : \"weather:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"features\": {\n      \"@id\": \"weather:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geometry\": {\n      \"@id\": \"weather:geometry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"weather:properties\",\n      \"@type\": \"@id\"\n    },\n    \"number\": {\n      \"@id\": \"weather:number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"weather:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"weather:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"isDaytime\": {\n      \"@id\": \"weather:isDaytime\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"temperature\": {\n      \"@id\": \"weather:temperature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"temperatureUnit\": {\n      \"@id\": \"weather:temperatureUnit\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"temperatureTrend\": {\n      \"@id\": \"weather:temperatureTrend\",\n      \"@type\": \"xsd:string\"\n    },\n    \"probabilityOfPrecipitation\": {\n      \"@id\": \"weather:probabilityOfPrecipitation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dewpoint\": {\n      \"@id\": \"weather:dewpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relativeHumidity\": {\n      \"@id\": \"weather:relativeHumidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windSpeed\": {\n      \"@id\": \"weather:windSpeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windGust\": {\n      \"@id\": \"weather:windGust\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windDirection\": {\n      \"@id\": \"weather:windDirection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icon\": {\n      \"@id\": \"weather:icon\",\n      \"@type\": \"@id\"\n    },\n    \"shortForecast\": {\n      \"@id\": \"weather:shortForecast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detailedForecast\"\
  : {\n      \"@id\": \"weather:detailedForecast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"weather:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastGenerator\": {\n      \"@id\": \"weather:forecastGenerator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generatedAt\": {\n      \"@id\": \"weather:generatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"weather:updateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"validTimes\": {\n      \"@id\": \"weather:validTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elevation\": {\n      \"@id\": \"weather:elevation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periods\": {\n      \"@id\": \"weather:periods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uom\": {\n      \"@id\": \"weather:uom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"weather:values\",\n\
  \      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"validTime\": {\n      \"@id\": \"weather:validTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@type\": {\n      \"@id\": \"weather:@type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastOffice\": {\n      \"@id\": \"weather:forecastOffice\",\n      \"@type\": \"@id\"\n    },\n    \"gridId\": {\n      \"@id\": \"weather:gridId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gridX\": {\n      \"@id\": \"weather:gridX\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gridY\": {\n      \"@id\": \"weather:gridY\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hazards\": {\n      \"@id\": \"weather:hazards\",\n      \"@type\": \"@id\"\n    },\n    \"intensity\": {\n      \"@id\": \"weather:intensity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifier\": {\n      \"@id\": \"weather:modifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rawString\": {\n      \"@id\": \"weather:rawString\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"inVicinity\": {\n      \"@id\": \"weather:inVicinity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"priority\": {\n      \"@id\": \"weather:priority\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"download\": {\n      \"@id\": \"weather:download\",\n      \"@type\": \"@id\"\n    },\n    \"station\": {\n      \"@id\": \"weather:station\",\n      \"@type\": \"@id\"\n    },\n    \"stationId\": {\n      \"@id\": \"weather:stationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stationName\": {\n      \"@id\": \"weather:stationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"weather:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rawMessage\": {\n      \"@id\": \"weather:rawMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"textDescription\": {\n      \"@id\": \"weather:textDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"presentWeather\": {\n      \"\
  @id\": \"weather:presentWeather\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"barometricPressure\": {\n      \"@id\": \"weather:barometricPressure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seaLevelPressure\": {\n      \"@id\": \"weather:seaLevelPressure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visibility\": {\n      \"@id\": \"weather:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxTemperatureLast24Hours\": {\n      \"@id\": \"weather:maxTemperatureLast24Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minTemperatureLast24Hours\": {\n      \"@id\": \"weather:minTemperatureLast24Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precipitationLastHour\": {\n      \"@id\": \"weather:precipitationLastHour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precipitationLast3Hours\": {\n      \"@id\": \"weather:precipitationLast3Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precipitationLast6Hours\"\
  : {\n      \"@id\": \"weather:precipitationLast6Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windChill\": {\n      \"@id\": \"weather:windChill\",\n      \"@type\": \"xsd:string\"\n    },\n    \"heatIndex\": {\n      \"@id\": \"weather:heatIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudLayers\": {\n      \"@id\": \"weather:cloudLayers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"observationStations\": {\n      \"@id\": \"weather:observationStations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"stationIdentifier\": {\n      \"@id\": \"weather:stationIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"weather:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"weather:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subProvider\": {\n      \"@id\": \"weather:subProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecast\": {\n\
  \      \"@id\": \"weather:forecast\",\n      \"@type\": \"@id\"\n    },\n    \"county\": {\n      \"@id\": \"weather:county\",\n      \"@type\": \"@id\"\n    },\n    \"fireWeatherZone\": {\n      \"@id\": \"weather:fireWeatherZone\",\n      \"@type\": \"@id\"\n    },\n    \"distance\": {\n      \"@id\": \"weather:distance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bearing\": {\n      \"@id\": \"weather:bearing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"office\": {\n      \"@id\": \"weather:office\",\n      \"@type\": \"@id\"\n    },\n    \"important\": {\n      \"@id\": \"weather:important\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"issuanceTime\": {\n      \"@id\": \"weather:issuanceTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"link\": {\n      \"@id\": \"weather:link\",\n      \"@type\": \"@id\"\n    },\n    \"content\": {\n      \"@id\": \"weather:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"weather:address\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"streetAddress\": {\n      \"@id\": \"weather:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressLocality\": {\n      \"@id\": \"weather:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressRegion\": {\n      \"@id\": \"weather:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"weather:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephone\": {\n      \"@id\": \"weather:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faxNumber\": {\n      \"@id\": \"weather:faxNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"sameAs\": {\n      \"@id\": \"weather:sameAs\",\n      \"@type\": \"@id\"\n    },\n    \"nwsRegion\": {\n      \"@id\": \"weather:nwsRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentOrganization\": {\n      \"@id\": \"weather:parentOrganization\",\n      \"@type\":\
  \ \"@id\"\n    },\n    \"responsibleCounties\": {\n      \"@id\": \"weather:responsibleCounties\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"responsibleForecastZones\": {\n      \"@id\": \"weather:responsibleForecastZones\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"responsibleFireZones\": {\n      \"@id\": \"weather:responsibleFireZones\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"approvedObservationStations\": {\n      \"@id\": \"weather:approvedObservationStations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"next\": {\n      \"@id\": \"weather:next\",\n      \"@type\": \"@id\"\n    },\n    \"cwa\": {\n      \"@id\": \"weather:cwa\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastHourly\": {\n      \"@id\": \"weather:forecastHourly\",\n      \"@type\": \"@id\"\n    },\n    \"forecastGridData\": {\n      \"@id\": \"weather:forecastGridData\",\n     \
  \ \"@type\": \"@id\"\n    },\n    \"relativeLocation\": {\n      \"@id\": \"weather:relativeLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastZone\": {\n      \"@id\": \"weather:forecastZone\",\n      \"@type\": \"@id\"\n    },\n    \"radarStation\": {\n      \"@id\": \"weather:radarStation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"astronomicalData\": {\n      \"@id\": \"weather:astronomicalData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nwr\": {\n      \"@id\": \"weather:nwr\",\n      \"@type\": \"@id\"\n    },\n    \"transmitter\": {\n      \"@id\": \"weather:transmitter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sameCode\": {\n      \"@id\": \"weather:sameCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"areaBroadcast\": {\n      \"@id\": \"weather:areaBroadcast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointBroadcast\": {\n      \"@id\": \"weather:pointBroadcast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxValue\":\
  \ {\n      \"@id\": \"weather:maxValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minValue\": {\n      \"@id\": \"weather:minValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unitCode\": {\n      \"@id\": \"weather:unitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qualityControl\": {\n      \"@id\": \"weather:qualityControl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"weather:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"weather:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fir\": {\n      \"@id\": \"weather:fir\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atsu\": {\n      \"@id\": \"weather:atsu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phenomenon\": {\n      \"@id\": \"weather:phenomenon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"weather:locations\",\n      \"@type\": \"@id\"\n    },\n    \"wmoCollectiveId\": {\n      \"\
  @id\": \"weather:wmoCollectiveId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingOffice\": {\n      \"@id\": \"weather:issuingOffice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productCode\": {\n      \"@id\": \"weather:productCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"weather:productName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productText\": {\n      \"@id\": \"weather:productText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zone\": {\n      \"@id\": \"weather:zone\",\n      \"@type\": \"@id\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"weather:effectiveDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"weather:expirationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"gridIdentifier\": {\n      \"@id\": \"weather:gridIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awipsLocationIdentifier\": {\n      \"@id\": \"weather:awipsLocationIdentifier\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastOffices\": {\n      \"@id\": \"weather:forecastOffices\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/json-ld/weather-gov-context.jsonld
tags:
- Weather
- Government
- United States
- Forecasting
- Alerts
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
