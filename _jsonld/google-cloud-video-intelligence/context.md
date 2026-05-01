---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Video Intelligence API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-video-intelligence/refs/heads/main/openapi/openapi.yml
class_count: 13
classes:
- VideoAnnotation
- inputUri
- features
- videoContext
- labelDetection
- shotChangeDetection
- explicitContentDetection
- objectTracking
- textDetection
- outputUri
- name
- description
- url
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-video-intelligence/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Video Intelligence.
layout: jsonld
name: context Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/video-intelligence#
properties: []
property_count: 0
provider_name: Google Cloud Video Intelligence
provider_slug: google-cloud-video-intelligence
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/video-intelligence#\",\n    \"VideoAnnotation\": \"gcp:VideoAnnotation\",\n    \"inputUri\": \"gcp:inputUri\",\n    \"features\": \"gcp:features\",\n    \"videoContext\": \"gcp:videoContext\",\n    \"labelDetection\": \"gcp:labelDetection\",\n    \"shotChangeDetection\": \"gcp:shotChangeDetection\",\n    \"explicitContentDetection\": \"gcp:explicitContentDetection\",\n    \"objectTracking\": \"gcp:objectTracking\",\n    \"textDetection\": \"gcp:textDetection\",\n    \"outputUri\": \"gcp:outputUri\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-video-intelligence/refs/heads/main/json-ld/context.jsonld
tags:
- Content Moderation
- Google Cloud
- Machine Learning
- Object Detection
- Video Analysis
- Video Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
