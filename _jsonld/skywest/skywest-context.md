---
class_count: 0
classes: []
context_file: json-ld/skywest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/skywest/refs/heads/main/json-ld/skywest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Skywest from SkyWest Airlines.
layout: jsonld
name: Skywest Context
namespaces:
- prefix: skywest
  uri: https://www.skywest.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Airline
  type: ''
- container: ''
  name: Flight
  type: ''
- container: ''
  name: Airport
  type: ''
- container: ''
  name: Aircraft
  type: ''
- container: ''
  name: CapacityPurchaseAgreement
  type: ''
- container: ''
  name: CrewMember
  type: ''
property_count: 6
provider_name: SkyWest Airlines
provider_slug: skywest
slug: skywest-context
source_filename: skywest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"skywest\": \"https://www.skywest.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Airline\": {\n      \"@id\": \"schema:Airline\",\n      \"@context\": {\n        \"iataCode\": {\n          \"@id\": \"schema:iataCode\"\n        },\n        \"icaoCode\": {\n          \"@id\": \"skywest:icaoCode\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"foundingDate\": {\n          \"@id\": \"schema:foundingDate\"\n        },\n        \"numberOfEmployees\": {\n          \"@id\": \"schema:numberOfEmployees\"\n        },\n        \"headquarters\": {\n          \"@id\": \"schema:location\"\n       \
  \ }\n      }\n    },\n\n    \"Flight\": {\n      \"@id\": \"schema:Flight\",\n      \"@context\": {\n        \"flightNumber\": {\n          \"@id\": \"schema:flightNumber\"\n        },\n        \"departureAirport\": {\n          \"@id\": \"schema:departureAirport\",\n          \"@type\": \"@id\"\n        },\n        \"arrivalAirport\": {\n          \"@id\": \"schema:arrivalAirport\",\n          \"@type\": \"@id\"\n        },\n        \"departureTime\": {\n          \"@id\": \"schema:departureTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"arrivalTime\": {\n          \"@id\": \"schema:arrivalTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"aircraft\": {\n          \"@id\": \"skywest:aircraft\"\n        },\n        \"flightStatus\": {\n          \"@id\": \"skywest:flightStatus\"\n        },\n        \"operatingAirline\": {\n          \"@id\": \"schema:provider\"\n        },\n        \"marketingAirline\": {\n          \"@id\": \"skywest:marketingAirline\"\
  \n        }\n      }\n    },\n\n    \"Airport\": {\n      \"@id\": \"schema:Airport\",\n      \"@context\": {\n        \"iataCode\": {\n          \"@id\": \"schema:iataCode\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"address\": {\n          \"@id\": \"schema:address\"\n        },\n        \"geo\": {\n          \"@id\": \"schema:geo\"\n        }\n      }\n    },\n\n    \"Aircraft\": {\n      \"@id\": \"skywest:Aircraft\",\n      \"@context\": {\n        \"tailNumber\": {\n          \"@id\": \"skywest:tailNumber\"\n        },\n        \"aircraftType\": {\n          \"@id\": \"skywest:aircraftType\"\n        },\n        \"seatCapacity\": {\n          \"@id\": \"skywest:seatCapacity\"\n        },\n        \"manufacturer\": {\n          \"@id\": \"schema:manufacturer\"\n        }\n      }\n    },\n\n    \"CapacityPurchaseAgreement\": {\n      \"@id\": \"skywest:CapacityPurchaseAgreement\",\n      \"@context\": {\n        \"majorCarrier\": {\n\
  \          \"@id\": \"skywest:majorCarrier\"\n        },\n        \"brandName\": {\n          \"@id\": \"skywest:brandName\"\n        },\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"CrewMember\": {\n      \"@id\": \"skywest:CrewMember\",\n      \"@context\": {\n        \"employeeId\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"role\": {\n          \"@id\": \"schema:jobTitle\"\n        },\n        \"homeBase\": {\n          \"@id\": \"skywest:homeBase\"\n        },\n        \"certifications\": {\n          \"@id\": \"skywest:certifications\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/skywest/refs/heads/main/json-ld/skywest-context.jsonld
tags:
- Airlines
- Aviation
- Regional Airline
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
