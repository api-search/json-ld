---
api_specs:
- filename: teamcity-rest-api.yml
  format: yaml
  label: TeamCity REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teamcity/refs/heads/main/openapi/teamcity-rest-api.yml
class_count: 0
classes: []
context_file: json-ld/teamcity-rest-api.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/teamcity/refs/heads/main/json-ld/teamcity-rest-api.jsonld
description: JSON-LD context defining the semantic vocabulary for Teamcity Rest Api from TeamCity.
layout: jsonld
name: Teamcity Rest Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tc
  uri: https://api-evangelist.github.io/teamcity/json-ld/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: BuildType
  type: ''
- container: ''
  name: Build
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: VcsRoot
  type: ''
- container: ''
  name: Change
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: TestOccurrence
  type: ''
- container: ''
  name: AgentPool
  type: ''
property_count: 9
provider_name: TeamCity
provider_slug: teamcity
slug: teamcity-rest-api
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api-evangelist.github.io/teamcity/json-ld/\",\n    \"schema\": \"https://schema.org/\",\n    \"tc\": \"https://api-evangelist.github.io/teamcity/json-ld/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": {\n      \"@id\": \"tc:Project\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n        \"webUrl\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n        \"parentProjectId\": {\"@id\": \"tc:parentProject\", \"@type\": \"xsd:string\"},\n        \"archived\": {\"@id\": \"tc:archived\", \"@type\": \"xsd:boolean\"},\n        \"buildTypes\": {\"@id\": \"tc:hasBuildTypes\", \"@type\": \"@id\"}\n      }\n    },\n\n    \"BuildType\": {\n      \"@id\": \"tc:BuildType\",\n      \"@context\": {\n\
  \        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n        \"projectId\": {\"@id\": \"tc:belongsToProject\", \"@type\": \"xsd:string\"},\n        \"projectName\": {\"@id\": \"tc:projectName\", \"@type\": \"xsd:string\"},\n        \"webUrl\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n        \"paused\": {\"@id\": \"tc:paused\", \"@type\": \"xsd:boolean\"}\n      }\n    },\n\n    \"Build\": {\n      \"@id\": \"tc:Build\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\"},\n        \"buildTypeId\": {\"@id\": \"tc:buildConfiguration\", \"@type\": \"xsd:string\"},\n        \"number\": {\"@id\": \"tc:buildNumber\", \"@type\": \"xsd:string\"},\n        \"status\": {\"@id\": \"tc:buildStatus\", \"@type\": \"xsd:string\"},\n        \"state\": {\"@id\"\
  : \"tc:buildState\", \"@type\": \"xsd:string\"},\n        \"statusText\": {\"@id\": \"tc:statusText\", \"@type\": \"xsd:string\"},\n        \"webUrl\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n        \"branchName\": {\"@id\": \"tc:branch\", \"@type\": \"xsd:string\"},\n        \"startDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\"},\n        \"finishDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:dateTime\"},\n        \"queuedDate\": {\"@id\": \"tc:queuedDate\", \"@type\": \"xsd:dateTime\"},\n        \"agent\": {\"@id\": \"tc:executedByAgent\", \"@type\": \"@id\"},\n        \"triggered\": {\"@id\": \"tc:triggeredBy\", \"@type\": \"@id\"}\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"tc:Agent\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"connected\": {\"@id\": \"tc:connected\", \"@type\": \"xsd:boolean\"\
  },\n        \"enabled\": {\"@id\": \"tc:enabled\", \"@type\": \"xsd:boolean\"},\n        \"authorized\": {\"@id\": \"tc:authorized\", \"@type\": \"xsd:boolean\"},\n        \"ip\": {\"@id\": \"tc:ipAddress\", \"@type\": \"xsd:string\"},\n        \"pool\": {\"@id\": \"tc:assignedPool\", \"@type\": \"@id\"}\n      }\n    },\n\n    \"VcsRoot\": {\n      \"@id\": \"tc:VcsRoot\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"vcsName\": {\"@id\": \"tc:vcsType\", \"@type\": \"xsd:string\"},\n        \"status\": {\"@id\": \"tc:vcsStatus\", \"@type\": \"xsd:string\"}\n      }\n    },\n\n    \"Change\": {\n      \"@id\": \"tc:Change\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\"},\n        \"version\": {\"@id\": \"tc:revision\", \"@type\": \"xsd:string\"},\n        \"username\": {\"@id\": \"schema:author\"\
  , \"@type\": \"xsd:string\"},\n        \"date\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n        \"comment\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"}\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"tc:User\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\"},\n        \"username\": {\"@id\": \"schema:alternateName\", \"@type\": \"xsd:string\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"email\": {\"@id\": \"schema:email\", \"@type\": \"xsd:string\"},\n        \"lastLogin\": {\"@id\": \"tc:lastLogin\", \"@type\": \"xsd:dateTime\"}\n      }\n    },\n\n    \"TestOccurrence\": {\n      \"@id\": \"tc:TestOccurrence\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"status\": {\"@id\": \"tc:testStatus\", \"@type\"\
  : \"xsd:string\"},\n        \"duration\": {\"@id\": \"schema:duration\", \"@type\": \"xsd:integer\"},\n        \"muted\": {\"@id\": \"tc:muted\", \"@type\": \"xsd:boolean\"}\n      }\n    },\n\n    \"AgentPool\": {\n      \"@id\": \"tc:AgentPool\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\"},\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"maxAgents\": {\"@id\": \"tc:maxAgents\", \"@type\": \"xsd:integer\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/teamcity/refs/heads/main/json-ld/teamcity-rest-api.jsonld
tags:
- Build Automation
- CI/CD
- Continuous Integration
- Deployment
- DevOps
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
