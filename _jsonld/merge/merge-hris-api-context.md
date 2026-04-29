---
api_specs:
- filename: merge-hris-api-openapi.yaml
  format: yaml
  label: Merge HRIS API
  slug: hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-hris-api-openapi.yaml
- filename: merge-ats-api-openapi.yaml
  format: yaml
  label: Merge ATS API
  slug: ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ats-api-openapi.yaml
- filename: merge-accounting-api-openapi.yaml
  format: yaml
  label: Merge Accounting API
  slug: accounting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-accounting-api-openapi.yaml
- filename: merge-ticketing-api-openapi.yaml
  format: yaml
  label: Merge Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ticketing-api-openapi.yaml
- filename: merge-crm-api-openapi.yaml
  format: yaml
  label: Merge CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-crm-api-openapi.yaml
- filename: merge-file-storage-api-openapi.yaml
  format: yaml
  label: Merge File Storage API
  slug: file-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-file-storage-api-openapi.yaml
class_count: 13
classes:
- Employee
- Company
- Employment
- Team
- Location
- Benefit
- TimeOff
- TimeOffBalance
- PayGroup
- Group
- BankInfo
- EmployeePayrollRun
- PayrollRun
context_file: json-ld/merge-hris-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-hris-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Merge Hris Api from Merge.
layout: jsonld
name: Merge Hris Api Context
namespaces:
- prefix: merge
  uri: https://api.merge.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: remoteId
  type: string
- container: ''
  name: employeeNumber
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: displayFullName
  type: string
- container: ''
  name: workEmail
  type: string
- container: ''
  name: personalEmail
  type: string
- container: ''
  name: mobilePhoneNumber
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: terminationDate
  type: dateTime
- container: ''
  name: employmentStatus
  type: string
- container: ''
  name: manager
  type: reference
- container: ''
  name: company
  type: reference
- container: ''
  name: team
  type: reference
- container: ''
  name: payGroup
  type: reference
- container: set
  name: groups
  type: reference
- container: ''
  name: remoteWasDeleted
  type: boolean
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: legalName
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: payRate
  type: decimal
- container: ''
  name: payPeriod
  type: string
- container: ''
  name: payCurrency
  type: string
- container: ''
  name: employmentType
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zipCode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: providerName
  type: string
- container: ''
  name: benefitPlanType
  type: string
- container: ''
  name: employeeContribution
  type: decimal
- container: ''
  name: companyContribution
  type: decimal
- container: ''
  name: balance
  type: decimal
- container: ''
  name: grossPay
  type: decimal
- container: ''
  name: netPay
  type: decimal
property_count: 39
provider_name: Merge
provider_slug: merge
slug: merge-hris-api-context
source_filename: merge-hris-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"merge\": \"https://api.merge.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Employee\": \"merge:Employee\",\n    \"Company\": \"merge:Company\",\n    \"Employment\": \"merge:Employment\",\n    \"Team\": \"merge:Team\",\n    \"Location\": \"merge:Location\",\n    \"Benefit\": \"merge:Benefit\",\n    \"TimeOff\": \"merge:TimeOff\",\n    \"TimeOffBalance\": \"merge:TimeOffBalance\",\n    \"PayGroup\": \"merge:PayGroup\",\n    \"Group\": \"merge:Group\",\n    \"BankInfo\": \"merge:BankInfo\",\n    \"EmployeePayrollRun\": \"merge:EmployeePayrollRun\",\n    \"PayrollRun\": \"merge:PayrollRun\",\n\n    \"id\": { \"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\" },\n    \"remoteId\": { \"@id\": \"merge:remote_id\", \"@type\": \"xsd:string\" },\n    \"employeeNumber\": { \"@id\": \"merge:employee_number\"\
  , \"@type\": \"xsd:string\" },\n    \"firstName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"lastName\": { \"@id\": \"schema:familyName\", \"@type\": \"xsd:string\" },\n    \"displayFullName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"workEmail\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"personalEmail\": { \"@id\": \"merge:personal_email\", \"@type\": \"xsd:string\" },\n    \"mobilePhoneNumber\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"dateOfBirth\": { \"@id\": \"schema:birthDate\", \"@type\": \"xsd:date\" },\n    \"startDate\": { \"@id\": \"merge:start_date\", \"@type\": \"xsd:dateTime\" },\n    \"terminationDate\": { \"@id\": \"merge:termination_date\", \"@type\": \"xsd:dateTime\" },\n    \"employmentStatus\": { \"@id\": \"merge:employment_status\", \"@type\": \"xsd:string\" },\n    \"manager\": { \"@id\": \"merge:manager\", \"@type\": \"@id\" },\n    \"company\": { \"@id\": \"merge:company\"\
  , \"@type\": \"@id\" },\n    \"team\": { \"@id\": \"merge:team\", \"@type\": \"@id\" },\n    \"payGroup\": { \"@id\": \"merge:pay_group\", \"@type\": \"@id\" },\n    \"groups\": { \"@id\": \"merge:groups\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"remoteWasDeleted\": { \"@id\": \"merge:remote_was_deleted\", \"@type\": \"xsd:boolean\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifiedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"legalName\": { \"@id\": \"schema:legalName\", \"@type\": \"xsd:string\" },\n    \"jobTitle\": { \"@id\": \"schema:jobTitle\", \"@type\": \"xsd:string\" },\n    \"payRate\": { \"@id\": \"merge:pay_rate\", \"@type\": \"xsd:decimal\" },\n    \"payPeriod\": { \"@id\": \"merge:pay_period\", \"@type\": \"xsd:string\" },\n    \"payCurrency\": { \"@id\": \"merge:pay_currency\", \"@type\": \"xsd:string\" },\n    \"employmentType\": { \"@id\": \"merge:employment_type\", \"\
  @type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"city\": { \"@id\": \"schema:addressLocality\", \"@type\": \"xsd:string\" },\n    \"state\": { \"@id\": \"schema:addressRegion\", \"@type\": \"xsd:string\" },\n    \"zipCode\": { \"@id\": \"schema:postalCode\", \"@type\": \"xsd:string\" },\n    \"country\": { \"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\" },\n    \"providerName\": { \"@id\": \"merge:provider_name\", \"@type\": \"xsd:string\" },\n    \"benefitPlanType\": { \"@id\": \"merge:benefit_plan_type\", \"@type\": \"xsd:string\" },\n    \"employeeContribution\": { \"@id\": \"merge:employee_contribution\", \"@type\": \"xsd:decimal\" },\n    \"companyContribution\": { \"@id\": \"merge:company_contribution\", \"@type\": \"xsd:decimal\" },\n    \"balance\": { \"@id\": \"merge:balance\", \"@type\": \"xsd:decimal\" },\n    \"grossPay\": { \"@id\": \"merge:gross_pay\", \"@type\": \"xsd:decimal\" },\n    \"netPay\": { \"\
  @id\": \"merge:net_pay\", \"@type\": \"xsd:decimal\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-hris-api-context.jsonld
tags:
- Integrations
- Platform
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
