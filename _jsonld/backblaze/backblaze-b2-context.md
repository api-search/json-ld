---
api_specs:
- filename: backblaze-b2-native-api.yaml
  format: yaml
  label: Backblaze B2 Cloud Storage API
  slug: backblaze-b2-cloud-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backblaze/refs/heads/main/openapi/backblaze-b2-native-api.yaml
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
source_filename: backblaze-b2-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"b2\": \"https://www.backblaze.com/apidocs/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AllowedCapabilities\": \"b2:AllowedCapabilities\",\n    \"ApiInfo\": \"b2:ApiInfo\",\n    \"ApplicationKey\": \"b2:ApplicationKey\",\n    \"AuthorizeAccountResponse\": \"b2:AuthorizeAccountResponse\",\n    \"Bucket\": \"b2:Bucket\",\n    \"BucketNotificationRulesResponse\": \"b2:BucketNotificationRulesResponse\",\n    \"CancelLargeFileRequest\": \"b2:CancelLargeFileRequest\",\n    \"CancelLargeFileResponse\": \"b2:CancelLargeFileResponse\",\n    \"CopyFileRequest\": \"b2:CopyFileRequest\",\n    \"CreateBucketRequest\": \"b2:CreateBucketRequest\",\n    \"CreateKeyRequest\": \"b2:CreateKeyRequest\",\n    \"DeleteBucketRequest\": \"b2:DeleteBucketRequest\",\n    \"DeleteFileVersionRequest\": \"b2:DeleteFileVersionRequest\",\n\
  \    \"DeleteFileVersionResponse\": \"b2:DeleteFileVersionResponse\",\n    \"DeleteKeyRequest\": \"b2:DeleteKeyRequest\",\n    \"FileInfo\": \"b2:FileInfo\",\n    \"FinishLargeFileRequest\": \"b2:FinishLargeFileRequest\",\n    \"GetBucketNotificationRulesRequest\": \"b2:GetBucketNotificationRulesRequest\",\n    \"GetDownloadAuthorizationRequest\": \"b2:GetDownloadAuthorizationRequest\",\n    \"GetDownloadAuthorizationResponse\": \"b2:GetDownloadAuthorizationResponse\",\n    \"GetFileInfoRequest\": \"b2:GetFileInfoRequest\",\n    \"GetUploadPartUrlRequest\": \"b2:GetUploadPartUrlRequest\",\n    \"GetUploadPartUrlResponse\": \"b2:GetUploadPartUrlResponse\",\n    \"GetUploadUrlRequest\": \"b2:GetUploadUrlRequest\",\n    \"GetUploadUrlResponse\": \"b2:GetUploadUrlResponse\",\n    \"HideFileRequest\": \"b2:HideFileRequest\",\n    \"ListBucketsRequest\": \"b2:ListBucketsRequest\",\n    \"ListBucketsResponse\": \"b2:ListBucketsResponse\",\n    \"ListFileNamesRequest\": \"b2:ListFileNamesRequest\"\
  ,\n    \"ListFileNamesResponse\": \"b2:ListFileNamesResponse\",\n    \"ListFileVersionsRequest\": \"b2:ListFileVersionsRequest\",\n    \"ListFileVersionsResponse\": \"b2:ListFileVersionsResponse\",\n    \"ListKeysRequest\": \"b2:ListKeysRequest\",\n    \"ListKeysResponse\": \"b2:ListKeysResponse\",\n    \"ListPartsRequest\": \"b2:ListPartsRequest\",\n    \"ListPartsResponse\": \"b2:ListPartsResponse\",\n    \"ListUnfinishedLargeFilesRequest\": \"b2:ListUnfinishedLargeFilesRequest\",\n    \"ListUnfinishedLargeFilesResponse\": \"b2:ListUnfinishedLargeFilesResponse\",\n    \"NotificationRule\": \"b2:NotificationRule\",\n    \"SetBucketNotificationRulesRequest\": \"b2:SetBucketNotificationRulesRequest\",\n    \"StartLargeFileRequest\": \"b2:StartLargeFileRequest\",\n    \"UpdateBucketRequest\": \"b2:UpdateBucketRequest\",\n    \"absoluteMinimumPartSize\": {\n      \"@id\": \"b2:absoluteMinimumPartSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accountId\": {\n      \"@id\": \"b2:accountId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"b2:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowed\": {\n      \"@id\": \"b2:allowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiInfo\": {\n      \"@id\": \"b2:apiInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiUrl\": {\n      \"@id\": \"b2:apiUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationKey\": {\n      \"@id\": \"b2:applicationKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationKeyId\": {\n      \"@id\": \"b2:applicationKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizationToken\": {\n      \"@id\": \"b2:authorizationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketId\": {\n      \"@id\": \"b2:bucketId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketInfo\": {\n      \"@id\": \"b2:bucketInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketName\": {\n      \"@id\": \"b2:bucketName\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"bucketType\": {\n      \"@id\": \"b2:bucketType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketTypes\": {\n      \"@id\": \"b2:bucketTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buckets\": {\n      \"@id\": \"b2:buckets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bypassGovernance\": {\n      \"@id\": \"b2:bypassGovernance\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"capabilities\": {\n      \"@id\": \"b2:capabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentLength\": {\n      \"@id\": \"b2:contentLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contentSha1\": {\n      \"@id\": \"b2:contentSha1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"b2:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"corsRules\": {\n      \"@id\": \"b2:corsRules\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delimiter\": {\n      \"@id\": \"b2:delimiter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationBucketId\": {\n      \"@id\": \"b2:destinationBucketId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"b2:downloadUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTypes\": {\n      \"@id\": \"b2:eventTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationTimestamp\": {\n      \"@id\": \"b2:expirationTimestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fileId\": {\n      \"@id\": \"b2:fileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileInfo\": {\n      \"@id\": \"b2:fileInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"b2:fileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileNamePrefix\": {\n      \"@id\": \"b2:fileNamePrefix\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"b2:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ifRevisionIs\": {\n      \"@id\": \"b2:ifRevisionIs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"b2:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"keyName\": {\n      \"@id\": \"b2:keyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keys\": {\n      \"@id\": \"b2:keys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleRules\": {\n      \"@id\": \"b2:lifecycleRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxFileCount\": {\n      \"@id\": \"b2:maxFileCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxKeyCount\": {\n      \"@id\": \"b2:maxKeyCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxPartCount\": {\n      \"@id\": \"b2:maxPartCount\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"metadataDirective\": {\n      \"@id\": \"b2:metadataDirective\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"namePrefix\": {\n      \"@id\": \"b2:namePrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextApplicationKeyId\": {\n      \"@id\": \"b2:nextApplicationKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextFileId\": {\n      \"@id\": \"b2:nextFileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextFileName\": {\n      \"@id\": \"b2:nextFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextPartNumber\": {\n      \"@id\": \"b2:nextPartNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partNumber\": {\n      \"@id\": \"b2:partNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partSha1Array\": {\n      \"@id\": \"b2:partSha1Array\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parts\": {\n      \"@id\": \"b2:parts\",\n     \
  \ \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"b2:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"range\": {\n      \"@id\": \"b2:range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedPartSize\": {\n      \"@id\": \"b2:recommendedPartSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"revision\": {\n      \"@id\": \"b2:revision\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rules\": {\n      \"@id\": \"b2:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3ApiUrl\": {\n      \"@id\": \"b2:s3ApiUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverSideEncryption\": {\n      \"@id\": \"b2:serverSideEncryption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceFileId\": {\n      \"@id\": \"b2:sourceFileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startApplicationKeyId\": {\n      \"@id\": \"b2:startApplicationKeyId\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"startFileId\": {\n      \"@id\": \"b2:startFileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startFileName\": {\n      \"@id\": \"b2:startFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startPartNumber\": {\n      \"@id\": \"b2:startPartNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"storageApi\": {\n      \"@id\": \"b2:storageApi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetConfiguration\": {\n      \"@id\": \"b2:targetConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetType\": {\n      \"@id\": \"b2:targetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadTimestamp\": {\n      \"@id\": \"b2:uploadTimestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"uploadUrl\": {\n      \"@id\": \"b2:uploadUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"validDurationInSeconds\": {\n      \"@id\": \"b2:validDurationInSeconds\",\n\
  \      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/backblaze/refs/heads/main/json-ld/backblaze-b2-context.jsonld
tags:
- Cloud Storage
- Object Storage
- Storage
- Backup
- JSON-LD
- Linked Data
- Semantic Web
---
