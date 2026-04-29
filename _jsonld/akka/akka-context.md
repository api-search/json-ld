---
class_count: 2
classes:
- ClusterMembers
- ClusterMember
context_file: json-ld/akka-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/json-ld/akka-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Akka from Akka.
layout: jsonld
name: Akka Context
namespaces:
- prefix: akka
  uri: https://akka.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: members
  type: reference
- container: ''
  name: selfAddress
  type: string
- container: set
  name: unreachable
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: roles
  type: string
- container: ''
  name: uid
  type: integer
property_count: 7
provider_name: Akka
provider_slug: akka
slug: akka-context
source_filename: akka-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"akka\": \"https://akka.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ClusterMembers\": \"akka:ClusterMembers\",\n    \"ClusterMember\": \"akka:ClusterMember\",\n\n    \"members\": {\n      \"@id\": \"akka:members\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"selfAddress\": {\n      \"@id\": \"akka:selfAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unreachable\": {\n      \"@id\": \"akka:unreachable\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"akka:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"akka:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"akka:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"uid\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/json-ld/akka-context.jsonld
tags:
- Actor Model
- Distributed Systems
- Frameworks
- Java
- Microservices
- Reactive
- Scala
- JSON-LD
- Linked Data
- Semantic Web
---
