---
class_count: 0
classes: []
context_file: json-ld/dentsply-sirona-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dentsply-sirona/refs/heads/main/json-ld/dentsply-sirona-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dentsply Sirona from Dentsply Sirona.
layout: jsonld
name: Dentsply Sirona Context
namespaces:
- prefix: ds
  uri: https://open.dscore.com/
properties:
- container: ''
  name: Patient
  type: ''
- container: ''
  name: Practice
  type: ''
- container: ''
  name: Lab
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Scan
  type: ''
- container: ''
  name: Image
  type: ''
property_count: 6
provider_name: Dentsply Sirona
provider_slug: dentsply-sirona
slug: dentsply-sirona-context
source_filename: dentsply-sirona-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ds\": \"https://open.dscore.com/\",\n    \"Patient\": {\n      \"@id\": \"https://schema.org/Patient\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"givenName\": \"https://schema.org/givenName\",\n        \"familyName\": \"https://schema.org/familyName\",\n        \"birthDate\": \"https://schema.org/birthDate\",\n        \"gender\": \"https://schema.org/gender\"\n      }\n    },\n    \"Practice\": {\n      \"@id\": \"https://schema.org/Dentist\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"address\": \"https://schema.org/address\"\n      }\n    },\n    \"Lab\": {\n      \"@id\": \"https://schema.org/Organization\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"address\": \"https://schema.org/address\"\
  \n      }\n    },\n    \"Order\": {\n      \"@id\": \"https://schema.org/Order\",\n      \"@context\": {\n        \"id\": \"https://schema.org/orderNumber\",\n        \"patient\": \"https://schema.org/customer\",\n        \"practice\": \"https://schema.org/seller\",\n        \"lab\": \"https://schema.org/provider\",\n        \"status\": \"https://schema.org/orderStatus\"\n      }\n    },\n    \"Scan\": {\n      \"@id\": \"ds:scan\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"patient\": \"https://schema.org/about\",\n        \"captureDate\": \"https://schema.org/dateCreated\",\n        \"device\": \"https://schema.org/usedDevice\",\n        \"format\": \"https://schema.org/encodingFormat\"\n      }\n    },\n    \"Image\": {\n      \"@id\": \"https://schema.org/MedicalImagingTechnique\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"patient\": \"https://schema.org/about\",\n        \"modality\": \"https://schema.org/category\"\
  ,\n        \"captureDate\": \"https://schema.org/dateCreated\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dentsply-sirona/refs/heads/main/json-ld/dentsply-sirona-context.jsonld
tags:
- CAD/CAM
- CEREC
- Dental
- DS Core
- Imaging
- Intraoral Imaging
- Lab Management
- Practice Management
- JSON-LD
- Linked Data
- Semantic Web
---
