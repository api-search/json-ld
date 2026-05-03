---
class_count: 11
classes:
- Submission
- Risk
- Coverage
- Quote
- Party
- Document
- submissionId
- name
- description
- taxId
- address
context_file: json-ld/underwriting-standards-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/underwriting-standards/refs/heads/main/json-ld/underwriting-standards-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Underwriting Standards from Underwriting Standards.
layout: jsonld
name: Underwriting Standards Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: uw
  uri: https://github.com/api-evangelist/underwriting-standards/blob/main/json-ld/underwriting-standards-context.jsonld#
properties:
- container: ''
  name: externalReference
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: status
  type: '@vocab'
- container: ''
  name: broker
  type: reference
- container: ''
  name: insured
  type: reference
- container: ''
  name: risk
  type: reference
- container: list
  name: requestedCoverages
  type: ''
- container: list
  name: quotes
  type: ''
- container: list
  name: documents
  type: ''
- container: ''
  name: lineOfBusiness
  type: '@vocab'
- container: ''
  name: naicsCode
  type: string
- container: ''
  name: annualRevenue
  type: decimal
- container: ''
  name: numberOfEmployees
  type: integer
- container: ''
  name: coverageType
  type: string
- container: ''
  name: limitAmount
  type: decimal
- container: ''
  name: deductibleAmount
  type: decimal
- container: ''
  name: premium
  type: decimal
- container: list
  name: conditions
  type: ''
- container: list
  name: exclusions
  type: ''
property_count: 19
provider_name: Underwriting Standards
provider_slug: underwriting-standards
slug: underwriting-standards-context
source_filename: underwriting-standards-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"uw\": \"https://github.com/api-evangelist/underwriting-standards/blob/main/json-ld/underwriting-standards-context.jsonld#\",\n\n    \"Submission\": \"uw:UnderwritingSubmission\",\n    \"Risk\": \"uw:InsuranceRisk\",\n    \"Coverage\": \"uw:Coverage\",\n    \"Quote\": \"uw:UnderwritingQuote\",\n    \"Party\": \"schema:Organization\",\n    \"Document\": \"schema:CreativeWork\",\n\n    \"submissionId\": \"schema:identifier\",\n    \"externalReference\": {\n      \"@id\": \"uw:externalReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"uw:submissionStatus\",\n      \"@type\": \"@vocab\"\n    },\n    \"broker\": {\n      \"@id\"\
  : \"uw:broker\",\n      \"@type\": \"@id\"\n    },\n    \"insured\": {\n      \"@id\": \"uw:insured\",\n      \"@type\": \"@id\"\n    },\n    \"risk\": {\n      \"@id\": \"uw:risk\",\n      \"@type\": \"@id\"\n    },\n    \"requestedCoverages\": {\n      \"@id\": \"uw:requestedCoverages\",\n      \"@container\": \"@list\"\n    },\n    \"quotes\": {\n      \"@id\": \"uw:quotes\",\n      \"@container\": \"@list\"\n    },\n    \"documents\": {\n      \"@id\": \"schema:hasPart\",\n      \"@container\": \"@list\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"taxId\": \"schema:taxID\",\n    \"address\": \"schema:address\",\n    \"lineOfBusiness\": {\n      \"@id\": \"uw:lineOfBusiness\",\n      \"@type\": \"@vocab\"\n    },\n    \"naicsCode\": {\n      \"@id\": \"uw:naicsCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annualRevenue\": {\n      \"@id\": \"schema:annualRevenue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"numberOfEmployees\"\
  : {\n      \"@id\": \"schema:numberOfEmployees\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"coverageType\": {\n      \"@id\": \"uw:coverageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limitAmount\": {\n      \"@id\": \"uw:limitAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deductibleAmount\": {\n      \"@id\": \"uw:deductibleAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"premium\": {\n      \"@id\": \"uw:premium\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"conditions\": {\n      \"@id\": \"uw:conditions\",\n      \"@container\": \"@list\"\n    },\n    \"exclusions\": {\n      \"@id\": \"uw:exclusions\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/underwriting-standards/refs/heads/main/json-ld/underwriting-standards-context.jsonld
tags:
- Underwriting
- Insurance
- Standards
- ACORD
- Data Exchange
- InsurTech
- JSON-LD
- Linked Data
- Semantic Web
---
