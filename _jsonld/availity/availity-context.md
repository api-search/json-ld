---
api_specs:
- filename: availity-eligibility-openapi.yml
  format: yaml
  label: Availity Eligibility & Benefits API
  slug: availity-eligibility-benefits-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-eligibility-openapi.yml
- filename: availity-claim-status-openapi.yml
  format: yaml
  label: Availity Claim Status API
  slug: availity-claims-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-status-openapi.yml
- filename: availity-claim-attachments-openapi.yml
  format: yaml
  label: Availity Claim Attachments API
  slug: availity-claim-attachments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-attachments-openapi.yml
- filename: availity-service-reviews-openapi.yml
  format: yaml
  label: Availity Service Reviews (Prior Authorization) API
  slug: availity-service-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-service-reviews-openapi.yml
class_count: 0
classes: []
context_file: json-ld/availity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Availity from availity.
layout: jsonld
name: Availity Context
namespaces:
- prefix: availity
  uri: https://developer.availity.com/api/
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: EligibilityRequest
  type: ''
- container: ''
  name: EligibilityResponse
  type: ''
- container: ''
  name: Coverage
  type: ''
- container: ''
  name: Benefit
  type: ''
- container: ''
  name: Provider
  type: ''
property_count: 5
provider_name: availity
provider_slug: availity
slug: availity-context
source_filename: availity-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"availity\": \"https://developer.availity.com/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"EligibilityRequest\": {\n      \"@id\": \"fhir:CoverageEligibilityRequest\",\n      \"@context\": {\n        \"controlNumber\": {\"@id\": \"availity:controlNumber\"},\n        \"provider\": {\"@id\": \"fhir:provider\"},\n        \"subscriber\": {\"@id\": \"fhir:subscriber\"},\n        \"payer\": {\"@id\": \"fhir:insurer\"},\n        \"serviceDate\": {\"@id\": \"fhir:servicedDate\", \"@type\": \"xsd:date\"}\n      }\n    },\n\n    \"EligibilityResponse\": {\n      \"@id\": \"fhir:CoverageEligibilityResponse\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"controlNumber\": {\"@id\": \"availity:controlNumber\"},\n        \"requestedDate\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"\
  },\n        \"subscriber\": {\"@id\": \"fhir:subscriber\"},\n        \"payer\": {\"@id\": \"fhir:insurer\"},\n        \"coverages\": {\"@id\": \"fhir:insurance\", \"@container\": \"@set\"},\n        \"planInformation\": {\"@id\": \"fhir:insurance/coverage\"}\n      }\n    },\n\n    \"Coverage\": {\n      \"@id\": \"fhir:Coverage\",\n      \"@context\": {\n        \"serviceTypeCodes\": {\"@id\": \"availity:serviceTypeCode\", \"@container\": \"@set\"},\n        \"coverageStatus\": {\"@id\": \"fhir:status\"},\n        \"effectiveDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n        \"expirationDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:date\"},\n        \"benefits\": {\"@id\": \"fhir:benefit\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Benefit\": {\n      \"@id\": \"fhir:Coverage.costToBeneficiary\",\n      \"@context\": {\n        \"code\": {\"@id\": \"availity:benefitCode\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"coverageLevel\"\
  : {\"@id\": \"availity:coverageLevel\"},\n        \"benefitAmount\": {\"@id\": \"fhir:value\"},\n        \"benefitPercent\": {\"@id\": \"fhir:valueMoney\"},\n        \"inPlanNetworkIndicator\": {\"@id\": \"availity:networkIndicator\"},\n        \"timeQualifier\": {\"@id\": \"availity:timeQualifier\"}\n      }\n    },\n\n    \"Provider\": {\n      \"@id\": \"schema:Physician\",\n      \"@context\": {\n        \"npi\": {\"@id\": \"availity:npi\"},\n        \"firstName\": {\"@id\": \"schema:givenName\"},\n        \"lastName\": {\"@id\": \"schema:familyName\"},\n        \"organizationName\": {\"@id\": \"schema:legalName\"},\n        \"taxId\": {\"@id\": \"availity:taxId\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
