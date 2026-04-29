---
api_specs:
- filename: jira-cloud-platform-rest-api-openapi.yml
  format: yaml
  label: Jira Cloud Platform REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jira/refs/heads/main/openapi/jira-cloud-platform-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/jira-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jira/refs/heads/main/json-ld/jira-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jira from Jira.
layout: jsonld
name: Jira Context
namespaces:
- prefix: jira
  uri: https://developer.atlassian.com/cloud/jira/platform/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Issue
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: IssueType
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: Priority
  type: ''
- container: ''
  name: Resolution
  type: ''
- container: ''
  name: Component
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: Worklog
  type: ''
- container: ''
  name: Sprint
  type: ''
- container: ''
  name: Board
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 15
provider_name: Jira
provider_slug: jira
slug: jira-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"jira\": \"https://developer.atlassian.com/cloud/jira/platform/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Issue\": {\n      \"@id\": \"jira:Issue\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"summary\": \"schema:name\",\n        \"description\": \"schema:text\",\n        \"status\": \"jira:status\",\n        \"priority\": \"jira:priority\",\n        \"resolution\": \"jira:resolution\",\n        \"self\": {\n          \"@id\": \"jira:apiUrl\",\n          \"@type\": \"@id\"\n        },\n        \"assignee\": {\n          \"@id\": \"jira:assignee\",\n          \"@type\": \"@id\"\n        },\n        \"reporter\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"creator\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\":\
  \ \"@id\"\n        },\n        \"labels\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"components\": {\n          \"@id\": \"jira:components\",\n          \"@container\": \"@set\"\n        },\n        \"fixVersions\": {\n          \"@id\": \"jira:fixVersions\",\n          \"@container\": \"@set\"\n        },\n        \"versions\": {\n          \"@id\": \"jira:affectedVersions\",\n          \"@container\": \"@set\"\n        },\n        \"subtasks\": {\n          \"@id\": \"jira:subtasks\",\n          \"@container\": \"@set\"\n        },\n        \"parent\": {\n          \"@id\": \"jira:parentIssue\",\n          \"@type\": \"@id\"\n        },\n        \"issuelinks\": {\n          \"@id\": \"jira:issueLinks\",\n          \"@container\": \"@set\"\n        },\n        \"comment\": \"schema:commentCount\",\n        \"watches\": \"jira:watchCount\",\n        \"votes\": \"jira:voteCount\",\n        \"duedate\": {\n          \"@id\": \"\
  jira:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolutiondate\": {\n          \"@id\": \"jira:resolutionDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"jira:Project\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"self\": {\n          \"@id\": \"jira:apiUrl\",\n          \"@type\": \"@id\"\n        },\n        \"lead\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"@id\"\n        },\n        \"projectTypeKey\": \"jira:projectType\",\n\
  \        \"simplified\": \"jira:isSimplified\",\n        \"style\": \"jira:projectStyle\",\n        \"archived\": \"jira:isArchived\",\n        \"deleted\": \"jira:isDeleted\",\n        \"assigneeType\": \"jira:defaultAssigneeType\",\n        \"components\": {\n          \"@id\": \"jira:components\",\n          \"@container\": \"@set\"\n        },\n        \"issueTypes\": {\n          \"@id\": \"jira:issueTypes\",\n          \"@container\": \"@set\"\n        },\n        \"versions\": {\n          \"@id\": \"jira:versions\",\n          \"@container\": \"@set\"\n        },\n        \"roles\": \"jira:roles\",\n        \"projectCategory\": \"jira:projectCategory\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"jira:User\",\n      \"@context\": {\n        \"accountId\": \"schema:identifier\",\n        \"displayName\": \"schema:name\",\n        \"emailAddress\": \"schema:email\",\n        \"self\": {\n          \"@id\": \"jira:apiUrl\",\n          \"@type\": \"@id\"\n        },\n    \
  \    \"avatarUrls\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"active\": \"jira:isActive\",\n        \"timeZone\": \"jira:timeZone\",\n        \"accountType\": \"jira:accountType\"\n      }\n    },\n\n    \"IssueType\": {\n      \"@id\": \"jira:IssueType\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"iconUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"subtask\": \"jira:isSubtask\",\n        \"hierarchyLevel\": \"jira:hierarchyLevel\"\n      }\n    },\n\n    \"Status\": {\n      \"@id\": \"jira:Status\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"statusCategory\": \"jira:statusCategory\",\n        \"iconUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Priority\": {\n    \
  \  \"@id\": \"jira:Priority\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"iconUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"statusColor\": \"jira:statusColor\"\n      }\n    },\n\n    \"Resolution\": {\n      \"@id\": \"jira:Resolution\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Component\": {\n      \"@id\": \"jira:Component\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"lead\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Version\": {\n      \"@id\": \"jira:Version\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"archived\": \"jira:isArchived\",\n   \
  \     \"released\": \"jira:isReleased\",\n        \"releaseDate\": {\n          \"@id\": \"jira:releaseDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"startDate\": {\n          \"@id\": \"jira:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"overdue\": \"jira:isOverdue\"\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"jira:Comment\",\n      \"@context\": {\n        \"body\": \"schema:text\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"updateAuthor\": {\n          \"@id\": \"jira:updateAuthor\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"visibility\": \"jira:visibility\"\n      }\n    },\n\n    \"Attachment\": {\n      \"@id\": \"\
  jira:Attachment\",\n      \"@context\": {\n        \"filename\": \"schema:name\",\n        \"mimeType\": \"schema:encodingFormat\",\n        \"size\": \"schema:contentSize\",\n        \"content\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"thumbnail\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Worklog\": {\n      \"@id\": \"jira:Worklog\",\n      \"@context\": {\n        \"timeSpent\": \"jira:timeSpent\",\n        \"timeSpentSeconds\": \"jira:timeSpentSeconds\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"started\": {\n          \"@id\": \"jira:started\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Sprint\": {\n      \"@id\": \"jira:Sprint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"jira:sprintState\",\n        \"goal\": \"schema:description\",\n        \"startDate\": {\n          \"@id\": \"jira:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDate\": {\n          \"@id\": \"jira:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completeDate\": {\n          \"@id\": \"jira:completeDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"originBoardId\": \"jira:originBoardId\"\n      }\n    },\n\n    \"Board\": {\n      \"@id\": \"jira:Board\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"type\": \"jira:boardType\",\n        \"self\": {\n          \"@id\": \"jira:apiUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"jira:WebhookEvent\",\n      \"@context\": {\n        \"webhookEvent\": \"jira:eventType\",\n        \"timestamp\": {\n          \"@id\": \"jira:timestamp\",\n          \"@type\": \"xsd:long\"\n        },\n        \"user\": {\n          \"@id\": \"jira:actor\",\n          \"@type\": \"@id\"\n        },\n        \"issue\": {\n          \"@id\": \"jira:issue\",\n          \"@type\": \"@id\"\n        },\n        \"project\": {\n          \"@id\": \"jira:project\",\n          \"@type\": \"@id\"\n        },\n        \"changelog\": \"jira:changelog\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jira/refs/heads/main/json-ld/jira-context.jsonld
tags:
- Agile
- Issue Tracking
- ITSM
- Project Management
- Service Management
- JSON-LD
- Linked Data
- Semantic Web
---
