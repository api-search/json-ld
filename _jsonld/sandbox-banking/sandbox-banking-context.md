---
api_specs:
- filename: sandbox-banking-glyue-openapi.yml
  format: yaml
  label: Glyue Integration Gateway API
  slug: glyue
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sandbox-banking/refs/heads/main/openapi/sandbox-banking-glyue-openapi.yml
class_count: 43
classes:
- Integration
- ServiceRequest
- FieldMapping
- ValidationRule
- RunHistory
- BankingAdapter
- id
- name
- description
- status
- version
- createdAt
- updatedAt
- integrationType
- sourceSystem
- targetSystem
- serviceRequests
- fieldMappings
- validationRules
- auditEnabled
- adapter
- operation
- callForEach
- sourceField
- targetField
- transform
- BankAccount
- Loan
- Transaction
- Customer
- FinancialInstitution
- accountNumber
- routingNumber
- loanAmount
- interestRate
- termMonths
- loanType
- runId
- runStatus
- startTime
- endTime
- requestBody
- responseBody
context_file: json-ld/sandbox-banking-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sandbox-banking/refs/heads/main/json-ld/sandbox-banking-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sandbox Banking from Sandbox Banking.
layout: jsonld
name: Sandbox Banking Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: glyue
  uri: https://glyue.sandboxbanking.com/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Sandbox Banking
provider_slug: sandbox-banking
slug: sandbox-banking-context
source_filename: sandbox-banking-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"glyue\": \"https://glyue.sandboxbanking.com/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Integration\": \"schema:SoftwareApplication\",\n    \"ServiceRequest\": \"schema:Action\",\n    \"FieldMapping\": \"schema:PropertyValue\",\n    \"ValidationRule\": \"schema:DefinedTerm\",\n    \"RunHistory\": \"schema:Event\",\n    \"BankingAdapter\": \"schema:SoftwareApplication\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"version\": \"schema:version\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n\n    \"integrationType\": \"glyue:integrationType\",\n    \"sourceSystem\": \"schema:provider\",\n    \"targetSystem\": \"schema:recipient\",\n    \"serviceRequests\"\
  : \"schema:hasPart\",\n    \"fieldMappings\": \"schema:propertyValue\",\n    \"validationRules\": \"glyue:validationRules\",\n    \"auditEnabled\": \"glyue:auditEnabled\",\n\n    \"adapter\": \"glyue:adapter\",\n    \"operation\": \"schema:action\",\n    \"callForEach\": \"glyue:callForEach\",\n    \"sourceField\": \"schema:name\",\n    \"targetField\": \"schema:value\",\n    \"transform\": \"glyue:transform\",\n\n    \"BankAccount\": \"fibo:FinancialAccount\",\n    \"Loan\": \"fibo:Loan\",\n    \"Transaction\": \"fibo:Payment\",\n    \"Customer\": \"schema:Person\",\n    \"FinancialInstitution\": \"schema:FinancialService\",\n\n    \"accountNumber\": \"fibo:accountNumber\",\n    \"routingNumber\": \"fibo:routingNumber\",\n    \"loanAmount\": \"fibo:principalAmount\",\n    \"interestRate\": \"fibo:interestRate\",\n    \"termMonths\": \"glyue:termMonths\",\n    \"loanType\": \"fibo:loanType\",\n\n    \"runId\": \"glyue:runId\",\n    \"runStatus\": \"glyue:runStatus\",\n    \"startTime\"\
  : \"schema:startTime\",\n    \"endTime\": \"schema:endTime\",\n    \"requestBody\": \"glyue:requestBody\",\n    \"responseBody\": \"glyue:responseBody\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sandbox-banking/refs/heads/main/json-ld/sandbox-banking-context.jsonld
tags:
- API Integration
- Banking
- Core Banking
- Credit Unions
- Financial Services
- Fintech
- Integration Platform
- iPaaS
- Open Banking
- JSON-LD
- Linked Data
- Semantic Web
---
