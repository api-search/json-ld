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
class_count: 19
classes:
- Adjustment
- AdjustmentCollection
- CreateAdjustmentRequest
- CreateInputBatchRequest
- CreateOneTimePaymentRequest
- CreateSupplementalEarningRequest
- CreateTimeOffInputRequest
- InputBatch
- InputBatchCollection
- InputRecord
- OneTimePayment
- OneTimePaymentCollection
- SupplementalEarning
- SupplementalEarningCollection
- TimeOffInput
- TimeOffInputCollection
- UpdateOneTimePaymentRequest
- WorkerRef
- name
context_file: json-ld/workday-payroll-payroll-input-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-payroll-input-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Payroll Payroll Input from Workday Payroll.
layout: jsonld
name: Workday Payroll Payroll Input Context
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
  name: adjustmentType
  type: string
- container: ''
  name: amount
  type: double
- container: ''
  name: completedOn
  type: dateTime
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
  type: string
- container: ''
  name: descriptor
  type: string
- container: ''
  name: earningCode
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: failedRecords
  type: integer
- container: ''
  name: hours
  type: double
- container: ''
  name: id
  type: string
- container: ''
  name: inputType
  type: string
- container: ''
  name: originalPayRunId
  type: string
- container: ''
  name: paid
  type: boolean
- container: ''
  name: reason
  type: string
- container: ''
  name: recordCount
  type: integer
- container: set
  name: records
  type: reference
- container: ''
  name: startDate
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: submittedBy
  type: string
- container: ''
  name: submittedOn
  type: dateTime
- container: ''
  name: timeOffType
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: validRecords
  type: integer
- container: ''
  name: worker
  type: reference
- container: ''
  name: workerId
  type: string
property_count: 30
provider_name: Workday Payroll
provider_slug: workday-payroll
slug: workday-payroll-payroll-input-context
source_filename: workday-payroll-payroll-input-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Adjustment\": \"workday:Adjustment\",\n    \"AdjustmentCollection\": \"workday:AdjustmentCollection\",\n    \"CreateAdjustmentRequest\": \"workday:CreateAdjustmentRequest\",\n    \"CreateInputBatchRequest\": \"workday:CreateInputBatchRequest\",\n    \"CreateOneTimePaymentRequest\": \"workday:CreateOneTimePaymentRequest\",\n    \"CreateSupplementalEarningRequest\": \"workday:CreateSupplementalEarningRequest\",\n    \"CreateTimeOffInputRequest\": \"workday:CreateTimeOffInputRequest\",\n    \"InputBatch\": \"workday:InputBatch\",\n    \"InputBatchCollection\": \"workday:InputBatchCollection\",\n    \"InputRecord\": \"workday:InputRecord\",\n    \"OneTimePayment\": \"workday:OneTimePayment\",\n    \"OneTimePaymentCollection\"\
  : \"workday:OneTimePaymentCollection\",\n    \"SupplementalEarning\": \"workday:SupplementalEarning\",\n    \"SupplementalEarningCollection\": \"workday:SupplementalEarningCollection\",\n    \"TimeOffInput\": \"workday:TimeOffInput\",\n    \"TimeOffInputCollection\": \"workday:TimeOffInputCollection\",\n    \"UpdateOneTimePaymentRequest\": \"workday:UpdateOneTimePaymentRequest\",\n    \"WorkerRef\": \"workday:WorkerRef\",\n    \"adjustmentType\": {\n      \"@id\": \"workday:adjustment_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"workday:amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"completedOn\": {\n      \"@id\": \"workday:completed_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"workday:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"workday:data\",\n \
  \     \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deductionCode\": {\n      \"@id\": \"workday:deduction_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descriptor\": {\n      \"@id\": \"workday:descriptor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"earningCode\": {\n      \"@id\": \"workday:earning_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"workday:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"workday:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"failedRecords\": {\n      \"@id\": \"workday:failed_records\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hours\": {\n      \"@id\": \"workday:hours\",\n      \"@type\": \"xsd:double\"\n    },\n    \"id\": {\n      \"@id\": \"workday:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputType\": {\n      \"@id\": \"workday:input_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\"\
  : \"schema:name\",\n    \"originalPayRunId\": {\n      \"@id\": \"workday:original_pay_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paid\": {\n      \"@id\": \"workday:paid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reason\": {\n      \"@id\": \"workday:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordCount\": {\n      \"@id\": \"workday:record_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"records\": {\n      \"@id\": \"workday:records\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"startDate\": {\n      \"@id\": \"workday:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"workday:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedBy\": {\n      \"@id\": \"workday:submitted_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedOn\": {\n      \"@id\": \"workday:submitted_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeOffType\": {\n  \
  \    \"@id\": \"workday:time_off_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"workday:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"workday:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validRecords\": {\n      \"@id\": \"workday:valid_records\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"worker\": {\n      \"@id\": \"workday:worker\",\n      \"@type\": \"@id\"\n    },\n    \"workerId\": {\n      \"@id\": \"workday:worker_id\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/json-ld/workday-payroll-payroll-input-context.jsonld
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
