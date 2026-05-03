---
api_specs:
- filename: ucsc-genomic-data-openapi.yml
  format: yaml
  label: UCSC Genome Browser REST API
  slug: ucsc-genomic-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/openapi/ucsc-genomic-data-openapi.yml
class_count: 5
classes:
- GenomeAssembly
- Track
- SequenceRegion
- Chromosome
- TrackHub
context_file: json-ld/ucsc-genomic-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/json-ld/ucsc-genomic-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ucsc Genomic Data from UCSC Genomic Data.
layout: jsonld
name: Ucsc Genomic Data Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ucsc
  uri: https://genome.ucsc.edu/vocab/
- prefix: bioschemas
  uri: https://bioschemas.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: so
  uri: http://purl.obolibrary.org/obo/SO_
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: organism
  type: string
- container: ''
  name: scientificName
  type: string
- container: ''
  name: taxId
  type: integer
- container: ''
  name: track
  type: string
- container: ''
  name: shortLabel
  type: string
- container: ''
  name: longLabel
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: genome
  type: string
- container: ''
  name: chrom
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: end
  type: integer
- container: ''
  name: dna
  type: string
- container: ''
  name: hubUrl
  type: reference
property_count: 16
provider_name: UCSC Genomic Data
provider_slug: ucsc-genomic-data
slug: ucsc-genomic-data-context
source_filename: ucsc-genomic-data-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ucsc\": \"https://genome.ucsc.edu/vocab/\",\n    \"bioschemas\": \"https://bioschemas.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"so\": \"http://purl.obolibrary.org/obo/SO_\",\n\n    \"GenomeAssembly\": \"bioschemas:Taxon\",\n    \"Track\": \"ucsc:Track\",\n    \"SequenceRegion\": \"so:0001411\",\n    \"Chromosome\": \"so:0000340\",\n    \"TrackHub\": \"ucsc:TrackHub\",\n\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"organism\": { \"@id\": \"bioschemas:taxonRank\", \"@type\": \"xsd:string\" },\n    \"scientificName\": { \"@id\": \"schema:scientificName\", \"@type\": \"xsd:string\" },\n    \"taxId\": { \"@id\": \"bioschemas:taxonomicRange\", \"@type\": \"xsd:integer\" },\n\n    \"track\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"\
  \ },\n    \"shortLabel\": { \"@id\": \"schema:alternateName\", \"@type\": \"xsd:string\" },\n    \"longLabel\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"type\": { \"@id\": \"schema:additionalType\", \"@type\": \"xsd:string\" },\n    \"visibility\": { \"@id\": \"ucsc:visibility\", \"@type\": \"xsd:string\" },\n\n    \"genome\": { \"@id\": \"ucsc:assembly\", \"@type\": \"xsd:string\" },\n    \"chrom\": { \"@id\": \"ucsc:chromosome\", \"@type\": \"xsd:string\" },\n    \"start\": { \"@id\": \"ucsc:startPosition\", \"@type\": \"xsd:integer\" },\n    \"end\": { \"@id\": \"ucsc:endPosition\", \"@type\": \"xsd:integer\" },\n    \"dna\": { \"@id\": \"ucsc:dnaSequence\", \"@type\": \"xsd:string\" },\n\n    \"hubUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/json-ld/ucsc-genomic-data-context.jsonld
tags:
- Genomics
- Bioinformatics
- DNA
- Biology
- Research
- Open Science
- JSON-LD
- Linked Data
- Semantic Web
---
