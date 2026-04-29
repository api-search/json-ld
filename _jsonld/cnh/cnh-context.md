---
api_specs:
- filename: cnh-fieldops-openapi.yml
  format: yaml
  label: CNH FieldOps API
  slug: cnh-fieldops-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/openapi/cnh-fieldops-openapi.yml
class_count: 31
classes:
- Equipment
- Telemetry
- FaultCode
- Location
- Operation
- Prescription
- Field
- Farm
- Grower
- vehicleId
- brand
- model
- serialNumber
- year
- vehicleType
- profile
- windowStart
- windowEnd
- operatingHours
- idleHours
- fuelRemainingRatio
- defRemaining
- peakDailySpeed
- distance
- errorTags
- code
- severity
- latitude
- longitude
- altitude
- gpsFix
context_file: json-ld/cnh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/json-ld/cnh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cnh from CNH.
layout: jsonld
name: Cnh Context
namespaces:
- prefix: cnh
  uri: https://api.fieldops.cnh.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: iso15143
  uri: https://www.iso.org/standard/63110.html#
properties: []
property_count: 0
provider_name: CNH
provider_slug: cnh
slug: cnh-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cnh\": \"https://api.fieldops.cnh.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"iso15143\": \"https://www.iso.org/standard/63110.html#\",\n    \"Equipment\": \"cnh:Equipment\",\n    \"Telemetry\": \"cnh:Telemetry\",\n    \"FaultCode\": \"cnh:FaultCode\",\n    \"Location\": \"cnh:Location\",\n    \"Operation\": \"cnh:Operation\",\n    \"Prescription\": \"cnh:Prescription\",\n    \"Field\": \"cnh:Field\",\n    \"Farm\": \"cnh:Farm\",\n    \"Grower\": \"cnh:Grower\",\n    \"vehicleId\": \"cnh:vehicleId\",\n    \"brand\": \"cnh:brand\",\n    \"model\": \"cnh:model\",\n    \"serialNumber\": \"cnh:serialNumber\",\n    \"year\": \"cnh:year\",\n    \"vehicleType\": \"cnh:vehicleType\",\n    \"profile\": \"cnh:profile\",\n    \"windowStart\": \"cnh:windowStart\",\n    \"windowEnd\": \"cnh:windowEnd\",\n    \"operatingHours\": \"cnh:operatingHours\",\n    \"idleHours\": \"cnh:idleHours\",\n    \"fuelRemainingRatio\"\
  : \"cnh:fuelRemainingRatio\",\n    \"defRemaining\": \"cnh:defRemaining\",\n    \"peakDailySpeed\": \"cnh:peakDailySpeed\",\n    \"distance\": \"cnh:distance\",\n    \"errorTags\": \"cnh:errorTags\",\n    \"code\": \"cnh:faultCode\",\n    \"severity\": \"cnh:severity\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"altitude\": \"schema:elevation\",\n    \"gpsFix\": \"cnh:gpsFix\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/json-ld/cnh-context.jsonld
tags:
- Agriculture
- Construction
- Telematics
- Equipment
- FieldOps
- JSON-LD
- Linked Data
- Semantic Web
---
