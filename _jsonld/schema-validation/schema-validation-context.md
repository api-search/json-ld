---
class_count: 25
classes:
- SchemaValidator
- ValidationRule
- ValidationResult
- ValidationError
- JSONSchema
- OpenAPISpec
- SchemaValidationConfig
- name
- description
- url
- version
- codeRepository
- documentation
- license
- programmingLanguage
- softwareVersion
- validationDraft
- severity
- given
- ruleName
- errorMessage
- isValid
- SoftwareApplication
- SoftwareLibrary
- APIReference
context_file: json-ld/schema-validation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-ld/schema-validation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schema Validation from Schema Validation.
layout: jsonld
name: Schema Validation Context
namespaces:
- prefix: validation
  uri: https://json-schema.org/vocab/validation#
- prefix: openapi
  uri: https://spec.openapis.org/oas/v3.1/vocab#
properties:
- container: ''
  name: validates
  type: reference
property_count: 1
provider_name: Schema Validation
provider_slug: schema-validation
slug: schema-validation-context
source_filename: schema-validation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"validation\": \"https://json-schema.org/vocab/validation#\",\n    \"openapi\": \"https://spec.openapis.org/oas/v3.1/vocab#\",\n\n    \"SchemaValidator\": \"validation:SchemaValidator\",\n    \"ValidationRule\": \"validation:ValidationRule\",\n    \"ValidationResult\": \"validation:ValidationResult\",\n    \"ValidationError\": \"validation:ValidationError\",\n    \"JSONSchema\": \"validation:JSONSchema\",\n    \"OpenAPISpec\": \"openapi:OpenAPIDocument\",\n    \"SchemaValidationConfig\": \"validation:SchemaValidationConfig\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"documentation\": \"schema:documentation\",\n    \"license\": \"schema:license\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"softwareVersion\": \"schema:softwareVersion\"\
  ,\n\n    \"validates\": {\n      \"@id\": \"validation:validates\",\n      \"@type\": \"@id\"\n    },\n    \"validationDraft\": \"validation:jsonSchemaDraft\",\n    \"severity\": \"validation:severity\",\n    \"given\": \"validation:jsonPath\",\n    \"ruleName\": \"validation:ruleName\",\n    \"errorMessage\": \"validation:errorMessage\",\n    \"isValid\": \"validation:isValid\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareLibrary\": \"schema:SoftwareApplication\",\n    \"APIReference\": \"schema:APIReference\"\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://ajv.js.org/\",\n      \"@type\": [\"SoftwareApplication\", \"SchemaValidator\"],\n      \"name\": \"AJV JSON Schema Validator\",\n      \"description\": \"The fastest JSON Schema validator for JavaScript, supporting all major JSON Schema drafts.\",\n      \"url\": \"https://ajv.js.org/\",\n      \"codeRepository\": \"https://github.com/ajv-validator/ajv\",\n      \"programmingLanguage\": \"\
  JavaScript\"\n    },\n    {\n      \"@id\": \"https://json-schema.hyperjump.io/\",\n      \"@type\": [\"SoftwareApplication\", \"SchemaValidator\"],\n      \"name\": \"Hyperjump JSON Schema\",\n      \"description\": \"Standards-compliant JSON Schema validation and bundling library supporting all drafts and OpenAPI vocabularies.\",\n      \"url\": \"https://json-schema.hyperjump.io/\",\n      \"codeRepository\": \"https://github.com/hyperjump-io/json-schema\",\n      \"programmingLanguage\": \"JavaScript\"\n    },\n    {\n      \"@id\": \"https://stoplight.io/open-source/spectral\",\n      \"@type\": [\"SoftwareApplication\", \"SchemaValidator\"],\n      \"name\": \"Spectral\",\n      \"description\": \"Open-source JSON/YAML linter and schema validator providing customizable rulesets for API governance.\",\n      \"url\": \"https://stoplight.io/open-source/spectral\",\n      \"codeRepository\": \"https://github.com/stoplightio/spectral\",\n      \"programmingLanguage\": \"JavaScript\"\n\
  \    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-ld/schema-validation-context.jsonld
tags:
- API Governance
- Contract Testing
- JSON Schema
- OpenAPI
- Schema Validation
- JSON-LD
- Linked Data
- Semantic Web
---
