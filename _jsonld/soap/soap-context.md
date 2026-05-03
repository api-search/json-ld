---
class_count: 6
classes:
- name
- description
- url
- version
- dateCreated
- dateModified
context_file: json-ld/soap-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/soap/refs/heads/main/json-ld/soap-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Soap from SOAP.
layout: jsonld
name: Soap Context
namespaces:
- prefix: soap
  uri: http://www.w3.org/2003/05/soap-envelope/
- prefix: wsdl
  uri: http://www.w3.org/ns/wsdl#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: schema
  uri: http://schema.org/
properties:
- container: ''
  name: Envelope
  type: reference
- container: ''
  name: Header
  type: reference
- container: ''
  name: Body
  type: reference
- container: ''
  name: Fault
  type: reference
- container: ''
  name: Code
  type: ''
- container: ''
  name: Reason
  type: ''
- container: ''
  name: Node
  type: reference
- container: ''
  name: Role
  type: reference
- container: ''
  name: Detail
  type: ''
- container: ''
  name: mustUnderstand
  type: boolean
- container: ''
  name: encodingStyle
  type: reference
- container: ''
  name: role
  type: reference
- container: ''
  name: relay
  type: boolean
property_count: 13
provider_name: SOAP
provider_slug: soap
slug: soap-context
source_filename: soap-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"soap\": \"http://www.w3.org/2003/05/soap-envelope/\",\n    \"wsdl\": \"http://www.w3.org/ns/wsdl#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"schema\": \"http://schema.org/\",\n    \"Envelope\": {\n      \"@id\": \"soap:Envelope\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"The root element of a SOAP message containing header and body.\"\n    },\n    \"Header\": {\n      \"@id\": \"soap:Header\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Optional element containing metadata and processing instructions.\"\n    },\n    \"Body\": {\n      \"@id\": \"soap:Body\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Required element containing the main payload of the SOAP message.\"\n    },\n    \"Fault\": {\n      \"\
  @id\": \"soap:Fault\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Element indicating an error occurred during SOAP message processing.\"\n    },\n    \"Code\": {\n      \"@id\": \"soap:Code\",\n      \"rdfs:comment\": \"Fault code providing algorithmic identification of the error.\"\n    },\n    \"Reason\": {\n      \"@id\": \"soap:Reason\",\n      \"rdfs:comment\": \"Human-readable explanation of a SOAP fault.\"\n    },\n    \"Node\": {\n      \"@id\": \"soap:Node\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"URI of the SOAP node that generated a fault.\"\n    },\n    \"Role\": {\n      \"@id\": \"soap:Role\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"URI identifying the role a SOAP node was operating in.\"\n    },\n    \"Detail\": {\n      \"@id\": \"soap:Detail\",\n      \"rdfs:comment\": \"Application-specific error information in a fault.\"\n    },\n    \"mustUnderstand\": {\n      \"@id\": \"soap:mustUnderstand\",\n      \"@type\": \"xsd:boolean\"\
  ,\n      \"rdfs:comment\": \"Indicates whether a header block must be processed by the target node.\"\n    },\n    \"encodingStyle\": {\n      \"@id\": \"soap:encodingStyle\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"URI identifying the serialization rules for the SOAP message.\"\n    },\n    \"role\": {\n      \"@id\": \"soap:role\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"The SOAP node role targeted by a header block.\"\n    },\n    \"relay\": {\n      \"@id\": \"soap:relay\",\n      \"@type\": \"xsd:boolean\",\n      \"rdfs:comment\": \"Indicates whether a header block should be relayed if not processed.\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/soap/refs/heads/main/json-ld/soap-context.jsonld
tags:
- SOAP
- Messaging Protocol
- Web Services
- XML
- W3C Standard
- Enterprise Integration
- WS-Star
- JSON-LD
- Linked Data
- Semantic Web
---
