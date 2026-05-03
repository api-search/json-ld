---
api_specs:
- filename: api.github.com.json
  format: json
  label: GitHub Actions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json
- filename: openapi.json
  format: json
  label: CircleCI API
  slug: ''
  spec_type: OpenAPI
  url: https://circleci.com/api/v2/openapi.json
class_count: 3
classes:
- CoverageReport
- TDDCycle
- TestSpec
context_file: json-ld/test-driven-development-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-driven-development/refs/heads/main/json-ld/test-driven-development-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Driven Development from Test-Driven Development.
layout: jsonld
name: Test Driven Development Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: testdrivendevelopment
  uri: https://api-evangelist.github.io/test-driven-development/schema/
properties:
- container: set
  name: assertions
  type: ''
- container: ''
  name: branch
  type: string
- container: ''
  name: branchesPct
  type: decimal
- container: ''
  name: buildId
  type: string
- container: ''
  name: commitHash
  type: string
- container: ''
  name: context
  type: string
- container: ''
  name: createdAt
  type: ''
- container: ''
  name: describe
  type: string
- container: ''
  name: expected
  type: ''
- container: ''
  name: filePath
  type: string
- container: set
  name: files
  type: ''
- container: ''
  name: framework
  type: string
- container: ''
  name: functionsPct
  type: decimal
- container: ''
  name: generatedAt
  type: dateTime
- container: ''
  name: given
  type: string
- container: ''
  name: id
  type: ''
- container: ''
  name: implementationCode
  type: string
- container: ''
  name: itShould
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: linesCovered
  type: integer
- container: ''
  name: linesPct
  type: decimal
- container: ''
  name: linesTotal
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: phase
  type: string
- container: ''
  name: project
  type: string
- container: ''
  name: refactoredCode
  type: string
- container: ''
  name: statementsPct
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: summary
  type: ''
- container: set
  name: tags
  type: string
- container: ''
  name: testCode
  type: string
- container: ''
  name: testDescription
  type: string
- container: ''
  name: testName
  type: string
- container: ''
  name: testStatus
  type: string
- container: ''
  name: then
  type: string
- container: ''
  name: tool
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: when
  type: string
property_count: 39
provider_name: Test-Driven Development
provider_slug: test-driven-development
slug: test-driven-development-context
source_filename: test-driven-development-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"testdrivendevelopment\": \"https://api-evangelist.github.io/test-driven-development/schema/\",\n    \"CoverageReport\": \"testdrivendevelopment:CoverageReport\",\n    \"TDDCycle\": \"testdrivendevelopment:TDDCycle\",\n    \"TestSpec\": \"testdrivendevelopment:TestSpec\",\n    \"assertions\": {\n      \"@id\": \"testdrivendevelopment:assertions\",\n      \"@container\": \"@set\"\n    },\n    \"branch\": {\n      \"@id\": \"testdrivendevelopment:branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branchesPct\": {\n      \"@id\": \"testdrivendevelopment:branches_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"buildId\": {\n      \"@id\": \"testdrivendevelopment:build_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commitHash\": {\n      \"@id\": \"testdrivendevelopment:commit_hash\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"testdrivendevelopment:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"describe\": {\n      \"@id\": \"testdrivendevelopment:describe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expected\": {\n      \"@id\": \"testdrivendevelopment:expected\"\n    },\n    \"filePath\": {\n      \"@id\": \"testdrivendevelopment:file_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"testdrivendevelopment:files\",\n      \"@container\": \"@set\"\n    },\n    \"framework\": {\n      \"@id\": \"testdrivendevelopment:framework\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionsPct\": {\n      \"@id\": \"testdrivendevelopment:functions_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"generatedAt\": {\n      \"@id\": \"testdrivendevelopment:generated_at\",\n      \"@type\": \"xsd:dateTime\"\n   \
  \ },\n    \"given\": {\n      \"@id\": \"testdrivendevelopment:given\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n    \"implementationCode\": {\n      \"@id\": \"testdrivendevelopment:implementation_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itShould\": {\n      \"@id\": \"testdrivendevelopment:it_should\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"testdrivendevelopment:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linesCovered\": {\n      \"@id\": \"testdrivendevelopment:lines_covered\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"linesPct\": {\n      \"@id\": \"testdrivendevelopment:lines_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"linesTotal\": {\n      \"@id\": \"testdrivendevelopment:lines_total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"testdrivendevelopment:message\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"phase\": {\n      \"@id\": \"testdrivendevelopment:phase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"testdrivendevelopment:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refactoredCode\": {\n      \"@id\": \"testdrivendevelopment:refactored_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statementsPct\": {\n      \"@id\": \"testdrivendevelopment:statements_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"testdrivendevelopment:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"testdrivendevelopment:summary\"\n    },\n    \"tags\": {\n      \"@id\": \"testdrivendevelopment:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testCode\": {\n      \"@id\": \"testdrivendevelopment:test_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testDescription\"\
  : {\n      \"@id\": \"testdrivendevelopment:test_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testName\": {\n      \"@id\": \"testdrivendevelopment:test_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testStatus\": {\n      \"@id\": \"testdrivendevelopment:test_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"then\": {\n      \"@id\": \"testdrivendevelopment:then\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tool\": {\n      \"@id\": \"testdrivendevelopment:tool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"testdrivendevelopment:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"when\": {\n      \"@id\": \"testdrivendevelopment:when\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-driven-development/refs/heads/main/json-ld/test-driven-development-context.jsonld
tags:
- Agile
- Best Practices
- Continuous Integration
- Extreme Programming
- Methodology
- Software Development
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
