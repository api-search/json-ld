---
api_specs:
- filename: sage-accounting-openapi.yml
  format: yaml
  label: Sage Accounting API
  slug: accounting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/openapi/sage-accounting-openapi.yml
class_count: 40
classes:
- Contact
- SalesInvoice
- PurchaseInvoice
- Payment
- BankAccount
- LedgerAccount
- Product
- TaxRate
- LineItem
- Business
- id
- name
- displayed_as
- reference
- email
- telephone
- website
- balance
- outstanding_balance
- date
- due_date
- net_amount
- tax_amount
- total_amount
- outstanding_amount
- quantity
- unit_price
- description
- item_code
- nominal_code
- percentage
- financial_year_start_date
- registration_number
- tax_number
- address_line_1
- city
- region
- postal_code
- country
- currency
context_file: json-ld/sage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/json-ld/sage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sage from Sage.
layout: jsonld
name: Sage Context
namespaces:
- prefix: sage
  uri: https://developer.sage.com/vocab/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: address
  type: schema:PostalAddress
property_count: 1
provider_name: Sage
provider_slug: sage
slug: sage-context
source_filename: sage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sage\": \"https://developer.sage.com/vocab/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Contact\": \"schema:Person\",\n    \"SalesInvoice\": \"schema:Invoice\",\n    \"PurchaseInvoice\": \"sage:PurchaseInvoice\",\n    \"Payment\": \"schema:PaymentCharge\",\n    \"BankAccount\": \"schema:BankAccount\",\n    \"LedgerAccount\": \"sage:LedgerAccount\",\n    \"Product\": \"schema:Product\",\n    \"TaxRate\": \"sage:TaxRate\",\n    \"LineItem\": \"schema:OrderItem\",\n    \"Business\": \"schema:Organization\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"displayed_as\": \"schema:alternateName\",\n    \"reference\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"telephone\": \"schema:telephone\",\n    \"website\": \"schema:url\",\n    \"balance\": \"fibo:hasBalance\",\n    \"outstanding_balance\": \"sage:outstandingBalance\",\n    \"date\": \"schema:dateCreated\"\
  ,\n    \"due_date\": \"schema:paymentDueDate\",\n    \"net_amount\": \"schema:price\",\n    \"tax_amount\": \"sage:taxAmount\",\n    \"total_amount\": \"schema:totalPaymentDue\",\n    \"outstanding_amount\": \"sage:outstandingAmount\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"unit_price\": \"schema:unitPrice\",\n    \"description\": \"schema:description\",\n    \"item_code\": \"schema:sku\",\n    \"nominal_code\": \"sage:nominalCode\",\n    \"percentage\": \"schema:percentage\",\n    \"financial_year_start_date\": \"sage:financialYearStartDate\",\n    \"registration_number\": \"schema:vatID\",\n    \"tax_number\": \"sage:taxNumber\",\n\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"address_line_1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"postal_code\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"currency\"\
  : \"schema:currency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/json-ld/sage-context.jsonld
tags:
- Accounting
- Business Management
- Cloud Software
- ERP
- Payroll
- HR
- JSON-LD
- Linked Data
- Semantic Web
---
