---
api_specs:
- filename: trimble-connect-openapi.yml
  format: yaml
  label: Trimble Connect API
  slug: trimble-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/openapi/trimble-connect-openapi.yml
- filename: trimble-maps-openapi.yml
  format: yaml
  label: Trimble Maps API
  slug: trimble-maps
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/openapi/trimble-maps-openapi.yml
class_count: 32
classes:
- Project
- File
- Topic
- Route
- RouteStop
- Member
- id
- name
- description
- status
- type
- location
- createdBy
- fileType
- contentType
- size
- version
- path
- guid
- topicType
- topicStatus
- title
- priority
- assignedTo
- totalMiles
- totalHours
- routeType
- vehicleType
- stops
- legs
- role
- email
context_file: json-ld/trimble-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/json-ld/trimble-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trimble from Trimble.
layout: jsonld
name: Trimble Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: trimble
  uri: https://developer.trimble.com/vocab/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: thumbnail
  type: reference
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: dueDate
  type: date
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
property_count: 7
provider_name: Trimble
provider_slug: trimble
slug: trimble-context
source_filename: trimble-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"trimble\": \"https://developer.trimble.com/vocab/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": \"schema:Project\",\n    \"File\": \"schema:DigitalDocument\",\n    \"Topic\": \"schema:ItemList\",\n    \"Route\": \"schema:Trip\",\n    \"RouteStop\": \"schema:Place\",\n    \"Member\": \"schema:OrganizationMember\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"type\": \"schema:additionalType\",\n    \"location\": \"schema:location\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": \"schema:author\",\n    \"thumbnail\"\
  : {\n      \"@id\": \"schema:thumbnailUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"fileType\": \"schema:fileFormat\",\n    \"contentType\": \"schema:encodingFormat\",\n    \"size\": \"schema:contentSize\",\n    \"version\": \"schema:version\",\n    \"downloadUrl\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"path\": \"schema:path\",\n\n    \"guid\": \"schema:identifier\",\n    \"topicType\": \"schema:additionalType\",\n    \"topicStatus\": \"schema:actionStatus\",\n    \"title\": \"schema:name\",\n    \"priority\": \"schema:priority\",\n    \"assignedTo\": \"schema:contributor\",\n    \"dueDate\": {\n      \"@id\": \"schema:scheduledTime\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"totalMiles\": \"schema:distance\",\n    \"totalHours\": \"schema:duration\",\n    \"routeType\": \"trimble:routeType\",\n    \"vehicleType\": \"schema:vehicleEngine\",\n    \"stops\": \"schema:itemListElement\",\n    \"legs\": \"trimble:routeLegs\",\n\n    \"\
  latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n\n    \"role\": \"schema:roleName\",\n    \"email\": \"schema:email\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/json-ld/trimble-context.jsonld
tags:
- Construction
- Transportation
- Geospatial
- GPS
- Mapping
- BIM
- Fleet Management
- Collaboration
- Agriculture
- JSON-LD
- Linked Data
- Semantic Web
---
