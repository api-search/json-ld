---
class_count: 9
classes:
- email
- name
- Contact
- Attachment
- Content
- Email
- SuccessfulResponse
- BadRequestResponse
- AccessDeniedResponse
context_file: json-ld/ahasend-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/json-ld/ahasend-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ahasend Api from AhaSend.
layout: jsonld
name: Ahasend Api Context
namespaces:
- prefix: ahasend
  uri: https://ahasend.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: data
  type: string
- container: ''
  name: base64
  type: boolean
- container: ''
  name: contentType
  type: string
- container: ''
  name: contentId
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: textBody
  type: string
- container: ''
  name: htmlBody
  type: string
- container: set
  name: attachments
  type: string
- container: ''
  name: replyTo
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: from
  type: string
- container: set
  name: recipients
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: successCount
  type: integer
- container: ''
  name: failCount
  type: integer
- container: set
  name: failedRecipients
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: status
  type: string
property_count: 19
provider_name: AhaSend
provider_slug: ahasend
slug: ahasend-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ahasend\": \"https://ahasend.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"email\": \"schema:email\",\n    \"name\": \"schema:name\",\n    \"Contact\": \"ahasend:Contact\",\n    \"data\": {\n      \"@id\": \"ahasend:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"base64\": {\n      \"@id\": \"ahasend:base64\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"contentType\": {\n      \"@id\": \"ahasend:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentId\": {\n      \"@id\": \"ahasend:content_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"ahasend:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attachment\": \"ahasend:Attachment\",\n    \"subject\": {\n      \"@id\": \"ahasend:subject\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"textBody\": {\n      \"@id\": \"ahasend:text_body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htmlBody\": {\n      \"@id\": \"ahasend:html_body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachments\": {\n      \"@id\": \"ahasend:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replyTo\": {\n      \"@id\": \"ahasend:reply_to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"ahasend:headers\",\n      \"@type\": \"@id\"\n    },\n    \"Content\": \"ahasend:Content\",\n    \"from\": {\n      \"@id\": \"ahasend:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipients\": {\n      \"@id\": \"ahasend:recipients\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"ahasend:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Email\": \"ahasend:Email\",\n    \"successCount\": {\n      \"@id\": \"ahasend:success_count\",\n\
  \      \"@type\": \"xsd:integer\"\n    },\n    \"failCount\": {\n      \"@id\": \"ahasend:fail_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failedRecipients\": {\n      \"@id\": \"ahasend:failed_recipients\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"ahasend:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SuccessfulResponse\": \"ahasend:SuccessfulResponse\",\n    \"status\": {\n      \"@id\": \"ahasend:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BadRequestResponse\": \"ahasend:BadRequestResponse\",\n    \"AccessDeniedResponse\": \"ahasend:AccessDeniedResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/json-ld/ahasend-api-context.jsonld
tags:
- Email
- Transactional Email
- Developer Tools
- SMTP
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
