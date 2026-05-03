---
api_specs:
- filename: sisense-rest-api-openapi.yml
  format: yaml
  label: Sisense REST API v1
  slug: rest-api-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/openapi/sisense-rest-api-openapi.yml
class_count: 19
classes:
- Dashboard
- Widget
- Elasticube
- DataSecurityRule
- User
- Group
- oid
- _id
- title
- desc
- email
- firstName
- lastName
- role
- active
- table
- column
- SoftwareApplication
- WebAPI
context_file: json-ld/sisense-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/json-ld/sisense-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sisense from Sisense.
layout: jsonld
name: Sisense Context
namespaces:
- prefix: sisense
  uri: https://developer.sisense.com/schema/
properties:
- container: ''
  name: owner
  type: reference
- container: set
  name: groups
  type: reference
- container: set
  name: shares
  type: ''
- container: ''
  name: created
  type: schema:DateTime
- container: ''
  name: lastUpdated
  type: schema:DateTime
- container: set
  name: members
  type: ''
property_count: 6
provider_name: Sisense
provider_slug: sisense
slug: sisense-context
source_filename: sisense-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sisense\": \"https://developer.sisense.com/schema/\",\n    \"Dashboard\": \"sisense:Dashboard\",\n    \"Widget\": \"sisense:Widget\",\n    \"Elasticube\": \"sisense:Elasticube\",\n    \"DataSecurityRule\": \"sisense:DataSecurityRule\",\n    \"User\": \"schema:Person\",\n    \"Group\": \"schema:Organization\",\n    \"oid\": \"@id\",\n    \"_id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"desc\": \"schema:description\",\n    \"owner\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"role\": \"sisense:role\",\n    \"groups\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"shares\": {\n      \"@id\": \"sisense:shares\",\n      \"@container\": \"@set\"\n    },\n    \"created\": {\n      \"@id\"\
  : \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"active\": \"sisense:active\",\n    \"table\": \"sisense:table\",\n    \"column\": \"sisense:column\",\n    \"members\": {\n      \"@id\": \"sisense:members\",\n      \"@container\": \"@set\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"WebAPI\": \"schema:WebAPI\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/json-ld/sisense-context.jsonld
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Models
- Embedded Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
