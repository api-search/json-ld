---
api_specs:
- filename: alaska-air-flight-status-openapi.yaml
  format: yaml
  label: Alaska Airlines Flight Status API
  slug: flight-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-flight-status-openapi.yaml
- filename: alaska-air-flight-schedules-openapi.yaml
  format: yaml
  label: Alaska Airlines Flight Schedules API
  slug: flight-schedules-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-flight-schedules-openapi.yaml
- filename: alaska-air-cargo-openapi.yaml
  format: yaml
  label: Alaska Air Cargo API
  slug: cargo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-cargo-openapi.yaml
- filename: alaska-air-mileage-plan-openapi.yaml
  format: yaml
  label: Alaska Airlines Mileage Plan API
  slug: mileage-plan-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-mileage-plan-openapi.yaml
class_count: 22
classes:
- Dimensions
- RateResponse
- ShipmentRequest
- Shipment
- FlightSummary
- FlightStatus
- Member
- RateRequest
- Aircraft
- ScheduleResponse
- AirportList
- ShipmentList
- ShipmentTracking
- TransactionList
- Schedule
- PartnerMilesRequest
- Transaction
- TrackingEvent
- AirportInfo
- FlightList
- Airport
- PartnerMilesResponse
context_file: json-ld/alaska-air-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/json-ld/alaska-air-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alaska Air from Alaska Airlines.
layout: jsonld
name: Alaska Air Context
namespaces:
- prefix: alaska
  uri: https://alaskaair.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: activityAmount
  type: decimal
- container: ''
  name: activityDate
  type: date
- container: ''
  name: activityType
  type: string
- container: ''
  name: aircraft
  type: string
- container: ''
  name: airportCode
  type: string
- container: ''
  name: airportName
  type: string
- container: set
  name: airports
  type: string
- container: ''
  name: arrivalTime
  type: string
- container: ''
  name: awbNumber
  type: string
- container: ''
  name: cabin
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: commodity
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: currentLocation
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: delayMinutes
  type: integer
- container: ''
  name: delayReason
  type: string
- container: ''
  name: departureDate
  type: date
- container: ''
  name: departureTime
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: destinationAirport
  type: string
- container: ''
  name: dimensions
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: email
  type: string
- container: ''
  name: estimatedArrival
  type: dateTime
- container: ''
  name: estimatedDelivery
  type: date
- container: ''
  name: estimatedDeparture
  type: dateTime
- container: ''
  name: event
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: flightDate
  type: date
- container: ''
  name: flightNumber
  type: string
- container: set
  name: flights
  type: string
- container: ''
  name: gate
  type: string
- container: ''
  name: height
  type: decimal
- container: ''
  name: iataCode
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: length
  type: decimal
- container: ''
  name: location
  type: string
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: memberId
  type: string
- container: ''
  name: memberSince
  type: date
- container: ''
  name: mileBalance
  type: integer
- container: ''
  name: miles
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: newBalance
  type: integer
- container: set
  name: operatingDays
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: originAirport
  type: string
- container: ''
  name: partner
  type: string
- container: ''
  name: partnerId
  type: string
- container: ''
  name: pieces
  type: integer
- container: ''
  name: ratePerKg
  type: decimal
- container: ''
  name: referenceId
  type: string
- container: ''
  name: scheduledArrival
  type: dateTime
- container: ''
  name: scheduledDeparture
  type: dateTime
- container: set
  name: schedules
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: shipDate
  type: date
- container: set
  name: shipments
  type: string
- container: set
  name: specialHandling
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: stops
  type: integer
- container: ''
  name: tailNumber
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: tier
  type: string
- container: ''
  name: tierMiles
  type: integer
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: timezone
  type: string
- container: ''
  name: totalCharge
  type: decimal
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: transactionId
  type: string
- container: set
  name: transactions
  type: string
- container: ''
  name: transitDays
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: weight
  type: decimal
- container: ''
  name: weightUnit
  type: string
- container: ''
  name: width
  type: decimal
property_count: 84
provider_name: Alaska Airlines
provider_slug: alaska-air
slug: alaska-air-context
source_filename: alaska-air-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alaska\": \"https://alaskaair.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Dimensions\": \"alaska:Dimensions\",\n    \"RateResponse\": \"alaska:RateResponse\",\n    \"ShipmentRequest\": \"alaska:ShipmentRequest\",\n    \"Shipment\": \"alaska:Shipment\",\n    \"FlightSummary\": \"alaska:FlightSummary\",\n    \"FlightStatus\": \"alaska:FlightStatus\",\n    \"Member\": \"alaska:Member\",\n    \"RateRequest\": \"alaska:RateRequest\",\n    \"Aircraft\": \"alaska:Aircraft\",\n    \"ScheduleResponse\": \"alaska:ScheduleResponse\",\n    \"AirportList\": \"alaska:AirportList\",\n    \"ShipmentList\": \"alaska:ShipmentList\",\n    \"ShipmentTracking\": \"alaska:ShipmentTracking\",\n    \"TransactionList\": \"alaska:TransactionList\",\n    \"Schedule\": \"alaska:Schedule\",\n    \"PartnerMilesRequest\": \"alaska:PartnerMilesRequest\"\
  ,\n    \"Transaction\": \"alaska:Transaction\",\n    \"TrackingEvent\": \"alaska:TrackingEvent\",\n    \"AirportInfo\": \"alaska:AirportInfo\",\n    \"FlightList\": \"alaska:FlightList\",\n    \"Airport\": \"alaska:Airport\",\n    \"PartnerMilesResponse\": \"alaska:PartnerMilesResponse\",\n    \"activityAmount\": {\n      \"@id\": \"alaska:activityAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"activityDate\": {\n      \"@id\": \"alaska:activityDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"activityType\": {\n      \"@id\": \"alaska:activityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"alaska:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airportCode\": {\n      \"@id\": \"alaska:airportCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airportName\": {\n      \"@id\": \"alaska:airportName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airports\": {\n      \"@id\": \"alaska:airports\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrivalTime\": {\n      \"@id\": \"alaska:arrivalTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awbNumber\": {\n      \"@id\": \"alaska:awbNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cabin\": {\n      \"@id\": \"alaska:cabin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"alaska:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"alaska:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commodity\": {\n      \"@id\": \"alaska:commodity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"alaska:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"alaska:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentLocation\": {\n      \"@id\": \"alaska:currentLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"alaska:date\",\n\
  \      \"@type\": \"xsd:date\"\n    },\n    \"delayMinutes\": {\n      \"@id\": \"alaska:delayMinutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"delayReason\": {\n      \"@id\": \"alaska:delayReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departureDate\": {\n      \"@id\": \"alaska:departureDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"departureTime\": {\n      \"@id\": \"alaska:departureTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"alaska:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationAirport\": {\n      \"@id\": \"alaska:destinationAirport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"alaska:dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"alaska:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedArrival\": {\n      \"@id\": \"alaska:estimatedArrival\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"estimatedDelivery\": {\n      \"@id\": \"alaska:estimatedDelivery\",\n      \"@type\": \"xsd:date\"\n    },\n    \"estimatedDeparture\": {\n      \"@id\": \"alaska:estimatedDeparture\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"event\": {\n      \"@id\": \"alaska:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"alaska:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"alaska:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightDate\": {\n      \"@id\": \"alaska:flightDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"flightNumber\": {\n      \"@id\": \"alaska:flightNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flights\": {\n  \
  \    \"@id\": \"alaska:flights\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gate\": {\n      \"@id\": \"alaska:gate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"height\": {\n      \"@id\": \"alaska:height\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"iataCode\": {\n      \"@id\": \"alaska:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"alaska:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"alaska:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"length\": {\n      \"@id\": \"alaska:length\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"location\": {\n      \"@id\": \"alaska:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longitude\": {\n      \"@id\": \"alaska:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"memberId\": {\n      \"@id\": \"alaska:memberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberSince\"\
  : {\n      \"@id\": \"alaska:memberSince\",\n      \"@type\": \"xsd:date\"\n    },\n    \"mileBalance\": {\n      \"@id\": \"alaska:mileBalance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"miles\": {\n      \"@id\": \"alaska:miles\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newBalance\": {\n      \"@id\": \"alaska:newBalance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"operatingDays\": {\n      \"@id\": \"alaska:operatingDays\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"alaska:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originAirport\": {\n      \"@id\": \"alaska:originAirport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partner\": {\n      \"@id\": \"alaska:partner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerId\": {\n      \"@id\": \"alaska:partnerId\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"pieces\": {\n      \"@id\": \"alaska:pieces\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ratePerKg\": {\n      \"@id\": \"alaska:ratePerKg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"referenceId\": {\n      \"@id\": \"alaska:referenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledArrival\": {\n      \"@id\": \"alaska:scheduledArrival\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scheduledDeparture\": {\n      \"@id\": \"alaska:scheduledDeparture\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"schedules\": {\n      \"@id\": \"alaska:schedules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"alaska:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipDate\": {\n      \"@id\": \"alaska:shipDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"shipments\": {\n      \"@id\": \"alaska:shipments\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"specialHandling\": {\n      \"@id\": \"alaska:specialHandling\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"alaska:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"alaska:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"alaska:stops\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tailNumber\": {\n      \"@id\": \"alaska:tailNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"alaska:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tier\": {\n      \"@id\": \"alaska:tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tierMiles\": {\n      \"@id\": \"alaska:tierMiles\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"alaska:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timezone\": {\n      \"@id\": \"alaska:timezone\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCharge\": {\n      \"@id\": \"alaska:totalCharge\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalCount\": {\n      \"@id\": \"alaska:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transactionId\": {\n      \"@id\": \"alaska:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactions\": {\n      \"@id\": \"alaska:transactions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transitDays\": {\n      \"@id\": \"alaska:transitDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"alaska:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"alaska:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"alaska:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"weightUnit\": {\n      \"@id\": \"alaska:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\"\
  : {\n      \"@id\": \"alaska:width\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/json-ld/alaska-air-context.jsonld
tags:
- Airlines
- Aviation
- Travel
- Cargo
- Loyalty
- Flight Status
- JSON-LD
- Linked Data
- Semantic Web
---
