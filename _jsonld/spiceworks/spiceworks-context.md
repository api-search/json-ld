---
api_specs:
- filename: spiceworks-cloud-apps-openapi.yml
  format: yaml
  label: Spiceworks Cloud Apps API
  slug: spiceworks-cloud-apps-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/openapi/spiceworks-cloud-apps-openapi.yml
class_count: 5
classes:
- Ticket
- Device
- User
- Comment
- id
context_file: json-ld/spiceworks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/json-ld/spiceworks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spiceworks from Spiceworks.
layout: jsonld
name: Spiceworks Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spiceworks
  uri: https://community.spiceworks.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: summary
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: assignee
  type: reference
- container: ''
  name: creator
  type: reference
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: due_date
  type: date
- container: list
  name: tags
  type: ''
- container: set
  name: comments
  type: ''
- container: ''
  name: body
  type: string
- container: ''
  name: is_public
  type: boolean
- container: ''
  name: author
  type: reference
- container: ''
  name: first_name
  type: string
- container: ''
  name: last_name
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: department
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: serial_number
  type: string
- container: ''
  name: ip_address
  type: string
- container: ''
  name: mac_address
  type: string
- container: ''
  name: os_name
  type: string
- container: ''
  name: os_version
  type: string
- container: ''
  name: last_seen_at
  type: dateTime
property_count: 29
provider_name: Spiceworks
provider_slug: spiceworks
slug: spiceworks-context
source_filename: spiceworks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spiceworks\": \"https://community.spiceworks.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Ticket\": \"spiceworks:Ticket\",\n    \"Device\": \"spiceworks:Device\",\n    \"User\": \"schema:Person\",\n    \"Comment\": \"schema:Comment\",\n\n    \"id\": \"@id\",\n    \"summary\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"spiceworks:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"spiceworks:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignee\": {\n      \"@id\": \"schema:agent\",\n      \"@type\": \"@id\"\n    },\n    \"creator\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    },\n    \"created_at\": {\n\
  \      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"due_date\": {\n      \"@id\": \"schema:scheduledTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"comments\": {\n      \"@id\": \"schema:comment\",\n      \"@container\": \"@set\"\n    },\n    \"body\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_public\": {\n      \"@id\": \"spiceworks:isPublic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"first_name\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_name\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"\
  @id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department\": {\n      \"@id\": \"schema:department\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"spiceworks:deviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serial_number\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip_address\": {\n      \"@id\": \"spiceworks:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mac_address\": {\n      \"@id\": \"spiceworks:macAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os_name\": {\n\
  \      \"@id\": \"spiceworks:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os_version\": {\n      \"@id\": \"spiceworks:osVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_seen_at\": {\n      \"@id\": \"spiceworks:lastSeenAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/json-ld/spiceworks-context.jsonld
tags:
- Community
- Enterprise IT
- IT Management
- JSON-LD
- Linked Data
- Semantic Web
---
