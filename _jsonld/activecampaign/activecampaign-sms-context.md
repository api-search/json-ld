---
api_specs:
- filename: activecampaign-v3.json
  format: json
  label: ActiveCampaign API v3
  slug: activecampaign-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/openapi/activecampaign-v3.json
- filename: activecampaign-sms.json
  format: json
  label: ActiveCampaign SMS Broadcast API
  slug: activecampaign-sms
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/openapi/activecampaign-sms.json
class_count: 18
classes:
- BroadcastListsResponse
- BroadcastUpdateRequest
- AIBroadcastRequest
- BroadcastMetrics
- BroadcastList
- BroadcastMessage
- SnapshotResponse
- BroadcastCreateRequest
- BroadcastMetricsResponse
- CreditsResponse
- RecipientsResponse
- FailureDetail
- AIBroadcastUpdateRequest
- AIBroadcastStatus
- BroadcastListResponse
- AIBroadcastResponse
- FailureDetailsResponse
- Recipient
context_file: json-ld/activecampaign-sms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/json-ld/activecampaign-sms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Activecampaign Sms from ActiveCampaign.
layout: jsonld
name: Activecampaign Sms Context
namespaces:
- prefix: activecampaign
  uri: https://developers.activecampaign.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: lists
  type: string
- container: ''
  name: meta
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: addressId
  type: integer
- container: ''
  name: body
  type: string
- container: set
  name: mediaUrls
  type: reference
- container: ''
  name: previewUrl
  type: reference
- container: ''
  name: shortenTrackLinksEnabled
  type: boolean
- container: ''
  name: status
  type: string
- container: ''
  name: scheduledDate
  type: dateTime
- container: ''
  name: sentToCount
  type: integer
- container: set
  name: listIds
  type: integer
- container: ''
  name: segmentId
  type: string
- container: ''
  name: customRunId
  type: string
- container: ''
  name: customSegmentId
  type: string
- container: set
  name: labelIds
  type: integer
- container: ''
  name: source
  type: string
- container: ''
  name: prompt
  type: string
- container: ''
  name: tone
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: sends
  type: integer
- container: ''
  name: deliveries
  type: integer
- container: ''
  name: replies
  type: integer
- container: ''
  name: failures
  type: integer
- container: ''
  name: optOuts
  type: integer
- container: ''
  name: clicks
  type: integer
- container: ''
  name: subscriberCount
  type: integer
- container: ''
  name: sentDate
  type: dateTime
- container: ''
  name: scheduledBy
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: createdBy
  type: integer
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: updatedBy
  type: integer
- container: ''
  name: deletedAt
  type: dateTime
- container: ''
  name: siftApproved
  type: integer
- container: ''
  name: arcApproved
  type: integer
- container: ''
  name: quietHoursEnabled
  type: integer
- container: ''
  name: snapshot
  type: reference
- container: set
  name: metrics
  type: string
- container: ''
  name: smsCredits
  type: reference
- container: set
  name: recipients
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorSource
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: broadcastId
  type: integer
- container: set
  name: broadcasts
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: deliverability
  type: string
- container: ''
  name: optOut
  type: string
- container: ''
  name: details
  type: reference
property_count: 51
provider_name: ActiveCampaign
provider_slug: activecampaign
slug: activecampaign-sms-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"activecampaign\": \"https://developers.activecampaign.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BroadcastListsResponse\": \"activecampaign:BroadcastListsResponse\",\n    \"BroadcastUpdateRequest\": \"activecampaign:BroadcastUpdateRequest\",\n    \"AIBroadcastRequest\": \"activecampaign:AIBroadcastRequest\",\n    \"BroadcastMetrics\": \"activecampaign:BroadcastMetrics\",\n    \"BroadcastList\": \"activecampaign:BroadcastList\",\n    \"BroadcastMessage\": \"activecampaign:BroadcastMessage\",\n    \"SnapshotResponse\": \"activecampaign:SnapshotResponse\",\n    \"BroadcastCreateRequest\": \"activecampaign:BroadcastCreateRequest\",\n    \"BroadcastMetricsResponse\": \"activecampaign:BroadcastMetricsResponse\",\n    \"CreditsResponse\": \"activecampaign:CreditsResponse\",\n    \"RecipientsResponse\": \"activecampaign:RecipientsResponse\"\
  ,\n    \"FailureDetail\": \"activecampaign:FailureDetail\",\n    \"AIBroadcastUpdateRequest\": \"activecampaign:AIBroadcastUpdateRequest\",\n    \"AIBroadcastStatus\": \"activecampaign:AIBroadcastStatus\",\n    \"BroadcastListResponse\": \"activecampaign:BroadcastListResponse\",\n    \"AIBroadcastResponse\": \"activecampaign:AIBroadcastResponse\",\n    \"FailureDetailsResponse\": \"activecampaign:FailureDetailsResponse\",\n    \"Recipient\": \"activecampaign:Recipient\",\n    \"lists\": {\n      \"@id\": \"activecampaign:lists\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"activecampaign:meta\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressId\": {\n      \"@id\": \"activecampaign:address_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"body\": {\n      \"@id\": \"activecampaign:body\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"mediaUrls\": {\n      \"@id\": \"activecampaign:media_urls\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"previewUrl\": {\n      \"@id\": \"activecampaign:preview_url\",\n      \"@type\": \"@id\"\n    },\n    \"shortenTrackLinksEnabled\": {\n      \"@id\": \"activecampaign:shorten_track_links_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"activecampaign:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledDate\": {\n      \"@id\": \"activecampaign:scheduled_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sentToCount\": {\n      \"@id\": \"activecampaign:sent_to_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"listIds\": {\n      \"@id\": \"activecampaign:list_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"segmentId\": {\n      \"@id\": \"activecampaign:segment_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customRunId\":\
  \ {\n      \"@id\": \"activecampaign:custom_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customSegmentId\": {\n      \"@id\": \"activecampaign:custom_segment_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labelIds\": {\n      \"@id\": \"activecampaign:label_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"source\": {\n      \"@id\": \"activecampaign:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prompt\": {\n      \"@id\": \"activecampaign:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tone\": {\n      \"@id\": \"activecampaign:tone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"activecampaign:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sends\": {\n      \"@id\": \"activecampaign:sends\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deliveries\": {\n      \"@id\": \"activecampaign:deliveries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"replies\": {\n   \
  \   \"@id\": \"activecampaign:replies\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failures\": {\n      \"@id\": \"activecampaign:failures\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"optOuts\": {\n      \"@id\": \"activecampaign:optOuts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clicks\": {\n      \"@id\": \"activecampaign:clicks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subscriberCount\": {\n      \"@id\": \"activecampaign:subscriber_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sentDate\": {\n      \"@id\": \"activecampaign:sentDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scheduledBy\": {\n      \"@id\": \"activecampaign:scheduled_by\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"activecampaign:created_by\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updatedAt\": {\n      \"@id\"\
  : \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedBy\": {\n      \"@id\": \"activecampaign:updated_by\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deletedAt\": {\n      \"@id\": \"activecampaign:deleted_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"siftApproved\": {\n      \"@id\": \"activecampaign:sift_approved\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"arcApproved\": {\n      \"@id\": \"activecampaign:arc_approved\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quietHoursEnabled\": {\n      \"@id\": \"activecampaign:quiet_hours_enabled\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"snapshot\": {\n      \"@id\": \"activecampaign:snapshot\",\n      \"@type\": \"@id\"\n    },\n    \"metrics\": {\n      \"@id\": \"activecampaign:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"smsCredits\": {\n      \"@id\": \"activecampaign:smsCredits\",\n      \"@type\": \"@id\"\n    },\n   \
  \ \"recipients\": {\n      \"@id\": \"activecampaign:recipients\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"activecampaign:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorSource\": {\n      \"@id\": \"activecampaign:errorSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"activecampaign:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"broadcastId\": {\n      \"@id\": \"activecampaign:broadcastId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"broadcasts\": {\n      \"@id\": \"activecampaign:broadcasts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"activecampaign:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"activecampaign:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliverability\": {\n      \"@id\": \"activecampaign:deliverability\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"optOut\": {\n      \"@id\": \"activecampaign:optOut\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"activecampaign:details\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/json-ld/activecampaign-sms-context.jsonld
tags:
- Marketing Automation
- Email Marketing
- CRM
- Sales Automation
- Customer Experience
- JSON-LD
- Linked Data
- Semantic Web
---
