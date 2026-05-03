---
api_specs:
- filename: rest-api-spec
  format: yaml
  label: Figma REST API
  slug: figma-api
  spec_type: OpenAPI
  url: https://github.com/figma/rest-api-spec
class_count: 19
classes:
- Wireframe
- WireframeComponent
- DesignSystem
- DesignToken
- Prototype
- fidelity
- annotations
- interactive
- linkedScreen
- designToken
- position
- dimensions
- userFlow
- componentType
- name
- description
- type
- CreativeWork
- SoftwareApplication
context_file: json-ld/wireframes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wireframes/refs/heads/main/json-ld/wireframes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wireframes from Wireframes.
layout: jsonld
name: Wireframes Context
namespaces:
- prefix: wf
  uri: https://www.w3.org/ns/wireframes/
properties: []
property_count: 0
provider_name: Wireframes
provider_slug: wireframes
slug: wireframes-context
source_filename: wireframes-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wf\": \"https://www.w3.org/ns/wireframes/\",\n    \"Wireframe\": \"wf:Wireframe\",\n    \"WireframeComponent\": \"wf:WireframeComponent\",\n    \"DesignSystem\": \"wf:DesignSystem\",\n    \"DesignToken\": \"wf:DesignToken\",\n    \"Prototype\": \"wf:Prototype\",\n    \"fidelity\": \"wf:fidelity\",\n    \"annotations\": \"wf:annotations\",\n    \"interactive\": \"wf:interactive\",\n    \"linkedScreen\": \"wf:linkedScreen\",\n    \"designToken\": \"wf:designToken\",\n    \"position\": \"wf:position\",\n    \"dimensions\": \"wf:dimensions\",\n    \"userFlow\": \"wf:userFlow\",\n    \"componentType\": \"wf:componentType\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"CreativeWork\": \"schema:CreativeWork\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wireframes/refs/heads/main/json-ld/wireframes-context.jsonld
tags:
- Design
- Figma
- Prototyping
- UI Design
- UX
- Wireframing
- JSON-LD
- Linked Data
- Semantic Web
---
