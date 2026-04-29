---
class_count: 0
classes: []
context_file: json-ld/clickup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/json-ld/clickup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clickup from clickup.
layout: jsonld
name: Clickup Context
namespaces:
- prefix: clickup
  uri: https://developer.clickup.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Task
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: List
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Goal
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: TimeEntry
  type: ''
- container: ''
  name: View
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 11
provider_name: clickup
provider_slug: clickup
slug: clickup-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"clickup\": \"https://developer.clickup.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Task\": {\n      \"@id\": \"clickup:Task\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateClosed\": {\n          \"@id\": \"clickup:dateClosed\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dueDate\": {\n          \"@id\": \"clickup:dueDate\",\n          \"@type\": \"xsd:dateTime\"\n       \
  \ },\n        \"startDate\": {\n          \"@id\": \"clickup:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"clickup:status\",\n        \"priority\": \"clickup:priority\",\n        \"creator\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"assignees\": {\n          \"@id\": \"clickup:assignees\",\n          \"@container\": \"@set\"\n        },\n        \"watchers\": {\n          \"@id\": \"clickup:watchers\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"parent\": {\n          \"@id\": \"clickup:parentTask\",\n          \"@type\": \"@id\"\n        },\n        \"timeEstimate\": {\n          \"@id\": \"clickup:timeEstimate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timeSpent\": {\n          \"@id\": \"clickup:timeSpent\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"points\": {\n          \"@id\": \"clickup:sprintPoints\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"archived\": {\n          \"@id\": \"clickup:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"list\": {\n          \"@id\": \"clickup:list\",\n          \"@type\": \"@id\"\n        },\n        \"folder\": {\n          \"@id\": \"clickup:folder\",\n          \"@type\": \"@id\"\n        },\n        \"space\": {\n          \"@id\": \"clickup:space\",\n          \"@type\": \"@id\"\n        },\n        \"customFields\": {\n          \"@id\": \"clickup:customFields\",\n          \"@container\": \"@set\"\n        },\n        \"dependencies\": {\n          \"@id\": \"clickup:dependencies\",\n          \"@container\": \"@set\"\n        },\n        \"linkedTasks\": {\n          \"@id\": \"clickup:linkedTasks\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"clickup:Space\",\n  \
  \    \"@context\": {\n        \"name\": \"schema:name\",\n        \"private\": {\n          \"@id\": \"clickup:private\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"archived\": {\n          \"@id\": \"clickup:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"color\": \"clickup:color\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        },\n        \"statuses\": {\n          \"@id\": \"clickup:statuses\",\n          \"@container\": \"@list\"\n        },\n        \"features\": \"clickup:features\"\n      }\n    },\n\n    \"List\": {\n      \"@id\": \"clickup:List\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"content\": \"schema:description\",\n        \"dueDate\": {\n          \"@id\": \"clickup:dueDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startDate\": {\n          \"@id\": \"clickup:startDate\",\n          \"@type\": \"xsd:dateTime\"\n\
  \        },\n        \"status\": \"clickup:status\",\n        \"priority\": \"clickup:priority\",\n        \"archived\": {\n          \"@id\": \"clickup:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"taskCount\": {\n          \"@id\": \"clickup:taskCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"folder\": {\n          \"@id\": \"clickup:folder\",\n          \"@type\": \"@id\"\n        },\n        \"space\": {\n          \"@id\": \"clickup:space\",\n          \"@type\": \"@id\"\n        },\n        \"statuses\": {\n          \"@id\": \"clickup:statuses\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"clickup:Folder\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"archived\": {\n          \"@id\": \"clickup:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hidden\": {\n          \"@id\": \"clickup:hidden\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"space\": {\n          \"@id\": \"clickup:space\",\n          \"@type\": \"@id\"\n        },\n        \"lists\": {\n          \"@id\": \"clickup:lists\",\n          \"@container\": \"@set\"\n        },\n        \"taskCount\": {\n          \"@id\": \"clickup:taskCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statuses\": {\n          \"@id\": \"clickup:statuses\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Goal\": {\n      \"@id\": \"clickup:Goal\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dueDate\": {\n          \"@id\": \"clickup:dueDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startDate\": {\n          \"@id\": \"clickup:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n    \
  \    \"color\": \"clickup:color\",\n        \"private\": {\n          \"@id\": \"clickup:private\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"archived\": {\n          \"@id\": \"clickup:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"percentCompleted\": {\n          \"@id\": \"clickup:percentCompleted\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"keyResults\": {\n          \"@id\": \"clickup:keyResults\",\n          \"@container\": \"@set\"\n        },\n        \"owners\": {\n          \"@id\": \"clickup:owners\",\n          \"@container\": \"@set\"\n        },\n        \"prettyUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"clickup:Comment\",\n      \"@context\": {\n        \"commentText\": \"schema:text\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n   \
  \     \"user\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"resolved\": {\n          \"@id\": \"clickup:resolved\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"assignee\": {\n          \"@id\": \"clickup:assignee\",\n          \"@type\": \"@id\"\n        },\n        \"reactions\": {\n          \"@id\": \"clickup:reactions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"clickup:Workspace\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"color\": \"clickup:color\",\n        \"avatar\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"clickup:User\",\n      \"@context\": {\n        \"username\": \"schema:name\",\n        \"email\": \"schema:email\"\
  ,\n        \"profilePicture\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"color\": \"clickup:color\",\n        \"initials\": \"clickup:initials\"\n      }\n    },\n\n    \"TimeEntry\": {\n      \"@id\": \"clickup:TimeEntry\",\n      \"@context\": {\n        \"description\": \"schema:description\",\n        \"start\": {\n          \"@id\": \"clickup:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end\": {\n          \"@id\": \"clickup:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"clickup:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"billable\": {\n          \"@id\": \"clickup:billable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"task\": {\n          \"@id\": \"clickup:task\",\n          \"@type\": \"@id\"\n        },\n        \"user\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\
  \n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"View\": {\n      \"@id\": \"clickup:View\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"clickup:viewType\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"creator\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"parent\": {\n          \"@id\": \"clickup:parent\",\n          \"@type\": \"@id\"\n        },\n        \"visibility\": \"clickup:visibility\",\n        \"protected\": {\n          \"@id\": \"clickup:protected\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"clickup:Webhook\",\n      \"@context\": {\n        \"endpoint\": {\n          \"@id\": \"clickup:endpoint\",\n          \"@type\": \"@id\"\n        },\n\
  \        \"events\": {\n          \"@id\": \"clickup:events\",\n          \"@container\": \"@set\"\n        },\n        \"status\": \"clickup:webhookStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/json-ld/clickup-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
