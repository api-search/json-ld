---
class_count: 34
classes:
- EmailMessage
- SMTPSession
- from
- to
- cc
- bcc
- replyTo
- subject
- date
- messageId
- body
- attachments
- filename
- contentType
- disposition
- size
- host
- port
- secure
- authentication
- mechanism
- extensions
- transaction
- recipients
- smtpCommand
- responseCode
- enhancedStatus
- rfc5321
- rfc5322
- ehlo
- mailFrom
- rcptTo
- data
- quit
context_file: json-ld/smtp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smtp/refs/heads/main/json-ld/smtp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smtp from SMTP.
layout: jsonld
name: Smtp Context
namespaces:
- prefix: smtp
  uri: https://smtp.standard/vocab#
- prefix: rfc
  uri: https://datatracker.ietf.org/doc/html/
properties: []
property_count: 0
provider_name: SMTP
provider_slug: smtp
slug: smtp-context
source_filename: smtp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"smtp\": \"https://smtp.standard/vocab#\",\n    \"rfc\": \"https://datatracker.ietf.org/doc/html/\",\n    \"EmailMessage\": \"EmailMessage\",\n    \"SMTPSession\": \"smtp:SMTPSession\",\n    \"from\": \"sender\",\n    \"to\": \"recipient\",\n    \"cc\": \"ccRecipient\",\n    \"bcc\": \"bccRecipient\",\n    \"replyTo\": \"replyToUrl\",\n    \"subject\": \"about\",\n    \"date\": \"dateCreated\",\n    \"messageId\": \"identifier\",\n    \"body\": \"text\",\n    \"attachments\": \"attachments\",\n    \"filename\": \"name\",\n    \"contentType\": \"encodingFormat\",\n    \"disposition\": \"smtp:disposition\",\n    \"size\": \"contentSize\",\n    \"host\": \"smtp:host\",\n    \"port\": \"smtp:port\",\n    \"secure\": \"smtp:secure\",\n    \"authentication\": \"smtp:authentication\",\n    \"mechanism\": \"smtp:authMechanism\",\n    \"extensions\": \"smtp:extensions\",\n    \"transaction\": \"smtp:transaction\",\n\
  \    \"recipients\": \"smtp:recipients\",\n    \"smtpCommand\": \"smtp:command\",\n    \"responseCode\": \"smtp:responseCode\",\n    \"enhancedStatus\": \"smtp:enhancedStatus\",\n    \"rfc5321\": \"rfc:rfc5321\",\n    \"rfc5322\": \"rfc:rfc5322\",\n    \"ehlo\": \"smtp:EHLO\",\n    \"mailFrom\": \"smtp:MAILFROM\",\n    \"rcptTo\": \"smtp:RCPTTO\",\n    \"data\": \"smtp:DATA\",\n    \"quit\": \"smtp:QUIT\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smtp/refs/heads/main/json-ld/smtp-context.jsonld
tags:
- SMTP
- Email
- Internet Standards
- IETF
- Messaging
- Protocols
- RFC 5321
- JSON-LD
- Linked Data
- Semantic Web
---
