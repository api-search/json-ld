---
class_count: 42
classes:
- name
- description
- version
- namespace
- language
- transport
- protocol
- server
- requiredness
- fieldType
- returnType
- throws
- extends
- bool
- byte
- i8
- i16
- i32
- i64
- double
- string
- binary
- uuid
- list
- set
- map
- TBinaryProtocol
- TCompactProtocol
- TJSONProtocol
- TSocket
- TFramedTransport
- TBufferedTransport
- THttpClient
- TSimpleServer
- TThreadPoolServer
- TNonblockingServer
- softwareVersion
- programmingLanguage
- license
- codeRepository
- downloadUrl
- releaseDate
context_file: json-ld/thrift-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thrift/refs/heads/main/json-ld/thrift-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thrift from Apache Thrift.
layout: jsonld
name: Thrift Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: thrift
  uri: https://thrift.apache.org/vocab#
properties:
- container: ''
  name: ThriftService
  type: reference
- container: ''
  name: ThriftStruct
  type: reference
- container: ''
  name: ThriftEnum
  type: reference
- container: ''
  name: ThriftException
  type: reference
- container: ''
  name: ThriftUnion
  type: reference
- container: ''
  name: ThriftFunction
  type: reference
- container: ''
  name: ThriftField
  type: reference
- container: ''
  name: isOneway
  type: boolean
- container: ''
  name: fieldId
  type: integer
- container: ''
  name: enumValue
  type: integer
- container: list
  name: functions
  type: ''
- container: list
  name: fields
  type: ''
- container: list
  name: parameters
  type: ''
- container: list
  name: values
  type: ''
- container: set
  name: baseTypes
  type: ''
property_count: 15
provider_name: Apache Thrift
provider_slug: thrift
slug: thrift-context
source_filename: thrift-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://thrift.apache.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"thrift\": \"https://thrift.apache.org/vocab#\",\n\n    \"ThriftService\": {\n      \"@id\": \"thrift:ThriftService\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A Thrift service interface definition\"\n    },\n    \"ThriftStruct\": {\n      \"@id\": \"thrift:ThriftStruct\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A Thrift struct type definition\"\n    },\n    \"ThriftEnum\": {\n      \"@id\": \"thrift:ThriftEnum\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A Thrift enum type definition\"\n    },\n    \"ThriftException\": {\n      \"@id\": \"thrift:ThriftException\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A Thrift exception type definition\"\n    },\n    \"ThriftUnion\": {\n      \"@id\": \"\
  thrift:ThriftUnion\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A Thrift union type definition\"\n    },\n    \"ThriftFunction\": {\n      \"@id\": \"thrift:ThriftFunction\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A function definition within a Thrift service\"\n    },\n    \"ThriftField\": {\n      \"@id\": \"thrift:ThriftField\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A field within a Thrift struct, union, or exception\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"namespace\": \"thrift:namespace\",\n    \"language\": \"thrift:language\",\n    \"transport\": \"thrift:transport\",\n    \"protocol\": \"thrift:protocol\",\n    \"server\": \"thrift:server\",\n    \"isOneway\": {\n      \"@id\": \"thrift:isOneway\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fieldId\": {\n      \"@id\": \"thrift:fieldId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  requiredness\": \"thrift:requiredness\",\n    \"fieldType\": \"thrift:fieldType\",\n    \"returnType\": \"thrift:returnType\",\n    \"throws\": \"thrift:throws\",\n    \"extends\": \"thrift:extends\",\n    \"enumValue\": {\n      \"@id\": \"thrift:enumValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"functions\": {\n      \"@id\": \"thrift:hasFunctions\",\n      \"@container\": \"@list\"\n    },\n    \"fields\": {\n      \"@id\": \"thrift:hasFields\",\n      \"@container\": \"@list\"\n    },\n    \"parameters\": {\n      \"@id\": \"thrift:hasParameters\",\n      \"@container\": \"@list\"\n    },\n    \"values\": {\n      \"@id\": \"thrift:hasValues\",\n      \"@container\": \"@list\"\n    },\n\n    \"baseTypes\": {\n      \"@id\": \"thrift:baseTypes\",\n      \"@container\": \"@set\"\n    },\n    \"bool\": \"thrift:TypeBool\",\n    \"byte\": \"thrift:TypeByte\",\n    \"i8\": \"thrift:TypeI8\",\n    \"i16\": \"thrift:TypeI16\",\n    \"i32\": \"thrift:TypeI32\",\n    \"i64\": \"\
  thrift:TypeI64\",\n    \"double\": \"thrift:TypeDouble\",\n    \"string\": \"thrift:TypeString\",\n    \"binary\": \"thrift:TypeBinary\",\n    \"uuid\": \"thrift:TypeUUID\",\n    \"list\": \"thrift:TypeList\",\n    \"set\": \"thrift:TypeSet\",\n    \"map\": \"thrift:TypeMap\",\n\n    \"TBinaryProtocol\": \"thrift:ProtocolBinary\",\n    \"TCompactProtocol\": \"thrift:ProtocolCompact\",\n    \"TJSONProtocol\": \"thrift:ProtocolJSON\",\n    \"TSocket\": \"thrift:TransportSocket\",\n    \"TFramedTransport\": \"thrift:TransportFramed\",\n    \"TBufferedTransport\": \"thrift:TransportBuffered\",\n    \"THttpClient\": \"thrift:TransportHTTPClient\",\n    \"TSimpleServer\": \"thrift:ServerSimple\",\n    \"TThreadPoolServer\": \"thrift:ServerThreadPool\",\n    \"TNonblockingServer\": \"thrift:ServerNonblocking\",\n\n    \"softwareVersion\": \"schema:softwareVersion\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"license\": \"schema:license\",\n    \"codeRepository\": \"\
  schema:codeRepository\",\n    \"downloadUrl\": \"schema:downloadUrl\",\n    \"releaseDate\": \"schema:releaseDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thrift/refs/heads/main/json-ld/thrift-context.jsonld
tags:
- Apache
- Code Generation
- Cross Language
- Open Source
- RPC
- SDKs
- Serialization
- Thrift
- JSON-LD
- Linked Data
- Semantic Web
---
