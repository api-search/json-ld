---
api_specs:
- filename: adp-workers-openapi.yml
  format: yaml
  label: ADP Workers API
  slug: adp-workers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adp/refs/heads/main/openapi/adp-workers-openapi.yml
- filename: adp-payroll-openapi.yml
  format: yaml
  label: ADP Payroll API
  slug: adp-payroll-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adp/refs/heads/main/openapi/adp-payroll-openapi.yml
class_count: 0
classes: []
context_file: json-ld/adp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adp/refs/heads/main/json-ld/adp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adp from ADP.
layout: jsonld
name: Adp Context
namespaces:
- prefix: adp
  uri: https://developers.adp.com/articles/api/
- prefix: schema
  uri: https://schema.org/
- prefix: hr
  uri: https://www.hr-xml.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Worker
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: WorkAssignment
  type: ''
- container: ''
  name: PayrollOutput
  type: ''
- container: ''
  name: Address
  type: ''
property_count: 5
provider_name: ADP
provider_slug: adp
slug: adp-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adp\": \"https://developers.adp.com/articles/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"hr\": \"https://www.hr-xml.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Worker\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"associateOID\": {\"@id\": \"adp:associateOID\", \"@type\": \"xsd:string\"},\n        \"workerID\": {\"@id\": \"adp:workerID\"},\n        \"person\": {\"@id\": \"schema:person\"},\n        \"workerDates\": {\"@id\": \"adp:workerDates\"},\n        \"workAssignments\": {\"@id\": \"adp:workAssignment\", \"@container\": \"@set\"},\n        \"workerStatus\": {\"@id\": \"adp:workerStatus\"}\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"legalName\": {\"@id\": \"schema:legalName\"},\n        \"givenName\": {\"@id\": \"schema:givenName\"},\n        \"familyName1\": {\"@id\": \"schema:familyName\"},\n\
  \        \"birthDate\": {\"@id\": \"schema:birthDate\", \"@type\": \"xsd:date\"},\n        \"genderCode\": {\"@id\": \"schema:gender\"},\n        \"legalAddress\": {\"@id\": \"schema:address\"},\n        \"communication\": {\"@id\": \"schema:contactPoint\"}\n      }\n    },\n\n    \"WorkAssignment\": {\n      \"@id\": \"schema:EmployeeRole\",\n      \"@context\": {\n        \"itemID\": {\"@id\": \"adp:assignmentItemID\"},\n        \"primaryIndicator\": {\"@id\": \"adp:primaryAssignment\", \"@type\": \"xsd:boolean\"},\n        \"hireDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n        \"jobTitle\": {\"@id\": \"schema:title\"},\n        \"positionID\": {\"@id\": \"adp:positionID\"},\n        \"jobCode\": {\"@id\": \"adp:jobCode\"},\n        \"standardHours\": {\"@id\": \"adp:standardHours\"},\n        \"annualBaseRemuneration\": {\"@id\": \"schema:baseSalary\"},\n        \"workerTypeCode\": {\"@id\": \"adp:workerType\"},\n        \"homeOrganizationalUnits\": {\"@id\"\
  : \"schema:memberOf\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"PayrollOutput\": {\n      \"@id\": \"adp:PayrollOutput\",\n      \"@context\": {\n        \"payrollOutputID\": {\"@id\": \"adp:payrollOutputID\"},\n        \"payDate\": {\"@id\": \"schema:paymentDueDate\", \"@type\": \"xsd:date\"},\n        \"grossPayAmount\": {\"@id\": \"adp:grossPay\"},\n        \"netPayAmount\": {\"@id\": \"adp:netPay\"},\n        \"totalDeductionsAmount\": {\"@id\": \"adp:totalDeductions\"},\n        \"totalTaxesAmount\": {\"@id\": \"adp:totalTaxes\"}\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"lineOne\": {\"@id\": \"schema:streetAddress\"},\n        \"cityName\": {\"@id\": \"schema:addressLocality\"},\n        \"countrySubdivisionLevel1\": {\"@id\": \"schema:addressRegion\"},\n        \"postalCode\": {\"@id\": \"schema:postalCode\"},\n        \"countryCode\": {\"@id\": \"schema:addressCountry\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adp/refs/heads/main/json-ld/adp-context.jsonld
tags:
- Benefits
- HCM
- HR
- Payroll
- Workforce
- JSON-LD
- Linked Data
- Semantic Web
---
