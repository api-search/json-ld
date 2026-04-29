---
api_specs:
- filename: amazon-healthimaging-openapi.yaml
  format: yaml
  label: AWS HealthImaging API
  slug: aws-healthimaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/openapi/amazon-healthimaging-openapi.yaml
class_count: 113
classes:
- CopyImageSetResponse
- CopySourceImageSetInformation
- CopyDestinationImageSet
- ThrottlingException
- ConflictException
- AccessDeniedException
- ValidationException
- InternalServerException
- ResourceNotFoundException
- ServiceQuotaExceededException
- CreateDatastoreResponse
- TagValue
- DeleteDatastoreResponse
- DeleteImageSetResponse
- GetDICOMImportJobResponse
- GetDatastoreResponse
- GetImageFrameResponse
- ImageFrameId
- GetImageSetResponse
- GetImageSetMetadataResponse
- ListDICOMImportJobsResponse
- ListDatastoresResponse
- ListImageSetVersionsResponse
- ListTagsForResourceResponse
- SearchImageSetsResponse
- SearchCriteriaFiltersList
- StartDICOMImportJobResponse
- TagResourceResponse
- UntagResourceResponse
- TagKey
- UpdateImageSetMetadataResponse
- DICOMUpdates
- Arn
- ClientToken
- ImageSetId
- ImageSetExternalVersionId
- ImageSetState
- ImageSetWorkflowStatus
- Date
- CopyDestinationImageSetProperties
- CopyImageSetInformation
- DatastoreId
- CopyImageSetRequest
- CopySourceImageSetProperties
- DatastoreName
- TagMap
- KmsKeyArn
- CreateDatastoreRequest
- DatastoreStatus
- DICOMAccessionNumber
- DICOMAttribute
- JobId
- JobName
- JobStatus
- RoleArn
- S3Uri
- Message
- DICOMImportJobProperties
- DICOMImportJobSummary
- DICOMImportJobSummaries
- DICOMNumberOfStudyRelatedInstances
- DICOMNumberOfStudyRelatedSeries
- DICOMPatientBirthDate
- DICOMPatientId
- DICOMPatientName
- DICOMPatientSex
- DICOMStudyDate
- DICOMStudyTime
- DICOMStudyDateAndTime
- DICOMStudyDescription
- DICOMStudyId
- DICOMStudyInstanceUID
- DICOMTags
- DatastoreProperties
- DatastoreSummary
- DatastoreSummaries
- DeleteDatastoreRequest
- DeleteImageSetRequest
- GetDICOMImportJobRequest
- GetDatastoreRequest
- ImageFrameInformation
- GetImageFrameRequest
- PayloadBlob
- String
- GetImageSetMetadataRequest
- ImageSetMetadataBlob
- GetImageSetRequest
- ImageSetProperties
- ImageSetPropertiesList
- ImageSetsMetadataSummary
- ImageSetsMetadataSummaries
- Integer
- NextToken
- ListDICOMImportJobsRequestMaxResultsInteger
- ListDICOMImportJobsRequest
- ListDatastoresRequestMaxResultsInteger
- ListDatastoresRequest
- ListImageSetVersionsRequestMaxResultsInteger
- ListImageSetVersionsRequest
- ListTagsForResourceRequest
- MetadataUpdates
- Operator
- SearchByAttributeValue
- SearchCriteria
- SearchFilter
- SearchFilterValuesList
- SearchImageSetsRequestMaxResultsInteger
- SearchImageSetsRequest
- StartDICOMImportJobRequest
- TagKeyList
- TagResourceRequest
- UntagResourceRequest
- UpdateImageSetMetadataRequest
context_file: json-ld/amazon-healthimaging-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/json-ld/amazon-healthimaging-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Healthimaging from Amazon HealthImaging.
layout: jsonld
name: Amazon Healthimaging Context
namespaces:
- prefix: hi
  uri: https://aws.amazon.com/healthimaging/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Amazon HealthImaging
provider_slug: amazon-healthimaging
slug: amazon-healthimaging-context
source_filename: amazon-healthimaging-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hi\": \"https://aws.amazon.com/healthimaging/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CopyImageSetResponse\": \"hi:CopyImageSetResponse\",\n    \"CopySourceImageSetInformation\": \"hi:CopySourceImageSetInformation\",\n    \"CopyDestinationImageSet\": \"hi:CopyDestinationImageSet\",\n    \"ThrottlingException\": \"hi:ThrottlingException\",\n    \"ConflictException\": \"hi:ConflictException\",\n    \"AccessDeniedException\": \"hi:AccessDeniedException\",\n    \"ValidationException\": \"hi:ValidationException\",\n    \"InternalServerException\": \"hi:InternalServerException\",\n    \"ResourceNotFoundException\": \"hi:ResourceNotFoundException\",\n    \"ServiceQuotaExceededException\": \"hi:ServiceQuotaExceededException\",\n    \"CreateDatastoreResponse\": \"hi:CreateDatastoreResponse\",\n    \"TagValue\": \"hi:TagValue\",\n    \"DeleteDatastoreResponse\":\
  \ \"hi:DeleteDatastoreResponse\",\n    \"DeleteImageSetResponse\": \"hi:DeleteImageSetResponse\",\n    \"GetDICOMImportJobResponse\": \"hi:GetDICOMImportJobResponse\",\n    \"GetDatastoreResponse\": \"hi:GetDatastoreResponse\",\n    \"GetImageFrameResponse\": \"hi:GetImageFrameResponse\",\n    \"ImageFrameId\": \"hi:ImageFrameId\",\n    \"GetImageSetResponse\": \"hi:GetImageSetResponse\",\n    \"GetImageSetMetadataResponse\": \"hi:GetImageSetMetadataResponse\",\n    \"ListDICOMImportJobsResponse\": \"hi:ListDICOMImportJobsResponse\",\n    \"ListDatastoresResponse\": \"hi:ListDatastoresResponse\",\n    \"ListImageSetVersionsResponse\": \"hi:ListImageSetVersionsResponse\",\n    \"ListTagsForResourceResponse\": \"hi:ListTagsForResourceResponse\",\n    \"SearchImageSetsResponse\": \"hi:SearchImageSetsResponse\",\n    \"SearchCriteriaFiltersList\": \"hi:SearchCriteriaFiltersList\",\n    \"StartDICOMImportJobResponse\": \"hi:StartDICOMImportJobResponse\",\n    \"TagResourceResponse\": \"hi:TagResourceResponse\"\
  ,\n    \"UntagResourceResponse\": \"hi:UntagResourceResponse\",\n    \"TagKey\": \"hi:TagKey\",\n    \"UpdateImageSetMetadataResponse\": \"hi:UpdateImageSetMetadataResponse\",\n    \"DICOMUpdates\": \"hi:DICOMUpdates\",\n    \"Arn\": \"hi:Arn\",\n    \"ClientToken\": \"hi:ClientToken\",\n    \"ImageSetId\": \"hi:ImageSetId\",\n    \"ImageSetExternalVersionId\": \"hi:ImageSetExternalVersionId\",\n    \"ImageSetState\": \"hi:ImageSetState\",\n    \"ImageSetWorkflowStatus\": \"hi:ImageSetWorkflowStatus\",\n    \"Date\": \"hi:Date\",\n    \"CopyDestinationImageSetProperties\": \"hi:CopyDestinationImageSetProperties\",\n    \"CopyImageSetInformation\": \"hi:CopyImageSetInformation\",\n    \"DatastoreId\": \"hi:DatastoreId\",\n    \"CopyImageSetRequest\": \"hi:CopyImageSetRequest\",\n    \"CopySourceImageSetProperties\": \"hi:CopySourceImageSetProperties\",\n    \"DatastoreName\": \"hi:DatastoreName\",\n    \"TagMap\": \"hi:TagMap\",\n    \"KmsKeyArn\": \"hi:KmsKeyArn\",\n    \"CreateDatastoreRequest\"\
  : \"hi:CreateDatastoreRequest\",\n    \"DatastoreStatus\": \"hi:DatastoreStatus\",\n    \"DICOMAccessionNumber\": \"hi:DICOMAccessionNumber\",\n    \"DICOMAttribute\": \"hi:DICOMAttribute\",\n    \"JobId\": \"hi:JobId\",\n    \"JobName\": \"hi:JobName\",\n    \"JobStatus\": \"hi:JobStatus\",\n    \"RoleArn\": \"hi:RoleArn\",\n    \"S3Uri\": \"hi:S3Uri\",\n    \"Message\": \"hi:Message\",\n    \"DICOMImportJobProperties\": \"hi:DICOMImportJobProperties\",\n    \"DICOMImportJobSummary\": \"hi:DICOMImportJobSummary\",\n    \"DICOMImportJobSummaries\": \"hi:DICOMImportJobSummaries\",\n    \"DICOMNumberOfStudyRelatedInstances\": \"hi:DICOMNumberOfStudyRelatedInstances\",\n    \"DICOMNumberOfStudyRelatedSeries\": \"hi:DICOMNumberOfStudyRelatedSeries\",\n    \"DICOMPatientBirthDate\": \"hi:DICOMPatientBirthDate\",\n    \"DICOMPatientId\": \"hi:DICOMPatientId\",\n    \"DICOMPatientName\": \"hi:DICOMPatientName\",\n    \"DICOMPatientSex\": \"hi:DICOMPatientSex\",\n    \"DICOMStudyDate\": \"hi:DICOMStudyDate\"\
  ,\n    \"DICOMStudyTime\": \"hi:DICOMStudyTime\",\n    \"DICOMStudyDateAndTime\": \"hi:DICOMStudyDateAndTime\",\n    \"DICOMStudyDescription\": \"hi:DICOMStudyDescription\",\n    \"DICOMStudyId\": \"hi:DICOMStudyId\",\n    \"DICOMStudyInstanceUID\": \"hi:DICOMStudyInstanceUID\",\n    \"DICOMTags\": \"hi:DICOMTags\",\n    \"DatastoreProperties\": \"hi:DatastoreProperties\",\n    \"DatastoreSummary\": \"hi:DatastoreSummary\",\n    \"DatastoreSummaries\": \"hi:DatastoreSummaries\",\n    \"DeleteDatastoreRequest\": \"hi:DeleteDatastoreRequest\",\n    \"DeleteImageSetRequest\": \"hi:DeleteImageSetRequest\",\n    \"GetDICOMImportJobRequest\": \"hi:GetDICOMImportJobRequest\",\n    \"GetDatastoreRequest\": \"hi:GetDatastoreRequest\",\n    \"ImageFrameInformation\": \"hi:ImageFrameInformation\",\n    \"GetImageFrameRequest\": \"hi:GetImageFrameRequest\",\n    \"PayloadBlob\": \"hi:PayloadBlob\",\n    \"String\": \"hi:String\",\n    \"GetImageSetMetadataRequest\": \"hi:GetImageSetMetadataRequest\"\
  ,\n    \"ImageSetMetadataBlob\": \"hi:ImageSetMetadataBlob\",\n    \"GetImageSetRequest\": \"hi:GetImageSetRequest\",\n    \"ImageSetProperties\": \"hi:ImageSetProperties\",\n    \"ImageSetPropertiesList\": \"hi:ImageSetPropertiesList\",\n    \"ImageSetsMetadataSummary\": \"hi:ImageSetsMetadataSummary\",\n    \"ImageSetsMetadataSummaries\": \"hi:ImageSetsMetadataSummaries\",\n    \"Integer\": \"hi:Integer\",\n    \"NextToken\": \"hi:NextToken\",\n    \"ListDICOMImportJobsRequestMaxResultsInteger\": \"hi:ListDICOMImportJobsRequestMaxResultsInteger\",\n    \"ListDICOMImportJobsRequest\": \"hi:ListDICOMImportJobsRequest\",\n    \"ListDatastoresRequestMaxResultsInteger\": \"hi:ListDatastoresRequestMaxResultsInteger\",\n    \"ListDatastoresRequest\": \"hi:ListDatastoresRequest\",\n    \"ListImageSetVersionsRequestMaxResultsInteger\": \"hi:ListImageSetVersionsRequestMaxResultsInteger\",\n    \"ListImageSetVersionsRequest\": \"hi:ListImageSetVersionsRequest\",\n    \"ListTagsForResourceRequest\"\
  : \"hi:ListTagsForResourceRequest\",\n    \"MetadataUpdates\": \"hi:MetadataUpdates\",\n    \"Operator\": \"hi:Operator\",\n    \"SearchByAttributeValue\": \"hi:SearchByAttributeValue\",\n    \"SearchCriteria\": \"hi:SearchCriteria\",\n    \"SearchFilter\": \"hi:SearchFilter\",\n    \"SearchFilterValuesList\": \"hi:SearchFilterValuesList\",\n    \"SearchImageSetsRequestMaxResultsInteger\": \"hi:SearchImageSetsRequestMaxResultsInteger\",\n    \"SearchImageSetsRequest\": \"hi:SearchImageSetsRequest\",\n    \"StartDICOMImportJobRequest\": \"hi:StartDICOMImportJobRequest\",\n    \"TagKeyList\": \"hi:TagKeyList\",\n    \"TagResourceRequest\": \"hi:TagResourceRequest\",\n    \"UntagResourceRequest\": \"hi:UntagResourceRequest\",\n    \"UpdateImageSetMetadataRequest\": \"hi:UpdateImageSetMetadataRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/json-ld/amazon-healthimaging-context.jsonld
tags:
- AWS
- Healthcare
- HIPAA
- Machine Learning
- Medical Imaging
- DICOM
- JSON-LD
- Linked Data
- Semantic Web
---
