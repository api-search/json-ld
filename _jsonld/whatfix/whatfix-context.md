---
api_specs:
- filename: whatfix-openapi.yml
  format: yaml
  label: Whatfix API
  slug: whatfix-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/openapi/whatfix-openapi.yml
class_count: 38
classes:
- DigitalAdoptionPlatform
- EndUser
- Content
- Flow
- Tooltip
- TaskList
- SmartTip
- Beacon
- Survey
- Segment
- FlowAnalytics
- userId
- contentId
- flowId
- segmentId
- targetUrl
- viewCount
- completionRate
- avgTimeToComplete
- lastSeenAt
- segmentationAttributes
- inAppGuidance
- selfHelp
- name
- description
- url
- email
- identifier
- dateCreated
- dateModified
- status
- knowsAbout
- audience
- SoftwareApplication
- Person
- Action
- Event
- Thing
context_file: json-ld/whatfix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/json-ld/whatfix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Whatfix from Whatfix.
layout: jsonld
name: Whatfix Context
namespaces:
- prefix: whatfix
  uri: https://whatfix.com/vocab#
properties: []
property_count: 0
provider_name: Whatfix
provider_slug: whatfix
slug: whatfix-context
source_filename: whatfix-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"whatfix\": \"https://whatfix.com/vocab#\",\n\n    \"DigitalAdoptionPlatform\": \"whatfix:DigitalAdoptionPlatform\",\n    \"EndUser\": \"whatfix:EndUser\",\n    \"Content\": \"whatfix:Content\",\n    \"Flow\": \"whatfix:Flow\",\n    \"Tooltip\": \"whatfix:Tooltip\",\n    \"TaskList\": \"whatfix:TaskList\",\n    \"SmartTip\": \"whatfix:SmartTip\",\n    \"Beacon\": \"whatfix:Beacon\",\n    \"Survey\": \"whatfix:Survey\",\n    \"Segment\": \"whatfix:Segment\",\n    \"FlowAnalytics\": \"whatfix:FlowAnalytics\",\n\n    \"userId\": \"whatfix:userId\",\n    \"contentId\": \"whatfix:contentId\",\n    \"flowId\": \"whatfix:flowId\",\n    \"segmentId\": \"whatfix:segmentId\",\n    \"targetUrl\": \"whatfix:targetUrl\",\n    \"viewCount\": \"whatfix:viewCount\",\n    \"completionRate\": \"whatfix:completionRate\",\n    \"avgTimeToComplete\": \"whatfix:avgTimeToComplete\",\n    \"lastSeenAt\": \"whatfix:lastSeenAt\",\n\
  \    \"segmentationAttributes\": \"whatfix:segmentationAttributes\",\n    \"inAppGuidance\": \"whatfix:inAppGuidance\",\n    \"selfHelp\": \"whatfix:selfHelp\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"email\": \"schema:email\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"status\": \"schema:status\",\n    \"knowsAbout\": \"schema:knowsAbout\",\n    \"audience\": \"schema:audience\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Person\": \"schema:Person\",\n    \"Action\": \"schema:Action\",\n    \"Event\": \"schema:Event\",\n    \"Thing\": \"schema:Thing\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/json-ld/whatfix-context.jsonld
tags:
- Digital Adoption
- SaaS Management
- User Onboarding
- In-App Guidance
- Analytics
- Change Management
- JSON-LD
- Linked Data
- Semantic Web
---
