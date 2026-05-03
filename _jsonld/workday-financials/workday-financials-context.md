---
api_specs:
- filename: Financial_Management.json
  format: json
  label: Workday Financial Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json
- filename: Revenue_Management.json
  format: json
  label: Workday Revenue Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Revenue_Management/v38.2/Revenue_Management.json
- filename: Expenses.json
  format: json
  label: Workday Expenses API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Expenses/v38.2/Expenses.json
- filename: Resource_Management.json
  format: json
  label: Workday Procurement API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Resource_Management/v38.2/Resource_Management.json
- filename: Cash_Management.json
  format: json
  label: Workday Cash Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Cash_Management/v38.2/Cash_Management.json
- filename: Financial_Management.json
  format: json
  label: Workday Financial Accounting API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json
- filename: Report_as_a_Service.json
  format: json
  label: Workday Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v38.2/Report_as_a_Service.json
class_count: 0
classes: []
context_file: json-ld/workday-financials-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/json-ld/workday-financials-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Financials from Workday Financials.
layout: jsonld
name: Workday Financials Context
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
  name: JournalEntry
  type: ''
- container: ''
  name: LedgerAccount
  type: ''
- container: ''
  name: SupplierInvoice
  type: ''
- container: ''
  name: CustomerInvoice
  type: ''
- container: ''
  name: ExpenseReport
  type: ''
- container: ''
  name: PurchaseOrder
  type: ''
- container: ''
  name: PurchaseRequisition
  type: ''
- container: ''
  name: Supplier
  type: ''
- container: ''
  name: BankAccount
  type: ''
- container: ''
  name: RevenueContract
  type: ''
- container: ''
  name: Company
  type: ''
- container: ''
  name: CostCenter
  type: ''
- container: ''
  name: AccountingPeriod
  type: ''
property_count: 13
provider_name: Workday Financials
provider_slug: workday-financials
slug: workday-financials-context
source_filename: workday-financials-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workday\": \"https://community.workday.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"JournalEntry\": {\n      \"@id\": \"workday:JournalEntry\",\n      \"@context\": {\n        \"journalNumber\": \"workday:journalNumber\",\n        \"journalDate\": {\n          \"@id\": \"workday:journalDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"description\": \"schema:description\",\n        \"status\": \"workday:status\",\n        \"totalDebit\": {\n          \"@id\": \"workday:totalDebit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalCredit\": {\n          \"@id\": \"workday:totalCredit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\
  \n    \"LedgerAccount\": {\n      \"@id\": \"workday:LedgerAccount\",\n      \"@context\": {\n        \"accountNumber\": \"workday:accountNumber\",\n        \"accountName\": \"schema:name\",\n        \"accountType\": \"workday:accountType\",\n        \"active\": {\n          \"@id\": \"workday:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"SupplierInvoice\": {\n      \"@id\": \"workday:SupplierInvoice\",\n      \"@context\": {\n        \"invoiceNumber\": \"workday:invoiceNumber\",\n        \"invoiceDate\": {\n          \"@id\": \"workday:invoiceDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dueDate\": {\n          \"@id\": \"workday:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"workday:status\"\n      }\n    },\n\n    \"CustomerInvoice\": {\n      \"@id\": \"workday:CustomerInvoice\"\
  ,\n      \"@context\": {\n        \"invoiceNumber\": \"workday:invoiceNumber\",\n        \"invoiceDate\": {\n          \"@id\": \"workday:invoiceDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dueDate\": {\n          \"@id\": \"workday:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"workday:status\"\n      }\n    },\n\n    \"ExpenseReport\": {\n      \"@id\": \"workday:ExpenseReport\",\n      \"@context\": {\n        \"reportNumber\": \"workday:reportNumber\",\n        \"memo\": \"schema:description\",\n        \"expenseDate\": {\n          \"@id\": \"workday:expenseDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"workday:status\",\n        \"createdOn\": {\n          \"\
  @id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"workday:PurchaseOrder\",\n      \"@context\": {\n        \"orderNumber\": \"workday:orderNumber\",\n        \"orderDate\": {\n          \"@id\": \"workday:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"workday:status\"\n      }\n    },\n\n    \"PurchaseRequisition\": {\n      \"@id\": \"workday:PurchaseRequisition\",\n      \"@context\": {\n        \"requisitionNumber\": \"workday:requisitionNumber\",\n        \"description\": \"schema:description\",\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"workday:status\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Supplier\": {\n      \"@id\": \"workday:Supplier\",\n      \"@context\": {\n        \"supplierName\": \"schema:name\",\n        \"supplierReferenceId\": \"workday:supplierReferenceId\",\n        \"taxId\": \"workday:taxId\",\n        \"paymentTerms\": \"workday:paymentTerms\",\n        \"active\": {\n          \"@id\": \"workday:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"BankAccount\": {\n      \"@id\": \"workday:BankAccount\",\n      \"@context\": {\n        \"accountName\": \"schema:name\",\n        \"accountNumber\": \"workday:accountNumber\",\n        \"bankName\": \"workday:bankName\",\n        \"accountType\": \"workday:accountType\",\n        \"currentBalance\": {\n          \"@id\": \"workday:currentBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"active\": {\n          \"@id\": \"workday:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n \
  \   },\n\n    \"RevenueContract\": {\n      \"@id\": \"workday:RevenueContract\",\n      \"@context\": {\n        \"contractNumber\": \"workday:contractNumber\",\n        \"startDate\": {\n          \"@id\": \"workday:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"workday:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalContractValue\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"workday:status\",\n        \"revenueRecognitionStandard\": \"workday:revenueRecognitionStandard\"\n      }\n    },\n\n    \"Company\": {\n      \"@id\": \"workday:Company\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"organizationCode\": \"workday:organizationCode\",\n        \"active\": {\n          \"@id\": \"workday:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CostCenter\": {\n      \"@id\"\
  : \"workday:CostCenter\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"code\": \"workday:code\",\n        \"active\": {\n          \"@id\": \"workday:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"AccountingPeriod\": {\n      \"@id\": \"workday:AccountingPeriod\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"startDate\": {\n          \"@id\": \"workday:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"workday:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"workday:status\",\n        \"fiscalYear\": \"workday:fiscalYear\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/json-ld/workday-financials-context.jsonld
tags:
- Accounting
- Cloud ERP
- Financial Management
- Procurement
- JSON-LD
- Linked Data
- Semantic Web
---
