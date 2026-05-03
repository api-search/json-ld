---
class_count: 4
classes:
- TestCase
- TestResult
- TestStep
- TestSuite
context_file: json-ld/test-cases-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-cases/refs/heads/main/json-ld/test-cases-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Cases from Test Cases.
layout: jsonld
name: Test Cases Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: testcases
  uri: https://api-evangelist.github.io/test-cases/schema/
properties:
- container: ''
  name: action
  type: string
- container: ''
  name: actualResult
  type: string
- container: ''
  name: automationStatus
  type: string
- container: ''
  name: buildVersion
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: createdAt
  type: ''
- container: ''
  name: createdBy
  type: string
- container: set
  name: defects
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: durationMs
  type: integer
- container: ''
  name: environment
  type: string
- container: ''
  name: executedAt
  type: dateTime
- container: ''
  name: executedBy
  type: string
- container: ''
  name: expectedResult
  type: string
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: notes
  type: string
- container: ''
  name: parentSuiteId
  type: string
- container: ''
  name: preconditions
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: projectId
  type: string
- container: set
  name: requirementRefs
  type: string
- container: ''
  name: screenshotUrl
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: stepNumber
  type: integer
- container: set
  name: stepResults
  type: ''
- container: set
  name: steps
  type: ''
- container: ''
  name: suiteId
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: testCaseId
  type: string
- container: set
  name: testCaseIds
  type: string
- container: ''
  name: testData
  type: string
- container: ''
  name: testRunId
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: totalTestCases
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: ''
property_count: 37
provider_name: Test Cases
provider_slug: test-cases
slug: test-cases-context
source_filename: test-cases-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"testcases\": \"https://api-evangelist.github.io/test-cases/schema/\",\n    \"TestCase\": \"testcases:TestCase\",\n    \"TestResult\": \"testcases:TestResult\",\n    \"TestStep\": \"testcases:TestStep\",\n    \"TestSuite\": \"testcases:TestSuite\",\n    \"action\": {\n      \"@id\": \"testcases:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actualResult\": {\n      \"@id\": \"testcases:actual_result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automationStatus\": {\n      \"@id\": \"testcases:automation_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildVersion\": {\n      \"@id\": \"testcases:build_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"testcases:comment\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"createdBy\": {\n      \"@id\": \"testcases:created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defects\": {\n      \"@id\": \"testcases:defects\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"durationMs\": {\n      \"@id\": \"testcases:duration_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"environment\": {\n      \"@id\": \"testcases:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executedAt\": {\n      \"@id\": \"testcases:executed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"executedBy\": {\n      \"@id\": \"testcases:executed_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expectedResult\": {\n      \"@id\": \"testcases:expected_result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n    \"name\": {\n\
  \      \"@id\": \"schema:name\"\n    },\n    \"notes\": {\n      \"@id\": \"testcases:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentSuiteId\": {\n      \"@id\": \"testcases:parent_suite_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preconditions\": {\n      \"@id\": \"testcases:preconditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"testcases:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"testcases:project_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requirementRefs\": {\n      \"@id\": \"testcases:requirement_refs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"screenshotUrl\": {\n      \"@id\": \"testcases:screenshot_url\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"testcases:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepNumber\": {\n      \"@id\": \"testcases:step_number\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"stepResults\": {\n      \"@id\": \"testcases:step_results\",\n      \"@container\": \"@set\"\n    },\n    \"steps\": {\n      \"@id\": \"testcases:steps\",\n      \"@container\": \"@set\"\n    },\n    \"suiteId\": {\n      \"@id\": \"testcases:suite_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"testcases:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testCaseId\": {\n      \"@id\": \"testcases:test_case_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testCaseIds\": {\n      \"@id\": \"testcases:test_case_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testData\": {\n      \"@id\": \"testcases:test_data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testRunId\": {\n      \"@id\": \"testcases:test_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"testcases:title\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"totalTestCases\": {\n      \"@id\": \"testcases:total_test_cases\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"testcases:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-cases/refs/heads/main/json-ld/test-cases-context.jsonld
tags:
- API Testing
- Automation
- Quality Assurance
- Software Development
- Software Testing
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
