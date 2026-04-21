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
