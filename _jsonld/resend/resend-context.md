---
api_specs:
- filename: resend-openapi.yml
  format: yaml
  label: Resend API
  slug: resend
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/openapi/resend-openapi.yml
class_count: 21
classes:
- object
- html
- text
- cc
- bcc
- reply_to
- scheduled_at
- last_event
- attachments
- tags
- audience_id
- Domain
- status
- region
- records
- open_tracking
- click_tracking
- unsubscribed
- Broadcast
- preview_text
- sent_at
context_file: json-ld/resend-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-ld/resend-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Resend from Resend.
layout: jsonld
name: Resend Context
namespaces:
- prefix: resend
  uri: https://resend.com/vocab/
- prefix: EmailMessage
  uri: https://schema.org/EmailMessage
- prefix: id
  uri: https://schema.org/identifier
- prefix: from
  uri: https://schema.org/sender
- prefix: to
  uri: https://schema.org/recipient
- prefix: subject
  uri: https://schema.org/headline
- prefix: created_at
  uri: https://schema.org/dateCreated
- prefix: Audience
  uri: https://schema.org/Audience
- prefix: name
  uri: https://schema.org/name
- prefix: Contact
  uri: https://schema.org/ContactPoint
- prefix: email
  uri: https://schema.org/email
- prefix: first_name
  uri: https://schema.org/givenName
- prefix: last_name
  uri: https://schema.org/familyName
properties: []
property_count: 0
provider_name: Resend
provider_slug: resend
slug: resend-context
source_filename: resend-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"resend\": \"https://resend.com/vocab/\",\n    \"EmailMessage\": \"https://schema.org/EmailMessage\",\n    \"id\": \"https://schema.org/identifier\",\n    \"object\": \"resend:objectType\",\n    \"from\": \"https://schema.org/sender\",\n    \"to\": \"https://schema.org/recipient\",\n    \"subject\": \"https://schema.org/headline\",\n    \"html\": \"resend:htmlBody\",\n    \"text\": \"resend:textBody\",\n    \"cc\": \"resend:cc\",\n    \"bcc\": \"resend:bcc\",\n    \"reply_to\": \"resend:replyTo\",\n    \"created_at\": \"https://schema.org/dateCreated\",\n    \"scheduled_at\": \"resend:scheduledAt\",\n    \"last_event\": \"resend:lastEvent\",\n    \"attachments\": \"resend:attachments\",\n    \"tags\": \"resend:tags\",\n    \"Audience\": \"https://schema.org/Audience\",\n    \"name\": \"https://schema.org/name\",\n    \"audience_id\": \"resend:audienceId\",\n    \"Domain\": \"resend:Domain\",\n    \"status\"\
  : \"resend:status\",\n    \"region\": \"resend:region\",\n    \"records\": \"resend:dnsRecords\",\n    \"open_tracking\": \"resend:openTracking\",\n    \"click_tracking\": \"resend:clickTracking\",\n    \"Contact\": \"https://schema.org/ContactPoint\",\n    \"email\": \"https://schema.org/email\",\n    \"first_name\": \"https://schema.org/givenName\",\n    \"last_name\": \"https://schema.org/familyName\",\n    \"unsubscribed\": \"resend:unsubscribed\",\n    \"Broadcast\": \"resend:Broadcast\",\n    \"preview_text\": \"resend:previewText\",\n    \"audience_id\": \"resend:audienceId\",\n    \"sent_at\": \"resend:sentAt\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-ld/resend-context.jsonld
tags:
- Email
- Developer Tools
- Transactional Email
- Marketing Email
- JSON-LD
- Linked Data
- Semantic Web
---
