---
api_specs:
- filename: thought-industries-openapi.yml
  format: yaml
  label: Thought Industries REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/openapi/thought-industries-openapi.yml
class_count: 20
classes:
- Course
- User
- Enrollment
- Group
- LearningPath
- ContentItem
- email
- first_name
- last_name
- active
- course_id
- user_id
- status
- progress
- enrolled_at
- completed_at
- category_id
- custom_fields
- per_page
- total_pages
context_file: json-ld/thought-industries-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/json-ld/thought-industries-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thought Industries from Thought Industries.
layout: jsonld
name: Thought Industries Context
namespaces:
- prefix: ti
  uri: https://thoughtindustries.com/vocab#
properties: []
property_count: 0
provider_name: Thought Industries
provider_slug: thought-industries
slug: thought-industries-context
source_filename: thought-industries-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ti\": \"https://thoughtindustries.com/vocab#\",\n    \"Course\": \"Course\",\n    \"User\": \"Person\",\n    \"Enrollment\": \"ti:Enrollment\",\n    \"Group\": \"ti:LearnerGroup\",\n    \"LearningPath\": \"ti:LearningPath\",\n    \"ContentItem\": \"LearningResource\",\n    \"email\": \"email\",\n    \"first_name\": \"givenName\",\n    \"last_name\": \"familyName\",\n    \"active\": \"ti:accountActive\",\n    \"course_id\": \"courseId\",\n    \"user_id\": \"ti:learnerId\",\n    \"status\": \"ti:enrollmentStatus\",\n    \"progress\": \"ti:completionPercentage\",\n    \"enrolled_at\": \"startDate\",\n    \"completed_at\": \"endDate\",\n    \"category_id\": \"about\",\n    \"custom_fields\": \"ti:customAttributes\",\n    \"per_page\": \"ti:pageSize\",\n    \"total_pages\": \"ti:totalPages\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/json-ld/thought-industries-context.jsonld
tags:
- Education
- Learning
- LMS
- LXP
- E-Learning
- Training
- JSON-LD
- Linked Data
- Semantic Web
---
