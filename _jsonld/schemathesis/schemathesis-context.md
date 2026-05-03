---
class_count: 23
classes:
- APITestingTool
- PropertyBasedTest
- TestCase
- TestCheck
- TestResult
- StatefulTest
- FuzzingTarget
- name
- description
- url
- version
- codeRepository
- documentation
- license
- programmingLanguage
- downloadUrl
- checkType
- severity
- maxExamples
- statefulMode
- workerCount
- SoftwareApplication
- SoftwareSourceCode
context_file: json-ld/schemathesis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schemathesis/refs/heads/main/json-ld/schemathesis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schemathesis from Schemathesis.
layout: jsonld
name: Schemathesis Context
namespaces:
- prefix: testing
  uri: https://testing.vocabularies.dev/vocab#
- prefix: schemathesis
  uri: https://schemathesis.io/vocab#
properties:
- container: ''
  name: testsSchema
  type: reference
- container: ''
  name: generatesFrom
  type: reference
property_count: 2
provider_name: Schemathesis
provider_slug: schemathesis
slug: schemathesis-context
source_filename: schemathesis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"testing\": \"https://testing.vocabularies.dev/vocab#\",\n    \"schemathesis\": \"https://schemathesis.io/vocab#\",\n\n    \"APITestingTool\": \"testing:APITestingTool\",\n    \"PropertyBasedTest\": \"testing:PropertyBasedTest\",\n    \"TestCase\": \"testing:TestCase\",\n    \"TestCheck\": \"testing:TestCheck\",\n    \"TestResult\": \"testing:TestResult\",\n    \"StatefulTest\": \"schemathesis:StatefulTest\",\n    \"FuzzingTarget\": \"schemathesis:FuzzingTarget\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"documentation\": \"schema:documentation\",\n    \"license\": \"schema:license\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"downloadUrl\": \"schema:downloadUrl\",\n\n    \"testsSchema\": {\n      \"@id\": \"testing:testsSchema\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"generatesFrom\": {\n      \"@id\": \"schemathesis:generatesFrom\",\n      \"@type\": \"@id\"\n    },\n    \"checkType\": \"testing:checkType\",\n    \"severity\": \"testing:severity\",\n    \"maxExamples\": \"schemathesis:maxExamples\",\n    \"statefulMode\": \"schemathesis:statefulMode\",\n    \"workerCount\": \"schemathesis:workerCount\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\"\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://schemathesis.io\",\n      \"@type\": [\"SoftwareApplication\", \"APITestingTool\"],\n      \"name\": \"Schemathesis\",\n      \"description\": \"A property-based API testing tool that automatically generates test cases from OpenAPI and GraphQL schemas to find bugs and spec violations.\",\n      \"url\": \"https://schemathesis.io\",\n      \"documentation\": \"https://schemathesis.readthedocs.io\",\n      \"codeRepository\": \"https://github.com/schemathesis/schemathesis\"\
  ,\n      \"programmingLanguage\": \"Python\",\n      \"downloadUrl\": \"https://pypi.org/project/schemathesis/\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schemathesis/refs/heads/main/json-ld/schemathesis-context.jsonld
tags:
- API Testing
- Contract Testing
- Fuzzing
- OpenAPI
- Property-Based Testing
- Schemathesis
- JSON-LD
- Linked Data
- Semantic Web
---
