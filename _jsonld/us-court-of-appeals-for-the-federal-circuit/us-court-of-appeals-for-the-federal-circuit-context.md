---
class_count: 5
classes:
- DocketEntry
- FederalCircuitCase
- FederalCircuitOpinion
- description
- title
context_file: json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Court Of Appeals For The Federal Circuit from US Court of Appeals for the Federal Circuit.
layout: jsonld
name: Us Court Of Appeals For The Federal Circuit Context
namespaces:
- prefix: cafc
  uri: https://www.cafc.uscourts.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: authoring_judge
  type: string
- container: ''
  name: case_number
  type: string
- container: ''
  name: case_title
  type: string
- container: ''
  name: case_type
  type: string
- container: ''
  name: court_code
  type: string
- container: ''
  name: date_decided
  type: date
- container: ''
  name: date_filed
  type: date
- container: ''
  name: date_issued
  type: date
- container: ''
  name: docket_number
  type: string
- container: ''
  name: document_type
  type: string
- container: ''
  name: entry_number
  type: integer
- container: ''
  name: filing_party
  type: string
- container: ''
  name: is_precedential
  type: boolean
- container: ''
  name: is_sealed
  type: boolean
- container: set
  name: judges
  type: string
- container: ''
  name: opinion_type
  type: string
- container: ''
  name: oral_argument_date
  type: date
- container: ''
  name: origin_court
  type: string
- container: ''
  name: outcome
  type: string
- container: ''
  name: pacer_doc_id
  type: string
- container: ''
  name: page_count
  type: integer
- container: set
  name: parties
  type: reference
- container: ''
  name: pdf_url
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: subject_matter
  type: string
property_count: 25
provider_name: US Court of Appeals for the Federal Circuit
provider_slug: us-court-of-appeals-for-the-federal-circuit
slug: us-court-of-appeals-for-the-federal-circuit-context
source_filename: us-court-of-appeals-for-the-federal-circuit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cafc\": \"https://www.cafc.uscourts.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DocketEntry\": \"cafc:DocketEntry\",\n    \"FederalCircuitCase\": \"cafc:FederalCircuitCase\",\n    \"FederalCircuitOpinion\": \"cafc:FederalCircuitOpinion\",\n    \"authoring_judge\": {\n      \"@id\": \"cafc:authoring_judge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"case_number\": {\n      \"@id\": \"cafc:case_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"case_title\": {\n      \"@id\": \"cafc:case_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"case_type\": {\n      \"@id\": \"cafc:case_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"court_code\": {\n      \"@id\": \"cafc:court_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date_decided\": {\n      \"@id\": \"cafc:date_decided\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"date_filed\": {\n      \"@id\": \"cafc:date_filed\",\n      \"@type\": \"xsd:date\"\n    },\n    \"date_issued\": {\n      \"@id\": \"cafc:date_issued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"description\": \"schema:description\",\n    \"docket_number\": {\n      \"@id\": \"cafc:docket_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document_type\": {\n      \"@id\": \"cafc:document_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entry_number\": {\n      \"@id\": \"cafc:entry_number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filing_party\": {\n      \"@id\": \"cafc:filing_party\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_precedential\": {\n      \"@id\": \"cafc:is_precedential\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_sealed\": {\n      \"@id\": \"cafc:is_sealed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"judges\": {\n      \"@id\": \"cafc:judges\",\n      \"@container\": \"\
  @set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opinion_type\": {\n      \"@id\": \"cafc:opinion_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oral_argument_date\": {\n      \"@id\": \"cafc:oral_argument_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"origin_court\": {\n      \"@id\": \"cafc:origin_court\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outcome\": {\n      \"@id\": \"cafc:outcome\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pacer_doc_id\": {\n      \"@id\": \"cafc:pacer_doc_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"page_count\": {\n      \"@id\": \"cafc:page_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parties\": {\n      \"@id\": \"cafc:parties\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"pdf_url\": {\n      \"@id\": \"cafc:pdf_url\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"cafc:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject_matter\"\
  : {\n      \"@id\": \"cafc:subject_matter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": \"schema:name\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld
tags:
- Federal Government
- Legal
- Patent Law
- Federal Courts
- Appellate Courts
- JSON-LD
- Linked Data
- Semantic Web
---
