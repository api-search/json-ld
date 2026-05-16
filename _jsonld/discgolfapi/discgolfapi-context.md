---
api_specs:
- filename: discgolfapi-openapi.yml
  format: yaml
  label: DiscGolfAPI REST API
  slug: discgolfapi-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/discgolfapi/refs/heads/main/openapi/discgolfapi-openapi.yml
class_count: 0
classes: []
context_file: json-ld/discgolfapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/discgolfapi/refs/heads/main/json-ld/discgolfapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Discgolfapi from DiscGolfAPI.
layout: jsonld
name: Discgolfapi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: dga
  uri: https://api-evangelist.github.io/discgolfapi/vocab#
properties:
- container: ''
  name: Course
  type: reference
- container: ''
  name: Layout
  type: reference
- container: ''
  name: Country
  type: reference
- container: ''
  name: Region
  type: reference
- container: ''
  name: Update
  type: reference
- container: ''
  name: Manifest
  type: reference
- container: ''
  name: id
  type: ''
- container: ''
  name: slug
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: website
  type: reference
- container: ''
  name: lat
  type: decimal
- container: ''
  name: lon
  type: decimal
- container: ''
  name: country_code
  type: ''
- container: ''
  name: region_code
  type: ''
- container: ''
  name: locality
  type: ''
- container: ''
  name: operator_name
  type: ''
- container: ''
  name: holes
  type: integer
- container: ''
  name: par_total
  type: integer
- container: ''
  name: length_meters
  type: decimal
- container: ''
  name: existence_status
  type: ''
- container: ''
  name: operational_status
  type: ''
- container: ''
  name: access_model
  type: ''
- container: ''
  name: condition_status
  type: ''
- container: ''
  name: listing_status
  type: ''
- container: ''
  name: confidence_score
  type: decimal
- container: ''
  name: verification_strength
  type: ''
- container: ''
  name: last_verified_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: generated_at
  type: dateTime
- container: ''
  name: primary_layout
  type: reference
- container: ''
  name: attributes
  type: ''
- container: ''
  name: schema_version
  type: ''
- container: ''
  name: publish_version
  type: ''
- container: ''
  name: contract_version
  type: ''
- container: ''
  name: release_scope
  type: ''
- container: ''
  name: artefact_base_url
  type: reference
- container: ''
  name: attribution
  type: ''
- container: ''
  name: attribution_required
  type: boolean
- container: ''
  name: license
  type: reference
- container: ''
  name: license_url
  type: reference
- container: ''
  name: terms_url
  type: reference
- container: ''
  name: no_warranty
  type: ''
- container: list
  name: courses
  type: ''
- container: list
  name: countries
  type: ''
- container: list
  name: regions
  type: ''
- container: list
  name: updates
  type: ''
- container: ''
  name: course_id
  type: ''
- container: ''
  name: course_slug
  type: ''
- container: ''
  name: course_name
  type: ''
- container: ''
  name: change_type
  type: ''
- container: ''
  name: course_count
  type: integer
- container: ''
  name: count
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: offset
  type: integer
property_count: 56
provider_name: DiscGolfAPI
provider_slug: discgolfapi
slug: discgolfapi-context
source_filename: discgolfapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"dga\": \"https://api-evangelist.github.io/discgolfapi/vocab#\",\n\n    \"Course\": {\n      \"@id\": \"dga:Course\",\n      \"@type\": \"@id\"\n    },\n    \"Layout\": {\n      \"@id\": \"dga:Layout\",\n      \"@type\": \"@id\"\n    },\n    \"Country\": {\n      \"@id\": \"schema:Country\",\n      \"@type\": \"@id\"\n    },\n    \"Region\": {\n      \"@id\": \"schema:AdministrativeArea\",\n      \"@type\": \"@id\"\n    },\n    \"Update\": {\n      \"@id\": \"dga:Update\",\n      \"@type\": \"@id\"\n    },\n    \"Manifest\": {\n      \"@id\": \"dcat:Dataset\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": { \"@id\": \"schema:identifier\" },\n    \"slug\": { \"@id\": \"dga:slug\"\
  \ },\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n\n    \"lat\": { \"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\" },\n    \"lon\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" },\n\n    \"country_code\": { \"@id\": \"dga:countryCode\" },\n    \"region_code\": { \"@id\": \"dga:regionCode\" },\n    \"locality\": { \"@id\": \"schema:addressLocality\" },\n\n    \"operator_name\": { \"@id\": \"dga:operatorName\" },\n    \"holes\": { \"@id\": \"dga:holes\", \"@type\": \"xsd:integer\" },\n    \"par_total\": { \"@id\": \"dga:parTotal\", \"@type\": \"xsd:integer\" },\n    \"length_meters\": { \"@id\": \"dga:lengthMeters\", \"@type\": \"xsd:decimal\" },\n\n    \"existence_status\": { \"@id\": \"dga:existenceStatus\" },\n    \"operational_status\": { \"@id\": \"dga:operationalStatus\" },\n    \"access_model\"\
  : { \"@id\": \"dga:accessModel\" },\n    \"condition_status\": { \"@id\": \"dga:conditionStatus\" },\n    \"listing_status\": { \"@id\": \"dga:listingStatus\" },\n\n    \"confidence_score\": { \"@id\": \"dga:confidenceScore\", \"@type\": \"xsd:decimal\" },\n    \"verification_strength\": { \"@id\": \"dga:verificationStrength\" },\n    \"last_verified_at\": { \"@id\": \"dga:lastVerifiedAt\", \"@type\": \"xsd:dateTime\" },\n    \"updated_at\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"generated_at\": { \"@id\": \"dct:issued\", \"@type\": \"xsd:dateTime\" },\n\n    \"primary_layout\": { \"@id\": \"dga:primaryLayout\", \"@type\": \"@id\" },\n    \"attributes\": { \"@id\": \"dga:attributes\" },\n\n    \"schema_version\": { \"@id\": \"dct:conformsTo\" },\n    \"publish_version\": { \"@id\": \"dga:publishVersion\" },\n    \"contract_version\": { \"@id\": \"dga:contractVersion\" },\n    \"release_scope\": { \"@id\": \"dga:releaseScope\" },\n    \"artefact_base_url\"\
  : { \"@id\": \"dcat:downloadURL\", \"@type\": \"@id\" },\n\n    \"attribution\": { \"@id\": \"dct:rightsHolder\" },\n    \"attribution_required\": { \"@id\": \"dga:attributionRequired\", \"@type\": \"xsd:boolean\" },\n    \"license\": { \"@id\": \"schema:license\", \"@type\": \"@id\" },\n    \"license_url\": { \"@id\": \"dct:license\", \"@type\": \"@id\" },\n    \"terms_url\": { \"@id\": \"dct:termsOfUse\", \"@type\": \"@id\" },\n    \"no_warranty\": { \"@id\": \"dga:noWarranty\" },\n\n    \"courses\": { \"@id\": \"dga:courses\", \"@container\": \"@list\" },\n    \"countries\": { \"@id\": \"dga:countries\", \"@container\": \"@list\" },\n    \"regions\": { \"@id\": \"dga:regions\", \"@container\": \"@list\" },\n    \"updates\": { \"@id\": \"dga:updates\", \"@container\": \"@list\" },\n\n    \"course_id\": { \"@id\": \"dga:courseId\" },\n    \"course_slug\": { \"@id\": \"dga:courseSlug\" },\n    \"course_name\": { \"@id\": \"schema:name\" },\n    \"change_type\": { \"@id\": \"dga:changeType\"\
  \ },\n    \"course_count\": { \"@id\": \"dga:courseCount\", \"@type\": \"xsd:integer\" },\n    \"count\": { \"@id\": \"dga:count\", \"@type\": \"xsd:integer\" },\n    \"total\": { \"@id\": \"dga:total\", \"@type\": \"xsd:integer\" },\n    \"offset\": { \"@id\": \"dga:offset\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/discgolfapi/refs/heads/main/json-ld/discgolfapi-context.jsonld
tags:
- Disc Golf
- Sports
- Courses
- Open Data
- Recreation
- JSON-LD
- Linked Data
- Semantic Web
---
