---
class_count: 0
classes: []
context_file: json-ld/dependency-injection.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dependency-injection/refs/heads/main/json-ld/dependency-injection.jsonld
description: JSON-LD context defining the semantic vocabulary for Dependency Injection from Dependency Injection.
layout: jsonld
name: Dependency Injection Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: di
  uri: https://raw.githubusercontent.com/api-evangelist/dependency-injection/main/vocabulary/dependency-injection-vocabulary.json#
properties: []
property_count: 0
provider_name: Dependency Injection
provider_slug: dependency-injection
slug: dependency-injection
source_filename: dependency-injection.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"schema\": \"https://schema.org/\",\n    \"di\": \"https://raw.githubusercontent.com/api-evangelist/dependency-injection/main/vocabulary/dependency-injection-vocabulary.json#\"\n  },\n  \"@type\": \"schema:TechArticle\",\n  \"@id\": \"https://github.com/api-evangelist/dependency-injection\",\n  \"schema:name\": \"Dependency Injection\",\n  \"schema:description\": \"A design pattern in which objects receive their dependencies from external sources rather than creating them internally, promoting loose coupling and easier testing.\",\n  \"schema:about\": [\n    { \"@id\": \"di:DependencyInjection\" },\n    { \"@id\": \"di:InversionOfControl\" },\n    { \"@id\": \"di:ConstructorInjection\" },\n    { \"@id\": \"di:SetterInjection\" },\n    { \"@id\": \"di:CompositionRoot\" },\n    { \"@id\": \"di:DIContainer\" },\n    { \"@id\": \"di:ServiceLocator\" }\n  ],\n  \"schema:keywords\": [\n    \"Design Patterns\",\n    \"Software Architecture\",\n    \"Testing\"\
  ,\n    \"Inversion of Control\"\n  ],\n  \"schema:sameAs\": \"https://en.wikipedia.org/wiki/Dependency_injection\",\n  \"schema:dateCreated\": \"2025-01-01\",\n  \"schema:dateModified\": \"2026-04-28\"\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dependency-injection/refs/heads/main/json-ld/dependency-injection.jsonld
tags:
- Design Patterns
- Inversion of Control
- Software Architecture
- Testing
- Composition Root
- JSON-LD
- Linked Data
- Semantic Web
---
