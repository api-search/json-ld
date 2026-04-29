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
source_filename: azure-logic-apps-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurelogicapps\": \"https://azure.microsoft.com/azure-logic-apps/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AS2AcknowledgementConnectionSettings\": \"azurelogicapps:AS2AcknowledgementConnectionSettings\",\n    \"AS2AgreementContent\": \"azurelogicapps:AS2AgreementContent\",\n    \"AS2EnvelopeSettings\": \"azurelogicapps:AS2EnvelopeSettings\",\n    \"AS2ErrorSettings\": \"azurelogicapps:AS2ErrorSettings\",\n    \"AS2MdnSettings\": \"azurelogicapps:AS2MdnSettings\",\n    \"AS2MessageConnectionSettings\": \"azurelogicapps:AS2MessageConnectionSettings\",\n    \"AS2OneWayAgreement\": \"azurelogicapps:AS2OneWayAgreement\",\n    \"AS2ProtocolSettings\": \"azurelogicapps:AS2ProtocolSettings\",\n    \"AS2SecuritySettings\": \"azurelogicapps:AS2SecuritySettings\",\n    \"AS2ValidationSettings\": \"azurelogicapps:AS2ValidationSettings\"\
  ,\n    \"AgreementContent\": \"azurelogicapps:AgreementContent\",\n    \"ApiDeploymentParameterMetadata\": \"azurelogicapps:ApiDeploymentParameterMetadata\",\n    \"ApiDeploymentParameterMetadataSet\": \"azurelogicapps:ApiDeploymentParameterMetadataSet\",\n    \"ApiOperation\": \"azurelogicapps:ApiOperation\",\n    \"ApiOperationAnnotation\": \"azurelogicapps:ApiOperationAnnotation\",\n    \"ApiOperationListResult\": \"azurelogicapps:ApiOperationListResult\",\n    \"ApiOperationPropertiesDefinition\": \"azurelogicapps:ApiOperationPropertiesDefinition\",\n    \"ApiReference\": \"azurelogicapps:ApiReference\",\n    \"ignoreCertificateNameMismatch\": {\n      \"@id\": \"azurelogicapps:ignoreCertificateNameMismatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"keepHttpConnectionAlive\": {\n      \"@id\": \"azurelogicapps:keepHttpConnectionAlive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"supportHttpStatusCodeContinue\": {\n      \"@id\": \"azurelogicapps:supportHttpStatusCodeContinue\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"unfoldHttpHeaders\": {\n      \"@id\": \"azurelogicapps:unfoldHttpHeaders\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"receiveAgreement\": {\n      \"@id\": \"azurelogicapps:receiveAgreement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sendAgreement\": {\n      \"@id\": \"azurelogicapps:sendAgreement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autogenerateFileName\": {\n      \"@id\": \"azurelogicapps:autogenerateFileName\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fileNameTemplate\": {\n      \"@id\": \"azurelogicapps:fileNameTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageContentType\": {\n      \"@id\": \"azurelogicapps:messageContentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suspendMessageOnFileNameGenerationError\": {\n      \"@id\": \"azurelogicapps:suspendMessageOnFileNameGenerationError\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"transmitFileNameInMimeHeader\"\
  : {\n      \"@id\": \"azurelogicapps:transmitFileNameInMimeHeader\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resendIfMDNNotReceived\": {\n      \"@id\": \"azurelogicapps:resendIfMDNNotReceived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"suspendDuplicateMessage\": {\n      \"@id\": \"azurelogicapps:suspendDuplicateMessage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dispositionNotificationTo\": {\n      \"@id\": \"azurelogicapps:dispositionNotificationTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mdnText\": {\n      \"@id\": \"azurelogicapps:mdnText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"micHashingAlgorithm\": {\n      \"@id\": \"azurelogicapps:micHashingAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"needMDN\": {\n      \"@id\": \"azurelogicapps:needMDN\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"receiptDeliveryUrl\": {\n      \"@id\": \"azurelogicapps:receiptDeliveryUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  sendInboundMDNToMessageBox\": {\n      \"@id\": \"azurelogicapps:sendInboundMDNToMessageBox\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sendMDNAsynchronously\": {\n      \"@id\": \"azurelogicapps:sendMDNAsynchronously\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"signMDN\": {\n      \"@id\": \"azurelogicapps:signMDN\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"signOutboundMDNIfOptional\": {\n      \"@id\": \"azurelogicapps:signOutboundMDNIfOptional\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"protocolSettings\": {\n      \"@id\": \"azurelogicapps:protocolSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receiverBusinessIdentity\": {\n      \"@id\": \"azurelogicapps:receiverBusinessIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"senderBusinessIdentity\": {\n      \"@id\": \"azurelogicapps:senderBusinessIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acknowledgementConnectionSettings\": {\n      \"@id\": \"azurelogicapps:acknowledgementConnectionSettings\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"envelopeSettings\": {\n      \"@id\": \"azurelogicapps:envelopeSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorSettings\": {\n      \"@id\": \"azurelogicapps:errorSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mdnSettings\": {\n      \"@id\": \"azurelogicapps:mdnSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageConnectionSettings\": {\n      \"@id\": \"azurelogicapps:messageConnectionSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securitySettings\": {\n      \"@id\": \"azurelogicapps:securitySettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validationSettings\": {\n      \"@id\": \"azurelogicapps:validationSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableNRRForInboundDecodedMessages\": {\n      \"@id\": \"azurelogicapps:enableNRRForInboundDecodedMessages\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableNRRForInboundEncodedMessages\": {\n    \
  \  \"@id\": \"azurelogicapps:enableNRRForInboundEncodedMessages\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableNRRForInboundMDN\": {\n      \"@id\": \"azurelogicapps:enableNRRForInboundMDN\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableNRRForOutboundDecodedMessages\": {\n      \"@id\": \"azurelogicapps:enableNRRForOutboundDecodedMessages\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableNRRForOutboundEncodedMessages\": {\n      \"@id\": \"azurelogicapps:enableNRRForOutboundEncodedMessages\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableNRRForOutboundMDN\": {\n      \"@id\": \"azurelogicapps:enableNRRForOutboundMDN\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"encryptionCertificateName\": {\n      \"@id\": \"azurelogicapps:encryptionCertificateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overrideGroupSigningCertificate\": {\n      \"@id\": \"azurelogicapps:overrideGroupSigningCertificate\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"sha2AlgorithmFormat\": {\n      \"@id\": \"azurelogicapps:sha2AlgorithmFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingCertificateName\": {\n      \"@id\": \"azurelogicapps:signingCertificateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkCertificateRevocationListOnReceive\": {\n      \"@id\": \"azurelogicapps:checkCertificateRevocationListOnReceive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"checkCertificateRevocationListOnSend\": {\n      \"@id\": \"azurelogicapps:checkCertificateRevocationListOnSend\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"checkDuplicateMessage\": {\n      \"@id\": \"azurelogicapps:checkDuplicateMessage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"compressMessage\": {\n      \"@id\": \"azurelogicapps:compressMessage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"encryptMessage\": {\n      \"@id\": \"azurelogicapps:encryptMessage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"encryptionAlgorithm\"\
  : {\n      \"@id\": \"azurelogicapps:encryptionAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interchangeDuplicatesValidityDays\": {\n      \"@id\": \"azurelogicapps:interchangeDuplicatesValidityDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"overrideMessageProperties\": {\n      \"@id\": \"azurelogicapps:overrideMessageProperties\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"signMessage\": {\n      \"@id\": \"azurelogicapps:signMessage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"signingAlgorithm\": {\n      \"@id\": \"azurelogicapps:signingAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aS2\": {\n      \"@id\": \"azurelogicapps:aS2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"edifact\": {\n      \"@id\": \"azurelogicapps:edifact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"x12\": {\n      \"@id\": \"azurelogicapps:x12\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"displayName\"\
  : {\n      \"@id\": \"azurelogicapps:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isRequired\": {\n      \"@id\": \"azurelogicapps:isRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"azurelogicapps:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visibility\": {\n      \"@id\": \"azurelogicapps:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageContentLink\": {\n      \"@id\": \"azurelogicapps:packageContentLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redisCacheConnectionString\": {\n      \"@id\": \"azurelogicapps:redisCacheConnectionString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"azurelogicapps:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"family\": {\n      \"@id\": \"azurelogicapps:family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"azurelogicapps:revision\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"status\": {\n      \"@id\": \"azurelogicapps:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azurelogicapps:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurelogicapps:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annotation\": {\n      \"@id\": \"azurelogicapps:annotation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"api\": {\n      \"@id\": \"azurelogicapps:api\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputsDefinition\": {\n      \"@id\": \"azurelogicapps:inputsDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isNotification\": {\n      \"@id\": \"azurelogicapps:isNotification\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isWebhook\": {\n      \"@id\": \"azurelogicapps:isWebhook\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pageable\": {\n      \"@id\": \"azurelogicapps:pageable\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"responsesDefinition\": {\n      \"@id\": \"azurelogicapps:responsesDefinition\",\n      \"@type\": \"@id\"\n    },\n    \"summary\": {\n      \"@id\": \"azurelogicapps:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trigger\": {\n      \"@id\": \"azurelogicapps:trigger\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerHint\": {\n      \"@id\": \"azurelogicapps:triggerHint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brandColor\": {\n      \"@id\": \"azurelogicapps:brandColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"azurelogicapps:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iconUri\": {\n      \"@id\": \"azurelogicapps:iconUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrationServiceEnvironment\": {\n      \"@id\": \"azurelogicapps:integrationServiceEnvironment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swagger\": {\n      \"@id\": \"azurelogicapps:swagger\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-logic-apps/refs/heads/main/json-ld/azure-logic-apps-context.jsonld
tags:
- Azure
- Integration
- iPaaS
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
