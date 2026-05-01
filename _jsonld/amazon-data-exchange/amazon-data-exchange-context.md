---
api_specs:
- filename: amazon-data-exchange-openapi.yml
  format: yaml
  label: AWS Data Exchange API
  slug: aws-data-exchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/openapi/amazon-data-exchange-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-data-exchange-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/json-ld/amazon-data-exchange-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Data Exchange from Amazon Data Exchange.
layout: jsonld
name: Amazon Data Exchange Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/data-exchange/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: DataSet
  type: ''
- container: ''
  name: Revision
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: EventAction
  type: ''
- container: ''
  name: Id
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: AssetType
  type: string
- container: ''
  name: Origin
  type: string
- container: ''
  name: OriginDetails
  type: ''
- container: ''
  name: DataSetId
  type: string
- container: ''
  name: RevisionId
  type: string
- container: ''
  name: Comment
  type: string
- container: ''
  name: Finalized
  type: boolean
- container: ''
  name: AssetDetails
  type: ''
- container: ''
  name: S3SnapshotAsset
  type: ''
- container: ''
  name: Size
  type: long
- container: ''
  name: Type
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: Details
  type: ''
- container: ''
  name: Errors
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Action
  type: ''
- container: ''
  name: RevisionPublished
  type: ''
- container: ''
  name: ExportRevisionToS3
  type: ''
- container: ''
  name: ExportAssetsToS3
  type: ''
- container: ''
  name: ImportAssetsFromS3
  type: ''
- container: ''
  name: RevisionDestination
  type: ''
- container: ''
  name: AssetDestinations
  type: ''
- container: ''
  name: Bucket
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: KeyPattern
  type: string
- container: ''
  name: Encryption
  type: ''
- container: ''
  name: ProductId
  type: string
- container: ''
  name: EventSourceToken
  type: string
- container: set
  name: DataSets
  type: ''
- container: set
  name: Revisions
  type: ''
- container: set
  name: Assets
  type: ''
- container: set
  name: Jobs
  type: ''
- container: set
  name: EventActions
  type: ''
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Tags
  type: ''
- container: ''
  name: CreatedAt
  type: dateTime
- container: ''
  name: UpdatedAt
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: requestId
  type: string
property_count: 49
provider_name: Amazon Data Exchange
provider_slug: amazon-data-exchange
slug: amazon-data-exchange-context
source_filename: amazon-data-exchange-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/data-exchange/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"DataSet\": {\"@id\": \"aws:DataSet\"},\n    \"Revision\": {\"@id\": \"aws:Revision\"},\n    \"Asset\": {\"@id\": \"aws:Asset\"},\n    \"Job\": {\"@id\": \"aws:Job\"},\n    \"EventAction\": {\"@id\": \"aws:EventAction\"},\n\n    \"Id\": {\"@id\": \"aws:id\", \"@type\": \"xsd:string\"},\n    \"Arn\": {\"@id\": \"aws:arn\", \"@type\": \"xsd:string\"},\n    \"Name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"Description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"AssetType\": {\"@id\": \"aws:assetType\", \"@type\": \"xsd:string\"},\n    \"Origin\": {\"@id\": \"aws:origin\", \"@type\": \"xsd:string\"},\n    \"OriginDetails\": {\"@id\": \"aws:originDetails\"},\n    \"DataSetId\"\
  : {\"@id\": \"aws:dataSetId\", \"@type\": \"xsd:string\"},\n    \"RevisionId\": {\"@id\": \"aws:revisionId\", \"@type\": \"xsd:string\"},\n    \"Comment\": {\"@id\": \"schema:comment\", \"@type\": \"xsd:string\"},\n    \"Finalized\": {\"@id\": \"aws:finalized\", \"@type\": \"xsd:boolean\"},\n    \"AssetDetails\": {\"@id\": \"aws:assetDetails\"},\n    \"S3SnapshotAsset\": {\"@id\": \"aws:s3SnapshotAsset\"},\n    \"Size\": {\"@id\": \"schema:size\", \"@type\": \"xsd:long\"},\n    \"Type\": {\"@id\": \"aws:jobType\", \"@type\": \"xsd:string\"},\n    \"State\": {\"@id\": \"aws:state\", \"@type\": \"xsd:string\"},\n    \"Details\": {\"@id\": \"aws:details\"},\n    \"Errors\": {\"@id\": \"aws:errors\"},\n    \"Event\": {\"@id\": \"aws:event\"},\n    \"Action\": {\"@id\": \"aws:action\"},\n    \"RevisionPublished\": {\"@id\": \"aws:revisionPublished\"},\n    \"ExportRevisionToS3\": {\"@id\": \"aws:exportRevisionToS3\"},\n    \"ExportAssetsToS3\": {\"@id\": \"aws:exportAssetsToS3\"},\n    \"ImportAssetsFromS3\"\
  : {\"@id\": \"aws:importAssetsFromS3\"},\n    \"RevisionDestination\": {\"@id\": \"aws:revisionDestination\"},\n    \"AssetDestinations\": {\"@id\": \"aws:assetDestinations\"},\n    \"Bucket\": {\"@id\": \"aws:s3Bucket\", \"@type\": \"xsd:string\"},\n    \"Key\": {\"@id\": \"aws:s3Key\", \"@type\": \"xsd:string\"},\n    \"KeyPattern\": {\"@id\": \"aws:keyPattern\", \"@type\": \"xsd:string\"},\n    \"Encryption\": {\"@id\": \"aws:encryption\"},\n    \"ProductId\": {\"@id\": \"aws:productId\", \"@type\": \"xsd:string\"},\n    \"EventSourceToken\": {\"@id\": \"aws:eventSourceToken\", \"@type\": \"xsd:string\"},\n\n    \"DataSets\": {\"@id\": \"aws:dataSets\", \"@container\": \"@set\"},\n    \"Revisions\": {\"@id\": \"aws:revisions\", \"@container\": \"@set\"},\n    \"Assets\": {\"@id\": \"aws:assets\", \"@container\": \"@set\"},\n    \"Jobs\": {\"@id\": \"aws:jobs\", \"@container\": \"@set\"},\n    \"EventActions\": {\"@id\": \"aws:eventActions\", \"@container\": \"@set\"},\n    \"NextToken\"\
  : {\"@id\": \"aws:nextToken\", \"@type\": \"xsd:string\"},\n\n    \"Tags\": {\"@id\": \"aws:tags\"},\n    \"CreatedAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"UpdatedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"aws:errorCode\", \"@type\": \"xsd:string\"},\n    \"requestId\": {\"@id\": \"aws:requestId\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/json-ld/amazon-data-exchange-context.jsonld
tags:
- Data Exchange
- Data Marketplace
- Third-Party Data
- Analytics
- Subscriptions
- JSON-LD
- Linked Data
- Semantic Web
---
