---
api_specs:
- filename: svn-webdav-openapi.yml
  format: yaml
  label: SVN WebDAV HTTP API
  slug: svn-webdav-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/openapi/svn-webdav-openapi.yml
class_count: 0
classes: []
context_file: json-ld/svn-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/json-ld/svn-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Svn from Subversion.
layout: jsonld
name: Svn Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: svn
  uri: https://api-evangelist.github.io/svn/vocab#
properties:
- container: ''
  name: Repository
  type: reference
- container: ''
  name: Commit
  type: reference
- container: ''
  name: WorkingCopy
  type: reference
- container: ''
  name: Branch
  type: reference
- container: ''
  name: Tag
  type: reference
- container: ''
  name: Revision
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: author
  type: reference
- container: ''
  name: identifier
  type: ''
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: programmingLanguage
  type: ''
- container: ''
  name: license
  type: reference
- container: ''
  name: uuid
  type: ''
- container: ''
  name: revision
  type: ''
- container: ''
  name: headRevision
  type: ''
- container: ''
  name: commitMessage
  type: ''
- container: list
  name: changedPaths
  type: ''
- container: ''
  name: copyFromPath
  type: ''
- container: ''
  name: copyFromRevision
  type: ''
- container: ''
  name: lockToken
  type: ''
- container: ''
  name: lockOwner
  type: ''
- container: ''
  name: mergeInfo
  type: ''
property_count: 26
provider_name: Subversion
provider_slug: svn
slug: svn-context
source_filename: svn-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"svn\": \"https://api-evangelist.github.io/svn/vocab#\",\n\n    \"Repository\": {\n      \"@id\": \"svn:Repository\",\n      \"@type\": \"@id\"\n    },\n    \"Commit\": {\n      \"@id\": \"svn:Commit\",\n      \"@type\": \"@id\"\n    },\n    \"WorkingCopy\": {\n      \"@id\": \"svn:WorkingCopy\",\n      \"@type\": \"@id\"\n    },\n    \"Branch\": {\n      \"@id\": \"svn:Branch\",\n      \"@type\": \"@id\"\n    },\n    \"Tag\": {\n      \"@id\": \"svn:Tag\",\n      \"@type\": \"@id\"\n    },\n    \"Revision\": {\n      \"@id\": \"svn:Revision\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"dateCreated\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"dateModified\": { \"@id\": \"schema:dateModified\"\
  , \"@type\": \"xsd:dateTime\" },\n    \"author\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n    \"identifier\": { \"@id\": \"schema:identifier\" },\n    \"codeRepository\": { \"@id\": \"schema:codeRepository\", \"@type\": \"@id\" },\n    \"programmingLanguage\": { \"@id\": \"schema:programmingLanguage\" },\n    \"license\": { \"@id\": \"schema:license\", \"@type\": \"@id\" },\n\n    \"uuid\": { \"@id\": \"svn:uuid\" },\n    \"revision\": { \"@id\": \"svn:revision\" },\n    \"headRevision\": { \"@id\": \"svn:headRevision\" },\n    \"commitMessage\": { \"@id\": \"svn:commitMessage\" },\n    \"changedPaths\": { \"@id\": \"svn:changedPaths\", \"@container\": \"@list\" },\n    \"copyFromPath\": { \"@id\": \"svn:copyFromPath\" },\n    \"copyFromRevision\": { \"@id\": \"svn:copyFromRevision\" },\n    \"lockToken\": { \"@id\": \"svn:lockToken\" },\n    \"lockOwner\": { \"@id\": \"svn:lockOwner\" },\n    \"mergeInfo\": { \"@id\": \"svn:mergeInfo\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/json-ld/svn-context.jsonld
tags:
- Apache
- Open Source
- Repository
- Source Control
- Svn
- Version Control
- Webdav
- JSON-LD
- Linked Data
- Semantic Web
---
