---
api_specs:
- filename: uipath-orchestrator-openapi.yml
  format: yaml
  label: UiPath Orchestrator API
  slug: uipath-orchestrator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-orchestrator-openapi.yml
- filename: uipath-automation-hub-openapi.yml
  format: yaml
  label: UiPath Automation Hub API
  slug: uipath-automation-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-automation-hub-openapi.yml
- filename: uipath-document-understanding-openapi.yml
  format: yaml
  label: UiPath Document Understanding API
  slug: uipath-document-understanding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-document-understanding-openapi.yml
- filename: uipath-data-service-openapi.yml
  format: yaml
  label: UiPath Data Service API
  slug: uipath-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-data-service-openapi.yml
- filename: uipath-platform-management-openapi.yml
  format: yaml
  label: UiPath Platform Management API
  slug: uipath-platform-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-platform-management-openapi.yml
- filename: uipath-test-manager-openapi.yml
  format: yaml
  label: UiPath Test Manager API
  slug: uipath-test-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-test-manager-openapi.yml
class_count: 19
classes:
- AsyncJobStartResponse
- ClassificationRequest
- ClassificationResultItem
- ClassificationResult
- ClassifierOption
- Classifier
- DigitizationRequest
- DigitizationResult
- ExtractedField
- ExtractionRequest
- ExtractionResultData
- ExtractionResult
- ExtractorOption
- Extractor
- FieldValue
- Project
- ValidationRequest
- name
- description
context_file: json-ld/uipath-document-understanding-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-document-understanding-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath Document Understanding from UiPath.
layout: jsonld
name: Uipath Document Understanding Context
namespaces:
- prefix: uipath
  uri: https://uipath.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: requestId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: documentId
  type: string
- container: set
  name: classifiersOptions
  type: string
- container: ''
  name: classifierId
  type: string
- container: ''
  name: documentTypeId
  type: string
- container: ''
  name: confidence
  type: float
- container: ''
  name: startPage
  type: integer
- container: ''
  name: endPage
  type: integer
- container: ''
  name: result
  type: reference
- container: set
  name: classificationResults
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: classifierType
  type: string
- container: set
  name: documentTypes
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: documentBase64
  type: string
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: FieldId
  type: string
- container: ''
  name: FieldName
  type: string
- container: ''
  name: IsMissing
  type: boolean
- container: ''
  name: Value
  type: string
- container: set
  name: extractorsOptions
  type: string
- container: ''
  name: ResultsVersion
  type: integer
- container: ''
  name: DocumentId
  type: string
- container: set
  name: Fields
  type: string
- container: ''
  name: extractionResult
  type: string
- container: ''
  name: extractorId
  type: string
- container: ''
  name: documentType
  type: string
- container: ''
  name: extractorType
  type: string
- container: ''
  name: Confidence
  type: float
- container: ''
  name: OcrConfidence
  type: float
- container: ''
  name: TextType
  type: string
- container: ''
  name: extractorsUrl
  type: reference
- container: ''
  name: classifiersUrl
  type: reference
- container: ''
  name: classificationResult
  type: string
property_count: 35
provider_name: UiPath
provider_slug: uipath
slug: uipath-document-understanding-context
source_filename: uipath-document-understanding-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AsyncJobStartResponse\": \"uipath:AsyncJobStartResponse\",\n    \"ClassificationRequest\": \"uipath:ClassificationRequest\",\n    \"ClassificationResultItem\": \"uipath:ClassificationResultItem\",\n    \"ClassificationResult\": \"uipath:ClassificationResult\",\n    \"ClassifierOption\": \"uipath:ClassifierOption\",\n    \"Classifier\": \"uipath:Classifier\",\n    \"DigitizationRequest\": \"uipath:DigitizationRequest\",\n    \"DigitizationResult\": \"uipath:DigitizationResult\",\n    \"ExtractedField\": \"uipath:ExtractedField\",\n    \"ExtractionRequest\": \"uipath:ExtractionRequest\",\n    \"ExtractionResultData\": \"uipath:ExtractionResultData\",\n    \"ExtractionResult\": \"uipath:ExtractionResult\",\n    \"ExtractorOption\": \"uipath:ExtractorOption\"\
  ,\n    \"Extractor\": \"uipath:Extractor\",\n    \"FieldValue\": \"uipath:FieldValue\",\n    \"Project\": \"uipath:Project\",\n    \"ValidationRequest\": \"uipath:ValidationRequest\",\n    \"requestId\": {\n      \"@id\": \"uipath:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"uipath:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentId\": {\n      \"@id\": \"uipath:documentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classifiersOptions\": {\n      \"@id\": \"uipath:classifiersOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classifierId\": {\n      \"@id\": \"uipath:classifierId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentTypeId\": {\n      \"@id\": \"uipath:documentTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confidence\": {\n      \"@id\": \"uipath:confidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"startPage\": {\n      \"@id\": \"uipath:startPage\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"endPage\": {\n      \"@id\": \"uipath:endPage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"result\": {\n      \"@id\": \"uipath:result\",\n      \"@type\": \"@id\"\n    },\n    \"classificationResults\": {\n      \"@id\": \"uipath:classificationResults\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"uipath:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"classifierType\": {\n      \"@id\": \"uipath:classifierType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentTypes\": {\n      \"@id\": \"uipath:documentTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"uipath:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentBase64\": {\n      \"@id\": \"uipath:documentBase64\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageCount\": {\n\
  \      \"@id\": \"uipath:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"FieldId\": {\n      \"@id\": \"uipath:FieldId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FieldName\": {\n      \"@id\": \"uipath:FieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsMissing\": {\n      \"@id\": \"uipath:IsMissing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Value\": {\n      \"@id\": \"uipath:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extractorsOptions\": {\n      \"@id\": \"uipath:extractorsOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultsVersion\": {\n      \"@id\": \"uipath:ResultsVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DocumentId\": {\n      \"@id\": \"uipath:DocumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Fields\": {\n      \"@id\": \"uipath:Fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extractionResult\": {\n   \
  \   \"@id\": \"uipath:extractionResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extractorId\": {\n      \"@id\": \"uipath:extractorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentType\": {\n      \"@id\": \"uipath:documentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extractorType\": {\n      \"@id\": \"uipath:extractorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Confidence\": {\n      \"@id\": \"uipath:Confidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"OcrConfidence\": {\n      \"@id\": \"uipath:OcrConfidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"TextType\": {\n      \"@id\": \"uipath:TextType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"extractorsUrl\": {\n      \"@id\": \"uipath:extractorsUrl\",\n      \"@type\": \"@id\"\n    },\n    \"classifiersUrl\": {\n      \"@id\": \"uipath:classifiersUrl\",\n      \"@type\": \"@id\"\n    },\n    \"classificationResult\": {\n\
  \      \"@id\": \"uipath:classificationResult\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-document-understanding-context.jsonld
tags:
- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
