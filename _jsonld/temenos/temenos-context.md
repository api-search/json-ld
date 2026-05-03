---
api_specs:
- filename: openapi.json
  format: json
  label: Temenos Transact API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.temenos.com/transact/openapi.json
- filename: openapi.json
  format: json
  label: Temenos Infinity API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.temenos.com/infinity/openapi.json
- filename: openapi.json
  format: json
  label: Temenos Payments API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.temenos.com/payments/openapi.json
- filename: openapi.json
  format: json
  label: Temenos Fund Administration API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.temenos.com/funds/openapi.json
- filename: openapi.json
  format: json
  label: Temenos Financial Crime Mitigation API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.temenos.com/fcm/openapi.json
- filename: temenos-data-hub-openapi.yml
  format: yaml
  label: Temenos Transact Data Hub API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-data-hub-openapi.yml
- filename: temenos-wealth-openapi.yml
  format: yaml
  label: Temenos Wealth API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-wealth-openapi.yml
- filename: temenos-enterprise-product-pricing-openapi.yml
  format: yaml
  label: Temenos Enterprise Product and Pricing API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-enterprise-product-pricing-openapi.yml
- filename: temenos-cloud-banking-openapi.yml
  format: yaml
  label: Temenos Cloud Banking (CMB) API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-cloud-banking-openapi.yml
- filename: temenos-journey-manager-openapi.yml
  format: yaml
  label: Temenos Journey Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-journey-manager-openapi.yml
- filename: temenos-microservices-openapi.yml
  format: yaml
  label: Temenos Transact Microservices API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-microservices-openapi.yml
- filename: temenos-bnpl-openapi.yml
  format: yaml
  label: Temenos Buy Now Pay Later API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/openapi/temenos-bnpl-openapi.yml
class_count: 0
classes: []
context_file: json-ld/temenos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/json-ld/temenos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Temenos from Temenos.
layout: jsonld
name: Temenos Context
namespaces:
- prefix: temenos
  uri: https://api.temenos.com/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: BankAccount
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: PaymentOrder
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Fund
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: BankingProduct
  type: ''
- container: ''
  name: ComplianceAlert
  type: ''
property_count: 9
provider_name: Temenos
provider_slug: temenos
slug: temenos-context
source_filename: temenos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"temenos\": \"https://api.temenos.com/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"BankAccount\": {\n      \"@id\": \"temenos:BankAccount\",\n      \"@context\": {\n        \"accountId\": \"temenos:accountId\",\n        \"accountName\": \"schema:name\",\n        \"accountType\": \"temenos:accountType\",\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"temenos:status\",\n        \"openingDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"closingDate\": {\n          \"@id\": \"temenos:closingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"workingBalance\": {\n          \"@id\": \"\
  temenos:workingBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"availableBalance\": {\n          \"@id\": \"temenos:availableBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"iban\": \"schema:identifier\",\n        \"customer\": {\n          \"@id\": \"temenos:customer\",\n          \"@type\": \"@id\"\n        },\n        \"product\": {\n          \"@id\": \"temenos:product\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"temenos:Customer\",\n      \"@context\": {\n        \"customerId\": \"temenos:customerId\",\n        \"customerType\": \"temenos:customerType\",\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n    \
  \    \"nationality\": \"schema:nationality\",\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\"\n        },\n        \"kycStatus\": \"temenos:kycStatus\",\n        \"riskRating\": \"temenos:riskRating\",\n        \"onboardingDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"accounts\": {\n          \"@id\": \"temenos:accounts\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PaymentOrder\": {\n      \"@id\": \"temenos:PaymentOrder\",\n      \"@context\": {\n        \"paymentOrderId\": \"temenos:paymentOrderId\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentType\": \"temenos:paymentType\",\n        \"status\": \"temenos:paymentStatus\"\
  ,\n        \"valueDate\": {\n          \"@id\": \"temenos:valueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"reference\": \"temenos:paymentReference\",\n        \"debitAccount\": {\n          \"@id\": \"temenos:debitAccount\",\n          \"@type\": \"@id\"\n        },\n        \"creditAccount\": {\n          \"@id\": \"temenos:creditAccount\",\n          \"@type\": \"@id\"\n        },\n        \"beneficiary\": {\n          \"@id\": \"temenos:beneficiary\",\n          \"@type\": \"@id\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"temenos:Transaction\",\n      \"@context\": {\n        \"transactionId\": \"temenos:transactionId\",\n        \"transactionType\": \"temenos:transactionType\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n\
  \          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"debitOrCredit\": \"temenos:debitOrCredit\",\n        \"bookingDate\": {\n          \"@id\": \"temenos:bookingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"valueDate\": {\n          \"@id\": \"temenos:valueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"description\": \"schema:description\",\n        \"account\": {\n          \"@id\": \"temenos:account\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Portfolio\": {\n      \"@id\": \"temenos:Portfolio\",\n      \"@context\": {\n        \"portfolioId\": \"temenos:portfolioId\",\n        \"portfolioName\": \"schema:name\",\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mandateType\": \"temenos:mandateType\",\n        \"riskProfile\": \"temenos:riskProfile\",\n        \"totalValue\": {\n          \"@id\"\
  : \"temenos:totalValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"client\": {\n          \"@id\": \"temenos:client\",\n          \"@type\": \"@id\"\n        },\n        \"positions\": {\n          \"@id\": \"temenos:positions\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Fund\": {\n      \"@id\": \"temenos:Fund\",\n      \"@context\": {\n        \"fundId\": \"temenos:fundId\",\n        \"fundName\": \"schema:name\",\n        \"fundType\": \"temenos:fundType\",\n        \"domicile\": \"temenos:domicile\",\n        \"baseCurrency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inceptionDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"manager\": {\n          \"@id\": \"temenos:fundManager\",\n          \"@type\": \"@id\"\n        },\n        \"shareClasses\": {\n          \"@id\": \"temenos:shareClasses\"\
  ,\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"addressLine1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n\n    \"BankingProduct\": {\n      \"@id\": \"temenos:BankingProduct\",\n      \"@context\": {\n        \"productId\": \"temenos:productId\",\n        \"productName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"productGroup\": \"temenos:productGroup\",\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ComplianceAlert\": {\n      \"@id\": \"temenos:ComplianceAlert\",\n      \"@context\": {\n        \"alertId\": \"temenos:alertId\"\
  ,\n        \"alertType\": \"temenos:alertType\",\n        \"severity\": \"temenos:severity\",\n        \"status\": \"temenos:alertStatus\",\n        \"customer\": {\n          \"@id\": \"temenos:customer\",\n          \"@type\": \"@id\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/temenos/refs/heads/main/json-ld/temenos-context.jsonld
tags:
- Banking
- Cloud Banking
- Core Banking
- Digital Banking
- Financial Services
- Fintech
- Open Banking
- Payments
- Wealth Management
- JSON-LD
- Linked Data
- Semantic Web
---
