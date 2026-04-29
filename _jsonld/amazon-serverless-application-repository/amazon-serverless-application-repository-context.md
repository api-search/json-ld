---
class_count: 7
classes:
- Application
- name
- author
- description
- ApplicationSummary
- VersionSummary
- ApplicationPolicyStatement
context_file: json-ld/amazon-serverless-application-repository-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-serverless-application-repository/refs/heads/main/json-ld/amazon-serverless-application-repository-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Serverless Application Repository from Amazon Serverless Application Repository.
layout: jsonld
name: Amazon Serverless Application Repository Context
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
  name: applicationId
  type: string
- container: ''
  name: creationTime
  type: dateTime
- container: ''
  name: homePageUrl
  type: string
- container: set
  name: labels
  type: string
- container: ''
  name: licenseUrl
  type: string
- container: ''
  name: readmeUrl
  type: string
- container: ''
  name: spdxLicenseId
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: semanticVersion
  type: string
- container: ''
  name: sourceCodeUrl
  type: string
- container: ''
  name: statementId
  type: string
- container: set
  name: principals
  type: string
- container: set
  name: actions
  type: string
property_count: 13
provider_name: Amazon Serverless Application Repository
provider_slug: amazon-serverless-application-repository
slug: amazon-serverless-application-repository-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Application\": \"aws:Application\",\n    \"applicationId\": {\n      \"@id\": \"aws:applicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"author\": \"schema:author\",\n    \"description\": \"schema:description\",\n    \"creationTime\": {\n      \"@id\": \"aws:creationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"homePageUrl\": {\n      \"@id\": \"aws:homePageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"aws:labels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenseUrl\": {\n      \"@id\": \"aws:licenseUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"readmeUrl\": {\n      \"@id\": \"aws:readmeUrl\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"spdxLicenseId\": {\n      \"@id\": \"aws:spdxLicenseId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"aws:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationSummary\": \"aws:ApplicationSummary\",\n    \"VersionSummary\": \"aws:VersionSummary\",\n    \"semanticVersion\": {\n      \"@id\": \"aws:semanticVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceCodeUrl\": {\n      \"@id\": \"aws:sourceCodeUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationPolicyStatement\": \"aws:ApplicationPolicyStatement\",\n    \"statementId\": {\n      \"@id\": \"aws:statementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principals\": {\n      \"@id\": \"aws:principals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actions\": {\n      \"@id\": \"aws:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n\
  \  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-serverless-application-repository/refs/heads/main/json-ld/amazon-serverless-application-repository-context.jsonld
tags:
- Application Repository
- AWS
- Lambda
- SAM
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
