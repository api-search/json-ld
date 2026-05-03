---
api_specs:
- filename: salesforce-knowledge-management-rest-api-openapi.yml
  format: yaml
  label: Salesforce Knowledge REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-knowledge-management/refs/heads/main/openapi/salesforce-knowledge-management-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforce-knowledge-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-knowledge-management/refs/heads/main/json-ld/salesforce-knowledge-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Knowledge Management from Salesforce Knowledge Management.
layout: jsonld
name: Salesforce Knowledge Management Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: KnowledgeArticle
  type: reference
- container: ''
  name: Title
  type: string
- container: ''
  name: Summary
  type: string
- container: ''
  name: UrlName
  type: string
- container: ''
  name: PublishStatus
  type: string
- container: ''
  name: Language
  type: string
- container: ''
  name: VersionNumber
  type: integer
- container: ''
  name: LastPublishedDate
  type: dateTime
- container: ''
  name: CreatedDate
  type: dateTime
- container: ''
  name: LastModifiedDate
  type: dateTime
- container: ''
  name: CreatedById
  type: string
- container: ''
  name: OwnerId
  type: string
- container: ''
  name: DataCategory
  type: reference
- container: ''
  name: label
  type: string
- container: ''
  name: name
  type: string
- container: list
  name: childCategories
  type: ''
- container: ''
  name: articleBody
  type: string
- container: list
  name: categories
  type: ''
property_count: 18
provider_name: Salesforce Knowledge Management
provider_slug: salesforce-knowledge-management
slug: salesforce-knowledge-management-context
source_filename: salesforce-knowledge-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sf\": \"https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KnowledgeArticle\": {\n      \"@id\": \"schema:Article\",\n      \"@type\": \"@id\"\n    },\n    \"Title\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Summary\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UrlName\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublishStatus\": {\n      \"@id\": \"schema:creativeWorkStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Language\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VersionNumber\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"LastPublishedDate\": {\n      \"\
  @id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreatedById\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerId\": {\n      \"@id\": \"schema:accountablePerson\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataCategory\": {\n      \"@id\": \"schema:DefinedTerm\",\n      \"@type\": \"@id\"\n    },\n    \"label\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"childCategories\": {\n      \"@id\": \"schema:hasPart\",\n      \"@container\": \"@list\"\n    },\n    \"articleBody\": {\n      \"@id\": \"schema:articleBody\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"categories\": {\n      \"@id\": \"schema:about\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-knowledge-management/refs/heads/main/json-ld/salesforce-knowledge-management-context.jsonld
tags:
- Articles
- CRM
- Customer Service
- Documentation
- Knowledge Management
- Support
- JSON-LD
- Linked Data
- Semantic Web
---
