---
class_count: 6
classes:
- SparqlResults
- DatasetList
- DatasetRequest
- RDFTerm
- Dataset
- Binding
context_file: json-ld/apache-jena-fuseki-sparql-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-jena/refs/heads/main/json-ld/apache-jena-fuseki-sparql-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Jena Fuseki Sparql Api from Apache Jena.
layout: jsonld
name: Apache Jena Fuseki Sparql Api Context
namespaces:
- prefix: jena
  uri: https://apache-jena.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: head
  type: reference
- container: set
  name: vars
  type: string
- container: ''
  name: results
  type: reference
- container: set
  name: bindings
  type: string
- container: ''
  name: boolean
  type: boolean
- container: set
  name: datasets
  type: string
- container: ''
  name: dbName
  type: string
- container: ''
  name: dbType
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: datatype
  type: string
- container: ''
  name: xml:lang
  type: string
- container: ''
  name: ds.name
  type: string
- container: ''
  name: ds.state
  type: boolean
- container: set
  name: ds.services
  type: reference
- container: ''
  name: s
  type: string
- container: ''
  name: p
  type: string
- container: ''
  name: o
  type: string
property_count: 18
provider_name: Apache Jena
provider_slug: apache-jena
slug: apache-jena-fuseki-sparql-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"jena\": \"https://apache-jena.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SparqlResults\": \"jena:SparqlResults\",\n    \"DatasetList\": \"jena:DatasetList\",\n    \"DatasetRequest\": \"jena:DatasetRequest\",\n    \"RDFTerm\": \"jena:RDFTerm\",\n    \"Dataset\": \"jena:Dataset\",\n    \"Binding\": \"jena:Binding\",\n    \"head\": {\n      \"@id\": \"jena:head\",\n      \"@type\": \"@id\"\n    },\n    \"vars\": {\n      \"@id\": \"jena:vars\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"jena:results\",\n      \"@type\": \"@id\"\n    },\n    \"bindings\": {\n      \"@id\": \"jena:bindings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"boolean\": {\n      \"@id\": \"jena:boolean\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"datasets\": {\n      \"@id\": \"jena:datasets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbName\": {\n      \"@id\": \"jena:dbName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbType\": {\n      \"@id\": \"jena:dbType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"jena:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"jena:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datatype\": {\n      \"@id\": \"jena:datatype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xml:lang\": {\n      \"@id\": \"jena:xml:lang\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ds.name\": {\n      \"@id\": \"jena:ds.name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ds.state\": {\n      \"@id\": \"jena:ds.state\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ds.services\": {\n      \"@id\": \"jena:ds.services\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"s\": {\n      \"@id\": \"jena:s\",\n      \"@type\": \"xsd:string\"\n    },\n    \"p\": {\n      \"@id\": \"jena:p\",\n      \"@type\": \"xsd:string\"\n    },\n    \"o\": {\n      \"@id\": \"jena:o\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-jena/refs/heads/main/json-ld/apache-jena-fuseki-sparql-api-context.jsonld
tags:
- Java
- Linked Data
- OWL
- Ontology
- Open Source
- RDF
- Semantic Web
- SPARQL
- JSON-LD
- Linked Data
- Semantic Web
---
