---
api_specs:
- filename: trimble-mobile-manager-openapi.yml
  format: yaml
  label: Trimble Mobile Manager API
  slug: trimble-mobile-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/openapi/trimble-mobile-manager-openapi.yml
class_count: 4
classes:
- GnssPosition
- Receiver
- SatelliteInfo
- CatalystLicense
context_file: json-ld/trimble-navigation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/json-ld/trimble-navigation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trimble Navigation from Trimble Navigation.
layout: jsonld
name: Trimble Navigation Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: trimble-nav
  uri: https://www.trimble.com/vocab/navigation/
properties:
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: altitude
  type: double
- container: ''
  name: speed
  type: float
- container: ''
  name: bearing
  type: float
- container: ''
  name: satellites
  type: integer
- container: ''
  name: hrms
  type: float
- container: ''
  name: vrms
  type: float
- container: ''
  name: pdop
  type: float
- container: ''
  name: hdop
  type: float
- container: ''
  name: vdop
  type: float
- container: ''
  name: diffStatus
  type: integer
- container: ''
  name: timestamp
  type: dateTime
- container: list
  name: satelliteView
  type: ''
- container: ''
  name: model
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: firmwareVersion
  type: string
- container: ''
  name: connectionType
  type: string
- container: ''
  name: gnssSystem
  type: string
- container: ''
  name: elevation
  type: integer
- container: ''
  name: azimuth
  type: integer
- container: ''
  name: snr
  type: float
- container: ''
  name: used
  type: boolean
- container: ''
  name: version
  type: string
- container: ''
  name: platform
  type: string
property_count: 25
provider_name: Trimble Navigation
provider_slug: trimble-navigation
slug: trimble-navigation-context
source_filename: trimble-navigation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"trimble-nav\": \"https://www.trimble.com/vocab/navigation/\",\n\n    \"GnssPosition\": \"sosa:Observation\",\n    \"Receiver\": \"trimble-nav:Receiver\",\n    \"SatelliteInfo\": \"trimble-nav:SatelliteInfo\",\n    \"CatalystLicense\": \"trimble-nav:CatalystLicense\",\n\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n    \"altitude\": {\n      \"@id\": \"geo:alt\",\n      \"@type\": \"xsd:double\"\n    },\n    \"speed\": {\n      \"@id\": \"schema:speed\",\n      \"@type\": \"xsd:float\"\n    },\n    \"bearing\": {\n      \"@id\": \"trimble-nav:bearing\",\n      \"@type\": \"xsd:float\"\n  \
  \  },\n    \"satellites\": {\n      \"@id\": \"trimble-nav:satellites\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hrms\": {\n      \"@id\": \"trimble-nav:hrms\",\n      \"@type\": \"xsd:float\"\n    },\n    \"vrms\": {\n      \"@id\": \"trimble-nav:vrms\",\n      \"@type\": \"xsd:float\"\n    },\n    \"pdop\": {\n      \"@id\": \"trimble-nav:pdop\",\n      \"@type\": \"xsd:float\"\n    },\n    \"hdop\": {\n      \"@id\": \"trimble-nav:hdop\",\n      \"@type\": \"xsd:float\"\n    },\n    \"vdop\": {\n      \"@id\": \"trimble-nav:vdop\",\n      \"@type\": \"xsd:float\"\n    },\n    \"diffStatus\": {\n      \"@id\": \"trimble-nav:diffStatus\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"satelliteView\": {\n      \"@id\": \"trimble-nav:satelliteView\",\n      \"@container\": \"@list\"\n    },\n\n    \"model\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"serialNumber\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firmwareVersion\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionType\": {\n      \"@id\": \"trimble-nav:connectionType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"gnssSystem\": {\n      \"@id\": \"trimble-nav:gnssSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elevation\": {\n      \"@id\": \"trimble-nav:elevation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"azimuth\": {\n      \"@id\": \"trimble-nav:azimuth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"snr\": {\n      \"@id\": \"trimble-nav:snr\",\n      \"@type\": \"xsd:float\"\n    },\n    \"used\": {\n      \"@id\": \"trimble-nav:used\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"schema:operatingSystem\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/json-ld/trimble-navigation-context.jsonld
tags:
- GPS
- GNSS
- Positioning
- Navigation
- Surveying
- Geospatial
- Construction
- JSON-LD
- Linked Data
- Semantic Web
---
