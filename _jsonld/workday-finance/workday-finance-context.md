---
api_specs:
- filename: workday-finance-financial-management-openapi.yml
  format: yaml
  label: Workday Financial Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-finance/refs/heads/main/openapi/workday-finance-financial-management-openapi.yml
- filename: workday-finance-procurement-openapi.yml
  format: yaml
  label: Workday Resource Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-finance/refs/heads/main/openapi/workday-finance-procurement-openapi.yml
class_count: 35
classes:
- JournalEntry
- Account
- CostCenter
- Worktag
- FinancialPeriod
- Supplier
- PurchaseOrder
- SupplierInvoice
- Requisition
- id
- descriptor
- name
- description
- status
- href
- journalEntryNumber
- postingDate
- lines
- currency
- worktags
- accountNumber
- accountType
- balance
- invoiceNumber
- invoiceDate
- dueDate
- totalAmount
- purchaseOrderNumber
- orderDate
- fiscalYear
- startDate
- endDate
- supplierNumber
- paymentTerms
- taxId
context_file: json-ld/workday-finance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-finance/refs/heads/main/json-ld/workday-finance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Finance from Workday Finance.
layout: jsonld
name: Workday Finance Context
namespaces:
- prefix: wd
  uri: https://www.workday.com/ontology/finance/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: period
  type: reference
- container: ''
  name: debitAmount
  type: schema:MonetaryAmount
- container: ''
  name: creditAmount
  type: schema:MonetaryAmount
- container: ''
  name: company
  type: reference
- container: ''
  name: supplier
  type: reference
- container: ''
  name: purchaseOrder
  type: reference
property_count: 6
provider_name: Workday Finance
provider_slug: workday-finance
slug: workday-finance-context
source_filename: workday-finance-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wd\": \"https://www.workday.com/ontology/finance/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"JournalEntry\": \"wd:JournalEntry\",\n    \"Account\": \"wd:Account\",\n    \"CostCenter\": \"wd:CostCenter\",\n    \"Worktag\": \"wd:Worktag\",\n    \"FinancialPeriod\": \"wd:FinancialPeriod\",\n    \"Supplier\": \"schema:Organization\",\n    \"PurchaseOrder\": \"schema:Order\",\n    \"SupplierInvoice\": \"schema:Invoice\",\n    \"Requisition\": \"wd:Requisition\",\n\n    \"id\": \"@id\",\n    \"descriptor\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"wd:status\",\n    \"href\": \"schema:url\",\n\n    \"journalEntryNumber\": \"wd:journalEntryNumber\",\n    \"postingDate\": \"schema:datePosted\",\n    \"period\": {\"@id\": \"wd:period\", \"@type\": \"@id\"},\n    \"lines\": \"wd:lines\",\n    \"debitAmount\": {\"\
  @id\": \"fibo:debitAmount\", \"@type\": \"schema:MonetaryAmount\"},\n    \"creditAmount\": {\"@id\": \"fibo:creditAmount\", \"@type\": \"schema:MonetaryAmount\"},\n    \"currency\": \"schema:currency\",\n    \"worktags\": \"wd:worktags\",\n\n    \"accountNumber\": \"wd:accountNumber\",\n    \"accountType\": \"wd:accountType\",\n    \"balance\": \"schema:amount\",\n    \"company\": {\"@id\": \"schema:legalName\", \"@type\": \"@id\"},\n\n    \"invoiceNumber\": \"schema:confirmationNumber\",\n    \"invoiceDate\": \"schema:dateIssued\",\n    \"dueDate\": \"schema:paymentDueDate\",\n    \"totalAmount\": \"schema:totalPaymentDue\",\n    \"supplier\": {\"@id\": \"schema:seller\", \"@type\": \"@id\"},\n    \"purchaseOrder\": {\"@id\": \"schema:referencesOrder\", \"@type\": \"@id\"},\n\n    \"purchaseOrderNumber\": \"schema:orderNumber\",\n    \"orderDate\": \"schema:orderDate\",\n\n    \"fiscalYear\": \"wd:fiscalYear\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\"\
  ,\n\n    \"supplierNumber\": \"wd:supplierNumber\",\n    \"paymentTerms\": \"wd:paymentTerms\",\n    \"taxId\": \"wd:taxId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-finance/refs/heads/main/json-ld/workday-finance-context.jsonld
tags:
- Accounting
- Cloud
- Enterprise
- ERP
- Finance
- Financial Management
- JSON-LD
- Linked Data
- Semantic Web
---
