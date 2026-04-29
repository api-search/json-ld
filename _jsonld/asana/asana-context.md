---
class_count: 0
classes: []
context_file: json-ld/asana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/asana/refs/heads/main/json-ld/asana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Asana from Asana.
layout: jsonld
name: Asana Context
namespaces:
- prefix: asana
  uri: https://developers.asana.com/schemas/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: gid
  type: schema:Text
- container: ''
  name: resource_type
  type: schema:Text
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: Task
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Goal
  type: ''
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Section
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Attachment
  type: ''
property_count: 16
provider_name: Asana
provider_slug: asana
slug: asana-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developers.asana.com/schemas/\",\n    \"asana\": \"https://developers.asana.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"gid\": {\n      \"@id\": \"asana:gid\",\n      \"@type\": \"schema:Text\",\n      \"description\": \"Globally unique identifier of the Asana resource\"\n    },\n    \"resource_type\": {\n      \"@id\": \"asana:resource_type\",\n      \"@type\": \"schema:Text\",\n      \"description\": \"The base type of this Asana resource\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"schema:Text\"\n    },\n    \"Task\": {\n      \"@id\": \"asana:Task\",\n      \"@context\": {\n        \"assignee\": {\n          \"@id\": \"asana:assignee\",\n          \"@type\": \"@id\",\n          \"description\": \"The user to whom this task is assigned\"\n        },\n        \"completed\"\
  : {\n          \"@id\": \"asana:completed\",\n          \"@type\": \"schema:Boolean\",\n          \"description\": \"Whether the task is completed\"\n        },\n        \"completed_at\": {\n          \"@id\": \"asana:completed_at\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"modified_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"due_at\": {\n          \"@id\": \"asana:due_at\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"due_on\": {\n          \"@id\": \"asana:due_on\",\n          \"@type\": \"schema:Date\"\n        },\n        \"start_on\": {\n          \"@id\": \"asana:start_on\",\n          \"@type\": \"schema:Date\"\n        },\n        \"start_at\": {\n          \"@id\": \"asana:start_at\",\n          \"@type\": \"schema:DateTime\"\n        },\n\
  \        \"notes\": {\n          \"@id\": \"asana:notes\",\n          \"@type\": \"schema:Text\"\n        },\n        \"html_notes\": {\n          \"@id\": \"asana:html_notes\",\n          \"@type\": \"schema:Text\"\n        },\n        \"parent\": {\n          \"@id\": \"asana:parent\",\n          \"@type\": \"@id\"\n        },\n        \"projects\": {\n          \"@id\": \"asana:projects\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"asana:tags\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"followers\": {\n          \"@id\": \"asana:followers\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"workspace\": {\n          \"@id\": \"asana:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"permalink_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"schema:URL\"\n        }\n      }\n    },\n \
  \   \"Project\": {\n      \"@id\": \"asana:Project\",\n      \"@context\": {\n        \"archived\": {\n          \"@id\": \"asana:archived\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"color\": {\n          \"@id\": \"asana:color\",\n          \"@type\": \"schema:Text\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"modified_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"due_on\": {\n          \"@id\": \"asana:due_on\",\n          \"@type\": \"schema:Date\"\n        },\n        \"start_on\": {\n          \"@id\": \"asana:start_on\",\n          \"@type\": \"schema:Date\"\n        },\n        \"owner\": {\n          \"@id\": \"asana:owner\",\n          \"@type\": \"@id\"\n        },\n        \"team\": {\n          \"@id\": \"asana:team\",\n          \"@type\": \"@id\"\n        },\n        \"workspace\"\
  : {\n          \"@id\": \"asana:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"permalink_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"schema:URL\"\n        }\n      }\n    },\n    \"User\": {\n      \"@id\": \"asana:User\",\n      \"@context\": {\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"schema:Text\"\n        },\n        \"photo\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"workspaces\": {\n          \"@id\": \"asana:workspaces\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n    \"Workspace\": {\n      \"@id\": \"asana:Workspace\",\n      \"@context\": {\n        \"is_organization\": {\n          \"@id\": \"asana:is_organization\",\n          \"@type\": \"schema:Boolean\"\
  \n        },\n        \"email_domains\": {\n          \"@id\": \"asana:email_domains\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n    \"Team\": {\n      \"@id\": \"asana:Team\",\n      \"@context\": {\n        \"organization\": {\n          \"@id\": \"asana:organization\",\n          \"@type\": \"@id\"\n        },\n        \"permalink_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"schema:URL\"\n        }\n      }\n    },\n    \"Goal\": {\n      \"@id\": \"asana:Goal\",\n      \"@context\": {\n        \"owner\": {\n          \"@id\": \"asana:owner\",\n          \"@type\": \"@id\"\n        },\n        \"due_on\": {\n          \"@id\": \"asana:due_on\",\n          \"@type\": \"schema:Date\"\n        },\n        \"start_on\": {\n          \"@id\": \"asana:start_on\",\n          \"@type\": \"schema:Date\"\n        },\n        \"status\": {\n          \"@id\": \"asana:status\",\n          \"@type\": \"schema:Text\"\n        },\n        \"workspace\"\
  : {\n          \"@id\": \"asana:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"team\": {\n          \"@id\": \"asana:team\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Portfolio\": {\n      \"@id\": \"asana:Portfolio\",\n      \"@context\": {\n        \"owner\": {\n          \"@id\": \"asana:owner\",\n          \"@type\": \"@id\"\n        },\n        \"workspace\": {\n          \"@id\": \"asana:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"permalink_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"schema:URL\"\n        }\n      }\n    },\n    \"Webhook\": {\n      \"@id\": \"asana:Webhook\",\n      \"@context\": {\n        \"active\": {\n          \"@id\": \"asana:active\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"resource\": {\n          \"@id\"\
  : \"asana:resource\",\n          \"@type\": \"@id\"\n        },\n        \"target\": {\n          \"@id\": \"asana:target\",\n          \"@type\": \"schema:URL\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n    \"Event\": {\n      \"@id\": \"asana:Event\",\n      \"@context\": {\n        \"action\": {\n          \"@id\": \"asana:action\",\n          \"@type\": \"schema:Text\"\n        },\n        \"resource\": {\n          \"@id\": \"asana:resource\",\n          \"@type\": \"@id\"\n        },\n        \"user\": {\n          \"@id\": \"asana:user\",\n          \"@type\": \"@id\"\n        },\n        \"parent\": {\n          \"@id\": \"asana:parent\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n    \"Section\": {\n      \"@id\": \"asana:Section\"\
  ,\n      \"@context\": {\n        \"project\": {\n          \"@id\": \"asana:project\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"asana:Tag\",\n      \"@context\": {\n        \"color\": {\n          \"@id\": \"asana:color\",\n          \"@type\": \"schema:Text\"\n        },\n        \"workspace\": {\n          \"@id\": \"asana:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n    \"Attachment\": {\n      \"@id\": \"asana:Attachment\",\n      \"@context\": {\n        \"download_url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"schema:URL\"\n        },\n        \"host\": {\n          \"@id\": \"asana:host\",\n          \"@type\": \"schema:Text\"\n\
  \        },\n        \"parent\": {\n          \"@id\": \"asana:parent\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"schema:Integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/asana/refs/heads/main/json-ld/asana-context.jsonld
tags:
- Collaboration
- Productivity
- Project Management
- Projects
- Task Management
- Tasks
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
