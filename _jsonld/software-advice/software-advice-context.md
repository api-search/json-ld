---
class_count: 0
classes: []
context_file: json-ld/software-advice-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-advice/refs/heads/main/json-ld/software-advice-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Advice from Software Advice.
layout: jsonld
name: Software Advice Context
namespaces:
- prefix: sa
  uri: https://www.softwareadvice.com/ns#
properties:
- container: ''
  name: Review
  type: reference
- container: ''
  name: SoftwareProduct
  type: reference
- container: ''
  name: reviewTitle
  type: ''
- container: ''
  name: reviewBody
  type: ''
- container: ''
  name: rating
  type: decimal
- container: ''
  name: product
  type: ''
- container: ''
  name: reviewer
  type: ''
- container: ''
  name: verified
  type: boolean
- container: ''
  name: pros
  type: ''
- container: ''
  name: cons
  type: ''
- container: ''
  name: industry
  type: ''
- container: ''
  name: companySize
  type: ''
- container: ''
  name: easeOfUse
  type: decimal
- container: ''
  name: features
  type: decimal
- container: ''
  name: customerSupport
  type: decimal
- container: ''
  name: valueForMoney
  type: decimal
- container: ''
  name: category
  type: ''
- container: ''
  name: vendor
  type: ''
- container: ''
  name: SoftwareAdvice
  type: reference
property_count: 19
provider_name: Software Advice
provider_slug: software-advice
slug: software-advice-context
source_filename: software-advice-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sa\": \"https://www.softwareadvice.com/ns#\",\n    \"Review\": {\n      \"@id\": \"schema:Review\",\n      \"@type\": \"@id\"\n    },\n    \"SoftwareProduct\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"reviewTitle\": {\n      \"@id\": \"schema:name\"\n    },\n    \"reviewBody\": {\n      \"@id\": \"schema:reviewBody\"\n    },\n    \"rating\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"product\": {\n      \"@id\": \"schema:itemReviewed\"\n    },\n    \"reviewer\": {\n      \"@id\": \"schema:author\"\n    },\n    \"verified\": {\n      \"@id\": \"sa:verified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pros\": {\n      \"@id\": \"sa:pros\"\n    },\n    \"cons\": {\n      \"@id\": \"sa:cons\"\n    },\n    \"industry\": {\n      \"@id\": \"schema:industry\"\n    },\n    \"companySize\": {\n      \"@id\": \"\
  schema:numberOfEmployees\"\n    },\n    \"easeOfUse\": {\n      \"@id\": \"sa:easeOfUse\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"features\": {\n      \"@id\": \"sa:features\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"customerSupport\": {\n      \"@id\": \"sa:customerSupport\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"valueForMoney\": {\n      \"@id\": \"sa:valueForMoney\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"category\": {\n      \"@id\": \"schema:applicationCategory\"\n    },\n    \"vendor\": {\n      \"@id\": \"schema:provider\"\n    },\n    \"SoftwareAdvice\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-advice/refs/heads/main/json-ld/software-advice-context.jsonld
tags:
- B2B
- Software Recommendations
- Software Reviews
- Analytics
- Gartner
- JSON-LD
- Linked Data
- Semantic Web
---
