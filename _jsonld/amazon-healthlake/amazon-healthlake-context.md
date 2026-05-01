---
api_specs:
- filename: amazon-healthlake-openapi.yaml
  format: yaml
  label: Amazon HealthLake API
  slug: amazon-healthlake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/openapi/amazon-healthlake-openapi.yaml
class_count: 76
classes:
- CreateFHIRDatastoreResponse
- CreateFHIRDatastoreRequest
- ValidationException
- ThrottlingException
- AccessDeniedException
- InternalServerException
- DeleteFHIRDatastoreResponse
- DeleteFHIRDatastoreRequest
- ConflictException
- ResourceNotFoundException
- DescribeFHIRDatastoreResponse
- DescribeFHIRDatastoreRequest
- DescribeFHIRExportJobResponse
- DescribeFHIRExportJobRequest
- DescribeFHIRImportJobResponse
- DescribeFHIRImportJobRequest
- ListFHIRDatastoresResponse
- ListFHIRDatastoresRequest
- ListFHIRExportJobsResponse
- ListFHIRExportJobsRequest
- ListFHIRImportJobsResponse
- ListFHIRImportJobsRequest
- ListTagsForResourceResponse
- ListTagsForResourceRequest
- StartFHIRExportJobResponse
- StartFHIRExportJobRequest
- StartFHIRImportJobResponse
- StartFHIRImportJobRequest
- TagResourceResponse
- TagResourceRequest
- UntagResourceResponse
- UntagResourceRequest
- AmazonResourceName
- AuthorizationStrategy
- Boolean
- BoundedLengthString
- ClientTokenString
- CmkType
- ConfigurationMetadata
- DatastoreName
- FHIRVersion
- SseConfiguration
- PreloadDataConfig
- TagList
- IdentityProviderConfiguration
- DatastoreId
- DatastoreArn
- DatastoreStatus
- Timestamp
- DatastoreFilter
- String
- DatastoreProperties
- DatastorePropertiesList
- JobId
- ExportJobProperties
- ImportJobProperties
- EncryptionKeyID
- JobName
- JobStatus
- OutputDataConfig
- IamRoleArn
- Message
- ExportJobPropertiesList
- LambdaArn
- InputDataConfig
- ImportJobPropertiesList
- S3Uri
- KmsEncryptionConfig
- NextToken
- MaxResultsInteger
- S3Configuration
- PreloadDataType
- TagKey
- TagValue
- Tag
- TagKeyList
context_file: json-ld/amazon-healthlake-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/json-ld/amazon-healthlake-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Healthlake from Amazon HealthLake.
layout: jsonld
name: Amazon Healthlake Context
namespaces:
- prefix: hl
  uri: https://aws.amazon.com/healthlake/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Amazon HealthLake
provider_slug: amazon-healthlake
slug: amazon-healthlake-context
source_filename: amazon-healthlake-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hl\": \"https://aws.amazon.com/healthlake/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateFHIRDatastoreResponse\": \"hl:CreateFHIRDatastoreResponse\",\n    \"CreateFHIRDatastoreRequest\": \"hl:CreateFHIRDatastoreRequest\",\n    \"ValidationException\": \"hl:ValidationException\",\n    \"ThrottlingException\": \"hl:ThrottlingException\",\n    \"AccessDeniedException\": \"hl:AccessDeniedException\",\n    \"InternalServerException\": \"hl:InternalServerException\",\n    \"DeleteFHIRDatastoreResponse\": \"hl:DeleteFHIRDatastoreResponse\",\n    \"DeleteFHIRDatastoreRequest\": \"hl:DeleteFHIRDatastoreRequest\",\n    \"ConflictException\": \"hl:ConflictException\",\n    \"ResourceNotFoundException\": \"hl:ResourceNotFoundException\",\n    \"DescribeFHIRDatastoreResponse\": \"hl:DescribeFHIRDatastoreResponse\",\n    \"DescribeFHIRDatastoreRequest\": \"hl:DescribeFHIRDatastoreRequest\"\
  ,\n    \"DescribeFHIRExportJobResponse\": \"hl:DescribeFHIRExportJobResponse\",\n    \"DescribeFHIRExportJobRequest\": \"hl:DescribeFHIRExportJobRequest\",\n    \"DescribeFHIRImportJobResponse\": \"hl:DescribeFHIRImportJobResponse\",\n    \"DescribeFHIRImportJobRequest\": \"hl:DescribeFHIRImportJobRequest\",\n    \"ListFHIRDatastoresResponse\": \"hl:ListFHIRDatastoresResponse\",\n    \"ListFHIRDatastoresRequest\": \"hl:ListFHIRDatastoresRequest\",\n    \"ListFHIRExportJobsResponse\": \"hl:ListFHIRExportJobsResponse\",\n    \"ListFHIRExportJobsRequest\": \"hl:ListFHIRExportJobsRequest\",\n    \"ListFHIRImportJobsResponse\": \"hl:ListFHIRImportJobsResponse\",\n    \"ListFHIRImportJobsRequest\": \"hl:ListFHIRImportJobsRequest\",\n    \"ListTagsForResourceResponse\": \"hl:ListTagsForResourceResponse\",\n    \"ListTagsForResourceRequest\": \"hl:ListTagsForResourceRequest\",\n    \"StartFHIRExportJobResponse\": \"hl:StartFHIRExportJobResponse\",\n    \"StartFHIRExportJobRequest\": \"hl:StartFHIRExportJobRequest\"\
  ,\n    \"StartFHIRImportJobResponse\": \"hl:StartFHIRImportJobResponse\",\n    \"StartFHIRImportJobRequest\": \"hl:StartFHIRImportJobRequest\",\n    \"TagResourceResponse\": \"hl:TagResourceResponse\",\n    \"TagResourceRequest\": \"hl:TagResourceRequest\",\n    \"UntagResourceResponse\": \"hl:UntagResourceResponse\",\n    \"UntagResourceRequest\": \"hl:UntagResourceRequest\",\n    \"AmazonResourceName\": \"hl:AmazonResourceName\",\n    \"AuthorizationStrategy\": \"hl:AuthorizationStrategy\",\n    \"Boolean\": \"hl:Boolean\",\n    \"BoundedLengthString\": \"hl:BoundedLengthString\",\n    \"ClientTokenString\": \"hl:ClientTokenString\",\n    \"CmkType\": \"hl:CmkType\",\n    \"ConfigurationMetadata\": \"hl:ConfigurationMetadata\",\n    \"DatastoreName\": \"hl:DatastoreName\",\n    \"FHIRVersion\": \"hl:FHIRVersion\",\n    \"SseConfiguration\": \"hl:SseConfiguration\",\n    \"PreloadDataConfig\": \"hl:PreloadDataConfig\",\n    \"TagList\": \"hl:TagList\",\n    \"IdentityProviderConfiguration\"\
  : \"hl:IdentityProviderConfiguration\",\n    \"DatastoreId\": \"hl:DatastoreId\",\n    \"DatastoreArn\": \"hl:DatastoreArn\",\n    \"DatastoreStatus\": \"hl:DatastoreStatus\",\n    \"Timestamp\": \"hl:Timestamp\",\n    \"DatastoreFilter\": \"hl:DatastoreFilter\",\n    \"String\": \"hl:String\",\n    \"DatastoreProperties\": \"hl:DatastoreProperties\",\n    \"DatastorePropertiesList\": \"hl:DatastorePropertiesList\",\n    \"JobId\": \"hl:JobId\",\n    \"ExportJobProperties\": \"hl:ExportJobProperties\",\n    \"ImportJobProperties\": \"hl:ImportJobProperties\",\n    \"EncryptionKeyID\": \"hl:EncryptionKeyID\",\n    \"JobName\": \"hl:JobName\",\n    \"JobStatus\": \"hl:JobStatus\",\n    \"OutputDataConfig\": \"hl:OutputDataConfig\",\n    \"IamRoleArn\": \"hl:IamRoleArn\",\n    \"Message\": \"hl:Message\",\n    \"ExportJobPropertiesList\": \"hl:ExportJobPropertiesList\",\n    \"LambdaArn\": \"hl:LambdaArn\",\n    \"InputDataConfig\": \"hl:InputDataConfig\",\n    \"ImportJobPropertiesList\"\
  : \"hl:ImportJobPropertiesList\",\n    \"S3Uri\": \"hl:S3Uri\",\n    \"KmsEncryptionConfig\": \"hl:KmsEncryptionConfig\",\n    \"NextToken\": \"hl:NextToken\",\n    \"MaxResultsInteger\": \"hl:MaxResultsInteger\",\n    \"S3Configuration\": \"hl:S3Configuration\",\n    \"PreloadDataType\": \"hl:PreloadDataType\",\n    \"TagKey\": \"hl:TagKey\",\n    \"TagValue\": \"hl:TagValue\",\n    \"Tag\": \"hl:Tag\",\n    \"TagKeyList\": \"hl:TagKeyList\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/json-ld/amazon-healthlake-context.jsonld
tags:
- FHIR
- Health Data
- Healthcare
- HIPAA
- Cloud Computing
- JSON-LD
- Linked Data
- Semantic Web
---
