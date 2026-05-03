---
api_specs:
- filename: sigma-aldrich-product-openapi.yml
  format: yaml
  label: Sigma-Aldrich Product Search API
  slug: sigma-aldrich-product-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/openapi/sigma-aldrich-product-openapi.yml
class_count: 15
classes:
- Product
- ChemicalSubstance
- SafetyDataSheet
- id
- catalogNumber
- name
- description
- brand
- purity
- grade
- physicalState
- synonyms
- price
- currency
- stockLevel
context_file: json-ld/sigma-aldrich-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/json-ld/sigma-aldrich-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sigma Aldrich from Sigma-Aldrich.
layout: jsonld
name: Sigma Aldrich Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: chebi
  uri: 'https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:'
- prefix: cheminf
  uri: http://semanticscience.org/resource/CHEMINF_
- prefix: sigmal
  uri: https://api.sigmaaldrich.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: casNumber
  type: string
- container: ''
  name: formula
  type: string
- container: ''
  name: molecularWeight
  type: decimal
- container: ''
  name: smiles
  type: string
- container: ''
  name: inchi
  type: string
- container: ''
  name: inchiKey
  type: string
- container: ''
  name: revisionDate
  type: date
- container: ''
  name: pdfUrl
  type: reference
property_count: 8
provider_name: Sigma-Aldrich
provider_slug: sigma-aldrich
slug: sigma-aldrich-context
source_filename: sigma-aldrich-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"chebi\": \"https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:\",\n    \"cheminf\": \"http://semanticscience.org/resource/CHEMINF_\",\n    \"sigmal\": \"https://api.sigmaaldrich.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"ChemicalSubstance\": \"schema:ChemicalSubstance\",\n    \"SafetyDataSheet\": \"sigmal:SafetyDataSheet\",\n\n    \"id\": \"@id\",\n    \"catalogNumber\": \"schema:productID\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"brand\": \"schema:brand\",\n    \"casNumber\": {\n      \"@id\": \"sigmal:casNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formula\": {\n      \"@id\": \"sigmal:molecularFormula\",\n      \"@type\": \"xsd:string\"\n    },\n    \"molecularWeight\": {\n      \"@id\": \"sigmal:molecularWeight\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"smiles\": {\n      \"@id\": \"cheminf:000018\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inchi\": {\n      \"@id\": \"cheminf:000113\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inchiKey\": {\n      \"@id\": \"cheminf:000059\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purity\": \"sigmal:purity\",\n    \"grade\": \"sigmal:grade\",\n    \"physicalState\": \"sigmal:physicalState\",\n    \"synonyms\": \"schema:alternateName\",\n    \"price\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"stockLevel\": \"schema:availability\",\n    \"revisionDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"pdfUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/json-ld/sigma-aldrich-context.jsonld
tags:
- Life Science
- Chemistry
- Biochemistry
- Laboratory
- Research
- Chemical Catalog
- JSON-LD
- Linked Data
- Semantic Web
---
