---
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-apps-script/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Apps Script.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: script
  uri: https://script.googleapis.com/v1/
- prefix: goog
  uri: https://developers.google.com/apps-script/api/reference/rest/v1/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: File
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: Process
  type: ''
property_count: 5
provider_name: Google Apps Script
provider_slug: google-apps-script
slug: json-ld
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"script\": \"https://script.googleapis.com/v1/\",\n    \"goog\": \"https://developers.google.com/apps-script/api/reference/rest/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"Project\": {\n      \"@id\": \"goog:projects\",\n      \"@context\": {\n        \"scriptId\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"parentId\": \"schema:isPartOf\",\n        \"createTime\": \"schema:dateCreated\",\n        \"updateTime\": \"schema:dateModified\",\n        \"creator\": \"schema:creator\"\n      }\n    },\n    \"File\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:programmingLanguage\",\n        \"source\": \"schema:text\",\n        \"createTime\": \"schema:dateCreated\",\n        \"updateTime\"\
  : \"schema:dateModified\"\n      }\n    },\n    \"Deployment\": {\n      \"@id\": \"goog:projects.deployments\",\n      \"@context\": {\n        \"deploymentId\": \"schema:identifier\",\n        \"deploymentConfig\": \"schema:softwareRequirements\",\n        \"updateTime\": \"schema:dateModified\"\n      }\n    },\n    \"Version\": {\n      \"@id\": \"goog:projects.versions\",\n      \"@context\": {\n        \"versionNumber\": \"schema:version\",\n        \"description\": \"schema:description\",\n        \"createTime\": \"schema:dateCreated\"\n      }\n    },\n    \"Process\": {\n      \"@id\": \"goog:processes\",\n      \"@context\": {\n        \"projectName\": \"schema:name\",\n        \"functionName\": \"schema:description\",\n        \"processType\": \"schema:additionalType\",\n        \"processStatus\": \"schema:status\",\n        \"startTime\": \"schema:startDate\",\n        \"duration\": \"schema:duration\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Apps\
  \ Script API\",\n  \"description\": \"The Apps Script API manages Google Apps Script projects, deployments, versions, and script execution processes.\",\n  \"url\": \"https://developers.google.com/apps-script/api/concepts\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-apps-script/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Apps Script
- Automation
- Deployments
- Google
- Google Workspace
- Scripting
- JSON-LD
- Linked Data
- Semantic Web
---
