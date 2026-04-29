---
api_specs:
- filename: amazon-iot-fleetwise-openapi-original.yml
  format: yaml
  label: AWS IoT FleetWise API
  slug: aws-iot-fleetwise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-fleetwise/refs/heads/main/openapi/amazon-iot-fleetwise-openapi-original.yml
class_count: 102
classes:
- Actuator
- AssociateVehicleFleetRequest
- AssociateVehicleFleetResponse
- Attribute
- BatchCreateVehicleRequest
- BatchCreateVehicleResponse
- BatchUpdateVehicleRequest
- BatchUpdateVehicleResponse
- Branch
- CampaignSummary
- CanDbcDefinition
- CanInterface
- CanSignal
- CloudWatchLogDeliveryOptions
- CollectionScheme
- ConditionBasedCollectionScheme
- CreateCampaignRequest
- CreateCampaignResponse
- CreateDecoderManifestRequest
- CreateDecoderManifestResponse
- CreateFleetRequest
- CreateFleetResponse
- CreateModelManifestRequest
- CreateModelManifestResponse
- CreateSignalCatalogRequest
- CreateSignalCatalogResponse
- CreateVehicleError
- CreateVehicleRequest
- CreateVehicleRequestItem
- CreateVehicleResponse
- CreateVehicleResponseItem
- DataDestinationConfig
- DecoderManifestSummary
- DeleteCampaignRequest
- DeleteCampaignResponse
- DeleteDecoderManifestRequest
- DeleteDecoderManifestResponse
- DeleteFleetRequest
- DeleteFleetResponse
- DeleteModelManifestRequest
- DeleteModelManifestResponse
- DeleteSignalCatalogRequest
- DeleteSignalCatalogResponse
- DeleteVehicleRequest
- DeleteVehicleResponse
- DisassociateVehicleFleetRequest
- DisassociateVehicleFleetResponse
- FleetSummary
- FormattedVss
- GetCampaignRequest
- GetCampaignResponse
- GetDecoderManifestRequest
- GetDecoderManifestResponse
- GetFleetRequest
- GetFleetResponse
- GetLoggingOptionsRequest
- GetLoggingOptionsResponse
- GetModelManifestRequest
- GetModelManifestResponse
- GetRegisterAccountStatusRequest
- GetRegisterAccountStatusResponse
- GetSignalCatalogRequest
- GetSignalCatalogResponse
- GetVehicleRequest
- GetVehicleResponse
- GetVehicleStatusRequest
- GetVehicleStatusResponse
- IamRegistrationResponse
- IamResources
- ImportDecoderManifestRequest
- ImportDecoderManifestResponse
- ImportSignalCatalogRequest
- ImportSignalCatalogResponse
- ListCampaignsRequest
- ListCampaignsResponse
- ListDecoderManifestNetworkInterfacesRequest
- ListDecoderManifestNetworkInterfacesResponse
- ListDecoderManifestSignalsRequest
- ListDecoderManifestSignalsResponse
- ListDecoderManifestsRequest
- ListDecoderManifestsResponse
- ListFleetsForVehicleRequest
- ListFleetsForVehicleResponse
- ListFleetsRequest
- ListFleetsResponse
- ListModelManifestNodesRequest
- ListModelManifestNodesResponse
- ListModelManifestsRequest
- ListModelManifestsResponse
- ListSignalCatalogNodesRequest
- ListSignalCatalogNodesResponse
- ListSignalCatalogsRequest
- ListSignalCatalogsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListVehiclesInFleetRequest
- ListVehiclesInFleetResponse
- ListVehiclesRequest
- ListVehiclesResponse
- ModelManifestSummary
- description
- name
context_file: json-ld/amazon-iot-fleetwise-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-fleetwise/refs/heads/main/json-ld/amazon-iot-fleetwise-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iot Fleetwise from Amazon IoT FleetWise.
layout: jsonld
name: Amazon Iot Fleetwise Context
namespaces:
- prefix: amzn
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Key
  type: string
- container: ''
  name: ResourceARN
  type: string
- container: ''
  name: TagKeys
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: accountStatus
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actuator
  type: string
- container: ''
  name: allowedValues
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: assignedValue
  type: string
- container: ''
  name: associationBehavior
  type: string
- container: ''
  name: attribute
  type: string
- container: ''
  name: attributeUpdateMode
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: bitMaskLength
  type: string
- container: ''
  name: bitRightShift
  type: string
- container: ''
  name: branch
  type: string
- container: ''
  name: bucketArn
  type: string
- container: ''
  name: byteLength
  type: string
- container: ''
  name: campaignName
  type: string
- container: ''
  name: campaignSummaries
  type: string
- container: ''
  name: campaigns
  type: string
- container: ''
  name: canDbc
  type: string
- container: ''
  name: canDbcFiles
  type: string
- container: ''
  name: canInterface
  type: string
- container: ''
  name: canSignal
  type: string
- container: ''
  name: cloudWatchLogDelivery
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: collectionScheme
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: compression
  type: string
- container: ''
  name: conditionBasedCollectionScheme
  type: string
- container: ''
  name: conditionLanguageVersion
  type: string
- container: ''
  name: creationTime
  type: string
- container: ''
  name: customerAccountId
  type: string
- container: ''
  name: dataDestinationConfigs
  type: string
- container: ''
  name: dataExtraDimensions
  type: string
- container: ''
  name: dataFormat
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: decoderManifestArn
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: deprecationMessage
  type: string
- container: ''
  name: diagnosticsMode
  type: string
- container: ''
  name: dtcRequestIntervalSeconds
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: executionRoleArn
  type: string
- container: ''
  name: expiryTime
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: factor
  type: string
- container: ''
  name: fleetId
  type: string
- container: ''
  name: fleetSummaries
  type: string
- container: ''
  name: fleets
  type: string
- container: ''
  name: fullyQualifiedName
  type: string
- container: ''
  name: hasTransmissionEcu
  type: string
- container: ''
  name: iamRegistrationResponse
  type: string
- container: ''
  name: iamResources
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: interfaceId
  type: string
- container: ''
  name: isBigEndian
  type: string
- container: ''
  name: isSigned
  type: string
- container: ''
  name: lastModificationTime
  type: string
- container: ''
  name: length
  type: string
- container: ''
  name: logGroupName
  type: string
- container: ''
  name: logType
  type: string
- container: ''
  name: max
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: maxSampleCount
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: min
  type: string
- container: ''
  name: minimumSamplingIntervalMs
  type: string
- container: ''
  name: minimumTriggerIntervalMs
  type: string
- container: ''
  name: modelManifestArn
  type: string
- container: ''
  name: networkFileDefinitions
  type: string
- container: ''
  name: networkInterface
  type: string
- container: ''
  name: networkInterfaces
  type: string
- container: ''
  name: networkInterfacesToAdd
  type: string
- container: ''
  name: networkInterfacesToRemove
  type: string
- container: ''
  name: networkInterfacesToUpdate
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: nodeCounts
  type: string
- container: ''
  name: nodes
  type: string
- container: ''
  name: nodesToAdd
  type: string
- container: ''
  name: nodesToRemove
  type: string
- container: ''
  name: nodesToUpdate
  type: string
- container: ''
  name: obdInterface
  type: string
- container: ''
  name: obdSignal
  type: string
- container: ''
  name: obdStandard
  type: string
- container: ''
  name: offset
  type: string
- container: ''
  name: periodMs
  type: string
- container: ''
  name: pid
  type: string
- container: ''
  name: pidRequestIntervalSeconds
  type: string
- container: ''
  name: pidResponseLength
  type: string
- container: ''
  name: postTriggerCollectionDuration
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: protocolName
  type: string
- container: ''
  name: protocolVersion
  type: string
- container: ''
  name: registerAccountStatus
  type: string
- container: ''
  name: registrationStatus
  type: string
- container: ''
  name: requestMessageId
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: s3Config
  type: string
- container: ''
  name: scaling
  type: string
- container: ''
  name: sensor
  type: string
- container: ''
  name: serviceMode
  type: string
- container: ''
  name: signalCatalogArn
  type: string
- container: ''
  name: signalDecoders
  type: string
- container: ''
  name: signalDecodersToAdd
  type: string
- container: ''
  name: signalDecodersToRemove
  type: string
- container: ''
  name: signalDecodersToUpdate
  type: string
- container: ''
  name: signalsMap
  type: string
- container: ''
  name: signalsToCollect
  type: string
- container: ''
  name: spoolingMode
  type: string
- container: ''
  name: startBit
  type: string
- container: ''
  name: startByte
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: storageCompressionFormat
  type: string
- container: ''
  name: summaries
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targetArn
  type: string
- container: ''
  name: thingArn
  type: string
- container: ''
  name: timeBasedCollectionScheme
  type: string
- container: ''
  name: timestreamConfig
  type: string
- container: ''
  name: timestreamDatabaseArn
  type: string
- container: ''
  name: timestreamDatabaseName
  type: string
- container: ''
  name: timestreamRegistrationResponse
  type: string
- container: ''
  name: timestreamResources
  type: string
- container: ''
  name: timestreamTableArn
  type: string
- container: ''
  name: timestreamTableName
  type: string
- container: ''
  name: totalActuators
  type: string
- container: ''
  name: totalAttributes
  type: string
- container: ''
  name: totalBranches
  type: string
- container: ''
  name: totalNodes
  type: string
- container: ''
  name: totalSensors
  type: string
- container: ''
  name: triggerMode
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: useExtendedIds
  type: string
- container: ''
  name: vehicleName
  type: string
- container: ''
  name: vehicleSummaries
  type: string
- container: ''
  name: vehicles
  type: string
- container: ''
  name: vss
  type: string
- container: ''
  name: vssJson
  type: string
property_count: 147
provider_name: Amazon IoT FleetWise
provider_slug: amazon-iot-fleetwise
slug: amazon-iot-fleetwise-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Actuator\": \"amzn:Actuator\",\n    \"AssociateVehicleFleetRequest\": \"amzn:AssociateVehicleFleetRequest\",\n    \"AssociateVehicleFleetResponse\": \"amzn:AssociateVehicleFleetResponse\",\n    \"Attribute\": \"amzn:Attribute\",\n    \"BatchCreateVehicleRequest\": \"amzn:BatchCreateVehicleRequest\",\n    \"BatchCreateVehicleResponse\": \"amzn:BatchCreateVehicleResponse\",\n    \"BatchUpdateVehicleRequest\": \"amzn:BatchUpdateVehicleRequest\",\n    \"BatchUpdateVehicleResponse\": \"amzn:BatchUpdateVehicleResponse\",\n    \"Branch\": \"amzn:Branch\",\n    \"CampaignSummary\": \"amzn:CampaignSummary\",\n    \"CanDbcDefinition\": \"amzn:CanDbcDefinition\",\n    \"CanInterface\": \"amzn:CanInterface\",\n    \"CanSignal\": \"amzn:CanSignal\"\
  ,\n    \"CloudWatchLogDeliveryOptions\": \"amzn:CloudWatchLogDeliveryOptions\",\n    \"CollectionScheme\": \"amzn:CollectionScheme\",\n    \"ConditionBasedCollectionScheme\": \"amzn:ConditionBasedCollectionScheme\",\n    \"CreateCampaignRequest\": \"amzn:CreateCampaignRequest\",\n    \"CreateCampaignResponse\": \"amzn:CreateCampaignResponse\",\n    \"CreateDecoderManifestRequest\": \"amzn:CreateDecoderManifestRequest\",\n    \"CreateDecoderManifestResponse\": \"amzn:CreateDecoderManifestResponse\",\n    \"CreateFleetRequest\": \"amzn:CreateFleetRequest\",\n    \"CreateFleetResponse\": \"amzn:CreateFleetResponse\",\n    \"CreateModelManifestRequest\": \"amzn:CreateModelManifestRequest\",\n    \"CreateModelManifestResponse\": \"amzn:CreateModelManifestResponse\",\n    \"CreateSignalCatalogRequest\": \"amzn:CreateSignalCatalogRequest\",\n    \"CreateSignalCatalogResponse\": \"amzn:CreateSignalCatalogResponse\",\n    \"CreateVehicleError\": \"amzn:CreateVehicleError\",\n    \"CreateVehicleRequest\"\
  : \"amzn:CreateVehicleRequest\",\n    \"CreateVehicleRequestItem\": \"amzn:CreateVehicleRequestItem\",\n    \"CreateVehicleResponse\": \"amzn:CreateVehicleResponse\",\n    \"CreateVehicleResponseItem\": \"amzn:CreateVehicleResponseItem\",\n    \"DataDestinationConfig\": \"amzn:DataDestinationConfig\",\n    \"DecoderManifestSummary\": \"amzn:DecoderManifestSummary\",\n    \"DeleteCampaignRequest\": \"amzn:DeleteCampaignRequest\",\n    \"DeleteCampaignResponse\": \"amzn:DeleteCampaignResponse\",\n    \"DeleteDecoderManifestRequest\": \"amzn:DeleteDecoderManifestRequest\",\n    \"DeleteDecoderManifestResponse\": \"amzn:DeleteDecoderManifestResponse\",\n    \"DeleteFleetRequest\": \"amzn:DeleteFleetRequest\",\n    \"DeleteFleetResponse\": \"amzn:DeleteFleetResponse\",\n    \"DeleteModelManifestRequest\": \"amzn:DeleteModelManifestRequest\",\n    \"DeleteModelManifestResponse\": \"amzn:DeleteModelManifestResponse\",\n    \"DeleteSignalCatalogRequest\": \"amzn:DeleteSignalCatalogRequest\",\n\
  \    \"DeleteSignalCatalogResponse\": \"amzn:DeleteSignalCatalogResponse\",\n    \"DeleteVehicleRequest\": \"amzn:DeleteVehicleRequest\",\n    \"DeleteVehicleResponse\": \"amzn:DeleteVehicleResponse\",\n    \"DisassociateVehicleFleetRequest\": \"amzn:DisassociateVehicleFleetRequest\",\n    \"DisassociateVehicleFleetResponse\": \"amzn:DisassociateVehicleFleetResponse\",\n    \"FleetSummary\": \"amzn:FleetSummary\",\n    \"FormattedVss\": \"amzn:FormattedVss\",\n    \"GetCampaignRequest\": \"amzn:GetCampaignRequest\",\n    \"GetCampaignResponse\": \"amzn:GetCampaignResponse\",\n    \"GetDecoderManifestRequest\": \"amzn:GetDecoderManifestRequest\",\n    \"GetDecoderManifestResponse\": \"amzn:GetDecoderManifestResponse\",\n    \"GetFleetRequest\": \"amzn:GetFleetRequest\",\n    \"GetFleetResponse\": \"amzn:GetFleetResponse\",\n    \"GetLoggingOptionsRequest\": \"amzn:GetLoggingOptionsRequest\",\n    \"GetLoggingOptionsResponse\": \"amzn:GetLoggingOptionsResponse\",\n    \"GetModelManifestRequest\"\
  : \"amzn:GetModelManifestRequest\",\n    \"GetModelManifestResponse\": \"amzn:GetModelManifestResponse\",\n    \"GetRegisterAccountStatusRequest\": \"amzn:GetRegisterAccountStatusRequest\",\n    \"GetRegisterAccountStatusResponse\": \"amzn:GetRegisterAccountStatusResponse\",\n    \"GetSignalCatalogRequest\": \"amzn:GetSignalCatalogRequest\",\n    \"GetSignalCatalogResponse\": \"amzn:GetSignalCatalogResponse\",\n    \"GetVehicleRequest\": \"amzn:GetVehicleRequest\",\n    \"GetVehicleResponse\": \"amzn:GetVehicleResponse\",\n    \"GetVehicleStatusRequest\": \"amzn:GetVehicleStatusRequest\",\n    \"GetVehicleStatusResponse\": \"amzn:GetVehicleStatusResponse\",\n    \"IamRegistrationResponse\": \"amzn:IamRegistrationResponse\",\n    \"IamResources\": \"amzn:IamResources\",\n    \"ImportDecoderManifestRequest\": \"amzn:ImportDecoderManifestRequest\",\n    \"ImportDecoderManifestResponse\": \"amzn:ImportDecoderManifestResponse\",\n    \"ImportSignalCatalogRequest\": \"amzn:ImportSignalCatalogRequest\"\
  ,\n    \"ImportSignalCatalogResponse\": \"amzn:ImportSignalCatalogResponse\",\n    \"ListCampaignsRequest\": \"amzn:ListCampaignsRequest\",\n    \"ListCampaignsResponse\": \"amzn:ListCampaignsResponse\",\n    \"ListDecoderManifestNetworkInterfacesRequest\": \"amzn:ListDecoderManifestNetworkInterfacesRequest\",\n    \"ListDecoderManifestNetworkInterfacesResponse\": \"amzn:ListDecoderManifestNetworkInterfacesResponse\",\n    \"ListDecoderManifestSignalsRequest\": \"amzn:ListDecoderManifestSignalsRequest\",\n    \"ListDecoderManifestSignalsResponse\": \"amzn:ListDecoderManifestSignalsResponse\",\n    \"ListDecoderManifestsRequest\": \"amzn:ListDecoderManifestsRequest\",\n    \"ListDecoderManifestsResponse\": \"amzn:ListDecoderManifestsResponse\",\n    \"ListFleetsForVehicleRequest\": \"amzn:ListFleetsForVehicleRequest\",\n    \"ListFleetsForVehicleResponse\": \"amzn:ListFleetsForVehicleResponse\",\n    \"ListFleetsRequest\": \"amzn:ListFleetsRequest\",\n    \"ListFleetsResponse\": \"amzn:ListFleetsResponse\"\
  ,\n    \"ListModelManifestNodesRequest\": \"amzn:ListModelManifestNodesRequest\",\n    \"ListModelManifestNodesResponse\": \"amzn:ListModelManifestNodesResponse\",\n    \"ListModelManifestsRequest\": \"amzn:ListModelManifestsRequest\",\n    \"ListModelManifestsResponse\": \"amzn:ListModelManifestsResponse\",\n    \"ListSignalCatalogNodesRequest\": \"amzn:ListSignalCatalogNodesRequest\",\n    \"ListSignalCatalogNodesResponse\": \"amzn:ListSignalCatalogNodesResponse\",\n    \"ListSignalCatalogsRequest\": \"amzn:ListSignalCatalogsRequest\",\n    \"ListSignalCatalogsResponse\": \"amzn:ListSignalCatalogsResponse\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"ListVehiclesInFleetRequest\": \"amzn:ListVehiclesInFleetRequest\",\n    \"ListVehiclesInFleetResponse\": \"amzn:ListVehiclesInFleetResponse\",\n    \"ListVehiclesRequest\": \"amzn:ListVehiclesRequest\",\n    \"ListVehiclesResponse\"\
  : \"amzn:ListVehiclesResponse\",\n    \"ModelManifestSummary\": \"amzn:ModelManifestSummary\",\n    \"Key\": {\n      \"@id\": \"amzn:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceARN\": {\n      \"@id\": \"amzn:ResourceARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagKeys\": {\n      \"@id\": \"amzn:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"amzn:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"amzn:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountStatus\": {\n      \"@id\": \"amzn:accountStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amzn:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actuator\": {\n      \"@id\": \"amzn:actuator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedValues\": {\n      \"@id\": \"amzn:allowedValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedValue\": {\n      \"@id\": \"amzn:assignedValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationBehavior\": {\n      \"@id\": \"amzn:associationBehavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attribute\": {\n      \"@id\": \"amzn:attribute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributeUpdateMode\": {\n      \"@id\": \"amzn:attributeUpdateMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"amzn:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bitMaskLength\": {\n      \"@id\": \"amzn:bitMaskLength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bitRightShift\": {\n      \"@id\": \"amzn:bitRightShift\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branch\": {\n      \"@id\": \"amzn:branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketArn\": {\n      \"@id\": \"amzn:bucketArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  byteLength\": {\n      \"@id\": \"amzn:byteLength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaignName\": {\n      \"@id\": \"amzn:campaignName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaignSummaries\": {\n      \"@id\": \"amzn:campaignSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaigns\": {\n      \"@id\": \"amzn:campaigns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canDbc\": {\n      \"@id\": \"amzn:canDbc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canDbcFiles\": {\n      \"@id\": \"amzn:canDbcFiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canInterface\": {\n      \"@id\": \"amzn:canInterface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canSignal\": {\n      \"@id\": \"amzn:canSignal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudWatchLogDelivery\": {\n      \"@id\": \"amzn:cloudWatchLogDelivery\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amzn:code\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"collectionScheme\": {\n      \"@id\": \"amzn:collectionScheme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"amzn:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compression\": {\n      \"@id\": \"amzn:compression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conditionBasedCollectionScheme\": {\n      \"@id\": \"amzn:conditionBasedCollectionScheme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conditionLanguageVersion\": {\n      \"@id\": \"amzn:conditionLanguageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"amzn:creationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerAccountId\": {\n      \"@id\": \"amzn:customerAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataDestinationConfigs\": {\n      \"@id\": \"amzn:dataDestinationConfigs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataExtraDimensions\": {\n      \"@id\": \"\
  amzn:dataExtraDimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataFormat\": {\n      \"@id\": \"amzn:dataFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"amzn:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decoderManifestArn\": {\n      \"@id\": \"amzn:decoderManifestArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"amzn:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deprecationMessage\": {\n      \"@id\": \"amzn:deprecationMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"diagnosticsMode\": {\n      \"@id\": \"amzn:diagnosticsMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dtcRequestIntervalSeconds\": {\n      \"@id\": \"amzn:dtcRequestIntervalSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"amzn:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"errors\": {\n      \"@id\": \"amzn:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionRoleArn\": {\n      \"@id\": \"amzn:executionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryTime\": {\n      \"@id\": \"amzn:expiryTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"amzn:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"factor\": {\n      \"@id\": \"amzn:factor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetId\": {\n      \"@id\": \"amzn:fleetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetSummaries\": {\n      \"@id\": \"amzn:fleetSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleets\": {\n      \"@id\": \"amzn:fleets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullyQualifiedName\": {\n      \"@id\": \"amzn:fullyQualifiedName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasTransmissionEcu\": {\n      \"@id\": \"amzn:hasTransmissionEcu\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"iamRegistrationResponse\": {\n      \"@id\": \"amzn:iamRegistrationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamResources\": {\n      \"@id\": \"amzn:iamResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amzn:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interfaceId\": {\n      \"@id\": \"amzn:interfaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isBigEndian\": {\n      \"@id\": \"amzn:isBigEndian\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isSigned\": {\n      \"@id\": \"amzn:isSigned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModificationTime\": {\n      \"@id\": \"amzn:lastModificationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"amzn:length\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logGroupName\": {\n      \"@id\": \"amzn:logGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logType\": {\n      \"\
  @id\": \"amzn:logType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"max\": {\n      \"@id\": \"amzn:max\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxSampleCount\": {\n      \"@id\": \"amzn:maxSampleCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"amzn:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"min\": {\n      \"@id\": \"amzn:min\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumSamplingIntervalMs\": {\n      \"@id\": \"amzn:minimumSamplingIntervalMs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumTriggerIntervalMs\": {\n      \"@id\": \"amzn:minimumTriggerIntervalMs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelManifestArn\": {\n      \"@id\": \"amzn:modelManifestArn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"name\": \"schema:name\",\n    \"networkFileDefinitions\": {\n      \"@id\": \"amzn:networkFileDefinitions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterface\": {\n      \"@id\": \"amzn:networkInterface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterfaces\": {\n      \"@id\": \"amzn:networkInterfaces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterfacesToAdd\": {\n      \"@id\": \"amzn:networkInterfacesToAdd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterfacesToRemove\": {\n      \"@id\": \"amzn:networkInterfacesToRemove\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterfacesToUpdate\": {\n      \"@id\": \"amzn:networkInterfacesToUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeCounts\": {\n      \"@id\": \"amzn:nodeCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodes\": {\n\
  \      \"@id\": \"amzn:nodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodesToAdd\": {\n      \"@id\": \"amzn:nodesToAdd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodesToRemove\": {\n      \"@id\": \"amzn:nodesToRemove\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodesToUpdate\": {\n      \"@id\": \"amzn:nodesToUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"obdInterface\": {\n      \"@id\": \"amzn:obdInterface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"obdSignal\": {\n      \"@id\": \"amzn:obdSignal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"obdStandard\": {\n      \"@id\": \"amzn:obdStandard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"amzn:offset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodMs\": {\n      \"@id\": \"amzn:periodMs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pid\": {\n      \"@id\": \"amzn:pid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pidRequestIntervalSeconds\"\
  : {\n      \"@id\": \"amzn:pidRequestIntervalSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pidResponseLength\": {\n      \"@id\": \"amzn:pidResponseLength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postTriggerCollectionDuration\": {\n      \"@id\": \"amzn:postTriggerCollectionDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"amzn:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"amzn:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolName\": {\n      \"@id\": \"amzn:protocolName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolVersion\": {\n      \"@id\": \"amzn:protocolVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registerAccountStatus\": {\n      \"@id\": \"amzn:registerAccountStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationStatus\": {\n      \"@id\": \"amzn:registrationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"requestMessageId\": {\n      \"@id\": \"amzn:requestMessageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Config\": {\n      \"@id\": \"amzn:s3Config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scaling\": {\n      \"@id\": \"amzn:scaling\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensor\": {\n      \"@id\": \"amzn:sensor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceMode\": {\n      \"@id\": \"amzn:serviceMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalCatalogArn\": {\n      \"@id\": \"amzn:signalCatalogArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalDecoders\": {\n      \"@id\": \"amzn:signalDecoders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalDecodersToAdd\": {\n      \"@id\": \"amzn:signalDecodersToAdd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalDecodersToRemove\": {\n      \"@id\": \"amzn:signalDecodersToRemove\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"signalDecodersToUpdate\": {\n      \"@id\": \"amzn:signalDecodersToUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalsMap\": {\n      \"@id\": \"amzn:signalsMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalsToCollect\": {\n      \"@id\": \"amzn:signalsToCollect\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spoolingMode\": {\n      \"@id\": \"amzn:spoolingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startBit\": {\n      \"@id\": \"amzn:startBit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startByte\": {\n      \"@id\": \"amzn:startByte\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amzn:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageCompressionFormat\": {\n      \"@id\": \"amzn:storageCompressionFormat\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"summaries\": {\n      \"@id\": \"amzn:summaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetArn\": {\n      \"@id\": \"amzn:targetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingArn\": {\n      \"@id\": \"amzn:thingArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeBasedCollectionScheme\": {\n      \"@id\": \"amzn:timeBasedCollectionScheme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestreamConfig\": {\n      \"@id\": \"amzn:timestreamConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestreamDatabaseArn\": {\n      \"@id\": \"amzn:timestreamDatabaseArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestreamDatabaseName\": {\n      \"@id\": \"amzn:timestreamDatabaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestreamRegistrationResponse\": {\n      \"@id\": \"amzn:timestreamRegistrationResponse\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"timestreamResources\": {\n      \"@id\": \"amzn:timestreamResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestreamTableArn\": {\n      \"@id\": \"amzn:timestreamTableArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestreamTableName\": {\n      \"@id\": \"amzn:timestreamTableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalActuators\": {\n      \"@id\": \"amzn:totalActuators\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAttributes\": {\n      \"@id\": \"amzn:totalAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalBranches\": {\n      \"@id\": \"amzn:totalBranches\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalNodes\": {\n      \"@id\": \"amzn:totalNodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalSensors\": {\n      \"@id\": \"amzn:totalSensors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerMode\": {\n      \"@id\": \"amzn:triggerMode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"amzn:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useExtendedIds\": {\n      \"@id\": \"amzn:useExtendedIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicleName\": {\n      \"@id\": \"amzn:vehicleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicleSummaries\": {\n      \"@id\": \"amzn:vehicleSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicles\": {\n      \"@id\": \"amzn:vehicles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vss\": {\n      \"@id\": \"amzn:vss\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vssJson\": {\n      \"@id\": \"amzn:vssJson\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-fleetwise/refs/heads/main/json-ld/amazon-iot-fleetwise-context.jsonld
tags:
- Automotive
- AWS
- Connected Vehicles
- IoT
- Telematics
- Vehicle Data
- JSON-LD
- Linked Data
- Semantic Web
---
