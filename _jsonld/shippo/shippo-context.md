---
api_specs:
- filename: shippo-openapi.yml
  format: yaml
  label: Shippo API
  slug: shippo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/openapi/shippo-openapi.yml
class_count: 41
classes:
- Shipment
- Transaction
- Rate
- Parcel
- TrackingStatus
- CarrierAccount
- Refund
- Webhook
- object_id
- status
- metadata
- name
- company
- street1
- street2
- city
- state
- zip
- country
- phone
- email
- is_residential
- is_complete
- distance_unit
- weight
- mass_unit
- template
- currency
- amount_local
- currency_local
- provider
- servicelevel
- arrives_by
- trackable
- tracking_number
- tracking_status
- carrier
- tracking_history
- label_file_type
- active
- event
context_file: json-ld/shippo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/json-ld/shippo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shippo from Shippo.
layout: jsonld
name: Shippo Context
namespaces:
- prefix: shippo
  uri: https://api.goshippo.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: object_created
  type: dateTime
- container: ''
  name: object_updated
  type: dateTime
- container: ''
  name: address_from
  type: schema:PostalAddress
- container: ''
  name: address_to
  type: schema:PostalAddress
- container: ''
  name: address_return
  type: schema:PostalAddress
- container: list
  name: parcels
  type: ''
- container: list
  name: rates
  type: ''
- container: ''
  name: length
  type: string
- container: ''
  name: width
  type: string
- container: ''
  name: height
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: days
  type: integer
- container: ''
  name: tracking_url_provider
  type: reference
- container: ''
  name: label_url
  type: reference
- container: ''
  name: eta
  type: dateTime
- container: ''
  name: rate
  type: shippo:Rate
- container: ''
  name: transaction
  type: shippo:Transaction
- container: ''
  name: url
  type: reference
property_count: 18
provider_name: Shippo
provider_slug: shippo
slug: shippo-context
source_filename: shippo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"shippo\": \"https://api.goshippo.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Shipment\": \"shippo:Shipment\",\n    \"Transaction\": \"shippo:Transaction\",\n    \"Rate\": \"shippo:Rate\",\n    \"Parcel\": \"shippo:Parcel\",\n    \"TrackingStatus\": \"shippo:TrackingStatus\",\n    \"CarrierAccount\": \"shippo:CarrierAccount\",\n    \"Refund\": \"shippo:Refund\",\n    \"Webhook\": \"shippo:Webhook\",\n\n    \"object_id\": \"schema:identifier\",\n    \"status\": \"schema:status\",\n    \"metadata\": \"schema:description\",\n    \"object_created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"object_updated\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n\n    \"address_from\": { \"@id\": \"schema:sender\", \"@type\": \"schema:PostalAddress\" },\n    \"address_to\": { \"@id\": \"schema:recipient\", \"@type\": \"schema:PostalAddress\"\
  \ },\n    \"address_return\": { \"@id\": \"shippo:returnAddress\", \"@type\": \"schema:PostalAddress\" },\n    \"parcels\": { \"@id\": \"shippo:parcels\", \"@container\": \"@list\" },\n    \"rates\": { \"@id\": \"shippo:rates\", \"@container\": \"@list\" },\n\n    \"name\": \"schema:name\",\n    \"company\": \"schema:legalName\",\n    \"street1\": \"schema:streetAddress\",\n    \"street2\": \"shippo:streetAddress2\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"phone\": \"schema:telephone\",\n    \"email\": \"schema:email\",\n    \"is_residential\": \"shippo:isResidential\",\n    \"is_complete\": \"shippo:isComplete\",\n\n    \"length\": { \"@id\": \"schema:depth\", \"@type\": \"xsd:string\" },\n    \"width\": { \"@id\": \"schema:width\", \"@type\": \"xsd:string\" },\n    \"height\": { \"@id\": \"schema:height\", \"@type\": \"xsd:string\" },\n    \"distance_unit\"\
  : \"schema:unitCode\",\n    \"weight\": \"schema:weight\",\n    \"mass_unit\": \"schema:unitCode\",\n    \"template\": \"schema:additionalType\",\n\n    \"amount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:string\" },\n    \"currency\": \"schema:priceCurrency\",\n    \"amount_local\": \"shippo:amountLocal\",\n    \"currency_local\": \"shippo:currencyLocal\",\n    \"provider\": \"schema:provider\",\n    \"servicelevel\": \"shippo:serviceLevel\",\n    \"days\": { \"@id\": \"schema:transitTime\", \"@type\": \"xsd:integer\" },\n    \"arrives_by\": \"shippo:arrivesBy\",\n    \"trackable\": \"shippo:isTrackable\",\n\n    \"tracking_number\": \"schema:trackingNumber\",\n    \"tracking_url_provider\": { \"@id\": \"schema:trackingUrl\", \"@type\": \"@id\" },\n    \"tracking_status\": \"shippo:trackingStatus\",\n    \"label_url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n\n    \"carrier\": \"schema:provider\",\n    \"tracking_number\": \"schema:trackingNumber\",\n    \"eta\": { \"\
  @id\": \"schema:expectedArrivalUntil\", \"@type\": \"xsd:dateTime\" },\n    \"tracking_history\": \"schema:itemListElement\",\n\n    \"rate\": { \"@id\": \"shippo:rate\", \"@type\": \"shippo:Rate\" },\n    \"label_file_type\": \"schema:encodingFormat\",\n\n    \"transaction\": { \"@id\": \"shippo:transaction\", \"@type\": \"shippo:Transaction\" },\n\n    \"active\": \"schema:actionStatus\",\n    \"event\": \"schema:eventType\",\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/json-ld/shippo-context.jsonld
tags:
- Ecommerce
- Labels
- Logistics
- Returns
- Shipping
- Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
