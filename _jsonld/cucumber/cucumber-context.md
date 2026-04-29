---
class_count: 23
classes:
- Feature
- Scenario
- ScenarioOutline
- Step
- StepDefinition
- Pickle
- TestRun
- TestCase
- TestStep
- TestStepResult
- Attachment
- Tag
- name
- description
- keyword
- language
- tags
- steps
- status
- duration
- message
- implementation
- runtime
context_file: json-ld/cucumber-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cucumber/refs/heads/main/json-ld/cucumber-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cucumber from Cucumber.
layout: jsonld
name: Cucumber Context
namespaces:
- prefix: cuc
  uri: https://cucumber.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: uri
  type: anyURI
- container: ''
  name: timestamp
  type: dateTime
property_count: 2
provider_name: Cucumber
provider_slug: cucumber
slug: cucumber-context
source_filename: cucumber-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cuc\": \"https://cucumber.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Feature\": \"cuc:Feature\",\n    \"Scenario\": \"cuc:Scenario\",\n    \"ScenarioOutline\": \"cuc:ScenarioOutline\",\n    \"Step\": \"cuc:Step\",\n    \"StepDefinition\": \"cuc:StepDefinition\",\n    \"Pickle\": \"cuc:Pickle\",\n    \"TestRun\": \"cuc:TestRun\",\n    \"TestCase\": \"cuc:TestCase\",\n    \"TestStep\": \"cuc:TestStep\",\n    \"TestStepResult\": \"cuc:TestStepResult\",\n    \"Attachment\": \"cuc:Attachment\",\n    \"Tag\": \"cuc:Tag\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"keyword\": \"cuc:keyword\",\n    \"language\": \"schema:inLanguage\",\n    \"uri\": {\"@id\": \"schema:url\", \"@type\": \"xsd:anyURI\"},\n    \"tags\": \"cuc:hasTag\",\n    \"steps\": \"cuc:hasStep\",\n    \"status\": \"cuc:resultStatus\",\n    \"duration\"\
  : \"cuc:duration\",\n    \"message\": \"schema:text\",\n    \"timestamp\": {\"@id\": \"schema:dateRecorded\", \"@type\": \"xsd:dateTime\"},\n    \"implementation\": \"cuc:implementation\",\n    \"runtime\": \"cuc:runtime\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cucumber/refs/heads/main/json-ld/cucumber-context.jsonld
tags:
- Automation
- BDD
- Behavior Driven Development
- Gherkin
- Open Source
- Quality Assurance
- Test Framework
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
