---
class_count: 0
classes: []
context_file: json-ld/codeproject-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/json-ld/codeproject-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Codeproject from CodeProject.
layout: jsonld
name: Codeproject Context
namespaces:
- prefix: codeproject
  uri: https://www.codeproject.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Article
  type: ''
- container: ''
  name: ForumMessage
  type: ''
- container: ''
  name: Question
  type: ''
- container: ''
  name: UserProfile
  type: ''
- container: ''
  name: Detection
  type: ''
- container: ''
  name: FaceRecognition
  type: ''
- container: ''
  name: LicensePlate
  type: ''
property_count: 7
provider_name: CodeProject
provider_slug: codeproject
slug: codeproject-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"codeproject\": \"https://www.codeproject.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Article\": {\n      \"@id\": \"schema:Article\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:headline\",\n        \"summary\": \"schema:abstract\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"rating\": {\n          \"@id\": \"schema:aggregateRating\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedDate\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ForumMessage\": {\n      \"@id\": \"codeproject:ForumMessage\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"subject\": \"schema:about\",\n        \"body\": \"schema:text\",\n        \"forumId\": \"codeproject:forumId\",\n        \"threadId\": \"codeproject:threadId\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"postedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Question\": {\n      \"@id\": \"schema:Question\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"body\": \"schema:text\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"askedBy\": {\n          \"\
  @id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"askedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"answerCount\": {\n          \"@id\": \"schema:answerCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"isAnswered\": {\n          \"@id\": \"codeproject:isAnswered\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"UserProfile\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"username\": \"schema:alternateName\",\n        \"displayName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"reputation\": {\n          \"@id\": \"codeproject:reputation\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memberSince\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Detection\": {\n      \"@id\": \"codeproject:Detection\"\
  ,\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"confidence\": {\n          \"@id\": \"codeproject:confidence\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"x_min\": \"codeproject:xMin\",\n        \"y_min\": \"codeproject:yMin\",\n        \"x_max\": \"codeproject:xMax\",\n        \"y_max\": \"codeproject:yMax\"\n      }\n    },\n\n    \"FaceRecognition\": {\n      \"@id\": \"codeproject:FaceRecognition\",\n      \"@context\": {\n        \"userid\": \"schema:identifier\",\n        \"confidence\": {\n          \"@id\": \"codeproject:confidence\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"x_min\": \"codeproject:xMin\",\n        \"y_min\": \"codeproject:yMin\",\n        \"x_max\": \"codeproject:xMax\",\n        \"y_max\": \"codeproject:yMax\"\n      }\n    },\n\n    \"LicensePlate\": {\n      \"@id\": \"codeproject:LicensePlate\",\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"plate\": \"codeproject:plate\"\
  ,\n        \"confidence\": {\n          \"@id\": \"codeproject:confidence\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/json-ld/codeproject-context.jsonld
tags:
- AI
- Articles
- Community
- Computer Vision
- Developer Community
- Face Recognition
- Forum
- Knowledge Base
- License Plate Recognition
- Object Detection
- Q&A
- Software Development
- Tutorials
- JSON-LD
- Linked Data
- Semantic Web
---
