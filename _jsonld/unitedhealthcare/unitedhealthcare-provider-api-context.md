---
api_specs:
- filename: unitedhealthcare-provider-api-openapi.yml
  format: yaml
  label: UnitedHealthcare Provider API
  slug: provider-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/openapi/unitedhealthcare-provider-api-openapi.yml
- filename: unitedhealthcare-interoperability-api-openapi.yml
  format: yaml
  label: UnitedHealthcare Interoperability API
  slug: interoperability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/openapi/unitedhealthcare-interoperability-api-openapi.yml
class_count: 14
classes:
- memberId
- memberName
- coverageStatus
- planName
- groupNumber
- networkStatus
- claimNumber
- claimStatus
- authorizationNumber
- authorizationStatus
- EligibilityResponse
- ClaimInquiryResponse
- PriorAuthCheckResponse
- ProviderDemographics
context_file: json-ld/unitedhealthcare-provider-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/json-ld/unitedhealthcare-provider-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unitedhealthcare Provider Api from UnitedHealthcare.
layout: jsonld
name: Unitedhealthcare Provider Api Context
namespaces:
- prefix: uhc
  uri: https://api.uhcprovider.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: fhir
  uri: http://hl7.org/fhir/
properties:
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: terminationDate
  type: date
- container: ''
  name: deductible
  type: decimal
- container: ''
  name: deductibleMet
  type: decimal
- container: ''
  name: outOfPocketMax
  type: decimal
- container: ''
  name: copay
  type: decimal
- container: ''
  name: coinsurance
  type: decimal
- container: ''
  name: billedAmount
  type: decimal
- container: ''
  name: allowedAmount
  type: decimal
- container: ''
  name: paidAmount
  type: decimal
- container: ''
  name: paymentDate
  type: date
- container: ''
  name: npi
  type: string
- container: ''
  name: authorizationRequired
  type: boolean
property_count: 13
provider_name: UnitedHealthcare
provider_slug: unitedhealthcare
slug: unitedhealthcare-provider-api-context
source_filename: unitedhealthcare-provider-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uhc\": \"https://api.uhcprovider.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"memberId\": \"uhc:memberId\",\n    \"memberName\": \"uhc:memberName\",\n    \"coverageStatus\": \"uhc:coverageStatus\",\n    \"planName\": \"uhc:planName\",\n    \"groupNumber\": \"uhc:groupNumber\",\n    \"effectiveDate\": {\n      \"@id\": \"uhc:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"terminationDate\": {\n      \"@id\": \"uhc:terminationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"deductible\": {\n      \"@id\": \"uhc:deductible\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deductibleMet\": {\n      \"@id\": \"uhc:deductibleMet\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"outOfPocketMax\": {\n      \"@id\": \"uhc:outOfPocketMax\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"copay\": {\n\
  \      \"@id\": \"uhc:copay\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"coinsurance\": {\n      \"@id\": \"uhc:coinsurance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"networkStatus\": \"uhc:networkStatus\",\n    \"claimNumber\": \"uhc:claimNumber\",\n    \"claimStatus\": \"uhc:claimStatus\",\n    \"billedAmount\": {\n      \"@id\": \"uhc:billedAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"allowedAmount\": {\n      \"@id\": \"uhc:allowedAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"paidAmount\": {\n      \"@id\": \"uhc:paidAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"paymentDate\": {\n      \"@id\": \"uhc:paymentDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"npi\": {\n      \"@id\": \"uhc:npi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizationRequired\": {\n      \"@id\": \"uhc:authorizationRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"authorizationNumber\": \"uhc:authorizationNumber\",\n    \"authorizationStatus\"\
  : \"uhc:authorizationStatus\",\n    \"EligibilityResponse\": \"uhc:EligibilityResponse\",\n    \"ClaimInquiryResponse\": \"uhc:ClaimInquiryResponse\",\n    \"PriorAuthCheckResponse\": \"uhc:PriorAuthCheckResponse\",\n    \"ProviderDemographics\": \"uhc:ProviderDemographics\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/json-ld/unitedhealthcare-provider-api-context.jsonld
tags:
- Health Insurance
- Healthcare
- FHIR
- Claims
- Eligibility
- JSON-LD
- Linked Data
- Semantic Web
---
