---
api_specs:
- filename: redfin-stingray-api-openapi.yml
  format: yaml
  label: Redfin Stingray API
  slug: redfin-stingray-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/openapi/redfin-stingray-api-openapi.yml
- filename: redfin-gis-csv-api-openapi.yml
  format: yaml
  label: Redfin GIS CSV Export API
  slug: redfin-gis-csv-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/openapi/redfin-gis-csv-api-openapi.yml
- filename: redfin-data-center-openapi.yml
  format: yaml
  label: Redfin Data Center
  slug: redfin-data-center
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/openapi/redfin-data-center-openapi.yml
class_count: 0
classes: []
context_file: json-ld/redfin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/json-ld/redfin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Redfin from Redfin.
layout: jsonld
name: Redfin Context
namespaces:
- prefix: redfin
  uri: https://www.redfin.com/ns/
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
  name: Property
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: PropertyHistoryEvent
  type: ''
- container: ''
  name: MarketTrackerRecord
  type: ''
property_count: 4
provider_name: Redfin
provider_slug: redfin
slug: redfin-context
source_filename: redfin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"redfin\": \"https://www.redfin.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Property\": {\n      \"@id\": \"schema:RealEstateListing\",\n      \"@context\": {\n        \"propertyId\": \"redfin:propertyId\",\n        \"listingId\": \"redfin:listingId\",\n        \"mlsId\": \"redfin:mlsId\",\n        \"address\": \"schema:address\",\n        \"price\": \"schema:price\",\n        \"beds\": \"schema:numberOfBedrooms\",\n        \"baths\": \"schema:numberOfBathroomsTotal\",\n        \"sqFt\": \"schema:floorSize\",\n        \"lotSize\": \"schema:lotSize\",\n        \"yearBuilt\": \"schema:yearBuilt\",\n        \"propertyType\": \"schema:propertyType\",\n        \"listingStatus\": \"redfin:listingStatus\",\n        \"daysOnMarket\": \"redfin:daysOnMarket\"\
  ,\n        \"latitude\": \"geo:lat\",\n        \"longitude\": \"geo:long\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"redfinEstimate\": \"redfin:redfinEstimate\",\n        \"history\": {\n          \"@id\": \"redfin:propertyHistory\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"streetAddress\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip\": \"schema:postalCode\"\n      }\n    },\n\n    \"PropertyHistoryEvent\": {\n      \"@id\": \"redfin:PropertyHistoryEvent\",\n      \"@context\": {\n        \"eventDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"eventType\": \"redfin:eventType\",\n        \"price\": \"schema:price\",\n        \"source\": \"dcterms:source\"\n\
  \      }\n    },\n\n    \"MarketTrackerRecord\": {\n      \"@id\": \"redfin:MarketTrackerRecord\",\n      \"@context\": {\n        \"periodBegin\": {\n          \"@id\": \"redfin:periodBegin\",\n          \"@type\": \"xsd:date\"\n        },\n        \"periodEnd\": {\n          \"@id\": \"redfin:periodEnd\",\n          \"@type\": \"xsd:date\"\n        },\n        \"periodDuration\": \"redfin:periodDuration\",\n        \"regionType\": \"redfin:regionType\",\n        \"region\": \"schema:name\",\n        \"state\": \"schema:addressRegion\",\n        \"stateCode\": \"redfin:stateCode\",\n        \"propertyType\": \"schema:propertyType\",\n        \"medianSalePrice\": \"redfin:medianSalePrice\",\n        \"medianListPrice\": \"redfin:medianListPrice\",\n        \"medianPpsf\": \"redfin:medianPricePerSquareFoot\",\n        \"homesSold\": \"redfin:homesSold\",\n        \"newListings\": \"redfin:newListings\",\n        \"inventory\": \"redfin:inventory\",\n        \"medianDom\": \"redfin:medianDaysOnMarket\"\
  ,\n        \"priceDrops\": \"redfin:priceDrops\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/json-ld/redfin-context.jsonld
tags:
- CSV Export
- GIS
- Home Values
- Housing Market
- Listings
- Property Data
- Real Estate
- JSON-LD
- Linked Data
- Semantic Web
---
