---
class_count: 26
classes:
- CreateMLEndpointInput
- EngineStatusOutput
- ExecuteGremlinProfileInput
- ExecuteGremlinQueryInput
- ExecuteGremlinQueryOutput
- ExecuteOpenCypherExplainInput
- ExecuteOpenCypherQueryInput
- ExecuteOpenCypherQueryOutput
- ExecuteSparqlQueryInput
- GremlinQueryStatus
- GremlinQueryStatusOutput
- LoaderJobStatusOutput
- MLEndpointStatusOutput
- MLJobStatusOutput
- OpenCypherQueryStatusOutput
- PropertygraphStatisticsOutput
- PropertygraphStreamOutput
- PropertygraphStreamRecord
- SparqlQueryOutput
- SparqlStatisticsOutput
- SparqlStreamOutput
- StartLoaderJobInput
- StartLoaderJobOutput
- StartMLDataProcessingJobInput
- StartMLModelTrainingJobInput
- StartMLModelTransformJobInput
context_file: json-ld/amazon-neptune-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Data from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Data Context
namespaces:
- prefix: neptune
  uri: https://neptune.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: acceptedQueryCount
  type: integer
- container: ''
  name: allowEmptyStrings
  type: boolean
- container: ''
  name: arn
  type: string
- container: ''
  name: baseProcessingInstanceType
  type: string
- container: ''
  name: baseProcessingInstanceVolumeSizeInGB
  type: integer
- container: ''
  name: baseUri
  type: string
- container: ''
  name: cancelled
  type: boolean
- container: ''
  name: chop
  type: integer
- container: ''
  name: commitNum
  type: integer
- container: ''
  name: commitTimestampInMillis
  type: integer
- container: ''
  name: configFileName
  type: string
- container: ''
  name: customModelTrainingParameters
  type: reference
- container: ''
  name: customModelTransformParameters
  type: reference
- container: ''
  name: data
  type: reference
- container: ''
  name: dataProcessingJobId
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: datatypeMismatchErrors
  type: integer
- container: ''
  name: dbEngineVersion
  type: string
- container: set
  name: dependencies
  type: string
- container: ''
  name: dfeQueryEngine
  type: string
- container: ''
  name: elapsed
  type: integer
- container: ''
  name: enableInterContainerTrafficEncryption
  type: boolean
- container: ''
  name: enableManagedSpotTraining
  type: boolean
- container: ''
  name: endpoint
  type: reference
- container: ''
  name: endpointConfig
  type: reference
- container: ''
  name: eventId
  type: reference
- container: ''
  name: explainMode
  type: string
- container: ''
  name: failOnError
  type: string
- container: ''
  name: features
  type: reference
- container: set
  name: feedCount
  type: reference
- container: ''
  name: format
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: fullUri
  type: string
- container: ''
  name: gremlin
  type: reference
- container: ''
  name: head
  type: reference
- container: ''
  name: iamRoleArn
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: indexOps
  type: boolean
- container: ''
  name: inputDataS3Location
  type: string
- container: ''
  name: insertErrors
  type: integer
- container: ''
  name: instanceCount
  type: integer
- container: ''
  name: instanceType
  type: string
- container: ''
  name: isLastOp
  type: boolean
- container: ''
  name: key
  type: string
- container: ''
  name: labMode
  type: reference
- container: ''
  name: lastEventId
  type: reference
- container: ''
  name: lastTrxTimestampInMillis
  type: integer
- container: ''
  name: maxHPONumberOfTrainingJobs
  type: integer
- container: ''
  name: maxHPOParallelTrainingJobs
  type: integer
- container: ''
  name: mlModelTrainingJobId
  type: string
- container: ''
  name: mlModelTransformJobId
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: modelName
  type: string
- container: ''
  name: modelTransformOutputS3Location
  type: string
- container: ''
  name: modelType
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: namedGraphUri
  type: string
- container: ''
  name: neptuneIamRoleArn
  type: string
- container: ''
  name: op
  type: string
- container: ''
  name: opNum
  type: integer
- container: ''
  name: opencypher
  type: reference
- container: ''
  name: outputLocation
  type: string
- container: ''
  name: overallStatus
  type: reference
- container: ''
  name: parallelism
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: parserConfiguration
  type: reference
- container: ''
  name: parsingErrors
  type: integer
- container: ''
  name: payload
  type: reference
- container: ''
  name: previousDataProcessingJobId
  type: string
- container: ''
  name: previousModelTrainingJobId
  type: string
- container: ''
  name: processedDataS3Location
  type: string
- container: ''
  name: processingInstanceType
  type: string
- container: ''
  name: processingInstanceVolumeSizeInGB
  type: integer
- container: ''
  name: processingJob
  type: reference
- container: ''
  name: processingTimeOutInSeconds
  type: integer
- container: set
  name: queries
  type: reference
- container: ''
  name: query
  type: string
- container: ''
  name: queryEvalStats
  type: reference
- container: ''
  name: queryId
  type: string
- container: ''
  name: queryString
  type: string
- container: ''
  name: queueRequest
  type: string
- container: set
  name: records
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: result
  type: reference
- container: set
  name: results
  type: reference
- container: ''
  name: retryNumber
  type: integer
- container: ''
  name: role
  type: string
- container: ''
  name: runNumber
  type: integer
- container: ''
  name: runningQueryCount
  type: integer
- container: ''
  name: s3OutputEncryptionKMSKey
  type: string
- container: ''
  name: sagemakerIamRoleArn
  type: string
- container: set
  name: securityGroupIds
  type: string
- container: ''
  name: serializer
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sourceS3DirectoryPath
  type: string
- container: ''
  name: sparql
  type: reference
- container: ''
  name: startTime
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: subnets
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: totalDuplicates
  type: integer
- container: ''
  name: totalRecords
  type: integer
- container: ''
  name: totalTimeSpent
  type: integer
- container: ''
  name: trainModelS3Location
  type: string
- container: ''
  name: trainingEntryPointScript
  type: string
- container: ''
  name: trainingInstanceType
  type: string
- container: ''
  name: trainingInstanceVolumeSizeInGB
  type: integer
- container: ''
  name: trainingJobName
  type: string
- container: ''
  name: trainingTimeOutInSeconds
  type: integer
- container: ''
  name: transformEntryPointScript
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: update
  type: string
- container: ''
  name: updateSingleCardinalityProperties
  type: string
- container: ''
  name: userProvidedEdgeIds
  type: string
- container: ''
  name: value
  type: reference
- container: set
  name: vars
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: volumeEncryptionKMSKey
  type: string
- container: ''
  name: waited
  type: integer
property_count: 120
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateMLEndpointInput\": \"neptune:CreateMLEndpointInput\",\n    \"EngineStatusOutput\": \"neptune:EngineStatusOutput\",\n    \"ExecuteGremlinProfileInput\": \"neptune:ExecuteGremlinProfileInput\",\n    \"ExecuteGremlinQueryInput\": \"neptune:ExecuteGremlinQueryInput\",\n    \"ExecuteGremlinQueryOutput\": \"neptune:ExecuteGremlinQueryOutput\",\n    \"ExecuteOpenCypherExplainInput\": \"neptune:ExecuteOpenCypherExplainInput\",\n    \"ExecuteOpenCypherQueryInput\": \"neptune:ExecuteOpenCypherQueryInput\",\n    \"ExecuteOpenCypherQueryOutput\": \"neptune:ExecuteOpenCypherQueryOutput\",\n    \"ExecuteSparqlQueryInput\": \"neptune:ExecuteSparqlQueryInput\",\n    \"GremlinQueryStatus\": \"neptune:GremlinQueryStatus\",\n    \"GremlinQueryStatusOutput\"\
  : \"neptune:GremlinQueryStatusOutput\",\n    \"LoaderJobStatusOutput\": \"neptune:LoaderJobStatusOutput\",\n    \"MLEndpointStatusOutput\": \"neptune:MLEndpointStatusOutput\",\n    \"MLJobStatusOutput\": \"neptune:MLJobStatusOutput\",\n    \"OpenCypherQueryStatusOutput\": \"neptune:OpenCypherQueryStatusOutput\",\n    \"PropertygraphStatisticsOutput\": \"neptune:PropertygraphStatisticsOutput\",\n    \"PropertygraphStreamOutput\": \"neptune:PropertygraphStreamOutput\",\n    \"PropertygraphStreamRecord\": \"neptune:PropertygraphStreamRecord\",\n    \"SparqlQueryOutput\": \"neptune:SparqlQueryOutput\",\n    \"SparqlStatisticsOutput\": \"neptune:SparqlStatisticsOutput\",\n    \"SparqlStreamOutput\": \"neptune:SparqlStreamOutput\",\n    \"StartLoaderJobInput\": \"neptune:StartLoaderJobInput\",\n    \"StartLoaderJobOutput\": \"neptune:StartLoaderJobOutput\",\n    \"StartMLDataProcessingJobInput\": \"neptune:StartMLDataProcessingJobInput\",\n    \"StartMLModelTrainingJobInput\": \"neptune:StartMLModelTrainingJobInput\"\
  ,\n    \"StartMLModelTransformJobInput\": \"neptune:StartMLModelTransformJobInput\",\n    \"acceptedQueryCount\": {\n      \"@id\": \"neptune:acceptedQueryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"allowEmptyStrings\": {\n      \"@id\": \"neptune:allowEmptyStrings\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"arn\": {\n      \"@id\": \"neptune:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseProcessingInstanceType\": {\n      \"@id\": \"neptune:baseProcessingInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseProcessingInstanceVolumeSizeInGB\": {\n      \"@id\": \"neptune:baseProcessingInstanceVolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"baseUri\": {\n      \"@id\": \"neptune:baseUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cancelled\": {\n      \"@id\": \"neptune:cancelled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"chop\": {\n      \"@id\": \"neptune:chop\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"commitNum\": {\n      \"@id\": \"neptune:commitNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commitTimestampInMillis\": {\n      \"@id\": \"neptune:commitTimestampInMillis\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configFileName\": {\n      \"@id\": \"neptune:configFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customModelTrainingParameters\": {\n      \"@id\": \"neptune:customModelTrainingParameters\",\n      \"@type\": \"@id\"\n    },\n    \"customModelTransformParameters\": {\n      \"@id\": \"neptune:customModelTransformParameters\",\n      \"@type\": \"@id\"\n    },\n    \"data\": {\n      \"@id\": \"neptune:data\",\n      \"@type\": \"@id\"\n    },\n    \"dataProcessingJobId\": {\n      \"@id\": \"neptune:dataProcessingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"neptune:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datatypeMismatchErrors\": {\n      \"@id\": \"neptune:datatypeMismatchErrors\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"dbEngineVersion\": {\n      \"@id\": \"neptune:dbEngineVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependencies\": {\n      \"@id\": \"neptune:dependencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dfeQueryEngine\": {\n      \"@id\": \"neptune:dfeQueryEngine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elapsed\": {\n      \"@id\": \"neptune:elapsed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enableInterContainerTrafficEncryption\": {\n      \"@id\": \"neptune:enableInterContainerTrafficEncryption\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableManagedSpotTraining\": {\n      \"@id\": \"neptune:enableManagedSpotTraining\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endpoint\": {\n      \"@id\": \"neptune:endpoint\",\n      \"@type\": \"@id\"\n    },\n    \"endpointConfig\": {\n      \"@id\": \"neptune:endpointConfig\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"eventId\": {\n      \"@id\": \"neptune:eventId\",\n      \"@type\": \"@id\"\n    },\n    \"explainMode\": {\n      \"@id\": \"neptune:explainMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failOnError\": {\n      \"@id\": \"neptune:failOnError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"features\": {\n      \"@id\": \"neptune:features\",\n      \"@type\": \"@id\"\n    },\n    \"feedCount\": {\n      \"@id\": \"neptune:feedCount\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"format\": {\n      \"@id\": \"neptune:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"neptune:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullUri\": {\n      \"@id\": \"neptune:fullUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gremlin\": {\n      \"@id\": \"neptune:gremlin\",\n      \"@type\": \"@id\"\n    },\n    \"head\": {\n      \"@id\": \"neptune:head\",\n      \"@type\": \"@id\"\n    },\n    \"iamRoleArn\"\
  : {\n      \"@id\": \"neptune:iamRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"neptune:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indexOps\": {\n      \"@id\": \"neptune:indexOps\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"inputDataS3Location\": {\n      \"@id\": \"neptune:inputDataS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insertErrors\": {\n      \"@id\": \"neptune:insertErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instanceCount\": {\n      \"@id\": \"neptune:instanceCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instanceType\": {\n      \"@id\": \"neptune:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isLastOp\": {\n      \"@id\": \"neptune:isLastOp\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"key\": {\n      \"@id\": \"neptune:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labMode\": {\n      \"@id\": \"neptune:labMode\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"lastEventId\": {\n      \"@id\": \"neptune:lastEventId\",\n      \"@type\": \"@id\"\n    },\n    \"lastTrxTimestampInMillis\": {\n      \"@id\": \"neptune:lastTrxTimestampInMillis\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxHPONumberOfTrainingJobs\": {\n      \"@id\": \"neptune:maxHPONumberOfTrainingJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxHPOParallelTrainingJobs\": {\n      \"@id\": \"neptune:maxHPOParallelTrainingJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mlModelTrainingJobId\": {\n      \"@id\": \"neptune:mlModelTrainingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mlModelTransformJobId\": {\n      \"@id\": \"neptune:mlModelTransformJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"neptune:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelName\": {\n      \"@id\": \"neptune:modelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelTransformOutputS3Location\": {\n\
  \      \"@id\": \"neptune:modelTransformOutputS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelType\": {\n      \"@id\": \"neptune:modelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"namedGraphUri\": {\n      \"@id\": \"neptune:namedGraphUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"neptuneIamRoleArn\": {\n      \"@id\": \"neptune:neptuneIamRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op\": {\n      \"@id\": \"neptune:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opNum\": {\n      \"@id\": \"neptune:opNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"opencypher\": {\n      \"@id\": \"neptune:opencypher\",\n      \"@type\": \"@id\"\n    },\n    \"outputLocation\": {\n      \"@id\": \"neptune:outputLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallStatus\": {\n      \"@id\": \"neptune:overallStatus\",\n      \"@type\": \"@id\"\n    },\n    \"parallelism\"\
  : {\n      \"@id\": \"neptune:parallelism\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"neptune:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parserConfiguration\": {\n      \"@id\": \"neptune:parserConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"parsingErrors\": {\n      \"@id\": \"neptune:parsingErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"payload\": {\n      \"@id\": \"neptune:payload\",\n      \"@type\": \"@id\"\n    },\n    \"previousDataProcessingJobId\": {\n      \"@id\": \"neptune:previousDataProcessingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousModelTrainingJobId\": {\n      \"@id\": \"neptune:previousModelTrainingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processedDataS3Location\": {\n      \"@id\": \"neptune:processedDataS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingInstanceType\": {\n      \"@id\": \"neptune:processingInstanceType\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"processingInstanceVolumeSizeInGB\": {\n      \"@id\": \"neptune:processingInstanceVolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"processingJob\": {\n      \"@id\": \"neptune:processingJob\",\n      \"@type\": \"@id\"\n    },\n    \"processingTimeOutInSeconds\": {\n      \"@id\": \"neptune:processingTimeOutInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queries\": {\n      \"@id\": \"neptune:queries\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"query\": {\n      \"@id\": \"neptune:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryEvalStats\": {\n      \"@id\": \"neptune:queryEvalStats\",\n      \"@type\": \"@id\"\n    },\n    \"queryId\": {\n      \"@id\": \"neptune:queryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryString\": {\n      \"@id\": \"neptune:queryString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueRequest\": {\n      \"@id\": \"\
  neptune:queueRequest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"records\": {\n      \"@id\": \"neptune:records\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"neptune:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"neptune:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"neptune:result\",\n      \"@type\": \"@id\"\n    },\n    \"results\": {\n      \"@id\": \"neptune:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"retryNumber\": {\n      \"@id\": \"neptune:retryNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"role\": {\n      \"@id\": \"neptune:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runNumber\": {\n      \"@id\": \"neptune:runNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runningQueryCount\": {\n      \"@id\": \"neptune:runningQueryCount\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"s3OutputEncryptionKMSKey\": {\n      \"@id\": \"neptune:s3OutputEncryptionKMSKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sagemakerIamRoleArn\": {\n      \"@id\": \"neptune:sagemakerIamRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"neptune:securityGroupIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serializer\": {\n      \"@id\": \"neptune:serializer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"neptune:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceS3DirectoryPath\": {\n      \"@id\": \"neptune:sourceS3DirectoryPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sparql\": {\n      \"@id\": \"neptune:sparql\",\n      \"@type\": \"@id\"\n    },\n    \"startTime\": {\n      \"@id\": \"neptune:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"neptune:status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"subnets\": {\n      \"@id\": \"neptune:subnets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"neptune:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalDuplicates\": {\n      \"@id\": \"neptune:totalDuplicates\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalRecords\": {\n      \"@id\": \"neptune:totalRecords\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalTimeSpent\": {\n      \"@id\": \"neptune:totalTimeSpent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trainModelS3Location\": {\n      \"@id\": \"neptune:trainModelS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingEntryPointScript\": {\n      \"@id\": \"neptune:trainingEntryPointScript\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingInstanceType\": {\n      \"@id\": \"neptune:trainingInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingInstanceVolumeSizeInGB\"\
  : {\n      \"@id\": \"neptune:trainingInstanceVolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trainingJobName\": {\n      \"@id\": \"neptune:trainingJobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingTimeOutInSeconds\": {\n      \"@id\": \"neptune:trainingTimeOutInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transformEntryPointScript\": {\n      \"@id\": \"neptune:transformEntryPointScript\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"neptune:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"update\": {\n      \"@id\": \"neptune:update\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateSingleCardinalityProperties\": {\n      \"@id\": \"neptune:updateSingleCardinalityProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProvidedEdgeIds\": {\n      \"@id\": \"neptune:userProvidedEdgeIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"neptune:value\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"vars\": {\n      \"@id\": \"neptune:vars\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"volumeEncryptionKMSKey\": {\n      \"@id\": \"neptune:volumeEncryptionKMSKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waited\": {\n      \"@id\": \"neptune:waited\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-data-context.jsonld
tags:
- AWS
- Database
- Graph Database
- Gremlin
- Neptune
- Property Graph
- RDF
- SPARQL
- JSON-LD
- Linked Data
- Semantic Web
---
