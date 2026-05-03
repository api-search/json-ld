---
api_specs:
- filename: quorum-land-management-openapi.yml
  format: yaml
  label: Quorum Land Management API
  slug: quorum-land-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quorum/refs/heads/main/openapi/quorum-land-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/quorum-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/quorum/refs/heads/main/json-ld/quorum-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Quorum from Quorum Software.
layout: jsonld
name: Quorum Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: quorum
  uri: https://www.quorumsoftware.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: Lease
  type: reference
- container: ''
  name: leaseId
  type: ''
- container: ''
  name: leaseName
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: royaltyRate
  type: decimal
- container: ''
  name: netAcres
  type: decimal
- container: ''
  name: grossAcres
  type: decimal
- container: ''
  name: county
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: lessor
  type: ''
- container: ''
  name: lessee
  type: ''
- container: ''
  name: hbpStatus
  type: boolean
- container: ''
  name: Tract
  type: reference
- container: ''
  name: tractId
  type: ''
- container: ''
  name: legalDescription
  type: ''
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: Well
  type: reference
- container: ''
  name: wellId
  type: ''
- container: ''
  name: wellName
  type: ''
- container: ''
  name: apiNumber
  type: ''
- container: ''
  name: wellType
  type: ''
- container: ''
  name: spudDate
  type: date
- container: ''
  name: totalDepth
  type: decimal
- container: ''
  name: formation
  type: ''
- container: ''
  name: DivisionOrder
  type: reference
- container: ''
  name: divisionOrderId
  type: ''
- container: ''
  name: interestType
  type: ''
- container: ''
  name: decimalInterest
  type: decimal
- container: ''
  name: Owner
  type: reference
- container: ''
  name: ownerId
  type: ''
- container: ''
  name: ownerName
  type: ''
- container: ''
  name: ownerType
  type: ''
property_count: 35
provider_name: Quorum Software
provider_slug: quorum
slug: quorum-context
source_filename: quorum-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"quorum\": \"https://www.quorumsoftware.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n\n    \"Lease\": {\n      \"@id\": \"schema:LicenseDocument\",\n      \"@type\": \"@id\"\n    },\n    \"leaseId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"leaseName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"royaltyRate\": {\n      \"@id\": \"quorum:royaltyRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"netAcres\": {\n      \"@id\": \"quorum:netAcres\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"grossAcres\": {\n      \"\
  @id\": \"quorum:grossAcres\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"county\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"lessor\": {\n      \"@id\": \"schema:seller\"\n    },\n    \"lessee\": {\n      \"@id\": \"schema:buyer\"\n    },\n    \"hbpStatus\": {\n      \"@id\": \"quorum:heldByProduction\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"Tract\": {\n      \"@id\": \"schema:LandForm\",\n      \"@type\": \"@id\"\n    },\n    \"tractId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"legalDescription\": {\n      \"@id\": \"schema:description\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Well\": {\n      \"@id\": \"schema:MoneyTransfer\",\n      \"@type\": \"@id\"\n    },\n    \"wellId\": {\n      \"@id\"\
  : \"schema:identifier\"\n    },\n    \"wellName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"apiNumber\": {\n      \"@id\": \"quorum:apiNumber\"\n    },\n    \"wellType\": {\n      \"@id\": \"quorum:wellType\"\n    },\n    \"spudDate\": {\n      \"@id\": \"quorum:spudDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalDepth\": {\n      \"@id\": \"quorum:totalDepth\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"formation\": {\n      \"@id\": \"quorum:formation\"\n    },\n\n    \"DivisionOrder\": {\n      \"@id\": \"schema:PaymentCard\",\n      \"@type\": \"@id\"\n    },\n    \"divisionOrderId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"interestType\": {\n      \"@id\": \"quorum:interestType\"\n    },\n    \"decimalInterest\": {\n      \"@id\": \"quorum:decimalInterest\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Owner\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"ownerId\": {\n      \"@id\": \"schema:identifier\"\
  \n    },\n    \"ownerName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"ownerType\": {\n      \"@id\": \"quorum:ownerType\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/quorum/refs/heads/main/json-ld/quorum-context.jsonld
tags:
- Energy
- Oil & Gas
- Upstream
- Land Management
- Royalty Accounting
- Production Reporting
- JSON-LD
- Linked Data
- Semantic Web
---
