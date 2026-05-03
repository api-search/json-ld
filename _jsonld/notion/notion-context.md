---
api_specs:
- filename: notion-openapi.yml
  format: yaml
  label: Notion API
  slug: notion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/notion/refs/heads/main/openapi/notion-openapi.yml
class_count: 0
classes: []
context_file: json-ld/notion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/notion/refs/heads/main/json-ld/notion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Notion from Notion.
layout: jsonld
name: Notion Context
namespaces:
- prefix: notion
  uri: https://api.notion.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Page
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Block
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: RichText
  type: ''
- container: ''
  name: Parent
  type: ''
- container: ''
  name: PropertySchema
  type: ''
- container: ''
  name: Emoji
  type: ''
- container: ''
  name: File
  type: ''
- container: ''
  name: PaginatedList
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 12
provider_name: Notion
provider_slug: notion
slug: notion-context
source_filename: notion-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://api.notion.com/v1/\",\n    \"notion\": \"https://api.notion.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Page\": {\n      \"@id\": \"notion:Page\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_edited_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_by\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"last_edited_by\": {\n          \"\
  @id\": \"notion:lastEditedBy\",\n          \"@type\": \"@id\"\n        },\n        \"archived\": {\n          \"@id\": \"notion:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"in_trash\": {\n          \"@id\": \"notion:inTrash\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"icon\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"cover\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"properties\": {\n          \"@id\": \"notion:properties\",\n          \"@container\": \"@index\"\n        },\n        \"parent\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"public_url\": {\n          \"@id\": \"notion:publicUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"\
  notion:Database\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_edited_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_by\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"last_edited_by\": {\n          \"@id\": \"notion:lastEditedBy\",\n          \"@type\": \"@id\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"icon\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n \
  \       \"cover\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"properties\": {\n          \"@id\": \"notion:properties\",\n          \"@container\": \"@index\"\n        },\n        \"parent\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"public_url\": {\n          \"@id\": \"notion:publicUrl\",\n          \"@type\": \"@id\"\n        },\n        \"archived\": {\n          \"@id\": \"notion:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"in_trash\": {\n          \"@id\": \"notion:inTrash\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"is_inline\": {\n          \"@id\": \"notion:isInline\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Block\": {\n      \"@id\": \"notion:Block\",\n      \"@context\": {\n        \"object\": {\n\
  \          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"notion:blockType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_edited_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_by\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"last_edited_by\": {\n          \"@id\": \"notion:lastEditedBy\",\n          \"@type\": \"@id\"\n        },\n        \"parent\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"archived\": {\n          \"@id\": \"notion:archived\",\n          \"@type\": \"xsd:boolean\"\n\
  \        },\n        \"in_trash\": {\n          \"@id\": \"notion:inTrash\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"has_children\": {\n          \"@id\": \"notion:hasChildren\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"notion:User\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"notion:userType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"avatar_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"person\": {\n          \"@id\": \"notion:person\"\n        },\n        \"bot\": {\n          \"@id\"\
  : \"notion:bot\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"notion:Comment\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"discussion_id\": {\n          \"@id\": \"notion:discussionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_edited_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_by\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"rich_text\": {\n          \"@id\": \"notion:richText\"\
  \n        }\n      }\n    },\n\n    \"RichText\": {\n      \"@id\": \"notion:RichText\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"notion:richTextType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"plain_text\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"href\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"annotations\": {\n          \"@id\": \"notion:annotations\"\n        }\n      }\n    },\n\n    \"Parent\": {\n      \"@id\": \"notion:Parent\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"notion:parentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"database_id\": {\n          \"@id\": \"notion:databaseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"page_id\": {\n          \"@id\": \"notion:pageId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"block_id\": {\n          \"\
  @id\": \"notion:blockId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workspace\": {\n          \"@id\": \"notion:workspace\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"PropertySchema\": {\n      \"@id\": \"notion:PropertySchema\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"notion:propertyType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Emoji\": {\n      \"@id\": \"notion:Emoji\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"notion:iconType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emoji\": {\n          \"@id\": \"notion:emojiCharacter\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"File\": {\n   \
  \   \"@id\": \"notion:File\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"notion:fileHosting\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PaginatedList\": {\n      \"@id\": \"notion:PaginatedList\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": {\n          \"@id\": \"schema:itemListElement\",\n          \"@container\": \"@list\"\n        },\n        \"next_cursor\": {\n          \"@id\": \"notion:nextCursor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"has_more\": {\n          \"@id\": \"notion:hasMore\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"type\": {\n          \"@id\": \"notion:resultType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Error\"\
  : {\n      \"@id\": \"notion:Error\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"notion:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"notion:httpStatus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"code\": {\n          \"@id\": \"notion:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/notion/refs/heads/main/json-ld/notion-context.jsonld
tags:
- Collaboration
- Database
- Ideas
- Notes
- Productivity
- Projects
- T1
- Tasks
- Wiki
- Workspace
- JSON-LD
- Linked Data
- Semantic Web
---
