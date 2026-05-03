---
class_count: 0
classes: []
context_file: json-ld/scott-foresman-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scott-foresman/refs/heads/main/json-ld/scott-foresman-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scott Foresman from Scott Foresman.
layout: jsonld
name: Scott Foresman Context
namespaces:
- prefix: lrmi
  uri: http://purl.org/dcx/lrmi-terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: EducationalContent
  type: rdfs:Class
- container: ''
  name: TextbookSeries
  type: rdfs:Class
- container: ''
  name: Publisher
  type: rdfs:Class
- container: ''
  name: gradeLevel
  type: string
- container: ''
  name: subjectArea
  type: string
- container: ''
  name: publisher
  type: reference
- container: ''
  name: isbn
  type: string
- container: ''
  name: publicationDate
  type: date
- container: ''
  name: seriesTitle
  type: reference
- container: ''
  name: curriculum
  type: string
- container: ''
  name: educationalAlignment
  type: reference
property_count: 11
provider_name: Scott Foresman
provider_slug: scott-foresman
slug: scott-foresman-context
source_filename: scott-foresman-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"lrmi\": \"http://purl.org/dcx/lrmi-terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"EducationalContent\": {\n      \"@id\": \"schema:LearningResource\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"K-12 educational content from Scott Foresman / Savvas Learning\"\n    },\n    \"TextbookSeries\": {\n      \"@id\": \"schema:BookSeries\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A multi-volume educational textbook series\"\n    },\n    \"Publisher\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"Educational content publisher\"\n    },\n\n    \"gradeLevel\": {\n      \"@id\": \"lrmi:educationalLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectArea\": {\n      \"@id\": \"lrmi:educationalSubject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publisher\": {\n      \"@id\": \"schema:publisher\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"isbn\": {\n      \"@id\": \"schema:isbn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicationDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"seriesTitle\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"curriculum\": {\n      \"@id\": \"lrmi:teaches\",\n      \"@type\": \"xsd:string\"\n    },\n    \"educationalAlignment\": {\n      \"@id\": \"schema:educationalAlignment\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scott-foresman/refs/heads/main/json-ld/scott-foresman-context.jsonld
tags:
- Education
- Publishing
- K-12
- E-Learning
- Textbooks
- JSON-LD
- Linked Data
- Semantic Web
---
