---
api_specs:
- filename: debian-sources-api-openapi.yml
  format: yaml
  label: Debian Sources API
  slug: debian-sources-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/openapi/debian-sources-api-openapi.yml
- filename: debian-bts-api-openapi.yml
  format: yaml
  label: Debian Bug Tracking System
  slug: debian-bts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/openapi/debian-bts-api-openapi.yml
- filename: debian-udd-api-openapi.yml
  format: yaml
  label: Debian Ultimate Database (UDD)
  slug: debian-udd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/openapi/debian-udd-api-openapi.yml
class_count: 3
classes:
- Package
- Bug
- Maintainer
context_file: json-ld/debian-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/json-ld/debian-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Debian from Debian.
layout: jsonld
name: Debian Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: debian
  uri: https://schema.debian.org/
properties:
- container: ''
  name: package
  type: schema:Text
- container: ''
  name: version
  type: schema:Text
- container: ''
  name: maintainer
  type: ''
- container: ''
  name: section
  type: schema:Text
- container: ''
  name: priority
  type: schema:Text
- container: ''
  name: homepage
  type: schema:URL
- container: ''
  name: id
  type: ''
- container: ''
  name: subject
  type: schema:Text
- container: ''
  name: severity
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: submitter
  type: ''
- container: ''
  name: date
  type: schema:DateTime
property_count: 12
provider_name: Debian
provider_slug: debian
slug: debian-context
source_filename: debian-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.debian.org/\",\n    \"schema\": \"https://schema.org/\",\n    \"debian\": \"https://schema.debian.org/\",\n    \"Package\": \"schema:SoftwareApplication\",\n    \"Bug\": \"debian:Bug\",\n    \"Maintainer\": \"schema:Person\",\n    \"package\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"version\": {\"@id\": \"schema:softwareVersion\", \"@type\": \"schema:Text\"},\n    \"maintainer\": {\"@id\": \"schema:maintainer\"},\n    \"section\": {\"@id\": \"schema:applicationCategory\", \"@type\": \"schema:Text\"},\n    \"priority\": {\"@id\": \"debian:priority\", \"@type\": \"schema:Text\"},\n    \"homepage\": {\"@id\": \"schema:url\", \"@type\": \"schema:URL\"},\n    \"id\": {\"@id\": \"schema:identifier\"},\n    \"subject\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"severity\": {\"@id\": \"debian:severity\", \"@type\": \"schema:Text\"},\n    \"status\": {\"@id\": \"\
  debian:status\", \"@type\": \"schema:Text\"},\n    \"submitter\": {\"@id\": \"schema:author\"},\n    \"date\": {\"@id\": \"schema:dateCreated\", \"@type\": \"schema:DateTime\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/json-ld/debian-context.jsonld
tags:
- Bug Tracker
- Debian
- Linux
- Open Source
- Operating System
- Package Management
- Source Code
- JSON-LD
- Linked Data
- Semantic Web
---
