---
api_specs:
- filename: sendoso-api-openapi.yml
  format: yaml
  label: Sendoso Sending Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/openapi/sendoso-api-openapi.yml
class_count: 27
classes:
- Send
- Recipient
- InventoryItem
- Address
- TeamBudget
- id
- status
- message
- cost
- first_name
- last_name
- email
- company
- title
- name
- description
- price
- street1
- street2
- city
- state
- postal_code
- country
- tracking_number
- crm_id
- crm_type
- team_id
context_file: json-ld/sendoso-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sendoso/refs/heads/main/json-ld/sendoso-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sendoso from Sendoso.
layout: jsonld
name: Sendoso Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sendoso
  uri: https://api-evangelist.github.io/sendoso/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: image_url
  type: reference
- container: ''
  name: tracking_url
  type: reference
- container: ''
  name: estimated_delivery
  type: date
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 5
provider_name: Sendoso
provider_slug: sendoso
slug: sendoso-context
source_filename: sendoso-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sendoso\": \"https://api-evangelist.github.io/sendoso/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Send\": \"sendoso:Send\",\n    \"Recipient\": \"schema:Person\",\n    \"InventoryItem\": \"schema:Product\",\n    \"Address\": \"schema:PostalAddress\",\n    \"TeamBudget\": \"sendoso:TeamBudget\",\n\n    \"id\": \"@id\",\n    \"status\": \"sendoso:sendStatus\",\n    \"message\": \"schema:description\",\n    \"cost\": \"schema:price\",\n\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"company\": \"schema:affiliation\",\n    \"title\": \"schema:jobTitle\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"price\": \"schema:price\",\n    \"image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n\n    \"street1\": \"schema:streetAddress\"\
  ,\n    \"street2\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postal_code\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"tracking_number\": \"sendoso:trackingNumber\",\n    \"tracking_url\": {\n      \"@id\": \"sendoso:trackingUrl\",\n      \"@type\": \"@id\"\n    },\n    \"estimated_delivery\": {\n      \"@id\": \"schema:deliveryTime\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"crm_id\": \"sendoso:crmId\",\n    \"crm_type\": \"sendoso:crmType\",\n    \"team_id\": \"sendoso:teamId\",\n\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sendoso/refs/heads/main/json-ld/sendoso-context.jsonld
tags:
- Corporate Gifting
- Direct Mail
- Sales Engagement
- Marketing Automation
- CRM Integration
- JSON-LD
- Linked Data
- Semantic Web
---
