---
api_specs:
- filename: weblogic-restful-management-services-openapi.yml
  format: yaml
  label: WebLogic RESTful Management Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/openapi/weblogic-restful-management-services-openapi.yml
- filename: weblogic-monitoring-diagnostics-openapi.yml
  format: yaml
  label: WebLogic Monitoring and Diagnostics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/openapi/weblogic-monitoring-diagnostics-openapi.yml
- filename: weblogic-deployment-openapi.yml
  format: yaml
  label: WebLogic Deployment API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/openapi/weblogic-deployment-openapi.yml
class_count: 0
classes: []
context_file: json-ld/weblogic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/json-ld/weblogic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Weblogic from Oracle WebLogic Server APIs.
layout: jsonld
name: Weblogic Context
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
  name: Domain
  type: ''
- container: ''
  name: Server
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: AppDeployment
  type: ''
- container: ''
  name: ServerRuntime
  type: ''
- container: ''
  name: HealthState
  type: ''
- container: ''
  name: JMSServer
  type: ''
- container: ''
  name: DeploymentProgress
  type: ''
property_count: 9
provider_name: Oracle WebLogic Server APIs
provider_slug: weblogic
slug: weblogic-context
source_filename: weblogic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.oracle.com/weblogic/\",\n    \"wls\": \"https://schema.oracle.com/weblogic/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Domain\": {\n      \"@id\": \"wls:Domain\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"adminServerName\": \"wls:adminServerName\",\n        \"domainVersion\": \"schema:softwareVersion\",\n        \"productionModeEnabled\": {\n          \"@id\": \"wls:productionModeEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"configurationVersion\": \"wls:configurationVersion\",\n        \"servers\": {\n          \"@id\": \"wls:hasServer\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"clusters\": {\n          \"@id\": \"wls:hasCluster\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n\
  \        },\n        \"JDBCSystemResources\": {\n          \"@id\": \"wls:hasDataSource\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"appDeployments\": {\n          \"@id\": \"wls:hasDeployment\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Server\": {\n      \"@id\": \"wls:Server\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"listenAddress\": \"wls:listenAddress\",\n        \"listenPort\": {\n          \"@id\": \"wls:listenPort\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"SSLListenPort\": {\n          \"@id\": \"wls:SSLListenPort\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cluster\": {\n          \"@id\": \"wls:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"machine\": {\n          \"@id\": \"wls:assignedTo\",\n          \"@type\": \"@id\"\n        },\n        \"state\": \"wls:serverState\",\n     \
  \   \"startupMode\": \"wls:startupMode\",\n        \"stagingMode\": \"wls:stagingMode\",\n        \"autoRestart\": {\n          \"@id\": \"wls:autoRestart\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Cluster\": {\n      \"@id\": \"wls:Cluster\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"clusterMessagingMode\": \"wls:messagingMode\",\n        \"clusterAddress\": \"wls:clusterAddress\",\n        \"defaultLoadAlgorithm\": \"wls:loadAlgorithm\",\n        \"frontendHost\": \"wls:frontendHost\",\n        \"frontendHTTPPort\": {\n          \"@id\": \"wls:frontendHTTPPort\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"frontendHTTPSPort\": {\n          \"@id\": \"wls:frontendHTTPSPort\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"members\": {\n          \"@id\": \"wls:hasMember\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n\
  \      \"@id\": \"wls:DataSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"targets\": {\n          \"@id\": \"wls:targetedTo\",\n          \"@container\": \"@set\"\n        },\n        \"JNDINames\": {\n          \"@id\": \"wls:jndiName\",\n          \"@container\": \"@set\"\n        },\n        \"url\": \"wls:jdbcUrl\",\n        \"driverName\": \"wls:jdbcDriver\",\n        \"initialCapacity\": {\n          \"@id\": \"wls:initialCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxCapacity\": {\n          \"@id\": \"wls:maxCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"minCapacity\": {\n          \"@id\": \"wls:minCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"state\": \"wls:dataSourceState\",\n        \"enabled\": {\n          \"@id\": \"wls:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"AppDeployment\": {\n      \"@id\": \"wls:AppDeployment\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"sourcePath\": \"wls:sourcePath\",\n        \"targets\": {\n          \"@id\": \"wls:targetedTo\",\n          \"@container\": \"@set\"\n        },\n        \"moduleType\": \"wls:moduleType\",\n        \"planPath\": \"wls:planPath\",\n        \"stagingMode\": \"wls:stagingMode\",\n        \"versionIdentifier\": \"schema:version\",\n        \"deploymentOrder\": {\n          \"@id\": \"wls:deploymentOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ServerRuntime\": {\n      \"@id\": \"wls:ServerRuntime\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"wls:serverState\",\n        \"weblogicVersion\": \"schema:softwareVersion\",\n        \"activationTime\": {\n          \"@id\": \"wls:activationTime\",\n          \"@type\": \"xsd:long\"\n        },\n        \"healthState\": {\n          \"@id\": \"wls:healthState\",\n          \"@type\": \"@id\"\n      \
  \  },\n        \"heapSizeCurrent\": {\n          \"@id\": \"wls:heapSizeCurrent\",\n          \"@type\": \"xsd:long\"\n        },\n        \"heapSizeMax\": {\n          \"@id\": \"wls:heapSizeMax\",\n          \"@type\": \"xsd:long\"\n        },\n        \"heapFreeCurrent\": {\n          \"@id\": \"wls:heapFreeCurrent\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"HealthState\": {\n      \"@id\": \"wls:HealthState\",\n      \"@context\": {\n        \"state\": \"wls:healthValue\",\n        \"subsystemName\": \"wls:subsystem\",\n        \"symptoms\": {\n          \"@id\": \"wls:symptom\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"JMSServer\": {\n      \"@id\": \"wls:JMSServer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"messagesCurrentCount\": {\n          \"@id\": \"wls:currentMessages\",\n          \"@type\": \"xsd:long\"\n        },\n        \"messagesPendingCount\": {\n          \"@id\": \"wls:pendingMessages\"\
  ,\n          \"@type\": \"xsd:long\"\n        },\n        \"consumersCurrentCount\": {\n          \"@id\": \"wls:currentConsumers\",\n          \"@type\": \"xsd:long\"\n        },\n        \"destinationsCurrentCount\": {\n          \"@id\": \"wls:currentDestinations\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"DeploymentProgress\": {\n      \"@id\": \"wls:DeploymentProgress\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"wls:deploymentState\",\n        \"progress\": \"wls:progressDescription\",\n        \"completed\": {\n          \"@id\": \"wls:completed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"failed\": {\n          \"@id\": \"wls:failed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/json-ld/weblogic-context.jsonld
tags:
- Application Server
- Enterprise
- Java EE
- Middleware
- Oracle
- WebLogic
- JSON-LD
- Linked Data
- Semantic Web
---
