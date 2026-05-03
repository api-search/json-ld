---
api_specs:
- filename: scispot-openapi.yml
  format: yaml
  label: Scispot API
  slug: scispot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/openapi/scispot-openapi.yml
class_count: 52
classes:
- Labsheet
- LabsheetRow
- ElectronicLabNotebook
- NotebookEntry
- Manifest
- Sequence
- Sample
- Experiment
- labsheetId
- name
- description
- barcode
- columns
- column
- columnType
- columnRequired
- rows
- rowData
- rowCount
- sequenceType
- dnSequence
- rnaSequence
- proteinSequence
- sequenceString
- sequenceLength
- annotation
- annotationType
- annotationStart
- annotationEnd
- strand
- notebook
- notebookEntry
- entryType
- experiment
- protocol
- observation
- manifest
- manifestType
- plate
- box
- rack
- dimensions
- containerRows
- containerColumns
- apiKey
- workspace
- hl7MessageType
- astmProtocol
- labType
- biotechLab
- clinicalLab
- researchLab
context_file: json-ld/scispot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/json-ld/scispot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scispot from Scispot.
layout: jsonld
name: Scispot Context
namespaces:
- prefix: scispot
  uri: https://www.scispot.com/ontology/
- prefix: sio
  uri: http://semanticscience.org/resource/
- prefix: obo
  uri: http://purl.obolibrary.org/obo/
- prefix: fhirObservation
  uri: https://www.hl7.org/fhir/observation.html
properties:
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: updatedAt
  type: schema:DateTime
property_count: 2
provider_name: Scispot
provider_slug: scispot
slug: scispot-context
source_filename: scispot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"scispot\": \"https://www.scispot.com/ontology/\",\n    \"sio\": \"http://semanticscience.org/resource/\",\n    \"obo\": \"http://purl.obolibrary.org/obo/\",\n\n    \"Labsheet\": \"scispot:Labsheet\",\n    \"LabsheetRow\": \"scispot:LabsheetRow\",\n    \"ElectronicLabNotebook\": \"scispot:ELN\",\n    \"NotebookEntry\": \"scispot:NotebookEntry\",\n    \"Manifest\": \"scispot:Manifest\",\n    \"Sequence\": \"scispot:Sequence\",\n    \"Sample\": \"sio:SIO_000123\",\n    \"Experiment\": \"sio:SIO_000070\",\n\n    \"labsheetId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"barcode\": \"schema:identifier\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n\n    \"columns\": \"scispot:hasColumn\"\
  ,\n    \"column\": \"scispot:Column\",\n    \"columnType\": \"scispot:columnDataType\",\n    \"columnRequired\": \"scispot:required\",\n\n    \"rows\": \"scispot:hasRow\",\n    \"rowData\": \"scispot:rowData\",\n    \"rowCount\": \"schema:numberOfItems\",\n\n    \"sequenceType\": \"obo:SO_0000001\",\n    \"dnSequence\": \"obo:SO_0000352\",\n    \"rnaSequence\": \"obo:SO_0000233\",\n    \"proteinSequence\": \"obo:SO_0001217\",\n    \"sequenceString\": \"sio:SIO_000030\",\n    \"sequenceLength\": \"sio:SIO_000041\",\n    \"annotation\": \"sio:SIO_000642\",\n    \"annotationType\": \"sio:SIO_000098\",\n    \"annotationStart\": \"sio:SIO_000943\",\n    \"annotationEnd\": \"sio:SIO_000944\",\n    \"strand\": \"obo:SO_0000699\",\n\n    \"notebook\": \"scispot:Notebook\",\n    \"notebookEntry\": \"scispot:NotebookEntry\",\n    \"entryType\": \"scispot:entryType\",\n    \"experiment\": \"sio:SIO_000070\",\n    \"protocol\": \"sio:SIO_000701\",\n    \"observation\": \"sio:SIO_000111\",\n\n    \"\
  manifest\": \"scispot:Manifest\",\n    \"manifestType\": \"scispot:containerType\",\n    \"plate\": \"obo:OBI_0000929\",\n    \"box\": \"scispot:StorageBox\",\n    \"rack\": \"scispot:StorageRack\",\n    \"dimensions\": \"schema:size\",\n    \"containerRows\": \"scispot:rows\",\n    \"containerColumns\": \"scispot:columns\",\n\n    \"apiKey\": \"schema:accessCode\",\n    \"workspace\": \"schema:Organization\",\n\n    \"fhirObservation\": \"https://www.hl7.org/fhir/observation.html\",\n    \"hl7MessageType\": \"scispot:hl7MessageType\",\n    \"astmProtocol\": \"scispot:astmProtocol\",\n\n    \"labType\": \"scispot:labType\",\n    \"biotechLab\": \"scispot:BiotechLab\",\n    \"clinicalLab\": \"scispot:ClinicalLab\",\n    \"researchLab\": \"scispot:ResearchLab\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/json-ld/scispot-context.jsonld
tags:
- Laboratory
- Life Science
- LIMS
- ELN
- Biotech
- API First
- Scientific Data
- Healthcare
- JSON-LD
- Linked Data
- Semantic Web
---
