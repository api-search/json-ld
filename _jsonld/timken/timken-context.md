---
class_count: 21
classes:
- Bearing
- Product
- TaperedRollerBearing
- BallBearing
- CylindricalRollerBearing
- SphericalRollerBearing
- ThrustBearing
- PrecisionBearing
- HousedUnit
- partNumber
- name
- description
- type
- series
- material
- applications
- weight
- cadAvailable
- speedRating
- greaseRpm
- oilRpm
context_file: json-ld/timken-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/timken/refs/heads/main/json-ld/timken-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Timken from Timken.
layout: jsonld
name: Timken Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: timken
  uri: https://www.timken.com/vocab/
- prefix: qudt
  uri: http://qudt.org/vocab/unit/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: boreDiameter
  type: decimal
- container: ''
  name: outsideDiameter
  type: decimal
- container: ''
  name: width
  type: decimal
- container: ''
  name: dynamicLoadRating
  type: decimal
- container: ''
  name: staticLoadRating
  type: decimal
property_count: 5
provider_name: Timken
provider_slug: timken
slug: timken-context
source_filename: timken-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"timken\": \"https://www.timken.com/vocab/\",\n    \"qudt\": \"http://qudt.org/vocab/unit/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Bearing\": \"timken:Bearing\",\n    \"Product\": \"schema:Product\",\n    \"TaperedRollerBearing\": \"timken:TaperedRollerBearing\",\n    \"BallBearing\": \"timken:BallBearing\",\n    \"CylindricalRollerBearing\": \"timken:CylindricalRollerBearing\",\n    \"SphericalRollerBearing\": \"timken:SphericalRollerBearing\",\n    \"ThrustBearing\": \"timken:ThrustBearing\",\n    \"PrecisionBearing\": \"timken:PrecisionBearing\",\n    \"HousedUnit\": \"timken:HousedUnit\",\n\n    \"partNumber\": \"schema:sku\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"series\": \"timken:productSeries\",\n    \"material\": \"schema:material\",\n    \"applications\": \"schema:applicationCategory\"\
  ,\n    \"weight\": \"schema:weight\",\n    \"cadAvailable\": \"timken:cadAvailable\",\n\n    \"boreDiameter\": {\n      \"@id\": \"timken:boreDiameter\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"outsideDiameter\": {\n      \"@id\": \"timken:outsideDiameter\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"width\": {\n      \"@id\": \"timken:bearingWidth\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dynamicLoadRating\": {\n      \"@id\": \"timken:dynamicLoadRatingC\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"staticLoadRating\": {\n      \"@id\": \"timken:staticLoadRatingC0\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"speedRating\": \"timken:speedRating\",\n    \"greaseRpm\": \"timken:greaseLubricationSpeedRpm\",\n    \"oilRpm\": \"timken:oilLubricationSpeedRpm\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/timken/refs/heads/main/json-ld/timken-context.jsonld
tags:
- Bearings
- Industrial
- Manufacturing
- Motion Control
- JSON-LD
- Linked Data
- Semantic Web
---
