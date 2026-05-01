---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 27
classes:
- EndpointMessageResult
- SendUsersMessageRequest
- DeleteUserEndpointsRequest
- DeleteUserEndpointsResponse
- EndpointsResponse
- GetUserEndpointsRequest
- EndpointItemResponse
- DeleteEndpointRequest
- UpdateEndpointRequest
- EndpointRequest
- GetEndpointRequest
- EndpointUser
- SendUsersMessageResponse
- EndpointResponse
- EndpointBatchItem
- SendUsersMessagesResponse
- GetUserEndpointsResponse
- UpdateEndpointsBatchResponse
- UpdateEndpointsBatchRequest
- EndpointBatchRequest
- SendUsersMessagesRequest
- DeleteEndpointResponse
- EndpointLocation
- EndpointSendConfiguration
- PublicEndpoint
- UpdateEndpointResponse
- GetEndpointResponse
context_file: json-ld/amazon-pinpoint-endpoints-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-endpoints-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Endpoints from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Endpoints Context
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
  name: Address
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
  name: Context
  type: string
- container: ''
  name: MessageConfiguration
  type: string
- container: ''
  name: TemplateConfiguration
  type: string
- container: ''
  name: TraceId
  type: string
- container: ''
  name: Users
  type: string
- container: ''
  name: Item
  type: string
- container: ''
  name: Message
  type: string
- container: ''
  name: UserAttributes
  type: string
- container: ''
  name: UserId
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: RequestId
  type: string
- container: ''
  name: Result
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: ChannelType
  type: string
- container: ''
  name: CohortId
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: Demographic
  type: string
- container: ''
  name: EffectiveDate
  type: string
- container: ''
  name: EndpointStatus
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Location
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: OptOut
  type: string
- container: ''
  name: User
  type: string
- container: ''
  name: MessageBody
  type: string
- container: ''
  name: City
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: Latitude
  type: string
- container: ''
  name: Longitude
  type: string
- container: ''
  name: PostalCode
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: BodyOverride
  type: string
- container: ''
  name: RawContent
  type: string
- container: ''
  name: Substitutions
  type: string
- container: ''
  name: TitleOverride
  type: string
property_count: 41
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-endpoints-context
source_filename: amazon-pinpoint-endpoints-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EndpointMessageResult\": \"pinpoint:EndpointMessageResult\",\n    \"Address\": {\n      \"@id\": \"pinpoint:Address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeliveryStatus\": {\n      \"@id\": \"pinpoint:DeliveryStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageId\": {\n      \"@id\": \"pinpoint:MessageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusCode\": {\n      \"@id\": \"pinpoint:StatusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusMessage\": {\n      \"@id\": \"pinpoint:StatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatedToken\": {\n      \"@id\": \"pinpoint:UpdatedToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SendUsersMessageRequest\"\
  : \"pinpoint:SendUsersMessageRequest\",\n    \"Context\": {\n      \"@id\": \"pinpoint:Context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageConfiguration\": {\n      \"@id\": \"pinpoint:MessageConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateConfiguration\": {\n      \"@id\": \"pinpoint:TemplateConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TraceId\": {\n      \"@id\": \"pinpoint:TraceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Users\": {\n      \"@id\": \"pinpoint:Users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteUserEndpointsRequest\": \"pinpoint:DeleteUserEndpointsRequest\",\n    \"DeleteUserEndpointsResponse\": \"pinpoint:DeleteUserEndpointsResponse\",\n    \"EndpointsResponse\": \"pinpoint:EndpointsResponse\",\n    \"GetUserEndpointsRequest\": \"pinpoint:GetUserEndpointsRequest\",\n    \"Item\": {\n      \"@id\": \"pinpoint:Item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointItemResponse\": \"\
  pinpoint:EndpointItemResponse\",\n    \"Message\": {\n      \"@id\": \"pinpoint:Message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteEndpointRequest\": \"pinpoint:DeleteEndpointRequest\",\n    \"UpdateEndpointRequest\": \"pinpoint:UpdateEndpointRequest\",\n    \"EndpointRequest\": \"pinpoint:EndpointRequest\",\n    \"GetEndpointRequest\": \"pinpoint:GetEndpointRequest\",\n    \"EndpointUser\": \"pinpoint:EndpointUser\",\n    \"UserAttributes\": {\n      \"@id\": \"pinpoint:UserAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserId\": {\n      \"@id\": \"pinpoint:UserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SendUsersMessageResponse\": \"pinpoint:SendUsersMessageResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestId\": {\n      \"@id\": \"pinpoint:RequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Result\": {\n      \"@id\": \"pinpoint:Result\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"EndpointResponse\": \"pinpoint:EndpointResponse\",\n    \"Attributes\": {\n      \"@id\": \"pinpoint:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelType\": {\n      \"@id\": \"pinpoint:ChannelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CohortId\": {\n      \"@id\": \"pinpoint:CohortId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Demographic\": {\n      \"@id\": \"pinpoint:Demographic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EffectiveDate\": {\n      \"@id\": \"pinpoint:EffectiveDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointStatus\": {\n      \"@id\": \"pinpoint:EndpointStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Location\": {\n      \"@id\": \"pinpoint:Location\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"Metrics\": {\n      \"@id\": \"pinpoint:Metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OptOut\": {\n      \"@id\": \"pinpoint:OptOut\",\n      \"@type\": \"xsd:string\"\n    },\n    \"User\": {\n      \"@id\": \"pinpoint:User\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointBatchItem\": \"pinpoint:EndpointBatchItem\",\n    \"SendUsersMessagesResponse\": \"pinpoint:SendUsersMessagesResponse\",\n    \"GetUserEndpointsResponse\": \"pinpoint:GetUserEndpointsResponse\",\n    \"UpdateEndpointsBatchResponse\": \"pinpoint:UpdateEndpointsBatchResponse\",\n    \"MessageBody\": {\n      \"@id\": \"pinpoint:MessageBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateEndpointsBatchRequest\": \"pinpoint:UpdateEndpointsBatchRequest\",\n    \"EndpointBatchRequest\": \"pinpoint:EndpointBatchRequest\",\n    \"SendUsersMessagesRequest\": \"pinpoint:SendUsersMessagesRequest\",\n    \"DeleteEndpointResponse\": \"pinpoint:DeleteEndpointResponse\"\
  ,\n    \"EndpointLocation\": \"pinpoint:EndpointLocation\",\n    \"City\": {\n      \"@id\": \"pinpoint:City\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Country\": {\n      \"@id\": \"pinpoint:Country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Latitude\": {\n      \"@id\": \"pinpoint:Latitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Longitude\": {\n      \"@id\": \"pinpoint:Longitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PostalCode\": {\n      \"@id\": \"pinpoint:PostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Region\": {\n      \"@id\": \"pinpoint:Region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointSendConfiguration\": \"pinpoint:EndpointSendConfiguration\",\n    \"BodyOverride\": {\n      \"@id\": \"pinpoint:BodyOverride\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RawContent\": {\n      \"@id\": \"pinpoint:RawContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Substitutions\": {\n      \"@id\": \"pinpoint:Substitutions\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"TitleOverride\": {\n      \"@id\": \"pinpoint:TitleOverride\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublicEndpoint\": \"pinpoint:PublicEndpoint\",\n    \"UpdateEndpointResponse\": \"pinpoint:UpdateEndpointResponse\",\n    \"GetEndpointResponse\": \"pinpoint:GetEndpointResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-endpoints-context.jsonld
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
