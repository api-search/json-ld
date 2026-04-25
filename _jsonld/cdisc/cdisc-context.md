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
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
