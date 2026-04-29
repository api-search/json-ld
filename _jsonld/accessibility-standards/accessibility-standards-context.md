---
class_count: 7
classes:
- AriaRole
- WcagConformanceReport
- WcagSuccessCriterion
- description
- name
- url
- version
context_file: json-ld/accessibility-standards-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-ld/accessibility-standards-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Accessibility Standards from Accessibility Standards.
layout: jsonld
name: Accessibility Standards Context
namespaces:
- prefix: a11y
  uri: https://www.w3.org/WAI/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: category
  type: string
- container: ''
  name: conformanceLevel
  type: string
- container: ''
  name: criterionId
  type: string
- container: ''
  name: element
  type: string
- container: ''
  name: evaluationDate
  type: date
- container: ''
  name: evaluator
  type: string
- container: ''
  name: guideline
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: implicitAriaSemantics
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: principle
  type: string
- container: ''
  name: remediation
  type: string
- container: set
  name: requiredStates
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: specUrl
  type: reference
- container: ''
  name: standard
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subject
  type: reference
- container: set
  name: superclassRole
  type: string
- container: set
  name: supportedProperties
  type: string
- container: set
  name: techniques
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: understanding
  type: reference
- container: set
  name: violations
  type: string
property_count: 24
provider_name: Accessibility Standards
provider_slug: accessibility-standards
slug: accessibility-standards-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"a11y\": \"https://www.w3.org/WAI/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AriaRole\": \"a11y:AriaRole\",\n    \"WcagConformanceReport\": \"a11y:WcagConformanceReport\",\n    \"WcagSuccessCriterion\": \"a11y:WcagSuccessCriterion\",\n    \"category\": {\n      \"@id\": \"a11y:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conformanceLevel\": {\n      \"@id\": \"a11y:conformanceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"criterionId\": {\n      \"@id\": \"a11y:criterionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"element\": {\n      \"@id\": \"a11y:element\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluationDate\": {\n      \"@id\": \"a11y:evaluationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"evaluator\": {\n\
  \      \"@id\": \"a11y:evaluator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guideline\": {\n      \"@id\": \"a11y:guideline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"a11y:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"implicitAriaSemantics\": {\n      \"@id\": \"a11y:implicitAriaSemantics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"a11y:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"principle\": {\n      \"@id\": \"a11y:principle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"a11y:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiredStates\": {\n      \"@id\": \"a11y:requiredStates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"a11y:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specUrl\": {\n      \"@id\": \"a11y:specUrl\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"standard\": {\n      \"@id\": \"a11y:standard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"a11y:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"a11y:subject\",\n      \"@type\": \"@id\"\n    },\n    \"superclassRole\": {\n      \"@id\": \"a11y:superclassRole\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedProperties\": {\n      \"@id\": \"a11y:supportedProperties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"techniques\": {\n      \"@id\": \"a11y:techniques\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"a11y:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"understanding\": {\n      \"@id\": \"a11y:understanding\",\n      \"@type\": \"@id\"\n    },\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\"\
  ,\n    \"violations\": {\n      \"@id\": \"a11y:violations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-ld/accessibility-standards-context.jsonld
tags:
- Accessibility
- Compliance
- UX
- Web Standards
- WCAG
- ARIA
- Section 508
- Disability
- JSON-LD
- Linked Data
- Semantic Web
---
