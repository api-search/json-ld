---
api_specs:
- filename: tidb-cloud-api-openapi.yml
  format: yaml
  label: TiDB Cloud API
  slug: tidb-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-cloud-api-openapi.yml
- filename: tidb-cloud-data-service-openapi.yml
  format: yaml
  label: TiDB Cloud Data Service API
  slug: tidb-cloud-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-cloud-data-service-openapi.yml
- filename: tidb-cloud-chat2query-openapi.yml
  format: yaml
  label: TiDB Cloud Chat2Query API
  slug: tidb-cloud-chat2query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-cloud-chat2query-openapi.yml
- filename: tidb-http-api-openapi.yml
  format: yaml
  label: TiDB HTTP API
  slug: tidb-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-http-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/tidb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/json-ld/tidb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tidb from tidb.
layout: jsonld
name: Tidb Context
namespaces:
- prefix: tidb
  uri: https://pingcap.com/vocab/tidb/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: ClusterComponents
  type: ''
- container: ''
  name: ComputeComponentSpec
  type: ''
- container: ''
  name: StorageComponentSpec
  type: ''
- container: ''
  name: ConnectionString
  type: ''
- container: ''
  name: ImportTask
  type: ''
- container: ''
  name: DataApp
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: EndpointParameter
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: AuditLog
  type: ''
- container: ''
  name: BillingRecord
  type: ''
- container: ''
  name: Region
  type: ''
- container: ''
  name: DataSummary
  type: ''
- container: ''
  name: Chat2DataResult
  type: ''
property_count: 16
provider_name: tidb
provider_slug: tidb
slug: tidb-context
source_filename: tidb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tidb\": \"https://pingcap.com/vocab/tidb/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Cluster\": {\n      \"@id\": \"tidb:Cluster\",\n      \"@context\": {\n        \"clusterId\": \"@id\",\n        \"displayName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"clusterType\": {\n          \"@id\": \"tidb:clusterType\"\n        },\n        \"cloudProvider\": {\n          \"@id\": \"tidb:cloudProvider\"\n        },\n        \"regionId\": {\n          \"@id\": \"tidb:regionId\"\n        },\n        \"projectId\": {\n          \"@id\": \"tidb:projectId\"\n        },\n        \"tidbVersion\": {\n          \"@id\": \"tidb:tidbVersion\"\n        },\n        \"state\": {\n          \"@id\": \"tidb:clusterState\"\n        },\n\
  \        \"port\": {\n          \"@id\": \"schema:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"components\": {\n          \"@id\": \"tidb:clusterComponents\"\n        },\n        \"connectionStrings\": {\n          \"@id\": \"tidb:connectionStrings\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ClusterComponents\": {\n      \"@id\": \"tidb:ClusterComponents\",\n      \"@context\": {\n        \"tidb\": {\n          \"@id\": \"tidb:tidbComponent\"\n        },\n        \"tikv\": {\n          \"@id\": \"tidb:tikvComponent\"\n        },\n        \"tiflash\": {\n          \"@id\": \"tidb:tiflashComponent\"\n        }\n      }\n    },\n\n    \"ComputeComponentSpec\": {\n      \"@id\": \"tidb:ComputeComponentSpec\"\
  ,\n      \"@context\": {\n        \"nodeSize\": {\n          \"@id\": \"tidb:nodeSize\"\n        },\n        \"nodeQuantity\": {\n          \"@id\": \"tidb:nodeQuantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vcpu\": {\n          \"@id\": \"tidb:vcpu\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memoryGiB\": {\n          \"@id\": \"tidb:memoryGiB\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"StorageComponentSpec\": {\n      \"@id\": \"tidb:StorageComponentSpec\",\n      \"@context\": {\n        \"nodeSize\": {\n          \"@id\": \"tidb:nodeSize\"\n        },\n        \"nodeQuantity\": {\n          \"@id\": \"tidb:nodeQuantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"storageSize\": {\n          \"@id\": \"tidb:storageSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"storageType\": {\n          \"@id\": \"tidb:storageType\"\n        }\n      }\n    },\n\n    \"ConnectionString\"\
  : {\n      \"@id\": \"tidb:ConnectionString\",\n      \"@context\": {\n        \"host\": {\n          \"@id\": \"schema:serverAddress\"\n        },\n        \"port\": {\n          \"@id\": \"schema:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"defaultUser\": {\n          \"@id\": \"tidb:defaultUser\"\n        }\n      }\n    },\n\n    \"ImportTask\": {\n      \"@id\": \"tidb:ImportTask\",\n      \"@context\": {\n        \"importId\": \"@id\",\n        \"clusterId\": {\n          \"@id\": \"tidb:clusterId\"\n        },\n        \"sourceType\": {\n          \"@id\": \"tidb:sourceType\"\n        },\n        \"fileFormat\": {\n          \"@id\": \"tidb:fileFormat\"\n        },\n        \"state\": {\n          \"@id\": \"tidb:taskState\"\n        },\n        \"progress\": {\n          \"@id\": \"schema:percentComplete\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"targetDatabase\": {\n          \"@id\": \"tidb:targetDatabase\"\n        },\n    \
  \    \"errorMessage\": {\n          \"@id\": \"schema:error\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataApp\": {\n      \"@id\": \"tidb:DataApp\",\n      \"@context\": {\n        \"dataAppId\": \"@id\",\n        \"displayName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"region\": {\n          \"@id\": \"tidb:region\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dataSources\": {\n          \"@id\": \"tidb:dataSources\",\n          \"@container\": \"@set\"\n        },\n        \"endpoints\": {\n          \"@id\": \"tidb:endpoints\",\n          \"@container\"\
  : \"@set\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"tidb:DataSource\",\n      \"@context\": {\n        \"clusterId\": {\n          \"@id\": \"tidb:clusterId\"\n        },\n        \"clusterName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"clusterType\": {\n          \"@id\": \"tidb:clusterType\"\n        }\n      }\n    },\n\n    \"Endpoint\": {\n      \"@id\": \"tidb:Endpoint\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:alternateName\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"path\": {\n          \"@id\": \"schema:path\"\n        },\n        \"method\": {\n          \"@id\": \"tidb:httpMethod\"\n        },\n        \"clusterId\": {\n          \"@id\": \"tidb:clusterId\"\n        },\n        \"sqlTemplate\": {\n          \"@id\": \"tidb:sqlTemplate\"\n        },\n    \
  \    \"tag\": {\n          \"@id\": \"schema:keywords\"\n        },\n        \"params\": {\n          \"@id\": \"tidb:endpointParams\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EndpointParameter\": {\n      \"@id\": \"tidb:EndpointParameter\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"type\": {\n          \"@id\": \"tidb:parameterType\"\n        },\n        \"required\": {\n          \"@id\": \"tidb:isRequired\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"defaultValue\": {\n          \"@id\": \"schema:defaultValue\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"tidb:ApiKey\",\n      \"@context\": {\n        \"accessKey\": \"@id\",\n        \"displayName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"role\": {\n          \"@id\": \"schema:roleName\"\n       \
  \ },\n        \"projectId\": {\n          \"@id\": \"tidb:projectId\"\n        }\n      }\n    },\n\n    \"AuditLog\": {\n      \"@id\": \"tidb:AuditLog\",\n      \"@context\": {\n        \"eventType\": {\n          \"@id\": \"tidb:eventType\"\n        },\n        \"operationEmail\": {\n          \"@id\": \"schema:email\"\n        },\n        \"result\": {\n          \"@id\": \"tidb:operationResult\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"clusterId\": {\n          \"@id\": \"tidb:clusterId\"\n        },\n        \"projectId\": {\n          \"@id\": \"tidb:projectId\"\n        },\n        \"orgId\": {\n          \"@id\": \"tidb:orgId\"\n        }\n      }\n    },\n\n    \"BillingRecord\": {\n      \"@id\": \"tidb:BillingRecord\",\n      \"@context\": {\n        \"billedDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"projectName\": {\n\
  \          \"@id\": \"schema:name\"\n        },\n        \"clusterName\": {\n          \"@id\": \"tidb:clusterName\"\n        },\n        \"servicePathName\": {\n          \"@id\": \"tidb:servicePathName\"\n        },\n        \"totalCost\": {\n          \"@id\": \"schema:totalPrice\"\n        },\n        \"credits\": {\n          \"@id\": \"tidb:credits\"\n        },\n        \"discounts\": {\n          \"@id\": \"tidb:discounts\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        }\n      }\n    },\n\n    \"Region\": {\n      \"@id\": \"tidb:Region\",\n      \"@context\": {\n        \"regionId\": \"@id\",\n        \"displayName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"cloudProvider\": {\n          \"@id\": \"tidb:cloudProvider\"\n        }\n      }\n    },\n\n    \"DataSummary\": {\n      \"@id\": \"tidb:DataSummary\",\n      \"@context\": {\n        \"data_summary_id\": \"@id\",\n        \"cluster_id\": {\n          \"@id\"\
  : \"tidb:clusterId\"\n        },\n        \"database\": {\n          \"@id\": \"tidb:database\"\n        },\n        \"status\": {\n          \"@id\": \"tidb:summaryStatus\"\n        }\n      }\n    },\n\n    \"Chat2DataResult\": {\n      \"@id\": \"tidb:Chat2DataResult\",\n      \"@context\": {\n        \"question_id\": \"@id\",\n        \"sql\": {\n          \"@id\": \"tidb:generatedSql\"\n        },\n        \"rows\": {\n          \"@id\": \"tidb:resultRows\",\n          \"@container\": \"@set\"\n        },\n        \"columns\": {\n          \"@id\": \"tidb:resultColumns\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/json-ld/tidb-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
