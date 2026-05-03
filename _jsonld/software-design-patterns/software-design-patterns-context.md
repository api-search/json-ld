---
class_count: 0
classes: []
context_file: json-ld/software-design-patterns-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-design-patterns/refs/heads/main/json-ld/software-design-patterns-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Design Patterns from Software Design Patterns.
layout: jsonld
name: Software Design Patterns Context
namespaces:
- prefix: gof
  uri: https://refactoring.guru/design-patterns/ns#
- prefix: pat
  uri: https://api-evangelist.github.io/software-design-patterns/ns#
properties:
- container: ''
  name: DesignPattern
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: intent
  type: ''
- container: ''
  name: motivation
  type: ''
- container: ''
  name: category
  type: ''
- container: ''
  name: Creational
  type: ''
- container: ''
  name: Structural
  type: ''
- container: ''
  name: Behavioral
  type: ''
- container: ''
  name: Participant
  type: reference
- container: ''
  name: applicability
  type: ''
- container: ''
  name: consequences
  type: ''
- container: ''
  name: relatedPatterns
  type: ''
- container: ''
  name: aliases
  type: ''
- container: ''
  name: languages
  type: ''
- container: ''
  name: Observer
  type: ''
- container: ''
  name: Factory
  type: ''
- container: ''
  name: Singleton
  type: ''
- container: ''
  name: Adapter
  type: ''
- container: ''
  name: Decorator
  type: ''
- container: ''
  name: Strategy
  type: ''
- container: ''
  name: Command
  type: ''
- container: ''
  name: Proxy
  type: ''
- container: ''
  name: Builder
  type: ''
- container: ''
  name: Facade
  type: ''
- container: ''
  name: Iterator
  type: ''
property_count: 25
provider_name: Software Design Patterns
provider_slug: software-design-patterns
slug: software-design-patterns-context
source_filename: software-design-patterns-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gof\": \"https://refactoring.guru/design-patterns/ns#\",\n    \"pat\": \"https://api-evangelist.github.io/software-design-patterns/ns#\",\n    \"DesignPattern\": {\n      \"@id\": \"schema:HowTo\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"intent\": {\n      \"@id\": \"schema:description\"\n    },\n    \"motivation\": {\n      \"@id\": \"pat:motivation\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\"\n    },\n    \"Creational\": {\n      \"@id\": \"gof:CreationalPattern\"\n    },\n    \"Structural\": {\n      \"@id\": \"gof:StructuralPattern\"\n    },\n    \"Behavioral\": {\n      \"@id\": \"gof:BehavioralPattern\"\n    },\n    \"Participant\": {\n      \"@id\": \"pat:Participant\",\n      \"@type\": \"@id\"\n    },\n    \"applicability\": {\n      \"@id\": \"schema:applicationCategory\"\n    },\n    \"consequences\": {\n      \"@id\"\
  : \"pat:consequence\"\n    },\n    \"relatedPatterns\": {\n      \"@id\": \"schema:isRelatedTo\"\n    },\n    \"aliases\": {\n      \"@id\": \"schema:alternateName\"\n    },\n    \"languages\": {\n      \"@id\": \"schema:programmingLanguage\"\n    },\n    \"Observer\": {\"@id\": \"gof:ObserverPattern\"},\n    \"Factory\": {\"@id\": \"gof:FactoryPattern\"},\n    \"Singleton\": {\"@id\": \"gof:SingletonPattern\"},\n    \"Adapter\": {\"@id\": \"gof:AdapterPattern\"},\n    \"Decorator\": {\"@id\": \"gof:DecoratorPattern\"},\n    \"Strategy\": {\"@id\": \"gof:StrategyPattern\"},\n    \"Command\": {\"@id\": \"gof:CommandPattern\"},\n    \"Proxy\": {\"@id\": \"gof:ProxyPattern\"},\n    \"Builder\": {\"@id\": \"gof:BuilderPattern\"},\n    \"Facade\": {\"@id\": \"gof:FacadePattern\"},\n    \"Iterator\": {\"@id\": \"gof:IteratorPattern\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-design-patterns/refs/heads/main/json-ld/software-design-patterns-context.jsonld
tags:
- Architecture
- Best Practices
- Object-Oriented Programming
- Software Engineering
- Design Patterns
- Gang of Four
- Creational Patterns
- Structural Patterns
- Behavioral Patterns
- JSON-LD
- Linked Data
- Semantic Web
---
