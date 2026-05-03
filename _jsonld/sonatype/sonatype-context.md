---
api_specs:
- filename: sonatype-lifecycle-openapi.yml
  format: yaml
  label: Sonatype Lifecycle API
  slug: sonatype-lifecycle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/openapi/sonatype-lifecycle-openapi.yml
class_count: 2
classes:
- id
- name
context_file: json-ld/sonatype-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/json-ld/sonatype-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sonatype from Sonatype.
layout: jsonld
name: Sonatype Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sonatype
  uri: https://help.sonatype.com/en/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Application
  type: reference
- container: ''
  name: PolicyViolation
  type: reference
- container: ''
  name: Vulnerability
  type: reference
- container: ''
  name: Organization
  type: reference
- container: ''
  name: publicId
  type: string
- container: ''
  name: organizationId
  type: string
- container: ''
  name: policyName
  type: string
- container: ''
  name: threatLevel
  type: integer
- container: ''
  name: packageUrl
  type: string
- container: ''
  name: waived
  type: boolean
- container: ''
  name: version
  type: string
- container: set
  name: applicationTags
  type: ''
property_count: 12
provider_name: Sonatype
provider_slug: sonatype
slug: sonatype-context
source_filename: sonatype-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sonatype\": \"https://help.sonatype.com/en/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"PolicyViolation\": {\n      \"@id\": \"sonatype:PolicyViolation\",\n      \"@type\": \"@id\"\n    },\n    \"Vulnerability\": {\n      \"@id\": \"schema:TechArticle\",\n      \"@type\": \"@id\"\n    },\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"publicId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationId\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatLevel\"\
  : {\n      \"@id\": \"sonatype:threatLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"packageUrl\": {\n      \"@id\": \"schema:softwareRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waived\": {\n      \"@id\": \"sonatype:waived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationTags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/json-ld/sonatype-context.jsonld
tags:
- Software Supply Chain
- Security
- Vulnerability Management
- SBOM
- Software Composition Analysis
- DevSecOps
- JSON-LD
- Linked Data
- Semantic Web
---
