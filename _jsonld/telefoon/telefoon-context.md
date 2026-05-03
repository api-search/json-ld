---
api_specs:
- filename: telefoon-voice-openapi.yml
  format: yaml
  label: Telefoon Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/openapi/telefoon-voice-openapi.yml
- filename: telefoon-sms-openapi.yml
  format: yaml
  label: Telefoon SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/openapi/telefoon-sms-openapi.yml
- filename: telefoon-numbers-openapi.yml
  format: yaml
  label: Telefoon Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/openapi/telefoon-numbers-openapi.yml
class_count: 4
classes:
- Call
- Message
- PhoneNumber
- Conference
context_file: json-ld/telefoon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/json-ld/telefoon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telefoon from Telefoon.
layout: jsonld
name: Telefoon Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: telefoon
  uri: https://developers.telefoon.com/schema/
- prefix: gdpr
  uri: https://gdpr-info.eu/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: start_time
  type: dateTime
- container: ''
  name: end_time
  type: dateTime
- container: ''
  name: price
  type: string
- container: ''
  name: price_unit
  type: string
- container: ''
  name: phone_number
  type: string
- container: ''
  name: country_code
  type: string
- container: ''
  name: friendly_name
  type: string
- container: ''
  name: date_created
  type: dateTime
- container: ''
  name: gdpr_consent_ref
  type: string
- container: ''
  name: monthly_rate
  type: string
- container: ''
  name: address_required
  type: boolean
property_count: 18
provider_name: Telefoon
provider_slug: telefoon
slug: telefoon-context
source_filename: telefoon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"telefoon\": \"https://developers.telefoon.com/schema/\",\n    \"gdpr\": \"https://gdpr-info.eu/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Call\": \"telefoon:Call\",\n    \"Message\": \"telefoon:Message\",\n    \"PhoneNumber\": \"schema:ContactPoint\",\n    \"Conference\": \"telefoon:Conference\",\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"telefoon:status\", \"@type\": \"xsd:string\" },\n    \"direction\": { \"@id\": \"telefoon:direction\", \"@type\": \"xsd:string\" },\n    \"from\": { \"@id\": \"schema:sender\", \"@type\": \"xsd:string\" },\n    \"to\": { \"@id\": \"schema:recipient\", \"@type\": \"xsd:string\" },\n    \"body\": { \"@id\": \"schema:text\", \"@type\": \"xsd:string\" },\n    \"duration\": { \"@id\": \"schema:duration\", \"@type\": \"xsd:integer\" },\n    \"start_time\": { \"@id\"\
  : \"schema:startTime\", \"@type\": \"xsd:dateTime\" },\n    \"end_time\": { \"@id\": \"schema:endTime\", \"@type\": \"xsd:dateTime\" },\n    \"price\": { \"@id\": \"schema:price\", \"@type\": \"xsd:string\" },\n    \"price_unit\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n    \"phone_number\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"country_code\": { \"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\" },\n    \"friendly_name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"date_created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"gdpr_consent_ref\": { \"@id\": \"gdpr:consentReference\", \"@type\": \"xsd:string\" },\n    \"monthly_rate\": { \"@id\": \"schema:price\", \"@type\": \"xsd:string\" },\n    \"address_required\": { \"@id\": \"telefoon:addressRequired\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/json-ld/telefoon-context.jsonld
tags:
- Belgium
- CPaaS
- EU Data Residency
- Europe
- GDPR Compliant
- Messaging
- Netherlands
- Number Provisioning
- SMS
- Telephony
- Voice
- JSON-LD
- Linked Data
- Semantic Web
---
