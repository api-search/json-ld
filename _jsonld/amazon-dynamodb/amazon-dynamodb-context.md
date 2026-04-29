---
class_count: 32
classes:
- Amazon DynamoDB Table
- AttributeDefinition
- AttributeValue
- BatchGetItemInput
- BatchGetItemOutput
- BatchWriteItemInput
- BatchWriteItemOutput
- CreateTableInput
- CreateTableOutput
- DeleteItemInput
- DeleteItemOutput
- DescribeTableOutput
- GetItemInput
- GetItemOutput
- GlobalSecondaryIndex
- KeySchemaElement
- LocalSecondaryIndex
- ProvisionedThroughputDescription
- PutItemInput
- PutItemOutput
- QueryInput
- QueryOutput
- ScanInput
- ScanOutput
- Tag
- TransactGetItemsInput
- TransactGetItemsOutput
- TransactWriteItemsInput
- TransactWriteItemsOutput
- UpdateItemInput
- UpdateItemOutput
- UpdateTableInput
context_file: json-ld/amazon-dynamodb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-dynamodb/refs/heads/main/json-ld/amazon-dynamodb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Dynamodb from Amazon DynamoDB.
layout: jsonld
name: Amazon Dynamodb Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: pan
  uri: https://aws.amazon.com/schema/
properties:
- container: ''
  name: Projection
  type: string
- container: ''
  name: ProvisionedThroughput
  type: string
- container: ''
  name: TableDescription
  type: string
- container: ''
  name: TableName
  type: string
- container: ''
  name: Key
  type: reference
- container: ''
  name: ProjectionExpression
  type: string
- container: ''
  name: ConsistentRead
  type: boolean
- container: ''
  name: ExpressionAttributeNames
  type: reference
- container: ''
  name: Responses
  type: reference
- container: ''
  name: UnprocessedKeys
  type: reference
- container: ''
  name: UnprocessedItems
  type: reference
- container: ''
  name: UpdateExpression
  type: string
- container: ''
  name: ConditionExpression
  type: string
- container: ''
  name: ExpressionAttributeValues
  type: reference
- container: ''
  name: ReturnValues
  type: string
- container: set
  name: TransactItems
  type: string
- container: ''
  name: ClientRequestToken
  type: string
- container: ''
  name: ConditionCheck
  type: reference
- container: ''
  name: Put
  type: reference
- container: ''
  name: Delete
  type: reference
- container: ''
  name: Update
  type: reference
- container: ''
  name: IndexName
  type: string
- container: set
  name: KeySchema
  type: string
- container: ''
  name: AttributeName
  type: string
- container: ''
  name: KeyType
  type: string
- container: ''
  name: Item
  type: reference
- container: ''
  name: S
  type: string
- container: ''
  name: N
  type: string
- container: ''
  name: B
  type: string
- container: set
  name: SS
  type: string
- container: set
  name: NS
  type: string
- container: set
  name: BS
  type: string
- container: ''
  name: M
  type: reference
- container: set
  name: L
  type: string
- container: ''
  name: 'NULL'
  type: boolean
- container: ''
  name: BOOL
  type: boolean
- container: ''
  name: Table
  type: string
- container: ''
  name: ReadCapacityUnits
  type: integer
- container: ''
  name: WriteCapacityUnits
  type: integer
- container: ''
  name: Get
  type: reference
- container: ''
  name: Attributes
  type: reference
- container: ''
  name: tableName
  type: string
- container: ''
  name: tableArn
  type: string
- container: ''
  name: tableId
  type: string
- container: ''
  name: tableStatus
  type: string
- container: ''
  name: creationDateTime
  type: dateTime
- container: set
  name: keySchema
  type: string
- container: set
  name: attributeDefinitions
  type: string
- container: ''
  name: provisionedThroughput
  type: string
- container: ''
  name: billingMode
  type: string
- container: ''
  name: itemCount
  type: integer
- container: ''
  name: tableSizeBytes
  type: integer
- container: set
  name: globalSecondaryIndexes
  type: string
- container: set
  name: localSecondaryIndexes
  type: string
- container: ''
  name: streamSpecification
  type: string
- container: ''
  name: sseDescription
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: Items
  type: string
- container: ''
  name: Count
  type: integer
- container: ''
  name: ScannedCount
  type: integer
- container: ''
  name: LastEvaluatedKey
  type: reference
- container: ''
  name: ProjectionType
  type: string
- container: set
  name: NonKeyAttributes
  type: string
- container: ''
  name: BillingMode
  type: string
- container: set
  name: GlobalSecondaryIndexUpdates
  type: string
- container: ''
  name: FilterExpression
  type: string
- container: ''
  name: Limit
  type: integer
- container: ''
  name: ExclusiveStartKey
  type: reference
- container: ''
  name: Segment
  type: integer
- container: ''
  name: TotalSegments
  type: integer
- container: ''
  name: Select
  type: string
- container: ''
  name: AttributeType
  type: string
- container: ''
  name: ItemCollectionMetrics
  type: reference
- container: ''
  name: RequestItems
  type: reference
- container: ''
  name: Value
  type: string
- container: ''
  name: LastIncreaseDateTime
  type: decimal
- container: ''
  name: LastDecreaseDateTime
  type: decimal
- container: ''
  name: NumberOfDecreasesToday
  type: integer
- container: set
  name: AttributeDefinitions
  type: string
- container: set
  name: GlobalSecondaryIndexes
  type: string
- container: set
  name: LocalSecondaryIndexes
  type: string
- container: set
  name: Tags
  type: string
- container: ''
  name: KeyConditionExpression
  type: string
- container: ''
  name: ScanIndexForward
  type: boolean
- container: ''
  name: TableStatus
  type: string
- container: ''
  name: TableArn
  type: string
- container: ''
  name: TableId
  type: string
- container: ''
  name: CreationDateTime
  type: decimal
- container: ''
  name: TableSizeBytes
  type: integer
- container: ''
  name: ItemCount
  type: integer
- container: ''
  name: BillingModeSummary
  type: reference
- container: ''
  name: LastUpdateToPayPerRequestDateTime
  type: decimal
property_count: 92
provider_name: Amazon DynamoDB
provider_slug: amazon-dynamodb
slug: amazon-dynamodb-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"Amazon DynamoDB Table\": \"aws:Amazon DynamoDB Table\",\n    \"AttributeDefinition\": \"aws:AttributeDefinition\",\n    \"AttributeValue\": \"aws:AttributeValue\",\n    \"BatchGetItemInput\": \"aws:BatchGetItemInput\",\n    \"BatchGetItemOutput\": \"aws:BatchGetItemOutput\",\n    \"BatchWriteItemInput\": \"aws:BatchWriteItemInput\",\n    \"BatchWriteItemOutput\": \"aws:BatchWriteItemOutput\",\n    \"CreateTableInput\": \"aws:CreateTableInput\",\n    \"CreateTableOutput\": \"aws:CreateTableOutput\",\n    \"DeleteItemInput\": \"aws:DeleteItemInput\",\n    \"DeleteItemOutput\": \"aws:DeleteItemOutput\",\n    \"DescribeTableOutput\": \"aws:DescribeTableOutput\",\n    \"GetItemInput\": \"\
  aws:GetItemInput\",\n    \"GetItemOutput\": \"aws:GetItemOutput\",\n    \"GlobalSecondaryIndex\": \"aws:GlobalSecondaryIndex\",\n    \"KeySchemaElement\": \"aws:KeySchemaElement\",\n    \"LocalSecondaryIndex\": \"aws:LocalSecondaryIndex\",\n    \"Projection\": {\n      \"@id\": \"pan:Projection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisionedThroughput\": {\n      \"@id\": \"pan:ProvisionedThroughput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisionedThroughputDescription\": \"aws:ProvisionedThroughputDescription\",\n    \"PutItemInput\": \"aws:PutItemInput\",\n    \"PutItemOutput\": \"aws:PutItemOutput\",\n    \"QueryInput\": \"aws:QueryInput\",\n    \"QueryOutput\": \"aws:QueryOutput\",\n    \"ScanInput\": \"aws:ScanInput\",\n    \"ScanOutput\": \"aws:ScanOutput\",\n    \"TableDescription\": {\n      \"@id\": \"pan:TableDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tag\": \"aws:Tag\",\n    \"TransactGetItemsInput\": \"aws:TransactGetItemsInput\"\
  ,\n    \"TransactGetItemsOutput\": \"aws:TransactGetItemsOutput\",\n    \"TransactWriteItemsInput\": \"aws:TransactWriteItemsInput\",\n    \"TransactWriteItemsOutput\": \"aws:TransactWriteItemsOutput\",\n    \"UpdateItemInput\": \"aws:UpdateItemInput\",\n    \"UpdateItemOutput\": \"aws:UpdateItemOutput\",\n    \"UpdateTableInput\": \"aws:UpdateTableInput\",\n    \"TableName\": {\n      \"@id\": \"pan:TableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"pan:Key\",\n      \"@type\": \"@id\"\n    },\n    \"ProjectionExpression\": {\n      \"@id\": \"pan:ProjectionExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConsistentRead\": {\n      \"@id\": \"pan:ConsistentRead\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ExpressionAttributeNames\": {\n      \"@id\": \"pan:ExpressionAttributeNames\",\n      \"@type\": \"@id\"\n    },\n    \"Responses\": {\n      \"@id\": \"pan:Responses\",\n      \"@type\": \"@id\"\n    },\n    \"UnprocessedKeys\"\
  : {\n      \"@id\": \"pan:UnprocessedKeys\",\n      \"@type\": \"@id\"\n    },\n    \"UnprocessedItems\": {\n      \"@id\": \"pan:UnprocessedItems\",\n      \"@type\": \"@id\"\n    },\n    \"UpdateExpression\": {\n      \"@id\": \"pan:UpdateExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConditionExpression\": {\n      \"@id\": \"pan:ConditionExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpressionAttributeValues\": {\n      \"@id\": \"pan:ExpressionAttributeValues\",\n      \"@type\": \"@id\"\n    },\n    \"ReturnValues\": {\n      \"@id\": \"pan:ReturnValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactItems\": {\n      \"@id\": \"pan:TransactItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientRequestToken\": {\n      \"@id\": \"pan:ClientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConditionCheck\": {\n      \"@id\": \"pan:ConditionCheck\",\n      \"@type\": \"@id\"\n    },\n \
  \   \"Put\": {\n      \"@id\": \"pan:Put\",\n      \"@type\": \"@id\"\n    },\n    \"Delete\": {\n      \"@id\": \"pan:Delete\",\n      \"@type\": \"@id\"\n    },\n    \"Update\": {\n      \"@id\": \"pan:Update\",\n      \"@type\": \"@id\"\n    },\n    \"IndexName\": {\n      \"@id\": \"pan:IndexName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeySchema\": {\n      \"@id\": \"pan:KeySchema\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeName\": {\n      \"@id\": \"pan:AttributeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyType\": {\n      \"@id\": \"pan:KeyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Item\": {\n      \"@id\": \"pan:Item\",\n      \"@type\": \"@id\"\n    },\n    \"S\": {\n      \"@id\": \"pan:S\",\n      \"@type\": \"xsd:string\"\n    },\n    \"N\": {\n      \"@id\": \"pan:N\",\n      \"@type\": \"xsd:string\"\n    },\n    \"B\": {\n      \"@id\": \"pan:B\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"SS\": {\n      \"@id\": \"pan:SS\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NS\": {\n      \"@id\": \"pan:NS\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BS\": {\n      \"@id\": \"pan:BS\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"M\": {\n      \"@id\": \"pan:M\",\n      \"@type\": \"@id\"\n    },\n    \"L\": {\n      \"@id\": \"pan:L\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NULL\": {\n      \"@id\": \"pan:NULL\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"BOOL\": {\n      \"@id\": \"pan:BOOL\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Table\": {\n      \"@id\": \"pan:Table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReadCapacityUnits\": {\n      \"@id\": \"pan:ReadCapacityUnits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"WriteCapacityUnits\": {\n      \"@id\": \"pan:WriteCapacityUnits\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"Get\": {\n      \"@id\": \"pan:Get\",\n      \"@type\": \"@id\"\n    },\n    \"Attributes\": {\n      \"@id\": \"pan:Attributes\",\n      \"@type\": \"@id\"\n    },\n    \"tableName\": {\n      \"@id\": \"pan:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableArn\": {\n      \"@id\": \"pan:tableArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableId\": {\n      \"@id\": \"pan:tableId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableStatus\": {\n      \"@id\": \"pan:tableStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDateTime\": {\n      \"@id\": \"pan:creationDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"keySchema\": {\n      \"@id\": \"pan:keySchema\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributeDefinitions\": {\n      \"@id\": \"pan:attributeDefinitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"provisionedThroughput\": {\n      \"@id\": \"pan:provisionedThroughput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingMode\": {\n      \"@id\": \"pan:billingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemCount\": {\n      \"@id\": \"pan:itemCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tableSizeBytes\": {\n      \"@id\": \"pan:tableSizeBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"globalSecondaryIndexes\": {\n      \"@id\": \"pan:globalSecondaryIndexes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localSecondaryIndexes\": {\n      \"@id\": \"pan:localSecondaryIndexes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamSpecification\": {\n      \"@id\": \"pan:streamSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sseDescription\": {\n      \"@id\": \"pan:sseDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n     \
  \ \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Items\": {\n      \"@id\": \"pan:Items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Count\": {\n      \"@id\": \"pan:Count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ScannedCount\": {\n      \"@id\": \"pan:ScannedCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"LastEvaluatedKey\": {\n      \"@id\": \"pan:LastEvaluatedKey\",\n      \"@type\": \"@id\"\n    },\n    \"ProjectionType\": {\n      \"@id\": \"pan:ProjectionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NonKeyAttributes\": {\n      \"@id\": \"pan:NonKeyAttributes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BillingMode\": {\n      \"@id\": \"pan:BillingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GlobalSecondaryIndexUpdates\": {\n      \"@id\": \"pan:GlobalSecondaryIndexUpdates\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterExpression\": {\n      \"@id\": \"pan:FilterExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Limit\": {\n      \"@id\": \"pan:Limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ExclusiveStartKey\": {\n      \"@id\": \"pan:ExclusiveStartKey\",\n      \"@type\": \"@id\"\n    },\n    \"Segment\": {\n      \"@id\": \"pan:Segment\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TotalSegments\": {\n      \"@id\": \"pan:TotalSegments\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Select\": {\n      \"@id\": \"pan:Select\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeType\": {\n      \"@id\": \"pan:AttributeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemCollectionMetrics\": {\n      \"@id\": \"pan:ItemCollectionMetrics\",\n      \"@type\": \"@id\"\n    },\n    \"RequestItems\": {\n      \"@id\": \"pan:RequestItems\",\n      \"@type\": \"@id\"\n    },\n    \"Value\": {\n      \"@id\": \"\
  pan:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastIncreaseDateTime\": {\n      \"@id\": \"pan:LastIncreaseDateTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LastDecreaseDateTime\": {\n      \"@id\": \"pan:LastDecreaseDateTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"NumberOfDecreasesToday\": {\n      \"@id\": \"pan:NumberOfDecreasesToday\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AttributeDefinitions\": {\n      \"@id\": \"pan:AttributeDefinitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GlobalSecondaryIndexes\": {\n      \"@id\": \"pan:GlobalSecondaryIndexes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LocalSecondaryIndexes\": {\n      \"@id\": \"pan:LocalSecondaryIndexes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"pan:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"KeyConditionExpression\": {\n      \"@id\": \"pan:KeyConditionExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScanIndexForward\": {\n      \"@id\": \"pan:ScanIndexForward\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TableStatus\": {\n      \"@id\": \"pan:TableStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TableArn\": {\n      \"@id\": \"pan:TableArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TableId\": {\n      \"@id\": \"pan:TableId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDateTime\": {\n      \"@id\": \"pan:CreationDateTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"TableSizeBytes\": {\n      \"@id\": \"pan:TableSizeBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ItemCount\": {\n      \"@id\": \"pan:ItemCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"BillingModeSummary\": {\n      \"@id\": \"pan:BillingModeSummary\",\n      \"@type\": \"@id\"\n    },\n    \"LastUpdateToPayPerRequestDateTime\"\
  : {\n      \"@id\": \"pan:LastUpdateToPayPerRequestDateTime\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-dynamodb/refs/heads/main/json-ld/amazon-dynamodb-context.jsonld
tags:
- AWS
- Database
- Document Store
- Key-Value
- NoSQL
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
