---
class_count: 0
classes: []
context_file: json-ld/tableau-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tableau/refs/heads/main/json-ld/tableau-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tableau from Tableau.
layout: jsonld
name: Tableau Context
namespaces:
- prefix: tableau
  uri: https://help.tableau.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Site
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Workbook
  type: ''
- container: ''
  name: View
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Revision
  type: ''
- container: ''
  name: Permission
  type: ''
property_count: 14
provider_name: Tableau
provider_slug: tableau
slug: tableau-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tableau\": \"https://help.tableau.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Site\": {\n      \"@id\": \"tableau:Site\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"contentUrl\": \"tableau:contentUrl\",\n        \"adminMode\": \"tableau:adminMode\",\n        \"state\": \"tableau:state\",\n        \"storageQuota\": \"tableau:storageQuota\",\n        \"userQuota\": \"tableau:userQuota\",\n        \"numCreators\": \"tableau:numCreators\",\n        \"numExplorers\": \"tableau:numExplorers\",\n        \"numViewers\": \"tableau:numViewers\",\n        \"disableSubscriptions\": \"tableau:disableSubscriptions\",\n        \"revision\": \"schema:version\"\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"tableau:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n\
  \        \"description\": \"schema:description\",\n        \"parentProjectId\": {\n          \"@id\": \"tableau:parentProject\",\n          \"@type\": \"@id\"\n        },\n        \"contentPermissions\": \"tableau:contentPermissions\",\n        \"topLevelProject\": \"tableau:isTopLevelProject\",\n        \"owner\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Workbook\": {\n      \"@id\": \"tableau:Workbook\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"contentUrl\": \"tableau:contentUrl\",\n        \"webpageUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"showTabs\"\
  : \"tableau:showTabs\",\n        \"size\": \"schema:contentSize\",\n        \"project\": {\n          \"@id\": \"tableau:project\",\n          \"@type\": \"@id\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"@id\"\n        },\n        \"views\": {\n          \"@id\": \"tableau:views\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"connections\": {\n          \"@id\": \"tableau:connections\",\n          \"@container\": \"@set\"\n        },\n        \"defaultViewId\": \"tableau:defaultViewId\",\n        \"encryptExtracts\": \"tableau:encryptExtracts\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"View\"\
  : {\n      \"@id\": \"tableau:View\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"contentUrl\": \"tableau:contentUrl\",\n        \"viewUrlName\": \"tableau:viewUrlName\",\n        \"sheetType\": \"tableau:sheetType\",\n        \"workbook\": {\n          \"@id\": \"tableau:workbook\",\n          \"@type\": \"@id\"\n        },\n        \"project\": {\n          \"@id\": \"tableau:project\",\n          \"@type\": \"@id\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"totalViewCount\": \"schema:interactionCount\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSource\"\
  : {\n      \"@id\": \"tableau:DataSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"contentUrl\": \"tableau:contentUrl\",\n        \"type\": \"tableau:dataSourceType\",\n        \"isCertified\": \"tableau:isCertified\",\n        \"certificationNote\": \"tableau:certificationNote\",\n        \"hasExtracts\": \"tableau:hasExtracts\",\n        \"encryptExtracts\": \"tableau:encryptExtracts\",\n        \"useRemoteQueryAgent\": \"tableau:useRemoteQueryAgent\",\n        \"project\": {\n          \"@id\": \"tableau:project\",\n          \"@type\": \"@id\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"connections\": {\n          \"@id\": \"tableau:connections\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"tableau:User\",\n      \"@context\": {\n        \"name\": \"schema:alternateName\",\n        \"fullName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"siteRole\": \"tableau:siteRole\",\n        \"authSetting\": \"tableau:authSetting\",\n        \"locale\": \"tableau:locale\",\n        \"language\": \"tableau:language\",\n        \"externalAuthUserId\": \"tableau:externalAuthUserId\",\n        \"lastLogin\": {\n          \"@id\": \"tableau:lastLogin\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"tableau:Group\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"domainName\": \"tableau:domainName\",\n        \"minimumSiteRole\"\
  : \"tableau:minimumSiteRole\",\n        \"userCount\": \"tableau:userCount\"\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"tableau:Connection\",\n      \"@context\": {\n        \"type\": \"tableau:connectionType\",\n        \"serverAddress\": \"tableau:serverAddress\",\n        \"serverPort\": \"tableau:serverPort\",\n        \"userName\": \"tableau:userName\",\n        \"datasource\": {\n          \"@id\": \"tableau:datasource\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"tableau:Tag\",\n      \"@context\": {\n        \"label\": \"schema:name\"\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"tableau:Schedule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"tableau:state\",\n        \"priority\": \"tableau:priority\",\n        \"type\": \"tableau:scheduleType\",\n        \"frequency\": \"tableau:frequency\",\n        \"nextRunAt\": {\n          \"@id\": \"tableau:nextRunAt\",\n\
  \          \"@type\": \"xsd:dateTime\"\n        },\n        \"endScheduleAt\": {\n          \"@id\": \"tableau:endScheduleAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"tableau:Subscription\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"message\": \"schema:text\",\n        \"attachImage\": \"tableau:attachImage\",\n        \"attachPdf\": \"tableau:attachPdf\",\n        \"suspended\": \"tableau:isSuspended\",\n        \"content\": {\n          \"@id\": \"tableau:subscribedContent\",\n          \"@type\": \"@id\"\n        },\n        \"schedule\": {\n          \"@id\": \"tableau:schedule\",\n          \"@type\": \"@id\"\n        },\n        \"user\": {\n  \
  \        \"@id\": \"tableau:subscriber\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"tableau:Job\",\n      \"@context\": {\n        \"type\": \"tableau:jobType\",\n        \"mode\": \"tableau:jobMode\",\n        \"status\": \"tableau:jobStatus\",\n        \"progress\": \"tableau:progress\",\n        \"finishCode\": \"tableau:finishCode\",\n        \"title\": \"schema:name\",\n        \"subtitle\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startedAt\": {\n          \"@id\": \"tableau:startedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"tableau:endedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Revision\": {\n      \"@id\": \"tableau:Revision\",\n      \"@context\": {\n        \"revisionNumber\": \"schema:version\",\n        \"deleted\"\
  : \"tableau:isDeleted\",\n        \"current\": \"tableau:isCurrent\",\n        \"sizeInBytes\": \"schema:contentSize\",\n        \"publisher\": {\n          \"@id\": \"tableau:publisher\",\n          \"@type\": \"@id\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Permission\": {\n      \"@id\": \"tableau:Permission\",\n      \"@context\": {\n        \"granteeCapabilities\": {\n          \"@id\": \"tableau:granteeCapabilities\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tableau/refs/heads/main/json-ld/tableau-context.jsonld
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
