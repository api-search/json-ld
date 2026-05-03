---
api_specs:
- filename: rsc-chemspider-compounds-openapi.yml
  format: yaml
  label: ChemSpider Compounds API
  slug: chemspider-compounds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml
- filename: rsc-chemspider-compounds-openapi.yml
  format: yaml
  label: ChemSpider Tools API
  slug: chemspider-tools
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml
class_count: 5
classes:
- Compound
- QueryResponse
- FilterStatus
- ExternalReference
- id
context_file: json-ld/rsc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/json-ld/rsc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rsc from RSC.
layout: jsonld
name: Rsc Context
namespaces:
- prefix: rsc
  uri: https://developer.rsc.org/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: chebi
  uri: http://purl.obolibrary.org/obo/CHEBI_
- prefix: cheminf
  uri: http://semanticscience.org/resource/CHEMINF_
properties:
- container: ''
  name: smiles
  type: schema:Text
- container: ''
  name: formula
  type: schema:Text
- container: ''
  name: averageMass
  type: schema:Number
- container: ''
  name: molecularWeight
  type: schema:Number
- container: ''
  name: monoisotopicMass
  type: schema:Number
- container: ''
  name: nominalMass
  type: schema:Integer
- container: ''
  name: commonName
  type: schema:Text
- container: ''
  name: referenceCount
  type: schema:Integer
- container: ''
  name: dataSourceCount
  type: schema:Integer
- container: ''
  name: pubmedCount
  type: schema:Integer
- container: ''
  name: queryId
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: source
  type: schema:Text
- container: ''
  name: externalId
  type: schema:Text
- container: ''
  name: externalUrl
  type: reference
property_count: 15
provider_name: RSC
provider_slug: rsc
slug: rsc-context
source_filename: rsc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rsc\": \"https://developer.rsc.org/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"chebi\": \"http://purl.obolibrary.org/obo/CHEBI_\",\n    \"cheminf\": \"http://semanticscience.org/resource/CHEMINF_\",\n\n    \"Compound\": \"rsc:Compound\",\n    \"QueryResponse\": \"rsc:QueryResponse\",\n    \"FilterStatus\": \"rsc:FilterStatus\",\n    \"ExternalReference\": \"rsc:ExternalReference\",\n\n    \"id\": \"@id\",\n    \"smiles\": {\n      \"@id\": \"cheminf:000018\",\n      \"@type\": \"schema:Text\"\n    },\n    \"formula\": {\n      \"@id\": \"cheminf:000042\",\n      \"@type\": \"schema:Text\"\n    },\n    \"averageMass\": {\n      \"@id\": \"cheminf:000060\",\n      \"@type\": \"schema:Number\"\n    },\n    \"molecularWeight\": {\n      \"@id\": \"cheminf:000058\",\n      \"@type\": \"schema:Number\"\n    },\n    \"monoisotopicMass\": {\n      \"@id\": \"cheminf:000337\",\n      \"@type\": \"schema:Number\"\n  \
  \  },\n    \"nominalMass\": {\n      \"@id\": \"rsc:nominalMass\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"commonName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"referenceCount\": {\n      \"@id\": \"rsc:referenceCount\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"dataSourceCount\": {\n      \"@id\": \"rsc:dataSourceCount\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"pubmedCount\": {\n      \"@id\": \"rsc:pubmedCount\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"queryId\": {\n      \"@id\": \"rsc:queryId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"status\": {\n      \"@id\": \"rsc:queryStatus\",\n      \"@type\": \"schema:Text\"\n    },\n    \"source\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Text\"\n    },\n    \"externalId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"schema:Text\"\n    },\n    \"externalUrl\": {\n      \"@id\": \"schema:url\",\n     \
  \ \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/json-ld/rsc-context.jsonld
tags:
- Chemistry
- Cheminformatics
- Chemical Data
- Science
- JSON-LD
- Linked Data
- Semantic Web
---
