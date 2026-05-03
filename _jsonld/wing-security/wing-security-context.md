---
class_count: 26
classes:
- SaaSApplication
- AIAgent
- riskScore
- riskLevel
- permissions
- connections
- misconfigurations
- threatIndicators
- discoverySource
- discoveryMethod
- dataAccess
- owner
- status
- firstSeen
- lastSeen
- mitreTechnique
- shadowAI
- shadowIT
- sspm
- itdr
- name
- description
- vendor
- category
- SoftwareApplication
- Organization
context_file: json-ld/wing-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wing-security/refs/heads/main/json-ld/wing-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wing Security from Wing Security.
layout: jsonld
name: Wing Security Context
namespaces:
- prefix: wing
  uri: https://wing.security/vocab/
properties: []
property_count: 0
provider_name: Wing Security
provider_slug: wing-security
slug: wing-security-context
source_filename: wing-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wing\": \"https://wing.security/vocab/\",\n    \"SaaSApplication\": \"wing:SaaSApplication\",\n    \"AIAgent\": \"wing:AIAgent\",\n    \"riskScore\": \"wing:riskScore\",\n    \"riskLevel\": \"wing:riskLevel\",\n    \"permissions\": \"wing:permissions\",\n    \"connections\": \"wing:connections\",\n    \"misconfigurations\": \"wing:misconfigurations\",\n    \"threatIndicators\": \"wing:threatIndicators\",\n    \"discoverySource\": \"wing:discoverySource\",\n    \"discoveryMethod\": \"wing:discoveryMethod\",\n    \"dataAccess\": \"wing:dataAccess\",\n    \"owner\": \"wing:owner\",\n    \"status\": \"wing:status\",\n    \"firstSeen\": \"wing:firstSeen\",\n    \"lastSeen\": \"wing:lastSeen\",\n    \"mitreTechnique\": \"wing:mitreTechnique\",\n    \"shadowAI\": \"wing:shadowAI\",\n    \"shadowIT\": \"wing:shadowIT\",\n    \"sspm\": \"wing:sspm\",\n    \"itdr\": \"wing:itdr\",\n    \"name\": \"schema:name\",\n\
  \    \"description\": \"schema:description\",\n    \"vendor\": \"schema:provider\",\n    \"category\": \"schema:category\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Organization\": \"schema:Organization\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wing-security/refs/heads/main/json-ld/wing-security-context.jsonld
tags:
- AI Security
- Identity Threat Detection
- ITDR
- SaaS Security
- SSPM
- Supply Chain Security
- JSON-LD
- Linked Data
- Semantic Web
---
