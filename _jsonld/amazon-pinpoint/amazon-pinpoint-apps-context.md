---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 9
classes:
- GetAppRequest
- DeleteAppRequest
- GetAppsRequest
- CreateAppRequest
- CreateApplicationRequest
- WriteApplicationSettingsRequest
- UpdateApplicationSettingsRequest
- GetApplicationSettingsRequest
- ApplicationSettingsResource
context_file: json-ld/amazon-pinpoint-apps-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-apps-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Apps from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Apps Context
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
  name: CampaignHook
  type: string
- container: ''
  name: CloudWatchMetricsEnabled
  type: string
- container: ''
  name: EventTaggingEnabled
  type: string
- container: ''
  name: Limits
  type: string
- container: ''
  name: QuietTime
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: tags
  type: string
property_count: 9
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-apps-context
source_filename: amazon-pinpoint-apps-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetAppRequest\": \"pinpoint:GetAppRequest\",\n    \"DeleteAppRequest\": \"pinpoint:DeleteAppRequest\",\n    \"GetAppsRequest\": \"pinpoint:GetAppsRequest\",\n    \"CreateAppRequest\": \"pinpoint:CreateAppRequest\",\n    \"CreateApplicationRequest\": \"pinpoint:CreateApplicationRequest\",\n    \"WriteApplicationSettingsRequest\": \"pinpoint:WriteApplicationSettingsRequest\",\n    \"CampaignHook\": {\n      \"@id\": \"pinpoint:CampaignHook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudWatchMetricsEnabled\": {\n      \"@id\": \"pinpoint:CloudWatchMetricsEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventTaggingEnabled\": {\n      \"@id\": \"pinpoint:EventTaggingEnabled\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Limits\": {\n      \"@id\": \"pinpoint:Limits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuietTime\": {\n      \"@id\": \"pinpoint:QuietTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateApplicationSettingsRequest\": \"pinpoint:UpdateApplicationSettingsRequest\",\n    \"GetApplicationSettingsRequest\": \"pinpoint:GetApplicationSettingsRequest\",\n    \"ApplicationSettingsResource\": \"pinpoint:ApplicationSettingsResource\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-apps-context.jsonld
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
