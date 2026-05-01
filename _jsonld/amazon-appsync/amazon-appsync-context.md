---
api_specs:
- filename: amazon-appsync-openapi.yml
  format: yaml
  label: Amazon AppSync API
  slug: amazon-appsync-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/openapi/amazon-appsync-openapi.yml
class_count: 73
classes:
- ErrorResponse
- GraphqlApi
- AdditionalAuthenticationProvider
- LogConfig
- LambdaAuthorizerConfig
- CognitoUserPoolConfig
- DataSource
- DynamodbDataSourceConfig
- LambdaDataSourceConfig
- ElasticsearchDataSourceConfig
- HttpDataSourceConfig
- Resolver
- PipelineConfig
- SyncConfig
- CachingConfig
- AppSyncRuntime
- FunctionConfiguration
- Type
- ApiKey
- DomainNameConfig
- ApiAssociation
- CreateGraphqlApiRequest
- CreateGraphqlApiResponse
- ListGraphqlApisResponse
- GetGraphqlApiResponse
- UpdateGraphqlApiRequest
- UpdateGraphqlApiResponse
- CreateDataSourceRequest
- CreateDataSourceResponse
- ListDataSourcesResponse
- GetDataSourceResponse
- UpdateDataSourceRequest
- UpdateDataSourceResponse
- CreateResolverRequest
- CreateResolverResponse
- ListResolversResponse
- GetResolverResponse
- UpdateResolverRequest
- UpdateResolverResponse
- CreateFunctionRequest
- CreateFunctionResponse
- ListFunctionsResponse
- GetFunctionResponse
- UpdateFunctionRequest
- UpdateFunctionResponse
- CreateTypeRequest
- CreateTypeResponse
- ListTypesResponse
- GetTypeResponse
- UpdateTypeRequest
- UpdateTypeResponse
- StartSchemaCreationRequest
- StartSchemaCreationResponse
- GetSchemaCreationStatusResponse
- CreateApiKeyRequest
- CreateApiKeyResponse
- ListApiKeysResponse
- UpdateApiKeyRequest
- UpdateApiKeyResponse
- CreateDomainNameRequest
- CreateDomainNameResponse
- ListDomainNamesResponse
- GetDomainNameResponse
- UpdateDomainNameRequest
- UpdateDomainNameResponse
- AssociateApiRequest
- AssociateApiResponse
- GetApiAssociationResponse
- ListTagsForResourceResponse
- TagResourceRequest
- EvaluateMappingTemplateRequest
- EvaluateMappingTemplateResponse
- GetIntrospectionSchemaResponse
context_file: json-ld/amazon-appsync-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-ld/amazon-appsync-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Appsync from Amazon AppSync.
layout: jsonld
name: Amazon Appsync Context
namespaces:
- prefix: appsync
  uri: https://api-evangelist.github.io/amazon-appsync/vocabulary/
- prefix: aws
  uri: https://aws.amazon.com/vocabulary/
properties: []
property_count: 0
provider_name: Amazon AppSync
provider_slug: amazon-appsync
slug: amazon-appsync-context
source_filename: amazon-appsync-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"appsync\": \"https://api-evangelist.github.io/amazon-appsync/vocabulary/\",\n    \"aws\": \"https://aws.amazon.com/vocabulary/\",\n    \"ErrorResponse\": \"appsync:ErrorResponse\",\n    \"GraphqlApi\": \"appsync:GraphqlApi\",\n    \"AdditionalAuthenticationProvider\": \"appsync:AdditionalAuthenticationProvider\",\n    \"LogConfig\": \"appsync:LogConfig\",\n    \"LambdaAuthorizerConfig\": \"appsync:LambdaAuthorizerConfig\",\n    \"CognitoUserPoolConfig\": \"appsync:CognitoUserPoolConfig\",\n    \"DataSource\": \"appsync:DataSource\",\n    \"DynamodbDataSourceConfig\": \"appsync:DynamodbDataSourceConfig\",\n    \"LambdaDataSourceConfig\": \"appsync:LambdaDataSourceConfig\",\n    \"ElasticsearchDataSourceConfig\": \"appsync:ElasticsearchDataSourceConfig\",\n    \"HttpDataSourceConfig\": \"appsync:HttpDataSourceConfig\",\n    \"Resolver\": \"appsync:Resolver\",\n    \"PipelineConfig\": \"appsync:PipelineConfig\"\
  ,\n    \"SyncConfig\": \"appsync:SyncConfig\",\n    \"CachingConfig\": \"appsync:CachingConfig\",\n    \"AppSyncRuntime\": \"appsync:AppSyncRuntime\",\n    \"FunctionConfiguration\": \"appsync:FunctionConfiguration\",\n    \"Type\": \"appsync:Type\",\n    \"ApiKey\": \"appsync:ApiKey\",\n    \"DomainNameConfig\": \"appsync:DomainNameConfig\",\n    \"ApiAssociation\": \"appsync:ApiAssociation\",\n    \"CreateGraphqlApiRequest\": \"appsync:CreateGraphqlApiRequest\",\n    \"CreateGraphqlApiResponse\": \"appsync:CreateGraphqlApiResponse\",\n    \"ListGraphqlApisResponse\": \"appsync:ListGraphqlApisResponse\",\n    \"GetGraphqlApiResponse\": \"appsync:GetGraphqlApiResponse\",\n    \"UpdateGraphqlApiRequest\": \"appsync:UpdateGraphqlApiRequest\",\n    \"UpdateGraphqlApiResponse\": \"appsync:UpdateGraphqlApiResponse\",\n    \"CreateDataSourceRequest\": \"appsync:CreateDataSourceRequest\",\n    \"CreateDataSourceResponse\": \"appsync:CreateDataSourceResponse\",\n    \"ListDataSourcesResponse\"\
  : \"appsync:ListDataSourcesResponse\",\n    \"GetDataSourceResponse\": \"appsync:GetDataSourceResponse\",\n    \"UpdateDataSourceRequest\": \"appsync:UpdateDataSourceRequest\",\n    \"UpdateDataSourceResponse\": \"appsync:UpdateDataSourceResponse\",\n    \"CreateResolverRequest\": \"appsync:CreateResolverRequest\",\n    \"CreateResolverResponse\": \"appsync:CreateResolverResponse\",\n    \"ListResolversResponse\": \"appsync:ListResolversResponse\",\n    \"GetResolverResponse\": \"appsync:GetResolverResponse\",\n    \"UpdateResolverRequest\": \"appsync:UpdateResolverRequest\",\n    \"UpdateResolverResponse\": \"appsync:UpdateResolverResponse\",\n    \"CreateFunctionRequest\": \"appsync:CreateFunctionRequest\",\n    \"CreateFunctionResponse\": \"appsync:CreateFunctionResponse\",\n    \"ListFunctionsResponse\": \"appsync:ListFunctionsResponse\",\n    \"GetFunctionResponse\": \"appsync:GetFunctionResponse\",\n    \"UpdateFunctionRequest\": \"appsync:UpdateFunctionRequest\",\n    \"UpdateFunctionResponse\"\
  : \"appsync:UpdateFunctionResponse\",\n    \"CreateTypeRequest\": \"appsync:CreateTypeRequest\",\n    \"CreateTypeResponse\": \"appsync:CreateTypeResponse\",\n    \"ListTypesResponse\": \"appsync:ListTypesResponse\",\n    \"GetTypeResponse\": \"appsync:GetTypeResponse\",\n    \"UpdateTypeRequest\": \"appsync:UpdateTypeRequest\",\n    \"UpdateTypeResponse\": \"appsync:UpdateTypeResponse\",\n    \"StartSchemaCreationRequest\": \"appsync:StartSchemaCreationRequest\",\n    \"StartSchemaCreationResponse\": \"appsync:StartSchemaCreationResponse\",\n    \"GetSchemaCreationStatusResponse\": \"appsync:GetSchemaCreationStatusResponse\",\n    \"CreateApiKeyRequest\": \"appsync:CreateApiKeyRequest\",\n    \"CreateApiKeyResponse\": \"appsync:CreateApiKeyResponse\",\n    \"ListApiKeysResponse\": \"appsync:ListApiKeysResponse\",\n    \"UpdateApiKeyRequest\": \"appsync:UpdateApiKeyRequest\",\n    \"UpdateApiKeyResponse\": \"appsync:UpdateApiKeyResponse\",\n    \"CreateDomainNameRequest\": \"appsync:CreateDomainNameRequest\"\
  ,\n    \"CreateDomainNameResponse\": \"appsync:CreateDomainNameResponse\",\n    \"ListDomainNamesResponse\": \"appsync:ListDomainNamesResponse\",\n    \"GetDomainNameResponse\": \"appsync:GetDomainNameResponse\",\n    \"UpdateDomainNameRequest\": \"appsync:UpdateDomainNameRequest\",\n    \"UpdateDomainNameResponse\": \"appsync:UpdateDomainNameResponse\",\n    \"AssociateApiRequest\": \"appsync:AssociateApiRequest\",\n    \"AssociateApiResponse\": \"appsync:AssociateApiResponse\",\n    \"GetApiAssociationResponse\": \"appsync:GetApiAssociationResponse\",\n    \"ListTagsForResourceResponse\": \"appsync:ListTagsForResourceResponse\",\n    \"TagResourceRequest\": \"appsync:TagResourceRequest\",\n    \"EvaluateMappingTemplateRequest\": \"appsync:EvaluateMappingTemplateRequest\",\n    \"EvaluateMappingTemplateResponse\": \"appsync:EvaluateMappingTemplateResponse\",\n    \"GetIntrospectionSchemaResponse\": \"appsync:GetIntrospectionSchemaResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-ld/amazon-appsync-context.jsonld
tags:
- Amazon AppSync
- GraphQL
- API Management
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
