---
class_count: 49
classes:
- CreateMatchingWorkflowInput
- description
- CreateMatchingWorkflowOutput
- CreateSchemaMappingInput
- CreateSchemaMappingOutput
- DeleteMatchingWorkflowInput
- DeleteMatchingWorkflowOutput
- DeleteSchemaMappingInput
- DeleteSchemaMappingOutput
- ErrorDetails
- GetMatchIdInput
- GetMatchIdOutput
- GetMatchingJobInput
- GetMatchingJobOutput
- GetMatchingWorkflowInput
- GetMatchingWorkflowOutput
- GetSchemaMappingInput
- GetSchemaMappingOutput
- IncrementalRunConfig
- InputSource
- JobMetrics
- JobSummary
- ListMatchingJobsInput
- ListMatchingJobsOutput
- ListMatchingWorkflowsInput
- ListMatchingWorkflowsOutput
- ListSchemaMappingsInput
- ListSchemaMappingsOutput
- ListTagsForResourceInput
- ListTagsForResourceOutput
- MatchingWorkflowSummary
- OutputAttribute
- name
- OutputSource
- RecordAttributeMap
- ResolutionTechniques
- RuleBasedProperties
- Rule
- SchemaInputAttribute
- SchemaMappingSummary
- StartMatchingJobInput
- StartMatchingJobOutput
- TagMap
- TagResourceInput
- TagResourceOutput
- UntagResourceInput
- UntagResourceOutput
- UpdateMatchingWorkflowInput
- UpdateMatchingWorkflowOutput
context_file: json-ld/amazon-entity-resolution-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-entity-resolution/refs/heads/main/json-ld/amazon-entity-resolution-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Entity Resolution from Amazon Entity Resolution.
layout: jsonld
name: Amazon Entity Resolution Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: incrementalRunConfig
  type: string
- container: ''
  name: inputSourceConfig
  type: string
- container: ''
  name: outputSourceConfig
  type: string
- container: ''
  name: resolutionTechniques
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: workflowName
  type: string
- container: ''
  name: workflowArn
  type: string
- container: ''
  name: mappedInputFields
  type: string
- container: ''
  name: schemaName
  type: string
- container: ''
  name: schemaArn
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: record
  type: string
- container: ''
  name: matchId
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: errorDetails
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: metrics
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: incrementalRunType
  type: string
- container: ''
  name: applyNormalization
  type: string
- container: ''
  name: inputSourceARN
  type: string
- container: ''
  name: inputRecords
  type: string
- container: ''
  name: matchIDs
  type: string
- container: ''
  name: recordsNotProcessed
  type: string
- container: ''
  name: totalRecordsProcessed
  type: string
- container: ''
  name: jobs
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: workflowSummaries
  type: string
- container: ''
  name: schemaList
  type: string
- container: ''
  name: hashed
  type: string
- container: ''
  name: KMSArn
  type: string
- container: ''
  name: output
  type: string
- container: ''
  name: outputS3Path
  type: string
- container: ''
  name: resolutionType
  type: string
- container: ''
  name: ruleBasedProperties
  type: string
- container: ''
  name: attributeMatchingModel
  type: string
- container: ''
  name: rules
  type: string
- container: ''
  name: matchingKeys
  type: string
- container: ''
  name: ruleName
  type: string
- container: ''
  name: fieldName
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: matchKey
  type: string
- container: ''
  name: type
  type: string
property_count: 48
provider_name: Amazon Entity Resolution
provider_slug: amazon-entity-resolution
slug: amazon-entity-resolution-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateMatchingWorkflowInput\": \"aws:CreateMatchingWorkflowInput\",\n    \"description\": \"schema:description\",\n    \"incrementalRunConfig\": {\n      \"@id\": \"aws:incrementalRunConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputSourceConfig\": {\n      \"@id\": \"aws:inputSourceConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputSourceConfig\": {\n      \"@id\": \"aws:outputSourceConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolutionTechniques\": {\n      \"@id\": \"aws:resolutionTechniques\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"aws:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"workflowName\": {\n      \"@id\": \"aws:workflowName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateMatchingWorkflowOutput\": \"aws:CreateMatchingWorkflowOutput\",\n    \"workflowArn\": {\n      \"@id\": \"aws:workflowArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateSchemaMappingInput\": \"aws:CreateSchemaMappingInput\",\n    \"mappedInputFields\": {\n      \"@id\": \"aws:mappedInputFields\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaName\": {\n      \"@id\": \"aws:schemaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateSchemaMappingOutput\": \"aws:CreateSchemaMappingOutput\",\n    \"schemaArn\": {\n      \"@id\": \"aws:schemaArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteMatchingWorkflowInput\": \"aws:DeleteMatchingWorkflowInput\",\n    \"DeleteMatchingWorkflowOutput\": \"aws:DeleteMatchingWorkflowOutput\",\n    \"message\": {\n      \"@id\": \"aws:message\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"DeleteSchemaMappingInput\": \"aws:DeleteSchemaMappingInput\",\n    \"DeleteSchemaMappingOutput\": \"aws:DeleteSchemaMappingOutput\",\n    \"ErrorDetails\": \"aws:ErrorDetails\",\n    \"errorMessage\": {\n      \"@id\": \"aws:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMatchIdInput\": \"aws:GetMatchIdInput\",\n    \"record\": {\n      \"@id\": \"aws:record\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMatchIdOutput\": \"aws:GetMatchIdOutput\",\n    \"matchId\": {\n      \"@id\": \"aws:matchId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMatchingJobInput\": \"aws:GetMatchingJobInput\",\n    \"GetMatchingJobOutput\": \"aws:GetMatchingJobOutput\",\n    \"endTime\": {\n      \"@id\": \"aws:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorDetails\": {\n      \"@id\": \"aws:errorDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"aws:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"metrics\": {\n      \"@id\": \"aws:metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"aws:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMatchingWorkflowInput\": \"aws:GetMatchingWorkflowInput\",\n    \"GetMatchingWorkflowOutput\": \"aws:GetMatchingWorkflowOutput\",\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"aws:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSchemaMappingInput\": \"aws:GetSchemaMappingInput\",\n    \"GetSchemaMappingOutput\": \"aws:GetSchemaMappingOutput\",\n    \"IncrementalRunConfig\": \"aws:IncrementalRunConfig\",\n    \"incrementalRunType\": {\n      \"@id\": \"aws:incrementalRunType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputSource\": \"aws:InputSource\",\n    \"applyNormalization\": {\n  \
  \    \"@id\": \"aws:applyNormalization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputSourceARN\": {\n      \"@id\": \"aws:inputSourceARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobMetrics\": \"aws:JobMetrics\",\n    \"inputRecords\": {\n      \"@id\": \"aws:inputRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchIDs\": {\n      \"@id\": \"aws:matchIDs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordsNotProcessed\": {\n      \"@id\": \"aws:recordsNotProcessed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRecordsProcessed\": {\n      \"@id\": \"aws:totalRecordsProcessed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobSummary\": \"aws:JobSummary\",\n    \"ListMatchingJobsInput\": \"aws:ListMatchingJobsInput\",\n    \"ListMatchingJobsOutput\": \"aws:ListMatchingJobsOutput\",\n    \"jobs\": {\n      \"@id\": \"aws:jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"aws:nextToken\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"ListMatchingWorkflowsInput\": \"aws:ListMatchingWorkflowsInput\",\n    \"ListMatchingWorkflowsOutput\": \"aws:ListMatchingWorkflowsOutput\",\n    \"workflowSummaries\": {\n      \"@id\": \"aws:workflowSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListSchemaMappingsInput\": \"aws:ListSchemaMappingsInput\",\n    \"ListSchemaMappingsOutput\": \"aws:ListSchemaMappingsOutput\",\n    \"schemaList\": {\n      \"@id\": \"aws:schemaList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceInput\": \"aws:ListTagsForResourceInput\",\n    \"ListTagsForResourceOutput\": \"aws:ListTagsForResourceOutput\",\n    \"MatchingWorkflowSummary\": \"aws:MatchingWorkflowSummary\",\n    \"OutputAttribute\": \"aws:OutputAttribute\",\n    \"hashed\": {\n      \"@id\": \"aws:hashed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"OutputSource\": \"aws:OutputSource\",\n    \"KMSArn\": {\n      \"@id\": \"aws:KMSArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"output\": {\n      \"@id\": \"aws:output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputS3Path\": {\n      \"@id\": \"aws:outputS3Path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecordAttributeMap\": \"aws:RecordAttributeMap\",\n    \"ResolutionTechniques\": \"aws:ResolutionTechniques\",\n    \"resolutionType\": {\n      \"@id\": \"aws:resolutionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleBasedProperties\": {\n      \"@id\": \"aws:ruleBasedProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleBasedProperties\": \"aws:RuleBasedProperties\",\n    \"attributeMatchingModel\": {\n      \"@id\": \"aws:attributeMatchingModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"aws:rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rule\": \"aws:Rule\",\n    \"matchingKeys\": {\n      \"@id\": \"aws:matchingKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleName\"\
  : {\n      \"@id\": \"aws:ruleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaInputAttribute\": \"aws:SchemaInputAttribute\",\n    \"fieldName\": {\n      \"@id\": \"aws:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"aws:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchKey\": {\n      \"@id\": \"aws:matchKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaMappingSummary\": \"aws:SchemaMappingSummary\",\n    \"StartMatchingJobInput\": \"aws:StartMatchingJobInput\",\n    \"StartMatchingJobOutput\": \"aws:StartMatchingJobOutput\",\n    \"TagMap\": \"aws:TagMap\",\n    \"TagResourceInput\": \"aws:TagResourceInput\",\n    \"TagResourceOutput\": \"aws:TagResourceOutput\",\n    \"UntagResourceInput\": \"aws:UntagResourceInput\",\n    \"UntagResourceOutput\": \"aws:UntagResourceOutput\",\n    \"UpdateMatchingWorkflowInput\"\
  : \"aws:UpdateMatchingWorkflowInput\",\n    \"UpdateMatchingWorkflowOutput\": \"aws:UpdateMatchingWorkflowOutput\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-entity-resolution/refs/heads/main/json-ld/amazon-entity-resolution-context.jsonld
tags:
- Amazon Web Services
- AWS
- Data Integration
- Data Matching
- Entity Resolution
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
