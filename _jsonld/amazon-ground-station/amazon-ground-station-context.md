---
api_specs:
- filename: amazon-ground-station-openapi.yaml
  format: yaml
  label: AWS Ground Station API
  slug: aws-ground-station-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/openapi/amazon-ground-station-openapi.yaml
class_count: 114
classes:
- TagsMap
- GetMinuteUsageRequest
- ComponentVersion
- DemodulationConfig
- DescribeContactRequest
- ListEphemeridesResponse
- EphemerisMetaData
- ListSatellitesRequest
- UplinkEchoConfig
- CreateEphemerisRequest
- EndpointDetails
- GetAgentConfigurationResponse
- GetMissionProfileResponse
- Frequency
- RangedConnectionDetails
- AgentDetails
- ComponentStatusData
- DataflowEndpointGroupIdResponse
- UpdateAgentStatusResponse
- MissionProfileListItem
- GroundStationData
- Source
- CreateDataflowEndpointGroupRequest
- ContactIdResponse
- DeleteConfigRequest
- Elevation
- EphemerisItem
- ConfigIdResponse
- GetSatelliteResponse
- DataflowEndpointConfig
- ListContactsRequest
- ListGroundStationsResponse
- DescribeEphemerisResponse
- MissionProfileIdResponse
- OEMEphemeris
- DeleteDataflowEndpointGroupRequest
- ListTagsForResourceRequest
- ListDataflowEndpointGroupsRequest
- S3RecordingConfig
- SecurityDetails
- CreateConfigRequest
- GetAgentConfigurationRequest
- FrequencyBandwidth
- GetDataflowEndpointGroupResponse
- GetConfigRequest
- SocketAddress
- DescribeContactResponse
- RangedSocketAddress
- ListGroundStationsRequest
- UpdateMissionProfileRequest
- DecodeConfig
- ReserveContactRequest
- AntennaDownlinkDemodDecodeConfig
- EphemerisIdResponse
- GetSatelliteRequest
- SpectrumConfig
- TimeRange
- ConfigDetails
- AntennaDownlinkConfig
- UpdateConfigRequest
- RegisterAgentRequest
- Eirp
- UpdateEphemerisRequest
- EphemerisDescription
- UplinkSpectrumConfig
- RegisterAgentResponse
- ListConfigsRequest
- SatelliteListItem
- EphemerisTypeDescription
- TagResourceResponse
- DataflowEndpoint
- UntagResourceRequest
- AggregateStatus
- EphemerisData
- DeleteEphemerisRequest
- GetMinuteUsageResponse
- ListTagsForResourceResponse
- UntagResourceResponse
- UpdateAgentStatusRequest
- CreateMissionProfileRequest
- ListMissionProfilesRequest
- DescribeEphemerisRequest
- SignatureMap
- KmsKey
- S3Object
- ListEphemeridesRequest
- ListDataflowEndpointGroupsResponse
- GetDataflowEndpointGroupRequest
- AwsGroundStationAgentEndpoint
- TrackingConfig
- ListMissionProfilesResponse
- GetMissionProfileRequest
- CancelContactRequest
- S3RecordingDetails
- DataflowEndpointListItem
- ListConfigsResponse
- ConfigTypeData
- GetConfigResponse
- Destination
- ConnectionDetails
- ListContactsResponse
- ListSatellitesResponse
- TagResourceRequest
- DataflowDetail
- AntennaDemodDecodeDetails
- DeleteMissionProfileRequest
- IntegerRange
- DiscoveryData
- ConfigListItem
- TLEData
- ContactData
- AntennaUplinkConfig
- TLEEphemeris
- name
context_file: json-ld/amazon-ground-station-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/json-ld/amazon-ground-station-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ground Station from Amazon Ground Station.
layout: jsonld
name: Amazon Ground Station Context
namespaces:
- prefix: gs
  uri: https://aws.amazon.com/ground-station/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: month
  type: string
- container: ''
  name: year
  type: string
- container: ''
  name: componentType
  type: string
- container: ''
  name: versions
  type: string
- container: ''
  name: unvalidatedJSON
  type: string
- container: ''
  name: ephemerides
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: ephemerisId
  type: string
- container: ''
  name: epoch
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: antennaUplinkConfigArn
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: ephemeris
  type: string
- container: ''
  name: expirationTime
  type: string
- container: ''
  name: kmsKeyArn
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: satelliteId
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: awsGroundStationAgentEndpoint
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: healthReasons
  type: string
- container: ''
  name: healthStatus
  type: string
- container: ''
  name: securityDetails
  type: string
- container: ''
  name: agentId
  type: string
- container: ''
  name: taskingDocument
  type: string
- container: ''
  name: contactPostPassDurationSeconds
  type: string
- container: ''
  name: contactPrePassDurationSeconds
  type: string
- container: ''
  name: dataflowEdges
  type: string
- container: ''
  name: minimumViableContactDurationSeconds
  type: string
- container: ''
  name: missionProfileArn
  type: string
- container: ''
  name: missionProfileId
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: streamsKmsKey
  type: string
- container: ''
  name: streamsKmsRole
  type: string
- container: ''
  name: trackingConfigArn
  type: string
- container: ''
  name: units
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: mtu
  type: string
- container: ''
  name: socketAddress
  type: string
- container: ''
  name: agentCpuCores
  type: string
- container: ''
  name: agentVersion
  type: string
- container: ''
  name: componentVersions
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: instanceType
  type: string
- container: ''
  name: reservedCpuCores
  type: string
- container: ''
  name: bytesReceived
  type: string
- container: ''
  name: bytesSent
  type: string
- container: ''
  name: capabilityArn
  type: string
- container: ''
  name: dataflowId
  type: string
- container: ''
  name: packetsDropped
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: dataflowEndpointGroupId
  type: string
- container: ''
  name: groundStationId
  type: string
- container: ''
  name: groundStationName
  type: string
- container: ''
  name: configDetails
  type: string
- container: ''
  name: configId
  type: string
- container: ''
  name: configType
  type: string
- container: ''
  name: dataflowSourceRegion
  type: string
- container: ''
  name: endpointDetails
  type: string
- container: ''
  name: contactId
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: creationTime
  type: string
- container: ''
  name: sourceS3Object
  type: string
- container: ''
  name: configArn
  type: string
- container: ''
  name: currentEphemeris
  type: string
- container: ''
  name: groundStations
  type: string
- container: ''
  name: noradSatelliteID
  type: string
- container: ''
  name: satelliteArn
  type: string
- container: ''
  name: dataflowEndpointName
  type: string
- container: ''
  name: dataflowEndpointRegion
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: groundStation
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: statusList
  type: string
- container: ''
  name: groundStationList
  type: string
- container: ''
  name: invalidReason
  type: string
- container: ''
  name: suppliedData
  type: string
- container: ''
  name: oemData
  type: string
- container: ''
  name: s3Object
  type: string
- container: ''
  name: bucketArn
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: securityGroupIds
  type: string
- container: ''
  name: subnetIds
  type: string
- container: ''
  name: configData
  type: string
- container: ''
  name: dataflowEndpointGroupArn
  type: string
- container: ''
  name: endpointsDetails
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: contactStatus
  type: string
- container: ''
  name: dataflowList
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: maximumElevation
  type: string
- container: ''
  name: postPassEndTime
  type: string
- container: ''
  name: prePassStartTime
  type: string
- container: ''
  name: portRange
  type: string
- container: ''
  name: decodeConfig
  type: string
- container: ''
  name: demodulationConfig
  type: string
- container: ''
  name: spectrumConfig
  type: string
- container: ''
  name: bandwidth
  type: string
- container: ''
  name: centerFrequency
  type: string
- container: ''
  name: polarization
  type: string
- container: ''
  name: antennaDemodDecodeDetails
  type: string
- container: ''
  name: s3RecordingDetails
  type: string
- container: ''
  name: agentDetails
  type: string
- container: ''
  name: discoveryData
  type: string
- container: ''
  name: ephemerisData
  type: string
- container: ''
  name: oem
  type: string
- container: ''
  name: tle
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: signatureMap
  type: string
- container: ''
  name: estimatedMinutesRemaining
  type: string
- container: ''
  name: isReservedMinutesCustomer
  type: string
- container: ''
  name: totalReservedMinuteAllocation
  type: string
- container: ''
  name: totalScheduledMinutes
  type: string
- container: ''
  name: upcomingMinutesScheduled
  type: string
- container: ''
  name: aggregateStatus
  type: string
- container: ''
  name: componentStatuses
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: kmsAliasArn
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: dataflowEndpointGroupList
  type: string
- container: ''
  name: agentStatus
  type: string
- container: ''
  name: auditResults
  type: string
- container: ''
  name: egressAddress
  type: string
- container: ''
  name: ingressAddress
  type: string
- container: ''
  name: autotrack
  type: string
- container: ''
  name: missionProfileList
  type: string
- container: ''
  name: keyTemplate
  type: string
- container: ''
  name: configList
  type: string
- container: ''
  name: antennaDownlinkConfig
  type: string
- container: ''
  name: antennaDownlinkDemodDecodeConfig
  type: string
- container: ''
  name: antennaUplinkConfig
  type: string
- container: ''
  name: dataflowEndpointConfig
  type: string
- container: ''
  name: s3RecordingConfig
  type: string
- container: ''
  name: trackingConfig
  type: string
- container: ''
  name: uplinkEchoConfig
  type: string
- container: ''
  name: dataflowDestinationRegion
  type: string
- container: ''
  name: contactList
  type: string
- container: ''
  name: satellites
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: outputNode
  type: string
- container: ''
  name: maximum
  type: string
- container: ''
  name: minimum
  type: string
- container: ''
  name: capabilityArns
  type: string
- container: ''
  name: privateIpAddresses
  type: string
- container: ''
  name: publicIpAddresses
  type: string
- container: ''
  name: tleLine1
  type: string
- container: ''
  name: tleLine2
  type: string
- container: ''
  name: validTimeRange
  type: string
- container: ''
  name: targetEirp
  type: string
- container: ''
  name: transmitDisabled
  type: string
- container: ''
  name: tleData
  type: string
property_count: 155
provider_name: Amazon Ground Station
provider_slug: amazon-ground-station
slug: amazon-ground-station-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gs\": \"https://aws.amazon.com/ground-station/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TagsMap\": \"gs:TagsMap\",\n    \"GetMinuteUsageRequest\": \"gs:GetMinuteUsageRequest\",\n    \"ComponentVersion\": \"gs:ComponentVersion\",\n    \"DemodulationConfig\": \"gs:DemodulationConfig\",\n    \"DescribeContactRequest\": \"gs:DescribeContactRequest\",\n    \"ListEphemeridesResponse\": \"gs:ListEphemeridesResponse\",\n    \"EphemerisMetaData\": \"gs:EphemerisMetaData\",\n    \"ListSatellitesRequest\": \"gs:ListSatellitesRequest\",\n    \"UplinkEchoConfig\": \"gs:UplinkEchoConfig\",\n    \"CreateEphemerisRequest\": \"gs:CreateEphemerisRequest\",\n    \"EndpointDetails\": \"gs:EndpointDetails\",\n    \"GetAgentConfigurationResponse\": \"gs:GetAgentConfigurationResponse\",\n    \"GetMissionProfileResponse\": \"gs:GetMissionProfileResponse\",\n    \"Frequency\":\
  \ \"gs:Frequency\",\n    \"RangedConnectionDetails\": \"gs:RangedConnectionDetails\",\n    \"AgentDetails\": \"gs:AgentDetails\",\n    \"ComponentStatusData\": \"gs:ComponentStatusData\",\n    \"DataflowEndpointGroupIdResponse\": \"gs:DataflowEndpointGroupIdResponse\",\n    \"UpdateAgentStatusResponse\": \"gs:UpdateAgentStatusResponse\",\n    \"MissionProfileListItem\": \"gs:MissionProfileListItem\",\n    \"GroundStationData\": \"gs:GroundStationData\",\n    \"Source\": \"gs:Source\",\n    \"CreateDataflowEndpointGroupRequest\": \"gs:CreateDataflowEndpointGroupRequest\",\n    \"ContactIdResponse\": \"gs:ContactIdResponse\",\n    \"DeleteConfigRequest\": \"gs:DeleteConfigRequest\",\n    \"Elevation\": \"gs:Elevation\",\n    \"EphemerisItem\": \"gs:EphemerisItem\",\n    \"ConfigIdResponse\": \"gs:ConfigIdResponse\",\n    \"GetSatelliteResponse\": \"gs:GetSatelliteResponse\",\n    \"DataflowEndpointConfig\": \"gs:DataflowEndpointConfig\",\n    \"ListContactsRequest\": \"gs:ListContactsRequest\"\
  ,\n    \"ListGroundStationsResponse\": \"gs:ListGroundStationsResponse\",\n    \"DescribeEphemerisResponse\": \"gs:DescribeEphemerisResponse\",\n    \"MissionProfileIdResponse\": \"gs:MissionProfileIdResponse\",\n    \"OEMEphemeris\": \"gs:OEMEphemeris\",\n    \"DeleteDataflowEndpointGroupRequest\": \"gs:DeleteDataflowEndpointGroupRequest\",\n    \"ListTagsForResourceRequest\": \"gs:ListTagsForResourceRequest\",\n    \"ListDataflowEndpointGroupsRequest\": \"gs:ListDataflowEndpointGroupsRequest\",\n    \"S3RecordingConfig\": \"gs:S3RecordingConfig\",\n    \"SecurityDetails\": \"gs:SecurityDetails\",\n    \"CreateConfigRequest\": \"gs:CreateConfigRequest\",\n    \"GetAgentConfigurationRequest\": \"gs:GetAgentConfigurationRequest\",\n    \"FrequencyBandwidth\": \"gs:FrequencyBandwidth\",\n    \"GetDataflowEndpointGroupResponse\": \"gs:GetDataflowEndpointGroupResponse\",\n    \"GetConfigRequest\": \"gs:GetConfigRequest\",\n    \"SocketAddress\": \"gs:SocketAddress\",\n    \"DescribeContactResponse\"\
  : \"gs:DescribeContactResponse\",\n    \"RangedSocketAddress\": \"gs:RangedSocketAddress\",\n    \"ListGroundStationsRequest\": \"gs:ListGroundStationsRequest\",\n    \"UpdateMissionProfileRequest\": \"gs:UpdateMissionProfileRequest\",\n    \"DecodeConfig\": \"gs:DecodeConfig\",\n    \"ReserveContactRequest\": \"gs:ReserveContactRequest\",\n    \"AntennaDownlinkDemodDecodeConfig\": \"gs:AntennaDownlinkDemodDecodeConfig\",\n    \"EphemerisIdResponse\": \"gs:EphemerisIdResponse\",\n    \"GetSatelliteRequest\": \"gs:GetSatelliteRequest\",\n    \"SpectrumConfig\": \"gs:SpectrumConfig\",\n    \"TimeRange\": \"gs:TimeRange\",\n    \"ConfigDetails\": \"gs:ConfigDetails\",\n    \"AntennaDownlinkConfig\": \"gs:AntennaDownlinkConfig\",\n    \"UpdateConfigRequest\": \"gs:UpdateConfigRequest\",\n    \"RegisterAgentRequest\": \"gs:RegisterAgentRequest\",\n    \"Eirp\": \"gs:Eirp\",\n    \"UpdateEphemerisRequest\": \"gs:UpdateEphemerisRequest\",\n    \"EphemerisDescription\": \"gs:EphemerisDescription\"\
  ,\n    \"UplinkSpectrumConfig\": \"gs:UplinkSpectrumConfig\",\n    \"RegisterAgentResponse\": \"gs:RegisterAgentResponse\",\n    \"ListConfigsRequest\": \"gs:ListConfigsRequest\",\n    \"SatelliteListItem\": \"gs:SatelliteListItem\",\n    \"EphemerisTypeDescription\": \"gs:EphemerisTypeDescription\",\n    \"TagResourceResponse\": \"gs:TagResourceResponse\",\n    \"DataflowEndpoint\": \"gs:DataflowEndpoint\",\n    \"UntagResourceRequest\": \"gs:UntagResourceRequest\",\n    \"AggregateStatus\": \"gs:AggregateStatus\",\n    \"EphemerisData\": \"gs:EphemerisData\",\n    \"DeleteEphemerisRequest\": \"gs:DeleteEphemerisRequest\",\n    \"GetMinuteUsageResponse\": \"gs:GetMinuteUsageResponse\",\n    \"ListTagsForResourceResponse\": \"gs:ListTagsForResourceResponse\",\n    \"UntagResourceResponse\": \"gs:UntagResourceResponse\",\n    \"UpdateAgentStatusRequest\": \"gs:UpdateAgentStatusRequest\",\n    \"CreateMissionProfileRequest\": \"gs:CreateMissionProfileRequest\",\n    \"ListMissionProfilesRequest\"\
  : \"gs:ListMissionProfilesRequest\",\n    \"DescribeEphemerisRequest\": \"gs:DescribeEphemerisRequest\",\n    \"SignatureMap\": \"gs:SignatureMap\",\n    \"KmsKey\": \"gs:KmsKey\",\n    \"S3Object\": \"gs:S3Object\",\n    \"ListEphemeridesRequest\": \"gs:ListEphemeridesRequest\",\n    \"ListDataflowEndpointGroupsResponse\": \"gs:ListDataflowEndpointGroupsResponse\",\n    \"GetDataflowEndpointGroupRequest\": \"gs:GetDataflowEndpointGroupRequest\",\n    \"AwsGroundStationAgentEndpoint\": \"gs:AwsGroundStationAgentEndpoint\",\n    \"TrackingConfig\": \"gs:TrackingConfig\",\n    \"ListMissionProfilesResponse\": \"gs:ListMissionProfilesResponse\",\n    \"GetMissionProfileRequest\": \"gs:GetMissionProfileRequest\",\n    \"CancelContactRequest\": \"gs:CancelContactRequest\",\n    \"S3RecordingDetails\": \"gs:S3RecordingDetails\",\n    \"DataflowEndpointListItem\": \"gs:DataflowEndpointListItem\",\n    \"ListConfigsResponse\": \"gs:ListConfigsResponse\",\n    \"ConfigTypeData\": \"gs:ConfigTypeData\"\
  ,\n    \"GetConfigResponse\": \"gs:GetConfigResponse\",\n    \"Destination\": \"gs:Destination\",\n    \"ConnectionDetails\": \"gs:ConnectionDetails\",\n    \"ListContactsResponse\": \"gs:ListContactsResponse\",\n    \"ListSatellitesResponse\": \"gs:ListSatellitesResponse\",\n    \"TagResourceRequest\": \"gs:TagResourceRequest\",\n    \"DataflowDetail\": \"gs:DataflowDetail\",\n    \"AntennaDemodDecodeDetails\": \"gs:AntennaDemodDecodeDetails\",\n    \"DeleteMissionProfileRequest\": \"gs:DeleteMissionProfileRequest\",\n    \"IntegerRange\": \"gs:IntegerRange\",\n    \"DiscoveryData\": \"gs:DiscoveryData\",\n    \"ConfigListItem\": \"gs:ConfigListItem\",\n    \"TLEData\": \"gs:TLEData\",\n    \"ContactData\": \"gs:ContactData\",\n    \"AntennaUplinkConfig\": \"gs:AntennaUplinkConfig\",\n    \"TLEEphemeris\": \"gs:TLEEphemeris\",\n    \"month\": {\n      \"@id\": \"gs:month\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"gs:year\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"componentType\": {\n      \"@id\": \"gs:componentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"gs:versions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unvalidatedJSON\": {\n      \"@id\": \"gs:unvalidatedJSON\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ephemerides\": {\n      \"@id\": \"gs:ephemerides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"gs:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ephemerisId\": {\n      \"@id\": \"gs:ephemerisId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"epoch\": {\n      \"@id\": \"gs:epoch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"source\": {\n      \"@id\": \"gs:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antennaUplinkConfigArn\": {\n      \"@id\": \"gs:antennaUplinkConfigArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"gs:enabled\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ephemeris\": {\n      \"@id\": \"gs:ephemeris\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationTime\": {\n      \"@id\": \"gs:expirationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyArn\": {\n      \"@id\": \"gs:kmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"gs:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"satelliteId\": {\n      \"@id\": \"gs:satelliteId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"gs:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsGroundStationAgentEndpoint\": {\n      \"@id\": \"gs:awsGroundStationAgentEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"gs:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthReasons\": {\n      \"@id\": \"gs:healthReasons\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthStatus\": {\n      \"@id\"\
  : \"gs:healthStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityDetails\": {\n      \"@id\": \"gs:securityDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentId\": {\n      \"@id\": \"gs:agentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskingDocument\": {\n      \"@id\": \"gs:taskingDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactPostPassDurationSeconds\": {\n      \"@id\": \"gs:contactPostPassDurationSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactPrePassDurationSeconds\": {\n      \"@id\": \"gs:contactPrePassDurationSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowEdges\": {\n      \"@id\": \"gs:dataflowEdges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumViableContactDurationSeconds\": {\n      \"@id\": \"gs:minimumViableContactDurationSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"missionProfileArn\": {\n      \"@id\": \"gs:missionProfileArn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"missionProfileId\": {\n      \"@id\": \"gs:missionProfileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"gs:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamsKmsKey\": {\n      \"@id\": \"gs:streamsKmsKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamsKmsRole\": {\n      \"@id\": \"gs:streamsKmsRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingConfigArn\": {\n      \"@id\": \"gs:trackingConfigArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"gs:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"gs:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mtu\": {\n      \"@id\": \"gs:mtu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socketAddress\": {\n      \"@id\": \"gs:socketAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentCpuCores\": {\n      \"@id\": \"gs:agentCpuCores\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"agentVersion\": {\n      \"@id\": \"gs:agentVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentVersions\": {\n      \"@id\": \"gs:componentVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"gs:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceType\": {\n      \"@id\": \"gs:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reservedCpuCores\": {\n      \"@id\": \"gs:reservedCpuCores\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bytesReceived\": {\n      \"@id\": \"gs:bytesReceived\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bytesSent\": {\n      \"@id\": \"gs:bytesSent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilityArn\": {\n      \"@id\": \"gs:capabilityArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowId\": {\n      \"@id\": \"gs:dataflowId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packetsDropped\": {\n      \"@id\": \"gs:packetsDropped\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"gs:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowEndpointGroupId\": {\n      \"@id\": \"gs:dataflowEndpointGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundStationId\": {\n      \"@id\": \"gs:groundStationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundStationName\": {\n      \"@id\": \"gs:groundStationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configDetails\": {\n      \"@id\": \"gs:configDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configId\": {\n      \"@id\": \"gs:configId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configType\": {\n      \"@id\": \"gs:configType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowSourceRegion\": {\n      \"@id\": \"gs:dataflowSourceRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointDetails\": {\n      \"@id\": \"gs:endpointDetails\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"contactId\": {\n      \"@id\": \"gs:contactId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"gs:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"gs:creationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceS3Object\": {\n      \"@id\": \"gs:sourceS3Object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configArn\": {\n      \"@id\": \"gs:configArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentEphemeris\": {\n      \"@id\": \"gs:currentEphemeris\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundStations\": {\n      \"@id\": \"gs:groundStations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"noradSatelliteID\": {\n      \"@id\": \"gs:noradSatelliteID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"satelliteArn\": {\n      \"@id\": \"gs:satelliteArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowEndpointName\": {\n      \"@id\": \"gs:dataflowEndpointName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowEndpointRegion\": {\n      \"@id\": \"gs:dataflowEndpointRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"gs:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundStation\": {\n      \"@id\": \"gs:groundStation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"gs:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"gs:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusList\": {\n      \"@id\": \"gs:statusList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundStationList\": {\n      \"@id\": \"gs:groundStationList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidReason\": {\n      \"@id\": \"gs:invalidReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suppliedData\": {\n      \"@id\": \"gs:suppliedData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oemData\": {\n\
  \      \"@id\": \"gs:oemData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Object\": {\n      \"@id\": \"gs:s3Object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketArn\": {\n      \"@id\": \"gs:bucketArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"gs:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"gs:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"gs:securityGroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"gs:subnetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configData\": {\n      \"@id\": \"gs:configData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowEndpointGroupArn\": {\n      \"@id\": \"gs:dataflowEndpointGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointsDetails\": {\n      \"@id\": \"gs:endpointsDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  port\": {\n      \"@id\": \"gs:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactStatus\": {\n      \"@id\": \"gs:contactStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowList\": {\n      \"@id\": \"gs:dataflowList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"gs:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumElevation\": {\n      \"@id\": \"gs:maximumElevation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postPassEndTime\": {\n      \"@id\": \"gs:postPassEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prePassStartTime\": {\n      \"@id\": \"gs:prePassStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portRange\": {\n      \"@id\": \"gs:portRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decodeConfig\": {\n      \"@id\": \"gs:decodeConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"demodulationConfig\": {\n      \"@id\": \"gs:demodulationConfig\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"spectrumConfig\": {\n      \"@id\": \"gs:spectrumConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bandwidth\": {\n      \"@id\": \"gs:bandwidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"centerFrequency\": {\n      \"@id\": \"gs:centerFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"polarization\": {\n      \"@id\": \"gs:polarization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antennaDemodDecodeDetails\": {\n      \"@id\": \"gs:antennaDemodDecodeDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3RecordingDetails\": {\n      \"@id\": \"gs:s3RecordingDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentDetails\": {\n      \"@id\": \"gs:agentDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discoveryData\": {\n      \"@id\": \"gs:discoveryData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ephemerisData\": {\n      \"@id\": \"gs:ephemerisData\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"oem\": {\n      \"@id\": \"gs:oem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tle\": {\n      \"@id\": \"gs:tle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"gs:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatureMap\": {\n      \"@id\": \"gs:signatureMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedMinutesRemaining\": {\n      \"@id\": \"gs:estimatedMinutesRemaining\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isReservedMinutesCustomer\": {\n      \"@id\": \"gs:isReservedMinutesCustomer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalReservedMinuteAllocation\": {\n      \"@id\": \"gs:totalReservedMinuteAllocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalScheduledMinutes\": {\n      \"@id\": \"gs:totalScheduledMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upcomingMinutesScheduled\": {\n      \"@id\": \"gs:upcomingMinutesScheduled\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"aggregateStatus\": {\n      \"@id\": \"gs:aggregateStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentStatuses\": {\n      \"@id\": \"gs:componentStatuses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"gs:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsAliasArn\": {\n      \"@id\": \"gs:kmsAliasArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"gs:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"gs:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"gs:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowEndpointGroupList\": {\n      \"@id\": \"gs:dataflowEndpointGroupList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentStatus\": {\n      \"@id\": \"gs:agentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auditResults\": {\n      \"@id\": \"gs:auditResults\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"egressAddress\": {\n      \"@id\": \"gs:egressAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingressAddress\": {\n      \"@id\": \"gs:ingressAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autotrack\": {\n      \"@id\": \"gs:autotrack\",\n      \"@type\": \"xsd:string\"\n    },\n    \"missionProfileList\": {\n      \"@id\": \"gs:missionProfileList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyTemplate\": {\n      \"@id\": \"gs:keyTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configList\": {\n      \"@id\": \"gs:configList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antennaDownlinkConfig\": {\n      \"@id\": \"gs:antennaDownlinkConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antennaDownlinkDemodDecodeConfig\": {\n      \"@id\": \"gs:antennaDownlinkDemodDecodeConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antennaUplinkConfig\": {\n      \"@id\": \"gs:antennaUplinkConfig\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"dataflowEndpointConfig\": {\n      \"@id\": \"gs:dataflowEndpointConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3RecordingConfig\": {\n      \"@id\": \"gs:s3RecordingConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingConfig\": {\n      \"@id\": \"gs:trackingConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uplinkEchoConfig\": {\n      \"@id\": \"gs:uplinkEchoConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataflowDestinationRegion\": {\n      \"@id\": \"gs:dataflowDestinationRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactList\": {\n      \"@id\": \"gs:contactList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"satellites\": {\n      \"@id\": \"gs:satellites\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"gs:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputNode\": {\n      \"@id\": \"gs:outputNode\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"maximum\": {\n      \"@id\": \"gs:maximum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimum\": {\n      \"@id\": \"gs:minimum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilityArns\": {\n      \"@id\": \"gs:capabilityArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateIpAddresses\": {\n      \"@id\": \"gs:privateIpAddresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicIpAddresses\": {\n      \"@id\": \"gs:publicIpAddresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tleLine1\": {\n      \"@id\": \"gs:tleLine1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tleLine2\": {\n      \"@id\": \"gs:tleLine2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validTimeRange\": {\n      \"@id\": \"gs:validTimeRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetEirp\": {\n      \"@id\": \"gs:targetEirp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transmitDisabled\": {\n      \"@id\": \"gs:transmitDisabled\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"tleData\": {\n      \"@id\": \"gs:tleData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/json-ld/amazon-ground-station-context.jsonld
tags:
- AWS
- Data Processing
- IoT
- Satellite Communications
- Space Technology
- JSON-LD
- Linked Data
- Semantic Web
---
