---
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
