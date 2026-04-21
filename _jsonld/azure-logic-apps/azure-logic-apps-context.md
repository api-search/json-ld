---
class_count: 19
classes:
- AS2AcknowledgementConnectionSettings
- AS2AgreementContent
- AS2EnvelopeSettings
- AS2ErrorSettings
- AS2MdnSettings
- AS2MessageConnectionSettings
- AS2OneWayAgreement
- AS2ProtocolSettings
- AS2SecuritySettings
- AS2ValidationSettings
- AgreementContent
- ApiDeploymentParameterMetadata
- ApiDeploymentParameterMetadataSet
- ApiOperation
- ApiOperationAnnotation
- ApiOperationListResult
- ApiOperationPropertiesDefinition
- ApiReference
- description
context_file: json-ld/azure-logic-apps-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-logic-apps/refs/heads/main/json-ld/azure-logic-apps-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Logic Apps from Azure Logic Apps.
layout: jsonld
name: Azure Logic Apps Context
namespaces:
- prefix: azurelogicapps
  uri: https://azure.microsoft.com/azure-logic-apps/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ignoreCertificateNameMismatch
  type: boolean
- container: ''
  name: keepHttpConnectionAlive
  type: boolean
- container: ''
  name: supportHttpStatusCodeContinue
  type: boolean
- container: ''
  name: unfoldHttpHeaders
  type: boolean
- container: ''
  name: receiveAgreement
  type: string
- container: ''
  name: sendAgreement
  type: string
- container: ''
  name: autogenerateFileName
  type: boolean
- container: ''
  name: fileNameTemplate
  type: string
- container: ''
  name: messageContentType
  type: string
- container: ''
  name: suspendMessageOnFileNameGenerationError
  type: boolean
- container: ''
  name: transmitFileNameInMimeHeader
  type: boolean
- container: ''
  name: resendIfMDNNotReceived
  type: boolean
- container: ''
  name: suspendDuplicateMessage
  type: boolean
- container: ''
  name: dispositionNotificationTo
  type: string
- container: ''
  name: mdnText
  type: string
- container: ''
  name: micHashingAlgorithm
  type: string
- container: ''
  name: needMDN
  type: boolean
- container: ''
  name: receiptDeliveryUrl
  type: string
- container: ''
  name: sendInboundMDNToMessageBox
  type: boolean
- container: ''
  name: sendMDNAsynchronously
  type: boolean
- container: ''
  name: signMDN
  type: boolean
- container: ''
  name: signOutboundMDNIfOptional
  type: boolean
- container: ''
  name: protocolSettings
  type: string
- container: ''
  name: receiverBusinessIdentity
  type: string
- container: ''
  name: senderBusinessIdentity
  type: string
- container: ''
  name: acknowledgementConnectionSettings
  type: string
- container: ''
  name: envelopeSettings
  type: string
- container: ''
  name: errorSettings
  type: string
- container: ''
  name: mdnSettings
  type: string
- container: ''
  name: messageConnectionSettings
  type: string
- container: ''
  name: securitySettings
  type: string
- container: ''
  name: validationSettings
  type: string
- container: ''
  name: enableNRRForInboundDecodedMessages
  type: boolean
- container: ''
  name: enableNRRForInboundEncodedMessages
  type: boolean
- container: ''
  name: enableNRRForInboundMDN
  type: boolean
- container: ''
  name: enableNRRForOutboundDecodedMessages
  type: boolean
- container: ''
  name: enableNRRForOutboundEncodedMessages
  type: boolean
- container: ''
  name: enableNRRForOutboundMDN
  type: boolean
- container: ''
  name: encryptionCertificateName
  type: string
- container: ''
  name: overrideGroupSigningCertificate
  type: boolean
- container: ''
  name: sha2AlgorithmFormat
  type: string
- container: ''
  name: signingCertificateName
  type: string
- container: ''
  name: checkCertificateRevocationListOnReceive
  type: boolean
- container: ''
  name: checkCertificateRevocationListOnSend
  type: boolean
- container: ''
  name: checkDuplicateMessage
  type: boolean
- container: ''
  name: compressMessage
  type: boolean
- container: ''
  name: encryptMessage
  type: boolean
- container: ''
  name: encryptionAlgorithm
  type: string
- container: ''
  name: interchangeDuplicatesValidityDays
  type: integer
- container: ''
  name: overrideMessageProperties
  type: boolean
- container: ''
  name: signMessage
  type: boolean
- container: ''
  name: signingAlgorithm
  type: string
- container: ''
  name: aS2
  type: string
- container: ''
  name: edifact
  type: string
- container: ''
  name: x12
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: isRequired
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: packageContentLink
  type: string
- container: ''
  name: redisCacheConnectionString
  type: string
- container: ''
  name: properties
  type: string
- container: ''
  name: family
  type: string
- container: ''
  name: revision
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: nextLink
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: annotation
  type: string
- container: ''
  name: api
  type: string
- container: ''
  name: inputsDefinition
  type: string
- container: ''
  name: isNotification
  type: boolean
- container: ''
  name: isWebhook
  type: boolean
- container: ''
  name: pageable
  type: boolean
- container: ''
  name: responsesDefinition
  type: reference
- container: ''
  name: summary
  type: string
- container: ''
  name: trigger
  type: string
- container: ''
  name: triggerHint
  type: string
- container: ''
  name: brandColor
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: iconUri
  type: string
- container: ''
  name: integrationServiceEnvironment
  type: string
- container: ''
  name: swagger
  type: string
property_count: 82
provider_name: Azure Logic Apps
provider_slug: azure-logic-apps
slug: azure-logic-apps-context
tags:
- Azure
- Integration
- iPaaS
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
