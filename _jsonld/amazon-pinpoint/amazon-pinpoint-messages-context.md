---
class_count: 25
classes:
- InAppMessagesResponse
- MessageResponse
- SendOTPMessageResponse
- DirectMessageConfiguration
- DefaultMessage
- DefaultPushNotificationMessage
- SendMessagesRequest
- MessageRequest
- SendOTPMessageRequest
- SendOTPMessageRequestParameters
- GetInAppMessagesRequest
- VerifyOTPMessageRequest
- VerifyOTPMessageRequestParameters
- GetInAppMessagesResponse
- VerifyOTPMessageResponse
- InAppMessageHeaderConfig
- MessageConfiguration
- InAppMessage
- InAppMessageBodyConfig
- MessageResult
- AddressConfiguration
- SendMessagesResponse
- InAppMessageContent
- Message
- InAppMessageButton
context_file: json-ld/amazon-pinpoint-messages-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-messages-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Messages from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Messages Context
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
  name: InAppMessageCampaigns
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: EndpointResult
  type: string
- container: ''
  name: RequestId
  type: string
- container: ''
  name: Result
  type: string
- container: ''
  name: ADMMessage
  type: string
- container: ''
  name: APNSMessage
  type: string
- container: ''
  name: BaiduMessage
  type: string
- container: ''
  name: EmailMessage
  type: string
- container: ''
  name: GCMMessage
  type: string
- container: ''
  name: SMSMessage
  type: string
- container: ''
  name: VoiceMessage
  type: string
- container: ''
  name: VerificationResponse
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: Body
  type: string
- container: ''
  name: Data
  type: string
- container: ''
  name: SilentPush
  type: string
- container: ''
  name: Substitutions
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Url
  type: string
- container: ''
  name: Alignment
  type: string
- container: ''
  name: Header
  type: string
- container: ''
  name: TextColor
  type: string
- container: ''
  name: CustomMessage
  type: string
- container: ''
  name: DeliveryStatus
  type: string
- container: ''
  name: MessageId
  type: string
- container: ''
  name: StatusCode
  type: string
- container: ''
  name: StatusMessage
  type: string
- container: ''
  name: UpdatedToken
  type: string
- container: ''
  name: BodyOverride
  type: string
- container: ''
  name: ChannelType
  type: string
- container: ''
  name: Context
  type: string
- container: ''
  name: RawContent
  type: string
- container: ''
  name: TitleOverride
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
  name: Addresses
  type: string
- container: ''
  name: Endpoints
  type: string
- container: ''
  name: TemplateConfiguration
  type: string
- container: ''
  name: TraceId
  type: string
- container: ''
  name: DestinationIdentity
  type: string
- container: ''
  name: Otp
  type: string
- container: ''
  name: ReferenceId
  type: string
- container: ''
  name: BackgroundColor
  type: string
- container: ''
  name: BodyConfig
  type: string
- container: ''
  name: HeaderConfig
  type: string
- container: ''
  name: ImageUrl
  type: string
- container: ''
  name: PrimaryBtn
  type: string
- container: ''
  name: SecondaryBtn
  type: string
- container: ''
  name: AllowedAttempts
  type: string
- container: ''
  name: BrandName
  type: string
- container: ''
  name: Channel
  type: string
- container: ''
  name: CodeLength
  type: string
- container: ''
  name: EntityId
  type: string
- container: ''
  name: Language
  type: string
- container: ''
  name: OriginationIdentity
  type: string
- container: ''
  name: TemplateId
  type: string
- container: ''
  name: ValidityPeriod
  type: string
- container: ''
  name: ImageIconUrl
  type: string
- container: ''
  name: ImageSmallIconUrl
  type: string
- container: ''
  name: JsonBody
  type: string
- container: ''
  name: MediaUrl
  type: string
- container: ''
  name: TimeToLive
  type: string
- container: ''
  name: Android
  type: string
- container: ''
  name: DefaultConfig
  type: string
- container: ''
  name: IOS
  type: string
- container: ''
  name: Web
  type: string
property_count: 68
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-messages-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InAppMessagesResponse\": \"pinpoint:InAppMessagesResponse\",\n    \"InAppMessageCampaigns\": {\n      \"@id\": \"pinpoint:InAppMessageCampaigns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageResponse\": \"pinpoint:MessageResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointResult\": {\n      \"@id\": \"pinpoint:EndpointResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestId\": {\n      \"@id\": \"pinpoint:RequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Result\": {\n      \"@id\": \"pinpoint:Result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SendOTPMessageResponse\": \"pinpoint:SendOTPMessageResponse\"\
  ,\n    \"DirectMessageConfiguration\": \"pinpoint:DirectMessageConfiguration\",\n    \"ADMMessage\": {\n      \"@id\": \"pinpoint:ADMMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APNSMessage\": {\n      \"@id\": \"pinpoint:APNSMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BaiduMessage\": {\n      \"@id\": \"pinpoint:BaiduMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultMessage\": \"pinpoint:DefaultMessage\",\n    \"DefaultPushNotificationMessage\": \"pinpoint:DefaultPushNotificationMessage\",\n    \"EmailMessage\": {\n      \"@id\": \"pinpoint:EmailMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GCMMessage\": {\n      \"@id\": \"pinpoint:GCMMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMSMessage\": {\n      \"@id\": \"pinpoint:SMSMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VoiceMessage\": {\n      \"@id\": \"pinpoint:VoiceMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SendMessagesRequest\": \"\
  pinpoint:SendMessagesRequest\",\n    \"MessageRequest\": \"pinpoint:MessageRequest\",\n    \"SendOTPMessageRequest\": \"pinpoint:SendOTPMessageRequest\",\n    \"SendOTPMessageRequestParameters\": \"pinpoint:SendOTPMessageRequestParameters\",\n    \"GetInAppMessagesRequest\": \"pinpoint:GetInAppMessagesRequest\",\n    \"VerifyOTPMessageRequest\": \"pinpoint:VerifyOTPMessageRequest\",\n    \"VerifyOTPMessageRequestParameters\": \"pinpoint:VerifyOTPMessageRequestParameters\",\n    \"GetInAppMessagesResponse\": \"pinpoint:GetInAppMessagesResponse\",\n    \"VerifyOTPMessageResponse\": \"pinpoint:VerifyOTPMessageResponse\",\n    \"VerificationResponse\": {\n      \"@id\": \"pinpoint:VerificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Action\": {\n      \"@id\": \"pinpoint:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Body\": {\n      \"@id\": \"pinpoint:Body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Data\": {\n      \"@id\": \"pinpoint:Data\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"SilentPush\": {\n      \"@id\": \"pinpoint:SilentPush\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Substitutions\": {\n      \"@id\": \"pinpoint:Substitutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"pinpoint:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Url\": {\n      \"@id\": \"pinpoint:Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InAppMessageHeaderConfig\": \"pinpoint:InAppMessageHeaderConfig\",\n    \"Alignment\": {\n      \"@id\": \"pinpoint:Alignment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Header\": {\n      \"@id\": \"pinpoint:Header\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TextColor\": {\n      \"@id\": \"pinpoint:TextColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageConfiguration\": \"pinpoint:MessageConfiguration\",\n    \"CustomMessage\": {\n      \"@id\": \"pinpoint:CustomMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  InAppMessage\": \"pinpoint:InAppMessage\",\n    \"InAppMessageBodyConfig\": \"pinpoint:InAppMessageBodyConfig\",\n    \"MessageResult\": \"pinpoint:MessageResult\",\n    \"DeliveryStatus\": {\n      \"@id\": \"pinpoint:DeliveryStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageId\": {\n      \"@id\": \"pinpoint:MessageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusCode\": {\n      \"@id\": \"pinpoint:StatusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusMessage\": {\n      \"@id\": \"pinpoint:StatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatedToken\": {\n      \"@id\": \"pinpoint:UpdatedToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressConfiguration\": \"pinpoint:AddressConfiguration\",\n    \"BodyOverride\": {\n      \"@id\": \"pinpoint:BodyOverride\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelType\": {\n      \"@id\": \"pinpoint:ChannelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Context\"\
  : {\n      \"@id\": \"pinpoint:Context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RawContent\": {\n      \"@id\": \"pinpoint:RawContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TitleOverride\": {\n      \"@id\": \"pinpoint:TitleOverride\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Content\": {\n      \"@id\": \"pinpoint:Content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomConfig\": {\n      \"@id\": \"pinpoint:CustomConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Layout\": {\n      \"@id\": \"pinpoint:Layout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Addresses\": {\n      \"@id\": \"pinpoint:Addresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Endpoints\": {\n      \"@id\": \"pinpoint:Endpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateConfiguration\": {\n      \"@id\": \"pinpoint:TemplateConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TraceId\": {\n      \"@id\": \"pinpoint:TraceId\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"DestinationIdentity\": {\n      \"@id\": \"pinpoint:DestinationIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Otp\": {\n      \"@id\": \"pinpoint:Otp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReferenceId\": {\n      \"@id\": \"pinpoint:ReferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SendMessagesResponse\": \"pinpoint:SendMessagesResponse\",\n    \"InAppMessageContent\": \"pinpoint:InAppMessageContent\",\n    \"BackgroundColor\": {\n      \"@id\": \"pinpoint:BackgroundColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BodyConfig\": {\n      \"@id\": \"pinpoint:BodyConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HeaderConfig\": {\n      \"@id\": \"pinpoint:HeaderConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageUrl\": {\n      \"@id\": \"pinpoint:ImageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrimaryBtn\": {\n      \"@id\": \"pinpoint:PrimaryBtn\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"SecondaryBtn\": {\n      \"@id\": \"pinpoint:SecondaryBtn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowedAttempts\": {\n      \"@id\": \"pinpoint:AllowedAttempts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BrandName\": {\n      \"@id\": \"pinpoint:BrandName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Channel\": {\n      \"@id\": \"pinpoint:Channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeLength\": {\n      \"@id\": \"pinpoint:CodeLength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityId\": {\n      \"@id\": \"pinpoint:EntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Language\": {\n      \"@id\": \"pinpoint:Language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OriginationIdentity\": {\n      \"@id\": \"pinpoint:OriginationIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateId\": {\n      \"@id\": \"pinpoint:TemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidityPeriod\"\
  : {\n      \"@id\": \"pinpoint:ValidityPeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Message\": \"pinpoint:Message\",\n    \"ImageIconUrl\": {\n      \"@id\": \"pinpoint:ImageIconUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageSmallIconUrl\": {\n      \"@id\": \"pinpoint:ImageSmallIconUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JsonBody\": {\n      \"@id\": \"pinpoint:JsonBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MediaUrl\": {\n      \"@id\": \"pinpoint:MediaUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimeToLive\": {\n      \"@id\": \"pinpoint:TimeToLive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InAppMessageButton\": \"pinpoint:InAppMessageButton\",\n    \"Android\": {\n      \"@id\": \"pinpoint:Android\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultConfig\": {\n      \"@id\": \"pinpoint:DefaultConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IOS\": {\n      \"@id\": \"pinpoint:IOS\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"Web\": {\n      \"@id\": \"pinpoint:Web\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-messages-context.jsonld
tags:
- AWS
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
