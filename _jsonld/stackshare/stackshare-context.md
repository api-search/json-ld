---
class_count: 11
classes:
- techStack
- companyTools
- domain
- slug
- category
- followers
- sourcesSummary
- name
- description
- websiteUrl
- githubUrl
context_file: json-ld/stackshare-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stackshare/refs/heads/main/json-ld/stackshare-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stackshare from StackShare.
layout: jsonld
name: Stackshare Context
namespaces:
- prefix: stackshare
  uri: https://stackshare.io/schema/
properties:
- container: ''
  name: Tool
  type: reference
- container: ''
  name: Company
  type: reference
property_count: 2
provider_name: StackShare
provider_slug: stackshare
slug: stackshare-context
source_filename: stackshare-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stackshare\": \"https://stackshare.io/schema/\",\n    \"Tool\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"Company\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"techStack\": \"stackshare:techStack\",\n    \"companyTools\": \"stackshare:companyTools\",\n    \"domain\": \"schema:url\",\n    \"slug\": \"stackshare:slug\",\n    \"category\": \"stackshare:category\",\n    \"followers\": \"stackshare:followers\",\n    \"sourcesSummary\": \"stackshare:sourcesSummary\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"websiteUrl\": \"schema:url\",\n    \"githubUrl\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stackshare/refs/heads/main/json-ld/stackshare-context.jsonld
tags:
- Developer Tools
- Software Discovery
- Tech Stacks
- JSON-LD
- Linked Data
- Semantic Web
---
