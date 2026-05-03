---
api_specs:
- filename: sourceforge-allura-openapi.yml
  format: yaml
  label: SourceForge Allura API
  slug: sourceforge-allura-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/openapi/sourceforge-allura-openapi.yml
class_count: 6
classes:
- Project
- Ticket
- WikiPage
- BlogPost
- Webhook
- id
context_file: json-ld/sourceforge-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/json-ld/sourceforge-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sourceforge from SourceForge.
layout: jsonld
name: Sourceforge Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: shortname
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: ticket_num
  type: integer
- container: ''
  name: summary
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: assigned_to
  type: string
- container: set
  name: labels
  type: ''
- container: ''
  name: created_date
  type: dateTime
- container: ''
  name: mod_date
  type: dateTime
property_count: 12
provider_name: SourceForge
provider_slug: sourceforge
slug: sourceforge-context
source_filename: sourceforge-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": \"doap:Project\",\n    \"Ticket\": \"schema:BugReport\",\n    \"WikiPage\": \"schema:WebPage\",\n    \"BlogPost\": \"schema:BlogPosting\",\n    \"Webhook\": \"schema:EntryPoint\",\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortname\": {\n      \"@id\": \"doap:shortdesc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ticket_num\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"summary\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assigned_to\": {\n      \"@id\": \"schema:assignee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"created_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mod_date\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/json-ld/sourceforge-context.jsonld
tags:
- Open Source
- Developer Tools
- Project Management
- Code Hosting
- Collaboration
- JSON-LD
- Linked Data
- Semantic Web
---
