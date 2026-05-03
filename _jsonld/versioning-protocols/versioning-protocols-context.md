---
class_count: 3
classes:
- SemanticVersion
- CalendarVersion
- URIPathVersion
context_file: json-ld/versioning-protocols-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/json-ld/versioning-protocols-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Versioning Protocols from Versioning Protocols.
layout: jsonld
name: Versioning Protocols Context
namespaces:
- prefix: versioning
  uri: https://versioning-protocols.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: version
  type: string
- container: ''
  name: major
  type: integer
- container: ''
  name: minor
  type: integer
- container: ''
  name: patch
  type: integer
- container: ''
  name: preRelease
  type: string
- container: ''
  name: buildMetadata
  type: string
- container: ''
  name: isBreaking
  type: boolean
- container: ''
  name: isFeature
  type: boolean
- container: ''
  name: isBugFix
  type: boolean
- container: ''
  name: year
  type: integer
- container: ''
  name: month
  type: integer
- container: ''
  name: day
  type: integer
- container: ''
  name: modifier
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: releaseDate
  type: date
- container: ''
  name: basePath
  type: string
- container: ''
  name: versionPrefix
  type: string
- container: ''
  name: currentVersion
  type: integer
- container: set
  name: supportedVersions
  type: integer
- container: set
  name: deprecatedVersions
  type: integer
- container: ''
  name: deprecated
  type: boolean
- container: ''
  name: sunsetDate
  type: date
property_count: 22
provider_name: Versioning Protocols
provider_slug: versioning-protocols
slug: versioning-protocols-context
source_filename: versioning-protocols-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"versioning\": \"https://versioning-protocols.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SemanticVersion\": \"versioning:SemanticVersion\",\n    \"CalendarVersion\": \"versioning:CalendarVersion\",\n    \"URIPathVersion\": \"versioning:URIPathVersion\",\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"major\": {\n      \"@id\": \"versioning:major\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minor\": {\n      \"@id\": \"versioning:minor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"patch\": {\n      \"@id\": \"versioning:patch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"preRelease\": {\n      \"@id\": \"versioning:preRelease\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildMetadata\": {\n      \"@id\": \"versioning:buildMetadata\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"isBreaking\": {\n      \"@id\": \"versioning:isBreaking\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFeature\": {\n      \"@id\": \"versioning:isFeature\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isBugFix\": {\n      \"@id\": \"versioning:isBugFix\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"year\": {\n      \"@id\": \"versioning:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"month\": {\n      \"@id\": \"versioning:month\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"day\": {\n      \"@id\": \"versioning:day\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modifier\": {\n      \"@id\": \"versioning:modifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"versioning:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releaseDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"basePath\": {\n      \"@id\": \"versioning:basePath\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"versionPrefix\": {\n      \"@id\": \"versioning:versionPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentVersion\": {\n      \"@id\": \"versioning:currentVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"supportedVersions\": {\n      \"@id\": \"versioning:supportedVersions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deprecatedVersions\": {\n      \"@id\": \"versioning:deprecatedVersions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deprecated\": {\n      \"@id\": \"versioning:deprecated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sunsetDate\": {\n      \"@id\": \"versioning:sunsetDate\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/json-ld/versioning-protocols-context.jsonld
tags:
- API Design
- Backward Compatibility
- Software Development
- Version Control
- Semantic Versioning
- API Lifecycle
- Deprecation
- JSON-LD
- Linked Data
- Semantic Web
---
