---
class_count: 1
classes:
- EmailMessage
context_file: json-ld/amazon-ses-emailmessage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ses/refs/heads/main/json-ld/amazon-ses-emailmessage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ses Emailmessage from Amazon SES.
layout: jsonld
name: Amazon Ses Emailmessage Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Simple
  type: string
- container: ''
  name: Subject
  type: string
- container: ''
  name: Data
  type: string
- container: ''
  name: Charset
  type: string
- container: ''
  name: Body
  type: string
- container: ''
  name: Text
  type: string
- container: ''
  name: Html
  type: string
- container: ''
  name: Raw
  type: string
- container: ''
  name: Template
  type: string
- container: ''
  name: TemplateName
  type: string
- container: ''
  name: TemplateArn
  type: string
- container: ''
  name: TemplateData
  type: string
- container: ''
  name: FromEmailAddress
  type: string
- container: ''
  name: Destination
  type: string
- container: set
  name: ToAddresses
  type: string
- container: set
  name: CcAddresses
  type: string
- container: set
  name: BccAddresses
  type: string
- container: set
  name: ReplyToAddresses
  type: string
- container: ''
  name: ConfigurationSetName
  type: string
property_count: 19
provider_name: Amazon SES
provider_slug: amazon-ses
slug: amazon-ses-emailmessage-context
source_filename: amazon-ses-emailmessage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmailMessage\": \"aws:EmailMessage\",\n    \"Simple\": {\n      \"@id\": \"aws:Simple\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subject\": {\n      \"@id\": \"aws:Subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Data\": {\n      \"@id\": \"aws:Data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Charset\": {\n      \"@id\": \"aws:Charset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Body\": {\n      \"@id\": \"aws:Body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Text\": {\n      \"@id\": \"aws:Text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Html\": {\n      \"@id\": \"aws:Html\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Raw\": {\n      \"@id\": \"aws:Raw\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Template\": {\n      \"@id\": \"aws:Template\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateName\": {\n      \"@id\": \"aws:TemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateArn\": {\n      \"@id\": \"aws:TemplateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateData\": {\n      \"@id\": \"aws:TemplateData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FromEmailAddress\": {\n      \"@id\": \"aws:FromEmailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Destination\": {\n      \"@id\": \"aws:Destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ToAddresses\": {\n      \"@id\": \"aws:ToAddresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CcAddresses\": {\n      \"@id\": \"aws:CcAddresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BccAddresses\": {\n      \"@id\": \"aws:BccAddresses\",\n      \"@container\": \"@set\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"ReplyToAddresses\": {\n      \"@id\": \"aws:ReplyToAddresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConfigurationSetName\": {\n      \"@id\": \"aws:ConfigurationSetName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ses/refs/heads/main/json-ld/amazon-ses-emailmessage-context.jsonld
tags:
- Email
- Email Deliverability
- Email Service
- Marketing Email
- Notifications
- SMTP
- Transactional Email
- JSON-LD
- Linked Data
- Semantic Web
---
