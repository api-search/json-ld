---
class_count: 9
classes:
- SoftwareApplication
- SoftwareSourceCode
- name
- description
- url
- codeRepository
- programmingLanguage
- license
- version
context_file: json-ld/rest-assured-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rest-assured/refs/heads/main/json-ld/rest-assured-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rest Assured from REST Assured.
layout: jsonld
name: Rest Assured Context
namespaces:
- prefix: ra
  uri: https://rest-assured.io/vocab#
properties:
- container: ''
  name: TestSpecification
  type: rdfs:Class
- container: ''
  name: RequestSpecification
  type: rdfs:Class
- container: ''
  name: ResponseSpecification
  type: rdfs:Class
- container: ''
  name: Assertion
  type: rdfs:Class
- container: ''
  name: JsonPath
  type: rdfs:Class
- container: ''
  name: XmlPath
  type: rdfs:Class
- container: ''
  name: Authentication
  type: rdfs:Class
- container: ''
  name: given
  type: ''
- container: ''
  name: when
  type: ''
- container: ''
  name: then
  type: ''
- container: ''
  name: statusCode
  type: ''
- container: ''
  name: header
  type: ''
- container: ''
  name: body
  type: ''
- container: ''
  name: queryParam
  type: ''
- container: ''
  name: pathParam
  type: ''
- container: ''
  name: authentication
  type: ra:Authentication
property_count: 16
provider_name: REST Assured
provider_slug: rest-assured
slug: rest-assured-context
source_filename: rest-assured-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ra\": \"https://rest-assured.io/vocab#\",\n    \"SoftwareApplication\": \"SoftwareApplication\",\n    \"SoftwareSourceCode\": \"SoftwareSourceCode\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"codeRepository\": \"codeRepository\",\n    \"programmingLanguage\": \"programmingLanguage\",\n    \"license\": \"license\",\n    \"version\": \"softwareVersion\",\n    \"TestSpecification\": {\n      \"@id\": \"ra:TestSpecification\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"RequestSpecification\": {\n      \"@id\": \"ra:RequestSpecification\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"ResponseSpecification\": {\n      \"@id\": \"ra:ResponseSpecification\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"Assertion\": {\n      \"@id\": \"ra:Assertion\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"JsonPath\": {\n      \"@id\": \"ra:JsonPath\",\n     \
  \ \"@type\": \"rdfs:Class\"\n    },\n    \"XmlPath\": {\n      \"@id\": \"ra:XmlPath\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"Authentication\": {\n      \"@id\": \"ra:Authentication\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"given\": {\n      \"@id\": \"ra:given\"\n    },\n    \"when\": {\n      \"@id\": \"ra:when\"\n    },\n    \"then\": {\n      \"@id\": \"ra:then\"\n    },\n    \"statusCode\": {\n      \"@id\": \"ra:statusCode\"\n    },\n    \"header\": {\n      \"@id\": \"ra:header\"\n    },\n    \"body\": {\n      \"@id\": \"ra:body\"\n    },\n    \"queryParam\": {\n      \"@id\": \"ra:queryParam\"\n    },\n    \"pathParam\": {\n      \"@id\": \"ra:pathParam\"\n    },\n    \"authentication\": {\n      \"@id\": \"ra:authentication\",\n      \"@type\": \"ra:Authentication\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rest-assured/refs/heads/main/json-ld/rest-assured-context.jsonld
tags:
- Functional Testing
- Testing
- Java
- API Testing
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
