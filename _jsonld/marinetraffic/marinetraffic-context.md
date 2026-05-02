---
api_specs:
- filename: marinetraffic-ais-openapi.yml
  format: yaml
  label: MarineTraffic AIS Vessel Tracking API
  slug: marinetraffic-ais-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml
class_count: 7
classes:
- Vessel
- VESSEL_NAME
- CALLSIGN
- FLAG
- PortCall
- PORT_NAME
- UNLOCODE
context_file: json-ld/marinetraffic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Marinetraffic from MarineTraffic.
layout: jsonld
name: Marinetraffic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: mt
  uri: https://www.marinetraffic.com/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: MMSI
  type: string
- container: ''
  name: IMO
  type: integer
- container: ''
  name: SHIP_ID
  type: integer
- container: ''
  name: YEAR_BUILT
  type: gYear
- container: ''
  name: LENGTH
  type: decimal
- container: ''
  name: WIDTH
  type: decimal
- container: ''
  name: GT
  type: integer
- container: ''
  name: DWT
  type: integer
- container: ''
  name: LAT
  type: decimal
- container: ''
  name: LON
  type: decimal
- container: ''
  name: SPEED
  type: decimal
- container: ''
  name: HEADING
  type: integer
- container: ''
  name: COURSE
  type: decimal
- container: ''
  name: STATUS
  type: integer
- container: ''
  name: TIMESTAMP
  type: dateTime
- container: ''
  name: DESTINATION
  type: string
- container: ''
  name: ETA
  type: dateTime
- container: ''
  name: ARRIVAL
  type: dateTime
- container: ''
  name: DEPARTURE
  type: dateTime
property_count: 19
provider_name: MarineTraffic
provider_slug: marinetraffic
slug: marinetraffic-context
source_filename: marinetraffic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"mt\": \"https://www.marinetraffic.com/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Vessel\": \"schema:Vehicle\",\n    \"MMSI\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IMO\": {\n      \"@id\": \"mt:imoNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SHIP_ID\": {\n      \"@id\": \"mt:shipId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"VESSEL_NAME\": \"schema:name\",\n    \"CALLSIGN\": \"mt:callsign\",\n    \"FLAG\": \"schema:countryOfOrigin\",\n    \"YEAR_BUILT\": {\n      \"@id\": \"schema:productionDate\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"LENGTH\": {\n      \"@id\": \"schema:depth\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"WIDTH\": {\n      \"@id\": \"schema:width\",\n      \"@type\": \"xsd:decimal\"\n  \
  \  },\n    \"GT\": {\n      \"@id\": \"mt:grossTonnage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DWT\": {\n      \"@id\": \"mt:deadweightTonnage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"LAT\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LON\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"SPEED\": {\n      \"@id\": \"mt:speedOverGround\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"HEADING\": {\n      \"@id\": \"mt:trueHeading\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"COURSE\": {\n      \"@id\": \"mt:courseOverGround\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"STATUS\": {\n      \"@id\": \"mt:navigationalStatus\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TIMESTAMP\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DESTINATION\": {\n      \"@id\": \"schema:toLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ETA\"\
  : {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PortCall\": \"schema:Event\",\n    \"PORT_NAME\": \"schema:name\",\n    \"UNLOCODE\": \"schema:identifier\",\n    \"ARRIVAL\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DEPARTURE\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld
tags:
- AIS
- Maritime
- Shipping
- Vessel Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
