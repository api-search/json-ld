---
api_specs:
- filename: ncbi-e-utilities-openapi.yml
  format: yaml
  label: NCBI E-Utilities API
  slug: ncbi-e-utilities-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-e-utilities-openapi.yml
- filename: openapi3.docs.yaml
  format: yaml
  label: NCBI Datasets REST API
  slug: ncbi-datasets-api
  spec_type: OpenAPI
  url: https://www.ncbi.nlm.nih.gov/datasets/docs/v2/openapi3/openapi3.docs.yaml
- filename: ncbi-blast-openapi.yml
  format: yaml
  label: NCBI BLAST URL API
  slug: ncbi-blast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-blast-openapi.yml
- filename: nlm-clinicaltrials-openapi.yml
  format: yaml
  label: ClinicalTrials.gov API
  slug: nlm-clinical-trials-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/nlm-clinicaltrials-openapi.yml
class_count: 4
classes:
- ScholarlyArticle
- MedicalStudy
- MedicalTrial
- GovernmentOrganization
context_file: json-ld/united-states-national-library-of-medicine-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/json-ld/united-states-national-library-of-medicine-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States National Library Of Medicine from United States National Library of Medicine.
layout: jsonld
name: United States National Library Of Medicine Context
namespaces:
- prefix: ncbi
  uri: https://www.ncbi.nlm.nih.gov/ontology/
- prefix: nlm
  uri: https://www.nlm.nih.gov/ontology/
- prefix: bioschemas
  uri: https://bioschemas.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: mesh
  uri: https://id.nlm.nih.gov/mesh/
properties:
- container: ''
  name: pmid
  type: reference
- container: ''
  name: nctId
  type: reference
- container: ''
  name: title
  type: ''
- container: ''
  name: abstract
  type: ''
- container: ''
  name: authors
  type: ''
- container: ''
  name: journal
  type: ''
- container: ''
  name: publicationDate
  type: schema:Date
- container: ''
  name: doi
  type: ''
- container: ''
  name: meshTerms
  type: ''
- container: ''
  name: conditions
  type: ''
- container: ''
  name: interventions
  type: ''
- container: ''
  name: studyType
  type: ''
- container: ''
  name: phases
  type: ''
- container: ''
  name: leadSponsor
  type: ''
- container: ''
  name: eligibilityCriteria
  type: ''
- container: ''
  name: enrollmentCount
  type: ''
- container: ''
  name: taxId
  type: ''
- container: ''
  name: geneId
  type: reference
- container: ''
  name: symbol
  type: ''
property_count: 19
provider_name: United States National Library of Medicine
provider_slug: united-states-national-library-of-medicine
slug: united-states-national-library-of-medicine-context
source_filename: united-states-national-library-of-medicine-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ncbi\": \"https://www.ncbi.nlm.nih.gov/ontology/\",\n    \"nlm\": \"https://www.nlm.nih.gov/ontology/\",\n    \"bioschemas\": \"https://bioschemas.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"mesh\": \"https://id.nlm.nih.gov/mesh/\",\n\n    \"ScholarlyArticle\": \"ScholarlyArticle\",\n    \"MedicalStudy\": \"MedicalStudy\",\n    \"MedicalTrial\": \"MedicalTrial\",\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n\n    \"pmid\": {\n      \"@id\": \"ncbi:pmid\",\n      \"@type\": \"@id\"\n    },\n    \"nctId\": {\n      \"@id\": \"nlm:nctId\",\n      \"@type\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\"\n    },\n    \"abstract\": {\n      \"@id\": \"schema:abstract\"\n    },\n    \"authors\": {\n      \"@id\": \"schema:author\"\n    },\n    \"journal\": {\n      \"@id\": \"schema:isPartOf\"\n    },\n    \"publicationDate\"\
  : {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"schema:Date\"\n    },\n    \"doi\": {\n      \"@id\": \"schema:sameAs\"\n    },\n    \"meshTerms\": {\n      \"@id\": \"schema:keywords\"\n    },\n    \"conditions\": {\n      \"@id\": \"schema:healthCondition\"\n    },\n    \"interventions\": {\n      \"@id\": \"schema:drug\"\n    },\n    \"studyType\": {\n      \"@id\": \"schema:studyDesign\"\n    },\n    \"phases\": {\n      \"@id\": \"schema:status\"\n    },\n    \"leadSponsor\": {\n      \"@id\": \"schema:sponsor\"\n    },\n    \"eligibilityCriteria\": {\n      \"@id\": \"schema:eligibilityRequirement\"\n    },\n    \"enrollmentCount\": {\n      \"@id\": \"schema:numberOfPatients\"\n    },\n    \"taxId\": {\n      \"@id\": \"ncbi:taxonomyId\"\n    },\n    \"geneId\": {\n      \"@id\": \"ncbi:geneId\",\n      \"@type\": \"@id\"\n    },\n    \"symbol\": {\n      \"@id\": \"bioschemas:symbol\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/json-ld/united-states-national-library-of-medicine-context.jsonld
tags:
- Federal Government
- Biomedical Research
- Healthcare
- Genomics
- Literature
- JSON-LD
- Linked Data
- Semantic Web
---
