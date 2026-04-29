---
api_specs:
- filename: amazon-fargate-openapi.yml
  format: yaml
  label: Amazon Fargate API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fargate/refs/heads/main/openapi/amazon-fargate-openapi.yml
class_count: 18
classes:
- PortMapping
- LogConfiguration
- KeyValuePair
- name
- LoadBalancer
- TaskDefinition
- Tag
- AccountSetting
- Failure
- NetworkConfiguration
- Amazon Fargate Task
- createdAt
- Service
- AwsVpcConfiguration
- ClusterSetting
- ContainerDefinition
- Cluster
- Task
context_file: json-ld/amazon-fargate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-fargate/refs/heads/main/json-ld/amazon-fargate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Fargate from Amazon Fargate.
layout: jsonld
name: Amazon Fargate Context
namespaces:
- prefix: fargate
  uri: https://aws.amazon.com/fargate/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: containerPort
  type: integer
- container: ''
  name: hostPort
  type: integer
- container: ''
  name: protocol
  type: string
- container: ''
  name: logDriver
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: targetGroupArn
  type: string
- container: ''
  name: loadBalancerName
  type: string
- container: ''
  name: containerName
  type: string
- container: ''
  name: taskDefinitionArn
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
- container: set
  name: requiresCompatibilities
  type: string
- container: ''
  name: networkMode
  type: string
- container: ''
  name: cpu
  type: string
- container: ''
  name: memory
  type: string
- container: ''
  name: executionRoleArn
  type: string
- container: ''
  name: taskRoleArn
  type: string
- container: set
  name: containerDefinitions
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: principalArn
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: awsvpcConfiguration
  type: string
- container: ''
  name: taskArn
  type: string
- container: ''
  name: clusterArn
  type: string
- container: ''
  name: launchType
  type: string
- container: ''
  name: lastStatus
  type: string
- container: ''
  name: desiredStatus
  type: string
- container: set
  name: containers
  type: reference
- container: ''
  name: containerArn
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: platformVersion
  type: string
- container: set
  name: tags
  type: reference
- container: ''
  name: serviceArn
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: taskDefinition
  type: string
- container: ''
  name: desiredCount
  type: integer
- container: ''
  name: runningCount
  type: integer
- container: ''
  name: pendingCount
  type: integer
- container: ''
  name: networkConfiguration
  type: string
- container: set
  name: loadBalancers
  type: string
- container: set
  name: subnets
  type: string
- container: set
  name: securityGroups
  type: string
- container: ''
  name: assignPublicIp
  type: string
- container: ''
  name: essential
  type: boolean
- container: set
  name: environment
  type: string
- container: set
  name: portMappings
  type: string
- container: ''
  name: logConfiguration
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: registeredContainerInstancesCount
  type: integer
- container: ''
  name: runningTasksCount
  type: integer
- container: ''
  name: pendingTasksCount
  type: integer
- container: ''
  name: activeServicesCount
  type: integer
- container: set
  name: settings
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: stoppedAt
  type: dateTime
- container: ''
  name: stoppedReason
  type: string
- container: set
  name: networkInterfaces
  type: reference
property_count: 61
provider_name: Amazon Fargate
provider_slug: amazon-fargate
slug: amazon-fargate-context
source_filename: amazon-fargate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fargate\": \"https://aws.amazon.com/fargate/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PortMapping\": \"fargate:PortMapping\",\n    \"containerPort\": {\n      \"@id\": \"fargate:containerPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostPort\": {\n      \"@id\": \"fargate:hostPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocol\": {\n      \"@id\": \"fargate:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogConfiguration\": \"fargate:LogConfiguration\",\n    \"logDriver\": {\n      \"@id\": \"fargate:logDriver\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"fargate:options\",\n      \"@type\": \"@id\"\n    },\n    \"KeyValuePair\": \"fargate:KeyValuePair\",\n    \"name\": \"schema:name\",\n    \"value\": {\n      \"@id\": \"fargate:value\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBalancer\": \"fargate:LoadBalancer\",\n    \"targetGroupArn\": {\n      \"@id\": \"fargate:targetGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loadBalancerName\": {\n      \"@id\": \"fargate:loadBalancerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerName\": {\n      \"@id\": \"fargate:containerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskDefinition\": \"fargate:TaskDefinition\",\n    \"taskDefinitionArn\": {\n      \"@id\": \"fargate:taskDefinitionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"family\": {\n      \"@id\": \"fargate:family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"fargate:revision\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"fargate:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiresCompatibilities\": {\n      \"@id\": \"fargate:requiresCompatibilities\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkMode\": {\n      \"@id\": \"fargate:networkMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpu\": {\n      \"@id\": \"fargate:cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memory\": {\n      \"@id\": \"fargate:memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionRoleArn\": {\n      \"@id\": \"fargate:executionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskRoleArn\": {\n      \"@id\": \"fargate:taskRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerDefinitions\": {\n      \"@id\": \"fargate:containerDefinitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tag\": \"fargate:Tag\",\n    \"key\": {\n      \"@id\": \"fargate:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountSetting\": \"fargate:AccountSetting\",\n    \"principalArn\": {\n      \"@id\": \"fargate:principalArn\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"Failure\": \"fargate:Failure\",\n    \"arn\": {\n      \"@id\": \"fargate:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"fargate:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"fargate:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkConfiguration\": \"fargate:NetworkConfiguration\",\n    \"awsvpcConfiguration\": {\n      \"@id\": \"fargate:awsvpcConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Amazon Fargate Task\": \"fargate:Amazon Fargate Task\",\n    \"taskArn\": {\n      \"@id\": \"fargate:taskArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterArn\": {\n      \"@id\": \"fargate:clusterArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchType\": {\n      \"@id\": \"fargate:launchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastStatus\": {\n      \"@id\": \"fargate:lastStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"desiredStatus\"\
  : {\n      \"@id\": \"fargate:desiredStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containers\": {\n      \"@id\": \"fargate:containers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"containerArn\": {\n      \"@id\": \"fargate:containerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"fargate:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformVersion\": {\n      \"@id\": \"fargate:platformVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"tags\": {\n      \"@id\": \"fargate:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Service\": \"fargate:Service\",\n    \"serviceArn\": {\n      \"@id\": \"fargate:serviceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"fargate:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskDefinition\": {\n      \"@id\": \"fargate:taskDefinition\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"desiredCount\": {\n      \"@id\": \"fargate:desiredCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runningCount\": {\n      \"@id\": \"fargate:runningCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pendingCount\": {\n      \"@id\": \"fargate:pendingCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"networkConfiguration\": {\n      \"@id\": \"fargate:networkConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loadBalancers\": {\n      \"@id\": \"fargate:loadBalancers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AwsVpcConfiguration\": \"fargate:AwsVpcConfiguration\",\n    \"subnets\": {\n      \"@id\": \"fargate:subnets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroups\": {\n      \"@id\": \"fargate:securityGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignPublicIp\"\
  : {\n      \"@id\": \"fargate:assignPublicIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterSetting\": \"fargate:ClusterSetting\",\n    \"ContainerDefinition\": \"fargate:ContainerDefinition\",\n    \"essential\": {\n      \"@id\": \"fargate:essential\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"environment\": {\n      \"@id\": \"fargate:environment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portMappings\": {\n      \"@id\": \"fargate:portMappings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logConfiguration\": {\n      \"@id\": \"fargate:logConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Cluster\": \"fargate:Cluster\",\n    \"clusterName\": {\n      \"@id\": \"fargate:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registeredContainerInstancesCount\": {\n      \"@id\": \"fargate:registeredContainerInstancesCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"runningTasksCount\": {\n      \"@id\": \"fargate:runningTasksCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pendingTasksCount\": {\n      \"@id\": \"fargate:pendingTasksCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activeServicesCount\": {\n      \"@id\": \"fargate:activeServicesCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"settings\": {\n      \"@id\": \"fargate:settings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Task\": \"fargate:Task\",\n    \"startedAt\": {\n      \"@id\": \"fargate:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"stoppedAt\": {\n      \"@id\": \"fargate:stoppedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"stoppedReason\": {\n      \"@id\": \"fargate:stoppedReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterfaces\": {\n      \"@id\": \"fargate:networkInterfaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-fargate/refs/heads/main/json-ld/amazon-fargate-context.jsonld
tags:
- AWS
- Compute
- Containers
- ECS
- EKS
- Microservices
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
