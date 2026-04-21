---
class_count: 9
classes:
- APIsJSON
- APIEntry
- Property
- Contact
- Include
- Overlay
- Network
- name
- description
context_file: json-ld/apis-json-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-ld/apis-json-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apis Json from APIs.json.
layout: jsonld
name: Apis Json Context
namespaces:
- prefix: apij
  uri: https://apisjson.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: aid
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: humanUrl
  type: reference
- container: ''
  name: baseURL
  type: reference
- container: ''
  name: image
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: specificationVersion
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: position
  type: string
- container: ''
  name: access
  type: string
- container: ''
  name: version
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: apis
  type: ''
- container: set
  name: common
  type: ''
- container: set
  name: properties
  type: ''
- container: set
  name: maintainers
  type: ''
- container: set
  name: contact
  type: ''
- container: set
  name: include
  type: ''
- container: set
  name: overlays
  type: ''
- container: set
  name: network
  type: ''
- container: ''
  name: FN
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: data
  type: ''
property_count: 26
provider_name: APIs.json
provider_slug: apis-json
slug: apis-json-context
tags:
- API Aggregation
- API Cataloging
- API Commons
- API Discovery
- API Governance
- API Operations
- Machine Readable
- Specification
- Standard
- JSON-LD
- Linked Data
- Semantic Web
---
