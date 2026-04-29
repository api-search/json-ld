---
api_specs:
- filename: amazon-cognito-user-pools-openapi.yml
  format: yaml
  label: Cognito User Pools API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/openapi/amazon-cognito-user-pools-openapi.yml
- filename: amazon-cognito-identity-pools-openapi.yml
  format: yaml
  label: Cognito Identity Pools API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/openapi/amazon-cognito-identity-pools-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-cognito-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/json-ld/amazon-cognito-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cognito from Amazon Cognito.
layout: jsonld
name: Amazon Cognito Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/ns/cognito#
- prefix: cognito
  uri: https://docs.aws.amazon.com/cognito/latest/developerguide/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: UserPool
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: IdentityPool
  type: ''
property_count: 3
provider_name: Amazon Cognito
provider_slug: amazon-cognito
slug: amazon-cognito-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/ns/cognito#\",\n    \"cognito\": \"https://docs.aws.amazon.com/cognito/latest/developerguide/\",\n    \"UserPool\": {\n      \"@id\": \"aws:UserPool\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"aws:UserPool/Id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"aws:UserPool/Name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"aws:UserPool/Status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"aws:UserPool/Arn\",\n          \"@type\": \"@id\"\n        },\n        \"CreationDate\": {\n          \"@id\": \"aws:UserPool/CreationDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"aws:UserPool/LastModifiedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"MfaConfiguration\": {\n          \"@id\": \"aws:UserPool/MfaConfiguration\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EstimatedNumberOfUsers\": {\n          \"@id\": \"aws:UserPool/EstimatedNumberOfUsers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"Policies\": {\n          \"@id\": \"aws:UserPool/Policies\",\n          \"@type\": \"@id\"\n        },\n        \"SchemaAttributes\": {\n          \"@id\": \"aws:UserPool/SchemaAttributes\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n    \"User\": {\n      \"@id\": \"aws:User\",\n      \"@context\": {\n        \"Username\": {\n          \"@id\": \"aws:User/Username\",\n          \"@type\": \"xsd:string\"\n        },\n        \"UserStatus\": {\n          \"@id\": \"aws:User/UserStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"UserCreateDate\": {\n          \"@id\": \"aws:User/UserCreateDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n     \
  \   \"UserLastModifiedDate\": {\n          \"@id\": \"aws:User/UserLastModifiedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Enabled\": {\n          \"@id\": \"aws:User/Enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"Attributes\": {\n          \"@id\": \"aws:User/Attributes\",\n          \"@container\": \"@list\"\n        },\n        \"MFAOptions\": {\n          \"@id\": \"aws:User/MFAOptions\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n    \"IdentityPool\": {\n      \"@id\": \"aws:IdentityPool\",\n      \"@context\": {\n        \"IdentityPoolId\": {\n          \"@id\": \"aws:IdentityPool/IdentityPoolId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"IdentityPoolName\": {\n          \"@id\": \"aws:IdentityPool/IdentityPoolName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"AllowUnauthenticatedIdentities\": {\n          \"@id\": \"aws:IdentityPool/AllowUnauthenticatedIdentities\",\n  \
  \        \"@type\": \"xsd:boolean\"\n        },\n        \"CognitoIdentityProviders\": {\n          \"@id\": \"aws:IdentityPool/CognitoIdentityProviders\",\n          \"@container\": \"@list\"\n        },\n        \"SupportedLoginProviders\": {\n          \"@id\": \"aws:IdentityPool/SupportedLoginProviders\",\n          \"@type\": \"@id\"\n        },\n        \"OpenIdConnectProviderARNs\": {\n          \"@id\": \"aws:IdentityPool/OpenIdConnectProviderARNs\",\n          \"@container\": \"@list\"\n        },\n        \"SamlProviderARNs\": {\n          \"@id\": \"aws:IdentityPool/SamlProviderARNs\",\n          \"@container\": \"@list\"\n        },\n        \"IdentityPoolTags\": {\n          \"@id\": \"aws:IdentityPool/IdentityPoolTags\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/json-ld/amazon-cognito-context.jsonld
tags:
- Authentication
- AWS
- Identity
- OAuth
- User Management
- JSON-LD
- Linked Data
- Semantic Web
---
