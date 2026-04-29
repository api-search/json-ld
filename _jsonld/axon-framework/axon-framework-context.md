---
api_specs:
- filename: axon-server-api.yml
  format: yaml
  label: Axon Framework
  slug: axon-framework
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/openapi/axon-server-api.yml
class_count: 10
classes:
- Event
- CommandHandler
- QueryHandler
- Context
- CreateContextRequest
- Application
- User
- CreateUserRequest
- ClusterNode
- EventProcessor
context_file: json-ld/axon-framework-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/json-ld/axon-framework-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Axon Framework from Axon Framework.
layout: jsonld
name: Axon Framework Context
namespaces:
- prefix: axon
  uri: https://docs.axoniq.io/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Axon Framework
provider_slug: axon-framework
slug: axon-framework-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"axon\": \"https://docs.axoniq.io/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Event\": \"axon:Event\",\n    \"CommandHandler\": \"axon:CommandHandler\",\n    \"QueryHandler\": \"axon:QueryHandler\",\n    \"Context\": \"axon:Context\",\n    \"CreateContextRequest\": \"axon:CreateContextRequest\",\n    \"Application\": \"axon:Application\",\n    \"User\": \"axon:User\",\n    \"CreateUserRequest\": \"axon:CreateUserRequest\",\n    \"ClusterNode\": \"axon:ClusterNode\",\n    \"EventProcessor\": \"axon:EventProcessor\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/json-ld/axon-framework-context.jsonld
tags:
- CQRS
- Event Sourcing
- Event-Driven
- Java
- Messaging
- Microservices
- JSON-LD
- Linked Data
- Semantic Web
---
