---
class_count: 0
classes: []
context_file: json-ld/amazon-systems-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/json-ld/amazon-systems-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Systems Manager from Amazon Systems Manager.
layout: jsonld
name: Amazon Systems Manager Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/systems-manager/schemas/
- prefix: ssm
  uri: https://docs.aws.amazon.com/systems-manager/latest/APIReference/
properties:
- container: ''
  name: Parameter
  type: ''
- container: ''
  name: Command
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: AutomationExecution
  type: ''
- container: ''
  name: InstanceInformation
  type: ''
property_count: 5
provider_name: Amazon Systems Manager
provider_slug: amazon-systems-manager
slug: amazon-systems-manager-context
source_filename: amazon-systems-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/systems-manager/schemas/\",\n    \"ssm\": \"https://docs.aws.amazon.com/systems-manager/latest/APIReference/\",\n    \"Parameter\": {\n      \"@id\": \"aws:Parameter\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Type\": \"schema:additionalType\",\n        \"Value\": \"schema:value\",\n        \"Version\": \"schema:version\",\n        \"ARN\": \"aws:arn\",\n        \"Description\": \"schema:description\",\n        \"LastModifiedDate\": \"schema:dateModified\",\n        \"LastModifiedUser\": \"aws:lastModifiedUser\",\n        \"KeyId\": \"aws:keyId\",\n        \"Tier\": \"aws:tier\",\n        \"DataType\": \"aws:dataType\"\n      }\n    },\n    \"Command\": {\n      \"@id\": \"aws:Command\",\n      \"@context\": {\n        \"CommandId\": \"schema:identifier\",\n        \"DocumentName\": \"schema:name\",\n        \"Status\": \"aws:commandStatus\",\n\
  \        \"InstanceIds\": \"aws:instanceIds\",\n        \"Parameters\": \"aws:parameters\",\n        \"RequestedDateTime\": \"schema:dateCreated\",\n        \"Comment\": \"schema:description\"\n      }\n    },\n    \"Document\": {\n      \"@id\": \"aws:Document\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"DocumentType\": \"schema:additionalType\",\n        \"DocumentFormat\": \"schema:encodingFormat\",\n        \"Content\": \"schema:text\",\n        \"Status\": \"aws:documentStatus\",\n        \"DocumentVersion\": \"schema:version\"\n      }\n    },\n    \"AutomationExecution\": {\n      \"@id\": \"aws:AutomationExecution\",\n      \"@context\": {\n        \"AutomationExecutionId\": \"schema:identifier\",\n        \"DocumentName\": \"schema:name\",\n        \"Mode\": \"aws:executionMode\",\n        \"Status\": \"aws:executionStatus\",\n        \"Parameters\": \"aws:parameters\"\n      }\n    },\n    \"InstanceInformation\": {\n      \"@id\": \"aws:InstanceInformation\"\
  ,\n      \"@context\": {\n        \"InstanceId\": \"schema:identifier\",\n        \"PingStatus\": \"aws:pingStatus\",\n        \"PlatformType\": \"schema:operatingSystem\",\n        \"PlatformName\": \"schema:name\",\n        \"AgentVersion\": \"schema:softwareVersion\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/json-ld/amazon-systems-manager-context.jsonld
tags:
- Automation
- AWS
- Management
- Operations
- JSON-LD
- Linked Data
- Semantic Web
---
