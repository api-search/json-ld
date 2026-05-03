---
api_specs:
- filename: webflux-websocket-asyncapi.yml
  format: yaml
  label: Spring WebFlux WebSocket
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/asyncapi/webflux-websocket-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/webflux-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/json-ld/webflux-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Webflux from Spring WebFlux.
layout: jsonld
name: Webflux Context
namespaces:
- prefix: webflux
  uri: https://spring.io/projects/spring-framework/webflux#
- prefix: schema
  uri: https://schema.org/
- prefix: reactor
  uri: https://projectreactor.io/docs/core/release/api/reactor/core/publisher/
- prefix: rfc
  uri: https://tools.ietf.org/html/
properties:
- container: ''
  name: WebFluxApplication
  type: reference
- container: ''
  name: ReactiveWebServerFactory
  type: reference
- container: ''
  name: WebClient
  type: reference
- container: ''
  name: WebSocketHandler
  type: reference
- container: ''
  name: WebSocketSession
  type: reference
- container: ''
  name: RouterFunction
  type: reference
- container: ''
  name: HandlerFunction
  type: reference
- container: ''
  name: DispatcherHandler
  type: reference
- container: ''
  name: Mono
  type: reference
- container: ''
  name: Flux
  type: reference
- container: ''
  name: ServerRequest
  type: reference
- container: ''
  name: ServerResponse
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: uri
  type: reference
- container: ''
  name: headers
  type: reference
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: body
  type: ''
- container: ''
  name: timeout
  type: integer
- container: ''
  name: sessionId
  type: string
- container: ''
  name: backpressure
  type: boolean
- container: ''
  name: ReactiveStreams
  type: reference
- container: ''
  name: RSocket
  type: reference
- container: ''
  name: WebFluxConfig
  type: reference
- container: ''
  name: WebTestClient
  type: reference
property_count: 24
provider_name: Spring WebFlux
provider_slug: webflux
slug: webflux-context
source_filename: webflux-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"webflux\": \"https://spring.io/projects/spring-framework/webflux#\",\n    \"schema\": \"https://schema.org/\",\n    \"reactor\": \"https://projectreactor.io/docs/core/release/api/reactor/core/publisher/\",\n    \"rfc\": \"https://tools.ietf.org/html/\",\n\n    \"WebFluxApplication\": {\n      \"@id\": \"webflux:WebFluxApplication\",\n      \"@type\": \"@id\",\n      \"description\": \"A Spring Boot application using the WebFlux reactive stack\"\n    },\n\n    \"ReactiveWebServerFactory\": {\n      \"@id\": \"webflux:ReactiveWebServerFactory\",\n      \"@type\": \"@id\",\n      \"description\": \"Factory for creating reactive web servers (Netty, Tomcat, Undertow, Jetty)\"\n    },\n\n    \"WebClient\": {\n      \"@id\": \"webflux:WebClient\",\n      \"@type\": \"@id\",\n      \"description\": \"Non-blocking HTTP client for consuming REST services reactively\"\n    },\n\n    \"WebSocketHandler\": {\n      \"@id\": \"webflux:WebSocketHandler\"\
  ,\n      \"@type\": \"@id\",\n      \"description\": \"Handler for WebSocket connections in Spring WebFlux\"\n    },\n\n    \"WebSocketSession\": {\n      \"@id\": \"webflux:WebSocketSession\",\n      \"@type\": \"@id\",\n      \"description\": \"Represents an active WebSocket session with reactive inbound/outbound streams\"\n    },\n\n    \"RouterFunction\": {\n      \"@id\": \"webflux:RouterFunction\",\n      \"@type\": \"@id\",\n      \"description\": \"Functional routing configuration composed of route predicates and handler functions\"\n    },\n\n    \"HandlerFunction\": {\n      \"@id\": \"webflux:HandlerFunction\",\n      \"@type\": \"@id\",\n      \"description\": \"Function that handles an incoming ServerRequest and returns a Mono<ServerResponse>\"\n    },\n\n    \"DispatcherHandler\": {\n      \"@id\": \"webflux:DispatcherHandler\",\n      \"@type\": \"@id\",\n      \"description\": \"Central request dispatcher for WebFlux (analogous to DispatcherServlet in Spring MVC)\"\n  \
  \  },\n\n    \"Mono\": {\n      \"@id\": \"reactor:Mono\",\n      \"@type\": \"@id\",\n      \"description\": \"Reactive publisher emitting 0 or 1 element (Project Reactor)\"\n    },\n\n    \"Flux\": {\n      \"@id\": \"reactor:Flux\",\n      \"@type\": \"@id\",\n      \"description\": \"Reactive publisher emitting 0 to N elements (Project Reactor)\"\n    },\n\n    \"ServerRequest\": {\n      \"@id\": \"webflux:ServerRequest\",\n      \"@type\": \"@id\",\n      \"description\": \"Represents an HTTP server request in the functional endpoints model\"\n    },\n\n    \"ServerResponse\": {\n      \"@id\": \"webflux:ServerResponse\",\n      \"@type\": \"@id\",\n      \"description\": \"Represents an HTTP server response in the functional endpoints model\"\n    },\n\n    \"method\": {\n      \"@id\": \"schema:httpMethod\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"HTTP method (GET, POST, PUT, PATCH, DELETE)\"\n    },\n\n    \"uri\": {\n      \"@id\": \"schema:url\",\n      \"\
  @type\": \"@id\",\n      \"description\": \"Target URI\"\n    },\n\n    \"headers\": {\n      \"@id\": \"webflux:headers\",\n      \"@type\": \"@id\",\n      \"description\": \"HTTP headers collection\"\n    },\n\n    \"statusCode\": {\n      \"@id\": \"schema:httpStatusCode\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"HTTP status code\"\n    },\n\n    \"body\": {\n      \"@id\": \"schema:object\",\n      \"description\": \"HTTP message body\"\n    },\n\n    \"timeout\": {\n      \"@id\": \"schema:Duration\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"Timeout duration in milliseconds\"\n    },\n\n    \"sessionId\": {\n      \"@id\": \"webflux:sessionId\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"WebSocket session identifier\"\n    },\n\n    \"backpressure\": {\n      \"@id\": \"webflux:backpressure\",\n      \"@type\": \"xsd:boolean\",\n      \"description\": \"Whether backpressure is applied to the reactive stream\"\n    },\n\n \
  \   \"ReactiveStreams\": {\n      \"@id\": \"https://www.reactive-streams.org/\",\n      \"@type\": \"@id\",\n      \"description\": \"Reactive Streams specification for asynchronous stream processing\"\n    },\n\n    \"RSocket\": {\n      \"@id\": \"https://rsocket.io/\",\n      \"@type\": \"@id\",\n      \"description\": \"Binary application protocol for reactive binary communication\"\n    },\n\n    \"WebFluxConfig\": {\n      \"@id\": \"webflux:WebFluxConfig\",\n      \"@type\": \"@id\",\n      \"description\": \"Configuration class for customizing WebFlux behavior\"\n    },\n\n    \"WebTestClient\": {\n      \"@id\": \"webflux:WebTestClient\",\n      \"@type\": \"@id\",\n      \"description\": \"Client for testing WebFlux server endpoints in integration tests\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/json-ld/webflux-context.jsonld
tags:
- Java
- Microservices
- Non-Blocking IO
- Reactive Programming
- REST API
- Spring Boot
- Spring Framework
- WebFlux
- JSON-LD
- Linked Data
- Semantic Web
---
