---
api_specs:
- filename: aws-s3-openapi.yaml
  format: yaml
  label: Amazon S3 REST API
  slug: amazon-s3-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/openapi/aws-s3-openapi.yaml
class_count: 30
classes:
- AbortMultipartUploadOutput
- NoSuchUpload
- CompleteMultipartUploadOutput
- CompletedPartList
- CopyObjectOutput
- MetadataValue
- ObjectNotInActiveTierError
- CreateBucketOutput
- BucketLocationConstraint
- BucketAlreadyExists
- BucketAlreadyOwnedByYou
- CreateMultipartUploadOutput
- DeleteObjectOutput
- DeleteObjectTaggingOutput
- DeleteObjectsOutput
- ObjectIdentifierList
- Quiet
- GetBucketAccelerateConfigurationOutput
- GetBucketAclOutput
- GetBucketAnalyticsConfigurationOutput
- GetBucketCorsOutput
- GetBucketEncryptionOutput
- GetBucketIntelligentTieringConfigurationOutput
- GetBucketInventoryConfigurationOutput
- GetBucketLifecycleOutput
- GetBucketLifecycleConfigurationOutput
- GetBucketLocationOutput
- GetBucketLoggingOutput
- GetBucketMetricsConfigurationOutput
- NotificationConfigurationDeprecated
context_file: json-ld/aws-s3-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/json-ld/aws-s3-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws S3 from Amazon S3 API.
layout: jsonld
name: Aws S3 Context
namespaces:
- prefix: s3
  uri: https://docs.aws.amazon.com/AmazonS3/latest/API/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Amazon S3 API
provider_slug: aws-s3
slug: aws-s3-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"s3\": \"https://docs.aws.amazon.com/AmazonS3/latest/API/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AbortMultipartUploadOutput\": \"s3:AbortMultipartUploadOutput\",\n    \"NoSuchUpload\": \"s3:NoSuchUpload\",\n    \"CompleteMultipartUploadOutput\": \"s3:CompleteMultipartUploadOutput\",\n    \"CompletedPartList\": \"s3:CompletedPartList\",\n    \"CopyObjectOutput\": \"s3:CopyObjectOutput\",\n    \"MetadataValue\": \"s3:MetadataValue\",\n    \"ObjectNotInActiveTierError\": \"s3:ObjectNotInActiveTierError\",\n    \"CreateBucketOutput\": \"s3:CreateBucketOutput\",\n    \"BucketLocationConstraint\": \"s3:BucketLocationConstraint\",\n    \"BucketAlreadyExists\": \"s3:BucketAlreadyExists\",\n    \"BucketAlreadyOwnedByYou\": \"s3:BucketAlreadyOwnedByYou\",\n    \"CreateMultipartUploadOutput\": \"s3:CreateMultipartUploadOutput\",\n    \"DeleteObjectOutput\": \"s3:DeleteObjectOutput\"\
  ,\n    \"DeleteObjectTaggingOutput\": \"s3:DeleteObjectTaggingOutput\",\n    \"DeleteObjectsOutput\": \"s3:DeleteObjectsOutput\",\n    \"ObjectIdentifierList\": \"s3:ObjectIdentifierList\",\n    \"Quiet\": \"s3:Quiet\",\n    \"GetBucketAccelerateConfigurationOutput\": \"s3:GetBucketAccelerateConfigurationOutput\",\n    \"GetBucketAclOutput\": \"s3:GetBucketAclOutput\",\n    \"GetBucketAnalyticsConfigurationOutput\": \"s3:GetBucketAnalyticsConfigurationOutput\",\n    \"GetBucketCorsOutput\": \"s3:GetBucketCorsOutput\",\n    \"GetBucketEncryptionOutput\": \"s3:GetBucketEncryptionOutput\",\n    \"GetBucketIntelligentTieringConfigurationOutput\": \"s3:GetBucketIntelligentTieringConfigurationOutput\",\n    \"GetBucketInventoryConfigurationOutput\": \"s3:GetBucketInventoryConfigurationOutput\",\n    \"GetBucketLifecycleOutput\": \"s3:GetBucketLifecycleOutput\",\n    \"GetBucketLifecycleConfigurationOutput\": \"s3:GetBucketLifecycleConfigurationOutput\",\n    \"GetBucketLocationOutput\": \"s3:GetBucketLocationOutput\"\
  ,\n    \"GetBucketLoggingOutput\": \"s3:GetBucketLoggingOutput\",\n    \"GetBucketMetricsConfigurationOutput\": \"s3:GetBucketMetricsConfigurationOutput\",\n    \"NotificationConfigurationDeprecated\": \"s3:NotificationConfigurationDeprecated\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/json-ld/aws-s3-context.jsonld
tags:
- AWS
- Cloud Storage
- Object Storage
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
