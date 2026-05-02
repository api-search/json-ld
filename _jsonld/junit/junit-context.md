---
class_count: 13
classes:
- name
- description
- url
- TestSuite
- TestCase
- TestResult
- TestFailure
- TestError
- tests
- failures
- errors
- skipped
- time
context_file: json-ld/junit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/junit/refs/heads/main/json-ld/junit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Junit from JUnit.
layout: jsonld
name: Junit Context
namespaces:
- prefix: ju
  uri: https://raw.githubusercontent.com/api-evangelist/junit/main/json-ld/junit-context.jsonld#
properties: []
property_count: 0
provider_name: JUnit
provider_slug: junit
slug: junit-context
source_filename: junit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ju\": \"https://raw.githubusercontent.com/api-evangelist/junit/main/json-ld/junit-context.jsonld#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"TestSuite\": \"ju:TestSuite\",\n    \"TestCase\": \"ju:TestCase\",\n    \"TestResult\": \"ju:TestResult\",\n    \"TestFailure\": \"ju:TestFailure\",\n    \"TestError\": \"ju:TestError\",\n    \"tests\": \"ju:tests\",\n    \"failures\": \"ju:failures\",\n    \"errors\": \"ju:errors\",\n    \"skipped\": \"ju:skipped\",\n    \"time\": \"ju:time\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/junit/refs/heads/main/json-ld/junit-context.jsonld
tags:
- Java
- TDD
- Test Automation
- Testing
- Unit Testing
- JSON-LD
- Linked Data
- Semantic Web
---
