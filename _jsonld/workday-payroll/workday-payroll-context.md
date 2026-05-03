---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Workday Payroll API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/payroll/v1/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Workday Payroll Results API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/payroll-results/v1/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Workday Payroll Input API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/payroll-input/v1/openapi.yaml
- filename: workday-payroll-tax-openapi.yml
  format: yaml
  label: Workday Tax API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-tax-openapi.yml
class_count: 0
classes: []
context_file: json-ld/workday-payroll-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Payroll from Workday Payroll.
layout: jsonld
name: Workday Payroll Context
namespaces:
- prefix: workday
  uri: https://community.workday.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: PayRun
  type: ''
- container: ''
  name: PayGroup
  type: ''
- container: ''
  name: Payslip
  type: ''
- container: ''
  name: Worker
  type: ''
- container: ''
  name: Earning
  type: ''
- container: ''
  name: Deduction
  type: ''
- container: ''
  name: TaxWithholding
  type: ''
- container: ''
  name: TaxElection
  type: ''
- container: ''
  name: Payment
  type: ''
- container: ''
  name: TaxJurisdiction
  type: ''
- container: ''
  name: OneTimePayment
  type: ''
- container: ''
  name: PayPeriod
  type: ''
property_count: 12
provider_name: Workday Payroll
provider_slug: workday-payroll
slug: workday-payroll-context
source_filename: workday-payroll-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"PayRun\": {\n      \"@id\": \"workday:PayRun\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"status\": \"workday:payRunStatus\",\n        \"runCategory\": \"workday:runCategory\",\n        \"paymentDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalGrossPay\": {\n          \"@id\": \"workday:totalGrossPay\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalNetPay\": {\n          \"@id\": \"workday:totalNetPay\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalDeductions\": {\n          \"@id\": \"workday:totalDeductions\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalTaxes\"\
  : {\n          \"@id\": \"workday:totalTaxes\",\n          \"@type\": \"xsd:double\"\n        },\n        \"workerCount\": {\n          \"@id\": \"workday:workerCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currency\": \"schema:currency\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedOn\": {\n          \"@id\": \"workday:completedOn\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PayGroup\": {\n      \"@id\": \"workday:PayGroup\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"payFrequency\": \"workday:payFrequency\",\n        \"currency\": \"schema:currency\",\n        \"country\": \"schema:addressCountry\",\n        \"workerCount\": {\n          \"@id\": \"workday:workerCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"inactive\": {\n          \"@id\": \"workday:inactive\",\n          \"@type\"\
  : \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Payslip\": {\n      \"@id\": \"workday:Payslip\",\n      \"@context\": {\n        \"paymentDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"grossPay\": {\n          \"@id\": \"workday:grossPay\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netPay\": {\n          \"@id\": \"workday:netPay\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalEarnings\": {\n          \"@id\": \"workday:totalEarnings\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalDeductions\": {\n          \"@id\": \"workday:totalDeductions\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalTaxes\": {\n          \"@id\": \"workday:totalTaxes\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currency\": \"schema:currency\",\n        \"yearToDateGross\": {\n          \"@id\": \"workday:yearToDateGross\",\n          \"@type\"\
  : \"xsd:double\"\n        },\n        \"yearToDateNet\": {\n          \"@id\": \"workday:yearToDateNet\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"Worker\": {\n      \"@id\": \"workday:Worker\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"paymentMethod\": \"workday:paymentMethod\",\n        \"annualSalary\": {\n          \"@id\": \"workday:annualSalary\",\n          \"@type\": \"xsd:double\"\n        },\n        \"hourlyRate\": {\n          \"@id\": \"workday:hourlyRate\",\n          \"@type\": \"xsd:double\"\n        },\n        \"compensationFrequency\": \"workday:compensationFrequency\",\n        \"currency\": \"schema:currency\",\n        \"taxJurisdiction\": \"workday:taxJurisdiction\"\n      }\n    },\n\n    \"Earning\": {\n      \"@id\": \"workday:Earning\",\n      \"@context\": {\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:double\"\n        },\n        \"hours\": {\n  \
  \        \"@id\": \"workday:hours\",\n          \"@type\": \"xsd:double\"\n        },\n        \"rate\": {\n          \"@id\": \"workday:rate\",\n          \"@type\": \"xsd:double\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"workday:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Deduction\": {\n      \"@id\": \"workday:Deduction\",\n      \"@context\": {\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:double\"\n        },\n        \"frequency\": \"workday:frequency\",\n        \"preTax\": {\n          \"@id\": \"workday:preTax\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"workday:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"TaxWithholding\": {\n      \"@id\": \"workday:TaxWithholding\",\n      \"@context\": {\n        \"taxType\": \"workday:taxType\",\n        \"filingStatus\": \"workday:filingStatus\"\
  ,\n        \"allowances\": {\n          \"@id\": \"workday:allowances\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"additionalWithholding\": {\n          \"@id\": \"workday:additionalWithholding\",\n          \"@type\": \"xsd:double\"\n        },\n        \"exempt\": {\n          \"@id\": \"workday:exempt\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"workday:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"TaxElection\": {\n      \"@id\": \"workday:TaxElection\",\n      \"@context\": {\n        \"formType\": \"workday:formType\",\n        \"filingStatus\": \"workday:filingStatus\",\n        \"multipleJobs\": {\n          \"@id\": \"workday:multipleJobs\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dependentsAmount\": {\n          \"@id\": \"workday:dependentsAmount\",\n          \"@type\": \"xsd:double\"\n        },\n        \"additionalWithholding\": {\n\
  \          \"@id\": \"workday:additionalWithholding\",\n          \"@type\": \"xsd:double\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"workday:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"submittedOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Payment\": {\n      \"@id\": \"workday:Payment\",\n      \"@context\": {\n        \"paymentMethod\": \"workday:paymentMethod\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currency\": \"schema:currency\",\n        \"paymentDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"settlementDate\": {\n          \"@id\": \"workday:settlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"workday:paymentStatus\"\n      }\n    },\n\n    \"TaxJurisdiction\": {\n \
  \     \"@id\": \"workday:TaxJurisdiction\",\n      \"@context\": {\n        \"descriptor\": \"schema:name\",\n        \"level\": \"workday:jurisdictionLevel\",\n        \"country\": \"schema:addressCountry\",\n        \"stateCode\": \"workday:stateCode\",\n        \"localityName\": \"workday:localityName\",\n        \"active\": {\n          \"@id\": \"workday:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"OneTimePayment\": {\n      \"@id\": \"workday:OneTimePayment\",\n      \"@context\": {\n        \"earningCode\": \"workday:earningCode\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currency\": \"schema:currency\",\n        \"reason\": \"schema:description\",\n        \"effectiveDate\": {\n          \"@id\": \"workday:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"workday:inputStatus\",\n        \"createdOn\": {\n          \"@id\":\
  \ \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PayPeriod\": {\n      \"@id\": \"workday:PayPeriod\",\n      \"@context\": {\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-context.jsonld
tags:
- Compensation
- Enterprise
- Human-Resources
- Payroll
- Saas
- Tax
- JSON-LD
- Linked Data
- Semantic Web
---
