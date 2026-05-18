---
class_count: 8
classes:
- name
- description
- license
- codeRepository
- SoftwareLibrary
- ClinicalDataTool
- BioinformaticsTool
- DevOpsTool
context_file: json-ld/roche-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roche/refs/heads/main/json-ld/roche-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roche from Roche.
layout: jsonld
name: Roche Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: roche
  uri: https://github.com/Roche#
properties: []
property_count: 0
provider_name: Roche
provider_slug: roche
slug: roche-context
source_filename: roche-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://github.com/Roche#\",\n    \"schema\": \"https://schema.org/\",\n    \"roche\": \"https://github.com/Roche#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"license\": \"schema:license\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"SoftwareLibrary\": \"schema:SoftwareSourceCode\",\n    \"ClinicalDataTool\": \"roche:ClinicalDataTool\",\n    \"BioinformaticsTool\": \"roche:BioinformaticsTool\",\n    \"DevOpsTool\": \"roche:DevOpsTool\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roche/refs/heads/main/json-ld/roche-context.jsonld
tags:
- Pharmaceutical
- Biotechnology
- Healthcare
- Diagnostics
- JSON-LD
- Linked Data
- Semantic Web
---
