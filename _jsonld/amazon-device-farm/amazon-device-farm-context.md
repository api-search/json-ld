---
api_specs:
- filename: amazon-device-farm-openapi.yaml
  format: yaml
  label: AWS Device Farm API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-device-farm/refs/heads/main/openapi/amazon-device-farm-openapi.yaml
class_count: 29
classes:
- AccountSettings
- Artifact
- Device
- DeviceFilter
- DeviceInstance
- DevicePool
- IncompatibilityMessage
- InstanceProfile
- Job
- NetworkProfile
- Offering
- OfferingTransaction
- Problem
- Project
- RemoteAccessSession
- Rule
- Run
- Sample
- Suite
- Test
- TestGridProject
- TestGridSession
- TestGridSessionAction
- TestGridSessionArtifact
- Upload
- VPCEConfiguration
- description
- name
- url
context_file: json-ld/amazon-device-farm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-device-farm/refs/heads/main/json-ld/amazon-device-farm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Device Farm from Amazon Device Farm.
layout: jsonld
name: Amazon Device Farm Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/device-farm/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: action
  type: string
- container: ''
  name: appUpload
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: attribute
  type: string
- container: ''
  name: availability
  type: string
- container: ''
  name: awsAccountNumber
  type: string
- container: ''
  name: billingMethod
  type: string
- container: ''
  name: billingMinutes
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: completedJobs
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: cost
  type: string
- container: ''
  name: counters
  type: string
- container: ''
  name: cpu
  type: string
- container: ''
  name: created
  type: string
- container: ''
  name: createdOn
  type: string
- container: ''
  name: customerArtifactPaths
  type: string
- container: ''
  name: defaultJobTimeoutMinutes
  type: string
- container: ''
  name: device
  type: string
- container: ''
  name: deviceArn
  type: string
- container: ''
  name: deviceMinutes
  type: string
- container: ''
  name: devicePoolArn
  type: string
- container: ''
  name: deviceSelectionResult
  type: string
- container: ''
  name: deviceUdid
  type: string
- container: ''
  name: downlinkBandwidthBits
  type: string
- container: ''
  name: downlinkDelayMs
  type: string
- container: ''
  name: downlinkJitterMs
  type: string
- container: ''
  name: downlinkLossPercent
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: ended
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: eventCount
  type: string
- container: ''
  name: excludeAppPackagesFromCleanup
  type: string
- container: ''
  name: extension
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: fleetName
  type: string
- container: ''
  name: fleetType
  type: string
- container: ''
  name: formFactor
  type: string
- container: ''
  name: heapSize
  type: string
- container: ''
  name: hostAddress
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: instanceArn
  type: string
- container: ''
  name: instanceProfile
  type: string
- container: ''
  name: instances
  type: string
- container: ''
  name: interactionMode
  type: string
- container: ''
  name: job
  type: string
- container: ''
  name: jobTimeoutMinutes
  type: string
- container: ''
  name: labels
  type: string
- container: ''
  name: locale
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: maxDevices
  type: string
- container: ''
  name: maxJobTimeoutMinutes
  type: string
- container: ''
  name: maxSlots
  type: string
- container: ''
  name: memory
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: modelId
  type: string
- container: ''
  name: networkProfile
  type: string
- container: ''
  name: offeringPromotionId
  type: string
- container: ''
  name: offeringStatus
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: packageCleanup
  type: string
- container: ''
  name: parsingResultUrl
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: radio
  type: string
- container: ''
  name: radios
  type: string
- container: ''
  name: rebootAfterUse
  type: string
- container: ''
  name: recurringCharges
  type: string
- container: ''
  name: remoteAccessEnabled
  type: string
- container: ''
  name: remoteDebugEnabled
  type: string
- container: ''
  name: remoteRecordAppArn
  type: string
- container: ''
  name: remoteRecordEnabled
  type: string
- container: ''
  name: requestMethod
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: rules
  type: string
- container: ''
  name: run
  type: string
- container: ''
  name: seed
  type: string
- container: ''
  name: seleniumProperties
  type: string
- container: ''
  name: serviceDnsName
  type: string
- container: ''
  name: skipAppResign
  type: string
- container: ''
  name: started
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusCode
  type: string
- container: ''
  name: stopped
  type: string
- container: ''
  name: suite
  type: string
- container: ''
  name: test
  type: string
- container: ''
  name: testSpecArn
  type: string
- container: ''
  name: totalJobs
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: trialMinutes
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: udid
  type: string
- container: ''
  name: unmeteredDevices
  type: string
- container: ''
  name: unmeteredRemoteAccessDevices
  type: string
- container: ''
  name: uplinkBandwidthBits
  type: string
- container: ''
  name: uplinkDelayMs
  type: string
- container: ''
  name: uplinkJitterMs
  type: string
- container: ''
  name: uplinkLossPercent
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: videoCapture
  type: string
- container: ''
  name: videoEndpoint
  type: string
- container: ''
  name: vpcConfig
  type: string
- container: ''
  name: vpceConfigurationDescription
  type: string
- container: ''
  name: vpceConfigurationName
  type: string
- container: ''
  name: vpceServiceName
  type: string
- container: ''
  name: webUrl
  type: string
property_count: 115
provider_name: Amazon Device Farm
provider_slug: amazon-device-farm
slug: amazon-device-farm-context
source_filename: amazon-device-farm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/device-farm/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountSettings\": \"amz:AccountSettings\",\n    \"Artifact\": \"amz:Artifact\",\n    \"Device\": \"amz:Device\",\n    \"DeviceFilter\": \"amz:DeviceFilter\",\n    \"DeviceInstance\": \"amz:DeviceInstance\",\n    \"DevicePool\": \"amz:DevicePool\",\n    \"IncompatibilityMessage\": \"amz:IncompatibilityMessage\",\n    \"InstanceProfile\": \"amz:InstanceProfile\",\n    \"Job\": \"amz:Job\",\n    \"NetworkProfile\": \"amz:NetworkProfile\",\n    \"Offering\": \"amz:Offering\",\n    \"OfferingTransaction\": \"amz:OfferingTransaction\",\n    \"Problem\": \"amz:Problem\",\n    \"Project\": \"amz:Project\",\n    \"RemoteAccessSession\": \"amz:RemoteAccessSession\",\n    \"Rule\": \"amz:Rule\",\n    \"Run\": \"amz:Run\",\n    \"Sample\"\
  : \"amz:Sample\",\n    \"Suite\": \"amz:Suite\",\n    \"Test\": \"amz:Test\",\n    \"TestGridProject\": \"amz:TestGridProject\",\n    \"TestGridSession\": \"amz:TestGridSession\",\n    \"TestGridSessionAction\": \"amz:TestGridSessionAction\",\n    \"TestGridSessionArtifact\": \"amz:TestGridSessionArtifact\",\n    \"Upload\": \"amz:Upload\",\n    \"VPCEConfiguration\": \"amz:VPCEConfiguration\",\n    \"action\": {\n      \"@id\": \"amz:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appUpload\": {\n      \"@id\": \"amz:appUpload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amz:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attribute\": {\n      \"@id\": \"amz:attribute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availability\": {\n      \"@id\": \"amz:availability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountNumber\": {\n      \"@id\": \"amz:awsAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingMethod\"\
  : {\n      \"@id\": \"amz:billingMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingMinutes\": {\n      \"@id\": \"amz:billingMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"amz:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amz:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"amz:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedJobs\": {\n      \"@id\": \"amz:completedJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"amz:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cost\": {\n      \"@id\": \"amz:cost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counters\": {\n      \"@id\": \"amz:counters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpu\": {\n      \"@id\": \"amz:cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"amz:created\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"amz:createdOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerArtifactPaths\": {\n      \"@id\": \"amz:customerArtifactPaths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultJobTimeoutMinutes\": {\n      \"@id\": \"amz:defaultJobTimeoutMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"device\": {\n      \"@id\": \"amz:device\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceArn\": {\n      \"@id\": \"amz:deviceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceMinutes\": {\n      \"@id\": \"amz:deviceMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"devicePoolArn\": {\n      \"@id\": \"amz:devicePoolArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceSelectionResult\": {\n      \"@id\": \"amz:deviceSelectionResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceUdid\": {\n      \"@id\":\
  \ \"amz:deviceUdid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downlinkBandwidthBits\": {\n      \"@id\": \"amz:downlinkBandwidthBits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downlinkDelayMs\": {\n      \"@id\": \"amz:downlinkDelayMs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downlinkJitterMs\": {\n      \"@id\": \"amz:downlinkJitterMs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downlinkLossPercent\": {\n      \"@id\": \"amz:downlinkLossPercent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"amz:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ended\": {\n      \"@id\": \"amz:ended\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"amz:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventCount\": {\n      \"@id\": \"amz:eventCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"excludeAppPackagesFromCleanup\": {\n      \"@id\": \"amz:excludeAppPackagesFromCleanup\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"extension\": {\n      \"@id\": \"amz:extension\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"amz:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetName\": {\n      \"@id\": \"amz:fleetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetType\": {\n      \"@id\": \"amz:fleetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formFactor\": {\n      \"@id\": \"amz:formFactor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"heapSize\": {\n      \"@id\": \"amz:heapSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostAddress\": {\n      \"@id\": \"amz:hostAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amz:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"amz:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceArn\": {\n      \"@id\": \"amz:instanceArn\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"instanceProfile\": {\n      \"@id\": \"amz:instanceProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instances\": {\n      \"@id\": \"amz:instances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interactionMode\": {\n      \"@id\": \"amz:interactionMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job\": {\n      \"@id\": \"amz:job\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTimeoutMinutes\": {\n      \"@id\": \"amz:jobTimeoutMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"amz:labels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locale\": {\n      \"@id\": \"amz:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"amz:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"amz:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxDevices\": {\n      \"@id\": \"amz:maxDevices\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"maxJobTimeoutMinutes\": {\n      \"@id\": \"amz:maxJobTimeoutMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxSlots\": {\n      \"@id\": \"amz:maxSlots\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memory\": {\n      \"@id\": \"amz:memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amz:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amz:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"amz:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelId\": {\n      \"@id\": \"amz:modelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"networkProfile\": {\n      \"@id\": \"amz:networkProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offeringPromotionId\": {\n      \"@id\": \"amz:offeringPromotionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offeringStatus\": {\n      \"@id\": \"amz:offeringStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"amz:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os\": {\n      \"@id\": \"amz:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageCleanup\": {\n      \"@id\": \"amz:packageCleanup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parsingResultUrl\": {\n      \"@id\": \"amz:parsingResultUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"amz:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"radio\": {\n      \"@id\": \"amz:radio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"radios\": {\n      \"@id\": \"amz:radios\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rebootAfterUse\": {\n      \"@id\": \"amz:rebootAfterUse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringCharges\": {\n      \"@id\": \"amz:recurringCharges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteAccessEnabled\": {\n      \"@id\": \"amz:remoteAccessEnabled\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteDebugEnabled\": {\n      \"@id\": \"amz:remoteDebugEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteRecordAppArn\": {\n      \"@id\": \"amz:remoteRecordAppArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteRecordEnabled\": {\n      \"@id\": \"amz:remoteRecordEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestMethod\": {\n      \"@id\": \"amz:requestMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"amz:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"amz:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"amz:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"amz:rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"run\": {\n      \"@id\": \"amz:run\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seed\": {\n      \"@id\":\
  \ \"amz:seed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seleniumProperties\": {\n      \"@id\": \"amz:seleniumProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceDnsName\": {\n      \"@id\": \"amz:serviceDnsName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skipAppResign\": {\n      \"@id\": \"amz:skipAppResign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"started\": {\n      \"@id\": \"amz:started\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"amz:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stopped\": {\n      \"@id\": \"amz:stopped\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suite\": {\n      \"@id\": \"amz:suite\",\n      \"@type\": \"xsd:string\"\n    },\n    \"test\": {\n      \"@id\": \"amz:test\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testSpecArn\": {\n      \"@id\": \"amz:testSpecArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"totalJobs\": {\n      \"@id\": \"amz:totalJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"amz:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trialMinutes\": {\n      \"@id\": \"amz:trialMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amz:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"udid\": {\n      \"@id\": \"amz:udid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unmeteredDevices\": {\n      \"@id\": \"amz:unmeteredDevices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unmeteredRemoteAccessDevices\": {\n      \"@id\": \"amz:unmeteredRemoteAccessDevices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uplinkBandwidthBits\": {\n      \"@id\": \"amz:uplinkBandwidthBits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uplinkDelayMs\": {\n      \"@id\": \"amz:uplinkDelayMs\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"uplinkJitterMs\": {\n      \"@id\": \"amz:uplinkJitterMs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uplinkLossPercent\": {\n      \"@id\": \"amz:uplinkLossPercent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"value\": {\n      \"@id\": \"amz:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"amz:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"videoCapture\": {\n      \"@id\": \"amz:videoCapture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"videoEndpoint\": {\n      \"@id\": \"amz:videoEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcConfig\": {\n      \"@id\": \"amz:vpcConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpceConfigurationDescription\": {\n      \"@id\": \"amz:vpceConfigurationDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpceConfigurationName\": {\n      \"@id\": \"amz:vpceConfigurationName\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"vpceServiceName\": {\n      \"@id\": \"amz:vpceServiceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webUrl\": {\n      \"@id\": \"amz:webUrl\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-device-farm/refs/heads/main/json-ld/amazon-device-farm-context.jsonld
tags:
- Application Testing
- AWS
- Device Testing
- Mobile Testing
- Quality Assurance
- JSON-LD
- Linked Data
- Semantic Web
---
