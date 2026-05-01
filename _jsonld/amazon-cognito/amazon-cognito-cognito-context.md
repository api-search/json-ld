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
class_count: 1
classes:
- Amazon Cognito User Pool
context_file: json-ld/amazon-cognito-cognito-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/json-ld/amazon-cognito-cognito-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cognito Cognito from Amazon Cognito.
layout: jsonld
name: Amazon Cognito Cognito Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Id
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: CreationDate
  type: dateTime
- container: ''
  name: LastModifiedDate
  type: dateTime
- container: ''
  name: EstimatedNumberOfUsers
  type: integer
- container: ''
  name: MfaConfiguration
  type: string
- container: ''
  name: Policies
  type: reference
- container: ''
  name: PasswordPolicy
  type: reference
- container: ''
  name: MinimumLength
  type: integer
- container: ''
  name: RequireUppercase
  type: boolean
- container: ''
  name: RequireLowercase
  type: boolean
- container: ''
  name: RequireNumbers
  type: boolean
- container: ''
  name: RequireSymbols
  type: boolean
- container: ''
  name: TemporaryPasswordValidityDays
  type: integer
- container: set
  name: AutoVerifiedAttributes
  type: string
- container: set
  name: UsernameAttributes
  type: string
- container: set
  name: SchemaAttributes
  type: reference
- container: ''
  name: EmailConfiguration
  type: reference
- container: ''
  name: SourceArn
  type: string
- container: ''
  name: ReplyToEmailAddress
  type: string
- container: ''
  name: EmailSendingAccount
  type: string
- container: ''
  name: SmsConfiguration
  type: reference
- container: ''
  name: SnsCallerArn
  type: string
- container: ''
  name: ExternalId
  type: string
- container: ''
  name: SnsRegion
  type: string
- container: ''
  name: UserPoolTags
  type: reference
- container: ''
  name: AdminCreateUserConfig
  type: reference
- container: ''
  name: AllowAdminCreateUserOnly
  type: boolean
- container: ''
  name: UnusedAccountValidityDays
  type: integer
- container: ''
  name: InviteMessageTemplate
  type: reference
- container: ''
  name: SMSMessage
  type: string
- container: ''
  name: EmailMessage
  type: string
- container: ''
  name: EmailSubject
  type: string
property_count: 35
provider_name: Amazon Cognito
provider_slug: amazon-cognito
slug: amazon-cognito-cognito-context
source_filename: amazon-cognito-cognito-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amazon Cognito User Pool\": \"aws:Amazon Cognito User Pool\",\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"aws:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"aws:CreationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"aws:LastModifiedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EstimatedNumberOfUsers\": {\n      \"@id\": \"aws:EstimatedNumberOfUsers\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"MfaConfiguration\": {\n      \"@id\": \"aws:MfaConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Policies\": {\n      \"@id\": \"aws:Policies\",\n      \"@type\": \"@id\"\n    },\n    \"PasswordPolicy\": {\n      \"@id\": \"aws:PasswordPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"MinimumLength\": {\n      \"@id\": \"aws:MinimumLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RequireUppercase\": {\n      \"@id\": \"aws:RequireUppercase\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RequireLowercase\": {\n      \"@id\": \"aws:RequireLowercase\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RequireNumbers\": {\n      \"@id\": \"aws:RequireNumbers\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RequireSymbols\": {\n      \"@id\": \"aws:RequireSymbols\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TemporaryPasswordValidityDays\": {\n      \"@id\": \"aws:TemporaryPasswordValidityDays\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"AutoVerifiedAttributes\": {\n      \"@id\": \"aws:AutoVerifiedAttributes\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"UsernameAttributes\": {\n      \"@id\": \"aws:UsernameAttributes\",\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@set\"\n    },\n    \"SchemaAttributes\": {\n      \"@id\": \"aws:SchemaAttributes\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"EmailConfiguration\": {\n      \"@id\": \"aws:EmailConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"SourceArn\": {\n      \"@id\": \"aws:SourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplyToEmailAddress\": {\n      \"@id\": \"aws:ReplyToEmailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailSendingAccount\": {\n      \"@id\": \"aws:EmailSendingAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SmsConfiguration\": {\n      \"@id\": \"aws:SmsConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"\
  SnsCallerArn\": {\n      \"@id\": \"aws:SnsCallerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalId\": {\n      \"@id\": \"aws:ExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnsRegion\": {\n      \"@id\": \"aws:SnsRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserPoolTags\": {\n      \"@id\": \"aws:UserPoolTags\",\n      \"@type\": \"@id\"\n    },\n    \"AdminCreateUserConfig\": {\n      \"@id\": \"aws:AdminCreateUserConfig\",\n      \"@type\": \"@id\"\n    },\n    \"AllowAdminCreateUserOnly\": {\n      \"@id\": \"aws:AllowAdminCreateUserOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"UnusedAccountValidityDays\": {\n      \"@id\": \"aws:UnusedAccountValidityDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"InviteMessageTemplate\": {\n      \"@id\": \"aws:InviteMessageTemplate\",\n      \"@type\": \"@id\"\n    },\n    \"SMSMessage\": {\n      \"@id\": \"aws:SMSMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailMessage\"\
  : {\n      \"@id\": \"aws:EmailMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailSubject\": {\n      \"@id\": \"aws:EmailSubject\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/json-ld/amazon-cognito-cognito-context.jsonld
tags:
- Authentication
- Identity
- OAuth
- User Management
- JSON-LD
- Linked Data
- Semantic Web
---
