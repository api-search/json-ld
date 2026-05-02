---
class_count: 0
classes: []
context_file: json-ld/json-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/json/refs/heads/main/json-ld/json-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Json from JSON.
layout: jsonld
name: Json Context
namespaces:
- prefix: json
  uri: https://www.json.org/terms/
- prefix: rfc
  uri: https://www.rfc-editor.org/rfc/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: JSONDocument
  type: reference
- container: ''
  name: JSONValue
  type: reference
- container: ''
  name: JSONObject
  type: reference
- container: ''
  name: JSONArray
  type: reference
- container: ''
  name: JSONString
  type: string
- container: ''
  name: JSONNumber
  type: double
- container: ''
  name: JSONBoolean
  type: boolean
- container: ''
  name: JSONNull
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: value
  type: ''
- container: set
  name: members
  type: ''
- container: list
  name: elements
  type: ''
- container: ''
  name: mediaType
  type: string
- container: ''
  name: encoding
  type: string
- container: ''
  name: specification
  type: reference
- container: ''
  name: RFC8259
  type: reference
- container: ''
  name: ECMA404
  type: reference
- container: ''
  name: RFC6901
  type: reference
- container: ''
  name: RFC6902
  type: reference
- container: ''
  name: RFC7396
  type: reference
- container: ''
  name: RFC7159
  type: reference
property_count: 21
provider_name: JSON
provider_slug: json
slug: json-context
source_filename: json-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"json\": \"https://www.json.org/terms/\",\n    \"rfc\": \"https://www.rfc-editor.org/rfc/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"JSONDocument\": {\n      \"@id\": \"json:Document\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A complete JSON document containing a single JSON value as defined in RFC 8259.\"\n    },\n    \"JSONValue\": {\n      \"@id\": \"json:Value\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A JSON value, which can be an object, array, string, number, boolean, or null.\"\n    },\n    \"JSONObject\": {\n      \"@id\": \"json:Object\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An unordered collection of zero or more name/value pairs enclosed in curly braces.\"\n    },\n    \"JSONArray\": {\n      \"@id\"\
  : \"json:Array\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An ordered sequence of zero or more JSON values enclosed in square brackets.\"\n    },\n    \"JSONString\": {\n      \"@id\": \"json:String\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"A sequence of zero or more Unicode characters enclosed in double quotation marks.\"\n    },\n    \"JSONNumber\": {\n      \"@id\": \"json:Number\",\n      \"@type\": \"xsd:double\",\n      \"rdfs:comment\": \"A numeric value in decimal notation, optionally with a fraction and/or exponent.\"\n    },\n    \"JSONBoolean\": {\n      \"@id\": \"json:Boolean\",\n      \"@type\": \"xsd:boolean\",\n      \"rdfs:comment\": \"A literal true or false value.\"\n    },\n    \"JSONNull\": {\n      \"@id\": \"json:Null\",\n      \"rdfs:comment\": \"The literal null value representing the absence of a value.\"\n    },\n\n    \"name\": {\n      \"@id\": \"json:memberName\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\"\
  : \"The name (key) in a JSON name/value pair within an object.\"\n    },\n    \"value\": {\n      \"@id\": \"json:memberValue\",\n      \"rdfs:comment\": \"The value in a JSON name/value pair within an object.\"\n    },\n    \"members\": {\n      \"@id\": \"json:hasMembers\",\n      \"@container\": \"@set\",\n      \"rdfs:comment\": \"The set of name/value pairs contained in a JSON object.\"\n    },\n    \"elements\": {\n      \"@id\": \"json:hasElements\",\n      \"@container\": \"@list\",\n      \"rdfs:comment\": \"The ordered list of values contained in a JSON array.\"\n    },\n\n    \"mediaType\": {\n      \"@id\": \"dcterms:format\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"The MIME media type for JSON: application/json.\"\n    },\n    \"encoding\": {\n      \"@id\": \"json:encoding\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"The character encoding for JSON text, which must be UTF-8 per RFC 8259.\"\n    },\n    \"specification\": {\n      \"\
  @id\": \"dcterms:conformsTo\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"The specification this JSON usage conforms to.\"\n    },\n\n    \"RFC8259\": {\n      \"@id\": \"rfc:rfc8259\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"The JSON Data Interchange Format - the primary IETF specification for JSON.\"\n    },\n    \"ECMA404\": {\n      \"@id\": \"https://ecma-international.org/publications-and-standards/standards/ecma-404/\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"ECMA-404 The JSON Data Interchange Syntax - the Ecma International standard for JSON.\"\n    },\n    \"RFC6901\": {\n      \"@id\": \"rfc:rfc6901\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"JavaScript Object Notation (JSON) Pointer.\"\n    },\n    \"RFC6902\": {\n      \"@id\": \"rfc:rfc6902\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"JavaScript Object Notation (JSON) Patch.\"\n    },\n    \"RFC7396\": {\n      \"@id\": \"rfc:rfc7396\",\n      \"@type\": \"@id\"\
  ,\n      \"rdfs:comment\": \"JSON Merge Patch.\"\n    },\n    \"RFC7159\": {\n      \"@id\": \"rfc:rfc7159\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"The JSON Data Interchange Format (superseded by RFC 8259).\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/json/refs/heads/main/json-ld/json-context.jsonld
tags:
- Data Format
- Serialization
- Web Development
- JSON
- RFC 8259
- JSON-LD
- Linked Data
- Semantic Web
---
