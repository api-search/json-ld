---
api_specs:
- filename: majesco-policy-openapi.yml
  format: yaml
  label: Majesco Insurance SaaS API
  slug: majesco-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/majesco/refs/heads/main/openapi/majesco-policy-openapi.yml
class_count: 24
classes:
- Policy
- policyNumber
- status
- policyholder
- Policyholder
- firstName
- lastName
- email
- phone
- address
- Address
- street1
- city
- state
- postalCode
- country
- Coverage
- coverageCode
- coverageDescription
- Premium
- currency
- Claim
- claimNumber
- lossDescription
context_file: json-ld/majesco-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/majesco/refs/heads/main/json-ld/majesco-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Majesco from majesco.
layout: jsonld
name: Majesco Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: majesco
  uri: https://www.majesco.com/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: limit
  type: decimal
- container: ''
  name: deductible
  type: decimal
- container: ''
  name: premium
  type: decimal
- container: ''
  name: annualPremium
  type: decimal
- container: ''
  name: totalPremium
  type: decimal
- container: ''
  name: lossDate
  type: date
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 11
provider_name: majesco
provider_slug: majesco
slug: majesco-context
source_filename: majesco-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"majesco\": \"https://www.majesco.com/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Policy\": \"schema:InsurancePolicy\",\n    \"policyNumber\": \"schema:identifier\",\n    \"status\": \"schema:status\",\n    \"effectiveDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"policyholder\": \"schema:holder\",\n    \"Policyholder\": \"schema:Person\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"address\": \"schema:address\",\n    \"Address\": \"schema:PostalAddress\",\n    \"street1\": \"schema:streetAddress\"\
  ,\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"Coverage\": \"majesco:Coverage\",\n    \"coverageCode\": \"schema:identifier\",\n    \"coverageDescription\": \"schema:description\",\n    \"limit\": { \"@id\": \"majesco:coverageLimit\", \"@type\": \"xsd:decimal\" },\n    \"deductible\": { \"@id\": \"majesco:deductible\", \"@type\": \"xsd:decimal\" },\n    \"premium\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"Premium\": \"schema:PriceSpecification\",\n    \"annualPremium\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"totalPremium\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:decimal\" },\n    \"currency\": \"schema:priceCurrency\",\n    \"Claim\": \"majesco:InsuranceClaim\",\n    \"claimNumber\": \"schema:identifier\",\n    \"lossDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n  \
  \  \"lossDescription\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/majesco/refs/heads/main/json-ld/majesco-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
