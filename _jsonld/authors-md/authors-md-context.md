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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"authors\": \"https://authors-md.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"spdx\": \"http://spdx.org/rdf/terms#\",\n\n    \"AllContributorsConfig\": \"authors:AllContributorsConfig\",\n    \"Contributor\": \"authors:Contributor\",\n    \"AuthorEntry\": \"authors:AuthorEntry\",\n\n    \"projectName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectOwner\": {\n      \"@id\": \"authors:projectOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repoType\": {\n      \"@id\": \"authors:repoType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repoHost\": {\n      \"@id\": \"authors:repoHost\",\n      \"@type\": \"@id\"\n    },\n    \"files\": {\n      \"@id\": \"authors:files\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"imageSize\": {\n      \"@id\": \"authors:imageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commit\": {\n      \"@id\": \"authors:commit\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"commitConvention\": {\n      \"@id\": \"authors:commitConvention\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contributorsPerLine\": {\n      \"@id\": \"authors:contributorsPerLine\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contributors\": {\n      \"@id\": \"authors:contributors\",\n      \"@container\": \"@set\"\n    },\n    \"login\": {\n      \"@id\": \"authors:login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatar_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"profile\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"contributions\": {\n      \"@id\": \"authors:contributions\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"organization\": {\n      \"@id\": \"schema:affiliation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"authors:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"spdx:license\",\n      \"@type\": \"xsd:string\"\n    },\n    \"copyrightHolder\": {\n      \"@id\": \"dcterms:rightsHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"copyrightYear\": {\n      \"@id\": \"dcterms:dateCopyrighted\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/json-ld/authors-md-context.jsonld
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
