---
api_specs:
- filename: amc-theatres-api-openapi.yml
  format: yaml
  label: AMC Theatres API
  slug: amc-theatres-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amc-entertainment-holdings/refs/heads/main/openapi/amc-theatres-api-openapi.yml
class_count: 53
classes:
- Theatre
- Movie
- Showtime
- Order
- Payment
- TicketPrice
- LoyaltyAccount
- LoyaltyCard
- Concession
- ConcessionCategory
- Attribute
- Location
- Market
- State
- SeatingLayout
- Seat
- MediaItem
- id
- name
- longName
- secondaryLongName
- synopsis
- synopsisTagLine
- genre
- mpaaRating
- priceType
- sku
- addressLine1
- city
- state
- stateName
- postalCode
- country
- marketName
- showtimesPhoneNumber
- guestServicesPhoneNumber
- websiteUrl
- facebookUrl
- directionsUrl
- loyaltyVersion
- brand
- westWorldMediaTheatreNumber
- code
- shortDescription
- longDescription
- orderId
- token
- status
- productType
- cardNumber
- loyaltyTier
- _embedded
- _links
context_file: json-ld/amc-entertainment-holdings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amc-entertainment-holdings/refs/heads/main/json-ld/amc-entertainment-holdings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amc Entertainment Holdings from AMC Entertainment Holdings.
layout: jsonld
name: Amc Entertainment Holdings Context
namespaces:
- prefix: amc
  uri: https://developers.amctheatres.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: slug
  type: string
- container: ''
  name: runTime
  type: integer
- container: ''
  name: releaseDateUtc
  type: dateTime
- container: ''
  name: earliestShowingUtc
  type: dateTime
- container: ''
  name: showDateTimeUtc
  type: dateTime
- container: ''
  name: showDateTimeLocal
  type: string
- container: ''
  name: utcOffset
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: auditorium
  type: integer
- container: ''
  name: isSoldOut
  type: boolean
- container: ''
  name: isAlmostSoldOut
  type: boolean
- container: ''
  name: isCanceled
  type: boolean
- container: ''
  name: purchaseUrl
  type: reference
- container: set
  name: ticketPrices
  type: ''
- container: ''
  name: price
  type: decimal
- container: ''
  name: tax
  type: decimal
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: marketId
  type: integer
- container: ''
  name: isClosed
  type: boolean
- container: set
  name: concessionsDeliveryOptions
  type: ''
- container: ''
  name: onlineConcessions
  type: boolean
- container: set
  name: redemptionMethods
  type: ''
- container: set
  name: attributes
  type: ''
- container: ''
  name: appliesToMovie
  type: boolean
- container: ''
  name: appliesToShowtime
  type: boolean
- container: ''
  name: appliesToTheatre
  type: boolean
- container: ''
  name: amcAccountId
  type: string
- container: ''
  name: createdUtc
  type: dateTime
- container: ''
  name: expirationUtc
  type: dateTime
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: totalTax
  type: decimal
- container: ''
  name: totalConvenienceFees
  type: decimal
- container: set
  name: products
  type: ''
- container: set
  name: payments
  type: ''
- container: ''
  name: lineNumber
  type: integer
- container: ''
  name: quantity
  type: integer
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: totalPrice
  type: decimal
- container: ''
  name: showtimeId
  type: integer
- container: set
  name: seatIds
  type: ''
- container: ''
  name: deliveryLocationId
  type: integer
- container: ''
  name: pickupTime
  type: dateTime
- container: ''
  name: deliveryTime
  type: dateTime
- container: ''
  name: pointsBalance
  type: integer
- container: set
  name: rewards
  type: ''
- container: set
  name: registrations
  type: ''
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: pageNumber
  type: integer
- container: ''
  name: count
  type: integer
property_count: 50
provider_name: AMC Entertainment Holdings
provider_slug: amc-entertainment-holdings
slug: amc-entertainment-holdings-context
source_filename: amc-entertainment-holdings-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amc\": \"https://developers.amctheatres.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Theatre\": \"schema:MovieTheater\",\n    \"Movie\": \"schema:Movie\",\n    \"Showtime\": \"schema:ScreeningEvent\",\n    \"Order\": \"schema:Order\",\n    \"Payment\": \"schema:PaymentMethod\",\n    \"TicketPrice\": \"schema:PriceSpecification\",\n    \"LoyaltyAccount\": \"schema:ProgramMembership\",\n    \"LoyaltyCard\": \"amc:LoyaltyCard\",\n    \"Concession\": \"schema:MenuItem\",\n    \"ConcessionCategory\": \"schema:MenuSection\",\n    \"Attribute\": \"amc:Attribute\",\n    \"Location\": \"schema:Place\",\n    \"Market\": \"amc:Market\",\n    \"State\": \"schema:State\",\n    \"SeatingLayout\": \"amc:SeatingLayout\",\n    \"Seat\": \"schema:Seat\",\n    \"MediaItem\": \"schema:MediaObject\",\n\n    \"id\": \"@id\"\
  ,\n    \"name\": \"schema:name\",\n    \"longName\": \"amc:longName\",\n    \"secondaryLongName\": \"amc:secondaryLongName\",\n    \"slug\": { \"@id\": \"amc:slug\", \"@type\": \"xsd:string\" },\n    \"synopsis\": \"schema:description\",\n    \"synopsisTagLine\": \"amc:tagLine\",\n    \"genre\": \"schema:genre\",\n    \"mpaaRating\": \"schema:contentRating\",\n    \"runTime\": { \"@id\": \"schema:duration\", \"@type\": \"xsd:integer\" },\n    \"releaseDateUtc\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n    \"earliestShowingUtc\": { \"@id\": \"amc:earliestShowingUtc\", \"@type\": \"xsd:dateTime\" },\n    \"showDateTimeUtc\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\" },\n    \"showDateTimeLocal\": { \"@id\": \"amc:showDateTimeLocal\", \"@type\": \"xsd:string\" },\n    \"utcOffset\": { \"@id\": \"amc:utcOffset\", \"@type\": \"xsd:string\" },\n    \"timezone\": { \"@id\": \"schema:timeZone\", \"@type\": \"xsd:string\" },\n    \"auditorium\": {\
  \ \"@id\": \"amc:auditorium\", \"@type\": \"xsd:integer\" },\n    \"isSoldOut\": { \"@id\": \"amc:isSoldOut\", \"@type\": \"xsd:boolean\" },\n    \"isAlmostSoldOut\": { \"@id\": \"amc:isAlmostSoldOut\", \"@type\": \"xsd:boolean\" },\n    \"isCanceled\": { \"@id\": \"schema:eventStatus\", \"@type\": \"xsd:boolean\" },\n    \"purchaseUrl\": { \"@id\": \"schema:offers\", \"@type\": \"@id\" },\n    \"ticketPrices\": { \"@id\": \"schema:offers\", \"@container\": \"@set\" },\n    \"priceType\": \"amc:priceType\",\n    \"price\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"tax\": { \"@id\": \"amc:tax\", \"@type\": \"xsd:decimal\" },\n    \"sku\": \"schema:sku\",\n\n    \"addressLine1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"stateName\": \"amc:stateName\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"latitude\": { \"@id\": \"schema:latitude\"\
  , \"@type\": \"xsd:double\" },\n    \"longitude\": { \"@id\": \"schema:longitude\", \"@type\": \"xsd:double\" },\n    \"marketName\": \"amc:marketName\",\n    \"marketId\": { \"@id\": \"amc:marketId\", \"@type\": \"xsd:integer\" },\n\n    \"showtimesPhoneNumber\": \"schema:telephone\",\n    \"guestServicesPhoneNumber\": \"amc:guestServicesPhoneNumber\",\n    \"websiteUrl\": \"schema:url\",\n    \"facebookUrl\": \"amc:facebookUrl\",\n    \"directionsUrl\": \"amc:directionsUrl\",\n    \"loyaltyVersion\": \"amc:loyaltyVersion\",\n    \"isClosed\": { \"@id\": \"amc:isClosed\", \"@type\": \"xsd:boolean\" },\n    \"brand\": \"schema:brand\",\n    \"westWorldMediaTheatreNumber\": \"amc:wwmTheatreNumber\",\n    \"concessionsDeliveryOptions\": { \"@id\": \"amc:concessionsDeliveryOptions\", \"@container\": \"@set\" },\n    \"onlineConcessions\": { \"@id\": \"amc:onlineConcessions\", \"@type\": \"xsd:boolean\" },\n    \"redemptionMethods\": { \"@id\": \"amc:redemptionMethods\", \"@container\": \"\
  @set\" },\n    \"attributes\": { \"@id\": \"amc:attributes\", \"@container\": \"@set\" },\n\n    \"code\": \"amc:code\",\n    \"shortDescription\": \"amc:shortDescription\",\n    \"longDescription\": \"amc:longDescription\",\n    \"appliesToMovie\": { \"@id\": \"amc:appliesToMovie\", \"@type\": \"xsd:boolean\" },\n    \"appliesToShowtime\": { \"@id\": \"amc:appliesToShowtime\", \"@type\": \"xsd:boolean\" },\n    \"appliesToTheatre\": { \"@id\": \"amc:appliesToTheatre\", \"@type\": \"xsd:boolean\" },\n\n    \"orderId\": \"@id\",\n    \"token\": \"amc:token\",\n    \"amcAccountId\": { \"@id\": \"amc:amcAccountId\", \"@type\": \"xsd:string\" },\n    \"status\": \"schema:orderStatus\",\n    \"createdUtc\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"expirationUtc\": { \"@id\": \"amc:expirationUtc\", \"@type\": \"xsd:dateTime\" },\n    \"totalAmount\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:decimal\" },\n    \"totalTax\": { \"@id\": \"amc:totalTax\"\
  , \"@type\": \"xsd:decimal\" },\n    \"totalConvenienceFees\": { \"@id\": \"amc:totalConvenienceFees\", \"@type\": \"xsd:decimal\" },\n    \"products\": { \"@id\": \"schema:orderedItem\", \"@container\": \"@set\" },\n    \"payments\": { \"@id\": \"schema:paymentMethod\", \"@container\": \"@set\" },\n    \"lineNumber\": { \"@id\": \"amc:lineNumber\", \"@type\": \"xsd:integer\" },\n    \"productType\": \"amc:productType\",\n    \"quantity\": { \"@id\": \"schema:orderQuantity\", \"@type\": \"xsd:integer\" },\n    \"unitPrice\": { \"@id\": \"amc:unitPrice\", \"@type\": \"xsd:decimal\" },\n    \"totalPrice\": { \"@id\": \"amc:totalPrice\", \"@type\": \"xsd:decimal\" },\n    \"showtimeId\": { \"@id\": \"amc:showtimeId\", \"@type\": \"xsd:integer\" },\n    \"seatIds\": { \"@id\": \"amc:seatIds\", \"@container\": \"@set\" },\n    \"deliveryLocationId\": { \"@id\": \"amc:deliveryLocationId\", \"@type\": \"xsd:integer\" },\n    \"pickupTime\": { \"@id\": \"amc:pickupTime\", \"@type\": \"xsd:dateTime\"\
  \ },\n    \"deliveryTime\": { \"@id\": \"amc:deliveryTime\", \"@type\": \"xsd:dateTime\" },\n\n    \"cardNumber\": \"amc:cardNumber\",\n    \"loyaltyTier\": \"amc:loyaltyTier\",\n    \"pointsBalance\": { \"@id\": \"amc:pointsBalance\", \"@type\": \"xsd:integer\" },\n    \"rewards\": { \"@id\": \"amc:rewards\", \"@container\": \"@set\" },\n    \"registrations\": { \"@id\": \"amc:registrations\", \"@container\": \"@set\" },\n\n    \"pageSize\": { \"@id\": \"amc:pageSize\", \"@type\": \"xsd:integer\" },\n    \"pageNumber\": { \"@id\": \"amc:pageNumber\", \"@type\": \"xsd:integer\" },\n    \"count\": { \"@id\": \"amc:count\", \"@type\": \"xsd:integer\" },\n    \"_embedded\": \"amc:embedded\",\n    \"_links\": \"amc:links\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amc-entertainment-holdings/refs/heads/main/json-ld/amc-entertainment-holdings-context.jsonld
tags:
- Entertainment
- Movies
- Theatres
- Showtimes
- Ticketing
- Concessions
- Loyalty
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
