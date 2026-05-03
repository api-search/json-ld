---
class_count: 6
classes:
- SuccessCriterion
- ConformanceClaim
- Guideline
- Principle
- Technique
- TestResult
context_file: json-ld/wcag-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wcag/refs/heads/main/json-ld/wcag-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wcag from WCAG.
layout: jsonld
name: Wcag Context
namespaces:
- prefix: wcag
  uri: https://www.w3.org/WAI/standards/wcag/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: earl
  uri: http://www.w3.org/ns/earl#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: level
  type: string
- container: ''
  name: principle
  type: string
- container: ''
  name: guideline
  type: string
- container: ''
  name: wcagVersion
  type: string
- container: ''
  name: understandingUrl
  type: reference
- container: set
  name: sufficientTechniques
  type: string
- container: set
  name: failures
  type: string
- container: ''
  name: claimDate
  type: date
- container: ''
  name: conformanceLevel
  type: string
- container: ''
  name: scopeUrl
  type: reference
- container: ''
  name: scopeDescription
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: evaluationApproach
  type: string
- container: set
  name: knownLimitations
  type: string
- container: ''
  name: contactUrl
  type: reference
property_count: 19
provider_name: WCAG
provider_slug: wcag
slug: wcag-context
source_filename: wcag-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wcag\": \"https://www.w3.org/WAI/standards/wcag/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"earl\": \"http://www.w3.org/ns/earl#\",\n\n    \"SuccessCriterion\": \"wcag:SuccessCriterion\",\n    \"ConformanceClaim\": \"wcag:ConformanceClaim\",\n    \"Guideline\": \"wcag:Guideline\",\n    \"Principle\": \"wcag:Principle\",\n    \"Technique\": \"wcag:Technique\",\n    \"TestResult\": \"earl:TestResult\",\n\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"level\": {\n      \"@id\": \"\
  wcag:conformanceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principle\": {\n      \"@id\": \"wcag:principle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guideline\": {\n      \"@id\": \"wcag:guideline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wcagVersion\": {\n      \"@id\": \"wcag:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"understandingUrl\": {\n      \"@id\": \"wcag:understandingUrl\",\n      \"@type\": \"@id\"\n    },\n    \"sufficientTechniques\": {\n      \"@id\": \"wcag:sufficientTechniques\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failures\": {\n      \"@id\": \"wcag:failures\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"conformanceLevel\": {\n      \"@id\": \"wcag:conformanceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scopeUrl\": {\n      \"@id\"\
  : \"wcag:scopeUrl\",\n      \"@type\": \"@id\"\n    },\n    \"scopeDescription\": {\n      \"@id\": \"wcag:scopeDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"schema:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluationApproach\": {\n      \"@id\": \"wcag:evaluationApproach\",\n      \"@type\": \"xsd:string\"\n    },\n    \"knownLimitations\": {\n      \"@id\": \"wcag:knownLimitations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactUrl\": {\n      \"@id\": \"wcag:contactUrl\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wcag/refs/heads/main/json-ld/wcag-context.jsonld
tags:
- Accessibility
- W3C
- WCAG
- Web Standards
- Disability
- Inclusive Design
- JSON-LD
- Linked Data
- Semantic Web
---
