---
class_count: 0
classes: []
context_file: json-ld/amazon-ses-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ses/refs/heads/main/json-ld/amazon-ses-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ses from Amazon SES.
layout: jsonld
name: Amazon Ses Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/ses/schemas/
- prefix: ses
  uri: https://docs.aws.amazon.com/ses/latest/APIReference-V2/
properties:
- container: ''
  name: EmailMessage
  type: ''
- container: ''
  name: EmailIdentity
  type: ''
- container: ''
  name: ContactList
  type: ''
- container: ''
  name: EmailTemplate
  type: ''
- container: ''
  name: Destination
  type: ''
- container: ''
  name: ConfigurationSet
  type: ''
property_count: 6
provider_name: Amazon SES
provider_slug: amazon-ses
slug: amazon-ses-context
source_filename: amazon-ses-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/ses/schemas/\",\n    \"ses\": \"https://docs.aws.amazon.com/ses/latest/APIReference-V2/\",\n    \"EmailMessage\": {\n      \"@id\": \"schema:EmailMessage\",\n      \"@context\": {\n        \"Subject\": \"schema:about\",\n        \"Body\": \"schema:text\",\n        \"FromEmailAddress\": \"schema:sender\",\n        \"Destination\": \"schema:recipient\",\n        \"ReplyToAddresses\": \"schema:replyToUrl\"\n      }\n    },\n    \"EmailIdentity\": {\n      \"@id\": \"aws:EmailIdentity\",\n      \"@context\": {\n        \"IdentityType\": \"schema:additionalType\",\n        \"IdentityName\": \"schema:name\",\n        \"VerifiedForSendingStatus\": \"aws:verifiedStatus\",\n        \"SendingEnabled\": \"aws:sendingEnabled\",\n        \"DkimAttributes\": \"aws:dkimAttributes\"\n      }\n    },\n    \"ContactList\": {\n      \"@id\": \"aws:ContactList\",\n      \"@context\": {\n     \
  \   \"ContactListName\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Topics\": \"aws:topics\",\n        \"CreatedTimestamp\": \"schema:dateCreated\",\n        \"LastUpdatedTimestamp\": \"schema:dateModified\"\n      }\n    },\n    \"EmailTemplate\": {\n      \"@id\": \"aws:EmailTemplate\",\n      \"@context\": {\n        \"TemplateName\": \"schema:name\",\n        \"TemplateContent\": \"schema:text\",\n        \"Subject\": \"schema:about\",\n        \"Html\": \"schema:encodingFormat\",\n        \"Text\": \"schema:text\"\n      }\n    },\n    \"Destination\": {\n      \"@id\": \"aws:Destination\",\n      \"@context\": {\n        \"ToAddresses\": \"schema:recipient\",\n        \"CcAddresses\": \"schema:ccRecipient\",\n        \"BccAddresses\": \"schema:bccRecipient\"\n      }\n    },\n    \"ConfigurationSet\": {\n      \"@id\": \"aws:ConfigurationSet\",\n      \"@context\": {\n        \"ConfigurationSetName\": \"schema:name\",\n        \"TrackingOptions\"\
  : \"aws:trackingOptions\",\n        \"SendingOptions\": \"aws:sendingOptions\",\n        \"ReputationOptions\": \"aws:reputationOptions\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ses/refs/heads/main/json-ld/amazon-ses-context.jsonld
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
