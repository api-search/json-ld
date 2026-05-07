---
api_specs:
- filename: email-verifier-api-openapi.yml
  format: yaml
  label: Email Verifier API Verification
  slug: verification
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/email-verifier-api/refs/heads/main/openapi/email-verifier-api-openapi.yml
class_count: 18
classes:
- VerificationResult
- EmailAddress
- MailExchange
- status
- event
- emailSuggested
- mailbox
- domain
- mxIp
- possibleSpamtrap
- isComplainer
- isDisposable
- isFreeService
- isOffensive
- isRoleAccount
- isGibberish
- remaining
- execution
context_file: json-ld/email-verifier-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/email-verifier-api/refs/heads/main/json-ld/email-verifier-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Email Verifier Api from Email Verifier API.
layout: jsonld
name: Email Verifier Api Context
namespaces:
- prefix: evapi
  uri: https://emailverifierapi.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: details
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: mxLocation
  type: string
property_count: 3
provider_name: Email Verifier API
provider_slug: email-verifier-api
slug: email-verifier-api-context
source_filename: email-verifier-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"evapi\": \"https://emailverifierapi.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"VerificationResult\": \"evapi:VerificationResult\",\n    \"EmailAddress\": \"evapi:EmailAddress\",\n    \"MailExchange\": \"evapi:MailExchange\",\n\n    \"status\": \"evapi:status\",\n    \"event\": \"evapi:event\",\n    \"details\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailSuggested\": \"evapi:emailSuggested\",\n    \"mailbox\": \"evapi:mailbox\",\n    \"domain\": \"evapi:domain\",\n    \"mxIp\": \"evapi:mxIp\",\n    \"mxLocation\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"possibleSpamtrap\": \"evapi:possibleSpamtrap\",\n    \"isComplainer\": \"evapi:isComplainer\",\n    \"isDisposable\"\
  : \"evapi:isDisposable\",\n    \"isFreeService\": \"evapi:isFreeService\",\n    \"isOffensive\": \"evapi:isOffensive\",\n    \"isRoleAccount\": \"evapi:isRoleAccount\",\n    \"isGibberish\": \"evapi:isGibberish\",\n    \"remaining\": \"evapi:remaining\",\n    \"execution\": \"evapi:execution\",\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/email-verifier-api/refs/heads/main/json-ld/email-verifier-api-context.jsonld
tags:
- Email Verification
- Deliverability
- SMTP Check
- Bounce Prevention
- Lead Validation
- Disposable Detection
- Spam Trap Detection
- Catch-All Detection
- Greylisting
- Role Account Detection
- Typo Suggestion
- B2B Lead Scoring
- JSON-LD
- Linked Data
- Semantic Web
---
