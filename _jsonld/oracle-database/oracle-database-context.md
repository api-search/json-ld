---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Oracle REST Data Services (ORDS)
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/
- filename: openapi.yaml
  format: yaml
  label: Oracle Cloud Infrastructure Database API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/iaas/api/#/en/database/
- filename: oracle-database-soda-openapi.yml
  format: yaml
  label: Oracle SODA (Simple Oracle Document Access)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/openapi/oracle-database-soda-openapi.yml
- filename: oracle-database-txeventq-asyncapi.yml
  format: yaml
  label: Oracle Transactional Event Queues (TxEventQ)
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/asyncapi/oracle-database-txeventq-asyncapi.yml
class_count: 12
classes:
- Database
- AutonomousDatabase
- PluggableDatabase
- DbSystem
- Collection
- Document
- Table
- Column
- Index
- Topic
- EventMessage
- ConsumerGroup
context_file: json-ld/oracle-database-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/json-ld/oracle-database-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Database from Oracle Database.
layout: jsonld
name: Oracle Database Context
namespaces:
- prefix: oracle
  uri: https://oracle.com/schemas/database/
- prefix: oci
  uri: https://docs.oracle.com/iaas/api/
- prefix: soda
  uri: https://oracle.com/schemas/database/soda/
- prefix: ords
  uri: https://oracle.com/schemas/database/ords/
- prefix: txeventq
  uri: https://oracle.com/schemas/database/txeventq/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: databaseName
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: compartmentId
  type: reference
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: dbWorkload
  type: string
- container: ''
  name: cpuCoreCount
  type: integer
- container: ''
  name: dataStorageSizeInTBs
  type: integer
- container: ''
  name: connectionStrings
  type: reference
- container: ''
  name: connectionUrls
  type: reference
- container: ''
  name: collectionName
  type: string
- container: ''
  name: documentKey
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: mediaType
  type: string
- container: ''
  name: tableName
  type: string
- container: ''
  name: schemaOwner
  type: string
- container: ''
  name: tablespaceName
  type: string
- container: ''
  name: columnName
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: topicName
  type: string
- container: ''
  name: partition
  type: integer
- container: ''
  name: offset
  type: long
- container: ''
  name: messageKey
  type: string
- container: ''
  name: messageValue
  type: ''
- container: ''
  name: consumerGroupId
  type: string
- container: ''
  name: pdbName
  type: string
- container: ''
  name: openMode
  type: string
- container: ''
  name: containerDatabaseId
  type: reference
- container: ''
  name: timeCreated
  type: dateTime
- container: ''
  name: version
  type: string
property_count: 30
provider_name: Oracle Database
provider_slug: oracle-database
slug: oracle-database-context
source_filename: oracle-database-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"oracle\": \"https://oracle.com/schemas/database/\",\n    \"oci\": \"https://docs.oracle.com/iaas/api/\",\n    \"soda\": \"https://oracle.com/schemas/database/soda/\",\n    \"ords\": \"https://oracle.com/schemas/database/ords/\",\n    \"txeventq\": \"https://oracle.com/schemas/database/txeventq/\",\n\n    \"Database\": \"oracle:Database\",\n    \"AutonomousDatabase\": \"oracle:AutonomousDatabase\",\n    \"PluggableDatabase\": \"oracle:PluggableDatabase\",\n    \"DbSystem\": \"oracle:DbSystem\",\n    \"Collection\": \"soda:Collection\",\n    \"Document\": \"soda:Document\",\n    \"Table\": \"oracle:Table\",\n    \"Column\": \"oracle:Column\",\n    \"Index\": \"oracle:Index\",\n    \"Topic\": \"txeventq:Topic\",\n    \"EventMessage\": \"txeventq:EventMessage\",\n    \"ConsumerGroup\": \"txeventq:ConsumerGroup\",\n\n    \"databaseName\": {\n      \"@id\": \"oracle:databaseName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"displayName\": {\n      \"@id\": \"oracle:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"@id\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"oracle:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbWorkload\": {\n      \"@id\": \"oracle:dbWorkload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuCoreCount\": {\n      \"@id\": \"oracle:cpuCoreCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataStorageSizeInTBs\": {\n      \"@id\": \"oracle:dataStorageSizeInTBs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"connectionStrings\": {\n      \"@id\": \"oracle:connectionStrings\",\n      \"@type\": \"@id\"\n    },\n    \"connectionUrls\": {\n      \"@id\": \"oracle:connectionUrls\",\n      \"@type\": \"@id\"\n    },\n\n    \"collectionName\": {\n      \"@id\": \"soda:collectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentKey\"\
  : {\n      \"@id\": \"soda:documentKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"soda:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"soda:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mediaType\": {\n      \"@id\": \"soda:mediaType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"tableName\": {\n      \"@id\": \"oracle:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaOwner\": {\n      \"@id\": \"oracle:schemaOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tablespaceName\": {\n      \"@id\": \"oracle:tablespaceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columnName\": {\n      \"@id\": \"oracle:columnName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"oracle:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"topicName\": {\n      \"@id\": \"txeventq:topicName\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"partition\": {\n      \"@id\": \"txeventq:partition\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"txeventq:offset\",\n      \"@type\": \"xsd:long\"\n    },\n    \"messageKey\": {\n      \"@id\": \"txeventq:messageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageValue\": {\n      \"@id\": \"txeventq:messageValue\"\n    },\n    \"consumerGroupId\": {\n      \"@id\": \"txeventq:consumerGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"pdbName\": {\n      \"@id\": \"oracle:pdbName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openMode\": {\n      \"@id\": \"oracle:openMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerDatabaseId\": {\n      \"@id\": \"oracle:containerDatabaseId\",\n      \"@type\": \"@id\"\n    },\n\n    \"timeCreated\": {\n      \"@id\": \"oracle:timeCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"version\": {\n      \"@id\": \"oracle:version\",\n      \"@type\": \"xsd:string\"\
  \n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/json-ld/oracle-database-context.jsonld
tags:
- Cloud
- Database
- Enterprise
- Oracle
- REST API
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
