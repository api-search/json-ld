---
api_specs:
- filename: us-space-command-space-track-openapi.yml
  format: yaml
  label: Space-Track.org REST API
  slug: space-track-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/openapi/us-space-command-space-track-openapi.yml
class_count: 3
classes:
- SpaceObject
- OrbitalElements
- ConjunctionWarning
context_file: json-ld/us-space-comman-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/json-ld/us-space-comman-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Space Comman from US Space Command.
layout: jsonld
name: Us Space Comman Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: space
  uri: https://www.space-track.org/vocab/
- prefix: astro
  uri: http://www.ivoa.net/xml/STC/stc-v1.3.xsd#
properties:
- container: ''
  name: NORAD_CAT_ID
  type: integer
- container: ''
  name: OBJECT_NAME
  type: string
- container: ''
  name: OBJECT_ID
  type: string
- container: ''
  name: OBJECT_TYPE
  type: string
- container: ''
  name: EPOCH
  type: dateTime
- container: ''
  name: MEAN_MOTION
  type: double
- container: ''
  name: ECCENTRICITY
  type: double
- container: ''
  name: INCLINATION
  type: double
- container: ''
  name: RA_OF_ASC_NODE
  type: double
- container: ''
  name: ARG_OF_PERICENTER
  type: double
- container: ''
  name: MEAN_ANOMALY
  type: double
- container: ''
  name: APOGEE
  type: double
- container: ''
  name: PERIGEE
  type: double
- container: ''
  name: PERIOD
  type: double
- container: ''
  name: COUNTRY_CODE
  type: string
- container: ''
  name: LAUNCH_DATE
  type: date
- container: ''
  name: DECAY_DATE
  type: date
- container: ''
  name: PC
  type: double
- container: ''
  name: TCA
  type: dateTime
- container: ''
  name: MIN_RNG
  type: double
property_count: 20
provider_name: US Space Command
provider_slug: us-space-comman
slug: us-space-comman-context
source_filename: us-space-comman-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"space\": \"https://www.space-track.org/vocab/\",\n    \"astro\": \"http://www.ivoa.net/xml/STC/stc-v1.3.xsd#\",\n\n    \"SpaceObject\": \"schema:Thing\",\n    \"OrbitalElements\": \"space:OrbitalElements\",\n    \"ConjunctionWarning\": \"space:Conjunction\",\n\n    \"NORAD_CAT_ID\": {\n      \"@id\": \"space:noradCatalogId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"OBJECT_NAME\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OBJECT_ID\": {\n      \"@id\": \"space:internationalDesignator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OBJECT_TYPE\": {\n      \"@id\": \"space:objectType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EPOCH\": {\n      \"@id\": \"space:epoch\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"MEAN_MOTION\": {\n      \"@id\": \"space:meanMotion\",\n\
  \      \"@type\": \"xsd:double\"\n    },\n    \"ECCENTRICITY\": {\n      \"@id\": \"space:eccentricity\",\n      \"@type\": \"xsd:double\"\n    },\n    \"INCLINATION\": {\n      \"@id\": \"space:inclination\",\n      \"@type\": \"xsd:double\"\n    },\n    \"RA_OF_ASC_NODE\": {\n      \"@id\": \"space:rightAscensionAscendingNode\",\n      \"@type\": \"xsd:double\"\n    },\n    \"ARG_OF_PERICENTER\": {\n      \"@id\": \"space:argumentOfPericenter\",\n      \"@type\": \"xsd:double\"\n    },\n    \"MEAN_ANOMALY\": {\n      \"@id\": \"space:meanAnomaly\",\n      \"@type\": \"xsd:double\"\n    },\n    \"APOGEE\": {\n      \"@id\": \"space:apogeeAltitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"PERIGEE\": {\n      \"@id\": \"space:perigeeAltitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"PERIOD\": {\n      \"@id\": \"space:orbitalPeriod\",\n      \"@type\": \"xsd:double\"\n    },\n    \"COUNTRY_CODE\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"LAUNCH_DATE\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"DECAY_DATE\": {\n      \"@id\": \"space:decayDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"PC\": {\n      \"@id\": \"space:collisionProbability\",\n      \"@type\": \"xsd:double\"\n    },\n    \"TCA\": {\n      \"@id\": \"space:timeOfClosestApproach\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"MIN_RNG\": {\n      \"@id\": \"space:minimumRange\",\n      \"@type\": \"xsd:double\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/json-ld/us-space-comman-context.jsonld
tags:
- Federal Government
- Space
- Space Situational Awareness
- Satellite Tracking
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
