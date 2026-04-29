---
api_specs:
- filename: amazon-codeartifact-openapi-original.yaml
  format: yaml
  label: Amazon CodeArtifact API
  slug: amazon-codeartifact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codeartifact/refs/heads/main/openapi/amazon-codeartifact-openapi-original.yaml
class_count: 106
classes:
- UpdateRepositoryResult
- RepositoryExternalConnectionInfo
- AssetSummary
- Tag
- PackageOriginConfiguration
- ListPackageVersionAssetsResult
- DescribeDomainRequest
- DeleteRepositoryPermissionsPolicyResult
- DescribePackageResult
- ListPackageVersionDependenciesResult
- UpdatePackageVersionsStatusResult
- TagResourceRequest
- DeleteRepositoryResult
- DeletePackageVersionsRequest
- DescribePackageVersionRequest
- GetAuthorizationTokenResult
- PackageVersionError
- DeleteRepositoryRequest
- GetPackageVersionAssetResult
- PutRepositoryPermissionsPolicyResult
- GetDomainPermissionsPolicyResult
- RepositoryDescription
- DomainSummary
- RepositorySummary
- DomainEntryPoint
- GetPackageVersionReadmeResult
- UntagResourceRequest
- ResourcePolicy
- DomainDescription
- PackageVersionDescription
- UpdateRepositoryRequest
- SuccessfulPackageVersionInfoMap
- DeletePackageVersionsResult
- AssetHashes
- ListRepositoriesInDomainResult
- DescribePackageRequest
- UpdatePackageVersionsStatusRequest
- ListRepositoriesResult
- PublishPackageVersionRequest
- DeleteRepositoryPermissionsPolicyRequest
- CreateRepositoryRequest
- DeletePackageRequest
- ListPackagesRequest
- ListRepositoriesInDomainRequest
- PackageOriginRestrictions
- SuccessfulPackageVersionInfo
- DescribeDomainResult
- DisposePackageVersionsResult
- LicenseInfo
- GetAuthorizationTokenRequest
- GetDomainPermissionsPolicyRequest
- AssociateExternalConnectionRequest
- PackageVersionRevisionMap
- DeleteDomainPermissionsPolicyRequest
- ListPackageVersionDependenciesRequest
- CreateRepositoryResult
- GetPackageVersionReadmeRequest
- DisassociateExternalConnectionResult
- UpstreamRepositoryInfo
- DisposePackageVersionsRequest
- PackageVersionErrorMap
- GetRepositoryEndpointResult
- PublishPackageVersionResult
- DescribeRepositoryResult
- UpstreamRepository
- CreateDomainRequest
- ListDomainsResult
- AssociateExternalConnectionResult
- GetRepositoryPermissionsPolicyResult
- PackageDescription
- DescribePackageVersionResult
- DeleteDomainResult
- ListPackageVersionsResult
- ListPackageVersionsRequest
- GetRepositoryPermissionsPolicyRequest
- UntagResourceResult
- PutDomainPermissionsPolicyResult
- ListRepositoriesRequest
- PutRepositoryPermissionsPolicyRequest
- PutDomainPermissionsPolicyRequest
- DeletePackageResult
- CopyPackageVersionsResult
- PackageDependency
- DeleteDomainPermissionsPolicyResult
- PackageSummary
- DeleteDomainRequest
- PutPackageOriginConfigurationResult
- ListPackageVersionAssetsRequest
- PutPackageOriginConfigurationRequest
- GetPackageVersionAssetRequest
- DisassociateExternalConnectionRequest
- ListTagsForResourceRequest
- CreateDomainResult
- ListDomainsRequest
- PackageVersionOrigin
- ListTagsForResourceResult
- PackageVersionSummary
- DescribeRepositoryRequest
- GetRepositoryEndpointRequest
- ListPackagesResult
- TagResourceResult
- CopyPackageVersionsRequest
- name
- version
- description
- url
context_file: json-ld/amazon-codeartifact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeartifact/refs/heads/main/json-ld/amazon-codeartifact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codeartifact from Amazon CodeArtifact.
layout: jsonld
name: Amazon Codeartifact Context
namespaces:
- prefix: amz
  uri: https://codeartifact.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: repository
  type: string
- container: ''
  name: externalConnectionName
  type: string
- container: ''
  name: packageFormat
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: size
  type: string
- container: ''
  name: hashes
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: restrictions
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: package
  type: string
- container: ''
  name: versionRevision
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: assets
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: dependencies
  type: string
- container: ''
  name: successfulVersions
  type: string
- container: ''
  name: failedVersions
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: versions
  type: string
- container: ''
  name: expectedStatus
  type: string
- container: ''
  name: authorizationToken
  type: string
- container: ''
  name: expiration
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: asset
  type: string
- container: ''
  name: administratorAccount
  type: string
- container: ''
  name: domainName
  type: string
- container: ''
  name: domainOwner
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: upstreams
  type: string
- container: ''
  name: externalConnections
  type: string
- container: ''
  name: createdTime
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: encryptionKey
  type: string
- container: ''
  name: repositoryName
  type: string
- container: ''
  name: readme
  type: string
- container: ''
  name: tagKeys
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: document
  type: string
- container: ''
  name: repositoryCount
  type: string
- container: ''
  name: assetSizeBytes
  type: string
- container: ''
  name: s3BucketArn
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: homePage
  type: string
- container: ''
  name: sourceCodeRepository
  type: string
- container: ''
  name: publishedTime
  type: string
- container: ''
  name: licenses
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: repositories
  type: string
- container: ''
  name: versionRevisions
  type: string
- container: ''
  name: targetStatus
  type: string
- container: ''
  name: assetContent
  type: string
- container: ''
  name: publish
  type: string
- container: ''
  name: upstream
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: repositoryEndpoint
  type: string
- container: ''
  name: domains
  type: string
- container: ''
  name: originConfiguration
  type: string
- container: ''
  name: packageVersion
  type: string
- container: ''
  name: defaultDisplayVersion
  type: string
- container: ''
  name: policyRevision
  type: string
- container: ''
  name: policyDocument
  type: string
- container: ''
  name: deletedPackage
  type: string
- container: ''
  name: dependencyType
  type: string
- container: ''
  name: versionRequirement
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: domainEntryPoint
  type: string
- container: ''
  name: originType
  type: string
- container: ''
  name: packages
  type: string
- container: ''
  name: allowOverwrite
  type: string
- container: ''
  name: includeFromUpstream
  type: string
property_count: 76
provider_name: Amazon CodeArtifact
provider_slug: amazon-codeartifact
slug: amazon-codeartifact-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://codeartifact.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateRepositoryResult\": \"amz:UpdateRepositoryResult\",\n    \"RepositoryExternalConnectionInfo\": \"amz:RepositoryExternalConnectionInfo\",\n    \"AssetSummary\": \"amz:AssetSummary\",\n    \"Tag\": \"amz:Tag\",\n    \"PackageOriginConfiguration\": \"amz:PackageOriginConfiguration\",\n    \"ListPackageVersionAssetsResult\": \"amz:ListPackageVersionAssetsResult\",\n    \"DescribeDomainRequest\": \"amz:DescribeDomainRequest\",\n    \"DeleteRepositoryPermissionsPolicyResult\": \"amz:DeleteRepositoryPermissionsPolicyResult\",\n    \"DescribePackageResult\": \"amz:DescribePackageResult\",\n    \"ListPackageVersionDependenciesResult\": \"amz:ListPackageVersionDependenciesResult\",\n    \"UpdatePackageVersionsStatusResult\"\
  : \"amz:UpdatePackageVersionsStatusResult\",\n    \"TagResourceRequest\": \"amz:TagResourceRequest\",\n    \"DeleteRepositoryResult\": \"amz:DeleteRepositoryResult\",\n    \"DeletePackageVersionsRequest\": \"amz:DeletePackageVersionsRequest\",\n    \"DescribePackageVersionRequest\": \"amz:DescribePackageVersionRequest\",\n    \"GetAuthorizationTokenResult\": \"amz:GetAuthorizationTokenResult\",\n    \"PackageVersionError\": \"amz:PackageVersionError\",\n    \"DeleteRepositoryRequest\": \"amz:DeleteRepositoryRequest\",\n    \"GetPackageVersionAssetResult\": \"amz:GetPackageVersionAssetResult\",\n    \"PutRepositoryPermissionsPolicyResult\": \"amz:PutRepositoryPermissionsPolicyResult\",\n    \"GetDomainPermissionsPolicyResult\": \"amz:GetDomainPermissionsPolicyResult\",\n    \"RepositoryDescription\": \"amz:RepositoryDescription\",\n    \"DomainSummary\": \"amz:DomainSummary\",\n    \"RepositorySummary\": \"amz:RepositorySummary\",\n    \"DomainEntryPoint\": \"amz:DomainEntryPoint\",\n \
  \   \"GetPackageVersionReadmeResult\": \"amz:GetPackageVersionReadmeResult\",\n    \"UntagResourceRequest\": \"amz:UntagResourceRequest\",\n    \"ResourcePolicy\": \"amz:ResourcePolicy\",\n    \"DomainDescription\": \"amz:DomainDescription\",\n    \"PackageVersionDescription\": \"amz:PackageVersionDescription\",\n    \"UpdateRepositoryRequest\": \"amz:UpdateRepositoryRequest\",\n    \"SuccessfulPackageVersionInfoMap\": \"amz:SuccessfulPackageVersionInfoMap\",\n    \"DeletePackageVersionsResult\": \"amz:DeletePackageVersionsResult\",\n    \"AssetHashes\": \"amz:AssetHashes\",\n    \"ListRepositoriesInDomainResult\": \"amz:ListRepositoriesInDomainResult\",\n    \"DescribePackageRequest\": \"amz:DescribePackageRequest\",\n    \"UpdatePackageVersionsStatusRequest\": \"amz:UpdatePackageVersionsStatusRequest\",\n    \"ListRepositoriesResult\": \"amz:ListRepositoriesResult\",\n    \"PublishPackageVersionRequest\": \"amz:PublishPackageVersionRequest\",\n    \"DeleteRepositoryPermissionsPolicyRequest\"\
  : \"amz:DeleteRepositoryPermissionsPolicyRequest\",\n    \"CreateRepositoryRequest\": \"amz:CreateRepositoryRequest\",\n    \"DeletePackageRequest\": \"amz:DeletePackageRequest\",\n    \"ListPackagesRequest\": \"amz:ListPackagesRequest\",\n    \"ListRepositoriesInDomainRequest\": \"amz:ListRepositoriesInDomainRequest\",\n    \"PackageOriginRestrictions\": \"amz:PackageOriginRestrictions\",\n    \"SuccessfulPackageVersionInfo\": \"amz:SuccessfulPackageVersionInfo\",\n    \"DescribeDomainResult\": \"amz:DescribeDomainResult\",\n    \"DisposePackageVersionsResult\": \"amz:DisposePackageVersionsResult\",\n    \"LicenseInfo\": \"amz:LicenseInfo\",\n    \"GetAuthorizationTokenRequest\": \"amz:GetAuthorizationTokenRequest\",\n    \"GetDomainPermissionsPolicyRequest\": \"amz:GetDomainPermissionsPolicyRequest\",\n    \"AssociateExternalConnectionRequest\": \"amz:AssociateExternalConnectionRequest\",\n    \"PackageVersionRevisionMap\": \"amz:PackageVersionRevisionMap\",\n    \"DeleteDomainPermissionsPolicyRequest\"\
  : \"amz:DeleteDomainPermissionsPolicyRequest\",\n    \"ListPackageVersionDependenciesRequest\": \"amz:ListPackageVersionDependenciesRequest\",\n    \"CreateRepositoryResult\": \"amz:CreateRepositoryResult\",\n    \"GetPackageVersionReadmeRequest\": \"amz:GetPackageVersionReadmeRequest\",\n    \"DisassociateExternalConnectionResult\": \"amz:DisassociateExternalConnectionResult\",\n    \"UpstreamRepositoryInfo\": \"amz:UpstreamRepositoryInfo\",\n    \"DisposePackageVersionsRequest\": \"amz:DisposePackageVersionsRequest\",\n    \"PackageVersionErrorMap\": \"amz:PackageVersionErrorMap\",\n    \"GetRepositoryEndpointResult\": \"amz:GetRepositoryEndpointResult\",\n    \"PublishPackageVersionResult\": \"amz:PublishPackageVersionResult\",\n    \"DescribeRepositoryResult\": \"amz:DescribeRepositoryResult\",\n    \"UpstreamRepository\": \"amz:UpstreamRepository\",\n    \"CreateDomainRequest\": \"amz:CreateDomainRequest\",\n    \"ListDomainsResult\": \"amz:ListDomainsResult\",\n    \"AssociateExternalConnectionResult\"\
  : \"amz:AssociateExternalConnectionResult\",\n    \"GetRepositoryPermissionsPolicyResult\": \"amz:GetRepositoryPermissionsPolicyResult\",\n    \"PackageDescription\": \"amz:PackageDescription\",\n    \"DescribePackageVersionResult\": \"amz:DescribePackageVersionResult\",\n    \"DeleteDomainResult\": \"amz:DeleteDomainResult\",\n    \"ListPackageVersionsResult\": \"amz:ListPackageVersionsResult\",\n    \"ListPackageVersionsRequest\": \"amz:ListPackageVersionsRequest\",\n    \"GetRepositoryPermissionsPolicyRequest\": \"amz:GetRepositoryPermissionsPolicyRequest\",\n    \"UntagResourceResult\": \"amz:UntagResourceResult\",\n    \"PutDomainPermissionsPolicyResult\": \"amz:PutDomainPermissionsPolicyResult\",\n    \"ListRepositoriesRequest\": \"amz:ListRepositoriesRequest\",\n    \"PutRepositoryPermissionsPolicyRequest\": \"amz:PutRepositoryPermissionsPolicyRequest\",\n    \"PutDomainPermissionsPolicyRequest\": \"amz:PutDomainPermissionsPolicyRequest\",\n    \"DeletePackageResult\": \"amz:DeletePackageResult\"\
  ,\n    \"CopyPackageVersionsResult\": \"amz:CopyPackageVersionsResult\",\n    \"PackageDependency\": \"amz:PackageDependency\",\n    \"DeleteDomainPermissionsPolicyResult\": \"amz:DeleteDomainPermissionsPolicyResult\",\n    \"PackageSummary\": \"amz:PackageSummary\",\n    \"DeleteDomainRequest\": \"amz:DeleteDomainRequest\",\n    \"PutPackageOriginConfigurationResult\": \"amz:PutPackageOriginConfigurationResult\",\n    \"ListPackageVersionAssetsRequest\": \"amz:ListPackageVersionAssetsRequest\",\n    \"PutPackageOriginConfigurationRequest\": \"amz:PutPackageOriginConfigurationRequest\",\n    \"GetPackageVersionAssetRequest\": \"amz:GetPackageVersionAssetRequest\",\n    \"DisassociateExternalConnectionRequest\": \"amz:DisassociateExternalConnectionRequest\",\n    \"ListTagsForResourceRequest\": \"amz:ListTagsForResourceRequest\",\n    \"CreateDomainResult\": \"amz:CreateDomainResult\",\n    \"ListDomainsRequest\": \"amz:ListDomainsRequest\",\n    \"PackageVersionOrigin\": \"amz:PackageVersionOrigin\"\
  ,\n    \"ListTagsForResourceResult\": \"amz:ListTagsForResourceResult\",\n    \"PackageVersionSummary\": \"amz:PackageVersionSummary\",\n    \"DescribeRepositoryRequest\": \"amz:DescribeRepositoryRequest\",\n    \"GetRepositoryEndpointRequest\": \"amz:GetRepositoryEndpointRequest\",\n    \"ListPackagesResult\": \"amz:ListPackagesResult\",\n    \"TagResourceResult\": \"amz:TagResourceResult\",\n    \"CopyPackageVersionsRequest\": \"amz:CopyPackageVersionsRequest\",\n    \"repository\": {\n      \"@id\": \"amz:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalConnectionName\": {\n      \"@id\": \"amz:externalConnectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageFormat\": {\n      \"@id\": \"amz:packageFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"size\": {\n      \"@id\": \"amz:size\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"hashes\": {\n      \"@id\": \"amz:hashes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amz:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amz:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restrictions\": {\n      \"@id\": \"amz:restrictions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"amz:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"amz:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"package\": {\n      \"@id\": \"amz:package\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"versionRevision\": {\n      \"@id\": \"amz:versionRevision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amz:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assets\": {\n      \"@id\": \"amz:assets\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"policy\": {\n      \"@id\": \"amz:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependencies\": {\n      \"@id\": \"amz:dependencies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"successfulVersions\": {\n      \"@id\": \"amz:successfulVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedVersions\": {\n      \"@id\": \"amz:failedVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amz:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"amz:versions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expectedStatus\": {\n      \"@id\": \"amz:expectedStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizationToken\": {\n      \"@id\": \"amz:authorizationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"amz:expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"amz:errorCode\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"amz:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"asset\": {\n      \"@id\": \"amz:asset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"administratorAccount\": {\n      \"@id\": \"amz:administratorAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainName\": {\n      \"@id\": \"amz:domainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainOwner\": {\n      \"@id\": \"amz:domainOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amz:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"upstreams\": {\n      \"@id\": \"amz:upstreams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalConnections\": {\n      \"@id\": \"amz:externalConnections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"amz:createdTime\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"owner\": {\n      \"@id\": \"amz:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionKey\": {\n      \"@id\": \"amz:encryptionKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryName\": {\n      \"@id\": \"amz:repositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"readme\": {\n      \"@id\": \"amz:readme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagKeys\": {\n      \"@id\": \"amz:tagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArn\": {\n      \"@id\": \"amz:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"amz:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document\": {\n      \"@id\": \"amz:document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryCount\": {\n      \"@id\": \"amz:repositoryCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetSizeBytes\": {\n      \"@id\": \"amz:assetSizeBytes\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"s3BucketArn\": {\n      \"@id\": \"amz:s3BucketArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageName\": {\n      \"@id\": \"amz:packageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amz:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"amz:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"homePage\": {\n      \"@id\": \"amz:homePage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceCodeRepository\": {\n      \"@id\": \"amz:sourceCodeRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishedTime\": {\n      \"@id\": \"amz:publishedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenses\": {\n      \"@id\": \"amz:licenses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"amz:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositories\": {\n      \"@id\": \"amz:repositories\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"versionRevisions\": {\n      \"@id\": \"amz:versionRevisions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetStatus\": {\n      \"@id\": \"amz:targetStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetContent\": {\n      \"@id\": \"amz:assetContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publish\": {\n      \"@id\": \"amz:publish\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upstream\": {\n      \"@id\": \"amz:upstream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"amz:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"repositoryEndpoint\": {\n      \"@id\": \"amz:repositoryEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domains\": {\n      \"@id\": \"amz:domains\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originConfiguration\": {\n      \"@id\": \"amz:originConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageVersion\": {\n  \
  \    \"@id\": \"amz:packageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultDisplayVersion\": {\n      \"@id\": \"amz:defaultDisplayVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyRevision\": {\n      \"@id\": \"amz:policyRevision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyDocument\": {\n      \"@id\": \"amz:policyDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deletedPackage\": {\n      \"@id\": \"amz:deletedPackage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependencyType\": {\n      \"@id\": \"amz:dependencyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionRequirement\": {\n      \"@id\": \"amz:versionRequirement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amz:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainEntryPoint\": {\n      \"@id\": \"amz:domainEntryPoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originType\": {\n      \"@id\":\
  \ \"amz:originType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packages\": {\n      \"@id\": \"amz:packages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowOverwrite\": {\n      \"@id\": \"amz:allowOverwrite\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeFromUpstream\": {\n      \"@id\": \"amz:includeFromUpstream\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeartifact/refs/heads/main/json-ld/amazon-codeartifact-context.jsonld
tags:
- Amazon
- AWS
- Artifact Repository
- Package Management
- DevOps
- Software Supply Chain
- npm
- Maven
- PyPI
- NuGet
- JSON-LD
- Linked Data
- Semantic Web
---
