---
api_specs:
- filename: bandwidth-voice-api-openapi.yml
  format: yaml
  label: Bandwidth Voice API
  slug: voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-voice-api-openapi.yml
- filename: bandwidth-messaging-api-openapi.yml
  format: yaml
  label: Bandwidth Messaging API
  slug: messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-messaging-api-openapi.yml
- filename: bandwidth-phone-numbers-api-openapi.yml
  format: yaml
  label: Bandwidth Phone Numbers API
  slug: phone-numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-phone-numbers-api-openapi.yml
- filename: bandwidth-mfa-api-openapi.yml
  format: yaml
  label: Bandwidth Multi-Factor Authentication API
  slug: multi-factor-authentication-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-mfa-api-openapi.yml
- filename: bandwidth-emergency-calling-api-openapi.yml
  format: yaml
  label: Bandwidth Emergency Calling API
  slug: emergency-calling-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-emergency-calling-api-openapi.yml
- filename: bandwidth-toll-free-verification-api-openapi.yml
  format: yaml
  label: Bandwidth Toll-Free Verification API
  slug: toll-free-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-toll-free-verification-api-openapi.yml
class_count: 51
classes:
- Address
- AvailableNumber
- AvailableNumbersResponse
- Bandwidth Call
- Bandwidth Message
- Bandwidth Phone Number
- Call
- Conference
- ConferenceMember
- CreateCallRequest
- CreateMessageRequest
- DisconnectRequest
- DisconnectResponse
- Endpoint
- EndpointListResponse
- Error
- FeatureOrderRequest
- Location
- LocationListResponse
- Media
- Message
- MessageList
- MfaMessagingRequest
- MfaMessagingResponse
- MfaVerifyRequest
- MfaVerifyResponse
- MfaVoiceRequest
- MfaVoiceResponse
- NotificationRecipient
- NotificationRecipientListResponse
- OrderListResponse
- OrderRequest
- OrderResponse
- PhoneNumber
- PhoneNumberListResponse
- PortInListResponse
- PortInRequest
- PortInResponse
- Recording
- SipPeer
- SipPeerListResponse
- Site
- SiteListResponse
- Transcription
- TranscriptionRequest
- UpdateCallRequest
- UpdateConferenceMemberRequest
- UpdateConferenceRequest
- Verification
- VerificationListResponse
- VerificationRequest
context_file: json-ld/bandwidth-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/json-ld/bandwidth-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bandwidth from Bandwidth.
layout: jsonld
name: Bandwidth Context
namespaces:
- prefix: bandwidth
  uri: https://dev.bandwidth.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountId
  type: string
- container: ''
  name: activated
  type: boolean
- container: set
  name: activeMembers
  type: string
- container: ''
  name: actualFocDate
  type: string
- container: ''
  name: additionalInformation
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: alternateEndUserId
  type: string
- container: ''
  name: answerFallbackMethod
  type: string
- container: ''
  name: answerFallbackUrl
  type: reference
- container: ''
  name: answerMethod
  type: string
- container: ''
  name: answerTime
  type: dateTime
- container: ''
  name: answerUrl
  type: reference
- container: ''
  name: applicationId
  type: string
- container: ''
  name: billingTelephoneNumber
  type: string
- container: ''
  name: businessContact
  type: string
- container: ''
  name: businessName
  type: string
- container: ''
  name: businessWebsite
  type: reference
- container: ''
  name: callId
  type: string
- container: set
  name: callIdsToCoach
  type: string
- container: ''
  name: callTimeout
  type: decimal
- container: ''
  name: callUrl
  type: reference
- container: ''
  name: callbackMethod
  type: string
- container: ''
  name: callbackTimeout
  type: decimal
- container: ''
  name: callbackUrl
  type: reference
- container: ''
  name: callerName
  type: string
- container: ''
  name: callingNameDisplay
  type: string
- container: ''
  name: channels
  type: integer
- container: ''
  name: city
  type: string
- container: ''
  name: code
  type: string
- container: set
  name: completedNumbers
  type: string
- container: ''
  name: completedQuantity
  type: integer
- container: ''
  name: completedTime
  type: dateTime
- container: ''
  name: conferenceId
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: contentLength
  type: integer
- container: ''
  name: contentType
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: denialReason
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: digits
  type: integer
- container: ''
  name: direction
  type: string
- container: ''
  name: directoryListing
  type: string
- container: ''
  name: disconnectCause
  type: string
- container: ''
  name: disconnectMethod
  type: string
- container: ''
  name: disconnectTelephoneNumberOrderType
  type: string
- container: ''
  name: disconnectUrl
  type: reference
- container: ''
  name: duration
  type: string
- container: ''
  name: emailAddress
  type: string
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: endpointId
  type: string
- container: set
  name: endpoints
  type: string
- container: ''
  name: existingTelephoneNumberOrderType
  type: string
- container: ''
  name: expiration
  type: dateTime
- container: ''
  name: expirationTimeInMinutes
  type: decimal
- container: ''
  name: failedQuantity
  type: integer
- container: ''
  name: features
  type: string
- container: set
  name: fieldErrors
  type: string
- container: ''
  name: fileFormat
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: fullNumber
  type: string
- container: ''
  name: hold
  type: boolean
- container: ''
  name: houseNumber
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: isDefaultPeer
  type: boolean
- container: ''
  name: lata
  type: string
- container: ''
  name: latitude
  type: decimal
- container: set
  name: listOfPhoneNumbers
  type: string
- container: ''
  name: locationId
  type: string
- container: set
  name: locations
  type: string
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: losingCarrierName
  type: string
- container: set
  name: media
  type: string
- container: ''
  name: mediaName
  type: string
- container: ''
  name: mediaUrl
  type: reference
- container: ''
  name: memberUrl
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: messageContent
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: messageVolume
  type: string
- container: set
  name: messages
  type: string
- container: ''
  name: mute
  type: boolean
- container: ''
  name: name
  type: ''
- container: set
  name: notificationRecipients
  type: string
- container: ''
  name: optInWorkflow
  type: string
- container: set
  name: optInWorkflowImageUrls
  type: string
- container: ''
  name: orderCreateDate
  type: dateTime
- container: ''
  name: orderId
  type: string
- container: ''
  name: orderStatus
  type: string
- container: set
  name: orders
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: pageInfo
  type: string
- container: ''
  name: peerId
  type: string
- container: ''
  name: peerName
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: portInId
  type: string
- container: set
  name: portIns
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: rateCenter
  type: string
- container: ''
  name: recordingId
  type: string
- container: ''
  name: redirectFallbackMethod
  type: string
- container: ''
  name: redirectFallbackUrl
  type: reference
- container: ''
  name: redirectMethod
  type: string
- container: ''
  name: redirectUrl
  type: reference
- container: ''
  name: requestedFocDate
  type: string
- container: ''
  name: resultCount
  type: integer
- container: ''
  name: scope
  type: string
- container: ''
  name: segmentCount
  type: integer
- container: ''
  name: sipPeerId
  type: string
- container: set
  name: sipPeers
  type: string
- container: ''
  name: siteId
  type: string
- container: set
  name: sites
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: state
  type: string
- container: ''
  name: stateCode
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: streetName
  type: string
- container: ''
  name: submissionDate
  type: dateTime
- container: ''
  name: subscriber
  type: string
- container: ''
  name: tag
  type: string
- container: ''
  name: telephoneNumber
  type: string
- container: set
  name: telephoneNumberList
  type: string
- container: set
  name: telephoneNumbers
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: time
  type: dateTime
- container: ''
  name: to
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: transcription
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: useCase
  type: string
- container: ''
  name: useCaseSummary
  type: string
- container: ''
  name: valid
  type: boolean
- container: ''
  name: verificationDate
  type: dateTime
- container: ''
  name: verificationId
  type: string
- container: set
  name: verifications
  type: string
- container: ''
  name: zip
  type: string
property_count: 137
provider_name: Bandwidth
provider_slug: bandwidth
slug: bandwidth-context
source_filename: bandwidth-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bandwidth\": \"https://dev.bandwidth.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"bandwidth:Address\",\n    \"AvailableNumber\": \"bandwidth:AvailableNumber\",\n    \"AvailableNumbersResponse\": \"bandwidth:AvailableNumbersResponse\",\n    \"Bandwidth Call\": \"bandwidth:Bandwidth Call\",\n    \"Bandwidth Message\": \"bandwidth:Bandwidth Message\",\n    \"Bandwidth Phone Number\": \"bandwidth:Bandwidth Phone Number\",\n    \"Call\": \"bandwidth:Call\",\n    \"Conference\": \"bandwidth:Conference\",\n    \"ConferenceMember\": \"bandwidth:ConferenceMember\",\n    \"CreateCallRequest\": \"bandwidth:CreateCallRequest\",\n    \"CreateMessageRequest\": \"bandwidth:CreateMessageRequest\",\n    \"DisconnectRequest\": \"bandwidth:DisconnectRequest\",\n    \"DisconnectResponse\": \"bandwidth:DisconnectResponse\",\n    \"Endpoint\": \"bandwidth:Endpoint\"\
  ,\n    \"EndpointListResponse\": \"bandwidth:EndpointListResponse\",\n    \"Error\": \"bandwidth:Error\",\n    \"FeatureOrderRequest\": \"bandwidth:FeatureOrderRequest\",\n    \"Location\": \"bandwidth:Location\",\n    \"LocationListResponse\": \"bandwidth:LocationListResponse\",\n    \"Media\": \"bandwidth:Media\",\n    \"Message\": \"bandwidth:Message\",\n    \"MessageList\": \"bandwidth:MessageList\",\n    \"MfaMessagingRequest\": \"bandwidth:MfaMessagingRequest\",\n    \"MfaMessagingResponse\": \"bandwidth:MfaMessagingResponse\",\n    \"MfaVerifyRequest\": \"bandwidth:MfaVerifyRequest\",\n    \"MfaVerifyResponse\": \"bandwidth:MfaVerifyResponse\",\n    \"MfaVoiceRequest\": \"bandwidth:MfaVoiceRequest\",\n    \"MfaVoiceResponse\": \"bandwidth:MfaVoiceResponse\",\n    \"NotificationRecipient\": \"bandwidth:NotificationRecipient\",\n    \"NotificationRecipientListResponse\": \"bandwidth:NotificationRecipientListResponse\",\n    \"OrderListResponse\": \"bandwidth:OrderListResponse\",\n\
  \    \"OrderRequest\": \"bandwidth:OrderRequest\",\n    \"OrderResponse\": \"bandwidth:OrderResponse\",\n    \"PhoneNumber\": \"bandwidth:PhoneNumber\",\n    \"PhoneNumberListResponse\": \"bandwidth:PhoneNumberListResponse\",\n    \"PortInListResponse\": \"bandwidth:PortInListResponse\",\n    \"PortInRequest\": \"bandwidth:PortInRequest\",\n    \"PortInResponse\": \"bandwidth:PortInResponse\",\n    \"Recording\": \"bandwidth:Recording\",\n    \"SipPeer\": \"bandwidth:SipPeer\",\n    \"SipPeerListResponse\": \"bandwidth:SipPeerListResponse\",\n    \"Site\": \"bandwidth:Site\",\n    \"SiteListResponse\": \"bandwidth:SiteListResponse\",\n    \"Transcription\": \"bandwidth:Transcription\",\n    \"TranscriptionRequest\": \"bandwidth:TranscriptionRequest\",\n    \"UpdateCallRequest\": \"bandwidth:UpdateCallRequest\",\n    \"UpdateConferenceMemberRequest\": \"bandwidth:UpdateConferenceMemberRequest\",\n    \"UpdateConferenceRequest\": \"bandwidth:UpdateConferenceRequest\",\n    \"Verification\"\
  : \"bandwidth:Verification\",\n    \"VerificationListResponse\": \"bandwidth:VerificationListResponse\",\n    \"VerificationRequest\": \"bandwidth:VerificationRequest\",\n    \"accountId\": {\n      \"@id\": \"bandwidth:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activated\": {\n      \"@id\": \"bandwidth:activated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"activeMembers\": {\n      \"@id\": \"bandwidth:activeMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actualFocDate\": {\n      \"@id\": \"bandwidth:actualFocDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalInformation\": {\n      \"@id\": \"bandwidth:additionalInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"bandwidth:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alternateEndUserId\": {\n      \"@id\": \"bandwidth:alternateEndUserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"answerFallbackMethod\"\
  : {\n      \"@id\": \"bandwidth:answerFallbackMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"answerFallbackUrl\": {\n      \"@id\": \"bandwidth:answerFallbackUrl\",\n      \"@type\": \"@id\"\n    },\n    \"answerMethod\": {\n      \"@id\": \"bandwidth:answerMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"answerTime\": {\n      \"@id\": \"bandwidth:answerTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"answerUrl\": {\n      \"@id\": \"bandwidth:answerUrl\",\n      \"@type\": \"@id\"\n    },\n    \"applicationId\": {\n      \"@id\": \"bandwidth:applicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingTelephoneNumber\": {\n      \"@id\": \"bandwidth:billingTelephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessContact\": {\n      \"@id\": \"bandwidth:businessContact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessName\": {\n      \"@id\": \"bandwidth:businessName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  businessWebsite\": {\n      \"@id\": \"bandwidth:businessWebsite\",\n      \"@type\": \"@id\"\n    },\n    \"callId\": {\n      \"@id\": \"bandwidth:callId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callIdsToCoach\": {\n      \"@id\": \"bandwidth:callIdsToCoach\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callTimeout\": {\n      \"@id\": \"bandwidth:callTimeout\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"callUrl\": {\n      \"@id\": \"bandwidth:callUrl\",\n      \"@type\": \"@id\"\n    },\n    \"callbackMethod\": {\n      \"@id\": \"bandwidth:callbackMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callbackTimeout\": {\n      \"@id\": \"bandwidth:callbackTimeout\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"callbackUrl\": {\n      \"@id\": \"bandwidth:callbackUrl\",\n      \"@type\": \"@id\"\n    },\n    \"callerName\": {\n      \"@id\": \"bandwidth:callerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callingNameDisplay\"\
  : {\n      \"@id\": \"bandwidth:callingNameDisplay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channels\": {\n      \"@id\": \"bandwidth:channels\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"city\": {\n      \"@id\": \"bandwidth:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"bandwidth:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedNumbers\": {\n      \"@id\": \"bandwidth:completedNumbers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedQuantity\": {\n      \"@id\": \"bandwidth:completedQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"completedTime\": {\n      \"@id\": \"bandwidth:completedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"conferenceId\": {\n      \"@id\": \"bandwidth:conferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"bandwidth:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentLength\"\
  : {\n      \"@id\": \"bandwidth:contentLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contentType\": {\n      \"@id\": \"bandwidth:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"bandwidth:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"bandwidth:createdTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"denialReason\": {\n      \"@id\": \"bandwidth:denialReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"digits\": {\n      \"@id\": \"bandwidth:digits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"direction\": {\n      \"@id\": \"bandwidth:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directoryListing\": {\n      \"@id\": \"bandwidth:directoryListing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disconnectCause\": {\n      \"@id\": \"bandwidth:disconnectCause\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"disconnectMethod\": {\n      \"@id\": \"bandwidth:disconnectMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disconnectTelephoneNumberOrderType\": {\n      \"@id\": \"bandwidth:disconnectTelephoneNumberOrderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disconnectUrl\": {\n      \"@id\": \"bandwidth:disconnectUrl\",\n      \"@type\": \"@id\"\n    },\n    \"duration\": {\n      \"@id\": \"bandwidth:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailAddress\": {\n      \"@id\": \"bandwidth:emailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"bandwidth:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endpointId\": {\n      \"@id\": \"bandwidth:endpointId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoints\": {\n      \"@id\": \"bandwidth:endpoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"existingTelephoneNumberOrderType\"\
  : {\n      \"@id\": \"bandwidth:existingTelephoneNumberOrderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"bandwidth:expiration\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expirationTimeInMinutes\": {\n      \"@id\": \"bandwidth:expirationTimeInMinutes\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"failedQuantity\": {\n      \"@id\": \"bandwidth:failedQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"features\": {\n      \"@id\": \"bandwidth:features\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldErrors\": {\n      \"@id\": \"bandwidth:fieldErrors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileFormat\": {\n      \"@id\": \"bandwidth:fileFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"bandwidth:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullNumber\": {\n      \"@id\": \"bandwidth:fullNumber\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"hold\": {\n      \"@id\": \"bandwidth:hold\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"houseNumber\": {\n      \"@id\": \"bandwidth:houseNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"bandwidth:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDefaultPeer\": {\n      \"@id\": \"bandwidth:isDefaultPeer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lata\": {\n      \"@id\": \"bandwidth:lata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"bandwidth:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"listOfPhoneNumbers\": {\n      \"@id\": \"bandwidth:listOfPhoneNumbers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationId\": {\n      \"@id\": \"bandwidth:locationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"bandwidth:locations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"longitude\": {\n      \"@id\": \"bandwidth:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"losingCarrierName\": {\n      \"@id\": \"bandwidth:losingCarrierName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"media\": {\n      \"@id\": \"bandwidth:media\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaName\": {\n      \"@id\": \"bandwidth:mediaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaUrl\": {\n      \"@id\": \"bandwidth:mediaUrl\",\n      \"@type\": \"@id\"\n    },\n    \"memberUrl\": {\n      \"@id\": \"bandwidth:memberUrl\",\n      \"@type\": \"@id\"\n    },\n    \"message\": {\n      \"@id\": \"bandwidth:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageContent\": {\n      \"@id\": \"bandwidth:messageContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"bandwidth:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageVolume\"\
  : {\n      \"@id\": \"bandwidth:messageVolume\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"bandwidth:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mute\": {\n      \"@id\": \"bandwidth:mute\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"notificationRecipients\": {\n      \"@id\": \"bandwidth:notificationRecipients\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"optInWorkflow\": {\n      \"@id\": \"bandwidth:optInWorkflow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"optInWorkflowImageUrls\": {\n      \"@id\": \"bandwidth:optInWorkflowImageUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderCreateDate\": {\n      \"@id\": \"bandwidth:orderCreateDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"orderId\": {\n      \"@id\": \"bandwidth:orderId\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"bandwidth:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orders\": {\n      \"@id\": \"bandwidth:orders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"bandwidth:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageInfo\": {\n      \"@id\": \"bandwidth:pageInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peerId\": {\n      \"@id\": \"bandwidth:peerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peerName\": {\n      \"@id\": \"bandwidth:peerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"bandwidth:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portInId\": {\n      \"@id\": \"bandwidth:portInId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portIns\": {\n      \"@id\": \"bandwidth:portIns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"priority\": {\n      \"@id\": \"bandwidth:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateCenter\": {\n      \"@id\": \"bandwidth:rateCenter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingId\": {\n      \"@id\": \"bandwidth:recordingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectFallbackMethod\": {\n      \"@id\": \"bandwidth:redirectFallbackMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectFallbackUrl\": {\n      \"@id\": \"bandwidth:redirectFallbackUrl\",\n      \"@type\": \"@id\"\n    },\n    \"redirectMethod\": {\n      \"@id\": \"bandwidth:redirectMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"bandwidth:redirectUrl\",\n      \"@type\": \"@id\"\n    },\n    \"requestedFocDate\": {\n      \"@id\": \"bandwidth:requestedFocDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCount\": {\n      \"@id\": \"bandwidth:resultCount\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"scope\": {\n      \"@id\": \"bandwidth:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentCount\": {\n      \"@id\": \"bandwidth:segmentCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sipPeerId\": {\n      \"@id\": \"bandwidth:sipPeerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sipPeers\": {\n      \"@id\": \"bandwidth:sipPeers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteId\": {\n      \"@id\": \"bandwidth:siteId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sites\": {\n      \"@id\": \"bandwidth:sites\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"bandwidth:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"state\": {\n      \"@id\": \"bandwidth:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"bandwidth:stateCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\"\
  : {\n      \"@id\": \"bandwidth:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetName\": {\n      \"@id\": \"bandwidth:streetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submissionDate\": {\n      \"@id\": \"bandwidth:submissionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"subscriber\": {\n      \"@id\": \"bandwidth:subscriber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"bandwidth:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"bandwidth:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumberList\": {\n      \"@id\": \"bandwidth:telephoneNumberList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumbers\": {\n      \"@id\": \"bandwidth:telephoneNumbers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"bandwidth:text\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"bandwidth:time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"to\": {\n      \"@id\": \"bandwidth:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"bandwidth:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transcription\": {\n      \"@id\": \"bandwidth:transcription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bandwidth:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"useCase\": {\n      \"@id\": \"bandwidth:useCase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useCaseSummary\": {\n      \"@id\": \"bandwidth:useCaseSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valid\": {\n      \"@id\": \"bandwidth:valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"verificationDate\": {\n      \"@id\": \"bandwidth:verificationDate\",\n      \"@type\": \"xsd:dateTime\"\n\
  \    },\n    \"verificationId\": {\n      \"@id\": \"bandwidth:verificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verifications\": {\n      \"@id\": \"bandwidth:verifications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zip\": {\n      \"@id\": \"bandwidth:zip\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/json-ld/bandwidth-context.jsonld
tags:
- Communications
- CPaaS
- Voice
- Messaging
- Telephony
- SMS
- MFA
- JSON-LD
- Linked Data
- Semantic Web
---
