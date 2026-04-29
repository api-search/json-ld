---
api_specs:
- filename: aws-redshift-openapi.json
  format: json
  label: Amazon Redshift API
  slug: amazon-redshift-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/openapi/aws-redshift-openapi.json
- filename: aws-redshift-data-openapi.json
  format: json
  label: Amazon Redshift Data API
  slug: amazon-redshift-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/openapi/aws-redshift-data-openapi.json
class_count: 28
classes:
- ListSchemasResponse
- TableMember
- DataShareAssociation
- GetStatementResultResponse
- DescribeTableRequest
- DescribeTableResponse
- DescribeStatementResponse
- DescribeStatementRequest
- SubStatementData
- ListSchemasRequest
- ListTablesResponse
- ListStatementsResponse
- ListDatabasesResponse
- ExecuteStatementOutput
- SqlParameter
- GetStatementResultRequest
- DataTransferProgress
- ListDatabasesRequest
- Field
- StatementData
- DataShare
- BatchExecuteStatementInput
- ExecuteStatementInput
- CancelStatementRequest
- BatchExecuteStatementOutput
- ListStatementsRequest
- CancelStatementResponse
- ListTablesRequest
context_file: json-ld/aws-redshift-redshift-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/json-ld/aws-redshift-redshift-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Redshift Redshift Data from AWS Redshift.
layout: jsonld
name: Aws Redshift Redshift Data Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: string
- container: ''
  name: ColumnMetadata
  type: string
- container: ''
  name: ClusterIdentifier
  type: string
- container: ''
  name: CreatedAt
  type: string
- container: ''
  name: Database
  type: string
- container: ''
  name: DbUser
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: SecretArn
  type: string
- container: ''
  name: WorkgroupName
  type: string
- container: ''
  name: Databases
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: IsBatchStatement
  type: string
- container: ''
  name: QueryParameters
  type: string
- container: ''
  name: QueryString
  type: string
- container: ''
  name: QueryStrings
  type: string
- container: ''
  name: StatementName
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: UpdatedAt
  type: string
- container: ''
  name: CurrentRateInMegaBytesPerSecond
  type: string
- container: ''
  name: TotalDataInMegaBytes
  type: string
- container: ''
  name: DataTransferredInMegaBytes
  type: string
- container: ''
  name: EstimatedTimeToCompletionInSeconds
  type: string
- container: ''
  name: ElapsedTimeInSeconds
  type: string
- container: ''
  name: Duration
  type: string
- container: ''
  name: Error
  type: string
- container: ''
  name: HasResultSet
  type: string
- container: ''
  name: RedshiftPid
  type: string
- container: ''
  name: RedshiftQueryId
  type: string
- container: ''
  name: ResultRows
  type: string
- container: ''
  name: ResultSize
  type: string
- container: ''
  name: SubStatements
  type: string
- container: ''
  name: ConsumerIdentifier
  type: string
- container: ''
  name: ConsumerRegion
  type: string
- container: ''
  name: CreatedDate
  type: string
- container: ''
  name: StatusChangeDate
  type: string
- container: ''
  name: Tables
  type: string
- container: ''
  name: blobValue
  type: string
- container: ''
  name: booleanValue
  type: string
- container: ''
  name: doubleValue
  type: string
- container: ''
  name: isNull
  type: string
- container: ''
  name: longValue
  type: string
- container: ''
  name: stringValue
  type: string
- container: ''
  name: columnDefault
  type: string
- container: ''
  name: isCaseSensitive
  type: string
- container: ''
  name: isCurrency
  type: string
- container: ''
  name: isSigned
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: length
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: nullable
  type: string
- container: ''
  name: precision
  type: string
- container: ''
  name: scale
  type: string
- container: ''
  name: schemaName
  type: string
- container: ''
  name: tableName
  type: string
- container: ''
  name: typeName
  type: string
- container: ''
  name: ClientToken
  type: string
- container: ''
  name: Sqls
  type: string
- container: ''
  name: WithEvent
  type: string
- container: ''
  name: Records
  type: string
- container: ''
  name: TotalNumRows
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: ConnectedDatabase
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: SchemaPattern
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: RoleLevel
  type: string
- container: ''
  name: Parameters
  type: string
- container: ''
  name: Sql
  type: string
- container: ''
  name: Schema
  type: string
- container: ''
  name: Table
  type: string
- container: ''
  name: DataShareArn
  type: string
- container: ''
  name: ProducerArn
  type: string
- container: ''
  name: AllowPubliclyAccessibleConsumers
  type: string
- container: ''
  name: DataShareAssociations
  type: string
- container: ''
  name: ManagedBy
  type: string
- container: ''
  name: ColumnList
  type: string
- container: ''
  name: TableName
  type: string
- container: ''
  name: Statements
  type: string
- container: ''
  name: TablePattern
  type: string
- container: ''
  name: Schemas
  type: string
property_count: 80
provider_name: AWS Redshift
provider_slug: aws-redshift
slug: aws-redshift-redshift-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": {\n      \"@id\": \"aws:schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListSchemasResponse\": \"aws:ListSchemasResponse\",\n    \"TableMember\": \"aws:TableMember\",\n    \"DataShareAssociation\": \"aws:DataShareAssociation\",\n    \"GetStatementResultResponse\": \"aws:GetStatementResultResponse\",\n    \"DescribeTableRequest\": \"aws:DescribeTableRequest\",\n    \"ColumnMetadata\": {\n      \"@id\": \"aws:ColumnMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeTableResponse\": \"aws:DescribeTableResponse\",\n    \"DescribeStatementResponse\": \"aws:DescribeStatementResponse\",\n    \"DescribeStatementRequest\": \"aws:DescribeStatementRequest\",\n    \"SubStatementData\": \"aws:SubStatementData\",\n    \"ListSchemasRequest\": \"aws:ListSchemasRequest\",\n    \"ListTablesResponse\": \"\
  aws:ListTablesResponse\",\n    \"ListStatementsResponse\": \"aws:ListStatementsResponse\",\n    \"ListDatabasesResponse\": \"aws:ListDatabasesResponse\",\n    \"ExecuteStatementOutput\": \"aws:ExecuteStatementOutput\",\n    \"SqlParameter\": \"aws:SqlParameter\",\n    \"GetStatementResultRequest\": \"aws:GetStatementResultRequest\",\n    \"DataTransferProgress\": \"aws:DataTransferProgress\",\n    \"ListDatabasesRequest\": \"aws:ListDatabasesRequest\",\n    \"Field\": \"aws:Field\",\n    \"StatementData\": \"aws:StatementData\",\n    \"DataShare\": \"aws:DataShare\",\n    \"BatchExecuteStatementInput\": \"aws:BatchExecuteStatementInput\",\n    \"ExecuteStatementInput\": \"aws:ExecuteStatementInput\",\n    \"CancelStatementRequest\": \"aws:CancelStatementRequest\",\n    \"BatchExecuteStatementOutput\": \"aws:BatchExecuteStatementOutput\",\n    \"ListStatementsRequest\": \"aws:ListStatementsRequest\",\n    \"CancelStatementResponse\": \"aws:CancelStatementResponse\",\n    \"ListTablesRequest\"\
  : \"aws:ListTablesRequest\",\n    \"ClusterIdentifier\": {\n      \"@id\": \"aws:ClusterIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedAt\": {\n      \"@id\": \"aws:CreatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Database\": {\n      \"@id\": \"aws:Database\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DbUser\": {\n      \"@id\": \"aws:DbUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretArn\": {\n      \"@id\": \"aws:SecretArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkgroupName\": {\n      \"@id\": \"aws:WorkgroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Databases\": {\n      \"@id\": \"aws:Databases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsBatchStatement\": {\n      \"@id\": \"aws:IsBatchStatement\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"QueryParameters\": {\n      \"@id\": \"aws:QueryParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QueryString\": {\n      \"@id\": \"aws:QueryString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QueryStrings\": {\n      \"@id\": \"aws:QueryStrings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatementName\": {\n      \"@id\": \"aws:StatementName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"aws:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatedAt\": {\n      \"@id\": \"aws:UpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentRateInMegaBytesPerSecond\": {\n      \"@id\": \"aws:CurrentRateInMegaBytesPerSecond\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalDataInMegaBytes\": {\n      \"@id\": \"aws:TotalDataInMegaBytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataTransferredInMegaBytes\": {\n      \"@id\": \"aws:DataTransferredInMegaBytes\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"EstimatedTimeToCompletionInSeconds\": {\n      \"@id\": \"aws:EstimatedTimeToCompletionInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ElapsedTimeInSeconds\": {\n      \"@id\": \"aws:ElapsedTimeInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Duration\": {\n      \"@id\": \"aws:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Error\": {\n      \"@id\": \"aws:Error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HasResultSet\": {\n      \"@id\": \"aws:HasResultSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RedshiftPid\": {\n      \"@id\": \"aws:RedshiftPid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RedshiftQueryId\": {\n      \"@id\": \"aws:RedshiftQueryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultRows\": {\n      \"@id\": \"aws:ResultRows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultSize\": {\n      \"@id\": \"aws:ResultSize\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"SubStatements\": {\n      \"@id\": \"aws:SubStatements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConsumerIdentifier\": {\n      \"@id\": \"aws:ConsumerIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConsumerRegion\": {\n      \"@id\": \"aws:ConsumerRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"aws:CreatedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusChangeDate\": {\n      \"@id\": \"aws:StatusChangeDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tables\": {\n      \"@id\": \"aws:Tables\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blobValue\": {\n      \"@id\": \"aws:blobValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"booleanValue\": {\n      \"@id\": \"aws:booleanValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"doubleValue\": {\n      \"@id\": \"aws:doubleValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isNull\": {\n      \"@id\": \"aws:isNull\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"longValue\": {\n      \"@id\": \"aws:longValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringValue\": {\n      \"@id\": \"aws:stringValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columnDefault\": {\n      \"@id\": \"aws:columnDefault\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isCaseSensitive\": {\n      \"@id\": \"aws:isCaseSensitive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isCurrency\": {\n      \"@id\": \"aws:isCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isSigned\": {\n      \"@id\": \"aws:isSigned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"aws:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"aws:length\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"aws:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nullable\": {\n      \"@id\": \"aws:nullable\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"precision\": {\n      \"@id\": \"aws:precision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scale\": {\n      \"@id\": \"aws:scale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaName\": {\n      \"@id\": \"aws:schemaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableName\": {\n      \"@id\": \"aws:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"typeName\": {\n      \"@id\": \"aws:typeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientToken\": {\n      \"@id\": \"aws:ClientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sqls\": {\n      \"@id\": \"aws:Sqls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WithEvent\": {\n      \"@id\": \"aws:WithEvent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Records\": {\n      \"@id\": \"aws:Records\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalNumRows\": {\n      \"@id\": \"aws:TotalNumRows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n   \
  \   \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectedDatabase\": {\n      \"@id\": \"aws:ConnectedDatabase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"aws:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaPattern\": {\n      \"@id\": \"aws:SchemaPattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleLevel\": {\n      \"@id\": \"aws:RoleLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Parameters\": {\n      \"@id\": \"aws:Parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sql\": {\n      \"@id\": \"aws:Sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Schema\": {\n      \"@id\": \"aws:Schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Table\": {\n      \"@id\": \"aws:Table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataShareArn\": {\n      \"@id\": \"aws:DataShareArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ProducerArn\": {\n      \"@id\": \"aws:ProducerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowPubliclyAccessibleConsumers\": {\n      \"@id\": \"aws:AllowPubliclyAccessibleConsumers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataShareAssociations\": {\n      \"@id\": \"aws:DataShareAssociations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManagedBy\": {\n      \"@id\": \"aws:ManagedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ColumnList\": {\n      \"@id\": \"aws:ColumnList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TableName\": {\n      \"@id\": \"aws:TableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Statements\": {\n      \"@id\": \"aws:Statements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TablePattern\": {\n      \"@id\": \"aws:TablePattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Schemas\": {\n      \"@id\": \"aws:Schemas\",\n      \"@type\": \"xsd:string\"\n \
  \   }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/json-ld/aws-redshift-redshift-data-context.jsonld
tags:
- Analytics
- Big Data
- Cloud Database
- Data Warehouse
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
