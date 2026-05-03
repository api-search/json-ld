---
class_count: 0
classes: []
context_file: json-ld/software-design-architectural-patterns-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-design-architectural-patterns/refs/heads/main/json-ld/software-design-architectural-patterns-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Design Architectural Patterns from Software Design Architectural Patterns.
layout: jsonld
name: Software Design Architectural Patterns Context
namespaces:
- prefix: arch
  uri: https://api-evangelist.github.io/software-design-architectural-patterns/ns#
- prefix: pat
  uri: https://microservices.io/patterns/ns#
properties:
- container: ''
  name: ArchitecturalPattern
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: category
  type: ''
- container: ''
  name: aliases
  type: ''
- container: ''
  name: components
  type: ''
- container: ''
  name: Component
  type: reference
- container: ''
  name: useCases
  type: ''
- container: ''
  name: benefits
  type: ''
- container: ''
  name: tradeoffs
  type: ''
- container: ''
  name: relatedPatterns
  type: ''
- container: ''
  name: MVC
  type: ''
- container: ''
  name: Microservices
  type: ''
- container: ''
  name: CQRS
  type: ''
- container: ''
  name: EventDriven
  type: ''
- container: ''
  name: Hexagonal
  type: ''
- container: ''
  name: Serverless
  type: ''
- container: ''
  name: LayeredArchitecture
  type: ''
property_count: 18
provider_name: Software Design Architectural Patterns
provider_slug: software-design-architectural-patterns
slug: software-design-architectural-patterns-context
source_filename: software-design-architectural-patterns-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"arch\": \"https://api-evangelist.github.io/software-design-architectural-patterns/ns#\",\n    \"pat\": \"https://microservices.io/patterns/ns#\",\n    \"ArchitecturalPattern\": {\n      \"@id\": \"schema:HowTo\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\"\n    },\n    \"aliases\": {\n      \"@id\": \"schema:alternateName\"\n    },\n    \"components\": {\n      \"@id\": \"arch:hasComponent\"\n    },\n    \"Component\": {\n      \"@id\": \"arch:Component\",\n      \"@type\": \"@id\"\n    },\n    \"useCases\": {\n      \"@id\": \"schema:applicationCategory\"\n    },\n    \"benefits\": {\n      \"@id\": \"arch:benefit\"\n    },\n    \"tradeoffs\": {\n      \"@id\": \"arch:tradeoff\"\n    },\n    \"relatedPatterns\": {\n      \"@id\": \"\
  schema:isRelatedTo\"\n    },\n    \"MVC\": {\n      \"@id\": \"arch:MVCPattern\"\n    },\n    \"Microservices\": {\n      \"@id\": \"arch:MicroservicesPattern\"\n    },\n    \"CQRS\": {\n      \"@id\": \"arch:CQRSPattern\"\n    },\n    \"EventDriven\": {\n      \"@id\": \"arch:EventDrivenPattern\"\n    },\n    \"Hexagonal\": {\n      \"@id\": \"arch:HexagonalPattern\"\n    },\n    \"Serverless\": {\n      \"@id\": \"arch:ServerlessPattern\"\n    },\n    \"LayeredArchitecture\": {\n      \"@id\": \"arch:LayeredPattern\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-design-architectural-patterns/refs/heads/main/json-ld/software-design-architectural-patterns-context.jsonld
tags:
- Best Practices
- Design Patterns
- Software Architecture
- System Design
- Microservices
- MVC
- CQRS
- Event-Driven
- JSON-LD
- Linked Data
- Semantic Web
---
