---
api_specs:
- filename: appyway-availability-realtime-api-openapi.yml
  format: yaml
  label: AppyWay Availability RealTime API
  slug: appyway-availability-realtime-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appyway/refs/heads/main/openapi/appyway-availability-realtime-api-openapi.yml
- filename: appyway-traffic-data-api-openapi.yml
  format: yaml
  label: AppyWay Traffic Data API
  slug: appyway-traffic-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appyway/refs/heads/main/openapi/appyway-traffic-data-api-openapi.yml
- filename: appyway-explorer-api-openapi.yml
  format: yaml
  label: AppyWay Explorer API
  slug: appyway-explorer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appyway/refs/heads/main/openapi/appyway-explorer-api-openapi.yml
- filename: appyway-platform-api-openapi.yml
  format: yaml
  label: AppyWay Platform API
  slug: appyway-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appyway/refs/heads/main/openapi/appyway-platform-api-openapi.yml
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
