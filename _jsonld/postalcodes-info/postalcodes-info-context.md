---
api_specs:
- filename: openapi.json
  format: json
  label: PostalCodes.info Postal Code Reference API
  slug: postal-code-reference-api
  spec_type: OpenAPI
  url: https://postalcodes.info/openapi.json
class_count: 11
classes:
- PostalRecord
- Country
- PostalCode
- AdministrativeArea
- Place
- Dataset
- dataset
- license
- publisher
- modified
- distribution
context_file: json-ld/postalcodes-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/postalcodes-info/refs/heads/main/json-ld/postalcodes-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Postalcodes Info from PostalCodes.info.
layout: jsonld
name: Postalcodes Info Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: iso
  uri: http://standards.iso.org/iso/3166/
- prefix: postalcodesinfo
  uri: https://postalcodes.info/vocab#
properties:
- container: ''
  name: country_code
  type: string
- container: ''
  name: postal_code
  type: string
- container: ''
  name: place_name
  type: string
- container: ''
  name: admin_name1
  type: string
- container: ''
  name: admin_name2
  type: string
- container: ''
  name: admin_name3
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
property_count: 8
provider_name: PostalCodes.info
provider_slug: postalcodes-info
slug: postalcodes-info-context
source_filename: postalcodes-info-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"iso\": \"http://standards.iso.org/iso/3166/\",\n    \"postalcodesinfo\": \"https://postalcodes.info/vocab#\",\n\n    \"PostalRecord\": \"postalcodesinfo:PostalRecord\",\n    \"Country\": \"schema:Country\",\n    \"PostalCode\": \"schema:PostalCode\",\n    \"AdministrativeArea\": \"schema:AdministrativeArea\",\n    \"Place\": \"schema:Place\",\n    \"Dataset\": \"schema:Dataset\",\n\n    \"country_code\": {\n      \"@id\": \"iso:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postal_code\": {\n      \"@id\": \"schema:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"place_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"admin_name1\": {\n      \"@id\": \"schema:addressRegion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"admin_name2\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"admin_name3\": {\n      \"@id\": \"postalcodesinfo:admin3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"dataset\": \"dcat:dataset\",\n    \"license\": \"dct:license\",\n    \"publisher\": \"dct:publisher\",\n    \"modified\": \"dct:modified\",\n    \"distribution\": \"dcat:distribution\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/postalcodes-info/refs/heads/main/json-ld/postalcodes-info-context.jsonld
tags:
- Postal Codes
- Geocoding
- Open Data
- Address Validation
- Logistics
- JSON-LD
- Linked Data
- Semantic Web
---
