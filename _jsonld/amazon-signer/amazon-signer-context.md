---
api_specs:
- filename: amazon-signer.yaml
  format: yaml
  label: AWS Signer API
  slug: aws-signer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/openapi/amazon-signer.yaml
class_count: 60
classes:
- AddProfilePermissionRequest
- AddProfilePermissionResponse
- CancelSigningProfileRequest
- DescribeSigningJobRequest
- DescribeSigningJobResponse
- Destination
- EncryptionAlgorithmOptions
- GetRevocationStatusRequest
- GetRevocationStatusResponse
- GetSigningPlatformRequest
- GetSigningPlatformResponse
- GetSigningProfileRequest
- GetSigningProfileResponse
- HashAlgorithmOptions
- ListProfilePermissionsRequest
- ListProfilePermissionsResponse
- ListSigningJobsRequest
- ListSigningJobsResponse
- ListSigningPlatformsRequest
- ListSigningPlatformsResponse
- ListSigningProfilesRequest
- ListSigningProfilesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- Metadata
- Permission
- PutSigningProfileRequest
- PutSigningProfileResponse
- RemoveProfilePermissionRequest
- RemoveProfilePermissionResponse
- RevokeSignatureRequest
- RevokeSigningProfileRequest
- S3Destination
- S3SignedObject
- S3Source
- SignPayloadRequest
- SignPayloadResponse
- SignatureValidityPeriod
- SignedObject
- SigningConfigurationOverrides
- SigningConfiguration
- SigningImageFormat
- SigningJobRevocationRecord
- SigningJob
- SigningMaterial
- SigningParameters
- SigningPlatformOverrides
- SigningPlatform
- SigningProfileRevocationRecord
- SigningProfile
- Source
- StartSigningJobRequest
- StartSigningJobResponse
- TagMap
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- createdAt
- version
context_file: json-ld/amazon-signer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/json-ld/amazon-signer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Signer from Amazon Signer.
layout: jsonld
name: Amazon Signer Context
namespaces:
- prefix: amazon
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: profileVersion
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: principal
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: statementId
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: signingMaterial
  type: string
- container: ''
  name: platformId
  type: string
- container: ''
  name: platformDisplayName
  type: string
- container: ''
  name: profileName
  type: string
- container: ''
  name: overrides
  type: string
- container: ''
  name: signingParameters
  type: string
- container: ''
  name: completedAt
  type: string
- container: ''
  name: signatureExpiresAt
  type: string
- container: ''
  name: requestedBy
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: revocationRecord
  type: string
- container: ''
  name: signedObject
  type: string
- container: ''
  name: jobOwner
  type: string
- container: ''
  name: jobInvoker
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: allowedValues
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: revokedEntities
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: partner
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: signingConfiguration
  type: string
- container: ''
  name: signingImageFormat
  type: string
- container: ''
  name: maxSizeInMB
  type: string
- container: ''
  name: revocationSupported
  type: string
- container: ''
  name: profileVersionArn
  type: string
- container: ''
  name: revocationEffectiveFrom
  type: string
- container: ''
  name: revokedAt
  type: string
- container: ''
  name: revokedBy
  type: string
- container: ''
  name: signatureValidityPeriod
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: policySizeBytes
  type: string
- container: ''
  name: permissions
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: jobs
  type: string
- container: ''
  name: platforms
  type: string
- container: ''
  name: profiles
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: effectiveTime
  type: string
- container: ''
  name: bucketName
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: profileOwner
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: payloadFormat
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: signature
  type: string
- container: ''
  name: encryptionAlgorithm
  type: string
- container: ''
  name: hashAlgorithm
  type: string
- container: ''
  name: encryptionAlgorithmOptions
  type: string
- container: ''
  name: hashAlgorithmOptions
  type: string
- container: ''
  name: supportedFormats
  type: string
- container: ''
  name: defaultFormat
  type: string
- container: ''
  name: isRevoked
  type: string
- container: ''
  name: certificateArn
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: clientRequestToken
  type: string
property_count: 69
provider_name: Amazon Signer
provider_slug: amazon-signer
slug: amazon-signer-context
source_filename: amazon-signer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddProfilePermissionRequest\": \"amazon:AddProfilePermissionRequest\",\n    \"AddProfilePermissionResponse\": \"amazon:AddProfilePermissionResponse\",\n    \"CancelSigningProfileRequest\": \"amazon:CancelSigningProfileRequest\",\n    \"DescribeSigningJobRequest\": \"amazon:DescribeSigningJobRequest\",\n    \"DescribeSigningJobResponse\": \"amazon:DescribeSigningJobResponse\",\n    \"Destination\": \"amazon:Destination\",\n    \"EncryptionAlgorithmOptions\": \"amazon:EncryptionAlgorithmOptions\",\n    \"GetRevocationStatusRequest\": \"amazon:GetRevocationStatusRequest\",\n    \"GetRevocationStatusResponse\": \"amazon:GetRevocationStatusResponse\",\n    \"GetSigningPlatformRequest\": \"amazon:GetSigningPlatformRequest\",\n    \"GetSigningPlatformResponse\"\
  : \"amazon:GetSigningPlatformResponse\",\n    \"GetSigningProfileRequest\": \"amazon:GetSigningProfileRequest\",\n    \"GetSigningProfileResponse\": \"amazon:GetSigningProfileResponse\",\n    \"HashAlgorithmOptions\": \"amazon:HashAlgorithmOptions\",\n    \"ListProfilePermissionsRequest\": \"amazon:ListProfilePermissionsRequest\",\n    \"ListProfilePermissionsResponse\": \"amazon:ListProfilePermissionsResponse\",\n    \"ListSigningJobsRequest\": \"amazon:ListSigningJobsRequest\",\n    \"ListSigningJobsResponse\": \"amazon:ListSigningJobsResponse\",\n    \"ListSigningPlatformsRequest\": \"amazon:ListSigningPlatformsRequest\",\n    \"ListSigningPlatformsResponse\": \"amazon:ListSigningPlatformsResponse\",\n    \"ListSigningProfilesRequest\": \"amazon:ListSigningProfilesRequest\",\n    \"ListSigningProfilesResponse\": \"amazon:ListSigningProfilesResponse\",\n    \"ListTagsForResourceRequest\": \"amazon:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amazon:ListTagsForResourceResponse\"\
  ,\n    \"Metadata\": \"amazon:Metadata\",\n    \"Permission\": \"amazon:Permission\",\n    \"PutSigningProfileRequest\": \"amazon:PutSigningProfileRequest\",\n    \"PutSigningProfileResponse\": \"amazon:PutSigningProfileResponse\",\n    \"RemoveProfilePermissionRequest\": \"amazon:RemoveProfilePermissionRequest\",\n    \"RemoveProfilePermissionResponse\": \"amazon:RemoveProfilePermissionResponse\",\n    \"RevokeSignatureRequest\": \"amazon:RevokeSignatureRequest\",\n    \"RevokeSigningProfileRequest\": \"amazon:RevokeSigningProfileRequest\",\n    \"S3Destination\": \"amazon:S3Destination\",\n    \"S3SignedObject\": \"amazon:S3SignedObject\",\n    \"S3Source\": \"amazon:S3Source\",\n    \"SignPayloadRequest\": \"amazon:SignPayloadRequest\",\n    \"SignPayloadResponse\": \"amazon:SignPayloadResponse\",\n    \"SignatureValidityPeriod\": \"amazon:SignatureValidityPeriod\",\n    \"SignedObject\": \"amazon:SignedObject\",\n    \"SigningConfigurationOverrides\": \"amazon:SigningConfigurationOverrides\"\
  ,\n    \"SigningConfiguration\": \"amazon:SigningConfiguration\",\n    \"SigningImageFormat\": \"amazon:SigningImageFormat\",\n    \"SigningJobRevocationRecord\": \"amazon:SigningJobRevocationRecord\",\n    \"SigningJob\": \"amazon:SigningJob\",\n    \"SigningMaterial\": \"amazon:SigningMaterial\",\n    \"SigningParameters\": \"amazon:SigningParameters\",\n    \"SigningPlatformOverrides\": \"amazon:SigningPlatformOverrides\",\n    \"SigningPlatform\": \"amazon:SigningPlatform\",\n    \"SigningProfileRevocationRecord\": \"amazon:SigningProfileRevocationRecord\",\n    \"SigningProfile\": \"amazon:SigningProfile\",\n    \"Source\": \"amazon:Source\",\n    \"StartSigningJobRequest\": \"amazon:StartSigningJobRequest\",\n    \"StartSigningJobResponse\": \"amazon:StartSigningJobResponse\",\n    \"TagMap\": \"amazon:TagMap\",\n    \"TagResourceRequest\": \"amazon:TagResourceRequest\",\n    \"TagResourceResponse\": \"amazon:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amazon:UntagResourceRequest\"\
  ,\n    \"UntagResourceResponse\": \"amazon:UntagResourceResponse\",\n    \"profileVersion\": {\n      \"@id\": \"amazon:profileVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amazon:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principal\": {\n      \"@id\": \"amazon:principal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"amazon:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statementId\": {\n      \"@id\": \"amazon:statementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"amazon:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amazon:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingMaterial\": {\n      \"@id\": \"amazon:signingMaterial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformId\": {\n      \"@id\": \"amazon:platformId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformDisplayName\"\
  : {\n      \"@id\": \"amazon:platformDisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileName\": {\n      \"@id\": \"amazon:profileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overrides\": {\n      \"@id\": \"amazon:overrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingParameters\": {\n      \"@id\": \"amazon:signingParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"completedAt\": {\n      \"@id\": \"amazon:completedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatureExpiresAt\": {\n      \"@id\": \"amazon:signatureExpiresAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedBy\": {\n      \"@id\": \"amazon:requestedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amazon:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"amazon:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revocationRecord\"\
  : {\n      \"@id\": \"amazon:revocationRecord\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedObject\": {\n      \"@id\": \"amazon:signedObject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobOwner\": {\n      \"@id\": \"amazon:jobOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobInvoker\": {\n      \"@id\": \"amazon:jobInvoker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"amazon:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedValues\": {\n      \"@id\": \"amazon:allowedValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"amazon:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revokedEntities\": {\n      \"@id\": \"amazon:revokedEntities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amazon:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partner\": {\n      \"@id\": \"amazon:partner\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"target\": {\n      \"@id\": \"amazon:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amazon:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingConfiguration\": {\n      \"@id\": \"amazon:signingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signingImageFormat\": {\n      \"@id\": \"amazon:signingImageFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxSizeInMB\": {\n      \"@id\": \"amazon:maxSizeInMB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revocationSupported\": {\n      \"@id\": \"amazon:revocationSupported\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileVersionArn\": {\n      \"@id\": \"amazon:profileVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revocationEffectiveFrom\": {\n      \"@id\": \"amazon:revocationEffectiveFrom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revokedAt\": {\n      \"@id\": \"amazon:revokedAt\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"revokedBy\": {\n      \"@id\": \"amazon:revokedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatureValidityPeriod\": {\n      \"@id\": \"amazon:signatureValidityPeriod\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"amazon:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amazon:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amazon:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amazon:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policySizeBytes\": {\n      \"@id\": \"amazon:policySizeBytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permissions\": {\n      \"@id\": \"amazon:permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobs\": {\n      \"@id\": \"amazon:jobs\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"platforms\": {\n      \"@id\": \"amazon:platforms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profiles\": {\n      \"@id\": \"amazon:profiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"amazon:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveTime\": {\n      \"@id\": \"amazon:effectiveTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketName\": {\n      \"@id\": \"amazon:bucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"amazon:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amazon:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"profileOwner\": {\n      \"@id\": \"amazon:profileOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"amazon:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payloadFormat\": {\n      \"@id\": \"amazon:payloadFormat\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amazon:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signature\": {\n      \"@id\": \"amazon:signature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionAlgorithm\": {\n      \"@id\": \"amazon:encryptionAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hashAlgorithm\": {\n      \"@id\": \"amazon:hashAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionAlgorithmOptions\": {\n      \"@id\": \"amazon:encryptionAlgorithmOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hashAlgorithmOptions\": {\n      \"@id\": \"amazon:hashAlgorithmOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedFormats\": {\n      \"@id\": \"amazon:supportedFormats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultFormat\": {\n      \"@id\": \"amazon:defaultFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isRevoked\": {\n      \"@id\": \"amazon:isRevoked\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateArn\": {\n      \"@id\": \"amazon:certificateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"amazon:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientRequestToken\": {\n      \"@id\": \"amazon:clientRequestToken\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/json-ld/amazon-signer-context.jsonld
tags:
- AWS
- Code Signing
- IoT
- Lambda
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
