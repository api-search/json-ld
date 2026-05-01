---
api_specs:
- filename: 9.0.5
  format: yaml
  label: WebSphere Application Server Admin API
  slug: websphere-admin-rest-api
  spec_type: OpenAPI
  url: https://www.ibm.com/docs/en/was/9.0.5?topic=api-openapi-specification
- filename: websphere-liberty-admin-rest-api.yml
  format: yaml
  label: WebSphere Liberty Admin REST API
  slug: websphere-liberty-admin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/openapi/websphere-liberty-admin-rest-api.yml
- filename: websphere-liberty-rest-connector-api.yml
  format: yaml
  label: WebSphere Liberty REST Connector API
  slug: websphere-liberty-rest-connector-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/openapi/websphere-liberty-rest-connector-api.yml
- filename: websphere-mq-rest-api.yml
  format: yaml
  label: WebSphere MQ REST API
  slug: websphere-mq-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/openapi/websphere-mq-rest-api.yml
- filename: websphere-liberty-collective-controller-rest-api.yml
  format: yaml
  label: WebSphere Liberty Collective Controller REST API
  slug: websphere-liberty-collective-controller-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/openapi/websphere-liberty-collective-controller-rest-api.yml
- filename: websphere-automation-rest-api.yml
  format: yaml
  label: WebSphere Automation REST API
  slug: websphere-automation-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/openapi/websphere-automation-rest-api.yml
- filename: open-liberty-apis.yml
  format: yaml
  label: Open Liberty APIs
  slug: open-liberty-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/openapi/open-liberty-apis.yml
class_count: 3
classes:
- name
- description
- version
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from IBM WebSphere.
layout: jsonld
name: context Context
namespaces:
- prefix: websphere
  uri: https://www.ibm.com/docs/en/was/schema/
- prefix: mq
  uri: https://www.ibm.com/docs/en/ibm-mq/schema/
- prefix: liberty
  uri: https://openliberty.io/schema/
- prefix: jee
  uri: https://jakarta.ee/schema/
properties:
- container: ''
  name: Application
  type: ''
- container: ''
  name: Server
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: MessageQueue
  type: ''
- container: ''
  name: QueueManager
  type: ''
- container: ''
  name: LibertyServer
  type: ''
- container: ''
  name: CollectiveMember
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: dateCreated
  type: schema:DateTime
- container: ''
  name: dateModified
  type: schema:DateTime
property_count: 11
provider_name: IBM WebSphere
provider_slug: websphere
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"websphere\": \"https://www.ibm.com/docs/en/was/schema/\",\n    \"mq\": \"https://www.ibm.com/docs/en/ibm-mq/schema/\",\n    \"liberty\": \"https://openliberty.io/schema/\",\n    \"jee\": \"https://jakarta.ee/schema/\",\n\n    \"Application\": {\n      \"@id\": \"websphere:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"status\": \"websphere:applicationStatus\",\n        \"type\": \"websphere:applicationType\",\n        \"contextRoot\": \"websphere:contextRoot\",\n        \"location\": \"websphere:fileLocation\",\n        \"autoStart\": \"websphere:autoStart\",\n        \"targetServer\": {\n          \"@id\": \"websphere:targetServer\",\n          \"@type\": \"@id\"\n        },\n        \"targetCluster\": {\n          \"@id\": \"websphere:targetCluster\",\n          \"\
  @type\": \"@id\"\n        },\n        \"modules\": \"websphere:hasModule\",\n        \"classloaderPolicy\": \"websphere:classloaderPolicy\",\n        \"classloaderMode\": \"websphere:classloaderMode\",\n        \"securityRoles\": \"websphere:hasSecurityRole\",\n        \"version\": \"schema:version\",\n        \"deployedDate\": {\n          \"@id\": \"websphere:deployedDate\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"Server\": {\n      \"@id\": \"websphere:Server\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"serverType\": \"websphere:serverType\",\n        \"status\": \"websphere:serverStatus\",\n        \"nodeName\": \"websphere:nodeName\",\n        \"cellName\": \"websphere:cellName\",\n      \
  \  \"clusterName\": {\n          \"@id\": \"websphere:memberOfCluster\",\n          \"@type\": \"@id\"\n        },\n        \"hostName\": \"schema:url\",\n        \"version\": \"schema:version\",\n        \"productEdition\": \"websphere:productEdition\",\n        \"pid\": \"websphere:processId\",\n        \"uptime\": \"websphere:uptime\",\n        \"installDirectory\": \"websphere:installDirectory\",\n        \"serverDirectory\": \"websphere:serverDirectory\",\n        \"ports\": \"websphere:hasPort\",\n        \"jvmConfig\": \"websphere:jvmConfiguration\",\n        \"features\": \"liberty:enabledFeature\",\n        \"applications\": \"websphere:hasDeployedApplication\",\n        \"dataSources\": \"websphere:hasDataSource\",\n        \"lastStarted\": {\n          \"@id\": \"websphere:lastStartedDate\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"Cluster\": {\n      \"@id\": \"websphere:Cluster\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"status\": \"websphere:clusterStatus\",\n        \"clusterType\": \"websphere:clusterType\",\n        \"cellName\": \"websphere:cellName\",\n        \"members\": \"websphere:hasClusterMember\",\n        \"memberCount\": \"websphere:memberCount\",\n        \"membersStarted\": \"websphere:membersStartedCount\",\n        \"preferLocal\": \"websphere:preferLocalRouting\",\n        \"loadBalancingPolicy\": \"websphere:loadBalancingPolicy\",\n        \"scalingPolicy\": \"websphere:scalingPolicy\",\n        \"applications\": \"websphere:hasDeployedApplication\",\n        \"createdDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"MessageQueue\": {\n      \"@id\": \"mq:MessageQueue\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"type\": \"mq:queueType\",\n        \"queueManager\": {\n          \"@id\": \"mq:managedByQueueManager\",\n          \"@type\": \"@id\"\n        },\n        \"maxDepth\": \"mq:maximumDepth\",\n        \"maxMessageLength\": \"mq:maximumMessageLength\",\n        \"currentDepth\": \"mq:currentDepth\",\n        \"persistence\": \"mq:persistenceConfig\",\n        \"inhibitPut\": \"mq:putInhibited\",\n        \"inhibitGet\": \"mq:getInhibited\",\n        \"triggerControl\": \"mq:triggerConfiguration\",\n        \"cluster\": \"mq:clusterConfig\",\n        \"deadLetterQueue\": {\n          \"@id\": \"mq:deadLetterQueue\",\n          \"@type\": \"@id\"\n        },\n        \"backoutThreshold\": \"mq:backoutThreshold\",\n        \"backoutQueue\": {\n          \"@id\": \"mq:backoutRequeueQueue\",\n          \"@type\": \"@id\"\n\
  \        },\n        \"shareability\": \"mq:shareability\",\n        \"status\": \"mq:runtimeStatus\",\n        \"createdDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"QueueManager\": {\n      \"@id\": \"mq:QueueManager\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"mq:queueManagerState\",\n        \"version\": \"schema:version\",\n        \"platform\": \"mq:platform\",\n        \"commandLevel\": \"mq:commandLevel\",\n        \"connectionCount\": \"mq:activeConnections\",\n        \"description\": \"schema:description\",\n        \"maximumMessageLength\": \"mq:maximumMessageLength\"\n      }\n    },\n\n    \"LibertyServer\": {\n      \"@id\": \"liberty:Server\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"wlpVersion\"\
  : \"schema:version\",\n        \"productEdition\": \"liberty:productEdition\",\n        \"serverStatus\": \"liberty:serverStatus\",\n        \"features\": \"liberty:enabledFeature\",\n        \"uptime\": \"liberty:uptime\",\n        \"installDirectory\": \"liberty:installDirectory\",\n        \"serverDirectory\": \"liberty:serverDirectory\"\n      }\n    },\n\n    \"CollectiveMember\": {\n      \"@id\": \"liberty:CollectiveMember\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"hostName\": \"schema:url\",\n        \"status\": \"liberty:memberStatus\",\n        \"clusterName\": {\n          \"@id\": \"liberty:memberOfCluster\",\n          \"@type\": \"@id\"\n        },\n        \"wlpVersion\": \"schema:version\"\n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"websphere:Vulnerability\",\n      \"@context\": {\n        \"cveIds\": \"websphere:cveIdentifier\",\n        \"severity\": \"websphere:vulnerabilitySeverity\",\n        \"cvssScore\": \"websphere:cvssBaseScore\"\
  ,\n        \"description\": \"schema:description\",\n        \"affectedServers\": \"websphere:affectsServer\",\n        \"status\": \"websphere:remediationStatus\",\n        \"availableFixes\": \"websphere:hasAvailableFix\",\n        \"publishedDate\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/json-ld/context.jsonld
tags:
- Application Server
- Cloud Native
- Enterprise Java
- J2EE
- Microservices
- Middleware
- JSON-LD
- Linked Data
- Semantic Web
---
