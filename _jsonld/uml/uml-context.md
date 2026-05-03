---
api_specs:
- filename: plantuml-server-openapi.yml
  format: yaml
  label: PlantUML Server API
  slug: plantuml-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/openapi/plantuml-server-openapi.yml
- filename: kroki-openapi.yml
  format: yaml
  label: Kroki Diagram API
  slug: kroki
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/openapi/kroki-openapi.yml
class_count: 6
classes:
- Diagram
- DiagramType
- DiagramFormat
- id
- title
- description
context_file: json-ld/uml-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/json-ld/uml-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uml from UML.
layout: jsonld
name: Uml Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: uml
  uri: https://github.com/api-evangelist/uml/blob/main/json-ld/uml-context.jsonld#
properties:
- container: ''
  name: diagramType
  type: '@vocab'
- container: ''
  name: source
  type: string
- container: ''
  name: format
  type: '@vocab'
- container: ''
  name: encodedSource
  type: string
- container: ''
  name: outputUrl
  type: reference
- container: ''
  name: outputFormat
  type: '@vocab'
- container: list
  name: tags
  type: ''
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: diagramTypes
  type: ''
property_count: 10
provider_name: UML
provider_slug: uml
slug: uml-context
source_filename: uml-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"uml\": \"https://github.com/api-evangelist/uml/blob/main/json-ld/uml-context.jsonld#\",\n\n    \"Diagram\": \"schema:CreativeWork\",\n    \"DiagramType\": \"uml:DiagramType\",\n    \"DiagramFormat\": \"uml:DiagramFormat\",\n\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"diagramType\": {\n      \"@id\": \"uml:diagramType\",\n      \"@type\": \"@vocab\"\n    },\n    \"source\": {\n      \"@id\": \"uml:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"uml:format\",\n      \"@type\": \"@vocab\"\n    },\n    \"encodedSource\": {\n      \"@id\": \"uml:encodedSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputUrl\": {\n\
  \      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"outputFormat\": {\n      \"@id\": \"uml:outputFormat\",\n      \"@type\": \"@vocab\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"diagramTypes\": {\n      \"class\": \"uml:ClassDiagram\",\n      \"sequence\": \"uml:SequenceDiagram\",\n      \"activity\": \"uml:ActivityDiagram\",\n      \"usecase\": \"uml:UseCaseDiagram\",\n      \"state\": \"uml:StateDiagram\",\n      \"component\": \"uml:ComponentDiagram\",\n      \"deployment\": \"uml:DeploymentDiagram\",\n      \"object\": \"uml:ObjectDiagram\",\n      \"package\": \"uml:PackageDiagram\",\n      \"timing\": \"uml:TimingDiagram\",\n      \"interaction\": \"uml:InteractionDiagram\",\n \
  \     \"entity-relationship\": \"uml:EntityRelationshipDiagram\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/json-ld/uml-context.jsonld
tags:
- UML
- Modeling
- Diagrams
- Software Architecture
- Design
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
