---
api_specs:
- filename: realtor-connections-plus-asyncapi.yml
  format: yaml
  label: Realtor.com Connections Plus API
  slug: connections-plus-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/asyncapi/realtor-connections-plus-asyncapi.yml
- filename: realtor-lead-delivery-asyncapi.yml
  format: yaml
  label: Realtor.com Lead Delivery API
  slug: lead-delivery-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/asyncapi/realtor-lead-delivery-asyncapi.yml
- filename: realtor-property-data-openapi.yml
  format: yaml
  label: Realtor.com Property Data API
  slug: property-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/openapi/realtor-property-data-openapi.yml
class_count: 0
classes: []
context_file: json-ld/realtor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/json-ld/realtor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Realtor from realtor.
layout: jsonld
name: Realtor Context
namespaces:
- prefix: realtor
  uri: https://realtor.com/ns/
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
  name: Lead
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: School
  type: ''
- container: ''
  name: MortgageRate
  type: ''
property_count: 8
provider_name: realtor
provider_slug: realtor
slug: realtor-context
source_filename: realtor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"realtor\": \"https://realtor.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Property\": {\n      \"@id\": \"schema:RealEstateListing\",\n      \"@context\": {\n        \"property_id\": \"schema:identifier\",\n        \"listing_id\": \"realtor:listingId\",\n        \"status\": \"realtor:listingStatus\",\n        \"list_price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"list_date\": {\n          \"@id\": \"schema:datePosted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_sold_price\": {\n          \"@id\": \"realtor:lastSoldPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"last_sold_date\": {\n          \"@id\": \"realtor:lastSoldDate\",\n          \"\
  @type\": \"xsd:date\"\n        },\n        \"listing_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"beds\": \"schema:numberOfBedrooms\",\n        \"baths\": \"schema:numberOfBathroomsTotal\",\n        \"sqft\": {\n          \"@id\": \"schema:floorSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lot_sqft\": {\n          \"@id\": \"schema:lotSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"year_built\": {\n          \"@id\": \"schema:yearBuilt\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"property_type\": \"realtor:propertyType\",\n        \"description\": \"schema:description\",\n        \"photos\": {\n          \"@id\": \"schema:image\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Lead\": {\n      \"@id\": \"realtor:Lead\",\n      \"@context\"\
  : {\n        \"lead_id\": \"schema:identifier\",\n        \"role\": \"realtor:leadRole\",\n        \"source\": \"realtor:leadSource\",\n        \"message\": \"realtor:leadMessage\",\n        \"is_likely_to_transact\": \"realtor:isLikelyToTransact\",\n        \"probability_to_transact\": {\n          \"@id\": \"realtor:probabilityToTransact\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\"\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"schema:RealEstateAgent\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"full_name\": \"schema:name\",\n        \"first_name\": \"schema:givenName\"\
  ,\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"photo\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"office\": \"schema:worksFor\",\n        \"area_served\": {\n          \"@id\": \"schema:areaServed\",\n          \"@container\": \"@set\"\n        },\n        \"recently_sold_count\": \"realtor:recentlySoldCount\",\n        \"for_sale_count\": \"realtor:forSaleCount\"\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"address\": \"schema:address\",\n        \"neighborhood_name\": \"realtor:neighborhoodName\",\n        \"latitude\": {\n          \"@id\": \"geo:lat\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"geo:long\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n       \
  \ \"line\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state_code\": \"schema:addressRegion\",\n        \"state\": \"schema:addressRegion\",\n        \"postal_code\": \"schema:postalCode\",\n        \"county\": \"realtor:county\"\n      }\n    },\n\n    \"School\": {\n      \"@id\": \"schema:School\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"education_levels\": {\n          \"@id\": \"realtor:educationLevels\",\n          \"@container\": \"@set\"\n        },\n        \"rating\": \"schema:aggregateRating\",\n        \"distance_in_miles\": \"realtor:distanceInMiles\",\n        \"funding_type\": \"realtor:fundingType\"\n      }\n    },\n\n    \"MortgageRate\": {\n      \"@id\": \"realtor:MortgageRate\",\n      \"@context\": {\n        \"loan_type\": \"realtor:loanType\",\n        \"rate\": {\n          \"@id\": \"realtor:interestRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"apr\": {\n          \"\
  @id\": \"realtor:annualPercentageRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"last_updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/json-ld/realtor-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
