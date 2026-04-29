---
api_specs:
- filename: amazon-simpledb.yaml
  format: yaml
  label: Amazon SimpleDB API
  slug: amazon-simpledb-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/openapi/amazon-simpledb.yaml
class_count: 39
classes:
- SelectRequest
- InvalidNumberPredicates
- InvalidQueryExpression
- SelectResult
- MissingParameter
- AttributeDoesNotExist
- BatchPutAttributesRequest
- InvalidNumberValueTests
- ReplaceableItem
- Item
- InvalidParameterValue
- NumberSubmittedAttributesExceeded
- DuplicateItemName
- NumberDomainsExceeded
- DomainMetadataResult
- DeletableAttribute
- NoSuchDomain
- RequestTimeout
- PutAttributesRequest
- UpdateCondition
- CreateDomainRequest
- InvalidNextToken
- ListDomainsResult
- BatchDeleteAttributesRequest
- NumberDomainAttributesExceeded
- NumberItemAttributesExceeded
- DeleteDomainRequest
- ListDomainsRequest
- DeleteAttributesRequest
- NumberDomainBytesExceeded
- DomainMetadataRequest
- DeletableItem
- GetAttributesRequest
- ReplaceableAttribute
- NumberSubmittedItemsExceeded
- GetAttributesResult
- TooManyRequestedAttributes
- Attribute
- Name
context_file: json-ld/amazon-simpledb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/json-ld/amazon-simpledb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Simpledb from Amazon SimpleDB.
layout: jsonld
name: Amazon Simpledb Context
namespaces:
- prefix: aws
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: SelectExpression
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: ConsistentRead
  type: string
- container: ''
  name: BoxUsage
  type: string
- container: ''
  name: Items
  type: string
- container: ''
  name: DomainName
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: AlternateNameEncoding
  type: string
- container: ''
  name: ItemCount
  type: string
- container: ''
  name: ItemNamesSizeBytes
  type: string
- container: ''
  name: AttributeNameCount
  type: string
- container: ''
  name: AttributeNamesSizeBytes
  type: string
- container: ''
  name: AttributeValueCount
  type: string
- container: ''
  name: AttributeValuesSizeBytes
  type: string
- container: ''
  name: Timestamp
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: ItemName
  type: string
- container: ''
  name: Expected
  type: string
- container: ''
  name: Exists
  type: string
- container: ''
  name: DomainNames
  type: string
- container: ''
  name: MaxNumberOfDomains
  type: string
- container: ''
  name: AttributeNames
  type: string
- container: ''
  name: Replace
  type: string
- container: ''
  name: AlternateValueEncoding
  type: string
property_count: 24
provider_name: Amazon SimpleDB
provider_slug: amazon-simpledb
slug: amazon-simpledb-context
source_filename: amazon-simpledb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SelectRequest\": \"aws:SelectRequest\",\n    \"InvalidNumberPredicates\": \"aws:InvalidNumberPredicates\",\n    \"InvalidQueryExpression\": \"aws:InvalidQueryExpression\",\n    \"SelectResult\": \"aws:SelectResult\",\n    \"MissingParameter\": \"aws:MissingParameter\",\n    \"AttributeDoesNotExist\": \"aws:AttributeDoesNotExist\",\n    \"BatchPutAttributesRequest\": \"aws:BatchPutAttributesRequest\",\n    \"InvalidNumberValueTests\": \"aws:InvalidNumberValueTests\",\n    \"ReplaceableItem\": \"aws:ReplaceableItem\",\n    \"Item\": \"aws:Item\",\n    \"InvalidParameterValue\": \"aws:InvalidParameterValue\",\n    \"NumberSubmittedAttributesExceeded\": \"aws:NumberSubmittedAttributesExceeded\",\n    \"DuplicateItemName\": \"aws:DuplicateItemName\"\
  ,\n    \"NumberDomainsExceeded\": \"aws:NumberDomainsExceeded\",\n    \"DomainMetadataResult\": \"aws:DomainMetadataResult\",\n    \"DeletableAttribute\": \"aws:DeletableAttribute\",\n    \"NoSuchDomain\": \"aws:NoSuchDomain\",\n    \"RequestTimeout\": \"aws:RequestTimeout\",\n    \"PutAttributesRequest\": \"aws:PutAttributesRequest\",\n    \"UpdateCondition\": \"aws:UpdateCondition\",\n    \"CreateDomainRequest\": \"aws:CreateDomainRequest\",\n    \"InvalidNextToken\": \"aws:InvalidNextToken\",\n    \"ListDomainsResult\": \"aws:ListDomainsResult\",\n    \"BatchDeleteAttributesRequest\": \"aws:BatchDeleteAttributesRequest\",\n    \"NumberDomainAttributesExceeded\": \"aws:NumberDomainAttributesExceeded\",\n    \"NumberItemAttributesExceeded\": \"aws:NumberItemAttributesExceeded\",\n    \"DeleteDomainRequest\": \"aws:DeleteDomainRequest\",\n    \"ListDomainsRequest\": \"aws:ListDomainsRequest\",\n    \"DeleteAttributesRequest\": \"aws:DeleteAttributesRequest\",\n    \"NumberDomainBytesExceeded\"\
  : \"aws:NumberDomainBytesExceeded\",\n    \"DomainMetadataRequest\": \"aws:DomainMetadataRequest\",\n    \"DeletableItem\": \"aws:DeletableItem\",\n    \"GetAttributesRequest\": \"aws:GetAttributesRequest\",\n    \"ReplaceableAttribute\": \"aws:ReplaceableAttribute\",\n    \"NumberSubmittedItemsExceeded\": \"aws:NumberSubmittedItemsExceeded\",\n    \"GetAttributesResult\": \"aws:GetAttributesResult\",\n    \"TooManyRequestedAttributes\": \"aws:TooManyRequestedAttributes\",\n    \"Attribute\": \"aws:Attribute\",\n    \"SelectExpression\": {\n      \"@id\": \"aws:SelectExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConsistentRead\": {\n      \"@id\": \"aws:ConsistentRead\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BoxUsage\": {\n      \"@id\": \"aws:BoxUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Items\": {\n      \"@id\": \"aws:Items\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"DomainName\": {\n      \"@id\": \"aws:DomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": \"schema:name\",\n    \"Attributes\": {\n      \"@id\": \"aws:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlternateNameEncoding\": {\n      \"@id\": \"aws:AlternateNameEncoding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemCount\": {\n      \"@id\": \"aws:ItemCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemNamesSizeBytes\": {\n      \"@id\": \"aws:ItemNamesSizeBytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeNameCount\": {\n      \"@id\": \"aws:AttributeNameCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeNamesSizeBytes\": {\n      \"@id\": \"aws:AttributeNamesSizeBytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeValueCount\": {\n      \"@id\": \"aws:AttributeValueCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeValuesSizeBytes\": {\n      \"@id\"\
  : \"aws:AttributeValuesSizeBytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"aws:Timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemName\": {\n      \"@id\": \"aws:ItemName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Expected\": {\n      \"@id\": \"aws:Expected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Exists\": {\n      \"@id\": \"aws:Exists\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DomainNames\": {\n      \"@id\": \"aws:DomainNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxNumberOfDomains\": {\n      \"@id\": \"aws:MaxNumberOfDomains\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeNames\": {\n      \"@id\": \"aws:AttributeNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Replace\": {\n      \"@id\": \"aws:Replace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlternateValueEncoding\"\
  : {\n      \"@id\": \"aws:AlternateValueEncoding\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/json-ld/amazon-simpledb-context.jsonld
tags:
- AWS
- Cloud Storage
- Data Storage
- Database
- NoSQL
- JSON-LD
- Linked Data
- Semantic Web
---
