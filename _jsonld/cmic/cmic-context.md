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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cmic\": \"https://api.cmic.ca/rest/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": {\n      \"@id\": \"cmic:Project\",\n      \"@type\": \"schema:Project\"\n    },\n    \"Job\": {\n      \"@id\": \"cmic:Job\",\n      \"@type\": \"schema:JobPosting\"\n    },\n    \"CostCode\": {\n      \"@id\": \"cmic:CostCode\"\n    },\n    \"Vendor\": {\n      \"@id\": \"cmic:Vendor\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"Equipment\": {\n      \"@id\": \"cmic:Equipment\",\n      \"@type\": \"schema:Product\"\n    },\n    \"Document\": {\n      \"@id\": \"cmic:Document\",\n      \"@type\": \"schema:DigitalDocument\"\n    },\n\n    \"projectId\": \"@id\",\n    \"projectName\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"companyCode\": {\n      \"@id\": \"cmic:companyCode\"\
  \n    },\n    \"status\": {\n      \"@id\": \"schema:eventStatus\"\n    },\n    \"projectManager\": {\n      \"@id\": \"schema:employee\",\n      \"@type\": \"schema:Person\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:client\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"contractAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"originalBudget\": {\n      \"@id\": \"cmic:originalBudget\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"revisedBudget\": {\n      \"@id\": \"cmic:revisedBudget\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"actualCost\": {\n      \"@id\": \"cmic:actualCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"committedCost\": {\n      \"@id\": \"cmic:committedCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"percentComplete\": {\n      \"@id\": \"schema:percentComplete\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vendorName\": \"schema:name\",\n    \"taxId\": {\n      \"@id\": \"schema:taxID\"\n    },\n    \"jobs\": {\n      \"@id\": \"cmic:hasJob\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/json-ld/cmic-context.jsonld
tags:
- Construction
- ERP
- Finance
- Project Management
- JSON-LD
- Linked Data
- Semantic Web
---
