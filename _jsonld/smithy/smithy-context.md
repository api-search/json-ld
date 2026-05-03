---
class_count: 26
classes:
- Model
- Shape
- Trait
- Service
- Operation
- Resource
- smithy:version
- smithy:shapes
- smithy:type
- smithy:traits
- smithy:members
- smithy:target
- smithy:input
- smithy:output
- smithy:errors
- smithy:operations
- smithy:resources
- smithy:version-field
- smithy:metadata
- smithy:namespace
- smithy:protocol
- smithy:shapeId
- smithy:documentation
- smithy:required
- smithy:httpMethod
- smithy:httpUri
context_file: json-ld/smithy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smithy/refs/heads/main/json-ld/smithy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smithy from Smithy.
layout: jsonld
name: Smithy Context
namespaces:
- prefix: smithy
  uri: https://smithy.io/vocab#
properties: []
property_count: 0
provider_name: Smithy
provider_slug: smithy
slug: smithy-context
source_filename: smithy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"smithy\": \"https://smithy.io/vocab#\",\n    \"Model\": \"SoftwareSourceCode\",\n    \"Shape\": \"smithy:Shape\",\n    \"Trait\": \"smithy:Trait\",\n    \"Service\": \"WebAPI\",\n    \"Operation\": \"EntryPoint\",\n    \"Resource\": \"smithy:Resource\",\n    \"smithy:version\": \"softwareVersion\",\n    \"smithy:shapes\": \"hasPart\",\n    \"smithy:type\": \"additionalType\",\n    \"smithy:traits\": \"smithy:traits\",\n    \"smithy:members\": \"smithy:members\",\n    \"smithy:target\": \"smithy:target\",\n    \"smithy:input\": \"smithy:input\",\n    \"smithy:output\": \"smithy:output\",\n    \"smithy:errors\": \"smithy:errors\",\n    \"smithy:operations\": \"potentialAction\",\n    \"smithy:resources\": \"hasPart\",\n    \"smithy:version-field\": \"version\",\n    \"smithy:metadata\": \"additionalProperty\",\n    \"smithy:namespace\": \"identifier\",\n    \"smithy:protocol\": \"encodingFormat\",\n    \"smithy:shapeId\"\
  : \"@id\",\n    \"smithy:documentation\": \"description\",\n    \"smithy:required\": \"valueRequired\",\n    \"smithy:httpMethod\": \"httpMethod\",\n    \"smithy:httpUri\": \"url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smithy/refs/heads/main/json-ld/smithy-context.jsonld
tags:
- Code Generation
- IDL
- SDKs
- API Design
- Interface Definition Language
- Toolchain
- JSON-LD
- Linked Data
- Semantic Web
---
