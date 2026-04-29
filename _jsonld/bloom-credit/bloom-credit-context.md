---
api_specs:
- filename: bloom-credit-api-openapi.yaml
  format: yaml
  label: Bloom Credit API
  slug: bloom-credit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/openapi/bloom-credit-api-openapi.yaml
class_count: 48
classes:
- id
- type
- Consumer
- CreditScore
- CreditReport
- TradeLine
- MonitoringEnrollment
- consumer_id
- first_name
- last_name
- email
- phone
- date_of_birth
- address
- street
- city
- state
- zip_code
- status
- created_at
- updated_at
- bureau
- score_type
- score
- score_range_min
- score_range_max
- factors
- account_id
- creditor_name
- account_type
- account_status
- credit_limit
- current_balance
- payment_status
- opened_date
- last_activity_date
- enrollment_id
- bureaus
- alert_types
- webhook_url
- trade_lines
- trade_lines_count
- open_accounts
- total_balance
- pull_date
- ssn
- reports
- scores
context_file: json-ld/bloom-credit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/json-ld/bloom-credit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bloom Credit from Bloom Credit.
layout: jsonld
name: Bloom Credit Context
namespaces:
- prefix: bloom
  uri: https://bloomcredit.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties: []
property_count: 0
provider_name: Bloom Credit
provider_slug: bloom-credit
slug: bloom-credit-context
source_filename: bloom-credit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bloom\": \"https://bloomcredit.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Consumer\": \"bloom:Consumer\",\n    \"CreditScore\": \"bloom:CreditScore\",\n    \"CreditReport\": \"bloom:CreditReport\",\n    \"TradeLine\": \"bloom:TradeLine\",\n    \"MonitoringEnrollment\": \"bloom:MonitoringEnrollment\",\n    \"consumer_id\": \"bloom:consumerId\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"date_of_birth\": \"schema:birthDate\",\n    \"address\": \"schema:address\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip_code\": \"schema:postalCode\",\n    \"status\": \"bloom:status\",\n    \"created_at\"\
  : \"schema:dateCreated\",\n    \"updated_at\": \"schema:dateModified\",\n    \"bureau\": \"bloom:bureau\",\n    \"score_type\": \"bloom:scoreType\",\n    \"score\": \"bloom:score\",\n    \"score_range_min\": \"bloom:scoreRangeMin\",\n    \"score_range_max\": \"bloom:scoreRangeMax\",\n    \"factors\": \"bloom:factors\",\n    \"account_id\": \"bloom:accountId\",\n    \"creditor_name\": \"bloom:creditorName\",\n    \"account_type\": \"bloom:accountType\",\n    \"account_status\": \"bloom:accountStatus\",\n    \"credit_limit\": \"bloom:creditLimit\",\n    \"current_balance\": \"bloom:currentBalance\",\n    \"payment_status\": \"bloom:paymentStatus\",\n    \"opened_date\": \"bloom:openedDate\",\n    \"last_activity_date\": \"bloom:lastActivityDate\",\n    \"enrollment_id\": \"bloom:enrollmentId\",\n    \"bureaus\": \"bloom:bureaus\",\n    \"alert_types\": \"bloom:alertTypes\",\n    \"webhook_url\": \"bloom:webhookUrl\",\n    \"trade_lines\": \"bloom:tradeLines\",\n    \"trade_lines_count\"\
  : \"bloom:tradeLinesCount\",\n    \"open_accounts\": \"bloom:openAccounts\",\n    \"total_balance\": \"bloom:totalBalance\",\n    \"pull_date\": \"bloom:pullDate\",\n    \"ssn\": \"bloom:ssn\",\n    \"reports\": \"bloom:reports\",\n    \"scores\": \"bloom:scores\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/json-ld/bloom-credit-context.jsonld
tags:
- Credit Bureau
- Credit Reports
- Credit Scores
- Fintech
- Lending
- Personal Finance
- JSON-LD
- Linked Data
- Semantic Web
---
