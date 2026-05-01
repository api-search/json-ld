---
api_specs:
- filename: va-facilities-api-openapi.yml
  format: yaml
  label: VA Facilities API
  slug: va-facilities-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-facilities-api-openapi.yml
- filename: va-forms-api-openapi.yml
  format: yaml
  label: VA Forms API
  slug: va-forms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-forms-api-openapi.yml
- filename: va-benefits-claims-api-openapi.yml
  format: yaml
  label: VA Benefits Claims API
  slug: va-benefits-claims-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-benefits-claims-api-openapi.yml
- filename: va-benefits-intake-api-openapi.yml
  format: yaml
  label: VA Benefits Intake API
  slug: va-benefits-intake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-benefits-intake-api-openapi.yml
- filename: va-appeals-status-api-openapi.yml
  format: yaml
  label: VA Appeals Status API
  slug: va-appeals-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-appeals-status-api-openapi.yml
- filename: va-clinical-health-fhir-api-openapi.yml
  format: yaml
  label: VA Clinical Health API (FHIR)
  slug: va-clinical-health-fhir-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-clinical-health-fhir-api-openapi.yml
- filename: va-veteran-confirmation-api-openapi.yml
  format: yaml
  label: VA Veteran Confirmation API
  slug: va-veteran-confirmation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/openapi/va-veteran-confirmation-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/va-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/json-ld/va-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Va from Department of Veterans Affairs (VA).
layout: jsonld
name: Va Context
namespaces:
- prefix: va
  uri: https://api-evangelist.com/department-of-veterans-affairs/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: Facility
  type: ''
- container: ''
  name: Form
  type: ''
- container: ''
  name: Claim
  type: ''
- container: ''
  name: Appeal
  type: ''
- container: ''
  name: VeteranConfirmation
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: BenefitCategory
  type: ''
property_count: 7
provider_name: Department of Veterans Affairs (VA)
provider_slug: department-of-veterans-affairs
slug: va-context
source_filename: va-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"va\": \"https://api-evangelist.com/department-of-veterans-affairs/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Facility\": {\n      \"@id\": \"va:Facility\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"facilityType\": \"va:facilityType\",\n        \"classification\": \"va:classification\",\n        \"website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"lat\": { \"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\" },\n        \"long\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" },\n        \"timeZone\": \"va:timeZone\",\n        \"visn\": \"va:visn\"\n      }\n    },\n    \"Form\": {\n      \"@id\": \"va:Form\",\n      \"@context\": {\n        \"formName\": \"schema:identifier\",\n        \"title\": \"\
  schema:name\",\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"firstIssuedOn\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:date\" },\n        \"lastRevisionOn\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:date\" },\n        \"pages\": { \"@id\": \"schema:numberOfPages\", \"@type\": \"xsd:integer\" },\n        \"language\": \"schema:inLanguage\",\n        \"validPdf\": { \"@id\": \"va:validPdf\", \"@type\": \"xsd:boolean\" }\n      }\n    },\n    \"Claim\": {\n      \"@id\": \"va:Claim\",\n      \"@context\": {\n        \"claimDate\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:date\" },\n        \"claimType\": \"va:claimType\",\n        \"status\": \"va:status\",\n        \"decisionLetterSent\": { \"@id\": \"va:decisionLetterSent\", \"@type\": \"xsd:boolean\" },\n        \"documentsNeeded\": { \"@id\": \"va:documentsNeeded\", \"@type\": \"xsd:boolean\" }\n      }\n    },\n    \"Appeal\": {\n      \"@id\": \"va:Appeal\",\n      \"\
  @context\": {\n        \"programArea\": \"va:programArea\",\n        \"description\": \"schema:description\",\n        \"aoj\": \"va:agencyOfJurisdiction\",\n        \"location\": \"va:appealLocation\",\n        \"updated\": { \"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\" }\n      }\n    },\n    \"VeteranConfirmation\": {\n      \"@id\": \"va:VeteranConfirmation\",\n      \"@context\": {\n        \"veteran_status\": \"va:veteranStatus\"\n      }\n    },\n    \"Service\": {\n      \"@id\": \"va:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"serviceId\": \"schema:identifier\",\n        \"active\": { \"@id\": \"va:active\", \"@type\": \"xsd:boolean\" }\n      }\n    },\n    \"BenefitCategory\": {\n      \"@id\": \"va:BenefitCategory\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/refs/heads/main/json-ld/va-context.jsonld
tags:
- Federal Government
- Healthcare
- Veterans
- JSON-LD
- Linked Data
- Semantic Web
---
