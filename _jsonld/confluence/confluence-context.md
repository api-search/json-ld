---
api_specs:
- filename: swagger.v3.json
  format: json
  label: Confluence Cloud REST API v1
  slug: ''
  spec_type: OpenAPI
  url: https://dac-static.atlassian.com/cloud/confluence/swagger.v3.json
- filename: openapi.yaml
  format: yaml
  label: Confluence Cloud REST API v2
  slug: ''
  spec_type: OpenAPI
  url: https://developer.atlassian.com/cloud/confluence/rest/v2/api-spec/
class_count: 0
classes: []
context_file: json-ld/confluence-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/confluence/refs/heads/main/json-ld/confluence-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Confluence from Confluence.
layout: jsonld
name: Confluence Context
namespaces:
- prefix: confluence
  uri: https://developer.atlassian.com/cloud/confluence/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
- prefix: as
  uri: https://www.w3.org/ns/activitystreams#
properties:
- container: ''
  name: Page
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: BlogPost
  type: ''
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: Label
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: SpacePermission
  type: ''
property_count: 8
provider_name: Confluence
provider_slug: confluence
slug: confluence-context
source_filename: confluence-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://developer.atlassian.com/cloud/confluence/vocab#\",\n    \"confluence\": \"https://developer.atlassian.com/cloud/confluence/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n    \"as\": \"https://www.w3.org/ns/activitystreams#\",\n\n    \"Page\": {\n      \"@id\": \"confluence:Page\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:pageId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"confluence:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spaceId\": {\n          \"@id\": \"confluence:spaceId\",\n     \
  \     \"@type\": \"xsd:string\"\n        },\n        \"parentId\": {\n          \"@id\": \"confluence:parentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentType\": {\n          \"@id\": \"confluence:parentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"position\": {\n          \"@id\": \"confluence:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"authorId\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"confluence:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"body\": {\n          \"@id\": \"sioc:content\"\n        },\n        \"version\": {\n          \"@id\": \"confluence:version\"\n        },\n        \"labels\": {\n          \"@id\": \"confluence:labels\",\n          \"@container\": \"\
  @set\"\n        }\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"confluence:Space\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:spaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"key\": {\n          \"@id\": \"confluence:spaceKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"confluence:spaceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"confluence:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authorId\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"homepageId\": {\n          \"@id\": \"confluence:homepageId\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"icon\": {\n          \"@id\": \"schema:image\"\n        },\n        \"labels\": {\n          \"@id\": \"confluence:labels\",\n          \"@container\": \"@set\"\n        },\n        \"permissions\": {\n          \"@id\": \"confluence:permissions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"confluence:Comment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:commentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"confluence:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pageId\": {\n          \"@id\": \"confluence:pageId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blogPostId\"\
  : {\n          \"@id\": \"confluence:blogPostId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentCommentId\": {\n          \"@id\": \"confluence:parentCommentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authorId\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"body\": {\n          \"@id\": \"sioc:content\"\n        },\n        \"resolutionStatus\": {\n          \"@id\": \"confluence:resolutionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"confluence:version\"\n        }\n      }\n    },\n\n    \"BlogPost\": {\n      \"@id\": \"confluence:BlogPost\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:blogPostId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n        \
  \  \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"confluence:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spaceId\": {\n          \"@id\": \"confluence:spaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authorId\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"body\": {\n          \"@id\": \"sioc:content\"\n        },\n        \"labels\": {\n          \"@id\": \"confluence:labels\",\n          \"@container\": \"@set\"\n        },\n        \"version\": {\n          \"@id\": \"confluence:version\"\n        }\n      }\n    },\n\n    \"Attachment\": {\n      \"@id\": \"confluence:Attachment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:attachmentId\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"confluence:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mediaType\": {\n          \"@id\": \"dcterms:format\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileSize\": {\n          \"@id\": \"confluence:fileSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pageId\": {\n          \"@id\": \"confluence:pageId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blogPostId\": {\n          \"@id\": \"confluence:blogPostId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"downloadLink\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"version\": {\n          \"@id\": \"confluence:version\"\n        }\n      }\n    },\n\n    \"Label\": {\n      \"@id\": \"confluence:Label\",\n    \
  \  \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:labelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prefix\": {\n          \"@id\": \"confluence:labelPrefix\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Version\": {\n      \"@id\": \"confluence:Version\",\n      \"@context\": {\n        \"number\": {\n          \"@id\": \"confluence:versionNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"message\": {\n          \"@id\": \"confluence:versionMessage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minorEdit\": {\n          \"@id\": \"confluence:minorEdit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"authorId\": {\n          \"@id\": \"dcterms:creator\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SpacePermission\": {\n      \"@id\": \"confluence:SpacePermission\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"confluence:permissionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"principal\": {\n          \"@id\": \"confluence:principal\"\n        },\n        \"operation\": {\n          \"@id\": \"confluence:operation\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/confluence/refs/heads/main/json-ld/confluence-context.jsonld
tags:
- Collaboration
- Content Management
- Documentation
- Knowledge Base
- Wiki
- JSON-LD
- Linked Data
- Semantic Web
---
