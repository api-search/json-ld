---
api_specs:
- filename: ubuntu-launchpad-openapi.yml
  format: yaml
  label: Launchpad API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/openapi/ubuntu-launchpad-openapi.yml
- filename: ubuntu-snap-store-openapi.yml
  format: yaml
  label: Snap Store API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/openapi/ubuntu-snap-store-openapi.yml
- filename: ubuntu-cve-openapi.yml
  format: yaml
  label: Ubuntu CVE API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/openapi/ubuntu-cve-openapi.yml
class_count: 8
classes:
- Snap
- Channel
- Vulnerability
- SecurityNotice
- Bug
- Project
- Person
- Distribution
context_file: json-ld/ubuntu-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/json-ld/ubuntu-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ubuntu from Ubuntu.
layout: jsonld
name: Ubuntu Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ubuntu
  uri: https://ubuntu.com/vocab/
- prefix: snap
  uri: https://snapcraft.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: publisher
  type: reference
- container: ''
  name: license
  type: string
- container: ''
  name: snap-id
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: released-at
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: cvss3
  type: double
- container: ''
  name: status
  type: string
- container: ''
  name: published
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: display_name
  type: string
- container: ''
  name: web_link
  type: reference
- container: ''
  name: self_link
  type: reference
property_count: 18
provider_name: Ubuntu
provider_slug: ubuntu
slug: ubuntu-context
source_filename: ubuntu-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ubuntu\": \"https://ubuntu.com/vocab/\",\n    \"snap\": \"https://snapcraft.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Snap\": \"snap:Snap\",\n    \"Channel\": \"snap:Channel\",\n    \"Vulnerability\": \"schema:SecurityVulnerability\",\n    \"SecurityNotice\": \"ubuntu:SecurityNotice\",\n    \"Bug\": \"schema:BugReport\",\n    \"Project\": \"schema:SoftwareSourceCode\",\n    \"Person\": \"schema:Person\",\n    \"Distribution\": \"ubuntu:Distribution\",\n\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"title\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"summary\": { \"@id\": \"schema:abstract\", \"@type\": \"xsd:string\" },\n    \"publisher\": { \"@id\": \"schema:publisher\", \"@type\": \"@id\" },\n    \"license\":\
  \ { \"@id\": \"schema:license\", \"@type\": \"xsd:string\" },\n\n    \"snap-id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"version\": { \"@id\": \"schema:softwareVersion\", \"@type\": \"xsd:string\" },\n    \"released-at\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"priority\": { \"@id\": \"ubuntu:priority\", \"@type\": \"xsd:string\" },\n    \"cvss3\": { \"@id\": \"ubuntu:cvssScore\", \"@type\": \"xsd:double\" },\n    \"status\": { \"@id\": \"schema:status\", \"@type\": \"xsd:string\" },\n    \"published\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n    \"updated_at\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n\n    \"display_name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"web_link\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"self_link\": { \"@id\": \"schema:identifier\"\
  , \"@type\": \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/json-ld/ubuntu-context.jsonld
tags:
- Cloud
- Containers
- Devops
- Enterprise
- Linux
- Security
- Ubuntu
- Package Management
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
