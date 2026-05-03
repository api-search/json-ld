---
api_specs:
- filename: workday-payroll-payroll-openapi.yml
  format: yaml
  label: Workday Payroll API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-payroll-openapi.yml
- filename: workday-payroll-payroll-results-openapi.yml
  format: yaml
  label: Workday Payroll Results API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-payroll-results-openapi.yml
- filename: workday-payroll-payroll-input-openapi.yml
  format: yaml
  label: Workday Payroll Input API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-payroll-input-openapi.yml
- filename: workday-payroll-tax-openapi.yml
  format: yaml
  label: Workday Tax API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-tax-openapi.yml
class_count: 15
classes:
- CreateTaxElectionRequest
- TaxElection
- TaxElectionCollection
- TaxFiling
- TaxFilingCollection
- TaxJurisdiction
- TaxJurisdictionCollection
- TaxJurisdictionRef
- TaxResult
- TaxResultCollection
- TaxWithholding
- TaxWithholdingCollection
- UpdateTaxWithholdingRequest
- WorkerRef
- WorkerTaxSummary
context_file: json-ld/workday-payroll-tax-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-tax-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Payroll Tax from Workday Payroll.
layout: jsonld
name: Workday Payroll Tax Context
namespaces:
- prefix: workday
  uri: https://community.workday.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: active
  type: boolean
- container: ''
  name: additionalWithholding
  type: double
- container: ''
  name: allowances
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: currency
  type: string
- container: set
  name: data
  type: reference
- container: ''
  name: deductions
  type: double
- container: ''
  name: dependentsAmount
  type: double
- container: ''
  name: descriptor
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: employeeAmount
  type: double
- container: ''
  name: employerAmount
  type: double
- container: ''
  name: exempt
  type: boolean
- container: ''
  name: filedDate
  type: date
- container: ''
  name: filingStatus
  type: string
- container: ''
  name: filingType
  type: string
- container: ''
  name: formNumber
  type: string
- container: ''
  name: formType
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: jurisdiction
  type: reference
- container: set
  name: jurisdictionBreakdown
  type: reference
- container: ''
  name: jurisdictionId
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: localityName
  type: string
- container: ''
  name: multipleJobs
  type: boolean
- container: ''
  name: otherIncome
  type: double
- container: ''
  name: quarter
  type: integer
- container: ''
  name: stateCode
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: submittedOn
  type: dateTime
- container: ''
  name: taxType
  type: string
- container: set
  name: taxTypes
  type: string
- container: ''
  name: taxYear
  type: integer
- container: ''
  name: taxableWages
  type: double
- container: ''
  name: total
  type: integer
- container: ''
  name: totalEmployerTax
  type: double
- container: ''
  name: totalFederalWithholding
  type: double
- container: ''
  name: totalGrossWages
  type: double
- container: ''
  name: totalLocalWithholding
  type: double
- container: ''
  name: totalMedicare
  type: double
- container: ''
  name: totalSocialSecurity
  type: double
- container: ''
  name: totalStateWithholding
  type: double
- container: ''
  name: totalTaxWithheld
  type: double
- container: ''
  name: totalTaxableWages
  type: double
- container: ''
  name: worker
  type: reference
property_count: 46
provider_name: Workday Payroll
provider_slug: workday-payroll
slug: workday-payroll-tax-context
source_filename: workday-payroll-tax-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateTaxElectionRequest\": \"workday:CreateTaxElectionRequest\",\n    \"TaxElection\": \"workday:TaxElection\",\n    \"TaxElectionCollection\": \"workday:TaxElectionCollection\",\n    \"TaxFiling\": \"workday:TaxFiling\",\n    \"TaxFilingCollection\": \"workday:TaxFilingCollection\",\n    \"TaxJurisdiction\": \"workday:TaxJurisdiction\",\n    \"TaxJurisdictionCollection\": \"workday:TaxJurisdictionCollection\",\n    \"TaxJurisdictionRef\": \"workday:TaxJurisdictionRef\",\n    \"TaxResult\": \"workday:TaxResult\",\n    \"TaxResultCollection\": \"workday:TaxResultCollection\",\n    \"TaxWithholding\": \"workday:TaxWithholding\",\n    \"TaxWithholdingCollection\": \"workday:TaxWithholdingCollection\",\n    \"UpdateTaxWithholdingRequest\"\
  : \"workday:UpdateTaxWithholdingRequest\",\n    \"WorkerRef\": \"workday:WorkerRef\",\n    \"WorkerTaxSummary\": \"workday:WorkerTaxSummary\",\n    \"active\": {\n      \"@id\": \"workday:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"additionalWithholding\": {\n      \"@id\": \"workday:additional_withholding\",\n      \"@type\": \"xsd:double\"\n    },\n    \"allowances\": {\n      \"@id\": \"workday:allowances\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"country\": {\n      \"@id\": \"workday:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"workday:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"workday:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deductions\": {\n      \"@id\": \"workday:deductions\",\n      \"@type\": \"xsd:double\"\n    },\n    \"dependentsAmount\": {\n      \"@id\": \"workday:dependents_amount\",\n      \"@type\": \"xsd:double\"\
  \n    },\n    \"descriptor\": {\n      \"@id\": \"workday:descriptor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dueDate\": {\n      \"@id\": \"workday:due_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"workday:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"employeeAmount\": {\n      \"@id\": \"workday:employee_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"employerAmount\": {\n      \"@id\": \"workday:employer_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"exempt\": {\n      \"@id\": \"workday:exempt\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"filedDate\": {\n      \"@id\": \"workday:filed_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"filingStatus\": {\n      \"@id\": \"workday:filing_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filingType\": {\n      \"@id\": \"workday:filing_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formNumber\": {\n      \"@id\": \"workday:form_number\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"formType\": {\n      \"@id\": \"workday:form_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"workday:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jurisdiction\": {\n      \"@id\": \"workday:jurisdiction\",\n      \"@type\": \"@id\"\n    },\n    \"jurisdictionBreakdown\": {\n      \"@id\": \"workday:jurisdiction_breakdown\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"jurisdictionId\": {\n      \"@id\": \"workday:jurisdiction_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"workday:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localityName\": {\n      \"@id\": \"workday:locality_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multipleJobs\": {\n      \"@id\": \"workday:multiple_jobs\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"otherIncome\": {\n      \"@id\": \"workday:other_income\",\n      \"@type\": \"xsd:double\"\
  \n    },\n    \"quarter\": {\n      \"@id\": \"workday:quarter\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stateCode\": {\n      \"@id\": \"workday:state_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"workday:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedOn\": {\n      \"@id\": \"workday:submitted_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"taxType\": {\n      \"@id\": \"workday:tax_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxTypes\": {\n      \"@id\": \"workday:tax_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxYear\": {\n      \"@id\": \"workday:tax_year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taxableWages\": {\n      \"@id\": \"workday:taxable_wages\",\n      \"@type\": \"xsd:double\"\n    },\n    \"total\": {\n      \"@id\": \"workday:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalEmployerTax\": {\n      \"@id\": \"\
  workday:total_employer_tax\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalFederalWithholding\": {\n      \"@id\": \"workday:total_federal_withholding\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalGrossWages\": {\n      \"@id\": \"workday:total_gross_wages\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalLocalWithholding\": {\n      \"@id\": \"workday:total_local_withholding\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalMedicare\": {\n      \"@id\": \"workday:total_medicare\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalSocialSecurity\": {\n      \"@id\": \"workday:total_social_security\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalStateWithholding\": {\n      \"@id\": \"workday:total_state_withholding\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalTaxWithheld\": {\n      \"@id\": \"workday:total_tax_withheld\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalTaxableWages\": {\n      \"@id\": \"workday:total_taxable_wages\"\
  ,\n      \"@type\": \"xsd:double\"\n    },\n    \"worker\": {\n      \"@id\": \"workday:worker\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-tax-context.jsonld
tags:
- Compensation
- Enterprise
- Human Resources
- Payroll
- SaaS
- Tax
- JSON-LD
- Linked Data
- Semantic Web
---
