---
api_specs:
- filename: csg-forte-rest-openapi.yml
  format: yaml
  label: CSG Forte REST API
  slug: csg-forte-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/openapi/csg-forte-rest-openapi.yml
class_count: 11
classes:
- transaction_id
- first_name
- last_name
- company_name
- physical_address
- locality
- region
- postal_code
- country_code
- email
- phone
context_file: json-ld/csg-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/json-ld/csg-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Csg from CSG Systems.
layout: jsonld
name: Csg Context
namespaces:
- prefix: forte
  uri: https://api.forte.net/v3/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Transaction
  type: schema:PaymentChargeSpecification
- container: ''
  name: Customer
  type: schema:Person
- container: ''
  name: PaymentMethod
  type: schema:PaymentMethod
- container: ''
  name: Settlement
  type: ''
- container: ''
  name: action
  type: ''
- container: ''
  name: authorization_amount
  type: decimal
- container: ''
  name: authorization_code
  type: ''
- container: ''
  name: order_number
  type: ''
- container: ''
  name: received_date
  type: dateTime
- container: ''
  name: transaction_date
  type: date
- container: ''
  name: billing_address
  type: schema:PostalAddress
- container: ''
  name: card_type
  type: ''
- container: ''
  name: name_on_card
  type: ''
- container: ''
  name: account_type
  type: ''
- container: ''
  name: routing_number
  type: ''
- container: ''
  name: customer_token
  type: ''
- container: ''
  name: paymethod_token
  type: ''
- container: ''
  name: created_date
  type: date
- container: ''
  name: settle_date
  type: date
property_count: 19
provider_name: CSG Systems
provider_slug: csg
slug: csg-context
source_filename: csg-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"forte\": \"https://api.forte.net/v3/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Transaction\": {\n      \"@id\": \"forte:Transaction\",\n      \"@type\": \"schema:PaymentChargeSpecification\"\n    },\n    \"Customer\": {\n      \"@id\": \"forte:Customer\",\n      \"@type\": \"schema:Person\"\n    },\n    \"PaymentMethod\": {\n      \"@id\": \"forte:PaymentMethod\",\n      \"@type\": \"schema:PaymentMethod\"\n    },\n    \"Settlement\": {\n      \"@id\": \"forte:Settlement\"\n    },\n\n    \"transaction_id\": \"@id\",\n    \"action\": {\n      \"@id\": \"forte:transactionAction\"\n    },\n    \"authorization_amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"authorization_code\": {\n      \"@id\": \"forte:authorizationCode\"\n    },\n    \"order_number\"\
  : {\n      \"@id\": \"schema:orderNumber\"\n    },\n    \"received_date\": {\n      \"@id\": \"schema:dateReceived\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"transaction_date\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"billing_address\": {\n      \"@id\": \"schema:billingAddress\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"company_name\": \"schema:legalName\",\n    \"physical_address\": \"schema:streetAddress\",\n    \"locality\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"postal_code\": \"schema:postalCode\",\n    \"country_code\": \"schema:addressCountry\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"card_type\": {\n      \"@id\": \"forte:cardBrand\"\n    },\n    \"name_on_card\": {\n      \"@id\": \"forte:cardholderName\"\n    },\n    \"account_type\": {\n  \
  \    \"@id\": \"forte:bankAccountType\"\n    },\n    \"routing_number\": {\n      \"@id\": \"forte:routingNumber\"\n    },\n    \"customer_token\": {\n      \"@id\": \"forte:customerReference\"\n    },\n    \"paymethod_token\": {\n      \"@id\": \"forte:paymentMethodReference\"\n    },\n    \"created_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"settle_date\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/json-ld/csg-context.jsonld
tags:
- Billing
- Customer Engagement
- Payments
- Revenue Management
- Telecom
- JSON-LD
- Linked Data
- Semantic Web
---
