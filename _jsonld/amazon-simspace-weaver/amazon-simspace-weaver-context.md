---
api_specs:
- filename: amazon-simspace-weaver.yaml
  format: yaml
  label: AWS SimSpace Weaver API
  slug: aws-simspace-weaver-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/openapi/amazon-simspace-weaver.yaml
class_count: 43
classes:
- StartAppInput
- ListTagsForResourceOutput
- StopClockInput
- ListSimulationsInput
- SimulationMetadata
- CreateSnapshotInput
- DeleteSimulationInput
- StartSimulationInput
- TagMap
- TagResourceInput
- DeleteAppInput
- SimulationClock
- DescribeSimulationOutput
- CreateSnapshotOutput
- ListAppsInput
- StartClockInput
- StartSimulationOutput
- UntagResourceOutput
- StopSimulationOutput
- SimulationAppPortMapping
- SimulationAppMetadata
- StartClockOutput
- SimulationAppEndpointInfo
- DeleteSimulationOutput
- DeleteAppOutput
- StopClockOutput
- StartAppOutput
- StopAppOutput
- LogDestination
- ListAppsOutput
- ListSimulationsOutput
- StopSimulationInput
- TagResourceOutput
- DescribeAppOutput
- S3Destination
- UntagResourceInput
- S3Location
- DescribeAppInput
- StopAppInput
- DescribeSimulationInput
- ListTagsForResourceInput
- Description
- Name
context_file: json-ld/amazon-simspace-weaver-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/json-ld/amazon-simspace-weaver-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Simspace Weaver from Amazon SimSpace Weaver.
layout: jsonld
name: Amazon Simspace Weaver Context
namespaces:
- prefix: aws
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: CloudWatchLogsLogGroup
  type: string
- container: ''
  name: LiveSimulationState
  type: string
- container: ''
  name: Domain
  type: string
- container: ''
  name: LoggingConfiguration
  type: string
- container: ''
  name: LaunchOverrides
  type: string
- container: ''
  name: LogGroupArn
  type: string
- container: ''
  name: Clocks
  type: string
- container: ''
  name: Domains
  type: string
- container: ''
  name: ClientToken
  type: string
- container: ''
  name: Simulation
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: CreationTime
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: TargetStatus
  type: string
- container: ''
  name: Destination
  type: string
- container: ''
  name: MaximumDuration
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: SchemaS3Location
  type: string
- container: ''
  name: SnapshotS3Location
  type: string
- container: ''
  name: ExecutionId
  type: string
- container: ''
  name: SchemaError
  type: string
- container: ''
  name: StartError
  type: string
- container: ''
  name: Lifecycle
  type: string
- container: ''
  name: Actual
  type: string
- container: ''
  name: Declared
  type: string
- container: ''
  name: Address
  type: string
- container: ''
  name: IngressPortMappings
  type: string
- container: ''
  name: Apps
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Simulations
  type: string
- container: ''
  name: Destinations
  type: string
- container: ''
  name: EndpointInfo
  type: string
- container: ''
  name: LaunchCommands
  type: string
- container: ''
  name: BucketName
  type: string
- container: ''
  name: ObjectKeyPrefix
  type: string
- container: ''
  name: ObjectKey
  type: string
- container: ''
  name: App
  type: string
property_count: 38
provider_name: Amazon SimSpace Weaver
provider_slug: amazon-simspace-weaver
slug: amazon-simspace-weaver-context
source_filename: amazon-simspace-weaver-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CloudWatchLogsLogGroup\": {\n      \"@id\": \"aws:CloudWatchLogsLogGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LiveSimulationState\": {\n      \"@id\": \"aws:LiveSimulationState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartAppInput\": \"aws:StartAppInput\",\n    \"ListTagsForResourceOutput\": \"aws:ListTagsForResourceOutput\",\n    \"StopClockInput\": \"aws:StopClockInput\",\n    \"ListSimulationsInput\": \"aws:ListSimulationsInput\",\n    \"SimulationMetadata\": \"aws:SimulationMetadata\",\n    \"CreateSnapshotInput\": \"aws:CreateSnapshotInput\",\n    \"DeleteSimulationInput\": \"aws:DeleteSimulationInput\",\n    \"StartSimulationInput\": \"aws:StartSimulationInput\",\n    \"TagMap\": \"aws:TagMap\",\n    \"\
  TagResourceInput\": \"aws:TagResourceInput\",\n    \"DeleteAppInput\": \"aws:DeleteAppInput\",\n    \"SimulationClock\": \"aws:SimulationClock\",\n    \"DescribeSimulationOutput\": \"aws:DescribeSimulationOutput\",\n    \"CreateSnapshotOutput\": \"aws:CreateSnapshotOutput\",\n    \"ListAppsInput\": \"aws:ListAppsInput\",\n    \"Domain\": {\n      \"@id\": \"aws:Domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartClockInput\": \"aws:StartClockInput\",\n    \"StartSimulationOutput\": \"aws:StartSimulationOutput\",\n    \"UntagResourceOutput\": \"aws:UntagResourceOutput\",\n    \"StopSimulationOutput\": \"aws:StopSimulationOutput\",\n    \"SimulationAppPortMapping\": \"aws:SimulationAppPortMapping\",\n    \"SimulationAppMetadata\": \"aws:SimulationAppMetadata\",\n    \"StartClockOutput\": \"aws:StartClockOutput\",\n    \"SimulationAppEndpointInfo\": \"aws:SimulationAppEndpointInfo\",\n    \"DeleteSimulationOutput\": \"aws:DeleteSimulationOutput\",\n    \"DeleteAppOutput\": \"aws:DeleteAppOutput\"\
  ,\n    \"StopClockOutput\": \"aws:StopClockOutput\",\n    \"StartAppOutput\": \"aws:StartAppOutput\",\n    \"StopAppOutput\": \"aws:StopAppOutput\",\n    \"LogDestination\": \"aws:LogDestination\",\n    \"ListAppsOutput\": \"aws:ListAppsOutput\",\n    \"ListSimulationsOutput\": \"aws:ListSimulationsOutput\",\n    \"StopSimulationInput\": \"aws:StopSimulationInput\",\n    \"LoggingConfiguration\": {\n      \"@id\": \"aws:LoggingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceOutput\": \"aws:TagResourceOutput\",\n    \"DescribeAppOutput\": \"aws:DescribeAppOutput\",\n    \"LaunchOverrides\": {\n      \"@id\": \"aws:LaunchOverrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Destination\": \"aws:S3Destination\",\n    \"UntagResourceInput\": \"aws:UntagResourceInput\",\n    \"S3Location\": \"aws:S3Location\",\n    \"DescribeAppInput\": \"aws:DescribeAppInput\",\n    \"StopAppInput\": \"aws:StopAppInput\",\n    \"DescribeSimulationInput\": \"aws:DescribeSimulationInput\"\
  ,\n    \"ListTagsForResourceInput\": \"aws:ListTagsForResourceInput\",\n    \"LogGroupArn\": {\n      \"@id\": \"aws:LogGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Clocks\": {\n      \"@id\": \"aws:Clocks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Domains\": {\n      \"@id\": \"aws:Domains\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientToken\": {\n      \"@id\": \"aws:ClientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": \"schema:description\",\n    \"Name\": \"schema:name\",\n    \"Simulation\": {\n      \"@id\": \"aws:Simulation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"aws:CreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"aws:Status\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"TargetStatus\": {\n      \"@id\": \"aws:TargetStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Destination\": {\n      \"@id\": \"aws:Destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumDuration\": {\n      \"@id\": \"aws:MaximumDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"aws:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaS3Location\": {\n      \"@id\": \"aws:SchemaS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnapshotS3Location\": {\n      \"@id\": \"aws:SnapshotS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExecutionId\": {\n      \"@id\": \"aws:ExecutionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaError\": {\n      \"@id\": \"aws:SchemaError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartError\": {\n      \"@id\": \"aws:StartError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Lifecycle\": {\n      \"@id\": \"aws:Lifecycle\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Actual\": {\n      \"@id\": \"aws:Actual\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Declared\": {\n      \"@id\": \"aws:Declared\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Address\": {\n      \"@id\": \"aws:Address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IngressPortMappings\": {\n      \"@id\": \"aws:IngressPortMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Apps\": {\n      \"@id\": \"aws:Apps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Simulations\": {\n      \"@id\": \"aws:Simulations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Destinations\": {\n      \"@id\": \"aws:Destinations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointInfo\": {\n      \"@id\": \"aws:EndpointInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchCommands\": {\n      \"@id\": \"aws:LaunchCommands\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"BucketName\": {\n      \"@id\": \"aws:BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObjectKeyPrefix\": {\n      \"@id\": \"aws:ObjectKeyPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObjectKey\": {\n      \"@id\": \"aws:ObjectKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"App\": {\n      \"@id\": \"aws:App\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/json-ld/amazon-simspace-weaver-context.jsonld
tags:
- Defense
- Digital Twin
- Simulation
- Spatial Simulation
- JSON-LD
- Linked Data
- Semantic Web
---
