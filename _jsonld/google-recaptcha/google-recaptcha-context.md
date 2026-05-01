---
api_specs:
- filename: recaptcha-enterprise-openapi.yml
  format: yaml
  label: reCAPTCHA Enterprise API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/openapi/recaptcha-enterprise-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-recaptcha-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/json-ld/google-recaptcha-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Recaptcha from Google reCAPTCHA.
layout: jsonld
name: Google Recaptcha Context
namespaces:
- prefix: recaptcha
  uri: https://cloud.google.com/recaptcha-enterprise/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Assessment
  type: ''
- container: ''
  name: Key
  type: ''
- container: ''
  name: Event
  type: ''
property_count: 3
provider_name: Google reCAPTCHA
provider_slug: google-recaptcha
slug: google-recaptcha-context
source_filename: google-recaptcha-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"recaptcha\": \"https://cloud.google.com/recaptcha-enterprise/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Assessment\": {\n      \"@id\": \"recaptcha:Assessment\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"score\": \"recaptcha:riskScore\",\n        \"reasons\": \"recaptcha:riskReasons\",\n        \"valid\": \"recaptcha:tokenValid\",\n        \"action\": \"recaptcha:action\",\n        \"hostname\": \"recaptcha:hostname\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Key\": {\n      \"@id\": \"recaptcha:Key\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"displayName\": \"schema:name\",\n        \"integrationType\": \"recaptcha:integrationType\",\n   \
  \     \"allowedDomains\": \"recaptcha:allowedDomains\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"recaptcha:Event\",\n      \"@context\": {\n        \"token\": \"recaptcha:token\",\n        \"siteKey\": \"recaptcha:siteKey\",\n        \"userAgent\": \"recaptcha:userAgent\",\n        \"userIpAddress\": \"recaptcha:userIpAddress\",\n        \"expectedAction\": \"recaptcha:expectedAction\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/json-ld/google-recaptcha-context.jsonld
tags:
- Abuse Prevention
- Bot Detection
- CAPTCHA
- Fraud Prevention
- Google Cloud
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
