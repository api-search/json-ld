---
class_count: 13
classes:
- API
- Image
- Garment
- Style
- Category
- Confidence
- Recommendation
- name
- description
- label
- score
- createdAt
- updatedAt
context_file: json-ld/classif-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/classif-io/refs/heads/main/json-ld/classif-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Classif Io from Classif.io.
layout: jsonld
name: Classif Io Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: classif
  uri: https://www.classif.io/vocab/
properties: []
property_count: 0
provider_name: Classif.io
provider_slug: classif-io
slug: classif-io-context
source_filename: classif-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/classif-io/\",\n    \"schema\": \"https://schema.org/\",\n    \"classif\": \"https://www.classif.io/vocab/\",\n    \"API\": \"schema:WebAPI\",\n    \"Image\": \"schema:ImageObject\",\n    \"Garment\": \"classif:Garment\",\n    \"Style\": \"classif:FashionStyle\",\n    \"Category\": \"schema:DefinedTerm\",\n    \"Confidence\": \"classif:ConfidenceScore\",\n    \"Recommendation\": \"classif:OutfitRecommendation\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"label\": \"schema:name\",\n    \"score\": \"classif:confidence\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/classif-io/refs/heads/main/json-ld/classif-io-context.jsonld
tags:
- Apparel
- Classification
- Computer Vision
- Fashion
- Image Recognition
- Machine Learning
- Recommendation
- JSON-LD
- Linked Data
- Semantic Web
---
