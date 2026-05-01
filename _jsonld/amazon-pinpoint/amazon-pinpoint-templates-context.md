---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 37
classes:
- ListTemplatesRequest
- UpdateInAppTemplateRequest
- InAppTemplateRequest
- TemplateResponse
- AndroidPushNotificationTemplate
- GetPushTemplateResponse
- PushNotificationTemplateResponse
- GetInAppTemplateRequest
- TemplateVersionsResponse
- PushNotificationTemplateRequest
- CreateTemplateMessageBody
- UpdatePushTemplateRequest
- ListTemplatesResponse
- TemplatesResponse
- DefaultPushNotificationTemplate
- DeletePushTemplateResponse
- TemplateCreateMessageBody
- CreatePushTemplateResponse
- TemplateConfiguration
- DeleteInAppTemplateRequest
- InAppTemplateResponse
- DeletePushTemplateRequest
- TemplateActiveVersionRequest
- CreatePushTemplateRequest
- UpdateTemplateActiveVersionResponse
- UpdateTemplateActiveVersionRequest
- GetInAppTemplateResponse
- CreateInAppTemplateRequest
- UpdateInAppTemplateResponse
- ListTemplateVersionsRequest
- Template
- UpdatePushTemplateResponse
- GetPushTemplateRequest
- TemplateVersionResponse
- DeleteInAppTemplateResponse
- ListTemplateVersionsResponse
- CreateInAppTemplateResponse
context_file: json-ld/amazon-pinpoint-templates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-templates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Templates from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Templates Context
namespaces:
- prefix: pinpoint
  uri: https://pinpoint.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Arn
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: DefaultSubstitutions
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: TemplateDescription
  type: string
- container: ''
  name: TemplateName
  type: string
- container: ''
  name: TemplateType
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: Body
  type: string
- container: ''
  name: ImageIconUrl
  type: string
- container: ''
  name: ImageUrl
  type: string
- container: ''
  name: RawContent
  type: string
- container: ''
  name: SmallImageIconUrl
  type: string
- container: ''
  name: Sound
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Url
  type: string
- container: ''
  name: Item
  type: string
- container: ''
  name: Message
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: RequestID
  type: string
- container: ''
  name: ADM
  type: string
- container: ''
  name: APNS
  type: string
- container: ''
  name: Baidu
  type: string
- container: ''
  name: Default
  type: string
- container: ''
  name: GCM
  type: string
- container: ''
  name: RecommenderId
  type: string
- container: ''
  name: MessageBody
  type: string
- container: ''
  name: Content
  type: string
- container: ''
  name: CustomConfig
  type: string
- container: ''
  name: Layout
  type: string
- container: ''
  name: EmailTemplate
  type: string
- container: ''
  name: PushTemplate
  type: string
- container: ''
  name: SMSTemplate
  type: string
- container: ''
  name: VoiceTemplate
  type: string
- container: ''
  name: Name
  type: string
property_count: 37
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-templates-context
source_filename: amazon-pinpoint-templates-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListTemplatesRequest\": \"pinpoint:ListTemplatesRequest\",\n    \"UpdateInAppTemplateRequest\": \"pinpoint:UpdateInAppTemplateRequest\",\n    \"InAppTemplateRequest\": \"pinpoint:InAppTemplateRequest\",\n    \"TemplateResponse\": \"pinpoint:TemplateResponse\",\n    \"Arn\": {\n      \"@id\": \"pinpoint:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultSubstitutions\": {\n      \"@id\": \"pinpoint:DefaultSubstitutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"\
  @id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateDescription\": {\n      \"@id\": \"pinpoint:TemplateDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateName\": {\n      \"@id\": \"pinpoint:TemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateType\": {\n      \"@id\": \"pinpoint:TemplateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"pinpoint:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AndroidPushNotificationTemplate\": \"pinpoint:AndroidPushNotificationTemplate\",\n    \"Action\": {\n      \"@id\": \"pinpoint:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Body\": {\n      \"@id\": \"pinpoint:Body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageIconUrl\": {\n      \"@id\": \"pinpoint:ImageIconUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageUrl\": {\n      \"@id\": \"pinpoint:ImageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"RawContent\": {\n      \"@id\": \"pinpoint:RawContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SmallImageIconUrl\": {\n      \"@id\": \"pinpoint:SmallImageIconUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sound\": {\n      \"@id\": \"pinpoint:Sound\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"pinpoint:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Url\": {\n      \"@id\": \"pinpoint:Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetPushTemplateResponse\": \"pinpoint:GetPushTemplateResponse\",\n    \"PushNotificationTemplateResponse\": \"pinpoint:PushNotificationTemplateResponse\",\n    \"GetInAppTemplateRequest\": \"pinpoint:GetInAppTemplateRequest\",\n    \"TemplateVersionsResponse\": \"pinpoint:TemplateVersionsResponse\",\n    \"Item\": {\n      \"@id\": \"pinpoint:Item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Message\": {\n      \"@id\": \"pinpoint:Message\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"NextToken\": {\n      \"@id\": \"pinpoint:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestID\": {\n      \"@id\": \"pinpoint:RequestID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PushNotificationTemplateRequest\": \"pinpoint:PushNotificationTemplateRequest\",\n    \"ADM\": {\n      \"@id\": \"pinpoint:ADM\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APNS\": {\n      \"@id\": \"pinpoint:APNS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Baidu\": {\n      \"@id\": \"pinpoint:Baidu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Default\": {\n      \"@id\": \"pinpoint:Default\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GCM\": {\n      \"@id\": \"pinpoint:GCM\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommenderId\": {\n      \"@id\": \"pinpoint:RecommenderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTemplateMessageBody\": \"pinpoint:CreateTemplateMessageBody\",\n    \"UpdatePushTemplateRequest\": \"pinpoint:UpdatePushTemplateRequest\"\
  ,\n    \"ListTemplatesResponse\": \"pinpoint:ListTemplatesResponse\",\n    \"TemplatesResponse\": \"pinpoint:TemplatesResponse\",\n    \"DefaultPushNotificationTemplate\": \"pinpoint:DefaultPushNotificationTemplate\",\n    \"DeletePushTemplateResponse\": \"pinpoint:DeletePushTemplateResponse\",\n    \"MessageBody\": {\n      \"@id\": \"pinpoint:MessageBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateCreateMessageBody\": \"pinpoint:TemplateCreateMessageBody\",\n    \"Content\": {\n      \"@id\": \"pinpoint:Content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomConfig\": {\n      \"@id\": \"pinpoint:CustomConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Layout\": {\n      \"@id\": \"pinpoint:Layout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatePushTemplateResponse\": \"pinpoint:CreatePushTemplateResponse\",\n    \"TemplateConfiguration\": \"pinpoint:TemplateConfiguration\",\n    \"EmailTemplate\": {\n      \"@id\": \"pinpoint:EmailTemplate\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"PushTemplate\": {\n      \"@id\": \"pinpoint:PushTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMSTemplate\": {\n      \"@id\": \"pinpoint:SMSTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VoiceTemplate\": {\n      \"@id\": \"pinpoint:VoiceTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteInAppTemplateRequest\": \"pinpoint:DeleteInAppTemplateRequest\",\n    \"InAppTemplateResponse\": \"pinpoint:InAppTemplateResponse\",\n    \"DeletePushTemplateRequest\": \"pinpoint:DeletePushTemplateRequest\",\n    \"TemplateActiveVersionRequest\": \"pinpoint:TemplateActiveVersionRequest\",\n    \"CreatePushTemplateRequest\": \"pinpoint:CreatePushTemplateRequest\",\n    \"UpdateTemplateActiveVersionResponse\": \"pinpoint:UpdateTemplateActiveVersionResponse\",\n    \"UpdateTemplateActiveVersionRequest\": \"pinpoint:UpdateTemplateActiveVersionRequest\",\n    \"GetInAppTemplateResponse\": \"pinpoint:GetInAppTemplateResponse\"\
  ,\n    \"CreateInAppTemplateRequest\": \"pinpoint:CreateInAppTemplateRequest\",\n    \"UpdateInAppTemplateResponse\": \"pinpoint:UpdateInAppTemplateResponse\",\n    \"ListTemplateVersionsRequest\": \"pinpoint:ListTemplateVersionsRequest\",\n    \"Template\": \"pinpoint:Template\",\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatePushTemplateResponse\": \"pinpoint:UpdatePushTemplateResponse\",\n    \"GetPushTemplateRequest\": \"pinpoint:GetPushTemplateRequest\",\n    \"TemplateVersionResponse\": \"pinpoint:TemplateVersionResponse\",\n    \"DeleteInAppTemplateResponse\": \"pinpoint:DeleteInAppTemplateResponse\",\n    \"ListTemplateVersionsResponse\": \"pinpoint:ListTemplateVersionsResponse\",\n    \"CreateInAppTemplateResponse\": \"pinpoint:CreateInAppTemplateResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-templates-context.jsonld
tags:
- Campaigns
- Communications
- Email
- Marketing
- Messaging
- Push Notifications
- SMS
- Voice
- Customer Engagement
- Segmentation
- Journeys
- Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
