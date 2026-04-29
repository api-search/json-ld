---
class_count: 11
classes:
- locationId
- name
- availableSpaces
- totalSpaces
- occupancyPercent
- timestamp
- coordinates
- latitude
- longitude
- evCharging
- restrictions
context_file: json-ld/appyway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appyway/refs/heads/main/json-ld/appyway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appyway from AppyWay.
layout: jsonld
name: Appyway Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: https://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: appyway
  uri: https://appyway.com/vocab#
properties: []
property_count: 0
provider_name: AppyWay
provider_slug: appyway
slug: appyway-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"https://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"appyway\": \"https://appyway.com/vocab#\",\n    \"locationId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"availableSpaces\": \"appyway:availableSpaces\",\n    \"totalSpaces\": \"appyway:totalSpaces\",\n    \"occupancyPercent\": \"appyway:occupancyPercent\",\n    \"timestamp\": \"schema:dateModified\",\n    \"coordinates\": \"geo:SpatialThing\",\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"evCharging\": \"appyway:evCharging\",\n    \"restrictions\": \"appyway:restrictions\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appyway/refs/heads/main/json-ld/appyway-context.jsonld
tags:
- Parking
- Traffic
- Urban Mobility
- Smart Cities
- EV Charging
- JSON-LD
- Linked Data
- Semantic Web
---
