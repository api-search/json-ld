---
api_specs:
- filename: state-farm-renters-insurance-openapi.yml
  format: yaml
  label: Renters Insurance API
  slug: renters-insurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/openapi/state-farm-renters-insurance-openapi.yml
class_count: 18
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
- additionalLivingExpenses
- identityRestorationCoverage
- quoteId
- firstName
- lastName
- email
- phone
context_file: json-ld/state-farm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/json-ld/state-farm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for State Farm from State Farm.
layout: jsonld
name: State Farm Context
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
  name: medicalPaymentsLimit
  type: schema:MonetaryAmount
- container: ''
  name: deductible
  type: schema:MonetaryAmount
- container: ''
  name: validUntil
  type: schema:DateTime
- container: ''
  name: dateOfBirth
  type: schema:Date
property_count: 11
provider_name: State Farm
provider_slug: state-farm
slug: state-farm-context
source_filename: state-farm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"statefarm\": \"https://www.statefarm.com/ontology/\",\n\n    \"RentersInsurancePolicy\": \"schema:InsurancePolicy\",\n    \"InsuranceQuote\": \"schema:InsuranceQuote\",\n    \"PolicyHolder\": \"schema:Person\",\n    \"Address\": \"schema:PostalAddress\",\n    \"Coverage\": \"statefarm:Coverage\",\n\n    \"policyNumber\": {\n      \"@id\": \"statefarm:policyNumber\",\n      \"@type\": \"schema:Identifier\"\n    },\n    \"status\": \"schema:status\",\n    \"effectiveDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"schema:Date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"schema:Date\"\n    },\n    \"annualPremium\": {\n      \"@id\": \"statefarm:annualPremium\",\n      \"@type\": \"schema:Number\"\n    },\n    \"monthlyPremium\": {\n      \"@id\": \"statefarm:monthlyPremium\"\
  ,\n      \"@type\": \"schema:Number\"\n    },\n    \"insuredName\": \"schema:name\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zipCode\": \"schema:postalCode\",\n    \"personalPropertyLimit\": {\n      \"@id\": \"statefarm:personalPropertyLimit\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"liabilityLimit\": {\n      \"@id\": \"statefarm:liabilityLimit\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"medicalPaymentsLimit\": {\n      \"@id\": \"statefarm:medicalPaymentsLimit\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"deductible\": {\n      \"@id\": \"schema:deductible\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"additionalLivingExpenses\": \"statefarm:additionalLivingExpenses\",\n    \"identityRestorationCoverage\": \"statefarm:identityRestorationCoverage\",\n    \"quoteId\": \"schema:identifier\",\n    \"validUntil\": {\n      \"@id\"\
  : \"schema:validThrough\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"schema:Date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/json-ld/state-farm-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
