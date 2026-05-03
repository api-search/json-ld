---
api_specs:
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Expense Report v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Expense Entry v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Quick Expense v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Receipt Image v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sap-concur-expense-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/json-ld/sap-concur-expense-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Concur Expense from SAP Concur Expense.
layout: jsonld
name: Sap Concur Expense Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: concur
  uri: https://developer.concur.com/ontology/expense#
- prefix: sap
  uri: https://api.sap.com/ontology#
properties:
- container: ''
  name: ExpenseReport
  type: reference
- container: ''
  name: ExpenseEntry
  type: reference
- container: ''
  name: QuickExpense
  type: reference
- container: ''
  name: ReceiptImage
  type: reference
- container: ''
  name: PaymentBatch
  type: reference
- container: ''
  name: ID
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Total
  type: decimal
- container: ''
  name: CurrencyCode
  type: string
- container: ''
  name: TransactionDate
  type: date
- container: ''
  name: TransactionAmount
  type: decimal
- container: ''
  name: TransactionCurrencyCode
  type: string
- container: ''
  name: VendorDescription
  type: string
- container: ''
  name: LocationName
  type: string
- container: ''
  name: BusinessPurpose
  type: string
- container: ''
  name: OwnerLoginID
  type: string
- container: ''
  name: OwnerName
  type: string
- container: ''
  name: SubmitDate
  type: dateTime
- container: ''
  name: CreateDate
  type: dateTime
- container: ''
  name: ApprovalStatusCode
  type: string
- container: ''
  name: PaymentStatusCode
  type: string
- container: ''
  name: ExpenseTypeCode
  type: string
- container: ''
  name: ExpenseTypeName
  type: string
- container: ''
  name: ReceiptImageID
  type: string
- container: ''
  name: IsItemized
  type: boolean
- container: ''
  name: PolicyID
  type: string
- container: ''
  name: ReportID
  type: string
- container: ''
  name: EntryID
  type: string
- container: ''
  name: Percentage
  type: decimal
- container: ''
  name: AccountCode1
  type: string
- container: ''
  name: BatchID
  type: string
- container: ''
  name: BatchTotal
  type: decimal
- container: ''
  name: PaymentMethod
  type: string
- container: ''
  name: URI
  type: reference
property_count: 34
provider_name: SAP Concur Expense
provider_slug: sap-concur-expense
slug: sap-concur-expense-context
source_filename: sap-concur-expense-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"concur\": \"https://developer.concur.com/ontology/expense#\",\n    \"sap\": \"https://api.sap.com/ontology#\",\n\n    \"ExpenseReport\": {\n      \"@id\": \"concur:ExpenseReport\",\n      \"@type\": \"@id\",\n      \"description\": \"An expense report aggregating employee business expenses for reimbursement\"\n    },\n    \"ExpenseEntry\": {\n      \"@id\": \"concur:ExpenseEntry\",\n      \"@type\": \"@id\",\n      \"description\": \"A single expense line item within an expense report\"\n    },\n    \"QuickExpense\": {\n      \"@id\": \"concur:QuickExpense\",\n      \"@type\": \"@id\",\n      \"description\": \"An unassigned expense captured before being added to a formal report\"\n    },\n    \"ReceiptImage\": {\n      \"@id\": \"concur:ReceiptImage\",\n      \"@type\": \"@id\",\n      \"description\": \"A digital receipt image\
  \ attached to an expense entry\"\n    },\n    \"PaymentBatch\": {\n      \"@id\": \"concur:PaymentBatch\",\n      \"@type\": \"@id\",\n      \"description\": \"A batch of approved expense reports grouped for reimbursement payment\"\n    },\n\n    \"ID\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Total\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CurrencyCode\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactionDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"TransactionAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"TransactionCurrencyCode\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VendorDescription\": {\n\
  \      \"@id\": \"schema:vendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LocationName\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BusinessPurpose\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerLoginID\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubmitDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreateDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ApprovalStatusCode\": {\n      \"@id\": \"concur:approvalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentStatusCode\": {\n      \"@id\": \"concur:paymentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpenseTypeCode\": {\n      \"@id\": \"concur:expenseType\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"ExpenseTypeName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReceiptImageID\": {\n      \"@id\": \"concur:receiptImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsItemized\": {\n      \"@id\": \"concur:isItemized\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"PolicyID\": {\n      \"@id\": \"concur:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReportID\": {\n      \"@id\": \"concur:report\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntryID\": {\n      \"@id\": \"concur:entry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Percentage\": {\n      \"@id\": \"schema:percentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"AccountCode1\": {\n      \"@id\": \"concur:glAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchID\": {\n      \"@id\": \"concur:paymentBatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchTotal\": {\n      \"@id\": \"schema:totalPrice\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PaymentMethod\": {\n      \"@id\": \"schema:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"URI\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/json-ld/sap-concur-expense-context.jsonld
tags:
- Expense Management
- Financial Management
- Receipts
- Reimbursement
- Reporting
- SAP
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
