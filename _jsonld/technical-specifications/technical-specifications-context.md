---
class_count: 36
classes:
- Specification
- specificationId
- specificationName
- specificationDescription
- specificationVersion
- specificationUrl
- specificationStatus
- specificationAuthority
- OpenAPISpecification
- AsyncAPISpecification
- JSONSchema
- GraphQLSpecification
- gRPCSpecification
- RAMLSpecification
- SpecificationVersion
- versionNumber
- releaseDate
- isCurrentVersion
- previousVersion
- ConformanceLevel
- levelName
- levelDescription
- levelRequirements
- DataFormat
- formatName
- formatMimeType
- formatExtension
- Protocol
- protocolName
- protocolPort
- protocolScheme
- Implementation
- implementationName
- implementationUrl
- implementationLanguage
- implementationLicense
context_file: json-ld/technical-specifications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/technical-specifications/refs/heads/main/json-ld/technical-specifications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Technical Specifications from Technical Specifications.
layout: jsonld
name: Technical Specifications Context
namespaces:
- prefix: spec
  uri: https://raw.githubusercontent.com/api-evangelist/technical-specifications/main/json-ld/technical-specifications-context.jsonld#
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Technical Specifications
provider_slug: technical-specifications
slug: technical-specifications-context
source_filename: technical-specifications-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spec\": \"https://raw.githubusercontent.com/api-evangelist/technical-specifications/main/json-ld/technical-specifications-context.jsonld#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Specification\": \"schema:TechArticle\",\n    \"specificationId\": \"schema:identifier\",\n    \"specificationName\": \"schema:name\",\n    \"specificationDescription\": \"schema:description\",\n    \"specificationVersion\": \"schema:version\",\n    \"specificationUrl\": \"schema:url\",\n    \"specificationStatus\": \"spec:status\",\n    \"specificationAuthority\": \"schema:publisher\",\n\n    \"OpenAPISpecification\": \"spec:OpenAPISpecification\",\n    \"AsyncAPISpecification\": \"spec:AsyncAPISpecification\",\n    \"JSONSchema\": \"spec:JSONSchema\",\n    \"GraphQLSpecification\": \"spec:GraphQLSpecification\",\n    \"gRPCSpecification\": \"spec:gRPCSpecification\",\n    \"RAMLSpecification\": \"spec:RAMLSpecification\"\
  ,\n\n    \"SpecificationVersion\": \"spec:SpecificationVersion\",\n    \"versionNumber\": \"schema:version\",\n    \"releaseDate\": \"schema:datePublished\",\n    \"isCurrentVersion\": \"spec:isCurrentVersion\",\n    \"previousVersion\": \"schema:previousItem\",\n\n    \"ConformanceLevel\": \"spec:ConformanceLevel\",\n    \"levelName\": \"schema:name\",\n    \"levelDescription\": \"schema:description\",\n    \"levelRequirements\": \"spec:requirements\",\n\n    \"DataFormat\": \"spec:DataFormat\",\n    \"formatName\": \"schema:name\",\n    \"formatMimeType\": \"schema:encodingFormat\",\n    \"formatExtension\": \"spec:fileExtension\",\n\n    \"Protocol\": \"spec:Protocol\",\n    \"protocolName\": \"schema:name\",\n    \"protocolPort\": \"spec:port\",\n    \"protocolScheme\": \"spec:scheme\",\n\n    \"Implementation\": \"schema:SoftwareApplication\",\n    \"implementationName\": \"schema:name\",\n    \"implementationUrl\": \"schema:url\",\n    \"implementationLanguage\": \"schema:programmingLanguage\"\
  ,\n    \"implementationLicense\": \"schema:license\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/technical-specifications/refs/heads/main/json-ld/technical-specifications-context.jsonld
tags:
- Documentation
- Engineering
- Requirements
- Specifications
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
