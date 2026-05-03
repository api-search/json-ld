---
api_specs:
- filename: sonar-sonarcloud-api-openapi.yml
  format: yaml
  label: SonarCloud API
  slug: sonarcloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/openapi/sonar-sonarcloud-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sonar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/json-ld/sonar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sonar from Sonar.
layout: jsonld
name: Sonar Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sonar
  uri: https://docs.sonarsource.com/sonarcloud/vocabulary/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
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
  name: UserToken
  type: ''
property_count: 5
provider_name: Sonar
provider_slug: sonar
slug: sonar-context
source_filename: sonar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sonar\": \"https://docs.sonarsource.com/sonarcloud/vocabulary/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"key\": \"@id\",\n        \"name\": \"schema:name\",\n        \"visibility\": \"schema:accessMode\",\n        \"alm\": \"sonar:connectedAlm\"\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"key\": \"@id\",\n        \"name\": \"schema:name\",\n        \"lastAnalysisDate\": \"schema:dateModified\",\n        \"organization\": \"schema:memberOf\",\n        \"visibility\": \"schema:accessMode\"\n      }\n    },\n\n    \"Issue\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"key\": \"@id\",\n        \"rule\": \"sonar:rule\",\n        \"severity\": \"sonar:severity\",\n        \"type\"\
  : \"sonar:issueType\",\n        \"status\": \"sonar:issueStatus\",\n        \"resolution\": \"sonar:resolution\",\n        \"message\": \"schema:description\",\n        \"organization\": \"schema:memberOf\",\n        \"component\": \"sonar:component\",\n        \"creationDate\": \"schema:dateCreated\",\n        \"effort\": \"sonar:effort\"\n      }\n    },\n\n    \"QualityGate\": {\n      \"@id\": \"sonar:QualityGate\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"isDefault\": \"sonar:isDefault\",\n        \"conditions\": \"sonar:conditions\"\n      }\n    },\n\n    \"UserToken\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"login\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"createdAt\": \"schema:dateCreated\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/json-ld/sonar-context.jsonld
tags:
- CI/CD
- Code Quality
- DevOps
- Security
- SonarCloud
- SonarQube
- Static Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
