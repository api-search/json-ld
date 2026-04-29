---
class_count: 0
classes: []
context_file: json-ld/amazon-textract-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-textract/refs/heads/main/json-ld/amazon-textract-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Textract from Amazon Textract.
layout: jsonld
name: Amazon Textract Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/textract/schemas/
- prefix: textract
  uri: https://docs.aws.amazon.com/textract/latest/dg/API_Reference.html#
properties:
- container: ''
  name: DocumentAnalysis
  type: ''
- container: ''
  name: Block
  type: ''
- container: ''
  name: Geometry
  type: ''
- container: ''
  name: BoundingBox
  type: ''
- container: ''
  name: DocumentMetadata
  type: ''
- container: ''
  name: ExpenseDocument
  type: ''
- container: ''
  name: IdentityDocument
  type: ''
- container: ''
  name: Query
  type: ''
property_count: 8
provider_name: Amazon Textract
provider_slug: amazon-textract
slug: amazon-textract-context
source_filename: amazon-textract-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/textract/schemas/\",\n    \"textract\": \"https://docs.aws.amazon.com/textract/latest/dg/API_Reference.html#\",\n    \"DocumentAnalysis\": {\n      \"@id\": \"aws:DocumentAnalysis\",\n      \"@context\": {\n        \"DocumentMetadata\": \"aws:documentMetadata\",\n        \"Blocks\": \"aws:Block\",\n        \"AnalyzeDocumentModelVersion\": \"schema:softwareVersion\"\n      }\n    },\n    \"Block\": {\n      \"@id\": \"aws:Block\",\n      \"@context\": {\n        \"BlockType\": \"schema:additionalType\",\n        \"Confidence\": \"aws:confidence\",\n        \"Text\": \"schema:text\",\n        \"TextType\": \"aws:textType\",\n        \"Id\": \"schema:identifier\",\n        \"Geometry\": \"aws:Geometry\",\n        \"Relationships\": \"aws:relationships\",\n        \"Page\": \"schema:pagination\",\n        \"EntityTypes\": \"aws:entityTypes\",\n        \"SelectionStatus\": \"aws:selectionStatus\"\
  \n      }\n    },\n    \"Geometry\": {\n      \"@id\": \"aws:Geometry\",\n      \"@context\": {\n        \"BoundingBox\": \"aws:BoundingBox\",\n        \"Polygon\": \"aws:polygon\"\n      }\n    },\n    \"BoundingBox\": {\n      \"@id\": \"aws:BoundingBox\",\n      \"@context\": {\n        \"Width\": \"schema:width\",\n        \"Height\": \"schema:height\",\n        \"Left\": \"aws:left\",\n        \"Top\": \"aws:top\"\n      }\n    },\n    \"DocumentMetadata\": {\n      \"@id\": \"aws:DocumentMetadata\",\n      \"@context\": {\n        \"Pages\": \"schema:numberOfPages\"\n      }\n    },\n    \"ExpenseDocument\": {\n      \"@id\": \"aws:ExpenseDocument\",\n      \"@context\": {\n        \"ExpenseIndex\": \"schema:position\",\n        \"SummaryFields\": \"aws:summaryFields\",\n        \"LineItemGroups\": \"aws:lineItemGroups\"\n      }\n    },\n    \"IdentityDocument\": {\n      \"@id\": \"aws:IdentityDocument\",\n      \"@context\": {\n        \"DocumentIndex\": \"schema:position\",\n\
  \        \"IdentityDocumentFields\": \"aws:identityDocumentFields\"\n      }\n    },\n    \"Query\": {\n      \"@id\": \"aws:Query\",\n      \"@context\": {\n        \"Text\": \"schema:text\",\n        \"Alias\": \"schema:alternateName\",\n        \"Pages\": \"aws:pages\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-textract/refs/heads/main/json-ld/amazon-textract-context.jsonld
tags:
- AWS
- Document Processing
- Machine Learning
- OCR
- JSON-LD
- Linked Data
- Semantic Web
---
