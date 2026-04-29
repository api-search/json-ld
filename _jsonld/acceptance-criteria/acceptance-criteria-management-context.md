---
class_count: 38
classes:
- UserStory
- AcceptanceCriterion
- Scenario
- TestRun
- id
- title
- description
- status
- priority
- storyPoints
- acceptanceCriteria
- tags
- assignee
- storyId
- criterionId
- format
- given
- when
- then
- order
- featureFile
- gherkin
- storyIds
- scenarioIds
- totalScenarios
- passedScenarios
- failedScenarios
- skippedScenarios
- reportUrl
- total
- page
- pageSize
- stories
- criteria
- runs
- code
- message
- details
context_file: json-ld/acceptance-criteria-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acceptance-criteria/refs/heads/main/json-ld/acceptance-criteria-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acceptance Criteria Management from Acceptance Criteria.
layout: jsonld
name: Acceptance Criteria Management Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: ac
  uri: https://api.example.com/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: lastRunAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
property_count: 5
provider_name: Acceptance Criteria
provider_slug: acceptance-criteria
slug: acceptance-criteria-management-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ac\": \"https://api.example.com/vocab/\",\n\n    \"UserStory\": \"ac:UserStory\",\n    \"AcceptanceCriterion\": \"ac:AcceptanceCriterion\",\n    \"Scenario\": \"ac:Scenario\",\n    \"TestRun\": \"ac:TestRun\",\n\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"status\": \"ac:status\",\n    \"priority\": \"ac:priority\",\n    \"storyPoints\": \"ac:storyPoints\",\n    \"acceptanceCriteria\": \"ac:acceptanceCriteria\",\n    \"tags\": \"schema:keywords\",\n    \"assignee\": \"schema:assignee\",\n\n    \"storyId\": \"ac:userStory\",\n    \"criterionId\": \"ac:acceptanceCriterion\"\
  ,\n    \"format\": \"ac:criterionFormat\",\n    \"given\": \"ac:given\",\n    \"when\": \"ac:when\",\n    \"then\": \"ac:then\",\n    \"order\": \"ac:order\",\n\n    \"featureFile\": \"ac:featureFile\",\n    \"gherkin\": \"ac:gherkin\",\n    \"lastRunAt\": {\n      \"@id\": \"ac:lastRunAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"storyIds\": \"ac:userStories\",\n    \"scenarioIds\": \"ac:scenarios\",\n    \"totalScenarios\": \"ac:totalScenarios\",\n    \"passedScenarios\": \"ac:passedScenarios\",\n    \"failedScenarios\": \"ac:failedScenarios\",\n    \"skippedScenarios\": \"ac:skippedScenarios\",\n    \"startedAt\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reportUrl\": \"schema:url\",\n\n    \"total\": \"ac:total\",\n    \"page\": \"ac:page\",\n    \"pageSize\": \"ac:pageSize\",\n    \"stories\": \"ac:stories\",\n    \"criteria\"\
  : \"ac:criteria\",\n    \"runs\": \"ac:runs\",\n\n    \"code\": \"ac:errorCode\",\n    \"message\": \"schema:description\",\n    \"details\": \"ac:errorDetails\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acceptance-criteria/refs/heads/main/json-ld/acceptance-criteria-management-context.jsonld
tags:
- Agile
- Behavior Driven Development
- Gherkin
- Quality Assurance
- Requirements
- Testing
- User Stories
- JSON-LD
- Linked Data
- Semantic Web
---
