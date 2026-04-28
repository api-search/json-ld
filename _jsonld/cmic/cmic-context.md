---
class_count: 9
classes:
- projectId
- projectName
- description
- street
- city
- state
- postalCode
- country
- vendorName
context_file: json-ld/cmic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/json-ld/cmic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cmic from CMiC.
layout: jsonld
name: Cmic Context
namespaces:
- prefix: cmic
  uri: https://api.cmic.ca/rest/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Project
  type: schema:Project
- container: ''
  name: Job
  type: schema:JobPosting
- container: ''
  name: CostCode
  type: ''
- container: ''
  name: Vendor
  type: schema:Organization
- container: ''
  name: Equipment
  type: schema:Product
- container: ''
  name: Document
  type: schema:DigitalDocument
- container: ''
  name: companyCode
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: projectManager
  type: schema:Person
- container: ''
  name: owner
  type: schema:Organization
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: contractAmount
  type: decimal
- container: ''
  name: originalBudget
  type: decimal
- container: ''
  name: revisedBudget
  type: decimal
- container: ''
  name: actualCost
  type: decimal
- container: ''
  name: committedCost
  type: decimal
- container: ''
  name: percentComplete
  type: decimal
- container: ''
  name: taxId
  type: ''
- container: set
  name: jobs
  type: ''
property_count: 21
provider_name: CMiC
provider_slug: cmic
slug: cmic-context
tags:
- Construction
- ERP
- Finance
- Project Management
- JSON-LD
- Linked Data
- Semantic Web
---
