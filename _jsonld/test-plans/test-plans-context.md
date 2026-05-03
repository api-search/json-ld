---
api_specs:
- filename: swagger.v3.json
  format: json
  label: Jira Software API
  slug: ''
  spec_type: OpenAPI
  url: https://dac-static.atlassian.com/cloud/jira/software/swagger.v3.json
- filename: vsts-rest-api-specs
  format: yaml
  label: Azure DevOps Test Plans API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/MicrosoftDocs/vsts-rest-api-specs
class_count: 3
classes:
- TestMilestone
- TestCycle
- TestPlan
context_file: json-ld/test-plans-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-plans/refs/heads/main/json-ld/test-plans-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Plans from Test Plans.
layout: jsonld
name: Test Plans Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: testplans
  uri: https://api-evangelist.github.io/test-plans/schema/
properties:
- container: ''
  name: approach
  type: string
- container: ''
  name: blocked
  type: integer
- container: ''
  name: buildVersion
  type: string
- container: ''
  name: completedDate
  type: date
- container: ''
  name: createdAt
  type: ''
- container: set
  name: criteria
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: dueDate
  type: date
- container: ''
  name: endDate
  type: date
- container: set
  name: entryCriteria
  type: string
- container: ''
  name: environment
  type: string
- container: set
  name: environments
  type: string
- container: set
  name: exitCriteria
  type: string
- container: ''
  name: failed
  type: integer
- container: ''
  name: id
  type: ''
- container: set
  name: inScope
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: notExecuted
  type: integer
- container: ''
  name: objectives
  type: string
- container: set
  name: outOfScope
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: passed
  type: integer
- container: ''
  name: projectId
  type: string
- container: ''
  name: scope
  type: ''
- container: ''
  name: startDate
  type: date
- container: ''
  name: status
  type: string
- container: set
  name: testCycleIds
  type: string
- container: ''
  name: testPlanId
  type: string
- container: set
  name: testTypes
  type: string
- container: ''
  name: totalTests
  type: integer
- container: ''
  name: updatedAt
  type: ''
property_count: 31
provider_name: Test Plans
provider_slug: test-plans
slug: test-plans-context
source_filename: test-plans-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"testplans\": \"https://api-evangelist.github.io/test-plans/schema/\",\n    \"TestMilestone\": \"testplans:TestMilestone\",\n    \"TestCycle\": \"testplans:TestCycle\",\n    \"TestPlan\": \"testplans:TestPlan\",\n    \"approach\": {\n      \"@id\": \"testplans:approach\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blocked\": {\n      \"@id\": \"testplans:blocked\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"buildVersion\": {\n      \"@id\": \"testplans:build_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedDate\": {\n      \"@id\": \"testplans:completed_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"criteria\": {\n      \"@id\": \"testplans:criteria\",\n      \"@container\": \"\
  @set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"dueDate\": {\n      \"@id\": \"testplans:due_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"testplans:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"entryCriteria\": {\n      \"@id\": \"testplans:entry_criteria\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"testplans:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environments\": {\n      \"@id\": \"testplans:environments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exitCriteria\": {\n      \"@id\": \"testplans:exit_criteria\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failed\": {\n      \"@id\": \"testplans:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\"\
  \n    },\n    \"inScope\": {\n      \"@id\": \"testplans:in_scope\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"notExecuted\": {\n      \"@id\": \"testplans:not_executed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"objectives\": {\n      \"@id\": \"testplans:objectives\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outOfScope\": {\n      \"@id\": \"testplans:out_of_scope\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"testplans:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passed\": {\n      \"@id\": \"testplans:passed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectId\": {\n      \"@id\": \"testplans:project_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"testplans:scope\"\n    },\n    \"startDate\": {\n      \"@id\": \"testplans:start_date\",\n      \"@type\"\
  : \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"testplans:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testCycleIds\": {\n      \"@id\": \"testplans:test_cycle_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testPlanId\": {\n      \"@id\": \"testplans:test_plan_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testTypes\": {\n      \"@id\": \"testplans:test_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTests\": {\n      \"@id\": \"testplans:total_tests\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-plans/refs/heads/main/json-ld/test-plans-context.jsonld
tags:
- Documentation
- Quality Assurance
- Software Development
- Test Management
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
