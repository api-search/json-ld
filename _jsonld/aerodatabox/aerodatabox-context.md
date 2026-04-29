---
class_count: 80
classes:
- AirportUrlsContract
- SpeedFlightPlanUnitContract
- SurfaceType
- AirportFlightContract
- FlightAirportMovementContract
- ListingAirportContract
- GeoCoordinatesContractListingAirportContractSearchResultCollectionContract
- Angle
- FlightPlanContract
- ModelFlightTimeEnum
- AirportFidsContract
- SubscriptionSubjectContract
- AirportDelayContract
- FlightDelayContract
- AirportFeedServiceStatusContract
- DistanceFlightPlanUnitContract
- DateTimeContract
- FlightAirportMovementQualityEnum
- FeedServiceStatus
- FlightContract
- AircraftContract
- ErrorContract
- SubscriptionContract
- Pressure
- AirportDistanceTimeContract
- FlightAircraftContract
- SubscriptionSubjectType
- FlightLocationContract
- LicenseType
- StringListingAirportContractSearchResultCollectionContract
- FlightDirection
- GeoCoordinatesContract
- Azimuth
- AircraftContractPagedCollectionContract
- StringFlightSearchItemContractSearchResultCollectionContract
- FlightRules
- ContinentContract
- SolarStateContract
- DailyRouteStatContract
- Speed
- AirportLocalTimeContract
- FlightSearchByEnum
- CountryContract
- DayTime
- AircraftSearchByEnum
- FlightType
- AirportContract
- SubscriptionsBalanceRefillRequestContract
- FlightNotificationItemContract
- FeedServiceEnum
- AirportCodesByEnum
- CreateWebHookSubscription
- FaaLaddAircraftStatusContract
- CodeshareStatus
- FlightLegDelayContract
- PercentileBracketContract
- AircraftRegistrationContract
- FlightAirlineContract
- FlightPlanStatus
- Distance
- SubscriberContract
- EngineType
- DailyRouteStatRecordContract
- StringCollectionContract
- SubscriptionBillingType
- FeedServiceStatusContract
- RunwayContract
- StringAircraftContractSearchResultCollectionContract
- FlightNotificationContract
- StatisticClass
- SubscriptionBalanceContract
- FlightStatus
- FlightSearchItemContract
- ResourceContract
- DelayBracketContract
- FlightDataGeneralAvailabilityContract
- FlightBatchDelayContract
- name
- url
- description
context_file: json-ld/aerodatabox-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aerodatabox/refs/heads/main/json-ld/aerodatabox-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aerodatabox from AeroDataBox.
layout: jsonld
name: Aerodatabox Context
namespaces:
- prefix: aedbx
  uri: https://aerodatabox.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: webSite
  type: string
- container: ''
  name: wikipedia
  type: string
- container: ''
  name: twitter
  type: string
- container: ''
  name: liveAtc
  type: string
- container: ''
  name: flightRadar
  type: string
- container: ''
  name: googleMaps
  type: string
- container: ''
  name: requested
  type: string
- container: ''
  name: assigned
  type: string
- container: ''
  name: movement
  type: string
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: callSign
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: codeshareStatus
  type: string
- container: ''
  name: isCargo
  type: boolean
- container: ''
  name: aircraft
  type: string
- container: ''
  name: airline
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: airport
  type: string
- container: ''
  name: scheduledTime
  type: string
- container: ''
  name: revisedTime
  type: string
- container: ''
  name: predictedTime
  type: string
- container: ''
  name: runwayTime
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: checkInDesk
  type: string
- container: ''
  name: gate
  type: string
- container: ''
  name: baggageBelt
  type: string
- container: ''
  name: runway
  type: string
- container: set
  name: quality
  type: string
- container: ''
  name: icao
  type: string
- container: ''
  name: iata
  type: string
- container: ''
  name: localCode
  type: string
- container: ''
  name: shortName
  type: string
- container: ''
  name: municipalityName
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: searchBy
  type: string
- container: ''
  name: count
  type: integer
- container: set
  name: items
  type: string
- container: ''
  name: deg
  type: decimal
- container: ''
  name: rad
  type: decimal
- container: ''
  name: flightRules
  type: string
- container: ''
  name: flightType
  type: string
- container: ''
  name: revisionNo
  type: integer
- container: ''
  name: route
  type: string
- container: ''
  name: altitude
  type: string
- container: ''
  name: airspeed
  type: string
- container: ''
  name: lastUpdatedUtc
  type: dateTime
- container: set
  name: departures
  type: string
- container: set
  name: arrivals
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: airportIcao
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: departuresDelayInformation
  type: string
- container: ''
  name: arrivalsDelayInformation
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: scheduledHourUtc
  type: integer
- container: ''
  name: medianDelay
  type: string
- container: set
  name: delayPercentiles
  type: string
- container: ''
  name: numConsideredFlights
  type: integer
- container: set
  name: numFlightsDelayedBrackets
  type: string
- container: ''
  name: fromUtc
  type: dateTime
- container: ''
  name: toUtc
  type: dateTime
- container: ''
  name: flightSchedulesFeed
  type: string
- container: ''
  name: liveFlightUpdatesFeed
  type: string
- container: ''
  name: adsbUpdatesFeed
  type: string
- container: ''
  name: generalAvailability
  type: string
- container: ''
  name: utc
  type: dateTime
- container: ''
  name: local
  type: dateTime
- container: ''
  name: greatCircleDistance
  type: string
- container: ''
  name: flightPlan
  type: string
- container: ''
  name: reg
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: serial
  type: string
- container: ''
  name: hexIcao
  type: string
- container: ''
  name: airlineName
  type: string
- container: ''
  name: iataType
  type: string
- container: ''
  name: iataCodeShort
  type: string
- container: ''
  name: icaoCode
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: modelCode
  type: string
- container: ''
  name: numSeats
  type: integer
- container: ''
  name: rolloutDate
  type: dateTime
- container: ''
  name: firstFlightDate
  type: dateTime
- container: ''
  name: deliveryDate
  type: dateTime
- container: ''
  name: registrationDate
  type: dateTime
- container: ''
  name: typeName
  type: string
- container: ''
  name: numEngines
  type: integer
- container: ''
  name: engineType
  type: string
- container: ''
  name: isFreighter
  type: boolean
- container: ''
  name: productionLine
  type: string
- container: ''
  name: ageYears
  type: decimal
- container: ''
  name: verified
  type: boolean
- container: ''
  name: image
  type: string
- container: ''
  name: numRegistrations
  type: integer
- container: set
  name: registrations
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: billingType
  type: string
- container: ''
  name: activateBeforeUtc
  type: dateTime
- container: ''
  name: expiresOnUtc
  type: dateTime
- container: ''
  name: createdOnUtc
  type: dateTime
- container: ''
  name: subject
  type: string
- container: ''
  name: subscriber
  type: string
- container: set
  name: notices
  type: string
- container: ''
  name: hPa
  type: decimal
- container: ''
  name: inHg
  type: decimal
- container: ''
  name: mmHg
  type: decimal
- container: ''
  name: approxFlightTime
  type: string
- container: ''
  name: modeS
  type: string
- container: ''
  name: pressureAltitude
  type: string
- container: ''
  name: pressure
  type: string
- container: ''
  name: groundSpeed
  type: string
- container: ''
  name: trueTrack
  type: string
- container: ''
  name: vsiFpm
  type: integer
- container: ''
  name: reportedAtUtc
  type: dateTime
- container: ''
  name: lat
  type: decimal
- container: ''
  name: lon
  type: decimal
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: pageOffset
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: hasNextPage
  type: boolean
- container: ''
  name: code
  type: string
- container: ''
  name: sunElevation
  type: string
- container: ''
  name: sunAzimuth
  type: string
- container: set
  name: dayTime
  type: string
- container: ''
  name: dawnAstronomical
  type: string
- container: ''
  name: dawnNautical
  type: string
- container: ''
  name: dawnCivil
  type: string
- container: ''
  name: sunrise
  type: string
- container: ''
  name: noonTrue
  type: string
- container: ''
  name: sunset
  type: string
- container: ''
  name: duskCivil
  type: string
- container: ''
  name: duskNautical
  type: string
- container: ''
  name: duskAstronomical
  type: string
- container: set
  name: routes
  type: string
- container: ''
  name: kt
  type: decimal
- container: ''
  name: kmPerHour
  type: decimal
- container: ''
  name: miPerHour
  type: decimal
- container: ''
  name: meterPerSecond
  type: decimal
- container: ''
  name: time
  type: string
- container: ''
  name: timeZoneId
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: elevation
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: continent
  type: string
- container: ''
  name: urls
  type: string
- container: set
  name: runways
  type: string
- container: ''
  name: currentTime
  type: string
- container: ''
  name: credits
  type: integer
- container: ''
  name: notificationSummary
  type: string
- container: ''
  name: notificationRemark
  type: string
- container: ''
  name: maxDeliveryRetries
  type: integer
- container: ''
  name: isBlocked
  type: boolean
- container: ''
  name: blockedSince
  type: dateTime
- container: ''
  name: lastBlockedOn
  type: dateTime
- container: set
  name: origins
  type: string
- container: set
  name: destinations
  type: string
- container: ''
  name: percentile
  type: integer
- container: ''
  name: delay
  type: string
- container: ''
  name: meter
  type: decimal
- container: ''
  name: km
  type: decimal
- container: ''
  name: mile
  type: decimal
- container: ''
  name: nm
  type: decimal
- container: ''
  name: feet
  type: decimal
- container: ''
  name: destination
  type: string
- container: ''
  name: averageDailyFlights
  type: decimal
- container: set
  name: operators
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: minAvailableLocalDate
  type: dateTime
- container: ''
  name: maxAvailableLocalDate
  type: dateTime
- container: ''
  name: trueHdg
  type: decimal
- container: ''
  name: length
  type: string
- container: ''
  name: width
  type: string
- container: ''
  name: isClosed
  type: boolean
- container: ''
  name: surface
  type: string
- container: ''
  name: displacedThreshold
  type: string
- container: ''
  name: hasLighting
  type: boolean
- container: set
  name: flights
  type: string
- container: ''
  name: subscription
  type: string
- container: ''
  name: balance
  type: string
- container: ''
  name: creditsRemaining
  type: integer
- container: ''
  name: lastRefilledUtc
  type: dateTime
- container: ''
  name: lastDeductedUtc
  type: dateTime
- container: ''
  name: webUrl
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: license
  type: string
- container: set
  name: htmlAttributions
  type: string
- container: ''
  name: delayedFrom
  type: string
- container: ''
  name: delayedTo
  type: string
- container: ''
  name: num
  type: integer
- container: ''
  name: percentage
  type: decimal
- container: ''
  name: numTotal
  type: integer
- container: ''
  name: numQualifiedTotal
  type: integer
- container: ''
  name: numCancelled
  type: integer
- container: ''
  name: delayIndex
  type: decimal
property_count: 200
provider_name: AeroDataBox
provider_slug: aerodatabox
slug: aerodatabox-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aedbx\": \"https://aerodatabox.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AirportUrlsContract\": \"aedbx:AirportUrlsContract\",\n    \"SpeedFlightPlanUnitContract\": \"aedbx:SpeedFlightPlanUnitContract\",\n    \"SurfaceType\": \"aedbx:SurfaceType\",\n    \"AirportFlightContract\": \"aedbx:AirportFlightContract\",\n    \"FlightAirportMovementContract\": \"aedbx:FlightAirportMovementContract\",\n    \"ListingAirportContract\": \"aedbx:ListingAirportContract\",\n    \"GeoCoordinatesContractListingAirportContractSearchResultCollectionContract\": \"aedbx:GeoCoordinatesContractListingAirportContractSearchResultCollectionContract\",\n    \"Angle\": \"aedbx:Angle\",\n    \"FlightPlanContract\": \"aedbx:FlightPlanContract\",\n    \"ModelFlightTimeEnum\": \"aedbx:ModelFlightTimeEnum\",\n    \"AirportFidsContract\"\
  : \"aedbx:AirportFidsContract\",\n    \"SubscriptionSubjectContract\": \"aedbx:SubscriptionSubjectContract\",\n    \"AirportDelayContract\": \"aedbx:AirportDelayContract\",\n    \"FlightDelayContract\": \"aedbx:FlightDelayContract\",\n    \"AirportFeedServiceStatusContract\": \"aedbx:AirportFeedServiceStatusContract\",\n    \"DistanceFlightPlanUnitContract\": \"aedbx:DistanceFlightPlanUnitContract\",\n    \"DateTimeContract\": \"aedbx:DateTimeContract\",\n    \"FlightAirportMovementQualityEnum\": \"aedbx:FlightAirportMovementQualityEnum\",\n    \"FeedServiceStatus\": \"aedbx:FeedServiceStatus\",\n    \"FlightContract\": \"aedbx:FlightContract\",\n    \"AircraftContract\": \"aedbx:AircraftContract\",\n    \"ErrorContract\": \"aedbx:ErrorContract\",\n    \"SubscriptionContract\": \"aedbx:SubscriptionContract\",\n    \"Pressure\": \"aedbx:Pressure\",\n    \"AirportDistanceTimeContract\": \"aedbx:AirportDistanceTimeContract\",\n    \"FlightAircraftContract\": \"aedbx:FlightAircraftContract\"\
  ,\n    \"SubscriptionSubjectType\": \"aedbx:SubscriptionSubjectType\",\n    \"FlightLocationContract\": \"aedbx:FlightLocationContract\",\n    \"LicenseType\": \"aedbx:LicenseType\",\n    \"StringListingAirportContractSearchResultCollectionContract\": \"aedbx:StringListingAirportContractSearchResultCollectionContract\",\n    \"FlightDirection\": \"aedbx:FlightDirection\",\n    \"GeoCoordinatesContract\": \"aedbx:GeoCoordinatesContract\",\n    \"Azimuth\": \"aedbx:Azimuth\",\n    \"AircraftContractPagedCollectionContract\": \"aedbx:AircraftContractPagedCollectionContract\",\n    \"StringFlightSearchItemContractSearchResultCollectionContract\": \"aedbx:StringFlightSearchItemContractSearchResultCollectionContract\",\n    \"FlightRules\": \"aedbx:FlightRules\",\n    \"ContinentContract\": \"aedbx:ContinentContract\",\n    \"SolarStateContract\": \"aedbx:SolarStateContract\",\n    \"DailyRouteStatContract\": \"aedbx:DailyRouteStatContract\",\n    \"Speed\": \"aedbx:Speed\",\n    \"AirportLocalTimeContract\"\
  : \"aedbx:AirportLocalTimeContract\",\n    \"FlightSearchByEnum\": \"aedbx:FlightSearchByEnum\",\n    \"CountryContract\": \"aedbx:CountryContract\",\n    \"DayTime\": \"aedbx:DayTime\",\n    \"AircraftSearchByEnum\": \"aedbx:AircraftSearchByEnum\",\n    \"FlightType\": \"aedbx:FlightType\",\n    \"AirportContract\": \"aedbx:AirportContract\",\n    \"SubscriptionsBalanceRefillRequestContract\": \"aedbx:SubscriptionsBalanceRefillRequestContract\",\n    \"FlightNotificationItemContract\": \"aedbx:FlightNotificationItemContract\",\n    \"FeedServiceEnum\": \"aedbx:FeedServiceEnum\",\n    \"AirportCodesByEnum\": \"aedbx:AirportCodesByEnum\",\n    \"CreateWebHookSubscription\": \"aedbx:CreateWebHookSubscription\",\n    \"FaaLaddAircraftStatusContract\": \"aedbx:FaaLaddAircraftStatusContract\",\n    \"CodeshareStatus\": \"aedbx:CodeshareStatus\",\n    \"FlightLegDelayContract\": \"aedbx:FlightLegDelayContract\",\n    \"PercentileBracketContract\": \"aedbx:PercentileBracketContract\",\n    \"\
  AircraftRegistrationContract\": \"aedbx:AircraftRegistrationContract\",\n    \"FlightAirlineContract\": \"aedbx:FlightAirlineContract\",\n    \"FlightPlanStatus\": \"aedbx:FlightPlanStatus\",\n    \"Distance\": \"aedbx:Distance\",\n    \"SubscriberContract\": \"aedbx:SubscriberContract\",\n    \"EngineType\": \"aedbx:EngineType\",\n    \"DailyRouteStatRecordContract\": \"aedbx:DailyRouteStatRecordContract\",\n    \"StringCollectionContract\": \"aedbx:StringCollectionContract\",\n    \"SubscriptionBillingType\": \"aedbx:SubscriptionBillingType\",\n    \"FeedServiceStatusContract\": \"aedbx:FeedServiceStatusContract\",\n    \"RunwayContract\": \"aedbx:RunwayContract\",\n    \"StringAircraftContractSearchResultCollectionContract\": \"aedbx:StringAircraftContractSearchResultCollectionContract\",\n    \"FlightNotificationContract\": \"aedbx:FlightNotificationContract\",\n    \"StatisticClass\": \"aedbx:StatisticClass\",\n    \"SubscriptionBalanceContract\": \"aedbx:SubscriptionBalanceContract\"\
  ,\n    \"FlightStatus\": \"aedbx:FlightStatus\",\n    \"FlightSearchItemContract\": \"aedbx:FlightSearchItemContract\",\n    \"ResourceContract\": \"aedbx:ResourceContract\",\n    \"DelayBracketContract\": \"aedbx:DelayBracketContract\",\n    \"FlightDataGeneralAvailabilityContract\": \"aedbx:FlightDataGeneralAvailabilityContract\",\n    \"FlightBatchDelayContract\": \"aedbx:FlightBatchDelayContract\",\n    \"webSite\": {\n      \"@id\": \"aedbx:webSite\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wikipedia\": {\n      \"@id\": \"aedbx:wikipedia\",\n      \"@type\": \"xsd:string\"\n    },\n    \"twitter\": {\n      \"@id\": \"aedbx:twitter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveAtc\": {\n      \"@id\": \"aedbx:liveAtc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightRadar\": {\n      \"@id\": \"aedbx:flightRadar\",\n      \"@type\": \"xsd:string\"\n    },\n    \"googleMaps\": {\n      \"@id\": \"aedbx:googleMaps\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"requested\": {\n      \"@id\": \"aedbx:requested\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assigned\": {\n      \"@id\": \"aedbx:assigned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"movement\": {\n      \"@id\": \"aedbx:movement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"aedbx:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"aedbx:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"aedbx:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callSign\": {\n      \"@id\": \"aedbx:callSign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aedbx:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeshareStatus\": {\n      \"@id\": \"aedbx:codeshareStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isCargo\": {\n      \"@id\": \"aedbx:isCargo\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"aircraft\"\
  : {\n      \"@id\": \"aedbx:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline\": {\n      \"@id\": \"aedbx:airline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"aedbx:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airport\": {\n      \"@id\": \"aedbx:airport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledTime\": {\n      \"@id\": \"aedbx:scheduledTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisedTime\": {\n      \"@id\": \"aedbx:revisedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"predictedTime\": {\n      \"@id\": \"aedbx:predictedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runwayTime\": {\n      \"@id\": \"aedbx:runwayTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"aedbx:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkInDesk\": {\n      \"@id\": \"aedbx:checkInDesk\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"gate\": {\n      \"@id\": \"aedbx:gate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baggageBelt\": {\n      \"@id\": \"aedbx:baggageBelt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runway\": {\n      \"@id\": \"aedbx:runway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality\": {\n      \"@id\": \"aedbx:quality\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icao\": {\n      \"@id\": \"aedbx:icao\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iata\": {\n      \"@id\": \"aedbx:iata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localCode\": {\n      \"@id\": \"aedbx:localCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"shortName\": {\n      \"@id\": \"aedbx:shortName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"municipalityName\": {\n      \"@id\": \"aedbx:municipalityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"aedbx:countryCode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"aedbx:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"searchBy\": {\n      \"@id\": \"aedbx:searchBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"aedbx:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"items\": {\n      \"@id\": \"aedbx:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deg\": {\n      \"@id\": \"aedbx:deg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rad\": {\n      \"@id\": \"aedbx:rad\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"flightRules\": {\n      \"@id\": \"aedbx:flightRules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightType\": {\n      \"@id\": \"aedbx:flightType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionNo\": {\n      \"@id\": \"aedbx:revisionNo\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"route\": {\n      \"@id\": \"aedbx:route\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"altitude\": {\n      \"@id\": \"aedbx:altitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airspeed\": {\n      \"@id\": \"aedbx:airspeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedUtc\": {\n      \"@id\": \"aedbx:lastUpdatedUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"departures\": {\n      \"@id\": \"aedbx:departures\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrivals\": {\n      \"@id\": \"aedbx:arrivals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aedbx:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"aedbx:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airportIcao\": {\n      \"@id\": \"aedbx:airportIcao\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"aedbx:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n \
  \     \"@id\": \"aedbx:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departuresDelayInformation\": {\n      \"@id\": \"aedbx:departuresDelayInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrivalsDelayInformation\": {\n      \"@id\": \"aedbx:arrivalsDelayInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\": \"aedbx:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledHourUtc\": {\n      \"@id\": \"aedbx:scheduledHourUtc\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medianDelay\": {\n      \"@id\": \"aedbx:medianDelay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delayPercentiles\": {\n      \"@id\": \"aedbx:delayPercentiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numConsideredFlights\": {\n      \"@id\": \"aedbx:numConsideredFlights\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numFlightsDelayedBrackets\": {\n      \"@id\": \"aedbx:numFlightsDelayedBrackets\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromUtc\": {\n      \"@id\": \"aedbx:fromUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"toUtc\": {\n      \"@id\": \"aedbx:toUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"flightSchedulesFeed\": {\n      \"@id\": \"aedbx:flightSchedulesFeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveFlightUpdatesFeed\": {\n      \"@id\": \"aedbx:liveFlightUpdatesFeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adsbUpdatesFeed\": {\n      \"@id\": \"aedbx:adsbUpdatesFeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generalAvailability\": {\n      \"@id\": \"aedbx:generalAvailability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utc\": {\n      \"@id\": \"aedbx:utc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"local\": {\n      \"@id\": \"aedbx:local\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"greatCircleDistance\": {\n      \"@id\": \"aedbx:greatCircleDistance\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"flightPlan\": {\n      \"@id\": \"aedbx:flightPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reg\": {\n      \"@id\": \"aedbx:reg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"aedbx:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"serial\": {\n      \"@id\": \"aedbx:serial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hexIcao\": {\n      \"@id\": \"aedbx:hexIcao\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airlineName\": {\n      \"@id\": \"aedbx:airlineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataType\": {\n      \"@id\": \"aedbx:iataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCodeShort\": {\n      \"@id\": \"aedbx:iataCodeShort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icaoCode\": {\n      \"@id\": \"aedbx:icaoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"aedbx:model\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"modelCode\": {\n      \"@id\": \"aedbx:modelCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numSeats\": {\n      \"@id\": \"aedbx:numSeats\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rolloutDate\": {\n      \"@id\": \"aedbx:rolloutDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firstFlightDate\": {\n      \"@id\": \"aedbx:firstFlightDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"aedbx:deliveryDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"registrationDate\": {\n      \"@id\": \"aedbx:registrationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"typeName\": {\n      \"@id\": \"aedbx:typeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numEngines\": {\n      \"@id\": \"aedbx:numEngines\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"engineType\": {\n      \"@id\": \"aedbx:engineType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFreighter\": {\n      \"@id\": \"aedbx:isFreighter\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"productionLine\": {\n      \"@id\": \"aedbx:productionLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ageYears\": {\n      \"@id\": \"aedbx:ageYears\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"verified\": {\n      \"@id\": \"aedbx:verified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"image\": {\n      \"@id\": \"aedbx:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numRegistrations\": {\n      \"@id\": \"aedbx:numRegistrations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"registrations\": {\n      \"@id\": \"aedbx:registrations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"aedbx:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isActive\": {\n      \"@id\": \"aedbx:isActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"billingType\": {\n      \"@id\": \"aedbx:billingType\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"activateBeforeUtc\": {\n      \"@id\": \"aedbx:activateBeforeUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expiresOnUtc\": {\n      \"@id\": \"aedbx:expiresOnUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdOnUtc\": {\n      \"@id\": \"aedbx:createdOnUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"subject\": {\n      \"@id\": \"aedbx:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriber\": {\n      \"@id\": \"aedbx:subscriber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notices\": {\n      \"@id\": \"aedbx:notices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hPa\": {\n      \"@id\": \"aedbx:hPa\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"inHg\": {\n      \"@id\": \"aedbx:inHg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"mmHg\": {\n      \"@id\": \"aedbx:mmHg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"approxFlightTime\": {\n      \"@id\": \"aedbx:approxFlightTime\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"modeS\": {\n      \"@id\": \"aedbx:modeS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pressureAltitude\": {\n      \"@id\": \"aedbx:pressureAltitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pressure\": {\n      \"@id\": \"aedbx:pressure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundSpeed\": {\n      \"@id\": \"aedbx:groundSpeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trueTrack\": {\n      \"@id\": \"aedbx:trueTrack\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vsiFpm\": {\n      \"@id\": \"aedbx:vsiFpm\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reportedAtUtc\": {\n      \"@id\": \"aedbx:reportedAtUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lat\": {\n      \"@id\": \"aedbx:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lon\": {\n      \"@id\": \"aedbx:lon\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalCount\": {\n      \"@id\": \"aedbx:totalCount\",\n   \
  \   \"@type\": \"xsd:integer\"\n    },\n    \"pageOffset\": {\n      \"@id\": \"aedbx:pageOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"aedbx:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hasNextPage\": {\n      \"@id\": \"aedbx:hasNextPage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"code\": {\n      \"@id\": \"aedbx:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunElevation\": {\n      \"@id\": \"aedbx:sunElevation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunAzimuth\": {\n      \"@id\": \"aedbx:sunAzimuth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayTime\": {\n      \"@id\": \"aedbx:dayTime\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dawnAstronomical\": {\n      \"@id\": \"aedbx:dawnAstronomical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dawnNautical\": {\n      \"@id\": \"aedbx:dawnNautical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  dawnCivil\": {\n      \"@id\": \"aedbx:dawnCivil\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunrise\": {\n      \"@id\": \"aedbx:sunrise\",\n      \"@type\": \"xsd:string\"\n    },\n    \"noonTrue\": {\n      \"@id\": \"aedbx:noonTrue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunset\": {\n      \"@id\": \"aedbx:sunset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duskCivil\": {\n      \"@id\": \"aedbx:duskCivil\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duskNautical\": {\n      \"@id\": \"aedbx:duskNautical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duskAstronomical\": {\n      \"@id\": \"aedbx:duskAstronomical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routes\": {\n      \"@id\": \"aedbx:routes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kt\": {\n      \"@id\": \"aedbx:kt\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"kmPerHour\": {\n      \"@id\": \"aedbx:kmPerHour\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"miPerHour\": {\n      \"@id\": \"aedbx:miPerHour\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"meterPerSecond\": {\n      \"@id\": \"aedbx:meterPerSecond\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"time\": {\n      \"@id\": \"aedbx:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZoneId\": {\n      \"@id\": \"aedbx:timeZoneId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"aedbx:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elevation\": {\n      \"@id\": \"aedbx:elevation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"aedbx:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"continent\": {\n      \"@id\": \"aedbx:continent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urls\": {\n      \"@id\": \"aedbx:urls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runways\": {\n      \"@id\": \"aedbx:runways\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"currentTime\": {\n      \"@id\": \"aedbx:currentTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credits\": {\n      \"@id\": \"aedbx:credits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notificationSummary\": {\n      \"@id\": \"aedbx:notificationSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationRemark\": {\n      \"@id\": \"aedbx:notificationRemark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"maxDeliveryRetries\": {\n      \"@id\": \"aedbx:maxDeliveryRetries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isBlocked\": {\n      \"@id\": \"aedbx:isBlocked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"blockedSince\": {\n      \"@id\": \"aedbx:blockedSince\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastBlockedOn\": {\n      \"@id\": \"aedbx:lastBlockedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"origins\": {\n      \"@id\": \"aedbx:origins\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinations\": {\n      \"@id\": \"aedbx:destinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentile\": {\n      \"@id\": \"aedbx:percentile\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"delay\": {\n      \"@id\": \"aedbx:delay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meter\": {\n      \"@id\": \"aedbx:meter\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"km\": {\n      \"@id\": \"aedbx:km\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"mile\": {\n      \"@id\": \"aedbx:mile\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"nm\": {\n      \"@id\": \"aedbx:nm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"feet\": {\n      \"@id\": \"aedbx:feet\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"destination\": {\n      \"@id\": \"aedbx:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"averageDailyFlights\": {\n      \"@id\": \"aedbx:averageDailyFlights\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"operators\": {\n      \"@id\": \"aedbx:operators\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"aedbx:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minAvailableLocalDate\": {\n      \"@id\": \"aedbx:minAvailableLocalDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"maxAvailableLocalDate\": {\n      \"@id\": \"aedbx:maxAvailableLocalDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"trueHdg\": {\n      \"@id\": \"aedbx:trueHdg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"length\": {\n      \"@id\": \"aedbx:length\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"aedbx:width\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isClosed\": {\n      \"@id\": \"aedbx:isClosed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"surface\": {\n      \"@id\": \"aedbx:surface\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"displacedThreshold\": {\n      \"@id\": \"aedbx:displacedThreshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasLighting\": {\n      \"@id\": \"aedbx:hasLighting\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"flights\": {\n      \"@id\": \"aedbx:flights\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription\": {\n      \"@id\": \"aedbx:subscription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balance\": {\n      \"@id\": \"aedbx:balance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditsRemaining\": {\n      \"@id\": \"aedbx:creditsRemaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastRefilledUtc\": {\n      \"@id\": \"aedbx:lastRefilledUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastDeductedUtc\": {\n      \"@id\": \"aedbx:lastDeductedUtc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"webUrl\": {\n      \"@id\": \"aedbx:webUrl\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"author\": {\n      \"@id\": \"aedbx:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"aedbx:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"license\": {\n      \"@id\": \"aedbx:license\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htmlAttributions\": {\n      \"@id\": \"aedbx:htmlAttributions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delayedFrom\": {\n      \"@id\": \"aedbx:delayedFrom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delayedTo\": {\n      \"@id\": \"aedbx:delayedTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"num\": {\n      \"@id\": \"aedbx:num\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"percentage\": {\n      \"@id\": \"aedbx:percentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"numTotal\": {\n      \"@id\": \"aedbx:numTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numQualifiedTotal\": {\n\
  \      \"@id\": \"aedbx:numQualifiedTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numCancelled\": {\n      \"@id\": \"aedbx:numCancelled\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"delayIndex\": {\n      \"@id\": \"aedbx:delayIndex\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aerodatabox/refs/heads/main/json-ld/aerodatabox-context.jsonld
tags:
- Aviation
- Flights
- Aerospace
- Flight Data
- Airport Data
- JSON-LD
- Linked Data
- Semantic Web
---
