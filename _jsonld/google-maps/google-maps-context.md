---
api_specs:
- filename: google-maps-geocoding-api.yml
  format: yaml
  label: Geocoding API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-maps/refs/heads/main/openapi/google-maps-geocoding-api.yml
- filename: google-maps-places-api.yml
  format: yaml
  label: Places API (New)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-maps/refs/heads/main/openapi/google-maps-places-api.yml
- filename: google-maps-directions-api.yml
  format: yaml
  label: Directions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-maps/refs/heads/main/openapi/google-maps-directions-api.yml
class_count: 11
classes:
- Place
- LocalBusiness
- PostalAddress
- GeoCoordinates
- OpeningHoursSpecification
- AggregateRating
- Review
- Person
- ImageObject
- id
- type
context_file: json-ld/google-maps-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-maps/refs/heads/main/json-ld/google-maps-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Maps from Google Maps Platform.
layout: jsonld
name: Google Maps Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: goog
  uri: https://developers.google.com/maps/terms#
- prefix: gmaps
  uri: https://developers.google.com/maps/documentation/places/web-service/reference/rest/v1/places#
properties:
- container: ''
  name: placeId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: formattedAddress
  type: string
- container: ''
  name: shortFormattedAddress
  type: string
- container: list
  name: addressComponents
  type: ''
- container: ''
  name: longText
  type: string
- container: ''
  name: shortText
  type: string
- container: ''
  name: location
  type: reference
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: lat
  type: double
- container: ''
  name: lng
  type: double
- container: ''
  name: viewport
  type: reference
- container: ''
  name: northeast
  type: reference
- container: ''
  name: southwest
  type: reference
- container: ''
  name: rating
  type: double
- container: ''
  name: userRatingCount
  type: integer
- container: ''
  name: aggregateRating
  type: AggregateRating
- container: ''
  name: nationalPhoneNumber
  type: string
- container: ''
  name: internationalPhoneNumber
  type: string
- container: ''
  name: websiteUri
  type: reference
- container: ''
  name: googleMapsUri
  type: reference
- container: set
  name: types
  type: ''
- container: ''
  name: primaryType
  type: string
- container: ''
  name: regularOpeningHours
  type: OpeningHoursSpecification
- container: ''
  name: currentOpeningHours
  type: OpeningHoursSpecification
- container: ''
  name: openNow
  type: boolean
- container: list
  name: weekdayDescriptions
  type: ''
- container: ''
  name: priceLevel
  type: string
- container: ''
  name: businessStatus
  type: string
- container: list
  name: reviews
  type: ''
- container: ''
  name: reviewRating
  type: schema:Rating
- container: ''
  name: reviewBody
  type: string
- container: ''
  name: authorAttribution
  type: Person
- container: ''
  name: publishTime
  type: dateTime
- container: list
  name: photos
  type: ''
- container: ''
  name: widthPx
  type: integer
- container: ''
  name: heightPx
  type: integer
- container: ''
  name: editorialSummary
  type: string
- container: ''
  name: plusCode
  type: reference
- container: ''
  name: globalCode
  type: string
- container: ''
  name: compoundCode
  type: string
- container: ''
  name: dineIn
  type: boolean
- container: ''
  name: takeout
  type: boolean
- container: ''
  name: delivery
  type: boolean
- container: ''
  name: curbsidePickup
  type: boolean
- container: ''
  name: reservable
  type: boolean
- container: ''
  name: servesBreakfast
  type: boolean
- container: ''
  name: servesLunch
  type: boolean
- container: ''
  name: servesDinner
  type: boolean
- container: ''
  name: servesBeer
  type: boolean
- container: ''
  name: servesWine
  type: boolean
- container: ''
  name: servesVegetarianFood
  type: boolean
- container: ''
  name: accessibilityOptions
  type: reference
- container: ''
  name: wheelchairAccessibleParking
  type: boolean
- container: ''
  name: wheelchairAccessibleEntrance
  type: boolean
- container: ''
  name: wheelchairAccessibleRestroom
  type: boolean
- container: ''
  name: wheelchairAccessibleSeating
  type: boolean
- container: ''
  name: parkingOptions
  type: reference
- container: ''
  name: paymentOptions
  type: reference
- container: ''
  name: formatted_address
  type: string
- container: list
  name: address_components
  type: ''
- container: ''
  name: long_name
  type: string
- container: ''
  name: short_name
  type: string
- container: ''
  name: geometry
  type: reference
- container: ''
  name: location_type
  type: string
- container: ''
  name: place_id
  type: string
- container: ''
  name: partial_match
  type: boolean
- container: ''
  name: plus_code
  type: reference
- container: ''
  name: global_code
  type: string
- container: ''
  name: compound_code
  type: string
- container: ''
  name: utcOffsetMinutes
  type: integer
- container: ''
  name: iconMaskBaseUri
  type: reference
- container: ''
  name: iconBackgroundColor
  type: string
- container: ''
  name: adrFormatAddress
  type: string
property_count: 75
provider_name: Google Maps Platform
provider_slug: google-maps
slug: google-maps-context
source_filename: google-maps-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"goog\": \"https://developers.google.com/maps/terms#\",\n    \"gmaps\": \"https://developers.google.com/maps/documentation/places/web-service/reference/rest/v1/places#\",\n\n    \"Place\": \"schema:Place\",\n    \"LocalBusiness\": \"schema:LocalBusiness\",\n    \"PostalAddress\": \"schema:PostalAddress\",\n    \"GeoCoordinates\": \"schema:GeoCoordinates\",\n    \"OpeningHoursSpecification\": \"schema:OpeningHoursSpecification\",\n    \"AggregateRating\": \"schema:AggregateRating\",\n    \"Review\": \"schema:Review\",\n    \"Person\": \"schema:Person\",\n    \"ImageObject\": \"schema:ImageObject\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"placeId\": {\n      \"@id\": \"gmaps:placeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n \
  \     \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formattedAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortFormattedAddress\": {\n      \"@id\": \"gmaps:shortFormattedAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressComponents\": {\n      \"@id\": \"gmaps:addressComponents\",\n      \"@container\": \"@list\"\n    },\n    \"longText\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortText\": {\n      \"@id\": \"schema:alternateName\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"location\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"@id\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lat\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lng\": {\n    \
  \  \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n\n    \"viewport\": {\n      \"@id\": \"gmaps:viewport\",\n      \"@type\": \"@id\"\n    },\n    \"northeast\": {\n      \"@id\": \"gmaps:northeast\",\n      \"@type\": \"@id\"\n    },\n    \"southwest\": {\n      \"@id\": \"gmaps:southwest\",\n      \"@type\": \"@id\"\n    },\n\n    \"rating\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:double\"\n    },\n    \"userRatingCount\": {\n      \"@id\": \"schema:ratingCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"aggregateRating\": {\n      \"@id\": \"schema:aggregateRating\",\n      \"@type\": \"AggregateRating\"\n    },\n\n    \"nationalPhoneNumber\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internationalPhoneNumber\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"websiteUri\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"\
  googleMapsUri\": {\n      \"@id\": \"schema:hasMap\",\n      \"@type\": \"@id\"\n    },\n\n    \"types\": {\n      \"@id\": \"schema:additionalType\",\n      \"@container\": \"@set\"\n    },\n    \"primaryType\": {\n      \"@id\": \"gmaps:primaryType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"regularOpeningHours\": {\n      \"@id\": \"schema:openingHoursSpecification\",\n      \"@type\": \"OpeningHoursSpecification\"\n    },\n    \"currentOpeningHours\": {\n      \"@id\": \"gmaps:currentOpeningHours\",\n      \"@type\": \"OpeningHoursSpecification\"\n    },\n    \"openNow\": {\n      \"@id\": \"gmaps:openNow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"weekdayDescriptions\": {\n      \"@id\": \"schema:openingHours\",\n      \"@container\": \"@list\"\n    },\n\n    \"priceLevel\": {\n      \"@id\": \"schema:priceRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessStatus\": {\n      \"@id\": \"gmaps:businessStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \n    \"reviews\": {\n      \"@id\": \"schema:review\",\n      \"@container\": \"@list\"\n    },\n    \"reviewRating\": {\n      \"@id\": \"schema:reviewRating\",\n      \"@type\": \"schema:Rating\"\n    },\n    \"reviewBody\": {\n      \"@id\": \"schema:reviewBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorAttribution\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"Person\"\n    },\n    \"publishTime\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"photos\": {\n      \"@id\": \"schema:photo\",\n      \"@container\": \"@list\"\n    },\n    \"widthPx\": {\n      \"@id\": \"schema:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"heightPx\": {\n      \"@id\": \"schema:height\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"editorialSummary\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"plusCode\": {\n      \"@id\": \"gmaps:plusCode\",\n      \"@type\":\
  \ \"@id\"\n    },\n    \"globalCode\": {\n      \"@id\": \"gmaps:globalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compoundCode\": {\n      \"@id\": \"gmaps:compoundCode\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"dineIn\": {\n      \"@id\": \"gmaps:dineIn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"takeout\": {\n      \"@id\": \"gmaps:takeout\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"delivery\": {\n      \"@id\": \"gmaps:delivery\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"curbsidePickup\": {\n      \"@id\": \"gmaps:curbsidePickup\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reservable\": {\n      \"@id\": \"schema:acceptsReservations\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"servesBreakfast\": {\n      \"@id\": \"gmaps:servesBreakfast\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"servesLunch\": {\n      \"@id\": \"gmaps:servesLunch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"servesDinner\": {\n      \"@id\"\
  : \"gmaps:servesDinner\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"servesBeer\": {\n      \"@id\": \"gmaps:servesBeer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"servesWine\": {\n      \"@id\": \"gmaps:servesWine\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"servesVegetarianFood\": {\n      \"@id\": \"gmaps:servesVegetarianFood\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"accessibilityOptions\": {\n      \"@id\": \"schema:accessibilityFeature\",\n      \"@type\": \"@id\"\n    },\n    \"wheelchairAccessibleParking\": {\n      \"@id\": \"gmaps:wheelchairAccessibleParking\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"wheelchairAccessibleEntrance\": {\n      \"@id\": \"gmaps:wheelchairAccessibleEntrance\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"wheelchairAccessibleRestroom\": {\n      \"@id\": \"gmaps:wheelchairAccessibleRestroom\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"wheelchairAccessibleSeating\": {\n      \"@id\": \"gmaps:wheelchairAccessibleSeating\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"parkingOptions\": {\n      \"@id\": \"schema:amenityFeature\",\n      \"@type\": \"@id\"\n    },\n    \"paymentOptions\": {\n      \"@id\": \"schema:paymentAccepted\",\n      \"@type\": \"@id\"\n    },\n\n    \"formatted_address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address_components\": {\n      \"@id\": \"gmaps:addressComponents\",\n      \"@container\": \"@list\"\n    },\n    \"long_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"short_name\": {\n      \"@id\": \"schema:alternateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geometry\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"@id\"\n    },\n    \"location_type\": {\n      \"@id\": \"gmaps:locationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"place_id\": {\n      \"@id\": \"gmaps:placeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partial_match\": {\n\
  \      \"@id\": \"gmaps:partialMatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"plus_code\": {\n      \"@id\": \"gmaps:plusCode\",\n      \"@type\": \"@id\"\n    },\n    \"global_code\": {\n      \"@id\": \"gmaps:globalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compound_code\": {\n      \"@id\": \"gmaps:compoundCode\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"utcOffsetMinutes\": {\n      \"@id\": \"gmaps:utcOffsetMinutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"iconMaskBaseUri\": {\n      \"@id\": \"gmaps:iconMaskBaseUri\",\n      \"@type\": \"@id\"\n    },\n    \"iconBackgroundColor\": {\n      \"@id\": \"gmaps:iconBackgroundColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adrFormatAddress\": {\n      \"@id\": \"gmaps:adrFormatAddress\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-maps/refs/heads/main/json-ld/google-maps-context.jsonld
tags:
- Environment
- Geocoding
- Geolocation
- Maps
- Navigation
- Places
- Routing
- Solar
- JSON-LD
- Linked Data
- Semantic Web
---
