---
class_count: 3
classes:
- AllContributorsConfig
- Contributor
- AuthorEntry
context_file: json-ld/authors-md-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/json-ld/authors-md-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Authors Md from AUTHORS.md.
layout: jsonld
name: Authors Md Context
namespaces:
- prefix: authors
  uri: https://authors-md.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: spdx
  uri: http://spdx.org/rdf/terms#
properties:
- container: ''
  name: projectName
  type: string
- container: ''
  name: projectOwner
  type: string
- container: ''
  name: repoType
  type: string
- container: ''
  name: repoHost
  type: reference
- container: set
  name: files
  type: string
- container: ''
  name: imageSize
  type: integer
- container: ''
  name: commit
  type: boolean
- container: ''
  name: commitConvention
  type: string
- container: ''
  name: contributorsPerLine
  type: integer
- container: set
  name: contributors
  type: ''
- container: ''
  name: login
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: avatar_url
  type: reference
- container: ''
  name: profile
  type: reference
- container: set
  name: contributions
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: organization
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: copyrightHolder
  type: string
- container: ''
  name: copyrightYear
  type: integer
property_count: 24
provider_name: AUTHORS.md
provider_slug: authors-md
slug: authors-md-context
tags:
- Attribution
- Documentation
- Open Source
- Repository
- File Format
- Contributor Management
- License Compliance
- Standard
- JSON-LD
- Linked Data
- Semantic Web
---
