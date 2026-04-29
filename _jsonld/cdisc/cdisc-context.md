---
class_count: 6
classes:
- name
- label
- description
- version
- dataType
- definition
context_file: json-ld/cdisc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/json-ld/cdisc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cdisc from cdisc.
layout: jsonld
name: Cdisc Context
namespaces:
- prefix: cdisc
  uri: https://library.cdisc.org/api/
- prefix: schema
  uri: https://schema.org/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Dataset
  type: schema:Dataset
- container: ''
  name: Variable
  type: ''
- container: ''
  name: Standard
  type: schema:CreativeWork
- container: ''
  name: BiomedicalConcept
  type: schema:MedicalConcept
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: core
  type: ''
- container: ''
  name: role
  type: ''
- container: set
  name: variables
  type: ''
- container: ''
  name: datasetClass
  type: ''
- container: set
  name: codelistSubmissionValues
  type: ''
- container: ''
  name: conceptId
  type: ''
- container: set
  name: dataElements
  type: ''
- container: ''
  name: length
  type: integer
- container: ''
  name: registrationStatus
  type: ''
- container: ''
  name: purpose
  type: ''
- container: set
  name: keys
  type: ''
property_count: 16
provider_name: cdisc
provider_slug: cdisc
slug: cdisc-context
source_filename: cdisc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cdisc\": \"https://library.cdisc.org/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Dataset\": {\n      \"@id\": \"cdisc:Dataset\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"Variable\": {\n      \"@id\": \"cdisc:Variable\"\n    },\n    \"Standard\": {\n      \"@id\": \"cdisc:Standard\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n    \"BiomedicalConcept\": {\n      \"@id\": \"cdisc:BiomedicalConcept\",\n      \"@type\": \"schema:MedicalConcept\"\n    },\n\n    \"name\": \"schema:name\",\n    \"label\": \"rdfs:label\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"effectiveDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dataType\": \"schema:DataType\"\
  ,\n    \"core\": {\n      \"@id\": \"cdisc:coreRequirement\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\"\n    },\n    \"variables\": {\n      \"@id\": \"cdisc:hasVariable\",\n      \"@container\": \"@set\"\n    },\n    \"datasetClass\": {\n      \"@id\": \"cdisc:observationClass\"\n    },\n    \"codelistSubmissionValues\": {\n      \"@id\": \"cdisc:codelistValue\",\n      \"@container\": \"@set\"\n    },\n    \"conceptId\": {\n      \"@id\": \"cdisc:conceptIdentifier\"\n    },\n    \"definition\": \"skos:definition\",\n    \"dataElements\": {\n      \"@id\": \"cdisc:hasDataElement\",\n      \"@container\": \"@set\"\n    },\n    \"length\": {\n      \"@id\": \"schema:maxValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"registrationStatus\": {\n      \"@id\": \"schema:creativeWorkStatus\"\n    },\n    \"purpose\": {\n      \"@id\": \"schema:purpose\"\n    },\n    \"keys\": {\n      \"@id\": \"cdisc:keyVariable\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/json-ld/cdisc-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
