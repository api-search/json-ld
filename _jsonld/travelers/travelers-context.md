---
api_specs:
- filename: travelers-openapi.yml
  format: yaml
  label: Travelers API
  slug: travelers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/openapi/travelers-openapi.yml
class_count: 40
classes:
- Claim
- Policy
- Quote
- Claimant
- Adjuster
- BusinessInfo
- Coverage
- id
- claim_number
- policy_number
- policy_type
- quote_id
- status
- loss_date
- reported_date
- description
- claimant
- adjuster
- total_incurred
- premium
- effective_date
- expiration_date
- coverages
- name
- contact_email
- contact_phone
- address
- city
- state
- zip
- industry_code
- annual_revenue
- employee_count
- product_type
- insured_name
- limit
- deductible
- created_at
- total
- page
context_file: json-ld/travelers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/json-ld/travelers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Travelers from Travelers.
layout: jsonld
name: Travelers Context
namespaces:
- prefix: travelers
  uri: https://travelers.com/vocab/
- prefix: ins
  uri: http://www.w3.org/ns/legal#
properties: []
property_count: 0
provider_name: Travelers
provider_slug: travelers
slug: travelers-context
source_filename: travelers-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"travelers\": \"https://travelers.com/vocab/\",\n    \"ins\": \"http://www.w3.org/ns/legal#\",\n    \"Claim\": \"travelers:InsuranceClaim\",\n    \"Policy\": \"travelers:InsurancePolicy\",\n    \"Quote\": \"travelers:InsuranceQuote\",\n    \"Claimant\": \"schema:Person\",\n    \"Adjuster\": \"schema:Person\",\n    \"BusinessInfo\": \"schema:Organization\",\n    \"Coverage\": \"travelers:InsuranceCoverage\",\n    \"id\": \"@id\",\n    \"claim_number\": \"travelers:claimNumber\",\n    \"policy_number\": \"travelers:policyNumber\",\n    \"policy_type\": \"travelers:policyType\",\n    \"quote_id\": \"travelers:quoteId\",\n    \"status\": \"schema:orderStatus\",\n    \"loss_date\": \"travelers:lossDate\",\n    \"reported_date\": \"schema:datePublished\",\n    \"description\": \"schema:description\",\n    \"claimant\": \"travelers:claimant\",\n    \"adjuster\": \"travelers:adjuster\",\n    \"total_incurred\": \"\
  travelers:totalIncurred\",\n    \"premium\": \"travelers:premium\",\n    \"effective_date\": \"schema:validFrom\",\n    \"expiration_date\": \"schema:validThrough\",\n    \"coverages\": \"travelers:coverages\",\n    \"name\": \"schema:name\",\n    \"contact_email\": \"schema:email\",\n    \"contact_phone\": \"schema:telephone\",\n    \"address\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"industry_code\": \"schema:naics\",\n    \"annual_revenue\": \"travelers:annualRevenue\",\n    \"employee_count\": \"schema:numberOfEmployees\",\n    \"product_type\": \"travelers:productType\",\n    \"insured_name\": \"travelers:insuredName\",\n    \"limit\": \"travelers:coverageLimit\",\n    \"deductible\": \"travelers:deductible\",\n    \"created_at\": \"schema:dateCreated\",\n    \"total\": \"travelers:totalCount\",\n    \"page\": \"travelers:currentPage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/json-ld/travelers-context.jsonld
tags:
- Insurance
- Property Casualty
- Commercial Insurance
- Claims
- Fintech
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
