---
api_specs:
- filename: vibes-platform-openapi.yml
  format: yaml
  label: Vibes Platform API
  slug: vibes-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/openapi/vibes-platform-openapi.yml
- filename: vibes-connect-openapi.yml
  format: yaml
  label: Vibes Connect API
  slug: vibes-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/openapi/vibes-connect-openapi.yml
class_count: 38
classes:
- Broadcast
- AcquisitionCampaign
- SubscriptionList
- Person
- Event
- WalletItem
- Callback
- SmsMessage
- MmsMessage
- id
- name
- description
- status
- message_type
- message_text
- subscription_list_id
- mobile_phone
- external_person_id
- person_key
- subscriber_count
- keyword
- short_code
- event_type
- attributes
- wallet_type
- template_id
- fields
- callback_type
- url
- to
- from
- text
- subject
- content
- carrier
- number_type
- country_code
- company_key
context_file: json-ld/vibes-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/json-ld/vibes-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vibes Platform from Vibes Platform.
layout: jsonld
name: Vibes Platform Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: scheduled_at
  type: dateTime
- container: ''
  name: sent_at
  type: dateTime
property_count: 4
provider_name: Vibes Platform
provider_slug: vibes-platform
slug: vibes-platform-context
source_filename: vibes-platform-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer-platform.vibes.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Broadcast\": \"schema:Action\",\n    \"AcquisitionCampaign\": \"schema:MarketingAction\",\n    \"SubscriptionList\": \"schema:ItemList\",\n    \"Person\": \"schema:Person\",\n    \"Event\": \"schema:Event\",\n    \"WalletItem\": \"schema:DigitalDocument\",\n    \"Callback\": \"schema:WebAPI\",\n    \"SmsMessage\": \"schema:Message\",\n    \"MmsMessage\": \"schema:Message\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:actionStatus\",\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scheduled_at\": {\n      \"@id\": \"schema:scheduledTime\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sent_at\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"message_type\": \"schema:encodingFormat\",\n    \"message_text\": \"schema:text\",\n    \"subscription_list_id\": \"schema:itemListElement\",\n\n    \"mobile_phone\": \"schema:telephone\",\n    \"external_person_id\": \"schema:identifier\",\n    \"person_key\": \"schema:identifier\",\n\n    \"subscriber_count\": \"schema:numberOfItems\",\n    \"keyword\": \"schema:keywords\",\n    \"short_code\": \"schema:identifier\",\n\n    \"event_type\": \"schema:additionalType\",\n    \"attributes\": \"schema:additionalProperty\",\n\n    \"wallet_type\": \"schema:encodingFormat\",\n    \"template_id\": \"schema:isBasedOn\",\n    \"fields\": \"schema:additionalProperty\",\n\n    \"callback_type\": \"schema:additionalType\",\n    \"url\": \"schema:url\",\n\n    \"to\": \"schema:recipient\",\n    \"from\": \"schema:sender\",\n    \"text\": \"schema:text\"\
  ,\n    \"subject\": \"schema:about\",\n    \"content\": \"schema:encodesCreativeWork\",\n\n    \"carrier\": \"schema:provider\",\n    \"number_type\": \"schema:additionalType\",\n    \"country_code\": \"schema:addressCountry\",\n\n    \"company_key\": \"schema:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/json-ld/vibes-platform-context.jsonld
tags:
- Mobile Marketing
- Mobile Messaging
- Push Notifications
- SMS
- MMS
- Broadcast Messaging
- Acquisition Campaigns
- Subscription Management
- Wallet Passes
- RCS
- JSON-LD
- Linked Data
- Semantic Web
---
