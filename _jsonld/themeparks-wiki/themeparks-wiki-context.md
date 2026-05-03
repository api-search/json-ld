---
api_specs:
- filename: themeparks-wiki-openapi.yml
  format: yaml
  label: ThemeParks.wiki API
  slug: themeparks-wiki
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/openapi/themeparks-wiki-openapi.yml
class_count: 12
classes:
- Location
- Destination
- LiveDataResponse
- LiveEntityData
- ScheduleResponse
- ScheduleEntry
- Entity
- Park
- ChildrenResponse
- QueueData
- DestinationsResponse
- name
context_file: json-ld/themeparks-wiki-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/json-ld/themeparks-wiki-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Themeparks Wiki from ThemeParks.wiki.
layout: jsonld
name: Themeparks Wiki Context
namespaces:
- prefix: themeparks
  uri: https://api.themeparks.wiki/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: id
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: externalId
  type: string
- container: set
  name: parks
  type: string
- container: ''
  name: entityType
  type: string
- container: set
  name: liveData
  type: string
- container: ''
  name: entityId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: queue
  type: string
- container: ''
  name: STANDBY
  type: string
- container: ''
  name: SINGLERider
  type: string
- container: ''
  name: RETURNTime
  type: string
- container: ''
  name: returnStart
  type: string
- container: ''
  name: returnEnd
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: lastUpdated
  type: string
- container: set
  name: showtimes
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: schedule
  type: string
- container: ''
  name: date
  type: string
- container: ''
  name: openingTime
  type: string
- container: ''
  name: closingTime
  type: string
- container: ''
  name: specialHours
  type: boolean
- container: ''
  name: parentId
  type: string
- container: ''
  name: location
  type: string
- container: set
  name: children
  type: string
- container: ''
  name: waitTime
  type: integer
- container: set
  name: destinations
  type: string
property_count: 32
provider_name: ThemeParks.wiki
provider_slug: themeparks-wiki
slug: themeparks-wiki-context
source_filename: themeparks-wiki-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"themeparks\": \"https://api.themeparks.wiki/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Location\": \"themeparks:Location\",\n    \"Destination\": \"themeparks:Destination\",\n    \"LiveDataResponse\": \"themeparks:LiveDataResponse\",\n    \"LiveEntityData\": \"themeparks:LiveEntityData\",\n    \"ScheduleResponse\": \"themeparks:ScheduleResponse\",\n    \"ScheduleEntry\": \"themeparks:ScheduleEntry\",\n    \"Entity\": \"themeparks:Entity\",\n    \"Park\": \"themeparks:Park\",\n    \"ChildrenResponse\": \"themeparks:ChildrenResponse\",\n    \"QueueData\": \"themeparks:QueueData\",\n    \"DestinationsResponse\": \"themeparks:DestinationsResponse\",\n    \"latitude\": {\n      \"@id\": \"themeparks:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"themeparks:longitude\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"id\": {\n      \"@id\": \"themeparks:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"themeparks:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"themeparks:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parks\": {\n      \"@id\": \"themeparks:parks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityType\": {\n      \"@id\": \"themeparks:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveData\": {\n      \"@id\": \"themeparks:liveData\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityId\": {\n      \"@id\": \"themeparks:entityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"themeparks:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queue\": {\n      \"@id\": \"themeparks:queue\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"STANDBY\": {\n      \"@id\": \"themeparks:STANDBY\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SINGLERider\": {\n      \"@id\": \"themeparks:SINGLE_RIDER\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RETURNTime\": {\n      \"@id\": \"themeparks:RETURN_TIME\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnStart\": {\n      \"@id\": \"themeparks:returnStart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnEnd\": {\n      \"@id\": \"themeparks:returnEnd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"themeparks:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"themeparks:lastUpdated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showtimes\": {\n      \"@id\": \"themeparks:showtimes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"themeparks:startTime\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"themeparks:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"themeparks:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"themeparks:schedule\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"themeparks:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openingTime\": {\n      \"@id\": \"themeparks:openingTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closingTime\": {\n      \"@id\": \"themeparks:closingTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specialHours\": {\n      \"@id\": \"themeparks:specialHours\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"parentId\": {\n      \"@id\": \"themeparks:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"themeparks:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"children\"\
  : {\n      \"@id\": \"themeparks:children\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waitTime\": {\n      \"@id\": \"themeparks:waitTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"destinations\": {\n      \"@id\": \"themeparks:destinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/json-ld/themeparks-wiki-context.jsonld
tags:
- Entertainment
- Real-Time
- Theme Parks
- Wait Times
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
