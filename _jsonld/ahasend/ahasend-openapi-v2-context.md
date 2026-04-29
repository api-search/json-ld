---
api_specs:
- filename: ahasend-openapi.yml
  format: yaml
  label: AhaSend
  slug: ahasend
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/openapi/ahasend-openapi.yml
class_count: 60
classes:
- PaginationInfo
- createdAt
- updatedAt
- APIKeyScope
- APIKey
- CreateAPIKeyRequest
- UpdateAPIKeyRequest
- PaginatedAPIKeysResponse
- DNSRecord
- Domain
- CreateDomainRequest
- UpdateDomainRequest
- PaginatedDomainsResponse
- email
- name
- Address
- Recipient
- Attachment
- Tracking
- Retention
- MessageSchedule
- CreateMessageRequest
- CreateConversationMessageRequest
- CreateSingleMessageResponse
- CreateMessageResponse
- DeliveryEvent
- MessageContentPart
- MessageAttachment
- MessageContentParsed
- MessageSummary
- PaginatedMessagesResponse
- Account
- UpdateAccountRequest
- UserAccount
- AccountMembersResponse
- AddMemberRequest
- Suppression
- CreateSuppressionResponse
- CreateSuppressionRequest
- PaginatedSuppressionsResponse
- url
- Route
- CreateRouteRequest
- UpdateRouteRequest
- PaginatedRoutesResponse
- Webhook
- CreateWebhookRequest
- UpdateWebhookRequest
- PaginatedWebhooksResponse
- SMTPCredential
- CreateSMTPCredentialRequest
- PaginatedSMTPCredentialsResponse
- DeliverabilityStatistics
- DeliverabilityStatisticsResponse
- Bounce
- BounceStatistics
- BounceStatisticsResponse
- DeliveryTimeStatistics
- DeliveryTime
- DeliveryTimeStatisticsResponse
context_file: json-ld/ahasend-openapi-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/json-ld/ahasend-openapi-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ahasend Openapi V2 from AhaSend.
layout: jsonld
name: Ahasend Openapi V2 Context
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
  name: hasMore
  type: boolean
- container: ''
  name: nextCursor
  type: string
- container: ''
  name: previousCursor
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: apiKeyId
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: domainId
  type: string
- container: ''
  name: object
  type: string
- container: ''
  name: lastUsedAt
  type: dateTime
- container: ''
  name: accountId
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: publicKey
  type: string
- container: ''
  name: secretKey
  type: string
- container: set
  name: scopes
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: pagination
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: required
  type: boolean
- container: ''
  name: propagated
  type: boolean
- container: ''
  name: domain
  type: string
- container: set
  name: dnsRecords
  type: string
- container: ''
  name: lastDnsCheckAt
  type: dateTime
- container: ''
  name: dnsValid
  type: boolean
- container: ''
  name: trackingSubdomain
  type: string
- container: ''
  name: returnPathSubdomain
  type: string
- container: ''
  name: subscriptionSubdomain
  type: string
- container: ''
  name: mediaSubdomain
  type: string
- container: ''
  name: dkimRotationIntervalDays
  type: integer
- container: ''
  name: rotationReady
  type: boolean
- container: ''
  name: dkimPrivateKey
  type: string
- container: ''
  name: substitutions
  type: reference
- container: ''
  name: base64
  type: boolean
- container: ''
  name: contentType
  type: string
- container: ''
  name: contentDisposition
  type: string
- container: ''
  name: contentId
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: open
  type: boolean
- container: ''
  name: click
  type: boolean
- container: ''
  name: metadata
  type: integer
- container: ''
  name: firstAttempt
  type: dateTime
- container: ''
  name: expires
  type: dateTime
- container: ''
  name: from
  type: string
- container: set
  name: recipients
  type: string
- container: ''
  name: replyTo
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: textContent
  type: string
- container: ''
  name: htmlContent
  type: string
- container: ''
  name: ampContent
  type: string
- container: set
  name: attachments
  type: string
- container: ''
  name: headers
  type: reference
- container: set
  name: tags
  type: string
- container: ''
  name: sandbox
  type: boolean
- container: ''
  name: sandboxResult
  type: string
- container: ''
  name: tracking
  type: string
- container: ''
  name: retention
  type: string
- container: ''
  name: schedule
  type: string
- container: set
  name: to
  type: string
- container: set
  name: cc
  type: string
- container: set
  name: bcc
  type: string
- container: ''
  name: recipient
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: time
  type: dateTime
- container: ''
  name: log
  type: string
- container: ''
  name: filename
  type: string
- container: set
  name: parts
  type: string
- container: ''
  name: sentAt
  type: dateTime
- container: ''
  name: deliveredAt
  type: dateTime
- container: ''
  name: retainUntil
  type: dateTime
- container: ''
  name: direction
  type: string
- container: ''
  name: isBounceNotification
  type: boolean
- container: ''
  name: bounceClassification
  type: string
- container: set
  name: deliveryAttempts
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: sender
  type: string
- container: ''
  name: numAttempts
  type: integer
- container: ''
  name: clickCount
  type: integer
- container: ''
  name: openCount
  type: integer
- container: ''
  name: referenceMessageId
  type: integer
- container: ''
  name: website
  type: reference
- container: ''
  name: about
  type: string
- container: ''
  name: trackOpens
  type: boolean
- container: ''
  name: trackClicks
  type: boolean
- container: ''
  name: rejectBadRecipients
  type: boolean
- container: ''
  name: rejectMistypedRecipients
  type: boolean
- container: ''
  name: messageMetadataRetention
  type: integer
- container: ''
  name: messageDataRetention
  type: integer
- container: ''
  name: userId
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: groupByMessageId
  type: boolean
- container: ''
  name: stripReplies
  type: boolean
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: successCount
  type: integer
- container: ''
  name: errorCount
  type: integer
- container: ''
  name: errorsSinceLastSuccess
  type: integer
- container: ''
  name: lastRequestAt
  type: dateTime
- container: ''
  name: onReception
  type: boolean
- container: ''
  name: onDelivered
  type: boolean
- container: ''
  name: onTransientError
  type: boolean
- container: ''
  name: onFailed
  type: boolean
- container: ''
  name: onBounced
  type: boolean
- container: ''
  name: onSuppressed
  type: boolean
- container: ''
  name: onOpened
  type: boolean
- container: ''
  name: onClicked
  type: boolean
- container: ''
  name: onSuppressionCreated
  type: boolean
- container: ''
  name: onDnsError
  type: boolean
- container: set
  name: domains
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: fromTimestamp
  type: dateTime
- container: ''
  name: toTimestamp
  type: dateTime
- container: ''
  name: receptionCount
  type: integer
- container: ''
  name: deliveredCount
  type: integer
- container: ''
  name: deferredCount
  type: integer
- container: ''
  name: bouncedCount
  type: integer
- container: ''
  name: failedCount
  type: integer
- container: ''
  name: suppressedCount
  type: integer
- container: ''
  name: openedCount
  type: integer
- container: ''
  name: clickedCount
  type: integer
- container: ''
  name: classification
  type: string
- container: ''
  name: count
  type: integer
- container: set
  name: bounces
  type: string
- container: ''
  name: avgDeliveryTime
  type: decimal
- container: set
  name: deliveryTimes
  type: string
- container: ''
  name: recipientDomain
  type: string
- container: ''
  name: deliveryTime
  type: decimal
property_count: 129
provider_name: AhaSend
provider_slug: ahasend
slug: ahasend-openapi-v2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ahasend\": \"https://ahasend.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"hasMore\": {\n      \"@id\": \"ahasend:has_more\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nextCursor\": {\n      \"@id\": \"ahasend:next_cursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousCursor\": {\n      \"@id\": \"ahasend:previous_cursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaginationInfo\": \"ahasend:PaginationInfo\",\n    \"id\": {\n      \"@id\": \"ahasend:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"apiKeyId\": {\n      \"@id\": \"ahasend:api_key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"ahasend:scope\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"domainId\": {\n      \"@id\": \"ahasend:domain_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APIKeyScope\": \"ahasend:APIKeyScope\",\n    \"object\": {\n      \"@id\": \"ahasend:object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUsedAt\": {\n      \"@id\": \"ahasend:last_used_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"accountId\": {\n      \"@id\": \"ahasend:account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"ahasend:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKey\": {\n      \"@id\": \"ahasend:public_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretKey\": {\n      \"@id\": \"ahasend:secret_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scopes\": {\n      \"@id\": \"ahasend:scopes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APIKey\": \"ahasend:APIKey\",\n    \"CreateAPIKeyRequest\": \"ahasend:CreateAPIKeyRequest\",\n    \"UpdateAPIKeyRequest\"\
  : \"ahasend:UpdateAPIKeyRequest\",\n    \"data\": {\n      \"@id\": \"ahasend:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagination\": {\n      \"@id\": \"ahasend:pagination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaginatedAPIKeysResponse\": \"ahasend:PaginatedAPIKeysResponse\",\n    \"type\": {\n      \"@id\": \"ahasend:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"ahasend:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"ahasend:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"ahasend:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"propagated\": {\n      \"@id\": \"ahasend:propagated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DNSRecord\": \"ahasend:DNSRecord\",\n    \"domain\": {\n      \"@id\": \"ahasend:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsRecords\": {\n      \"@id\"\
  : \"ahasend:dns_records\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastDnsCheckAt\": {\n      \"@id\": \"ahasend:last_dns_check_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dnsValid\": {\n      \"@id\": \"ahasend:dns_valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"trackingSubdomain\": {\n      \"@id\": \"ahasend:tracking_subdomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnPathSubdomain\": {\n      \"@id\": \"ahasend:return_path_subdomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionSubdomain\": {\n      \"@id\": \"ahasend:subscription_subdomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaSubdomain\": {\n      \"@id\": \"ahasend:media_subdomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dkimRotationIntervalDays\": {\n      \"@id\": \"ahasend:dkim_rotation_interval_days\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rotationReady\": {\n      \"@id\": \"ahasend:rotation_ready\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Domain\": \"ahasend:Domain\",\n    \"dkimPrivateKey\": {\n      \"@id\": \"ahasend:dkim_private_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateDomainRequest\": \"ahasend:CreateDomainRequest\",\n    \"UpdateDomainRequest\": \"ahasend:UpdateDomainRequest\",\n    \"PaginatedDomainsResponse\": \"ahasend:PaginatedDomainsResponse\",\n    \"email\": \"schema:email\",\n    \"name\": \"schema:name\",\n    \"Address\": \"ahasend:Address\",\n    \"substitutions\": {\n      \"@id\": \"ahasend:substitutions\",\n      \"@type\": \"@id\"\n    },\n    \"Recipient\": \"ahasend:Recipient\",\n    \"base64\": {\n      \"@id\": \"ahasend:base64\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"contentType\": {\n      \"@id\": \"ahasend:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentDisposition\": {\n      \"@id\": \"ahasend:content_disposition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentId\": {\n      \"\
  @id\": \"ahasend:content_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"ahasend:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attachment\": \"ahasend:Attachment\",\n    \"open\": {\n      \"@id\": \"ahasend:open\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"click\": {\n      \"@id\": \"ahasend:click\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Tracking\": \"ahasend:Tracking\",\n    \"metadata\": {\n      \"@id\": \"ahasend:metadata\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Retention\": \"ahasend:Retention\",\n    \"firstAttempt\": {\n      \"@id\": \"ahasend:first_attempt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expires\": {\n      \"@id\": \"ahasend:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"MessageSchedule\": \"ahasend:MessageSchedule\",\n    \"from\": {\n      \"@id\": \"ahasend:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipients\": {\n      \"@id\": \"ahasend:recipients\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replyTo\": {\n      \"@id\": \"ahasend:reply_to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"ahasend:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"textContent\": {\n      \"@id\": \"ahasend:text_content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htmlContent\": {\n      \"@id\": \"ahasend:html_content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ampContent\": {\n      \"@id\": \"ahasend:amp_content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachments\": {\n      \"@id\": \"ahasend:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"ahasend:headers\",\n      \"@type\": \"@id\"\n    },\n    \"CreateMessageRequest\": \"ahasend:CreateMessageRequest\",\n    \"tags\": {\n      \"@id\": \"ahasend:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"sandbox\": {\n      \"@id\": \"ahasend:sandbox\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sandboxResult\": {\n      \"@id\": \"ahasend:sandbox_result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tracking\": {\n      \"@id\": \"ahasend:tracking\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retention\": {\n      \"@id\": \"ahasend:retention\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"ahasend:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"ahasend:to\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cc\": {\n      \"@id\": \"ahasend:cc\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bcc\": {\n      \"@id\": \"ahasend:bcc\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateConversationMessageRequest\": \"ahasend:CreateConversationMessageRequest\",\n    \"recipient\": {\n \
  \     \"@id\": \"ahasend:recipient\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"ahasend:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"ahasend:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateSingleMessageResponse\": \"ahasend:CreateSingleMessageResponse\",\n    \"CreateMessageResponse\": \"ahasend:CreateMessageResponse\",\n    \"time\": {\n      \"@id\": \"ahasend:time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"log\": {\n      \"@id\": \"ahasend:log\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeliveryEvent\": \"ahasend:DeliveryEvent\",\n    \"MessageContentPart\": \"ahasend:MessageContentPart\",\n    \"filename\": {\n      \"@id\": \"ahasend:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageAttachment\": \"ahasend:MessageAttachment\",\n    \"parts\": {\n      \"@id\": \"ahasend:parts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"MessageContentParsed\": \"ahasend:MessageContentParsed\",\n    \"sentAt\": {\n      \"@id\": \"ahasend:sent_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveredAt\": {\n      \"@id\": \"ahasend:delivered_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"retainUntil\": {\n      \"@id\": \"ahasend:retain_until\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"direction\": {\n      \"@id\": \"ahasend:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isBounceNotification\": {\n      \"@id\": \"ahasend:is_bounce_notification\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"bounceClassification\": {\n      \"@id\": \"ahasend:bounce_classification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryAttempts\": {\n      \"@id\": \"ahasend:delivery_attempts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"ahasend:message_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sender\"\
  : {\n      \"@id\": \"ahasend:sender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numAttempts\": {\n      \"@id\": \"ahasend:num_attempts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clickCount\": {\n      \"@id\": \"ahasend:click_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"openCount\": {\n      \"@id\": \"ahasend:open_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"referenceMessageId\": {\n      \"@id\": \"ahasend:reference_message_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MessageSummary\": \"ahasend:MessageSummary\",\n    \"PaginatedMessagesResponse\": \"ahasend:PaginatedMessagesResponse\",\n    \"website\": {\n      \"@id\": \"ahasend:website\",\n      \"@type\": \"@id\"\n    },\n    \"about\": {\n      \"@id\": \"ahasend:about\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackOpens\": {\n      \"@id\": \"ahasend:track_opens\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"trackClicks\": {\n      \"@id\": \"ahasend:track_clicks\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rejectBadRecipients\": {\n      \"@id\": \"ahasend:reject_bad_recipients\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rejectMistypedRecipients\": {\n      \"@id\": \"ahasend:reject_mistyped_recipients\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"messageMetadataRetention\": {\n      \"@id\": \"ahasend:message_metadata_retention\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"messageDataRetention\": {\n      \"@id\": \"ahasend:message_data_retention\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Account\": \"ahasend:Account\",\n    \"UpdateAccountRequest\": \"ahasend:UpdateAccountRequest\",\n    \"userId\": {\n      \"@id\": \"ahasend:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"ahasend:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserAccount\": \"ahasend:UserAccount\",\n    \"AccountMembersResponse\": \"ahasend:AccountMembersResponse\",\n    \"AddMemberRequest\"\
  : \"ahasend:AddMemberRequest\",\n    \"reason\": {\n      \"@id\": \"ahasend:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"ahasend:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Suppression\": \"ahasend:Suppression\",\n    \"CreateSuppressionResponse\": \"ahasend:CreateSuppressionResponse\",\n    \"CreateSuppressionRequest\": \"ahasend:CreateSuppressionRequest\",\n    \"PaginatedSuppressionsResponse\": \"ahasend:PaginatedSuppressionsResponse\",\n    \"url\": \"schema:url\",\n    \"groupByMessageId\": {\n      \"@id\": \"ahasend:group_by_message_id\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stripReplies\": {\n      \"@id\": \"ahasend:strip_replies\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabled\": {\n      \"@id\": \"ahasend:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"successCount\": {\n      \"@id\": \"ahasend:success_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorCount\"\
  : {\n      \"@id\": \"ahasend:error_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorsSinceLastSuccess\": {\n      \"@id\": \"ahasend:errors_since_last_success\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastRequestAt\": {\n      \"@id\": \"ahasend:last_request_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Route\": \"ahasend:Route\",\n    \"CreateRouteRequest\": \"ahasend:CreateRouteRequest\",\n    \"UpdateRouteRequest\": \"ahasend:UpdateRouteRequest\",\n    \"PaginatedRoutesResponse\": \"ahasend:PaginatedRoutesResponse\",\n    \"onReception\": {\n      \"@id\": \"ahasend:on_reception\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onDelivered\": {\n      \"@id\": \"ahasend:on_delivered\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onTransientError\": {\n      \"@id\": \"ahasend:on_transient_error\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onFailed\": {\n      \"@id\": \"ahasend:on_failed\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"onBounced\": {\n      \"@id\": \"ahasend:on_bounced\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onSuppressed\": {\n      \"@id\": \"ahasend:on_suppressed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onOpened\": {\n      \"@id\": \"ahasend:on_opened\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onClicked\": {\n      \"@id\": \"ahasend:on_clicked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onSuppressionCreated\": {\n      \"@id\": \"ahasend:on_suppression_created\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onDnsError\": {\n      \"@id\": \"ahasend:on_dns_error\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"domains\": {\n      \"@id\": \"ahasend:domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Webhook\": \"ahasend:Webhook\",\n    \"CreateWebhookRequest\": \"ahasend:CreateWebhookRequest\",\n    \"UpdateWebhookRequest\": \"ahasend:UpdateWebhookRequest\",\n    \"PaginatedWebhooksResponse\": \"ahasend:PaginatedWebhooksResponse\"\
  ,\n    \"username\": {\n      \"@id\": \"ahasend:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMTPCredential\": \"ahasend:SMTPCredential\",\n    \"CreateSMTPCredentialRequest\": \"ahasend:CreateSMTPCredentialRequest\",\n    \"PaginatedSMTPCredentialsResponse\": \"ahasend:PaginatedSMTPCredentialsResponse\",\n    \"fromTimestamp\": {\n      \"@id\": \"ahasend:from_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"toTimestamp\": {\n      \"@id\": \"ahasend:to_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"receptionCount\": {\n      \"@id\": \"ahasend:reception_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deliveredCount\": {\n      \"@id\": \"ahasend:delivered_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deferredCount\": {\n      \"@id\": \"ahasend:deferred_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bouncedCount\": {\n      \"@id\": \"ahasend:bounced_count\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"failedCount\": {\n      \"@id\": \"ahasend:failed_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"suppressedCount\": {\n      \"@id\": \"ahasend:suppressed_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"openedCount\": {\n      \"@id\": \"ahasend:opened_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clickedCount\": {\n      \"@id\": \"ahasend:clicked_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DeliverabilityStatistics\": \"ahasend:DeliverabilityStatistics\",\n    \"DeliverabilityStatisticsResponse\": \"ahasend:DeliverabilityStatisticsResponse\",\n    \"classification\": {\n      \"@id\": \"ahasend:classification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"ahasend:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Bounce\": \"ahasend:Bounce\",\n    \"bounces\": {\n      \"@id\": \"ahasend:bounces\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BounceStatistics\"\
  : \"ahasend:BounceStatistics\",\n    \"BounceStatisticsResponse\": \"ahasend:BounceStatisticsResponse\",\n    \"avgDeliveryTime\": {\n      \"@id\": \"ahasend:avg_delivery_time\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deliveryTimes\": {\n      \"@id\": \"ahasend:delivery_times\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeliveryTimeStatistics\": \"ahasend:DeliveryTimeStatistics\",\n    \"recipientDomain\": {\n      \"@id\": \"ahasend:recipient_domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryTime\": {\n      \"@id\": \"ahasend:delivery_time\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"DeliveryTime\": \"ahasend:DeliveryTime\",\n    \"DeliveryTimeStatisticsResponse\": \"ahasend:DeliveryTimeStatisticsResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/json-ld/ahasend-openapi-v2-context.jsonld
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
