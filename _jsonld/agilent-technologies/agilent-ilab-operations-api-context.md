---
api_specs:
- filename: agilent-ilab-operations-api.yaml
  format: yaml
  label: Agilent iLab Operations API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/openapi/agilent-ilab-operations-api.yaml
class_count: 23
classes:
- Price Update Request
- Service Requests List Response
- Service Request Create Request
- Core
- name
- description
- url
- Invoices List Response
- Cores List Response
- Member
- email
- Price
- Prices List Response
- Invoice
- Service Request
- Project
- Members List Response
- Service
- Projects List Response
- Reservations List Response
- Error Response
- Services List Response
- Reservation
context_file: json-ld/agilent-ilab-operations-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/json-ld/agilent-ilab-operations-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agilent Ilab Operations Api from agilent-technologies.
layout: jsonld
name: Agilent Ilab Operations Api Context
namespaces:
- prefix: agilent
  uri: https://agilent.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: amount
  type: double
- container: ''
  name: currency
  type: string
- container: set
  name: serviceRequests
  type: string
- container: ''
  name: serviceId
  type: integer
- container: ''
  name: projectId
  type: integer
- container: ''
  name: quantity
  type: integer
- container: ''
  name: notes
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: institution
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: contactEmail
  type: string
- container: set
  name: invoices
  type: string
- container: set
  name: cores
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: perPage
  type: integer
- container: ''
  name: role
  type: string
- container: ''
  name: memberType
  type: string
- container: ''
  name: unit
  type: string
- container: set
  name: prices
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: totalAmount
  type: double
- container: ''
  name: issuedAt
  type: dateTime
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: principalInvestigator
  type: string
- container: ''
  name: piName
  type: string
- container: ''
  name: accountNumber
  type: string
- container: set
  name: members
  type: string
- container: set
  name: projects
  type: string
- container: set
  name: reservations
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: set
  name: services
  type: string
- container: ''
  name: equipmentName
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: user
  type: string
property_count: 37
provider_name: agilent-technologies
provider_slug: agilent-technologies
slug: agilent-ilab-operations-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agilent\": \"https://agilent.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Price Update Request\": \"agilent:Price Update Request\",\n    \"amount\": {\n      \"@id\": \"agilent:amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"currency\": {\n      \"@id\": \"agilent:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Service Requests List Response\": \"agilent:Service Requests List Response\",\n    \"serviceRequests\": {\n      \"@id\": \"agilent:service_requests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Service Request Create Request\": \"agilent:Service Request Create Request\",\n    \"serviceId\": {\n      \"@id\": \"agilent:service_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectId\": {\n      \"@id\": \"agilent:project_id\",\n \
  \     \"@type\": \"xsd:integer\"\n    },\n    \"quantity\": {\n      \"@id\": \"agilent:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notes\": {\n      \"@id\": \"agilent:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Core\": \"agilent:Core\",\n    \"id\": {\n      \"@id\": \"agilent:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"institution\": {\n      \"@id\": \"agilent:institution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"status\": {\n      \"@id\": \"agilent:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactEmail\": {\n      \"@id\": \"agilent:contact_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"Invoices List Response\": \"agilent:Invoices List Response\",\n    \"invoices\": {\n      \"@id\": \"agilent:invoices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Cores List Response\"\
  : \"agilent:Cores List Response\",\n    \"cores\": {\n      \"@id\": \"agilent:cores\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"agilent:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"agilent:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perPage\": {\n      \"@id\": \"agilent:per_page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Member\": \"agilent:Member\",\n    \"email\": \"schema:email\",\n    \"role\": {\n      \"@id\": \"agilent:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Price\": \"agilent:Price\",\n    \"memberType\": {\n      \"@id\": \"agilent:member_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"agilent:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Prices List Response\": \"agilent:Prices List Response\",\n    \"prices\": {\n      \"@id\": \"agilent:prices\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Invoice\": \"agilent:Invoice\",\n    \"period\": {\n      \"@id\": \"agilent:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"agilent:total_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"issuedAt\": {\n      \"@id\": \"agilent:issued_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Service Request\": \"agilent:Service Request\",\n    \"submittedAt\": {\n      \"@id\": \"agilent:submitted_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"principalInvestigator\": {\n      \"@id\": \"agilent:principal_investigator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Project\": \"agilent:Project\",\n    \"piName\": {\n      \"@id\": \"agilent:pi_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"agilent:account_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Members List Response\": \"agilent:Members List Response\",\n    \"members\"\
  : {\n      \"@id\": \"agilent:members\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Service\": \"agilent:Service\",\n    \"Projects List Response\": \"agilent:Projects List Response\",\n    \"projects\": {\n      \"@id\": \"agilent:projects\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reservations List Response\": \"agilent:Reservations List Response\",\n    \"reservations\": {\n      \"@id\": \"agilent:reservations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Error Response\": \"agilent:Error Response\",\n    \"error\": {\n      \"@id\": \"agilent:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"agilent:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Services List Response\": \"agilent:Services List Response\",\n    \"services\": {\n      \"@id\": \"agilent:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"Reservation\": \"agilent:Reservation\",\n    \"equipmentName\": {\n      \"@id\": \"agilent:equipment_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"agilent:start_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"agilent:end_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"user\": {\n      \"@id\": \"agilent:user\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/json-ld/agilent-ilab-operations-api-context.jsonld
tags:
- Life Sciences
- Diagnostics
- Laboratory
- Scientific Instruments
- LIMS
- Laboratory Automation
- JSON-LD
- Linked Data
- Semantic Web
---
