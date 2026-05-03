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
class_count: 23
classes:
- CalculationStatus
- CreatePayRunRequest
- Deduction
- DeductionCode
- DeductionCodeCollection
- DeductionCodeRef
- DeductionCollection
- Earning
- EarningCode
- EarningCodeCollection
- EarningCodeRef
- EarningCollection
- Error
- PayGroup
- PayGroupCollection
- PayGroupRef
- PayPeriod
- PayRun
- PayRunCollection
- UpdatePayRunRequest
- WorkerCollection
- WorkerPayrollDetails
- WorkerRef
context_file: json-ld/workday-payroll-payroll-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-payroll-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Payroll Payroll from Workday Payroll.
layout: jsonld
name: Workday Payroll Payroll Context
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
  name: amount
  type: double
- container: ''
  name: annualSalary
  type: double
- container: ''
  name: compensationFrequency
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: completedOn
  type: dateTime
- container: ''
  name: country
  type: string
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: currency
  type: string
- container: set
  name: data
  type: reference
- container: ''
  name: deductionCode
  type: reference
- container: ''
  name: descriptor
  type: string
- container: set
  name: details
  type: reference
- container: ''
  name: earningCode
  type: reference
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: error
  type: string
- container: set
  name: errors
  type: reference
- container: ''
  name: field
  type: string
- container: ''
  name: frequency
  type: string
- container: ''
  name: hourlyRate
  type: double
- container: ''
  name: hours
  type: double
- container: ''
  name: id
  type: string
- container: ''
  name: inactive
  type: boolean
- container: ''
  name: message
  type: string
- container: ''
  name: payFrequency
  type: string
- container: ''
  name: payGroup
  type: reference
- container: ''
  name: payGroupId
  type: string
- container: ''
  name: payPeriod
  type: reference
- container: ''
  name: payRunId
  type: string
- container: ''
  name: paymentDate
  type: date
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: preTax
  type: boolean
- container: ''
  name: rate
  type: double
- container: ''
  name: runCategory
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: taxJurisdiction
  type: string
- container: ''
  name: taxable
  type: boolean
- container: ''
  name: total
  type: integer
- container: ''
  name: totalDeductions
  type: double
- container: ''
  name: totalGrossPay
  type: double
- container: ''
  name: totalNetPay
  type: double
- container: ''
  name: totalTaxes
  type: double
- container: ''
  name: type
  type: string
- container: ''
  name: workerCount
  type: integer
- container: ''
  name: workerDescriptor
  type: string
- container: ''
  name: workerId
  type: string
property_count: 49
provider_name: Workday Payroll
provider_slug: workday-payroll
slug: workday-payroll-payroll-context
source_filename: workday-payroll-payroll-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CalculationStatus\": \"workday:CalculationStatus\",\n    \"CreatePayRunRequest\": \"workday:CreatePayRunRequest\",\n    \"Deduction\": \"workday:Deduction\",\n    \"DeductionCode\": \"workday:DeductionCode\",\n    \"DeductionCodeCollection\": \"workday:DeductionCodeCollection\",\n    \"DeductionCodeRef\": \"workday:DeductionCodeRef\",\n    \"DeductionCollection\": \"workday:DeductionCollection\",\n    \"Earning\": \"workday:Earning\",\n    \"EarningCode\": \"workday:EarningCode\",\n    \"EarningCodeCollection\": \"workday:EarningCodeCollection\",\n    \"EarningCodeRef\": \"workday:EarningCodeRef\",\n    \"EarningCollection\": \"workday:EarningCollection\",\n    \"Error\": \"workday:Error\",\n    \"PayGroup\": \"workday:PayGroup\"\
  ,\n    \"PayGroupCollection\": \"workday:PayGroupCollection\",\n    \"PayGroupRef\": \"workday:PayGroupRef\",\n    \"PayPeriod\": \"workday:PayPeriod\",\n    \"PayRun\": \"workday:PayRun\",\n    \"PayRunCollection\": \"workday:PayRunCollection\",\n    \"UpdatePayRunRequest\": \"workday:UpdatePayRunRequest\",\n    \"WorkerCollection\": \"workday:WorkerCollection\",\n    \"WorkerPayrollDetails\": \"workday:WorkerPayrollDetails\",\n    \"WorkerRef\": \"workday:WorkerRef\",\n    \"active\": {\n      \"@id\": \"workday:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"amount\": {\n      \"@id\": \"workday:amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"annualSalary\": {\n      \"@id\": \"workday:annual_salary\",\n      \"@type\": \"xsd:double\"\n    },\n    \"compensationFrequency\": {\n      \"@id\": \"workday:compensation_frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"workday:completed_at\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"completedOn\": {\n      \"@id\": \"workday:completed_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"country\": {\n      \"@id\": \"workday:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"workday:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"workday:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deductionCode\": {\n      \"@id\": \"workday:deduction_code\",\n      \"@type\": \"@id\"\n    },\n    \"descriptor\": {\n      \"@id\": \"workday:descriptor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"workday:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"earningCode\": {\n      \"@id\": \"workday:earning_code\",\n      \"@type\": \"@id\"\n    },\n    \"effectiveDate\": {\n    \
  \  \"@id\": \"workday:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"workday:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"error\": {\n      \"@id\": \"workday:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"workday:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"field\": {\n      \"@id\": \"workday:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequency\": {\n      \"@id\": \"workday:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hourlyRate\": {\n      \"@id\": \"workday:hourly_rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"hours\": {\n      \"@id\": \"workday:hours\",\n      \"@type\": \"xsd:double\"\n    },\n    \"id\": {\n      \"@id\": \"workday:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inactive\": {\n      \"@id\": \"workday:inactive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"message\": {\n  \
  \    \"@id\": \"workday:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payFrequency\": {\n      \"@id\": \"workday:pay_frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payGroup\": {\n      \"@id\": \"workday:pay_group\",\n      \"@type\": \"@id\"\n    },\n    \"payGroupId\": {\n      \"@id\": \"workday:pay_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payPeriod\": {\n      \"@id\": \"workday:pay_period\",\n      \"@type\": \"@id\"\n    },\n    \"payRunId\": {\n      \"@id\": \"workday:pay_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentDate\": {\n      \"@id\": \"workday:payment_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"workday:payment_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preTax\": {\n      \"@id\": \"workday:pre_tax\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rate\": {\n      \"@id\": \"workday:rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"runCategory\"\
  : {\n      \"@id\": \"workday:run_category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"workday:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startedAt\": {\n      \"@id\": \"workday:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"workday:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxJurisdiction\": {\n      \"@id\": \"workday:tax_jurisdiction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxable\": {\n      \"@id\": \"workday:taxable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"total\": {\n      \"@id\": \"workday:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalDeductions\": {\n      \"@id\": \"workday:total_deductions\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalGrossPay\": {\n      \"@id\": \"workday:total_gross_pay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalNetPay\": {\n      \"@id\": \"workday:total_net_pay\",\n      \"\
  @type\": \"xsd:double\"\n    },\n    \"totalTaxes\": {\n      \"@id\": \"workday:total_taxes\",\n      \"@type\": \"xsd:double\"\n    },\n    \"type\": {\n      \"@id\": \"workday:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerCount\": {\n      \"@id\": \"workday:worker_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"workerDescriptor\": {\n      \"@id\": \"workday:worker_descriptor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerId\": {\n      \"@id\": \"workday:worker_id\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-payroll-context.jsonld
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
