---
class_count: 14
classes:
- Organization
- Product
- API
- Publication
- Patent
- Citation
- Trial
- Drug
- Institution
- name
- description
- category
- createdAt
- updatedAt
context_file: json-ld/clarivate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clarivate/refs/heads/main/json-ld/clarivate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clarivate from Clarivate.
layout: jsonld
name: Clarivate Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cv
  uri: https://developer.clarivate.com/vocab/
properties: []
property_count: 0
provider_name: Clarivate
provider_slug: clarivate
slug: clarivate-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/clarivate/\",\n    \"schema\": \"https://schema.org/\",\n    \"cv\": \"https://developer.clarivate.com/vocab/\",\n    \"Organization\": \"schema:Organization\",\n    \"Product\": \"schema:Product\",\n    \"API\": \"schema:WebAPI\",\n    \"Publication\": \"schema:ScholarlyArticle\",\n    \"Patent\": \"cv:Patent\",\n    \"Citation\": \"cv:Citation\",\n    \"Trial\": \"cv:ClinicalTrial\",\n    \"Drug\": \"cv:Drug\",\n    \"Institution\": \"schema:EducationalOrganization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"category\": \"schema:category\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clarivate/refs/heads/main/json-ld/clarivate-context.jsonld
tags:
- Analytics
- Citations
- Data
- Drug Pipeline
- Insights
- Intellectual Property
- Life Sciences
- Patents
- Publications
- Research
- JSON-LD
- Linked Data
- Semantic Web
---
