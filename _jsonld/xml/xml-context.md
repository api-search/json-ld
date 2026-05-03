---
class_count: 0
classes: []
context_file: json-ld/xml-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-ld/xml-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Xml from XML.
layout: jsonld
name: Xml Context
namespaces:
- prefix: xml
  uri: http://www.w3.org/XML/1998/namespace#
- prefix: xmlns
  uri: http://www.w3.org/2000/xmlns/
- prefix: xs
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: xsi
  uri: http://www.w3.org/2001/XMLSchema-instance#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xmlvocab
  uri: https://github.com/api-evangelist/xml/blob/main/json-ld/xml-context.jsonld#
properties:
- container: ''
  name: Document
  type: reference
- container: ''
  name: Element
  type: reference
- container: ''
  name: Attribute
  type: reference
- container: ''
  name: Namespace
  type: reference
- container: ''
  name: ProcessingInstruction
  type: reference
- container: ''
  name: DocumentType
  type: reference
- container: ''
  name: version
  type: ''
- container: ''
  name: encoding
  type: ''
- container: ''
  name: standalone
  type: xs:boolean
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: rootElement
  type: ''
- container: ''
  name: qualifiedName
  type: ''
- container: ''
  name: namespaceURI
  type: reference
- container: ''
  name: prefix
  type: ''
- container: ''
  name: uri
  type: reference
- container: set
  name: attributes
  type: ''
- container: set
  name: namespaces
  type: ''
- container: list
  name: children
  type: ''
- container: ''
  name: value
  type: ''
- container: ''
  name: text
  type: ''
- container: ''
  name: doctype
  type: ''
- container: ''
  name: publicId
  type: ''
- container: ''
  name: systemId
  type: reference
- container: ''
  name: schemaLocation
  type: ''
- container: ''
  name: noNamespaceSchemaLocation
  type: reference
- container: ''
  name: validation
  type: ''
- container: ''
  name: wellFormed
  type: xs:boolean
- container: ''
  name: valid
  type: xs:boolean
- container: ''
  name: schemaType
  type: ''
- container: ''
  name: xmlLang
  type: ''
- container: ''
  name: xmlSpace
  type: ''
- container: ''
  name: xmlBase
  type: reference
- container: ''
  name: xmlId
  type: ''
- container: ''
  name: created
  type: xs:date
- container: ''
  name: modified
  type: xs:date
property_count: 36
provider_name: XML
provider_slug: xml
slug: xml-context
source_filename: xml-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xml\": \"http://www.w3.org/XML/1998/namespace#\",\n    \"xmlns\": \"http://www.w3.org/2000/xmlns/\",\n    \"xs\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"xsi\": \"http://www.w3.org/2001/XMLSchema-instance#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xmlvocab\": \"https://github.com/api-evangelist/xml/blob/main/json-ld/xml-context.jsonld#\",\n\n    \"Document\": {\n      \"@id\": \"xmlvocab:Document\",\n      \"@type\": \"@id\"\n    },\n    \"Element\": {\n      \"@id\": \"xmlvocab:Element\",\n      \"@type\": \"@id\"\n    },\n    \"Attribute\": {\n      \"@id\": \"xmlvocab:Attribute\",\n      \"@type\": \"@id\"\n    },\n    \"Namespace\": {\n      \"@id\": \"xmlvocab:Namespace\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"ProcessingInstruction\": {\n      \"@id\": \"xmlvocab:ProcessingInstruction\",\n      \"@type\": \"@id\"\n    },\n    \"DocumentType\": {\n      \"@id\": \"xmlvocab:DocumentType\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"dcterms:hasVersion\"\n    },\n    \"encoding\": {\n      \"@id\": \"xmlvocab:encoding\"\n    },\n    \"standalone\": {\n      \"@id\": \"xmlvocab:standalone\",\n      \"@type\": \"xs:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"rootElement\": {\n      \"@id\": \"xmlvocab:rootElement\"\n    },\n    \"qualifiedName\": {\n      \"@id\": \"xmlvocab:qualifiedName\"\n    },\n    \"namespaceURI\": {\n      \"@id\": \"xmlvocab:namespaceURI\",\n      \"@type\": \"@id\"\n    },\n    \"prefix\": {\n      \"@id\": \"xmlvocab:prefix\"\n    },\n    \"uri\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n  \
  \  },\n    \"attributes\": {\n      \"@id\": \"xmlvocab:attributes\",\n      \"@container\": \"@set\"\n    },\n    \"namespaces\": {\n      \"@id\": \"xmlvocab:namespaces\",\n      \"@container\": \"@set\"\n    },\n    \"children\": {\n      \"@id\": \"xmlvocab:children\",\n      \"@container\": \"@list\"\n    },\n    \"value\": {\n      \"@id\": \"rdf:value\"\n    },\n    \"text\": {\n      \"@id\": \"xmlvocab:text\"\n    },\n    \"doctype\": {\n      \"@id\": \"xmlvocab:doctype\"\n    },\n    \"publicId\": {\n      \"@id\": \"xmlvocab:publicId\"\n    },\n    \"systemId\": {\n      \"@id\": \"xmlvocab:systemId\",\n      \"@type\": \"@id\"\n    },\n    \"schemaLocation\": {\n      \"@id\": \"xmlvocab:schemaLocation\"\n    },\n    \"noNamespaceSchemaLocation\": {\n      \"@id\": \"xmlvocab:noNamespaceSchemaLocation\",\n      \"@type\": \"@id\"\n    },\n    \"validation\": {\n      \"@id\": \"xmlvocab:validation\"\n    },\n    \"wellFormed\": {\n      \"@id\": \"xmlvocab:wellFormed\",\n\
  \      \"@type\": \"xs:boolean\"\n    },\n    \"valid\": {\n      \"@id\": \"xmlvocab:valid\",\n      \"@type\": \"xs:boolean\"\n    },\n    \"schemaType\": {\n      \"@id\": \"xmlvocab:schemaType\"\n    },\n    \"xmlLang\": {\n      \"@id\": \"xml:lang\"\n    },\n    \"xmlSpace\": {\n      \"@id\": \"xml:space\"\n    },\n    \"xmlBase\": {\n      \"@id\": \"xml:base\",\n      \"@type\": \"@id\"\n    },\n    \"xmlId\": {\n      \"@id\": \"xml:id\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xs:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xs:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-ld/xml-context.jsonld
tags:
- Data Formats
- Document
- Markup Language
- Standard
- W3C
- Web Services
- XML
- JSON-LD
- Linked Data
- Semantic Web
---
