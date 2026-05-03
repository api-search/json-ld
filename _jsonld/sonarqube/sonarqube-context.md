---
api_specs:
- filename: sonarqube-web-api-openapi.yml
  format: yaml
  label: SonarQube Web API
  slug: web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/openapi/sonarqube-web-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sonarqube-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/json-ld/sonarqube-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sonarqube from SonarQube.
layout: jsonld
name: Sonarqube Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sonarqube
  uri: https://docs.sonarsource.com/sonarqube-server/latest/vocabulary/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: SonarQube
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Issue
  type: ''
- container: ''
  name: QualityGate
  type: ''
- container: ''
  name: Measure
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: User
  type: ''
property_count: 7
provider_name: SonarQube
provider_slug: sonarqube
slug: sonarqube-context
source_filename: sonarqube-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sonarqube\": \"https://docs.sonarsource.com/sonarqube-server/latest/vocabulary/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"SonarQube\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"version\": \"schema:version\",\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\"\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"key\": \"@id\",\n        \"name\": \"schema:name\",\n        \"visibility\": \"schema:accessMode\",\n        \"lastAnalysisDate\": \"schema:dateModified\",\n        \"revision\": \"sonarqube:revision\"\n      }\n    },\n\n    \"Issue\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"key\": \"@id\",\n        \"rule\": \"sonarqube:rule\",\n        \"severity\": \"sonarqube:severity\",\n        \"type\": \"sonarqube:issueType\"\
  ,\n        \"status\": \"sonarqube:issueStatus\",\n        \"resolution\": \"sonarqube:resolution\",\n        \"message\": \"schema:description\",\n        \"component\": \"sonarqube:component\",\n        \"line\": \"sonarqube:line\",\n        \"creationDate\": \"schema:dateCreated\",\n        \"updateDate\": \"schema:dateModified\",\n        \"assignee\": \"sonarqube:assignee\",\n        \"author\": \"schema:author\",\n        \"effort\": \"sonarqube:effort\"\n      }\n    },\n\n    \"QualityGate\": {\n      \"@id\": \"sonarqube:QualityGate\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"isDefault\": \"sonarqube:isDefault\",\n        \"isBuiltIn\": \"sonarqube:isBuiltIn\",\n        \"conditions\": \"sonarqube:conditions\"\n      }\n    },\n\n    \"Measure\": {\n      \"@id\": \"schema:MeasuredValue\",\n      \"@context\": {\n        \"metric\": \"schema:measurementMethod\",\n        \"value\": \"schema:value\"\n      }\n    },\n\n   \
  \ \"Rule\": {\n      \"@id\": \"sonarqube:Rule\",\n      \"@context\": {\n        \"key\": \"@id\",\n        \"name\": \"schema:name\",\n        \"lang\": \"sonarqube:language\",\n        \"type\": \"sonarqube:ruleType\",\n        \"severity\": \"sonarqube:severity\",\n        \"htmlDesc\": \"schema:description\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"login\": \"@id\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"active\": \"schema:active\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/json-ld/sonarqube-context.jsonld
tags:
- Code Quality
- DevOps
- Security
- Static Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
