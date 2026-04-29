---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 125
classes:
- CreateVoiceTemplateResponse
- DeleteBaiduChannelRequest
- GetSmsChannelResponse
- SMSChannelResponse
- EmailTemplateRequest
- APNSChannelRequest
- GetGcmChannelRequest
- UpdateEmailChannelRequest
- EmailChannelRequest
- UpdateEmailTemplateResponse
- GetApnsVoipSandboxChannelResponse
- APNSVoipSandboxChannelResponse
- DeleteVoiceChannelResponse
- VoiceChannelResponse
- GetApnsVoipChannelResponse
- APNSVoipChannelResponse
- GetGcmChannelResponse
- GCMChannelResponse
- UpdateSmsTemplateRequest
- SMSTemplateRequest
- DeleteApnsVoipSandboxChannelRequest
- VoiceTemplateRequest
- BaiduChannelResponse
- GetApnsVoipSandboxChannelRequest
- DeleteVoiceChannelRequest
- GCMMessage
- DeleteSmsTemplateRequest
- CreateSmsTemplateResponse
- UpdateApnsChannelResponse
- APNSChannelResponse
- GetEmailTemplateResponse
- EmailTemplateResponse
- GetAdmChannelResponse
- ADMChannelResponse
- GetChannelsRequest
- DeleteSmsTemplateResponse
- DeleteEmailChannelResponse
- EmailChannelResponse
- UpdateAdmChannelRequest
- ADMChannelRequest
- GetApnsChannelRequest
- APNSMessage
- EmailMessage
- RawEmail
- SimpleEmail
- GetEmailChannelResponse
- APNSVoipChannelRequest
- GetVoiceChannelRequest
- DeleteVoiceTemplateResponse
- SMSTemplateResponse
- UpdateApnsVoipSandboxChannelRequest
- APNSVoipSandboxChannelRequest
- VoiceChannelRequest
- UpdateBaiduChannelResponse
- GetSmsTemplateResponse
- APNSPushNotificationTemplate
- UpdateVoiceTemplateRequest
- DeleteApnsVoipChannelRequest
- APNSSandboxChannelResponse
- GetBaiduChannelRequest
- GetApnsVoipChannelRequest
- GetVoiceChannelResponse
- UpdateSmsChannelRequest
- SMSChannelRequest
- APNSSandboxChannelRequest
- GCMChannelRequest
- UpdateApnsSandboxChannelRequest
- DeleteGcmChannelRequest
- UpdateEmailTemplateRequest
- BaiduChannelRequest
- GetApnsSandboxChannelRequest
- GetEmailTemplateRequest
- VoiceMessage
- BaiduMessage
- DeleteAdmChannelRequest
- UpdateApnsVoipChannelRequest
- UpdateVoiceChannelResponse
- GetApnsChannelResponse
- GetChannelsResponse
- ChannelsResponse
- SimpleEmailPart
- DeleteApnsVoipChannelResponse
- DeleteApnsSandboxChannelRequest
- UpdateApnsChannelRequest
- DeleteEmailTemplateResponse
- ChannelResponse
- GetApnsSandboxChannelResponse
- DeleteSmsChannelRequest
- GetEmailChannelRequest
- GetBaiduChannelResponse
- GetVoiceTemplateRequest
- DeleteApnsChannelRequest
- UpdateApnsVoipChannelResponse
- VoiceTemplateResponse
- UpdateEmailChannelResponse
- UpdateGcmChannelRequest
- UpdateApnsVoipSandboxChannelResponse
- GetSmsTemplateRequest
- DeleteAdmChannelResponse
- UpdateGcmChannelResponse
- DeleteApnsSandboxChannelResponse
- UpdateVoiceTemplateResponse
- UpdateBaiduChannelRequest
- CreateVoiceTemplateRequest
- DeleteEmailChannelRequest
- SMSMessage
- CreateEmailTemplateResponse
- UpdateSmsChannelResponse
- UpdateApnsSandboxChannelResponse
- DeleteVoiceTemplateRequest
- GetSmsChannelRequest
- DeleteBaiduChannelResponse
- CreateSmsTemplateRequest
- GetVoiceTemplateResponse
- UpdateVoiceChannelRequest
- CreateEmailTemplateRequest
- DeleteGcmChannelResponse
- UpdateAdmChannelResponse
- DeleteEmailTemplateRequest
- ADMMessage
- DeleteApnsChannelResponse
- GetAdmChannelRequest
- DeleteApnsVoipSandboxChannelResponse
- UpdateSmsTemplateResponse
- DeleteSmsChannelResponse
context_file: json-ld/amazon-pinpoint-channels-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-channels-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Channels from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Channels Context
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
  name: CreateTemplateMessageBody
  type: string
- container: ''
  name: DefaultSubstitutions
  type: string
- container: ''
  name: HtmlPart
  type: string
- container: ''
  name: RecommenderId
  type: string
- container: ''
  name: Subject
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: TemplateDescription
  type: string
- container: ''
  name: TextPart
  type: string
- container: ''
  name: BundleId
  type: string
- container: ''
  name: Certificate
  type: string
- container: ''
  name: DefaultAuthenticationMethod
  type: string
- container: ''
  name: Enabled
  type: string
- container: ''
  name: PrivateKey
  type: string
- container: ''
  name: TeamId
  type: string
- container: ''
  name: TokenKey
  type: string
- container: ''
  name: TokenKeyId
  type: string
- container: ''
  name: MessageBody
  type: string
- container: ''
  name: Body
  type: string
- container: ''
  name: LanguageCode
  type: string
- container: ''
  name: VoiceId
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: Credential
  type: string
- container: ''
  name: HasCredential
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: IsArchived
  type: string
- container: ''
  name: LastModifiedBy
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: Platform
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: CollapseKey
  type: string
- container: ''
  name: Data
  type: string
- container: ''
  name: IconReference
  type: string
- container: ''
  name: ImageIconUrl
  type: string
- container: ''
  name: ImageUrl
  type: string
- container: ''
  name: Priority
  type: string
- container: ''
  name: RawContent
  type: string
- container: ''
  name: RestrictedPackageName
  type: string
- container: ''
  name: SilentPush
  type: string
- container: ''
  name: SmallImageIconUrl
  type: string
- container: ''
  name: Sound
  type: string
- container: ''
  name: Substitutions
  type: string
- container: ''
  name: TimeToLive
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Url
  type: string
- container: ''
  name: APNSPushType
  type: string
- container: ''
  name: Badge
  type: string
- container: ''
  name: Category
  type: string
- container: ''
  name: CollapseId
  type: string
- container: ''
  name: MediaUrl
  type: string
- container: ''
  name: PreferredAuthenticationMethod
  type: string
- container: ''
  name: ThreadId
  type: string
- container: ''
  name: FeedbackForwardingAddress
  type: string
- container: ''
  name: FromAddress
  type: string
- container: ''
  name: ReplyToAddresses
  type: string
- container: ''
  name: PromotionalMessagesPerSecond
  type: string
- container: ''
  name: SenderId
  type: string
- container: ''
  name: ShortCode
  type: string
- container: ''
  name: TransactionalMessagesPerSecond
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: TemplateName
  type: string
- container: ''
  name: TemplateType
  type: string
- container: ''
  name: HasTokenKey
  type: string
- container: ''
  name: ApiKey
  type: string
- container: ''
  name: SecretKey
  type: string
- container: ''
  name: OriginationNumber
  type: string
- container: ''
  name: ClientId
  type: string
- container: ''
  name: ClientSecret
  type: string
- container: ''
  name: Charset
  type: string
- container: ''
  name: ConfigurationSet
  type: string
- container: ''
  name: Identity
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: MessagesPerSecond
  type: string
- container: ''
  name: Keyword
  type: string
- container: ''
  name: MessageType
  type: string
- container: ''
  name: EntityId
  type: string
- container: ''
  name: TemplateId
  type: string
- container: ''
  name: ConsolidationKey
  type: string
- container: ''
  name: ExpiresAfter
  type: string
- container: ''
  name: MD5
  type: string
- container: ''
  name: Channels
  type: string
property_count: 82
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-channels-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateVoiceTemplateResponse\": \"pinpoint:CreateVoiceTemplateResponse\",\n    \"CreateTemplateMessageBody\": {\n      \"@id\": \"pinpoint:CreateTemplateMessageBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteBaiduChannelRequest\": \"pinpoint:DeleteBaiduChannelRequest\",\n    \"GetSmsChannelResponse\": \"pinpoint:GetSmsChannelResponse\",\n    \"SMSChannelResponse\": \"pinpoint:SMSChannelResponse\",\n    \"EmailTemplateRequest\": \"pinpoint:EmailTemplateRequest\",\n    \"DefaultSubstitutions\": {\n      \"@id\": \"pinpoint:DefaultSubstitutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HtmlPart\": {\n      \"@id\": \"pinpoint:HtmlPart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommenderId\"\
  : {\n      \"@id\": \"pinpoint:RecommenderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subject\": {\n      \"@id\": \"pinpoint:Subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateDescription\": {\n      \"@id\": \"pinpoint:TemplateDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TextPart\": {\n      \"@id\": \"pinpoint:TextPart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APNSChannelRequest\": \"pinpoint:APNSChannelRequest\",\n    \"BundleId\": {\n      \"@id\": \"pinpoint:BundleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Certificate\": {\n      \"@id\": \"pinpoint:Certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultAuthenticationMethod\": {\n      \"@id\": \"pinpoint:DefaultAuthenticationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Enabled\": {\n      \"@id\": \"pinpoint:Enabled\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"PrivateKey\": {\n      \"@id\": \"pinpoint:PrivateKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TeamId\": {\n      \"@id\": \"pinpoint:TeamId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenKey\": {\n      \"@id\": \"pinpoint:TokenKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenKeyId\": {\n      \"@id\": \"pinpoint:TokenKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetGcmChannelRequest\": \"pinpoint:GetGcmChannelRequest\",\n    \"UpdateEmailChannelRequest\": \"pinpoint:UpdateEmailChannelRequest\",\n    \"EmailChannelRequest\": \"pinpoint:EmailChannelRequest\",\n    \"UpdateEmailTemplateResponse\": \"pinpoint:UpdateEmailTemplateResponse\",\n    \"MessageBody\": {\n      \"@id\": \"pinpoint:MessageBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetApnsVoipSandboxChannelResponse\": \"pinpoint:GetApnsVoipSandboxChannelResponse\",\n    \"APNSVoipSandboxChannelResponse\": \"pinpoint:APNSVoipSandboxChannelResponse\",\n    \"DeleteVoiceChannelResponse\"\
  : \"pinpoint:DeleteVoiceChannelResponse\",\n    \"VoiceChannelResponse\": \"pinpoint:VoiceChannelResponse\",\n    \"GetApnsVoipChannelResponse\": \"pinpoint:GetApnsVoipChannelResponse\",\n    \"APNSVoipChannelResponse\": \"pinpoint:APNSVoipChannelResponse\",\n    \"GetGcmChannelResponse\": \"pinpoint:GetGcmChannelResponse\",\n    \"GCMChannelResponse\": \"pinpoint:GCMChannelResponse\",\n    \"UpdateSmsTemplateRequest\": \"pinpoint:UpdateSmsTemplateRequest\",\n    \"SMSTemplateRequest\": \"pinpoint:SMSTemplateRequest\",\n    \"DeleteApnsVoipSandboxChannelRequest\": \"pinpoint:DeleteApnsVoipSandboxChannelRequest\",\n    \"VoiceTemplateRequest\": \"pinpoint:VoiceTemplateRequest\",\n    \"Body\": {\n      \"@id\": \"pinpoint:Body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LanguageCode\": {\n      \"@id\": \"pinpoint:LanguageCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VoiceId\": {\n      \"@id\": \"pinpoint:VoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BaiduChannelResponse\"\
  : \"pinpoint:BaiduChannelResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Credential\": {\n      \"@id\": \"pinpoint:Credential\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HasCredential\": {\n      \"@id\": \"pinpoint:HasCredential\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsArchived\": {\n      \"@id\": \"pinpoint:IsArchived\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedBy\": {\n      \"@id\": \"pinpoint:LastModifiedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Platform\": {\n      \"@id\": \"pinpoint:Platform\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"Version\": {\n      \"@id\": \"pinpoint:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetApnsVoipSandboxChannelRequest\": \"pinpoint:GetApnsVoipSandboxChannelRequest\",\n    \"DeleteVoiceChannelRequest\": \"pinpoint:DeleteVoiceChannelRequest\",\n    \"GCMMessage\": \"pinpoint:GCMMessage\",\n    \"Action\": {\n      \"@id\": \"pinpoint:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollapseKey\": {\n      \"@id\": \"pinpoint:CollapseKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Data\": {\n      \"@id\": \"pinpoint:Data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IconReference\": {\n      \"@id\": \"pinpoint:IconReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageIconUrl\": {\n      \"@id\": \"pinpoint:ImageIconUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageUrl\": {\n      \"@id\": \"pinpoint:ImageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Priority\": {\n      \"@id\": \"pinpoint:Priority\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"RawContent\": {\n      \"@id\": \"pinpoint:RawContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RestrictedPackageName\": {\n      \"@id\": \"pinpoint:RestrictedPackageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SilentPush\": {\n      \"@id\": \"pinpoint:SilentPush\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SmallImageIconUrl\": {\n      \"@id\": \"pinpoint:SmallImageIconUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sound\": {\n      \"@id\": \"pinpoint:Sound\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Substitutions\": {\n      \"@id\": \"pinpoint:Substitutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimeToLive\": {\n      \"@id\": \"pinpoint:TimeToLive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"pinpoint:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Url\": {\n      \"@id\": \"pinpoint:Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteSmsTemplateRequest\"\
  : \"pinpoint:DeleteSmsTemplateRequest\",\n    \"CreateSmsTemplateResponse\": \"pinpoint:CreateSmsTemplateResponse\",\n    \"UpdateApnsChannelResponse\": \"pinpoint:UpdateApnsChannelResponse\",\n    \"APNSChannelResponse\": \"pinpoint:APNSChannelResponse\",\n    \"GetEmailTemplateResponse\": \"pinpoint:GetEmailTemplateResponse\",\n    \"EmailTemplateResponse\": \"pinpoint:EmailTemplateResponse\",\n    \"GetAdmChannelResponse\": \"pinpoint:GetAdmChannelResponse\",\n    \"ADMChannelResponse\": \"pinpoint:ADMChannelResponse\",\n    \"GetChannelsRequest\": \"pinpoint:GetChannelsRequest\",\n    \"DeleteSmsTemplateResponse\": \"pinpoint:DeleteSmsTemplateResponse\",\n    \"DeleteEmailChannelResponse\": \"pinpoint:DeleteEmailChannelResponse\",\n    \"EmailChannelResponse\": \"pinpoint:EmailChannelResponse\",\n    \"UpdateAdmChannelRequest\": \"pinpoint:UpdateAdmChannelRequest\",\n    \"ADMChannelRequest\": \"pinpoint:ADMChannelRequest\",\n    \"GetApnsChannelRequest\": \"pinpoint:GetApnsChannelRequest\"\
  ,\n    \"APNSMessage\": \"pinpoint:APNSMessage\",\n    \"APNSPushType\": {\n      \"@id\": \"pinpoint:APNSPushType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Badge\": {\n      \"@id\": \"pinpoint:Badge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Category\": {\n      \"@id\": \"pinpoint:Category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollapseId\": {\n      \"@id\": \"pinpoint:CollapseId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MediaUrl\": {\n      \"@id\": \"pinpoint:MediaUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PreferredAuthenticationMethod\": {\n      \"@id\": \"pinpoint:PreferredAuthenticationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ThreadId\": {\n      \"@id\": \"pinpoint:ThreadId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailMessage\": \"pinpoint:EmailMessage\",\n    \"FeedbackForwardingAddress\": {\n      \"@id\": \"pinpoint:FeedbackForwardingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FromAddress\"\
  : {\n      \"@id\": \"pinpoint:FromAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RawEmail\": \"pinpoint:RawEmail\",\n    \"ReplyToAddresses\": {\n      \"@id\": \"pinpoint:ReplyToAddresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SimpleEmail\": \"pinpoint:SimpleEmail\",\n    \"GetEmailChannelResponse\": \"pinpoint:GetEmailChannelResponse\",\n    \"APNSVoipChannelRequest\": \"pinpoint:APNSVoipChannelRequest\",\n    \"GetVoiceChannelRequest\": \"pinpoint:GetVoiceChannelRequest\",\n    \"DeleteVoiceTemplateResponse\": \"pinpoint:DeleteVoiceTemplateResponse\",\n    \"PromotionalMessagesPerSecond\": {\n      \"@id\": \"pinpoint:PromotionalMessagesPerSecond\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SenderId\": {\n      \"@id\": \"pinpoint:SenderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShortCode\": {\n      \"@id\": \"pinpoint:ShortCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactionalMessagesPerSecond\": {\n      \"@id\": \"pinpoint:TransactionalMessagesPerSecond\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"SMSTemplateResponse\": \"pinpoint:SMSTemplateResponse\",\n    \"Arn\": {\n      \"@id\": \"pinpoint:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateName\": {\n      \"@id\": \"pinpoint:TemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateType\": {\n      \"@id\": \"pinpoint:TemplateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateApnsVoipSandboxChannelRequest\": \"pinpoint:UpdateApnsVoipSandboxChannelRequest\",\n    \"APNSVoipSandboxChannelRequest\": \"pinpoint:APNSVoipSandboxChannelRequest\",\n    \"VoiceChannelRequest\": \"pinpoint:VoiceChannelRequest\",\n    \"UpdateBaiduChannelResponse\": \"pinpoint:UpdateBaiduChannelResponse\",\n    \"GetSmsTemplateResponse\": \"pinpoint:GetSmsTemplateResponse\",\n    \"APNSPushNotificationTemplate\": \"pinpoint:APNSPushNotificationTemplate\",\n    \"UpdateVoiceTemplateRequest\": \"pinpoint:UpdateVoiceTemplateRequest\",\n    \"DeleteApnsVoipChannelRequest\"\
  : \"pinpoint:DeleteApnsVoipChannelRequest\",\n    \"APNSSandboxChannelResponse\": \"pinpoint:APNSSandboxChannelResponse\",\n    \"HasTokenKey\": {\n      \"@id\": \"pinpoint:HasTokenKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetBaiduChannelRequest\": \"pinpoint:GetBaiduChannelRequest\",\n    \"GetApnsVoipChannelRequest\": \"pinpoint:GetApnsVoipChannelRequest\",\n    \"GetVoiceChannelResponse\": \"pinpoint:GetVoiceChannelResponse\",\n    \"UpdateSmsChannelRequest\": \"pinpoint:UpdateSmsChannelRequest\",\n    \"SMSChannelRequest\": \"pinpoint:SMSChannelRequest\",\n    \"APNSSandboxChannelRequest\": \"pinpoint:APNSSandboxChannelRequest\",\n    \"GCMChannelRequest\": \"pinpoint:GCMChannelRequest\",\n    \"ApiKey\": {\n      \"@id\": \"pinpoint:ApiKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateApnsSandboxChannelRequest\": \"pinpoint:UpdateApnsSandboxChannelRequest\",\n    \"DeleteGcmChannelRequest\": \"pinpoint:DeleteGcmChannelRequest\",\n    \"UpdateEmailTemplateRequest\"\
  : \"pinpoint:UpdateEmailTemplateRequest\",\n    \"BaiduChannelRequest\": \"pinpoint:BaiduChannelRequest\",\n    \"SecretKey\": {\n      \"@id\": \"pinpoint:SecretKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetApnsSandboxChannelRequest\": \"pinpoint:GetApnsSandboxChannelRequest\",\n    \"GetEmailTemplateRequest\": \"pinpoint:GetEmailTemplateRequest\",\n    \"VoiceMessage\": \"pinpoint:VoiceMessage\",\n    \"OriginationNumber\": {\n      \"@id\": \"pinpoint:OriginationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BaiduMessage\": \"pinpoint:BaiduMessage\",\n    \"DeleteAdmChannelRequest\": \"pinpoint:DeleteAdmChannelRequest\",\n    \"ClientId\": {\n      \"@id\": \"pinpoint:ClientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientSecret\": {\n      \"@id\": \"pinpoint:ClientSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateApnsVoipChannelRequest\": \"pinpoint:UpdateApnsVoipChannelRequest\",\n    \"UpdateVoiceChannelResponse\": \"pinpoint:UpdateVoiceChannelResponse\"\
  ,\n    \"GetApnsChannelResponse\": \"pinpoint:GetApnsChannelResponse\",\n    \"GetChannelsResponse\": \"pinpoint:GetChannelsResponse\",\n    \"ChannelsResponse\": \"pinpoint:ChannelsResponse\",\n    \"SimpleEmailPart\": \"pinpoint:SimpleEmailPart\",\n    \"Charset\": {\n      \"@id\": \"pinpoint:Charset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteApnsVoipChannelResponse\": \"pinpoint:DeleteApnsVoipChannelResponse\",\n    \"DeleteApnsSandboxChannelRequest\": \"pinpoint:DeleteApnsSandboxChannelRequest\",\n    \"UpdateApnsChannelRequest\": \"pinpoint:UpdateApnsChannelRequest\",\n    \"DeleteEmailTemplateResponse\": \"pinpoint:DeleteEmailTemplateResponse\",\n    \"ChannelResponse\": \"pinpoint:ChannelResponse\",\n    \"GetApnsSandboxChannelResponse\": \"pinpoint:GetApnsSandboxChannelResponse\",\n    \"DeleteSmsChannelRequest\": \"pinpoint:DeleteSmsChannelRequest\",\n    \"GetEmailChannelRequest\": \"pinpoint:GetEmailChannelRequest\",\n    \"GetBaiduChannelResponse\": \"pinpoint:GetBaiduChannelResponse\"\
  ,\n    \"GetVoiceTemplateRequest\": \"pinpoint:GetVoiceTemplateRequest\",\n    \"DeleteApnsChannelRequest\": \"pinpoint:DeleteApnsChannelRequest\",\n    \"UpdateApnsVoipChannelResponse\": \"pinpoint:UpdateApnsVoipChannelResponse\",\n    \"ConfigurationSet\": {\n      \"@id\": \"pinpoint:ConfigurationSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Identity\": {\n      \"@id\": \"pinpoint:Identity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"pinpoint:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VoiceTemplateResponse\": \"pinpoint:VoiceTemplateResponse\",\n    \"UpdateEmailChannelResponse\": \"pinpoint:UpdateEmailChannelResponse\",\n    \"UpdateGcmChannelRequest\": \"pinpoint:UpdateGcmChannelRequest\",\n    \"UpdateApnsVoipSandboxChannelResponse\": \"pinpoint:UpdateApnsVoipSandboxChannelResponse\",\n    \"GetSmsTemplateRequest\": \"pinpoint:GetSmsTemplateRequest\",\n    \"DeleteAdmChannelResponse\": \"pinpoint:DeleteAdmChannelResponse\"\
  ,\n    \"UpdateGcmChannelResponse\": \"pinpoint:UpdateGcmChannelResponse\",\n    \"DeleteApnsSandboxChannelResponse\": \"pinpoint:DeleteApnsSandboxChannelResponse\",\n    \"UpdateVoiceTemplateResponse\": \"pinpoint:UpdateVoiceTemplateResponse\",\n    \"UpdateBaiduChannelRequest\": \"pinpoint:UpdateBaiduChannelRequest\",\n    \"CreateVoiceTemplateRequest\": \"pinpoint:CreateVoiceTemplateRequest\",\n    \"DeleteEmailChannelRequest\": \"pinpoint:DeleteEmailChannelRequest\",\n    \"MessagesPerSecond\": {\n      \"@id\": \"pinpoint:MessagesPerSecond\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMSMessage\": \"pinpoint:SMSMessage\",\n    \"Keyword\": {\n      \"@id\": \"pinpoint:Keyword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageType\": {\n      \"@id\": \"pinpoint:MessageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityId\": {\n      \"@id\": \"pinpoint:EntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateId\": {\n      \"@id\": \"pinpoint:TemplateId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateEmailTemplateResponse\": \"pinpoint:CreateEmailTemplateResponse\",\n    \"UpdateSmsChannelResponse\": \"pinpoint:UpdateSmsChannelResponse\",\n    \"UpdateApnsSandboxChannelResponse\": \"pinpoint:UpdateApnsSandboxChannelResponse\",\n    \"DeleteVoiceTemplateRequest\": \"pinpoint:DeleteVoiceTemplateRequest\",\n    \"GetSmsChannelRequest\": \"pinpoint:GetSmsChannelRequest\",\n    \"DeleteBaiduChannelResponse\": \"pinpoint:DeleteBaiduChannelResponse\",\n    \"CreateSmsTemplateRequest\": \"pinpoint:CreateSmsTemplateRequest\",\n    \"GetVoiceTemplateResponse\": \"pinpoint:GetVoiceTemplateResponse\",\n    \"UpdateVoiceChannelRequest\": \"pinpoint:UpdateVoiceChannelRequest\",\n    \"CreateEmailTemplateRequest\": \"pinpoint:CreateEmailTemplateRequest\",\n    \"DeleteGcmChannelResponse\": \"pinpoint:DeleteGcmChannelResponse\",\n    \"UpdateAdmChannelResponse\": \"pinpoint:UpdateAdmChannelResponse\",\n    \"DeleteEmailTemplateRequest\": \"pinpoint:DeleteEmailTemplateRequest\"\
  ,\n    \"ADMMessage\": \"pinpoint:ADMMessage\",\n    \"ConsolidationKey\": {\n      \"@id\": \"pinpoint:ConsolidationKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpiresAfter\": {\n      \"@id\": \"pinpoint:ExpiresAfter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MD5\": {\n      \"@id\": \"pinpoint:MD5\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteApnsChannelResponse\": \"pinpoint:DeleteApnsChannelResponse\",\n    \"GetAdmChannelRequest\": \"pinpoint:GetAdmChannelRequest\",\n    \"DeleteApnsVoipSandboxChannelResponse\": \"pinpoint:DeleteApnsVoipSandboxChannelResponse\",\n    \"UpdateSmsTemplateResponse\": \"pinpoint:UpdateSmsTemplateResponse\",\n    \"DeleteSmsChannelResponse\": \"pinpoint:DeleteSmsChannelResponse\",\n    \"Channels\": {\n      \"@id\": \"pinpoint:Channels\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-channels-context.jsonld
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
