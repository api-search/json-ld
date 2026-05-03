---
class_count: 4
classes:
- GovernmentOrganization
- TouristAttraction
- CivicStructure
- Museum
context_file: json-ld/us-capitol-visitor-center-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-capitol-visitor-center/refs/heads/main/json-ld/us-capitol-visitor-center-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Capitol Visitor Center from US Capitol Visitor Center.
layout: jsonld
name: Us Capitol Visitor Center Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: CapitolVisitorCenter
  type: reference
- container: ''
  name: CapitolTour
  type: reference
- container: ''
  name: TourReservation
  type: reference
- container: ''
  name: EducationalProgram
  type: reference
- container: ''
  name: tourName
  type: string
- container: ''
  name: tourDescription
  type: string
- container: ''
  name: tourDuration
  type: string
- container: ''
  name: startTime
  type: time
- container: ''
  name: endTime
  type: time
- container: ''
  name: reservationDate
  type: date
- container: ''
  name: reservationNumber
  type: string
- container: ''
  name: groupSize
  type: integer
- container: ''
  name: isFree
  type: boolean
- container: ''
  name: location
  type: reference
- container: ''
  name: address
  type: reference
- container: ''
  name: openingHours
  type: string
- container: ''
  name: telephone
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: image
  type: reference
- container: ''
  name: exhibit
  type: reference
- container: ''
  name: educationalLevel
  type: string
- container: ''
  name: targetAudience
  type: reference
- container: ''
  name: publisher
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: modified
  type: date
property_count: 26
provider_name: US Capitol Visitor Center
provider_slug: us-capitol-visitor-center
slug: us-capitol-visitor-center-context
source_filename: us-capitol-visitor-center-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"CapitolVisitorCenter\": {\n      \"@id\": \"schema:GovernmentBuilding\",\n      \"@type\": \"@id\"\n    },\n    \"CapitolTour\": {\n      \"@id\": \"schema:TouristTrip\",\n      \"@type\": \"@id\"\n    },\n    \"TourReservation\": {\n      \"@id\": \"schema:TouristTrip\",\n      \"@type\": \"@id\"\n    },\n    \"EducationalProgram\": {\n      \"@id\": \"schema:EducationalOccupationalProgram\",\n      \"@type\": \"@id\"\n    },\n\n    \"tourName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourDescription\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourDuration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startTime\"\
  ,\n      \"@type\": \"xsd:time\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:time\"\n    },\n    \"reservationDate\": {\n      \"@id\": \"schema:reservationFor\",\n      \"@type\": \"xsd:date\"\n    },\n    \"reservationNumber\": {\n      \"@id\": \"schema:reservationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupSize\": {\n      \"@id\": \"schema:numberOfRooms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isFree\": {\n      \"@id\": \"schema:isAccessibleForFree\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"@id\"\n    },\n    \"openingHours\": {\n      \"@id\": \"schema:openingHours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephone\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\":\
  \ \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"image\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"exhibit\": {\n      \"@id\": \"schema:Exhibit\",\n      \"@type\": \"@id\"\n    },\n    \"educationalLevel\": {\n      \"@id\": \"schema:educationalLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAudience\": {\n      \"@id\": \"schema:audience\",\n      \"@type\": \"@id\"\n    },\n\n    \"GovernmentOrganization\": \"schema:GovernmentOrganization\",\n    \"TouristAttraction\": \"schema:TouristAttraction\",\n    \"CivicStructure\": \"schema:CivicStructure\",\n    \"Museum\": \"schema:Museum\",\n    \"publisher\": {\n      \"@id\": \"dct:publisher\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"dct:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dct:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n   \
  \   \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-capitol-visitor-center/refs/heads/main/json-ld/us-capitol-visitor-center-context.jsonld
tags:
- Federal Government
- Legislative Branch
- Tourism
- Education
- US Capitol
- JSON-LD
- Linked Data
- Semantic Web
---
