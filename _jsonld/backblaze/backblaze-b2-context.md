---
class_count: 42
classes:
- AllowedCapabilities
- ApiInfo
- ApplicationKey
- AuthorizeAccountResponse
- Bucket
- BucketNotificationRulesResponse
- CancelLargeFileRequest
- CancelLargeFileResponse
- CopyFileRequest
- CreateBucketRequest
- CreateKeyRequest
- DeleteBucketRequest
- DeleteFileVersionRequest
- DeleteFileVersionResponse
- DeleteKeyRequest
- FileInfo
- FinishLargeFileRequest
- GetBucketNotificationRulesRequest
- GetDownloadAuthorizationRequest
- GetDownloadAuthorizationResponse
- GetFileInfoRequest
- GetUploadPartUrlRequest
- GetUploadPartUrlResponse
- GetUploadUrlRequest
- GetUploadUrlResponse
- HideFileRequest
- ListBucketsRequest
- ListBucketsResponse
- ListFileNamesRequest
- ListFileNamesResponse
- ListFileVersionsRequest
- ListFileVersionsResponse
- ListKeysRequest
- ListKeysResponse
- ListPartsRequest
- ListPartsResponse
- ListUnfinishedLargeFilesRequest
- ListUnfinishedLargeFilesResponse
- NotificationRule
- SetBucketNotificationRulesRequest
- StartLargeFileRequest
- UpdateBucketRequest
context_file: json-ld/backblaze-b2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/backblaze/refs/heads/main/json-ld/backblaze-b2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Backblaze B2 from Backblaze.
layout: jsonld
name: Backblaze B2 Context
namespaces:
- prefix: b2
  uri: https://www.backblaze.com/apidocs/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: absoluteMinimumPartSize
  type: integer
- container: ''
  name: accountId
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: allowed
  type: string
- container: ''
  name: apiInfo
  type: string
- container: ''
  name: apiUrl
  type: string
- container: ''
  name: applicationKey
  type: string
- container: ''
  name: applicationKeyId
  type: string
- container: ''
  name: authorizationToken
  type: string
- container: ''
  name: bucketId
  type: string
- container: ''
  name: bucketInfo
  type: string
- container: ''
  name: bucketName
  type: string
- container: ''
  name: bucketType
  type: string
- container: set
  name: bucketTypes
  type: string
- container: set
  name: buckets
  type: string
- container: ''
  name: bypassGovernance
  type: boolean
- container: set
  name: capabilities
  type: string
- container: ''
  name: contentLength
  type: integer
- container: ''
  name: contentSha1
  type: string
- container: ''
  name: contentType
  type: string
- container: set
  name: corsRules
  type: string
- container: ''
  name: delimiter
  type: string
- container: ''
  name: destinationBucketId
  type: string
- container: ''
  name: downloadUrl
  type: string
- container: set
  name: eventTypes
  type: string
- container: ''
  name: expirationTimestamp
  type: integer
- container: ''
  name: fileId
  type: string
- container: ''
  name: fileInfo
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: fileNamePrefix
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: ifRevisionIs
  type: integer
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: keyName
  type: string
- container: set
  name: keys
  type: string
- container: set
  name: lifecycleRules
  type: string
- container: ''
  name: maxFileCount
  type: integer
- container: ''
  name: maxKeyCount
  type: integer
- container: ''
  name: maxPartCount
  type: integer
- container: ''
  name: metadataDirective
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: namePrefix
  type: string
- container: ''
  name: nextApplicationKeyId
  type: string
- container: ''
  name: nextFileId
  type: string
- container: ''
  name: nextFileName
  type: string
- container: ''
  name: nextPartNumber
  type: integer
- container: ''
  name: partNumber
  type: integer
- container: set
  name: partSha1Array
  type: string
- container: set
  name: parts
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: range
  type: string
- container: ''
  name: recommendedPartSize
  type: integer
- container: ''
  name: revision
  type: integer
- container: set
  name: rules
  type: string
- container: ''
  name: s3ApiUrl
  type: string
- container: ''
  name: serverSideEncryption
  type: string
- container: ''
  name: sourceFileId
  type: string
- container: ''
  name: startApplicationKeyId
  type: string
- container: ''
  name: startFileId
  type: string
- container: ''
  name: startFileName
  type: string
- container: ''
  name: startPartNumber
  type: integer
- container: ''
  name: storageApi
  type: string
- container: ''
  name: targetConfiguration
  type: string
- container: ''
  name: targetType
  type: string
- container: ''
  name: uploadTimestamp
  type: integer
- container: ''
  name: uploadUrl
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: validDurationInSeconds
  type: integer
property_count: 68
provider_name: Backblaze
provider_slug: backblaze
slug: backblaze-b2-context
tags:
- Cloud Storage
- Object Storage
- Storage
- Backup
- JSON-LD
- Linked Data
- Semantic Web
---
