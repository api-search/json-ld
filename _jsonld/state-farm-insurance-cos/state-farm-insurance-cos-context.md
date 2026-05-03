---
api_specs:
- filename: state-farm-insurance-cos-renters-openapi.yml
  format: yaml
  label: Renters Insurance API
  slug: renters-insurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/openapi/state-farm-insurance-cos-renters-openapi.yml
class_count: 11
classes:
- RentersInsurancePolicy
- InsuranceQuote
- PolicyHolder
- Address
- Coverage
- status
- insuredName
- street
- city
- state
- zipCode
context_file: json-ld/state-farm-insurance-cos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/json-ld/state-farm-insurance-cos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for State Farm Insurance Cos from State Farm Insurance Companies.
layout: jsonld
name: State Farm Insurance Cos Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: statefarm
  uri: https://www.statefarm.com/ontology/
properties:
- container: ''
  name: policyNumber
  type: schema:Identifier
- container: ''
  name: effectiveDate
  type: schema:Date
- container: ''
  name: expirationDate
  type: schema:Date
- container: ''
  name: annualPremium
  type: schema:Number
- container: ''
  name: monthlyPremium
  type: schema:Number
- container: ''
  name: personalPropertyLimit
  type: schema:MonetaryAmount
- container: ''
  name: liabilityLimit
  type: schema:MonetaryAmount
- container: ''
  name: deductible
  type: schema:MonetaryAmount
property_count: 8
provider_name: State Farm Insurance Companies
provider_slug: state-farm-insurance-cos
slug: state-farm-insurance-cos-context
source_filename: state-farm-insurance-cos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"statefarm\": \"https://www.statefarm.com/ontology/\",\n\n    \"RentersInsurancePolicy\": \"schema:InsurancePolicy\",\n    \"InsuranceQuote\": \"schema:InsuranceQuote\",\n    \"PolicyHolder\": \"schema:Person\",\n    \"Address\": \"schema:PostalAddress\",\n    \"Coverage\": \"statefarm:Coverage\",\n\n    \"policyNumber\": {\n      \"@id\": \"statefarm:policyNumber\",\n      \"@type\": \"schema:Identifier\"\n    },\n    \"status\": \"schema:status\",\n    \"effectiveDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"schema:Date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"schema:Date\"\n    },\n    \"annualPremium\": {\n      \"@id\": \"statefarm:annualPremium\",\n      \"@type\": \"schema:Number\"\n    },\n    \"monthlyPremium\": {\n      \"@id\": \"statefarm:monthlyPremium\"\
  ,\n      \"@type\": \"schema:Number\"\n    },\n    \"insuredName\": \"schema:name\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zipCode\": \"schema:postalCode\",\n    \"personalPropertyLimit\": {\n      \"@id\": \"statefarm:personalPropertyLimit\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"liabilityLimit\": {\n      \"@id\": \"statefarm:liabilityLimit\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"deductible\": {\n      \"@id\": \"schema:deductible\",\n      \"@type\": \"schema:MonetaryAmount\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/json-ld/state-farm-insurance-cos-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
