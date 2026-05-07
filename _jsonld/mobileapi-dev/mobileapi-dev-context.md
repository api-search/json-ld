---
api_specs:
- filename: mobileapi-openapi.yml
  format: yaml
  label: MobileAPI
  slug: mobileapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mobileapi-dev/refs/heads/main/openapi/mobileapi-openapi.yml
class_count: 43
classes:
- id
- type
- name
- manufacturer_name
- description
- device_type
- colors
- weight
- thickness
- screen_resolution
- storage
- camera
- battery_capacity
- hardware
- image_b64
- logo_b64
- is_official
- order
- caption
- battery
- display
- platform
- memory
- main_camera
- selfie_camera
- sound
- comms
- features
- body
- network
- misc
- technology
- bands_2g
- bands_3g
- bands_4g
- bands_5g
- speed
- size
- resolution
- protection
- modules
- video
- charging
context_file: json-ld/mobileapi-dev-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mobileapi-dev/refs/heads/main/json-ld/mobileapi-dev-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mobileapi Dev from MobileAPI.dev.
layout: jsonld
name: Mobileapi Dev Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: mobileapi
  uri: https://mobileapi.dev/vocab#
properties:
- container: ''
  name: Device
  type: reference
- container: ''
  name: Manufacturer
  type: reference
- container: ''
  name: Image
  type: reference
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: release_date
  type: schema:Date
- container: ''
  name: image_url
  type: reference
- container: ''
  name: website_url
  type: reference
property_count: 7
provider_name: MobileAPI.dev
provider_slug: mobileapi-dev
slug: mobileapi-dev-context
source_filename: mobileapi-dev-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"mobileapi\": \"https://mobileapi.dev/vocab#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Device\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"Manufacturer\": {\n      \"@id\": \"schema:Brand\",\n      \"@type\": \"@id\"\n    },\n    \"Image\": {\n      \"@id\": \"schema:ImageObject\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"manufacturer_name\": \"schema:brand\",\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n    \"description\": \"schema:description\",\n    \"device_type\": \"mobileapi:deviceType\",\n    \"colors\": \"schema:color\",\n    \"release_date\": {\n      \"@id\": \"schema:releaseDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"weight\": \"mobileapi:weight\",\n    \"thickness\": \"mobileapi:thickness\",\n    \"screen_resolution\"\
  : \"mobileapi:screenResolution\",\n    \"storage\": \"mobileapi:storage\",\n    \"camera\": \"mobileapi:cameraSummary\",\n    \"battery_capacity\": \"mobileapi:batteryCapacity\",\n    \"hardware\": \"mobileapi:hardwareSummary\",\n    \"image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"image_b64\": \"mobileapi:imageBase64\",\n    \"logo_b64\": \"mobileapi:logoBase64\",\n    \"website_url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"is_official\": \"mobileapi:isOfficial\",\n    \"order\": \"schema:position\",\n    \"caption\": \"schema:caption\",\n    \"battery\": \"mobileapi:battery\",\n    \"display\": \"mobileapi:display\",\n    \"platform\": \"mobileapi:platform\",\n    \"memory\": \"mobileapi:memory\",\n    \"main_camera\": \"mobileapi:mainCamera\",\n    \"selfie_camera\": \"mobileapi:selfieCamera\",\n    \"sound\": \"mobileapi:sound\",\n    \"comms\": \"mobileapi:comms\",\n    \"features\": \"mobileapi:features\"\
  ,\n    \"body\": \"mobileapi:body\",\n    \"network\": \"mobileapi:network\",\n    \"misc\": \"mobileapi:misc\",\n    \"technology\": \"mobileapi:networkTechnology\",\n    \"bands_2g\": \"mobileapi:bands2g\",\n    \"bands_3g\": \"mobileapi:bands3g\",\n    \"bands_4g\": \"mobileapi:bands4g\",\n    \"bands_5g\": \"mobileapi:bands5g\",\n    \"speed\": \"mobileapi:networkSpeed\",\n    \"size\": \"mobileapi:displaySize\",\n    \"resolution\": \"mobileapi:displayResolution\",\n    \"protection\": \"mobileapi:displayProtection\",\n    \"modules\": \"mobileapi:cameraModules\",\n    \"video\": \"mobileapi:cameraVideo\",\n    \"charging\": \"mobileapi:batteryCharging\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mobileapi-dev/refs/heads/main/json-ld/mobileapi-dev-context.jsonld
tags:
- Data API
- Developer Tools
- Device Specifications
- Mobile Data
- Phone Specs
- REST API
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
