---
class_count: 12
classes:
- equipmentId
- serialNumber
- model
- type
- status
- location
- installDate
- lastMaintenanceDate
- recordId
- scheduledDate
- completedDate
- notes
context_file: json-ld/applied-materials-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/applied-materials/refs/heads/main/json-ld/applied-materials-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Applied Materials from Applied Materials.
layout: jsonld
name: Applied Materials Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: amat
  uri: https://www.applied-materials.com/vocab#
properties: []
property_count: 0
provider_name: Applied Materials
provider_slug: applied-materials
slug: applied-materials-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"amat\": \"https://www.applied-materials.com/vocab#\",\n    \"equipmentId\": \"schema:identifier\",\n    \"serialNumber\": \"schema:serialNumber\",\n    \"model\": \"schema:model\",\n    \"type\": \"schema:category\",\n    \"status\": \"amat:status\",\n    \"location\": \"schema:location\",\n    \"installDate\": \"schema:dateCreated\",\n    \"lastMaintenanceDate\": \"amat:lastMaintenanceDate\",\n    \"recordId\": \"schema:identifier\",\n    \"scheduledDate\": \"amat:scheduledDate\",\n    \"completedDate\": \"amat:completedDate\",\n    \"notes\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/applied-materials/refs/heads/main/json-ld/applied-materials-context.jsonld
tags:
- Semiconductor
- Manufacturing
- Equipment
- Fab Operations
- Materials Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
