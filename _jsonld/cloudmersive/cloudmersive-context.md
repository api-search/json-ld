---
api_specs:
- filename: virus
  format: yaml
  label: Cloudmersive Virus Scan API
  slug: cloudmersive-virus-scan-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/virus
- filename: security
  format: yaml
  label: Cloudmersive Security Threat Detection API
  slug: cloudmersive-security-threat-detection-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/security
- filename: spam
  format: yaml
  label: Cloudmersive Spam Detection API
  slug: cloudmersive-spam-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/spam
- filename: phishing
  format: yaml
  label: Cloudmersive Phishing Detection API
  slug: cloudmersive-phishing-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/phishing
- filename: cdr
  format: yaml
  label: Cloudmersive Content Disarm and Reconstruction (CDR) API
  slug: cloudmersive-cdr-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/cdr
- filename: fraud
  format: yaml
  label: Cloudmersive Fraud Detection API
  slug: cloudmersive-fraud-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/fraud
- filename: dlp
  format: yaml
  label: Cloudmersive Data Loss Prevention (DLP) API
  slug: cloudmersive-dlp-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/dlp
- filename: convert
  format: yaml
  label: Cloudmersive Document Convert API
  slug: cloudmersive-convert-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/convert
- filename: barcode
  format: yaml
  label: Cloudmersive Barcode API
  slug: cloudmersive-barcode-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/barcode
- filename: image
  format: yaml
  label: Cloudmersive Image Recognition and Processing API
  slug: cloudmersive-image-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/image
- filename: nlp
  format: yaml
  label: Cloudmersive Natural Language Processing API
  slug: cloudmersive-nlp-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/nlp
- filename: ocr
  format: yaml
  label: Cloudmersive OCR API
  slug: cloudmersive-ocr-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/ocr
- filename: speech
  format: yaml
  label: Cloudmersive Speech API
  slug: cloudmersive-speech-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/speech
- filename: validate
  format: yaml
  label: Cloudmersive Validate API
  slug: cloudmersive-validate-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/validate
- filename: video
  format: yaml
  label: Cloudmersive Video API
  slug: cloudmersive-video-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/video
- filename: currency
  format: yaml
  label: Cloudmersive Currency API
  slug: cloudmersive-currency-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/currency
- filename: config
  format: yaml
  label: Cloudmersive Configuration API
  slug: cloudmersive-config-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/config
- filename: dataintegration
  format: yaml
  label: Cloudmersive Data Integration API
  slug: cloudmersive-data-integration-api
  spec_type: OpenAPI
  url: https://api-console.cloudmersive.com/swagger/api/dataintegration
class_count: 0
classes: []
context_file: json-ld/cloudmersive-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/json-ld/cloudmersive-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudmersive from Cloudmersive.
layout: jsonld
name: Cloudmersive Context
namespaces:
- prefix: cm
  uri: https://cloudmersive.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: VirusScanResult
  type: ''
- container: ''
  name: Virus
  type: ''
- container: ''
  name: ConvertedDocument
  type: ''
- container: ''
  name: OcrResult
  type: ''
- container: ''
  name: ImageRecognitionResult
  type: ''
- container: ''
  name: ValidationResult
  type: ''
property_count: 6
provider_name: Cloudmersive
provider_slug: cloudmersive
slug: cloudmersive-context
source_filename: cloudmersive-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cm\": \"https://cloudmersive.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"VirusScanResult\": {\n      \"@id\": \"cm:VirusScanResult\",\n      \"@context\": {\n        \"cleanResult\": \"cm:cleanResult\",\n        \"foundViruses\": \"cm:foundViruses\",\n        \"containsExecutable\": \"cm:containsExecutable\",\n        \"containsMacros\": \"cm:containsMacros\",\n        \"containsScript\": \"cm:containsScript\",\n        \"verifiedFileFormat\": \"cm:verifiedFileFormat\"\n      }\n    },\n\n    \"Virus\": {\n      \"@id\": \"cm:Virus\",\n      \"@context\": {\n        \"fileName\": \"schema:name\",\n        \"virusName\": \"cm:virusName\"\n      }\n    },\n\n    \"ConvertedDocument\": {\n      \"@id\": \"cm:ConvertedDocument\",\n      \"@context\": {\n        \"successful\": \"cm:successful\",\n        \"outputContent\"\
  : \"cm:outputContent\",\n        \"outputContentType\": \"schema:encodingFormat\"\n      }\n    },\n\n    \"OcrResult\": {\n      \"@id\": \"cm:OcrResult\",\n      \"@context\": {\n        \"successful\": \"cm:successful\",\n        \"textResult\": \"schema:text\",\n        \"meanConfidenceLevel\": \"cm:meanConfidenceLevel\"\n      }\n    },\n\n    \"ImageRecognitionResult\": {\n      \"@id\": \"cm:ImageRecognitionResult\",\n      \"@context\": {\n        \"successful\": \"cm:successful\",\n        \"objects\": \"cm:objects\",\n        \"labels\": \"cm:labels\"\n      }\n    },\n\n    \"ValidationResult\": {\n      \"@id\": \"cm:ValidationResult\",\n      \"@context\": {\n        \"valid\": \"cm:valid\",\n        \"input\": \"cm:input\",\n        \"messages\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/json-ld/cloudmersive-context.jsonld
tags:
- Barcodes
- Conversions
- Documents
- Image Recognition
- Natural Language
- OCR
- Processing
- Validation
- Virus Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
