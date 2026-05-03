---
class_count: 33
classes:
- Warehouse
- LogisticsService
- Shipment
- Location
- Organization
- id
- name
- description
- address
- street1
- street2
- city
- state
- zip
- country
- squareFootage
- type
- capabilities
- certifications
- operatingHours
- contactName
- contactPhone
- contactEmail
- warehousing
- distribution
- coPackaging
- fulfillment
- transportationManagement
- valueAddedServices
- crossDocking
- pickAndPack
- thirdPartyLogistics
- supplyChain
context_file: json-ld/shippers-group-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shippers-group/refs/heads/main/json-ld/shippers-group-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shippers Group from The Shippers Group.
layout: jsonld
name: Shippers Group Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sg
  uri: https://api-evangelist.github.io/shippers-group/vocabulary/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 2
provider_name: The Shippers Group
provider_slug: shippers-group
slug: shippers-group-context
source_filename: shippers-group-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sg\": \"https://api-evangelist.github.io/shippers-group/vocabulary/\",\n\n    \"Warehouse\": \"schema:Warehouse\",\n    \"LogisticsService\": \"schema:Service\",\n    \"Shipment\": \"schema:ParcelDelivery\",\n    \"Location\": \"schema:Place\",\n    \"Organization\": \"schema:Organization\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"address\": \"schema:address\",\n    \"street1\": \"schema:streetAddress\",\n    \"street2\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"squareFootage\": \"schema:floorSize\",\n    \"type\": \"schema:additionalType\",\n    \"capabilities\": \"schema:hasOfferCatalog\",\n    \"certifications\"\
  : \"schema:award\",\n    \"operatingHours\": \"schema:openingHoursSpecification\",\n    \"contactName\": \"schema:contactPoint\",\n    \"contactPhone\": \"schema:telephone\",\n    \"contactEmail\": \"schema:email\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"warehousing\": \"sg:warehousing\",\n    \"distribution\": \"sg:distribution\",\n    \"coPackaging\": \"sg:coPackaging\",\n    \"fulfillment\": \"sg:fulfillment\",\n    \"transportationManagement\": \"sg:transportationManagement\",\n    \"valueAddedServices\": \"sg:valueAddedServices\",\n    \"crossDocking\": \"sg:crossDocking\",\n    \"pickAndPack\": \"sg:pickAndPack\",\n    \"thirdPartyLogistics\": \"sg:thirdPartyLogistics\",\n    \"supplyChain\": \"sg:supplyChain\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shippers-group/refs/heads/main/json-ld/shippers-group-context.jsonld
tags:
- Third-Party Logistics
- Warehousing
- Fulfillment
- Supply Chain
- Transportation Management
- Co-Packaging
- Consumer Packaged Goods
- JSON-LD
- Linked Data
- Semantic Web
---
