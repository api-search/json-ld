---
class_count: 26
classes:
- Hub
- Project
- Folder
- Item
- Version
- Bucket
- ObjectDetail
- Issue
- Webhook
- WebhookEvent
- Photoscene
- DigitalTwin
- Activity
- AppBundle
- WorkItem
- ParameterDefinition
- ParameterCollection
- id
- type
- name
- description
- displayName
- created
- modified
- creator
- title
context_file: json-ld/autodesk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/autodesk/refs/heads/main/json-ld/autodesk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Autodesk from Autodesk.
layout: jsonld
name: Autodesk Context
namespaces:
- prefix: adsk
  uri: https://developer.api.autodesk.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: hubId
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: folderId
  type: string
- container: ''
  name: itemId
  type: string
- container: ''
  name: versionNumber
  type: integer
- container: ''
  name: urn
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: mimeType
  type: string
- container: ''
  name: fileType
  type: string
- container: ''
  name: storageSize
  type: integer
- container: ''
  name: bucketKey
  type: string
- container: ''
  name: objectKey
  type: string
- container: ''
  name: policyKey
  type: string
- container: ''
  name: callbackUrl
  type: anyURI
- container: ''
  name: event
  type: string
- container: ''
  name: system
  type: string
- container: ''
  name: hookId
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: assignedTo
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: engine
  type: string
- container: ''
  name: activityId
  type: string
- container: ''
  name: emissionFactor
  type: decimal
- container: ''
  name: gwp
  type: decimal
- container: ''
  name: twin
  type: reference
- container: ''
  name: model
  type: reference
- container: ''
  name: element
  type: reference
- container: set
  name: hasProject
  type: reference
- container: set
  name: hasFolder
  type: reference
- container: set
  name: hasItem
  type: reference
- container: set
  name: hasVersion
  type: reference
- container: ''
  name: parentFolder
  type: reference
- container: ''
  name: parentHub
  type: reference
property_count: 34
provider_name: Autodesk
provider_slug: autodesk
slug: autodesk-context
source_filename: autodesk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adsk\": \"https://developer.api.autodesk.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Hub\": \"adsk:Hub\",\n    \"Project\": \"adsk:Project\",\n    \"Folder\": \"adsk:Folder\",\n    \"Item\": \"adsk:Item\",\n    \"Version\": \"adsk:Version\",\n    \"Bucket\": \"adsk:Bucket\",\n    \"ObjectDetail\": \"adsk:ObjectDetail\",\n    \"Issue\": \"adsk:Issue\",\n    \"Webhook\": \"adsk:Webhook\",\n    \"WebhookEvent\": \"adsk:WebhookEvent\",\n    \"Photoscene\": \"adsk:Photoscene\",\n    \"DigitalTwin\": \"adsk:DigitalTwin\",\n    \"Activity\": \"adsk:Activity\",\n    \"AppBundle\": \"adsk:AppBundle\",\n    \"WorkItem\": \"adsk:WorkItem\",\n    \"ParameterDefinition\": \"adsk:ParameterDefinition\",\n    \"ParameterCollection\": \"adsk:ParameterCollection\"\
  ,\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"displayName\": \"schema:name\",\n    \"created\": \"dcterms:created\",\n    \"modified\": \"dcterms:modified\",\n    \"creator\": \"dcterms:creator\",\n\n    \"hubId\": {\n      \"@id\": \"adsk:hubId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"adsk:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"folderId\": {\n      \"@id\": \"adsk:folderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemId\": {\n      \"@id\": \"adsk:itemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionNumber\": {\n      \"@id\": \"adsk:versionNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"urn\": {\n      \"@id\": \"adsk:urn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"adsk:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adsk:status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"mimeType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileType\": {\n      \"@id\": \"adsk:fileType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageSize\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bucketKey\": {\n      \"@id\": \"adsk:bucketKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectKey\": {\n      \"@id\": \"adsk:objectKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyKey\": {\n      \"@id\": \"adsk:policyKey\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"callbackUrl\": {\n      \"@id\": \"adsk:callbackUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"event\": {\n      \"@id\": \"adsk:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"system\": {\n      \"@id\": \"adsk:system\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hookId\": {\n      \"@id\": \"adsk:hookId\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n\n    \"title\": \"schema:name\",\n    \"priority\": {\n      \"@id\": \"adsk:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedTo\": {\n      \"@id\": \"adsk:assignedTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dueDate\": {\n      \"@id\": \"adsk:dueDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"engine\": {\n      \"@id\": \"adsk:engine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityId\": {\n      \"@id\": \"adsk:activityId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"emissionFactor\": {\n      \"@id\": \"adsk:emissionFactor\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"gwp\": {\n      \"@id\": \"adsk:globalWarmingPotential\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"twin\": {\n      \"@id\": \"adsk:twin\",\n      \"@type\": \"@id\"\n    },\n    \"model\": {\n      \"@id\": \"adsk:model\",\n      \"@type\": \"@id\"\n    },\n    \"element\": {\n      \"@id\": \"adsk:element\",\n      \"@type\"\
  : \"@id\"\n    },\n\n    \"hasProject\": {\n      \"@id\": \"adsk:hasProject\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"hasFolder\": {\n      \"@id\": \"adsk:hasFolder\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"hasItem\": {\n      \"@id\": \"adsk:hasItem\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"hasVersion\": {\n      \"@id\": \"adsk:hasVersion\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"parentFolder\": {\n      \"@id\": \"adsk:parentFolder\",\n      \"@type\": \"@id\"\n    },\n    \"parentHub\": {\n      \"@id\": \"adsk:parentHub\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/autodesk/refs/heads/main/json-ld/autodesk-context.jsonld
tags:
- 3D Modeling
- Architecture
- BIM
- CAD
- Construction
- Design
- Digital Twins
- Engineering
- Manufacturing
- Media and Entertainment
- Sustainability
- JSON-LD
- Linked Data
- Semantic Web
---
