---
api_specs:
- filename: intralinks-api-openapi.yml
  format: yaml
  label: Intralinks API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/intralinks/refs/heads/main/openapi/intralinks-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/intralinks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/intralinks/refs/heads/main/json-ld/intralinks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Intralinks from Intralinks.
layout: jsonld
name: Intralinks Context
namespaces:
- prefix: intralinks
  uri: https://developers.intralinks.com/schema/
properties:
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: Splash
  type: ''
- container: ''
  name: CustomField
  type: ''
property_count: 8
provider_name: Intralinks
provider_slug: intralinks
slug: intralinks-context
source_filename: intralinks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"intralinks\": \"https://developers.intralinks.com/schema/\",\n    \"Workspace\": {\n      \"@id\": \"intralinks:Workspace\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"phase\": \"intralinks:phase\",\n        \"status\": \"intralinks:status\",\n        \"host\": \"schema:provider\",\n        \"createdOn\": \"schema:dateCreated\",\n        \"updatedOn\": \"schema:dateModified\",\n        \"statistics\": \"intralinks:statistics\"\n      }\n    },\n    \"Document\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"folderId\": \"schema:isPartOf\",\n        \"fileSize\": \"schema:contentSize\",\n        \"extension\": \"schema:encodingFormat\",\n        \"version\": \"schema:version\",\n        \"note\": \"schema:description\"\
  ,\n        \"createdBy\": \"schema:creator\",\n        \"createdOn\": \"schema:dateCreated\",\n        \"updatedOn\": \"schema:dateModified\",\n        \"lastAccessedOn\": \"intralinks:lastAccessedOn\"\n      }\n    },\n    \"Folder\": {\n      \"@id\": \"intralinks:Folder\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"parentId\": \"schema:isPartOf\",\n        \"indexNumber\": \"schema:position\",\n        \"hasChildFolders\": \"intralinks:hasChildFolders\",\n        \"version\": \"schema:version\",\n        \"createdOn\": \"schema:dateCreated\",\n        \"updatedOn\": \"schema:dateModified\"\n      }\n    },\n    \"Group\": {\n      \"@id\": \"intralinks:Group\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"note\": \"schema:description\",\n        \"memberCount\": \"intralinks:memberCount\",\n        \"foldersWithAccess\": \"intralinks:foldersWithAccess\"\
  ,\n        \"createdOn\": \"schema:dateCreated\",\n        \"updatedOn\": \"schema:dateModified\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"emailId\": \"schema:email\",\n        \"organization\": \"schema:memberOf\",\n        \"roleType\": \"intralinks:roleType\",\n        \"lastAccessedOn\": \"intralinks:lastAccessedOn\",\n        \"createdOn\": \"schema:dateCreated\"\n      }\n    },\n    \"Permission\": {\n      \"@id\": \"intralinks:Permission\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"groupId\": \"intralinks:groupId\",\n        \"folderId\": \"intralinks:folderId\",\n        \"permission\": \"intralinks:permissionLevel\"\n      }\n    },\n    \"Splash\": {\n      \"@id\": \"intralinks:Splash\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"hasAcceptButton\": \"intralinks:hasAcceptButton\"\
  ,\n        \"splashText\": \"schema:text\",\n        \"hasImage\": \"intralinks:hasImage\"\n      }\n    },\n    \"CustomField\": {\n      \"@id\": \"intralinks:CustomField\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"isRequired\": \"intralinks:isRequired\",\n        \"options\": \"intralinks:options\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/intralinks/refs/heads/main/json-ld/intralinks-context.jsonld
tags:
- Document Management
- Secure File Sharing
- Virtual Data Room
- JSON-LD
- Linked Data
- Semantic Web
---
