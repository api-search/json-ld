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
class_count: 14
classes:
- PayPeriod
- PayRunResult
- Payment
- PaymentCollection
- PaymentElection
- PaymentElectionCollection
- Payslip
- PayslipCollection
- PayslipDeductionLine
- PayslipEarningLine
- PayslipTaxLine
- WorkerRef
- WorkerResult
- WorkerResultCollection
context_file: json-ld/workday-payroll-payroll-results-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-payroll-results-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Payroll Payroll Results from Workday Payroll.
layout: jsonld
name: Workday Payroll Payroll Results Context
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
  name: accountType
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: amount
  type: double
- container: ''
  name: bankAccount
  type: reference
- container: ''
  name: bankName
  type: string
- container: ''
  name: checkNumber
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: currentAmount
  type: double
- container: ''
  name: currentHours
  type: double
- container: set
  name: data
  type: reference
- container: ''
  name: deductionCode
  type: string
- container: set
  name: deductions
  type: reference
- container: ''
  name: descriptor
  type: string
- container: ''
  name: distributionType
  type: string
- container: ''
  name: earningCode
  type: string
- container: set
  name: earnings
  type: reference
- container: ''
  name: employeeAmount
  type: double
- container: ''
  name: employerAmount
  type: double
- container: ''
  name: endDate
  type: date
- container: ''
  name: grossPay
  type: double
- container: ''
  name: id
  type: string
- container: ''
  name: lastFourDigits
  type: string
- container: ''
  name: netPay
  type: double
- container: ''
  name: order
  type: integer
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
  name: percentage
  type: double
- container: ''
  name: preTax
  type: boolean
- container: ''
  name: rate
  type: double
- container: ''
  name: settlementDate
  type: date
- container: ''
  name: startDate
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: taxAuthority
  type: string
- container: ''
  name: taxType
  type: string
- container: set
  name: taxes
  type: reference
- container: ''
  name: total
  type: integer
- container: ''
  name: totalDeductions
  type: double
- container: ''
  name: totalEarnings
  type: double
- container: ''
  name: totalEmployeeTaxes
  type: double
- container: ''
  name: totalEmployerTaxes
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
  name: worker
  type: reference
- container: ''
  name: workerCount
  type: integer
- container: ''
  name: yearToDateAmount
  type: double
- container: ''
  name: yearToDateEmployee
  type: double
- container: ''
  name: yearToDateEmployer
  type: double
- container: ''
  name: yearToDateGross
  type: double
- container: ''
  name: yearToDateNet
  type: double
- container: ''
  name: yearToDateTaxes
  type: double
property_count: 53
provider_name: Workday Payroll
provider_slug: workday-payroll
slug: workday-payroll-payroll-results-context
source_filename: workday-payroll-payroll-results-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayPeriod\": \"workday:PayPeriod\",\n    \"PayRunResult\": \"workday:PayRunResult\",\n    \"Payment\": \"workday:Payment\",\n    \"PaymentCollection\": \"workday:PaymentCollection\",\n    \"PaymentElection\": \"workday:PaymentElection\",\n    \"PaymentElectionCollection\": \"workday:PaymentElectionCollection\",\n    \"Payslip\": \"workday:Payslip\",\n    \"PayslipCollection\": \"workday:PayslipCollection\",\n    \"PayslipDeductionLine\": \"workday:PayslipDeductionLine\",\n    \"PayslipEarningLine\": \"workday:PayslipEarningLine\",\n    \"PayslipTaxLine\": \"workday:PayslipTaxLine\",\n    \"WorkerRef\": \"workday:WorkerRef\",\n    \"WorkerResult\": \"workday:WorkerResult\",\n    \"WorkerResultCollection\": \"workday:WorkerResultCollection\"\
  ,\n    \"accountType\": {\n      \"@id\": \"workday:account_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"workday:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"amount\": {\n      \"@id\": \"workday:amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"bankAccount\": {\n      \"@id\": \"workday:bank_account\",\n      \"@type\": \"@id\"\n    },\n    \"bankName\": {\n      \"@id\": \"workday:bank_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkNumber\": {\n      \"@id\": \"workday:check_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"workday:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentAmount\": {\n      \"@id\": \"workday:current_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"currentHours\": {\n      \"@id\": \"workday:current_hours\",\n      \"@type\": \"xsd:double\"\n    },\n    \"data\": {\n      \"@id\": \"workday:data\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deductionCode\": {\n      \"@id\": \"workday:deduction_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deductions\": {\n      \"@id\": \"workday:deductions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"descriptor\": {\n      \"@id\": \"workday:descriptor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distributionType\": {\n      \"@id\": \"workday:distribution_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"earningCode\": {\n      \"@id\": \"workday:earning_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"earnings\": {\n      \"@id\": \"workday:earnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"employeeAmount\": {\n      \"@id\": \"workday:employee_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"employerAmount\": {\n      \"@id\": \"workday:employer_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"endDate\": {\n      \"@id\"\
  : \"workday:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"grossPay\": {\n      \"@id\": \"workday:gross_pay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"id\": {\n      \"@id\": \"workday:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastFourDigits\": {\n      \"@id\": \"workday:last_four_digits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"netPay\": {\n      \"@id\": \"workday:net_pay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"order\": {\n      \"@id\": \"workday:order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"payPeriod\": {\n      \"@id\": \"workday:pay_period\",\n      \"@type\": \"@id\"\n    },\n    \"payRunId\": {\n      \"@id\": \"workday:pay_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentDate\": {\n      \"@id\": \"workday:payment_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"workday:payment_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentage\": {\n   \
  \   \"@id\": \"workday:percentage\",\n      \"@type\": \"xsd:double\"\n    },\n    \"preTax\": {\n      \"@id\": \"workday:pre_tax\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rate\": {\n      \"@id\": \"workday:rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"settlementDate\": {\n      \"@id\": \"workday:settlement_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startDate\": {\n      \"@id\": \"workday:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"workday:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxAuthority\": {\n      \"@id\": \"workday:tax_authority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxType\": {\n      \"@id\": \"workday:tax_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxes\": {\n      \"@id\": \"workday:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"total\": {\n      \"@id\": \"workday:total\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"totalDeductions\": {\n      \"@id\": \"workday:total_deductions\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalEarnings\": {\n      \"@id\": \"workday:total_earnings\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalEmployeeTaxes\": {\n      \"@id\": \"workday:total_employee_taxes\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalEmployerTaxes\": {\n      \"@id\": \"workday:total_employer_taxes\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalGrossPay\": {\n      \"@id\": \"workday:total_gross_pay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalNetPay\": {\n      \"@id\": \"workday:total_net_pay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalTaxes\": {\n      \"@id\": \"workday:total_taxes\",\n      \"@type\": \"xsd:double\"\n    },\n    \"worker\": {\n      \"@id\": \"workday:worker\",\n      \"@type\": \"@id\"\n    },\n    \"workerCount\": {\n      \"@id\": \"workday:worker_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  yearToDateAmount\": {\n      \"@id\": \"workday:year_to_date_amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"yearToDateEmployee\": {\n      \"@id\": \"workday:year_to_date_employee\",\n      \"@type\": \"xsd:double\"\n    },\n    \"yearToDateEmployer\": {\n      \"@id\": \"workday:year_to_date_employer\",\n      \"@type\": \"xsd:double\"\n    },\n    \"yearToDateGross\": {\n      \"@id\": \"workday:year_to_date_gross\",\n      \"@type\": \"xsd:double\"\n    },\n    \"yearToDateNet\": {\n      \"@id\": \"workday:year_to_date_net\",\n      \"@type\": \"xsd:double\"\n    },\n    \"yearToDateTaxes\": {\n      \"@id\": \"workday:year_to_date_taxes\",\n      \"@type\": \"xsd:double\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-payroll-results-context.jsonld
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
