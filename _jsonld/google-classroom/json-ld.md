---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Classroom API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-classroom/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-classroom/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Classroom.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: classroom
  uri: https://classroom.googleapis.com/v1/
- prefix: goog
  uri: https://developers.google.com/workspace/classroom/reference/rest/v1/
properties:
- container: ''
  name: Course
  type: ''
- container: ''
  name: CourseWork
  type: ''
- container: ''
  name: StudentSubmission
  type: ''
- container: ''
  name: Student
  type: ''
- container: ''
  name: Teacher
  type: ''
- container: ''
  name: Announcement
  type: ''
- container: ''
  name: Topic
  type: ''
property_count: 7
provider_name: Google Classroom
provider_slug: google-classroom
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"classroom\": \"https://classroom.googleapis.com/v1/\",\n    \"goog\": \"https://developers.google.com/workspace/classroom/reference/rest/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"Course\": {\n      \"@id\": \"goog:courses\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"section\": \"schema:courseCode\",\n        \"description\": \"schema:description\",\n        \"room\": \"schema:location\",\n        \"ownerId\": \"schema:creator\",\n        \"courseState\": \"schema:status\",\n        \"enrollmentCode\": \"schema:accessCode\",\n        \"creationTime\": \"schema:dateCreated\",\n        \"updateTime\": \"schema:dateModified\"\n      }\n    },\n    \"CourseWork\": {\n      \"@id\": \"goog:courses.courseWork\",\n      \"@context\"\
  : {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"state\": \"schema:creativeWorkStatus\",\n        \"workType\": \"schema:learningResourceType\",\n        \"maxPoints\": \"schema:educationalLevel\",\n        \"dueDate\": \"schema:expires\",\n        \"creationTime\": \"schema:dateCreated\"\n      }\n    },\n    \"StudentSubmission\": {\n      \"@id\": \"goog:courses.courseWork.studentSubmissions\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"userId\": \"schema:agent\",\n        \"state\": \"schema:status\",\n        \"assignedGrade\": \"schema:ratingValue\",\n        \"creationTime\": \"schema:dateCreated\",\n        \"updateTime\": \"schema:dateModified\"\n      }\n    },\n    \"Student\": {\n      \"@id\": \"goog:courses.students\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"profile\": \"schema:Person\"\n      }\n    },\n    \"Teacher\"\
  : {\n      \"@id\": \"goog:courses.teachers\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"profile\": \"schema:Person\"\n      }\n    },\n    \"Announcement\": {\n      \"@id\": \"goog:courses.announcements\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"text\": \"schema:text\",\n        \"state\": \"schema:creativeWorkStatus\",\n        \"creationTime\": \"schema:dateCreated\"\n      }\n    },\n    \"Topic\": {\n      \"@id\": \"goog:courses.topics\",\n      \"@context\": {\n        \"topicId\": \"schema:identifier\",\n        \"name\": \"schema:name\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Classroom API\",\n  \"description\": \"The Google Classroom API manages courses, coursework, student submissions, rosters, and educational workflows.\",\n  \"url\": \"https://developers.google.com/classroom\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"\
  https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-classroom/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Assignments
- Classroom
- Courses
- Education
- Google
- Google Workspace
- Students
- JSON-LD
- Linked Data
- Semantic Web
---
