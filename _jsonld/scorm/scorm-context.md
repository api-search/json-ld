---
class_count: 0
classes: []
context_file: json-ld/scorm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/json-ld/scorm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scorm from SCORM.
layout: jsonld
name: Scorm Context
namespaces:
- prefix: scorm
  uri: https://api-evangelist.github.io/scorm/vocab#
- prefix: adl
  uri: https://www.adlnet.gov/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: lrmi
  uri: http://purl.org/dcx/lrmi-terms/
properties:
- container: ''
  name: LearningPackage
  type: rdfs:Class
- container: ''
  name: SCO
  type: rdfs:Class
- container: ''
  name: LearnerRecord
  type: rdfs:Class
- container: ''
  name: Interaction
  type: rdfs:Class
- container: ''
  name: completionStatus
  type: string
- container: ''
  name: successStatus
  type: string
- container: ''
  name: lessonStatus
  type: string
- container: ''
  name: score
  type: decimal
- container: ''
  name: scaledScore
  type: decimal
- container: ''
  name: totalTime
  type: string
- container: ''
  name: suspendData
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: progressMeasure
  type: decimal
- container: ''
  name: learnerId
  type: string
- container: ''
  name: learnerName
  type: string
- container: ''
  name: educationalLevel
  type: string
property_count: 16
provider_name: SCORM
provider_slug: scorm
slug: scorm-context
source_filename: scorm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"scorm\": \"https://api-evangelist.github.io/scorm/vocab#\",\n    \"adl\": \"https://www.adlnet.gov/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"lrmi\": \"http://purl.org/dcx/lrmi-terms/\",\n\n    \"LearningPackage\": {\n      \"@id\": \"schema:LearningResource\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A SCORM content package (ZIP file with imsmanifest.xml)\"\n    },\n    \"SCO\": {\n      \"@id\": \"scorm:ShareableContentObject\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A Shareable Content Object - the atomic unit of SCORM learning content\"\n    },\n    \"LearnerRecord\": {\n      \"@id\": \"scorm:LearnerRecord\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A record of a learner's interactions with a SCORM SCO\"\n    },\n    \"Interaction\": {\n      \"@id\": \"scorm:Interaction\",\n      \"@type\": \"rdfs:Class\",\n   \
  \   \"rdfs:comment\": \"A learner interaction (quiz question response, exercise completion)\"\n    },\n\n    \"completionStatus\": {\n      \"@id\": \"adl:completionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"successStatus\": {\n      \"@id\": \"adl:successStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lessonStatus\": {\n      \"@id\": \"scorm:lessonStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"schema:achievementStatus\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"scaledScore\": {\n      \"@id\": \"adl:scaledScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalTime\": {\n      \"@id\": \"schema:timeRequired\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suspendData\": {\n      \"@id\": \"scorm:suspendData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"scorm:learnerLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progressMeasure\": {\n      \"@id\": \"adl:progressMeasure\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"learnerId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"learnerName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"educationalLevel\": {\n      \"@id\": \"lrmi:educationalLevel\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/json-ld/scorm-context.jsonld
tags:
- E-Learning
- LMS
- Standards
- Education
- Interoperability
- JSON-LD
- Linked Data
- Semantic Web
---
