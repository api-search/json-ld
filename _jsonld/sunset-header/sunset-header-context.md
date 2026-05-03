---
class_count: 0
classes: []
context_file: json-ld/sunset-header-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sunset-header/refs/heads/main/json-ld/sunset-header-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sunset Header from Sunset Header.
layout: jsonld
name: Sunset Header Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ietf
  uri: https://www.rfc-editor.org/rfc/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: http
  uri: http://www.iana.org/assignments/http-fields/
properties:
- container: ''
  name: SunsetHeader
  type: reference
- container: ''
  name: DeprecationHeader
  type: reference
- container: ''
  name: sunsetDate
  type: dateTime
- container: ''
  name: deprecationDate
  type: dateTime
- container: ''
  name: sunsetLinkRelation
  type: reference
- container: ''
  name: deprecationLinkRelation
  type: reference
- container: ''
  name: APIEndpoint
  type: ''
- container: ''
  name: APIVersion
  type: ''
- container: ''
  name: deprecatedBy
  type: reference
- container: ''
  name: replacedBy
  type: reference
- container: ''
  name: endOfLifeDate
  type: dateTime
- container: ''
  name: migrationGuide
  type: reference
- container: ''
  name: httpStatusCode
  type: ''
- container: ''
  name: linkRelation
  type: reference
- container: ''
  name: rfc
  type: reference
property_count: 15
provider_name: Sunset Header
provider_slug: sunset-header
slug: sunset-header-context
source_filename: sunset-header-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ietf\": \"https://www.rfc-editor.org/rfc/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"http\": \"http://www.iana.org/assignments/http-fields/\",\n\n    \"SunsetHeader\": {\n      \"@id\": \"ietf:rfc8594#section-3\",\n      \"@type\": \"@id\"\n    },\n    \"DeprecationHeader\": {\n      \"@id\": \"ietf:rfc9745#section-2\",\n      \"@type\": \"@id\"\n    },\n    \"sunsetDate\": {\n      \"@id\": \"ietf:rfc8594#section-3\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deprecationDate\": {\n      \"@id\": \"ietf:rfc9745#section-2\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sunsetLinkRelation\": {\n      \"@id\": \"ietf:rfc8594#section-5\",\n      \"@type\": \"@id\"\n    },\n    \"deprecationLinkRelation\": {\n      \"@id\": \"ietf:rfc9745#section-3\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"APIEndpoint\": {\n      \"@id\": \"schema:EntryPoint\"\n    },\n    \"APIVersion\": {\n      \"@id\": \"schema:version\"\n    },\n    \"deprecatedBy\": {\n      \"@id\": \"schema:supersededBy\",\n      \"@type\": \"@id\"\n    },\n    \"replacedBy\": {\n      \"@id\": \"schema:successorOf\",\n      \"@type\": \"@id\"\n    },\n    \"endOfLifeDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"migrationGuide\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"httpStatusCode\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"linkRelation\": {\n      \"@id\": \"http:link-relation\",\n      \"@type\": \"@id\"\n    },\n    \"rfc\": {\n      \"@id\": \"owl:seeAlso\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sunset-header/refs/heads/main/json-ld/sunset-header-context.jsonld
tags:
- API Deprecation
- HTTP Headers
- RFC 8594
- RFC 9745
- API Lifecycle
- REST APIs
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
