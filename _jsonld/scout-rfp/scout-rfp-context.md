---
api_specs:
- filename: scout-rfp-events-openapi.yml
  format: yaml
  label: Workday Strategic Sourcing API
  slug: workday-strategic-sourcing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/openapi/scout-rfp-events-openapi.yml
class_count: 2
classes:
- title
- description
context_file: json-ld/scout-rfp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/json-ld/scout-rfp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scout Rfp from Scout RFP.
layout: jsonld
name: Scout Rfp Context
namespaces:
- prefix: scout
  uri: https://api-evangelist.github.io/scout-rfp/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: SourcingEvent
  type: rdfs:Class
- container: ''
  name: Bid
  type: rdfs:Class
- container: ''
  name: Supplier
  type: schema:Organization
- container: ''
  name: Worksheet
  type: rdfs:Class
- container: ''
  name: LineItem
  type: rdfs:Class
- container: ''
  name: state
  type: string
- container: ''
  name: spendAmount
  type: decimal
- container: ''
  name: eventType
  type: string
- container: ''
  name: bidSubmissionDeadline
  type: dateTime
- container: ''
  name: supplierRsvpDeadline
  type: dateTime
- container: ''
  name: externalId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: totalCost
  type: decimal
property_count: 16
provider_name: Scout RFP
provider_slug: scout-rfp
slug: scout-rfp-context
source_filename: scout-rfp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"scout\": \"https://api-evangelist.github.io/scout-rfp/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SourcingEvent\": {\n      \"@id\": \"scout:SourcingEvent\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A sourcing event such as an RFP, RFI, or reverse auction in a procurement platform\"\n    },\n    \"Bid\": {\n      \"@id\": \"scout:Bid\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A supplier's bid response to a sourcing event\"\n    },\n    \"Supplier\": {\n      \"@id\": \"scout:Supplier\",\n      \"@type\": \"schema:Organization\",\n      \"rdfs:comment\": \"A supplier company participating in sourcing events\"\n    },\n    \"Worksheet\": {\n      \"@id\": \"scout:Worksheet\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A structured worksheet within a sourcing event containing line items\"\n    },\n    \"LineItem\": {\n   \
  \   \"@id\": \"scout:LineItem\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A product or service being sourced in a worksheet\"\n    },\n\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"state\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spendAmount\": {\n      \"@id\": \"scout:spendAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"eventType\": {\n      \"@id\": \"scout:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bidSubmissionDeadline\": {\n      \"@id\": \"scout:bidSubmissionDeadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"supplierRsvpDeadline\": {\n      \"@id\": \"scout:supplierRsvpDeadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"externalId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unit\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCost\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/json-ld/scout-rfp-context.jsonld
tags:
- Procurement
- Sourcing
- RFP
- Supply Chain
- Workday
- JSON-LD
- Linked Data
- Semantic Web
---
