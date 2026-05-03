---
api_specs:
- filename: oracle-weblogic-management-openapi.yml
  format: yaml
  label: WebLogic RESTful Management Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/openapi/oracle-weblogic-management-openapi.yml
- filename: oracle-weblogic-monitoring-openapi.yml
  format: yaml
  label: WebLogic Monitoring and Diagnostics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/openapi/oracle-weblogic-monitoring-openapi.yml
- filename: oracle-weblogic-deployment-openapi.yml
  format: yaml
  label: WebLogic Deployment API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/openapi/oracle-weblogic-deployment-openapi.yml
class_count: 40
classes:
- Domain
- Server
- Cluster
- Machine
- ServerTemplate
- AppDeployment
- LibDeployment
- JDBCSystemResource
- JDBCResource
- JDBCDataSourceParams
- JDBCDriverParams
- JDBCConnectionPoolParams
- JMSSystemResource
- JMSServer
- JMSResource
- ConnectionFactory
- UniformDistributedQueue
- UniformDistributedTopic
- FileStore
- SecurityRealm
- AuthenticationProvider
- VirtualTarget
- Partition
- ResourceGroup
- NodeManager
- SSLConfiguration
- NetworkAccessPoint
- DynamicServers
- ServerRuntime
- ServerLifeCycleRuntime
- ApplicationRuntime
- ComponentRuntime
- ServletRuntime
- JDBCServiceRuntime
- JDBCDataSourceRuntime
- JMSRuntime
- JMSServerRuntime
- ThreadPoolRuntime
- HealthState
- TaskStatus
context_file: json-ld/oracle-weblogic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/json-ld/oracle-weblogic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Weblogic from Oracle WebLogic Server.
layout: jsonld
name: Oracle Weblogic Context
namespaces:
- prefix: wls
  uri: https://schema.oracle.com/weblogic/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: list
  name: identity
  type: ''
- container: ''
  name: state
  type: string
- container: ''
  name: listenPort
  type: integer
- container: ''
  name: listenAddress
  type: string
- container: ''
  name: listenPortEnabled
  type: boolean
- container: ''
  name: SSLListenPort
  type: integer
- container: ''
  name: administrationPort
  type: integer
- container: ''
  name: defaultProtocol
  type: string
- container: ''
  name: machine
  type: reference
- container: ''
  name: cluster
  type: reference
- container: set
  name: targets
  type: ''
- container: ''
  name: sourcePath
  type: string
- container: ''
  name: deploymentOrder
  type: integer
- container: ''
  name: planPath
  type: string
- container: list
  name: JNDINames
  type: ''
- container: ''
  name: JNDIName
  type: string
- container: ''
  name: driverName
  type: string
- container: ''
  name: url
  type: string
- container: ''
  name: messagesMaximum
  type: integer
- container: ''
  name: bytesMaximum
  type: integer
- container: ''
  name: persistentStore
  type: reference
- container: ''
  name: clusterMessagingMode
  type: string
- container: ''
  name: dynamicClusterSize
  type: integer
- container: ''
  name: serverTemplate
  type: reference
- container: ''
  name: serverNamePrefix
  type: string
- container: ''
  name: NMType
  type: string
- container: list
  name: hostNames
  type: ''
- container: ''
  name: uriPrefix
  type: string
- container: ''
  name: realm
  type: reference
- container: ''
  name: primaryIdentityDomain
  type: string
- container: ''
  name: healthState
  type: wls:HealthState
- container: ''
  name: weblogicVersion
  type: string
- container: ''
  name: adminServer
  type: boolean
- container: ''
  name: restartRequired
  type: boolean
- container: ''
  name: running
  type: boolean
- container: ''
  name: completed
  type: boolean
- container: ''
  name: taskStatus
  type: string
- container: ''
  name: progress
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: activeConnectionsCurrentCount
  type: integer
- container: ''
  name: currCapacity
  type: integer
- container: ''
  name: numAvailable
  type: integer
- container: ''
  name: executeThreadTotalCount
  type: integer
- container: ''
  name: hoggingThreadCount
  type: integer
- container: ''
  name: throughput
  type: double
- container: ''
  name: openSessionsCurrentCount
  type: integer
- container: ''
  name: invocationTotalCount
  type: integer
- container: set
  name: links
  type: ''
- container: ''
  name: rel
  type: string
- container: ''
  name: href
  type: reference
property_count: 54
provider_name: Oracle WebLogic Server
provider_slug: oracle-weblogic
slug: oracle-weblogic-context
source_filename: oracle-weblogic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.oracle.com/weblogic/\",\n    \"wls\": \"https://schema.oracle.com/weblogic/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Domain\": \"wls:Domain\",\n    \"Server\": \"wls:Server\",\n    \"Cluster\": \"wls:Cluster\",\n    \"Machine\": \"wls:Machine\",\n    \"ServerTemplate\": \"wls:ServerTemplate\",\n    \"AppDeployment\": \"wls:AppDeployment\",\n    \"LibDeployment\": \"wls:LibDeployment\",\n    \"JDBCSystemResource\": \"wls:JDBCSystemResource\",\n    \"JDBCResource\": \"wls:JDBCResource\",\n    \"JDBCDataSourceParams\": \"wls:JDBCDataSourceParams\",\n    \"JDBCDriverParams\": \"wls:JDBCDriverParams\",\n    \"JDBCConnectionPoolParams\": \"wls:JDBCConnectionPoolParams\",\n    \"JMSSystemResource\": \"wls:JMSSystemResource\",\n    \"JMSServer\": \"wls:JMSServer\",\n    \"JMSResource\": \"wls:JMSResource\"\
  ,\n    \"ConnectionFactory\": \"wls:ConnectionFactory\",\n    \"UniformDistributedQueue\": \"wls:UniformDistributedQueue\",\n    \"UniformDistributedTopic\": \"wls:UniformDistributedTopic\",\n    \"FileStore\": \"wls:FileStore\",\n    \"SecurityRealm\": \"wls:SecurityRealm\",\n    \"AuthenticationProvider\": \"wls:AuthenticationProvider\",\n    \"VirtualTarget\": \"wls:VirtualTarget\",\n    \"Partition\": \"wls:Partition\",\n    \"ResourceGroup\": \"wls:ResourceGroup\",\n    \"NodeManager\": \"wls:NodeManager\",\n    \"SSLConfiguration\": \"wls:SSLConfiguration\",\n    \"NetworkAccessPoint\": \"wls:NetworkAccessPoint\",\n    \"DynamicServers\": \"wls:DynamicServers\",\n\n    \"ServerRuntime\": \"wls:ServerRuntime\",\n    \"ServerLifeCycleRuntime\": \"wls:ServerLifeCycleRuntime\",\n    \"ApplicationRuntime\": \"wls:ApplicationRuntime\",\n    \"ComponentRuntime\": \"wls:ComponentRuntime\",\n    \"ServletRuntime\": \"wls:ServletRuntime\",\n    \"JDBCServiceRuntime\": \"wls:JDBCServiceRuntime\"\
  ,\n    \"JDBCDataSourceRuntime\": \"wls:JDBCDataSourceRuntime\",\n    \"JMSRuntime\": \"wls:JMSRuntime\",\n    \"JMSServerRuntime\": \"wls:JMSServerRuntime\",\n    \"ThreadPoolRuntime\": \"wls:ThreadPoolRuntime\",\n    \"HealthState\": \"wls:HealthState\",\n    \"TaskStatus\": \"wls:TaskStatus\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identity\": {\n      \"@id\": \"wls:identity\",\n      \"@container\": \"@list\"\n    },\n    \"state\": {\n      \"@id\": \"wls:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listenPort\": {\n      \"@id\": \"wls:listenPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"listenAddress\": {\n      \"@id\": \"wls:listenAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listenPortEnabled\": {\n      \"@id\": \"wls:listenPortEnabled\",\n      \"@type\": \"xsd:boolean\"\n  \
  \  },\n    \"SSLListenPort\": {\n      \"@id\": \"wls:SSLListenPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"administrationPort\": {\n      \"@id\": \"wls:administrationPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"defaultProtocol\": {\n      \"@id\": \"wls:defaultProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"machine\": {\n      \"@id\": \"wls:machine\",\n      \"@type\": \"@id\"\n    },\n    \"cluster\": {\n      \"@id\": \"wls:cluster\",\n      \"@type\": \"@id\"\n    },\n    \"targets\": {\n      \"@id\": \"wls:targets\",\n      \"@container\": \"@set\"\n    },\n    \"sourcePath\": {\n      \"@id\": \"wls:sourcePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentOrder\": {\n      \"@id\": \"wls:deploymentOrder\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"planPath\": {\n      \"@id\": \"wls:planPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JNDINames\": {\n      \"@id\": \"wls:JNDINames\",\n      \"@container\": \"@list\"\
  \n    },\n    \"JNDIName\": {\n      \"@id\": \"wls:JNDIName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"driverName\": {\n      \"@id\": \"wls:driverName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messagesMaximum\": {\n      \"@id\": \"wls:messagesMaximum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bytesMaximum\": {\n      \"@id\": \"wls:bytesMaximum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"persistentStore\": {\n      \"@id\": \"wls:persistentStore\",\n      \"@type\": \"@id\"\n    },\n    \"clusterMessagingMode\": {\n      \"@id\": \"wls:clusterMessagingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamicClusterSize\": {\n      \"@id\": \"wls:dynamicClusterSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serverTemplate\": {\n      \"@id\": \"wls:serverTemplate\",\n      \"@type\": \"@id\"\n    },\n    \"serverNamePrefix\": {\n      \"@id\": \"wls:serverNamePrefix\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"NMType\": {\n      \"@id\": \"wls:NMType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostNames\": {\n      \"@id\": \"wls:hostNames\",\n      \"@container\": \"@list\"\n    },\n    \"uriPrefix\": {\n      \"@id\": \"wls:uriPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realm\": {\n      \"@id\": \"wls:realm\",\n      \"@type\": \"@id\"\n    },\n    \"primaryIdentityDomain\": {\n      \"@id\": \"wls:primaryIdentityDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthState\": {\n      \"@id\": \"wls:healthState\",\n      \"@type\": \"wls:HealthState\"\n    },\n    \"weblogicVersion\": {\n      \"@id\": \"wls:weblogicVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adminServer\": {\n      \"@id\": \"wls:adminServer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"restartRequired\": {\n      \"@id\": \"wls:restartRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"running\": {\n      \"@id\"\
  : \"wls:running\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"completed\": {\n      \"@id\": \"wls:completed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taskStatus\": {\n      \"@id\": \"wls:taskStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress\": {\n      \"@id\": \"wls:progress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"wls:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"wls:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"wls:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"activeConnectionsCurrentCount\": {\n      \"@id\": \"wls:activeConnectionsCurrentCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currCapacity\": {\n      \"@id\": \"wls:currCapacity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numAvailable\": {\n      \"@id\": \"wls:numAvailable\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"executeThreadTotalCount\": {\n      \"@id\": \"wls:executeThreadTotalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hoggingThreadCount\": {\n      \"@id\": \"wls:hoggingThreadCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throughput\": {\n      \"@id\": \"wls:throughput\",\n      \"@type\": \"xsd:double\"\n    },\n    \"openSessionsCurrentCount\": {\n      \"@id\": \"wls:openSessionsCurrentCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"invocationTotalCount\": {\n      \"@id\": \"wls:invocationTotalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"wls:links\",\n      \"@container\": \"@set\"\n    },\n    \"rel\": {\n      \"@id\": \"wls:rel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"wls:href\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/json-ld/oracle-weblogic-context.jsonld
tags:
- Application Server
- Enterprise
- Java EE
- Middleware
- Oracle
- JSON-LD
- Linked Data
- Semantic Web
---
