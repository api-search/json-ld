---
api_specs:
- filename: canva-connect-api-openapi.yml
  format: yaml
  label: Canva Connect API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/canva/refs/heads/main/openapi/canva-connect-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/canva-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/canva/refs/heads/main/json-ld/canva-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Canva from Canva.
layout: jsonld
name: Canva Context
namespaces:
- prefix: canva
  uri: https://api.canva.com/rest/v1/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Design
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: FolderItem
  type: ''
- container: ''
  name: ExportJob
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: BrandTemplate
  type: ''
- container: ''
  name: AutofillJob
  type: ''
- container: ''
  name: ResizeJob
  type: ''
- container: ''
  name: Owner
  type: ''
- container: ''
  name: TeamUser
  type: ''
- container: ''
  name: Thumbnail
  type: ''
- container: ''
  name: DatasetField
  type: ''
property_count: 13
provider_name: Canva
provider_slug: canva
slug: canva-context
source_filename: canva-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"canva\": \"https://api.canva.com/rest/v1/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Design\": {\n      \"@id\": \"canva:Design\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"owner\": \"canva:owner\",\n        \"urls\": \"canva:designUrls\",\n        \"edit_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"view_url\": {\n          \"@id\": \"canva:viewUrl\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"thumbnail\": \"canva:thumbnail\",\n        \"page_count\": \"canva:pageCount\"\
  \n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"canva:Asset\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": \"canva:assetType\",\n        \"name\": \"schema:name\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"owner\": \"canva:owner\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"thumbnail\": \"canva:thumbnail\",\n        \"import_status\": \"canva:importStatus\"\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"canva:Folder\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"\
  dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"thumbnail\": \"canva:thumbnail\"\n      }\n    },\n\n    \"FolderItem\": {\n      \"@id\": \"canva:FolderItem\",\n      \"@context\": {\n        \"type\": \"canva:itemType\",\n        \"design\": \"canva:design\",\n        \"folder\": \"canva:folder\",\n        \"image\": \"canva:image\"\n      }\n    },\n\n    \"ExportJob\": {\n      \"@id\": \"canva:ExportJob\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"status\": \"canva:jobStatus\",\n        \"urls\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@container\": \"@list\"\n        },\n        \"error\": \"canva:error\"\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"canva:Comment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": \"canva:commentType\",\n        \"message\": \"schema:text\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n  \
  \      \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"mentions\": \"canva:mentions\",\n        \"attached_to\": \"canva:attachedTo\"\n      }\n    },\n\n    \"BrandTemplate\": {\n      \"@id\": \"canva:BrandTemplate\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"view_url\": {\n          \"@id\": \"canva:viewUrl\",\n          \"@type\": \"@id\"\n        },\n        \"create_url\": {\n          \"@id\": \"canva:createUrl\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"thumbnail\": \"canva:thumbnail\"\n    \
  \  }\n    },\n\n    \"AutofillJob\": {\n      \"@id\": \"canva:AutofillJob\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"status\": \"canva:jobStatus\",\n        \"result\": \"canva:jobResult\",\n        \"error\": \"canva:error\"\n      }\n    },\n\n    \"ResizeJob\": {\n      \"@id\": \"canva:ResizeJob\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"status\": \"canva:jobStatus\",\n        \"result\": \"canva:jobResult\",\n        \"error\": \"canva:error\"\n      }\n    },\n\n    \"Owner\": {\n      \"@id\": \"canva:Owner\",\n      \"@context\": {\n        \"user_id\": \"canva:userId\",\n        \"team_id\": \"canva:teamId\"\n      }\n    },\n\n    \"TeamUser\": {\n      \"@id\": \"canva:TeamUser\",\n      \"@context\": {\n        \"user_id\": \"canva:userId\",\n        \"team_id\": \"canva:teamId\"\n      }\n    },\n\n    \"Thumbnail\": {\n      \"@id\": \"canva:Thumbnail\",\n      \"@context\": {\n        \"width\": \"schema:width\",\n        \"height\"\
  : \"schema:height\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"DatasetField\": {\n      \"@id\": \"canva:DatasetField\",\n      \"@context\": {\n        \"type\": \"canva:fieldType\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/canva/refs/heads/main/json-ld/canva-context.jsonld
tags:
- Apps
- Automation
- Brand Management
- Collaboration
- Design
- Graphics
- Marketing
- Print
- Templates
- Visual Content
- JSON-LD
- Linked Data
- Semantic Web
---
