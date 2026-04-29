---
api_specs:
- filename: microsoft-graph-mail-api-openapi.yml
  format: yaml
  label: Microsoft Graph Mail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-outlook/refs/heads/main/openapi/microsoft-graph-mail-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-outlook-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-outlook/refs/heads/main/json-ld/microsoft-outlook-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Outlook from Microsoft Outlook.
layout: jsonld
name: Microsoft Outlook Context
namespaces:
- prefix: graph
  uri: https://graph.microsoft.com/v1.0/
- prefix: msgraph
  uri: https://graph.microsoft.com/v1.0/$metadata#
- prefix: outlook
  uri: https://schema.api.gov/microsoft-outlook/
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: MailFolder
  type: ''
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: FileAttachment
  type: ''
- container: ''
  name: ItemAttachment
  type: ''
- container: ''
  name: ReferenceAttachment
  type: ''
- container: ''
  name: Recipient
  type: ''
- container: ''
  name: EmailAddress
  type: ''
- container: ''
  name: ItemBody
  type: ''
- container: ''
  name: FollowupFlag
  type: ''
- container: ''
  name: InternetMessageHeader
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: ChangeNotification
  type: ''
property_count: 13
provider_name: Microsoft Outlook
provider_slug: microsoft-outlook
slug: microsoft-outlook-context
source_filename: microsoft-outlook-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"graph\": \"https://graph.microsoft.com/v1.0/\",\n    \"msgraph\": \"https://graph.microsoft.com/v1.0/$metadata#\",\n    \"outlook\": \"https://schema.api.gov/microsoft-outlook/\",\n\n    \"Message\": {\n      \"@id\": \"outlook:Message\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"subject\": \"schema:name\",\n        \"body\": \"outlook:body\",\n        \"bodyPreview\": \"schema:description\",\n        \"from\": \"schema:sender\",\n        \"sender\": \"outlook:sender\",\n        \"toRecipients\": \"schema:recipient\",\n        \"ccRecipients\": \"outlook:ccRecipient\",\n        \"bccRecipients\": \"outlook:bccRecipient\",\n        \"replyTo\": \"outlook:replyTo\",\n        \"receivedDateTime\": {\n          \"@id\": \"schema:dateReceived\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"sentDateTime\": {\n          \"@id\": \"schema:dateSent\",\n\
  \          \"@type\": \"schema:DateTime\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"hasAttachments\": {\n          \"@id\": \"outlook:hasAttachments\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"importance\": \"outlook:importance\",\n        \"isRead\": {\n          \"@id\": \"outlook:isRead\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"isDraft\": {\n          \"@id\": \"outlook:isDraft\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"isDeliveryReceiptRequested\": {\n          \"@id\": \"outlook:isDeliveryReceiptRequested\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"isReadReceiptRequested\": {\n          \"@id\": \"outlook:isReadReceiptRequested\",\n          \"\
  @type\": \"schema:Boolean\"\n        },\n        \"internetMessageId\": \"outlook:internetMessageId\",\n        \"internetMessageHeaders\": \"outlook:internetMessageHeaders\",\n        \"conversationId\": \"outlook:conversationId\",\n        \"conversationIndex\": \"outlook:conversationIndex\",\n        \"parentFolderId\": \"outlook:parentFolderId\",\n        \"inferenceClassification\": \"outlook:inferenceClassification\",\n        \"flag\": \"outlook:flag\",\n        \"webLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"categories\": \"outlook:categories\",\n        \"changeKey\": \"outlook:changeKey\",\n        \"uniqueBody\": \"outlook:uniqueBody\",\n        \"attachments\": \"outlook:attachments\"\n      }\n    },\n\n    \"MailFolder\": {\n      \"@id\": \"outlook:MailFolder\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"parentFolderId\": \"outlook:parentFolderId\",\n     \
  \   \"childFolderCount\": {\n          \"@id\": \"outlook:childFolderCount\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"unreadItemCount\": {\n          \"@id\": \"outlook:unreadItemCount\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"totalItemCount\": {\n          \"@id\": \"outlook:totalItemCount\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"isHidden\": {\n          \"@id\": \"outlook:isHidden\",\n          \"@type\": \"schema:Boolean\"\n        }\n      }\n    },\n\n    \"Attachment\": {\n      \"@id\": \"outlook:Attachment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"contentType\": \"schema:encodingFormat\",\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"schema:Integer\"\n        },\n        \"isInline\": {\n          \"@id\": \"outlook:isInline\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"lastModifiedDateTime\"\
  : {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"contentBytes\": \"outlook:contentBytes\",\n        \"contentId\": \"outlook:contentId\",\n        \"contentLocation\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FileAttachment\": {\n      \"@id\": \"outlook:FileAttachment\",\n      \"@context\": {\n        \"@base\": \"outlook:Attachment\"\n      }\n    },\n\n    \"ItemAttachment\": {\n      \"@id\": \"outlook:ItemAttachment\",\n      \"@context\": {\n        \"@base\": \"outlook:Attachment\"\n      }\n    },\n\n    \"ReferenceAttachment\": {\n      \"@id\": \"outlook:ReferenceAttachment\",\n      \"@context\": {\n        \"@base\": \"outlook:Attachment\"\n      }\n    },\n\n    \"Recipient\": {\n      \"@id\": \"outlook:Recipient\",\n      \"@context\": {\n        \"emailAddress\": \"outlook:emailAddress\"\n      }\n    },\n\n    \"EmailAddress\": {\n  \
  \    \"@id\": \"outlook:EmailAddress\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"address\": \"schema:email\"\n      }\n    },\n\n    \"ItemBody\": {\n      \"@id\": \"outlook:ItemBody\",\n      \"@context\": {\n        \"contentType\": \"schema:encodingFormat\",\n        \"content\": \"schema:text\"\n      }\n    },\n\n    \"FollowupFlag\": {\n      \"@id\": \"outlook:FollowupFlag\",\n      \"@context\": {\n        \"flagStatus\": \"outlook:flagStatus\",\n        \"startDateTime\": {\n          \"@id\": \"outlook:startDateTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"dueDateTime\": {\n          \"@id\": \"outlook:dueDateTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"completedDateTime\": {\n          \"@id\": \"outlook:completedDateTime\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"InternetMessageHeader\": {\n      \"@id\": \"outlook:InternetMessageHeader\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"value\": \"schema:value\"\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"outlook:Subscription\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"resource\": \"outlook:resource\",\n        \"changeType\": \"outlook:changeType\",\n        \"notificationUrl\": {\n          \"@id\": \"outlook:notificationUrl\",\n          \"@type\": \"@id\"\n        },\n        \"expirationDateTime\": {\n          \"@id\": \"outlook:expirationDateTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"clientState\": \"outlook:clientState\",\n        \"lifecycleNotificationUrl\": {\n          \"@id\": \"outlook:lifecycleNotificationUrl\",\n          \"@type\": \"@id\"\n        },\n        \"includeResourceData\": {\n          \"@id\": \"outlook:includeResourceData\",\n          \"@type\": \"schema:Boolean\"\n        }\n      }\n    },\n\n    \"ChangeNotification\": {\n      \"@id\": \"outlook:ChangeNotification\"\
  ,\n      \"@context\": {\n        \"id\": \"@id\",\n        \"subscriptionId\": \"outlook:subscriptionId\",\n        \"changeType\": \"outlook:changeType\",\n        \"resource\": \"outlook:resource\",\n        \"clientState\": \"outlook:clientState\",\n        \"tenantId\": \"outlook:tenantId\",\n        \"subscriptionExpirationDateTime\": {\n          \"@id\": \"outlook:subscriptionExpirationDateTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"resourceData\": \"outlook:resourceData\",\n        \"encryptedContent\": \"outlook:encryptedContent\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-outlook/refs/heads/main/json-ld/microsoft-outlook-context.jsonld
tags:
- Calendar
- Contacts
- Email
- Enterprise
- Microsoft
- Office 365
- Productivity
- JSON-LD
- Linked Data
- Semantic Web
---
