---
class_count: 4
classes:
- name
- description
- SoftwareApplication
- SoftwareSourceCode
context_file: json-ld/specflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/specflow/refs/heads/main/json-ld/specflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Specflow from SpecFlow.
layout: jsonld
name: Specflow Context
namespaces:
- prefix: specflow
  uri: https://specflow.org/vocab/
- prefix: gherkin
  uri: https://cucumber.io/gherkin/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Feature
  type: reference
- container: ''
  name: Scenario
  type: reference
- container: ''
  name: ScenarioOutline
  type: reference
- container: ''
  name: StepDefinition
  type: reference
- container: ''
  name: Background
  type: reference
- container: ''
  name: Step
  type: reference
- container: ''
  name: Given
  type: ''
- container: ''
  name: When
  type: ''
- container: ''
  name: Then
  type: ''
- container: ''
  name: tag
  type: string
- container: ''
  name: keyword
  type: string
- container: ''
  name: stepText
  type: string
- container: ''
  name: featureFile
  type: string
- container: ''
  name: language
  type: string
property_count: 14
provider_name: SpecFlow
provider_slug: specflow
slug: specflow-context
source_filename: specflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"specflow\": \"https://specflow.org/vocab/\",\n    \"gherkin\": \"https://cucumber.io/gherkin/vocab/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"SoftwareApplication\": \"SoftwareApplication\",\n    \"SoftwareSourceCode\": \"SoftwareSourceCode\",\n    \"Feature\": {\n      \"@id\": \"specflow:Feature\",\n      \"@type\": \"@id\"\n    },\n    \"Scenario\": {\n      \"@id\": \"specflow:Scenario\",\n      \"@type\": \"@id\"\n    },\n    \"ScenarioOutline\": {\n      \"@id\": \"specflow:ScenarioOutline\",\n      \"@type\": \"@id\"\n    },\n    \"StepDefinition\": {\n      \"@id\": \"specflow:StepDefinition\",\n      \"@type\": \"@id\"\n    },\n    \"Background\": {\n      \"@id\": \"specflow:Background\",\n      \"@type\": \"@id\"\n    },\n    \"Step\": {\n      \"@id\": \"gherkin:Step\",\n      \"@type\": \"@id\"\n    },\n    \"Given\": {\n      \"@id\": \"gherkin:Given\"\n    },\n\
  \    \"When\": {\n      \"@id\": \"gherkin:When\"\n    },\n    \"Then\": {\n      \"@id\": \"gherkin:Then\"\n    },\n    \"tag\": {\n      \"@id\": \"specflow:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyword\": {\n      \"@id\": \"gherkin:keyword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepText\": {\n      \"@id\": \"gherkin:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"featureFile\": {\n      \"@id\": \"specflow:featureFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"specflow:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/specflow/refs/heads/main/json-ld/specflow-context.jsonld
tags:
- .NET
- BDD
- Cucumber
- Gherkin
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
