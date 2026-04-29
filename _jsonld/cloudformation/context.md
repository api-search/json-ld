---
api_specs:
- filename: cloudformation-api.yml
  format: yaml
  label: AWS CloudFormation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/openapi/cloudformation-api.yml
- filename: cloud-control-api.yml
  format: yaml
  label: AWS Cloud Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/openapi/cloud-control-api.yml
class_count: 0
classes: []
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from AWS CloudFormation.
layout: jsonld
name: context Context
namespaces:
- prefix: aws
  uri: https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/
- prefix: awscc
  uri: https://docs.aws.amazon.com/cloudcontrolapi/latest/APIReference/
- prefix: cfn
  uri: https://schemas.api.aws/cloudformation/
properties:
- container: ''
  name: Stack
  type: schema:SoftwareApplication
- container: ''
  name: Template
  type: schema:SoftwareSourceCode
- container: ''
  name: Resource
  type: schema:Thing
- container: ''
  name: ChangeSet
  type: schema:UpdateAction
- container: ''
  name: CloudControlResource
  type: schema:Thing
- container: ''
  name: ProgressEvent
  type: schema:Action
- container: ''
  name: Tag
  type: schema:DefinedTerm
- container: ''
  name: Output
  type: schema:PropertyValue
property_count: 8
provider_name: AWS CloudFormation
provider_slug: cloudformation
slug: context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/\",\n    \"awscc\": \"https://docs.aws.amazon.com/cloudcontrolapi/latest/APIReference/\",\n    \"cfn\": \"https://schemas.api.aws/cloudformation/\",\n\n    \"Stack\": {\n      \"@id\": \"cfn:Stack\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"StackId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"schema:Text\"\n        },\n        \"StackName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"schema:Text\"\n        },\n        \"StackStatus\": {\n          \"@id\": \"cfn:stackStatus\",\n          \"@type\": \"schema:Text\"\n        },\n        \"CreationTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\
  \n        },\n        \"LastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"DeletionTime\": {\n          \"@id\": \"cfn:deletionTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"StackStatusReason\": {\n          \"@id\": \"cfn:statusReason\",\n          \"@type\": \"schema:Text\"\n        },\n        \"RoleARN\": {\n          \"@id\": \"cfn:roleArn\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@type\": \"schema:DefinedTerm\"\n        },\n        \"Outputs\": {\n          \"@id\": \"cfn:outputs\",\n          \"@type\": \"schema:PropertyValue\"\n        },\n        \"Parameters\": {\n          \"@id\": \"cfn:parameters\",\n          \"@type\": \"schema:PropertyValue\"\n        },\n        \"Capabilities\": {\n          \"@id\": \"cfn:capabilities\",\n          \"@type\": \"schema:Text\"\n        },\n      \
  \  \"EnableTerminationProtection\": {\n          \"@id\": \"cfn:terminationProtection\",\n          \"@type\": \"schema:Boolean\"\n        },\n        \"ParentId\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"RootId\": {\n          \"@id\": \"cfn:rootStack\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Template\": {\n      \"@id\": \"cfn:Template\",\n      \"@type\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"AWSTemplateFormatVersion\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Resources\": {\n          \"@id\": \"schema:hasPart\",\n          \"@type\": \"cfn:Resource\"\n        },\n        \"Parameters\": {\n          \"@id\": \"cfn:parameters\",\n          \"@type\": \"schema:PropertyValue\"\n        },\n   \
  \     \"Outputs\": {\n          \"@id\": \"cfn:outputs\",\n          \"@type\": \"schema:PropertyValue\"\n        },\n        \"Mappings\": {\n          \"@id\": \"cfn:mappings\",\n          \"@type\": \"schema:StructuredValue\"\n        },\n        \"Conditions\": {\n          \"@id\": \"cfn:conditions\",\n          \"@type\": \"schema:StructuredValue\"\n        },\n        \"Transform\": {\n          \"@id\": \"cfn:transform\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Metadata\": {\n          \"@id\": \"cfn:metadata\",\n          \"@type\": \"schema:StructuredValue\"\n        }\n      }\n    },\n\n    \"Resource\": {\n      \"@id\": \"cfn:Resource\",\n      \"@type\": \"schema:Thing\",\n      \"@context\": {\n        \"LogicalResourceId\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"schema:Text\"\n        },\n        \"PhysicalResourceId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"schema:Text\"\n        },\n        \"\
  ResourceType\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"schema:Text\"\n        },\n        \"ResourceStatus\": {\n          \"@id\": \"cfn:resourceStatus\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Timestamp\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"schema:Text\"\n        },\n        \"ResourceStatusReason\": {\n          \"@id\": \"cfn:statusReason\",\n          \"@type\": \"schema:Text\"\n        },\n        \"StackName\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"schema:Text\"\n        }\n      }\n    },\n\n    \"ChangeSet\": {\n      \"@id\": \"cfn:ChangeSet\",\n      \"@type\": \"schema:UpdateAction\",\n      \"@context\": {\n        \"ChangeSetId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"schema:Text\"\n        },\n   \
  \     \"ChangeSetName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Status\": {\n          \"@id\": \"schema:actionStatus\",\n          \"@type\": \"schema:Text\"\n        },\n        \"ExecutionStatus\": {\n          \"@id\": \"cfn:executionStatus\",\n          \"@type\": \"schema:Text\"\n        },\n        \"CreationTime\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"StackId\": {\n          \"@id\": \"schema:targetCollection\",\n          \"@type\": \"@id\"\n        },\n        \"StackName\": {\n          \"@id\": \"cfn:stackName\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Changes\": {\n          \"@id\": \"cfn:changes\",\n          \"@type\": \"cfn:Change\"\n        },\n        \"StatusReason\": {\n          \"@id\": \"cfn:statusReason\"\
  ,\n          \"@type\": \"schema:Text\"\n        }\n      }\n    },\n\n    \"CloudControlResource\": {\n      \"@id\": \"awscc:Resource\",\n      \"@type\": \"schema:Thing\",\n      \"@context\": {\n        \"TypeName\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Identifier\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Properties\": {\n          \"@id\": \"schema:additionalProperty\",\n          \"@type\": \"schema:PropertyValue\"\n        },\n        \"DesiredState\": {\n          \"@id\": \"cfn:desiredState\",\n          \"@type\": \"schema:Text\"\n        }\n      }\n    },\n\n    \"ProgressEvent\": {\n      \"@id\": \"awscc:ProgressEvent\",\n      \"@type\": \"schema:Action\",\n      \"@context\": {\n        \"RequestToken\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Operation\": {\n       \
  \   \"@id\": \"schema:actionStatus\",\n          \"@type\": \"schema:Text\"\n        },\n        \"OperationStatus\": {\n          \"@id\": \"cfn:operationStatus\",\n          \"@type\": \"schema:Text\"\n        },\n        \"EventTime\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"StatusMessage\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"schema:Text\"\n        },\n        \"ErrorCode\": {\n          \"@id\": \"cfn:errorCode\",\n          \"@type\": \"schema:Text\"\n        },\n        \"TypeName\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"schema:Text\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"cfn:Tag\",\n      \"@type\": \"schema:DefinedTerm\",\n      \"@context\": {\n        \"Key\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Value\": {\n          \"@id\": \"schema:value\",\n     \
  \     \"@type\": \"schema:Text\"\n        }\n      }\n    },\n\n    \"Output\": {\n      \"@id\": \"cfn:Output\",\n      \"@type\": \"schema:PropertyValue\",\n      \"@context\": {\n        \"OutputKey\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"schema:Text\"\n        },\n        \"OutputValue\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"schema:Text\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"schema:Text\"\n        },\n        \"ExportName\": {\n          \"@id\": \"cfn:exportName\",\n          \"@type\": \"schema:Text\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/json-ld/context.jsonld
tags:
- Automation
- AWS
- Cloud Resources
- IaC
- Infrastructure As Code
- Stack Management
- JSON-LD
- Linked Data
- Semantic Web
---
