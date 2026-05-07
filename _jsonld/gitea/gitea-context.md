---
api_specs:
- filename: swagger.v1.json
  format: json
  label: Gitea REST API
  slug: gitea-rest-api
  spec_type: OpenAPI
  url: https://demo.gitea.com/swagger.v1.json
class_count: 0
classes: []
context_file: json-ld/gitea-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gitea/refs/heads/main/json-ld/gitea-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gitea from Gitea.
layout: jsonld
name: Gitea Context
namespaces:
- prefix: gitea
  uri: https://gitea.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
properties:
- container: ''
  name: Repository
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Issue
  type: ''
- container: ''
  name: PullRequest
  type: ''
- container: ''
  name: Branch
  type: ''
- container: ''
  name: Commit
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: Hook
  type: ''
- container: ''
  name: Package
  type: ''
- container: ''
  name: NotificationThread
  type: ''
- container: ''
  name: Label
  type: ''
- container: ''
  name: Milestone
  type: ''
property_count: 14
provider_name: Gitea
provider_slug: gitea
slug: gitea-context
source_filename: gitea-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gitea\": \"https://gitea.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n\n    \"Repository\": {\n      \"@id\": \"doap:GitRepository\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"fullName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"owner\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n        \"private\": \"gitea:private\",\n        \"fork\": \"gitea:fork\",\n        \"empty\": \"gitea:empty\",\n        \"htmlUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"sshUrl\": \"gitea:sshUrl\",\n        \"cloneUrl\": \"gitea:cloneUrl\",\n        \"defaultBranch\": \"gitea:defaultBranch\",\n   \
  \     \"starsCount\": \"gitea:starsCount\",\n        \"forksCount\": \"gitea:forksCount\",\n        \"watchersCount\": \"gitea:watchersCount\",\n        \"openIssuesCount\": \"gitea:openIssuesCount\",\n        \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" },\n        \"updatedAt\": { \"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"login\": \"gitea:login\",\n        \"username\": \"gitea:username\",\n        \"fullName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"avatarUrl\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n        \"isAdmin\": \"gitea:isAdmin\",\n        \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\"\
  ,\n        \"username\": \"gitea:username\",\n        \"fullName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"visibility\": \"gitea:visibility\",\n        \"avatarUrl\": { \"@id\": \"schema:image\", \"@type\": \"@id\" }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"permission\": \"gitea:permission\",\n        \"units\": \"gitea:units\"\n      }\n    },\n\n    \"Issue\": {\n      \"@id\": \"gitea:Issue\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"number\": \"gitea:number\",\n        \"title\": \"schema:headline\",\n        \"body\": \"schema:articleBody\",\n        \"state\": \"gitea:state\",\n        \"user\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n\
  \        \"labels\": \"gitea:labels\",\n        \"assignees\": \"gitea:assignees\",\n        \"milestone\": \"gitea:milestone\",\n        \"comments\": \"gitea:commentsCount\",\n        \"htmlUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" },\n        \"updatedAt\": { \"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"PullRequest\": {\n      \"@id\": \"gitea:PullRequest\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"number\": \"gitea:number\",\n        \"title\": \"schema:headline\",\n        \"body\": \"schema:articleBody\",\n        \"state\": \"gitea:state\",\n        \"head\": \"gitea:head\",\n        \"base\": \"gitea:base\",\n        \"mergeable\": \"gitea:mergeable\",\n        \"merged\": \"gitea:merged\",\n        \"mergedAt\": { \"@id\": \"gitea:mergedAt\", \"@type\": \"xsd:dateTime\" },\n        \"createdAt\": { \"@id\"\
  : \"dcterms:created\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"Branch\": {\n      \"@id\": \"gitea:Branch\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"commit\": \"gitea:commit\",\n        \"protected\": \"gitea:protected\"\n      }\n    },\n\n    \"Commit\": {\n      \"@id\": \"gitea:Commit\",\n      \"@context\": {\n        \"sha\": \"gitea:sha\",\n        \"message\": \"schema:text\",\n        \"author\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n        \"committer\": { \"@id\": \"schema:contributor\", \"@type\": \"@id\" },\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" }\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"gitea:Release\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"tagName\": \"gitea:tagName\",\n        \"name\": \"schema:name\",\n        \"body\": \"schema:description\",\n        \"draft\": \"gitea:draft\",\n        \"prerelease\": \"gitea:prerelease\",\n   \
  \     \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" },\n        \"publishedAt\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"Hook\": {\n      \"@id\": \"gitea:Webhook\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"type\": \"gitea:hookType\",\n        \"config\": \"gitea:config\",\n        \"events\": \"gitea:events\",\n        \"active\": \"gitea:active\",\n        \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"gitea:Package\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"owner\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n        \"type\": \"gitea:packageType\",\n        \"name\": \"schema:name\",\n        \"version\": \"gitea:version\",\n        \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"NotificationThread\"\
  : {\n      \"@id\": \"gitea:NotificationThread\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"unread\": \"gitea:unread\",\n        \"subject\": \"gitea:subject\",\n        \"repository\": \"gitea:repository\",\n        \"updatedAt\": { \"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n\n    \"Label\": {\n      \"@id\": \"gitea:Label\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"color\": \"gitea:color\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Milestone\": {\n      \"@id\": \"gitea:Milestone\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"state\": \"gitea:state\",\n        \"dueOn\": { \"@id\": \"schema:expires\", \"@type\": \"xsd:dateTime\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gitea/refs/heads/main/json-ld/gitea-context.jsonld
tags:
- Git
- Source Control
- DevOps
- CI/CD
- Code Hosting
- Open Source
- Self Hosted
- Package Registry
- Issue Tracking
- Pull Requests
- JSON-LD
- Linked Data
- Semantic Web
---
