---
class_count: 10
classes:
- WasteCollectionService
- Customer
- ServiceAddress
- Invoice
- ServiceSchedule
- PickupNotification
- TransferStation
- Landfill
- RecyclingProgram
- ServiceArea
context_file: json-ld/waste-connections-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/waste-connections/refs/heads/main/json-ld/waste-connections-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Waste Connections from Waste Connections.
layout: jsonld
name: Waste Connections Context
namespaces:
- prefix: wc
  uri: https://wasteconnections.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: address
  type: ''
- container: ''
  name: telephone
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: pickupDay
  type: string
- container: ''
  name: balanceDue
  type: decimal
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: serviceStatus
  type: string
- container: ''
  name: municipality
  type: ''
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
property_count: 13
provider_name: Waste Connections
provider_slug: waste-connections
slug: waste-connections-context
source_filename: waste-connections-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wc\": \"https://wasteconnections.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"WasteCollectionService\": \"wc:WasteCollectionService\",\n    \"Customer\": \"schema:Customer\",\n    \"ServiceAddress\": \"schema:PostalAddress\",\n    \"Invoice\": \"schema:Invoice\",\n    \"ServiceSchedule\": \"wc:ServiceSchedule\",\n    \"PickupNotification\": \"wc:PickupNotification\",\n    \"TransferStation\": \"wc:TransferStation\",\n    \"Landfill\": \"wc:Landfill\",\n    \"RecyclingProgram\": \"wc:RecyclingProgram\",\n    \"ServiceArea\": \"wc:ServiceArea\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  address\": {\n      \"@id\": \"schema:address\"\n    },\n    \"telephone\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"wc:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"wc:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pickupDay\": {\n      \"@id\": \"wc:pickupDay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceDue\": {\n      \"@id\": \"wc:balanceDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"invoiceDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"serviceStatus\": {\n      \"@id\": \"wc:serviceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"municipality\": {\n      \"@id\": \"schema:containedInPlace\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\"\
  : \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/waste-connections/refs/heads/main/json-ld/waste-connections-context.jsonld
tags:
- Environmental Services
- Fortune 500
- Recycling
- Solid Waste
- Sustainability
- Waste Management
- JSON-LD
- Linked Data
- Semantic Web
---
