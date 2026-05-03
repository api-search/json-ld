---
api_specs:
- filename: telesign-sms-openapi.yml
  format: yaml
  label: Telesign SMS API
  slug: sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-sms-openapi.yml
- filename: telesign-phoneid-openapi.yml
  format: yaml
  label: Telesign PhoneID API
  slug: phoneid-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-phoneid-openapi.yml
- filename: telesign-verify-openapi.yml
  format: yaml
  label: Telesign Verify API
  slug: verify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-verify-openapi.yml
- filename: telesign-score-openapi.yml
  format: yaml
  label: Telesign Score API
  slug: score-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-score-openapi.yml
class_count: 3
classes:
- name
- description
- telephone
context_file: json-ld/telesign-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/json-ld/telesign-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telesign from Telesign.
layout: jsonld
name: Telesign Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ts
  uri: https://telesign.com/vocabulary/
properties:
- container: ''
  name: PhoneVerification
  type: ''
- container: ''
  name: SmsMessage
  type: ''
- container: ''
  name: PhoneIntelligence
  type: ''
- container: ''
  name: FraudScore
  type: ''
- container: ''
  name: TransactionStatus
  type: ''
property_count: 5
provider_name: Telesign
provider_slug: telesign
slug: telesign-context
source_filename: telesign-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ts\": \"https://telesign.com/vocabulary/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"telephone\": \"schema:telephone\",\n    \"PhoneVerification\": {\n      \"@id\": \"ts:PhoneVerification\",\n      \"@context\": {\n        \"phoneNumber\": \"schema:telephone\",\n        \"channel\": \"ts:channel\",\n        \"status\": \"ts:verificationStatus\",\n        \"referenceId\": \"ts:referenceId\",\n        \"otpCode\": \"ts:otpCode\"\n      }\n    },\n    \"SmsMessage\": {\n      \"@id\": \"ts:SmsMessage\",\n      \"@context\": {\n        \"recipient\": \"schema:recipient\",\n        \"messageBody\": \"schema:text\",\n        \"messageType\": \"ts:messageType\",\n        \"senderId\": \"ts:senderId\",\n        \"referenceId\": \"ts:referenceId\",\n        \"deliveryStatus\": \"ts:deliveryStatus\"\n      }\n    },\n    \"PhoneIntelligence\": {\n\
  \      \"@id\": \"ts:PhoneIntelligence\",\n      \"@context\": {\n        \"phoneNumber\": \"schema:telephone\",\n        \"phoneType\": \"ts:phoneType\",\n        \"carrier\": \"ts:carrier\",\n        \"location\": \"schema:location\",\n        \"countryCode\": \"ts:countryCode\",\n        \"riskScore\": \"ts:riskScore\"\n      }\n    },\n    \"FraudScore\": {\n      \"@id\": \"ts:FraudScore\",\n      \"@context\": {\n        \"score\": \"ts:riskScore\",\n        \"level\": \"ts:riskLevel\",\n        \"recommendation\": \"ts:recommendation\",\n        \"phoneNumber\": \"schema:telephone\"\n      }\n    },\n    \"TransactionStatus\": {\n      \"@id\": \"ts:TransactionStatus\",\n      \"@context\": {\n        \"code\": \"ts:statusCode\",\n        \"description\": \"schema:description\",\n        \"updatedOn\": \"schema:dateModified\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/json-ld/telesign-context.jsonld
tags:
- Authentication
- Communications
- Fraud Prevention
- Phone Intelligence
- SMS
- Verification
- JSON-LD
- Linked Data
- Semantic Web
---
