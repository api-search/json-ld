---
class_count: 5
classes:
- AccessibilityStandard
- GuidanceDocument
- Complaint
- Training
- TechnicalAssistance
context_file: json-ld/u-s-access-board-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/u-s-access-board/refs/heads/main/json-ld/u-s-access-board-context.jsonld
description: JSON-LD context defining the semantic vocabulary for U S Access Board from U.S. Access Board.
layout: jsonld
name: U S Access Board Context
namespaces:
- prefix: ab
  uri: https://www.access-board.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: title
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: citation
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: publicationDate
  type: date
- container: ''
  name: authority
  type: string
- container: ''
  name: applicability
  type: string
- container: ''
  name: technicalRequirements
  type: string
- container: ''
  name: standardType
  type: string
- container: ''
  name: complaintId
  type: string
- container: ''
  name: facilityName
  type: string
- container: ''
  name: facilityAddress
  type: string
- container: ''
  name: federalFunding
  type: boolean
- container: ''
  name: barrierDescription
  type: string
- container: ''
  name: filingDate
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: standard
  type: string
- container: ''
  name: identifier
  type: string
property_count: 21
provider_name: U.S. Access Board
provider_slug: u-s-access-board
slug: u-s-access-board-context
source_filename: u-s-access-board-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ab\": \"https://www.access-board.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"AccessibilityStandard\": \"ab:AccessibilityStandard\",\n    \"GuidanceDocument\": \"ab:GuidanceDocument\",\n    \"Complaint\": \"ab:Complaint\",\n    \"Training\": \"ab:Training\",\n    \"TechnicalAssistance\": \"ab:TechnicalAssistance\",\n\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"citation\": {\n      \"@id\": \"ab:citation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n \
  \     \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"publicationDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"authority\": {\n      \"@id\": \"dcterms:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicability\": {\n      \"@id\": \"ab:applicability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"technicalRequirements\": {\n      \"@id\": \"ab:technicalRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardType\": {\n      \"@id\": \"ab:standardType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complaintId\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilityName\": {\n      \"@id\": \"ab:facilityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilityAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"federalFunding\": {\n      \"@id\": \"ab:federalFunding\",\n  \
  \    \"@type\": \"xsd:boolean\"\n    },\n    \"barrierDescription\": {\n      \"@id\": \"ab:barrierDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filingDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"ab:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"dcterms:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standard\": {\n      \"@id\": \"ab:standard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/u-s-access-board/refs/heads/main/json-ld/u-s-access-board-context.jsonld
tags:
- Federal Government
- Accessibility
- Disability
- Standards
- Built Environment
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
