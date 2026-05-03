---
api_specs:
- filename: segment-public-api-openapi.yml
  format: yaml
  label: Segment Public API
  slug: public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-public-api-openapi.yml
- filename: segment-http-tracking-api-openapi.yml
  format: yaml
  label: Segment HTTP Tracking API
  slug: http-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-http-tracking-api-openapi.yml
- filename: segment-profile-api-openapi.yml
  format: yaml
  label: Segment Profile API
  slug: profile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-profile-api-openapi.yml
- filename: segment-config-api-openapi.yml
  format: yaml
  label: Segment Config API
  slug: config-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-config-api-openapi.yml
- filename: segment-pixel-tracking-api-openapi.yml
  format: yaml
  label: Segment Pixel Tracking API
  slug: pixel-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-pixel-tracking-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/segment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/json-ld/segment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Segment from segment.
layout: jsonld
name: Segment Context
namespaces:
- prefix: segment
  uri: https://segment.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Source
  type: ''
- container: ''
  name: Destination
  type: ''
- container: ''
  name: Warehouse
  type: ''
- container: ''
  name: TrackingPlan
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: UserProfile
  type: ''
- container: ''
  name: Function
  type: ''
- container: ''
  name: Regulation
  type: ''
property_count: 9
provider_name: segment
provider_slug: segment
slug: segment-context
source_filename: segment-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"segment\": \"https://segment.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Workspace\": {\n      \"@id\": \"segment:Workspace\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"segment:slug\",\n        \"workspaceId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Source\": {\n      \"@id\": \"segment:Source\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"segment:slug\",\n        \"sourceId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\": \"segment:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"writeKeys\": {\n          \"@id\": \"segment:writeKeys\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"workspace\": {\n          \"@id\": \"segment:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"catalogEntry\": {\n          \"@id\": \"segment:catalogEntry\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": {\n          \"@id\": \"segment:labels\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Destination\": {\n      \"@id\": \"segment:Destination\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"destinationId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\": \"segment:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"source\": {\n          \"@id\": \"segment:source\",\n          \"@type\": \"@id\"\n        },\n        \"catalogEntry\": {\n          \"@id\": \"segment:catalogEntry\",\n          \"@type\": \"@id\"\n        },\n        \"\
  connectionMode\": {\n          \"@id\": \"segment:connectionMode\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Warehouse\": {\n      \"@id\": \"segment:Warehouse\",\n      \"@context\": {\n        \"warehouseId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\": \"segment:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"warehouseType\": {\n          \"@id\": \"segment:warehouseType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"TrackingPlan\": {\n      \"@id\": \"segment:TrackingPlan\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"trackingPlanId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"planType\": {\n          \"@id\": \"segment:planType\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"rules\": {\n          \"@id\": \"segment:rules\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"segment:Event\",\n      \"@context\": {\n        \"eventType\": {\n          \"@id\": \"segment:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"eventName\": \"schema:name\",\n        \"userId\": {\n          \"@id\": \"segment:userId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"anonymousId\": {\n          \"@id\": \"segment:anonymousId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"messageId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n        \
  \  \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"properties\": {\n          \"@id\": \"segment:properties\"\n        },\n        \"traits\": {\n          \"@id\": \"segment:traits\"\n        },\n        \"context\": {\n          \"@id\": \"segment:context\"\n        }\n      }\n    },\n\n    \"UserProfile\": {\n      \"@id\": \"segment:UserProfile\",\n      \"@context\": {\n        \"segmentId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"traits\": {\n          \"@id\": \"segment:traits\"\n        },\n        \"externalIds\": {\n          \"@id\": \"segment:externalIds\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Function\"\
  : {\n      \"@id\": \"segment:Function\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"functionId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceType\": {\n          \"@id\": \"segment:resourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"segment:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Regulation\": {\n      \"@id\": \"segment:Regulation\",\n      \"@context\": {\n        \"regulationId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"regulationType\": {\n          \"@id\": \"segment:regulationType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n  \
  \        \"@id\": \"segment:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/json-ld/segment-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
