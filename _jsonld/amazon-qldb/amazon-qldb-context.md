---
class_count: 33
classes:
- S3EncryptionConfiguration
- ValueHolder
- ListJournalS3ExportsResponse
- CreateLedgerResponse
- GetDigestResponse
- UpdateLedgerRequest
- LedgerSummary
- KinesisConfiguration
- ListJournalS3ExportsForLedgerResponse
- StreamJournalToKinesisResponse
- GetRevisionResponse
- GetRevisionRequest
- JournalKinesisStreamDescription
- DescribeJournalS3ExportResponse
- StreamJournalToKinesisRequest
- UpdateLedgerResponse
- UpdateLedgerPermissionsModeResponse
- GetBlockResponse
- ListTagsForResourceResponse
- ExportJournalToS3Response
- DescribeLedgerResponse
- GetBlockRequest
- DescribeJournalKinesisStreamResponse
- ExportJournalToS3Request
- S3ExportConfiguration
- JournalS3ExportDescription
- ListLedgersResponse
- LedgerEncryptionDescription
- TagResourceRequest
- ListJournalKinesisStreamsForLedgerResponse
- CreateLedgerRequest
- UpdateLedgerPermissionsModeRequest
- CancelJournalKinesisStreamResponse
context_file: json-ld/amazon-qldb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-qldb/refs/heads/main/json-ld/amazon-qldb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Qldb from Amazon QLDB.
layout: jsonld
name: Amazon Qldb Context
namespaces:
- prefix: qldb
  uri: https://qldb.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ObjectEncryptionType
  type: string
- container: ''
  name: KmsKeyArn
  type: string
- container: ''
  name: IonText
  type: string
- container: ''
  name: JournalS3Exports
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: CreationDateTime
  type: string
- container: ''
  name: PermissionsMode
  type: string
- container: ''
  name: DeletionProtection
  type: string
- container: ''
  name: Digest
  type: string
- container: ''
  name: DigestTipAddress
  type: string
- container: ''
  name: KmsKey
  type: string
- container: ''
  name: StreamArn
  type: string
- container: ''
  name: AggregationEnabled
  type: string
- container: ''
  name: StreamId
  type: string
- container: ''
  name: Proof
  type: string
- container: ''
  name: Revision
  type: string
- container: ''
  name: BlockAddress
  type: string
- container: ''
  name: DocumentId
  type: string
- container: ''
  name: LedgerName
  type: string
- container: ''
  name: CreationTime
  type: string
- container: ''
  name: InclusiveStartTime
  type: string
- container: ''
  name: ExclusiveEndTime
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: ErrorCause
  type: string
- container: ''
  name: StreamName
  type: string
- container: ''
  name: ExportDescription
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: EncryptionDescription
  type: string
- container: ''
  name: Block
  type: string
- container: ''
  name: ExportId
  type: string
- container: ''
  name: Stream
  type: string
- container: ''
  name: OutputFormat
  type: string
- container: ''
  name: ExportCreationTime
  type: string
- container: ''
  name: Ledgers
  type: string
- container: ''
  name: EncryptionStatus
  type: string
- container: ''
  name: InaccessibleKmsKeyDateTime
  type: string
- container: ''
  name: Streams
  type: string
- container: ''
  name: Bucket
  type: string
- container: ''
  name: Prefix
  type: string
- container: ''
  name: EncryptionConfiguration
  type: string
property_count: 44
provider_name: Amazon QLDB
provider_slug: amazon-qldb
slug: amazon-qldb-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"qldb\": \"https://qldb.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"S3EncryptionConfiguration\": \"qldb:S3EncryptionConfiguration\",\n    \"ObjectEncryptionType\": {\n      \"@id\": \"qldb:ObjectEncryptionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyArn\": {\n      \"@id\": \"qldb:KmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValueHolder\": \"qldb:ValueHolder\",\n    \"IonText\": {\n      \"@id\": \"qldb:IonText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListJournalS3ExportsResponse\": \"qldb:ListJournalS3ExportsResponse\",\n    \"JournalS3Exports\": {\n      \"@id\": \"qldb:JournalS3Exports\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"qldb:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateLedgerResponse\": \"qldb:CreateLedgerResponse\",\n    \"Name\"\
  : {\n      \"@id\": \"qldb:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"qldb:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"qldb:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDateTime\": {\n      \"@id\": \"qldb:CreationDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionsMode\": {\n      \"@id\": \"qldb:PermissionsMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeletionProtection\": {\n      \"@id\": \"qldb:DeletionProtection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetDigestResponse\": \"qldb:GetDigestResponse\",\n    \"Digest\": {\n      \"@id\": \"qldb:Digest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DigestTipAddress\": {\n      \"@id\": \"qldb:DigestTipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateLedgerRequest\": \"qldb:UpdateLedgerRequest\",\n    \"KmsKey\": {\n      \"@id\": \"qldb:KmsKey\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"LedgerSummary\": \"qldb:LedgerSummary\",\n    \"KinesisConfiguration\": \"qldb:KinesisConfiguration\",\n    \"StreamArn\": {\n      \"@id\": \"qldb:StreamArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AggregationEnabled\": {\n      \"@id\": \"qldb:AggregationEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListJournalS3ExportsForLedgerResponse\": \"qldb:ListJournalS3ExportsForLedgerResponse\",\n    \"StreamJournalToKinesisResponse\": \"qldb:StreamJournalToKinesisResponse\",\n    \"StreamId\": {\n      \"@id\": \"qldb:StreamId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetRevisionResponse\": \"qldb:GetRevisionResponse\",\n    \"Proof\": {\n      \"@id\": \"qldb:Proof\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Revision\": {\n      \"@id\": \"qldb:Revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetRevisionRequest\": \"qldb:GetRevisionRequest\",\n    \"BlockAddress\": {\n      \"@id\": \"qldb:BlockAddress\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"DocumentId\": {\n      \"@id\": \"qldb:DocumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JournalKinesisStreamDescription\": \"qldb:JournalKinesisStreamDescription\",\n    \"LedgerName\": {\n      \"@id\": \"qldb:LedgerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"qldb:CreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InclusiveStartTime\": {\n      \"@id\": \"qldb:InclusiveStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExclusiveEndTime\": {\n      \"@id\": \"qldb:ExclusiveEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"qldb:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"qldb:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCause\": {\n      \"@id\": \"qldb:ErrorCause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StreamName\": {\n      \"@id\": \"qldb:StreamName\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"DescribeJournalS3ExportResponse\": \"qldb:DescribeJournalS3ExportResponse\",\n    \"ExportDescription\": {\n      \"@id\": \"qldb:ExportDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StreamJournalToKinesisRequest\": \"qldb:StreamJournalToKinesisRequest\",\n    \"Tags\": {\n      \"@id\": \"qldb:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateLedgerResponse\": \"qldb:UpdateLedgerResponse\",\n    \"EncryptionDescription\": {\n      \"@id\": \"qldb:EncryptionDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateLedgerPermissionsModeResponse\": \"qldb:UpdateLedgerPermissionsModeResponse\",\n    \"GetBlockResponse\": \"qldb:GetBlockResponse\",\n    \"Block\": {\n      \"@id\": \"qldb:Block\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceResponse\": \"qldb:ListTagsForResourceResponse\",\n    \"ExportJournalToS3Response\": \"qldb:ExportJournalToS3Response\",\n    \"ExportId\": {\n      \"\
  @id\": \"qldb:ExportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeLedgerResponse\": \"qldb:DescribeLedgerResponse\",\n    \"GetBlockRequest\": \"qldb:GetBlockRequest\",\n    \"DescribeJournalKinesisStreamResponse\": \"qldb:DescribeJournalKinesisStreamResponse\",\n    \"Stream\": {\n      \"@id\": \"qldb:Stream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExportJournalToS3Request\": \"qldb:ExportJournalToS3Request\",\n    \"S3ExportConfiguration\": \"qldb:S3ExportConfiguration\",\n    \"OutputFormat\": {\n      \"@id\": \"qldb:OutputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JournalS3ExportDescription\": \"qldb:JournalS3ExportDescription\",\n    \"ExportCreationTime\": {\n      \"@id\": \"qldb:ExportCreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListLedgersResponse\": \"qldb:ListLedgersResponse\",\n    \"Ledgers\": {\n      \"@id\": \"qldb:Ledgers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LedgerEncryptionDescription\": \"qldb:LedgerEncryptionDescription\"\
  ,\n    \"EncryptionStatus\": {\n      \"@id\": \"qldb:EncryptionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InaccessibleKmsKeyDateTime\": {\n      \"@id\": \"qldb:InaccessibleKmsKeyDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceRequest\": \"qldb:TagResourceRequest\",\n    \"ListJournalKinesisStreamsForLedgerResponse\": \"qldb:ListJournalKinesisStreamsForLedgerResponse\",\n    \"Streams\": {\n      \"@id\": \"qldb:Streams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Bucket\": {\n      \"@id\": \"qldb:Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Prefix\": {\n      \"@id\": \"qldb:Prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EncryptionConfiguration\": {\n      \"@id\": \"qldb:EncryptionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateLedgerRequest\": \"qldb:CreateLedgerRequest\",\n    \"UpdateLedgerPermissionsModeRequest\": \"qldb:UpdateLedgerPermissionsModeRequest\",\n    \"CancelJournalKinesisStreamResponse\"\
  : \"qldb:CancelJournalKinesisStreamResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-qldb/refs/heads/main/json-ld/amazon-qldb-context.jsonld
tags:
- AWS
- Blockchain
- Database
- Ledger
- JSON-LD
- Linked Data
- Semantic Web
---
