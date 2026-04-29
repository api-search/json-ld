---
api_specs:
- filename: agave-unified-api-openapi.yml
  format: yaml
  label: Agave Unified Construction API
  slug: unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agave/refs/heads/main/openapi/agave-unified-api-openapi.yml
class_count: 24
classes:
- EmployeeList
- CostCodeList
- TimesheetList
- Contract
- name
- ContractList
- Budget
- description
- LinkSessionRequest
- VendorList
- LinkSession
- ProjectList
- Timesheet
- BudgetList
- Invoice
- Project
- createdAt
- updatedAt
- Vendor
- email
- Employee
- InvoiceList
- CostCode
- InvoiceRequest
context_file: json-ld/agave-unified-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agave/refs/heads/main/json-ld/agave-unified-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agave Unified from Agave.
layout: jsonld
name: Agave Unified Context
namespaces:
- prefix: agave
  uri: https://agave.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: data
  type: string
- container: ''
  name: nextCursor
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: originalValue
  type: decimal
- container: ''
  name: revisedValue
  type: decimal
- container: ''
  name: executedDate
  type: date
- container: ''
  name: costCodeId
  type: string
- container: ''
  name: originalAmount
  type: decimal
- container: ''
  name: revisedAmount
  type: decimal
- container: ''
  name: actualCost
  type: decimal
- container: ''
  name: projectedCost
  type: decimal
- container: ''
  name: referenceId
  type: string
- container: ''
  name: redirectUrl
  type: string
- container: ''
  name: linkToken
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: employeeId
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: regularHours
  type: decimal
- container: ''
  name: overtimeHours
  type: decimal
- container: ''
  name: payRate
  type: decimal
- container: ''
  name: vendorId
  type: string
- container: ''
  name: invoiceNumber
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: sourceId
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: estimatedCompletionDate
  type: date
- container: ''
  name: totalBudget
  type: decimal
- container: ''
  name: phone
  type: string
- container: ''
  name: taxId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: hireDate
  type: date
- container: ''
  name: code
  type: string
- container: ''
  name: costType
  type: string
property_count: 42
provider_name: Agave
provider_slug: agave
slug: agave-unified-context
source_filename: agave-unified-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agave\": \"https://agave.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmployeeList\": \"agave:EmployeeList\",\n    \"data\": {\n      \"@id\": \"agave:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextCursor\": {\n      \"@id\": \"agave:next_cursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"agave:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CostCodeList\": \"agave:CostCodeList\",\n    \"TimesheetList\": \"agave:TimesheetList\",\n    \"Contract\": \"agave:Contract\",\n    \"id\": {\n      \"@id\": \"agave:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"agave:project_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"number\": {\n      \"@id\"\
  : \"agave:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"agave:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalValue\": {\n      \"@id\": \"agave:original_value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"revisedValue\": {\n      \"@id\": \"agave:revised_value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"executedDate\": {\n      \"@id\": \"agave:executed_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"ContractList\": \"agave:ContractList\",\n    \"Budget\": \"agave:Budget\",\n    \"costCodeId\": {\n      \"@id\": \"agave:cost_code_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"originalAmount\": {\n      \"@id\": \"agave:original_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"revisedAmount\": {\n      \"@id\": \"agave:revised_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"actualCost\": {\n      \"@id\": \"agave:actual_cost\",\n    \
  \  \"@type\": \"xsd:decimal\"\n    },\n    \"projectedCost\": {\n      \"@id\": \"agave:projected_cost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LinkSessionRequest\": \"agave:LinkSessionRequest\",\n    \"referenceId\": {\n      \"@id\": \"agave:reference_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"agave:redirect_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VendorList\": \"agave:VendorList\",\n    \"LinkSession\": \"agave:LinkSession\",\n    \"linkToken\": {\n      \"@id\": \"agave:link_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"agave:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ProjectList\": \"agave:ProjectList\",\n    \"Timesheet\": \"agave:Timesheet\",\n    \"employeeId\": {\n      \"@id\": \"agave:employee_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"agave:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"regularHours\"\
  : {\n      \"@id\": \"agave:regular_hours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"overtimeHours\": {\n      \"@id\": \"agave:overtime_hours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"payRate\": {\n      \"@id\": \"agave:pay_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"BudgetList\": \"agave:BudgetList\",\n    \"Invoice\": \"agave:Invoice\",\n    \"vendorId\": {\n      \"@id\": \"agave:vendor_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoiceNumber\": {\n      \"@id\": \"agave:invoice_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"agave:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"invoiceDate\": {\n      \"@id\": \"agave:invoice_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dueDate\": {\n      \"@id\": \"agave:due_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"Project\": \"agave:Project\",\n    \"sourceId\": {\n      \"@id\": \"agave:source_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"address\": {\n      \"@id\": \"agave:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"agave:start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"estimatedCompletionDate\": {\n      \"@id\": \"agave:estimated_completion_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalBudget\": {\n      \"@id\": \"agave:total_budget\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"Vendor\": \"agave:Vendor\",\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"agave:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"agave:tax_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Employee\": \"agave:Employee\",\n    \"firstName\": {\n      \"@id\": \"agave:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"agave:last_name\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"agave:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hireDate\": {\n      \"@id\": \"agave:hire_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"InvoiceList\": \"agave:InvoiceList\",\n    \"CostCode\": \"agave:CostCode\",\n    \"code\": {\n      \"@id\": \"agave:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"costType\": {\n      \"@id\": \"agave:cost_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvoiceRequest\": \"agave:InvoiceRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agave/refs/heads/main/json-ld/agave-unified-context.jsonld
tags:
- Accounting
- Construction
- Integration
- JSON-LD
- Linked Data
- Semantic Web
---
