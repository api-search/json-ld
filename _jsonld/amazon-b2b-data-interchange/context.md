---
api_specs:
- filename: aws-b2b-data-interchange-api-openapi.yml
  format: yaml
  label: AWS B2B Data Interchange API
  slug: aws-b2b-data-interchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/openapi/aws-b2b-data-interchange-api-openapi.yml
class_count: 36
classes:
- Profile
- profileId
- profileArn
- businessName
- phone
- email
- logging
- logGroupName
- Partnership
- partnershipId
- partnershipArn
- tradingPartnerId
- capabilities
- Capability
- capabilityId
- capabilityArn
- capabilityDirection
- configuration
- inputLocation
- outputLocation
- instructionsDocuments
- Transformer
- transformerId
- transformerArn
- mappingTemplate
- fileFormat
- ediType
- status
- S3Location
- bucketName
- key
- X12Details
- transactionSet
- version
- name
- description
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Amazon B2B Data Interchange.
layout: jsonld
name: context Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: b2bi
  uri: https://aws.amazon.com/b2b-data-interchange/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 2
provider_name: Amazon B2B Data Interchange
provider_slug: amazon-b2b-data-interchange
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"b2bi\": \"https://aws.amazon.com/b2b-data-interchange/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Profile\": \"b2bi:Profile\",\n    \"profileId\": \"b2bi:profileId\",\n    \"profileArn\": \"b2bi:profileArn\",\n    \"businessName\": \"schema:legalName\",\n    \"phone\": \"schema:telephone\",\n    \"email\": \"schema:email\",\n    \"logging\": \"b2bi:logging\",\n    \"logGroupName\": \"b2bi:logGroupName\",\n\n    \"Partnership\": \"b2bi:Partnership\",\n    \"partnershipId\": \"b2bi:partnershipId\",\n    \"partnershipArn\": \"b2bi:partnershipArn\",\n    \"tradingPartnerId\": \"b2bi:tradingPartnerId\",\n    \"capabilities\": \"b2bi:capabilities\",\n\n    \"Capability\": \"b2bi:Capability\",\n    \"capabilityId\": \"b2bi:capabilityId\",\n    \"capabilityArn\": \"b2bi:capabilityArn\",\n    \"capabilityDirection\": \"b2bi:capabilityDirection\",\n    \"configuration\"\
  : \"b2bi:configuration\",\n    \"inputLocation\": \"b2bi:inputLocation\",\n    \"outputLocation\": \"b2bi:outputLocation\",\n    \"instructionsDocuments\": \"b2bi:instructionsDocuments\",\n\n    \"Transformer\": \"b2bi:Transformer\",\n    \"transformerId\": \"b2bi:transformerId\",\n    \"transformerArn\": \"b2bi:transformerArn\",\n    \"mappingTemplate\": \"b2bi:mappingTemplate\",\n    \"fileFormat\": \"b2bi:fileFormat\",\n    \"ediType\": \"b2bi:ediType\",\n    \"status\": \"b2bi:status\",\n\n    \"S3Location\": \"b2bi:S3Location\",\n    \"bucketName\": \"b2bi:bucketName\",\n    \"key\": \"b2bi:s3Key\",\n\n    \"X12Details\": \"b2bi:X12Details\",\n    \"transactionSet\": \"b2bi:transactionSet\",\n    \"version\": \"b2bi:version\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"\
  @type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-ld/context.jsonld
tags:
- EDI
- B2B
- Data Interchange
- Supply Chain
- Healthcare
- Financial Services
- Amazon Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
