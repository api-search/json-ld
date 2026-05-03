---
api_specs:
- filename: tratta-openapi.yml
  format: yaml
  label: Tratta API
  slug: tratta
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/openapi/tratta-openapi.yml
class_count: 35
classes:
- Customer
- DebtAccount
- PaymentPlan
- PaymentMethod
- Charge
- Transaction
- Webhook
- CustomerSession
- Ticket
- id
- first_name
- last_name
- email
- phone
- customer_id
- debt_account_id
- original_balance
- current_balance
- total_amount
- installment_amount
- frequency
- status
- payment_source
- start_date
- next_payment_date
- amount
- type
- last_four
- brand
- url
- events
- magic_link
- expires_at
- created_at
- updated_at
context_file: json-ld/tratta-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/json-ld/tratta-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tratta from Tratta.
layout: jsonld
name: Tratta Context
namespaces:
- prefix: tratta
  uri: https://tratta.io/vocab/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties: []
property_count: 0
provider_name: Tratta
provider_slug: tratta
slug: tratta-context
source_filename: tratta-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tratta\": \"https://tratta.io/vocab/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"Customer\": \"schema:Person\",\n    \"DebtAccount\": \"tratta:DebtAccount\",\n    \"PaymentPlan\": \"tratta:PaymentPlan\",\n    \"PaymentMethod\": \"schema:PaymentMethod\",\n    \"Charge\": \"schema:Invoice\",\n    \"Transaction\": \"schema:MonetaryTransaction\",\n    \"Webhook\": \"tratta:Webhook\",\n    \"CustomerSession\": \"tratta:CustomerSession\",\n    \"Ticket\": \"tratta:SupportTicket\",\n    \"id\": \"@id\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"customer_id\": \"tratta:customer\",\n    \"debt_account_id\": \"tratta:debtAccount\",\n    \"original_balance\": \"tratta:originalBalance\",\n    \"current_balance\": \"tratta:currentBalance\",\n    \"total_amount\": \"schema:totalPaymentDue\"\
  ,\n    \"installment_amount\": \"tratta:installmentAmount\",\n    \"frequency\": \"tratta:paymentFrequency\",\n    \"status\": \"schema:orderStatus\",\n    \"payment_source\": \"tratta:paymentSource\",\n    \"start_date\": \"schema:startDate\",\n    \"next_payment_date\": \"tratta:nextPaymentDate\",\n    \"amount\": \"schema:amount\",\n    \"type\": \"schema:additionalType\",\n    \"last_four\": \"tratta:lastFourDigits\",\n    \"brand\": \"schema:brand\",\n    \"url\": \"schema:url\",\n    \"events\": \"tratta:webhookEvents\",\n    \"magic_link\": \"tratta:magicLink\",\n    \"expires_at\": \"schema:expires\",\n    \"created_at\": \"schema:dateCreated\",\n    \"updated_at\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/json-ld/tratta-context.jsonld
tags:
- Billing
- Collections
- Payments
- Debt Collection
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
