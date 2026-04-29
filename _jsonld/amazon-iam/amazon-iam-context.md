---
api_specs:
- filename: amazon-iam-openapi.yml
  format: yaml
  label: AWS IAM API
  slug: aws-iam-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/openapi/amazon-iam-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-iam-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/json-ld/amazon-iam-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iam from Amazon IAM.
layout: jsonld
name: Amazon Iam Context
namespaces:
- prefix: iam
  uri: https://docs.aws.amazon.com/IAM/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: AccessKey
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 6
provider_name: Amazon IAM
provider_slug: amazon-iam
slug: amazon-iam-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"iam\": \"https://docs.aws.amazon.com/IAM/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"User\": {\n      \"@id\": \"iam:API_User\",\n      \"@context\": {\n        \"UserName\": {\n          \"@id\": \"iam:User-UserName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"UserId\": {\n          \"@id\": \"iam:User-UserId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"iam:User-Arn\",\n          \"@type\": \"@id\"\n        },\n        \"Path\": {\n          \"@id\": \"iam:User-Path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreateDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"PasswordLastUsed\": {\n          \"@id\": \"iam:User-PasswordLastUsed\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Tags\": {\n          \"@id\": \"iam:User-Tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"iam:API_Role\",\n      \"@context\": {\n        \"RoleName\": {\n          \"@id\": \"iam:Role-RoleName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"RoleId\": {\n          \"@id\": \"iam:Role-RoleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"iam:Role-Arn\",\n          \"@type\": \"@id\"\n        },\n        \"Path\": {\n          \"@id\": \"iam:Role-Path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"AssumeRolePolicyDocument\": {\n          \"@id\": \"iam:Role-AssumeRolePolicyDocument\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MaxSessionDuration\": {\n\
  \          \"@id\": \"iam:Role-MaxSessionDuration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"CreateDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Tags\": {\n          \"@id\": \"iam:Role-Tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"iam:API_Policy\",\n      \"@context\": {\n        \"PolicyName\": {\n          \"@id\": \"iam:Policy-PolicyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PolicyId\": {\n          \"@id\": \"iam:Policy-PolicyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"iam:Policy-Arn\",\n          \"@type\": \"@id\"\n        },\n        \"Path\": {\n          \"@id\": \"iam:Policy-Path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DefaultVersionId\": {\n          \"@id\": \"iam:Policy-DefaultVersionId\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"AttachmentCount\": {\n          \"@id\": \"iam:Policy-AttachmentCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"IsAttachable\": {\n          \"@id\": \"iam:Policy-IsAttachable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"Description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreateDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"UpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"iam:API_Group\",\n      \"@context\": {\n        \"GroupName\": {\n          \"@id\": \"iam:Group-GroupName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"GroupId\": {\n          \"@id\": \"iam:Group-GroupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"\
  @id\": \"iam:Group-Arn\",\n          \"@type\": \"@id\"\n        },\n        \"Path\": {\n          \"@id\": \"iam:Group-Path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreateDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AccessKey\": {\n      \"@id\": \"iam:API_AccessKey\",\n      \"@context\": {\n        \"AccessKeyId\": {\n          \"@id\": \"iam:AccessKey-AccessKeyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"iam:AccessKey-Status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"UserName\": {\n          \"@id\": \"iam:AccessKey-UserName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreateDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"iam:API_Tag\",\n      \"@context\": {\n        \"Key\": {\n  \
  \        \"@id\": \"iam:Tag-Key\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Value\": {\n          \"@id\": \"iam:Tag-Value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/json-ld/amazon-iam-context.jsonld
tags:
- Access Management
- Authentication
- Authorization
- AWS
- Identity
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
