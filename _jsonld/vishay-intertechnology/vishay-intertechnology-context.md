---
class_count: 0
classes: []
context_file: json-ld/vishay-intertechnology-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vishay-intertechnology/refs/heads/main/json-ld/vishay-intertechnology-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vishay Intertechnology from Vishay Intertechnology.
layout: jsonld
name: Vishay Intertechnology Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: eclass
  uri: https://www.eclass.eu/
properties:
- container: ''
  name: ElectronicComponent
  type: reference
- container: ''
  name: Resistor
  type: reference
- container: ''
  name: Capacitor
  type: reference
- container: ''
  name: Diode
  type: reference
- container: ''
  name: MOSFET
  type: reference
- container: ''
  name: Optoelectronic
  type: reference
- container: ''
  name: Inductor
  type: reference
- container: ''
  name: partNumber
  type: http://www.w3.org/2001/XMLSchema#string
- container: ''
  name: manufacturer
  type: ''
- container: ''
  name: category
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: datasheet
  type: reference
- container: ''
  name: productPage
  type: reference
- container: ''
  name: rohs
  type: http://www.w3.org/2001/XMLSchema#boolean
- container: ''
  name: voltageRating
  type: ''
- container: ''
  name: currentRating
  type: ''
- container: ''
  name: powerRating
  type: ''
- container: ''
  name: tolerance
  type: ''
- container: ''
  name: packageType
  type: ''
- container: ''
  name: temperatureRange
  type: ''
- container: list
  name: applications
  type: ''
- container: ''
  name: name
  type: ''
property_count: 22
provider_name: Vishay Intertechnology
provider_slug: vishay-intertechnology
slug: vishay-intertechnology-context
source_filename: vishay-intertechnology-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://www.vishay.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"eclass\": \"https://www.eclass.eu/\",\n\n    \"ElectronicComponent\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"Resistor\": {\n      \"@id\": \"https://www.vishay.com/vocab/Resistor\",\n      \"@type\": \"@id\"\n    },\n    \"Capacitor\": {\n      \"@id\": \"https://www.vishay.com/vocab/Capacitor\",\n      \"@type\": \"@id\"\n    },\n    \"Diode\": {\n      \"@id\": \"https://www.vishay.com/vocab/Diode\",\n      \"@type\": \"@id\"\n    },\n    \"MOSFET\": {\n      \"@id\": \"https://www.vishay.com/vocab/MOSFET\",\n      \"@type\": \"@id\"\n    },\n    \"Optoelectronic\": {\n      \"@id\": \"https://www.vishay.com/vocab/Optoelectronic\",\n      \"@type\": \"@id\"\n    },\n    \"Inductor\": {\n      \"@id\": \"https://www.vishay.com/vocab/Inductor\",\n      \"@type\": \"@id\"\n\
  \    },\n\n    \"partNumber\": {\n      \"@id\": \"schema:mpn\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"datasheet\": {\n      \"@id\": \"schema:documentation\",\n      \"@type\": \"@id\"\n    },\n    \"productPage\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"rohs\": {\n      \"@id\": \"https://www.vishay.com/vocab/rohsCompliant\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#boolean\"\n    },\n    \"voltageRating\": {\n      \"@id\": \"https://www.vishay.com/vocab/voltageRating\"\n    },\n    \"currentRating\": {\n      \"@id\": \"https://www.vishay.com/vocab/currentRating\"\n    },\n    \"powerRating\": {\n      \"@id\": \"https://www.vishay.com/vocab/powerRating\"\n    },\n    \"tolerance\": {\n     \
  \ \"@id\": \"https://www.vishay.com/vocab/tolerance\"\n    },\n    \"packageType\": {\n      \"@id\": \"https://www.vishay.com/vocab/packageType\"\n    },\n    \"temperatureRange\": {\n      \"@id\": \"https://www.vishay.com/vocab/temperatureRange\"\n    },\n    \"applications\": {\n      \"@id\": \"schema:applicationCategory\",\n      \"@container\": \"@list\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vishay-intertechnology/refs/heads/main/json-ld/vishay-intertechnology-context.jsonld
tags:
- Automotive
- Capacitors
- Diodes
- Electronics
- Industrial
- MOSFETs
- Manufacturing
- Medical
- Optoelectronics
- Passive Components
- Resistors
- Semiconductors
- JSON-LD
- Linked Data
- Semantic Web
---
