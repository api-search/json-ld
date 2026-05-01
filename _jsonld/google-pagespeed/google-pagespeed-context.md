---
api_specs:
- filename: pagespeed-insights-openapi.yml
  format: yaml
  label: PageSpeed Insights API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-pagespeed/refs/heads/main/openapi/pagespeed-insights-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-pagespeed-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-pagespeed/refs/heads/main/json-ld/google-pagespeed-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Pagespeed from Google PageSpeed.
layout: jsonld
name: Google Pagespeed Context
namespaces:
- prefix: psi
  uri: https://googleapis.com/pagespeedonline/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: PageSpeedResult
  type: ''
- container: ''
  name: CoreWebVitals
  type: ''
- container: ''
  name: LighthouseAudit
  type: ''
property_count: 3
provider_name: Google PageSpeed
provider_slug: google-pagespeed
slug: google-pagespeed-context
source_filename: google-pagespeed-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"psi\": \"https://googleapis.com/pagespeedonline/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"PageSpeedResult\": {\n      \"@id\": \"psi:PageSpeedResult\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"analysisTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"performanceScore\": \"psi:performanceScore\",\n        \"accessibilityScore\": \"psi:accessibilityScore\",\n        \"seoScore\": \"psi:seoScore\",\n        \"bestPracticesScore\": \"psi:bestPracticesScore\"\n      }\n    },\n\n    \"CoreWebVitals\": {\n      \"@id\": \"psi:CoreWebVitals\",\n      \"@context\": {\n        \"largestContentfulPaint\": \"psi:largestContentfulPaint\",\n        \"firstInputDelay\"\
  : \"psi:firstInputDelay\",\n        \"cumulativeLayoutShift\": \"psi:cumulativeLayoutShift\",\n        \"interactionToNextPaint\": \"psi:interactionToNextPaint\",\n        \"firstContentfulPaint\": \"psi:firstContentfulPaint\",\n        \"category\": \"psi:overallCategory\"\n      }\n    },\n\n    \"LighthouseAudit\": {\n      \"@id\": \"psi:LighthouseAudit\",\n      \"@context\": {\n        \"auditId\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"score\": \"psi:auditScore\",\n        \"displayValue\": \"psi:displayValue\",\n        \"numericValue\": \"psi:numericValue\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-pagespeed/refs/heads/main/json-ld/google-pagespeed-context.jsonld
tags:
- Core Web Vitals
- Google
- Lighthouse
- Page Speed
- SEO
- Web Performance
- JSON-LD
- Linked Data
- Semantic Web
---
