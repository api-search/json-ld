---
api_specs:
- filename: ryder-fleet-management-api-openapi.yml
  format: yaml
  label: Ryder Fleet Management API
  slug: fleet-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-fleet-management-api-openapi.yml
- filename: ryder-carrier-api-openapi.yml
  format: yaml
  label: Ryder Carrier API
  slug: carrier-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-carrier-api-openapi.yml
- filename: ryder-tm-shipment-api-openapi.yml
  format: yaml
  label: Ryder TM Shipment Management API
  slug: tm-shipment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-tm-shipment-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/ryder-system-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-ld/ryder-system-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ryder System from Ryder System.
layout: jsonld
name: Ryder System Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ryder
  uri: https://www.ryder.com/vocab/
properties:
- container: ''
  name: Vehicle
  type: reference
- container: ''
  name: vehicleId
  type: schema:Text
- container: ''
  name: vin
  type: schema:Text
- container: ''
  name: make
  type: schema:Text
- container: ''
  name: model
  type: schema:Text
- container: ''
  name: year
  type: schema:Integer
- container: ''
  name: mileage
  type: schema:QuantitativeValue
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: ServiceRecord
  type: reference
- container: ''
  name: serviceDate
  type: schema:Date
- container: ''
  name: cost
  type: schema:Number
- container: ''
  name: Location
  type: reference
- container: ''
  name: locationId
  type: schema:Text
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: city
  type: schema:Text
- container: ''
  name: state
  type: schema:Text
- container: ''
  name: zip
  type: schema:Text
- container: ''
  name: businessHours
  type: schema:Text
- container: ''
  name: Shipment
  type: reference
- container: ''
  name: shipmentId
  type: schema:Text
- container: ''
  name: origin
  type: reference
- container: ''
  name: destination
  type: reference
- container: ''
  name: requestedPickupDate
  type: schema:Date
- container: ''
  name: requestedDeliveryDate
  type: schema:Date
- container: ''
  name: actualDeliveryDate
  type: schema:DateTime
- container: ''
  name: Invoice
  type: reference
- container: ''
  name: invoiceId
  type: schema:Text
- container: ''
  name: amount
  type: schema:MonetaryAmount
property_count: 29
provider_name: Ryder System
provider_slug: ryder-system
slug: ryder-system-context
source_filename: ryder-system-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ryder\": \"https://www.ryder.com/vocab/\",\n    \"Vehicle\": {\n      \"@id\": \"schema:Vehicle\",\n      \"@type\": \"@id\"\n    },\n    \"vehicleId\": {\n      \"@id\": \"ryder:vehicleId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"vin\": {\n      \"@id\": \"schema:vehicleIdentificationNumber\",\n      \"@type\": \"schema:Text\"\n    },\n    \"make\": {\n      \"@id\": \"schema:vehicleMake\",\n      \"@type\": \"schema:Text\"\n    },\n    \"model\": {\n      \"@id\": \"schema:vehicleModelDate\",\n      \"@type\": \"schema:Text\"\n    },\n    \"year\": {\n      \"@id\": \"schema:modelDate\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"mileage\": {\n      \"@id\": \"schema:mileageFromOdometer\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"schema:Text\"\n    },\n    \"ServiceRecord\"\
  : {\n      \"@id\": \"ryder:ServiceRecord\",\n      \"@type\": \"@id\"\n    },\n    \"serviceDate\": {\n      \"@id\": \"schema:datePosted\",\n      \"@type\": \"schema:Date\"\n    },\n    \"cost\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"Location\": {\n      \"@id\": \"schema:LocalBusiness\",\n      \"@type\": \"@id\"\n    },\n    \"locationId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"schema:Text\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"schema:Text\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"schema:Text\"\n    },\n    \"zip\": {\n      \"@id\": \"schema:postalCode\",\n      \"@type\": \"schema:Text\"\n    },\n    \"businessHours\"\
  : {\n      \"@id\": \"schema:openingHours\",\n      \"@type\": \"schema:Text\"\n    },\n    \"Shipment\": {\n      \"@id\": \"schema:ParcelDelivery\",\n      \"@type\": \"@id\"\n    },\n    \"shipmentId\": {\n      \"@id\": \"schema:trackingNumber\",\n      \"@type\": \"schema:Text\"\n    },\n    \"origin\": {\n      \"@id\": \"schema:originAddress\",\n      \"@type\": \"@id\"\n    },\n    \"destination\": {\n      \"@id\": \"schema:deliveryAddress\",\n      \"@type\": \"@id\"\n    },\n    \"requestedPickupDate\": {\n      \"@id\": \"ryder:requestedPickupDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"requestedDeliveryDate\": {\n      \"@id\": \"schema:expectedArrivalUntil\",\n      \"@type\": \"schema:Date\"\n    },\n    \"actualDeliveryDate\": {\n      \"@id\": \"schema:deliveryDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"Invoice\": {\n      \"@id\": \"schema:Invoice\",\n      \"@type\": \"@id\"\n    },\n    \"invoiceId\": {\n      \"@id\": \"schema:identifier\"\
  ,\n      \"@type\": \"schema:Text\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"schema:MonetaryAmount\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-ld/ryder-system-context.jsonld
tags:
- Fleet Management
- Logistics
- Supply Chain
- Transportation
- Trucking
- JSON-LD
- Linked Data
- Semantic Web
---
