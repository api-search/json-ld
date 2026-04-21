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
