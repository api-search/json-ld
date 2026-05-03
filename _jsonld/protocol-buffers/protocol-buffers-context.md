---
class_count: 0
classes: []
context_file: json-ld/protocol-buffers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/protocol-buffers/refs/heads/main/json-ld/protocol-buffers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Protocol Buffers from Protocol Buffers.
layout: jsonld
name: Protocol Buffers Context
namespaces:
- prefix: protobuf
  uri: https://protobuf.dev/reference/protobuf/google.protobuf#
- prefix: schema
  uri: https://schema.org/
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: FileDescriptor
  type: reference
- container: ''
  name: MessageDescriptor
  type: reference
- container: ''
  name: FieldDescriptor
  type: reference
- container: ''
  name: EnumDescriptor
  type: reference
- container: ''
  name: EnumValue
  type: reference
- container: ''
  name: ServiceDescriptor
  type: reference
- container: ''
  name: MethodDescriptor
  type: reference
- container: ''
  name: OneofDescriptor
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: package
  type: string
- container: ''
  name: syntax
  type: string
- container: set
  name: fields
  type: reference
- container: set
  name: messageType
  type: reference
- container: set
  name: enumType
  type: reference
- container: set
  name: service
  type: reference
- container: set
  name: method
  type: reference
- container: ''
  name: inputType
  type: string
- container: ''
  name: outputType
  type: string
- container: ''
  name: fieldNumber
  type: integer
- container: ''
  name: fieldType
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: repeated
  type: boolean
- container: ''
  name: clientStreaming
  type: boolean
- container: ''
  name: serverStreaming
  type: boolean
- container: set
  name: dependency
  type: string
property_count: 27
provider_name: Protocol Buffers
provider_slug: protocol-buffers
slug: protocol-buffers-context
source_filename: protocol-buffers-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"protobuf\": \"https://protobuf.dev/reference/protobuf/google.protobuf#\",\n    \"schema\": \"https://schema.org/\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FileDescriptor\": {\n      \"@id\": \"protobuf:FileDescriptorProto\",\n      \"@type\": \"@id\"\n    },\n    \"MessageDescriptor\": {\n      \"@id\": \"protobuf:DescriptorProto\",\n      \"@type\": \"@id\"\n    },\n    \"FieldDescriptor\": {\n      \"@id\": \"protobuf:FieldDescriptorProto\",\n      \"@type\": \"@id\"\n    },\n    \"EnumDescriptor\": {\n      \"@id\": \"protobuf:EnumDescriptorProto\",\n      \"@type\": \"@id\"\n    },\n    \"EnumValue\": {\n      \"@id\": \"protobuf:EnumValueDescriptorProto\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceDescriptor\": {\n      \"@id\": \"protobuf:ServiceDescriptorProto\",\n   \
  \   \"@type\": \"@id\"\n    },\n    \"MethodDescriptor\": {\n      \"@id\": \"protobuf:MethodDescriptorProto\",\n      \"@type\": \"@id\"\n    },\n    \"OneofDescriptor\": {\n      \"@id\": \"protobuf:OneofDescriptorProto\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"package\": {\n      \"@id\": \"schema:softwarePackage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syntax\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fields\": {\n      \"@id\": \"rdfs:member\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"messageType\": {\n      \"@id\": \"rdfs:Class\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"enumType\": {\n      \"@id\": \"rdfs:Datatype\",\n      \"@type\": \"@id\",\n      \"@container\"\
  : \"@set\"\n    },\n    \"service\": {\n      \"@id\": \"schema:Service\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"method\": {\n      \"@id\": \"schema:potentialAction\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"inputType\": {\n      \"@id\": \"schema:object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputType\": {\n      \"@id\": \"schema:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldNumber\": {\n      \"@id\": \"schema:position\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fieldType\": {\n      \"@id\": \"rdf:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"schema:valueRequired\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"schema:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repeated\": {\n      \"@id\": \"schema:multipleValues\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"clientStreaming\"\
  : {\n      \"@id\": \"schema:dataFlow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"serverStreaming\": {\n      \"@id\": \"schema:dataFlow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dependency\": {\n      \"@id\": \"schema:dependency\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/protocol-buffers/refs/heads/main/json-ld/protocol-buffers-context.jsonld
tags:
- Data Format
- gRPC
- Protobuf
- Protocol Buffers
- Serialization
- JSON-LD
- Linked Data
- Semantic Web
---
