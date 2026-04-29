---
class_count: 0
classes: []
context_file: json-ld/acc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/autodesk-construction-cloud/refs/heads/main/json-ld/acc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acc from Autodesk Construction Cloud.
layout: jsonld
name: Acc Context
namespaces:
- prefix: acc
  uri: https://aps.autodesk.com/en/docs/acc/v1/reference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Issue
  type: ''
- container: ''
  name: ProjectUser
  type: ''
property_count: 3
provider_name: Autodesk Construction Cloud
provider_slug: autodesk-construction-cloud
slug: acc-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acc\": \"https://aps.autodesk.com/en/docs/acc/v1/reference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": {\n      \"@id\": \"schema:Project\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"accountId\": {\"@id\": \"acc:accountId\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"startDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n        \"endDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:date\"},\n        \"projectValue\": {\"@id\": \"schema:priceRange\"},\n        \"status\": {\"@id\": \"acc:projectStatus\"},\n        \"jobNumber\": {\"@id\": \"schema:productID\"},\n        \"city\": {\"@id\": \"schema:addressLocality\"},\n        \"stateOrProvince\": {\"@id\": \"schema:addressRegion\"},\n        \"country\": {\"@id\": \"schema:addressCountry\"},\n        \"constructionType\"\
  : {\"@id\": \"acc:constructionType\"},\n        \"deliveryMethod\": {\"@id\": \"acc:deliveryMethod\"},\n        \"currentPhase\": {\"@id\": \"acc:currentPhase\"}\n      }\n    },\n\n    \"Issue\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"displayId\": {\"@id\": \"acc:issueDisplayId\", \"@type\": \"xsd:integer\"},\n        \"title\": {\"@id\": \"schema:name\"},\n        \"description\": {\"@id\": \"schema:description\"},\n        \"status\": {\"@id\": \"acc:issueStatus\"},\n        \"issueTypeId\": {\"@id\": \"acc:issueType\"},\n        \"dueDate\": {\"@id\": \"schema:scheduledTime\", \"@type\": \"xsd:date\"},\n        \"assignedToId\": {\"@id\": \"schema:agent\"},\n        \"locationDescription\": {\"@id\": \"schema:locationCreated\"},\n        \"createdBy\": {\"@id\": \"schema:creator\"},\n        \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n        \"closedAt\": {\"@id\"\
  : \"schema:endTime\", \"@type\": \"xsd:dateTime\"}\n      }\n    },\n\n    \"ProjectUser\": {\n      \"@id\": \"schema:OrganizationRole\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"email\": {\"@id\": \"schema:email\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"status\": {\"@id\": \"acc:userStatus\"},\n        \"roleIds\": {\"@id\": \"schema:roleName\", \"@container\": \"@set\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/autodesk-construction-cloud/refs/heads/main/json-ld/acc-context.jsonld
tags:
- Construction
- BIM
- Project Management
- AEC
- CAD
- Architecture
- Engineering
- Field Management
- JSON-LD
- Linked Data
- Semantic Web
---
