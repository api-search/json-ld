---
api_specs:
- filename: sap-hana-cloud-rest-api.yml
  format: yaml
  label: SAP HANA Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-hana/refs/heads/main/openapi/sap-hana-cloud-rest-api.yml
class_count: 0
classes: []
context_file: json-ld/sap-hana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-hana/refs/heads/main/json-ld/sap-hana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Hana from SAP HANA.
layout: jsonld
name: Sap Hana Context
namespaces:
- prefix: saphana
  uri: https://help.sap.com/docs/HANA_CLOUD/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DatabaseInstance
  type: ''
- container: ''
  name: InstanceContext
  type: ''
- container: ''
  name: InstanceConfiguration
  type: ''
- container: ''
  name: EnabledServices
  type: ''
- container: ''
  name: ConnectionEndpoints
  type: ''
- container: ''
  name: LastOperation
  type: ''
- container: ''
  name: AlertEvent
  type: ''
- container: ''
  name: AlertRule
  type: ''
- container: ''
  name: MetricSeries
  type: ''
- container: ''
  name: MetricDataPoint
  type: ''
- container: ''
  name: MeteringValue
  type: ''
- container: ''
  name: InstanceMapping
  type: ''
- container: ''
  name: InstanceMetrics
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 14
provider_name: SAP HANA
provider_slug: sap-hana
slug: sap-hana-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"saphana\": \"https://help.sap.com/docs/HANA_CLOUD/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DatabaseInstance\": {\n      \"@id\": \"saphana:DatabaseInstance\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"service_plan_id\": {\n          \"@id\": \"saphana:servicePlanId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"service_plan_name\": {\n          \"@id\": \"saphana:servicePlanName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"platform_id\": {\n          \"@id\": \"saphana:platformId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n      \
  \    \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ready\": {\n          \"@id\": \"saphana:ready\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"usable\": {\n          \"@id\": \"saphana:usable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"provisioningState\": {\n          \"@id\": \"saphana:provisioningState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operationalState\": {\n          \"@id\": \"saphana:operationalState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"saphana:labels\",\n          \"@type\": \"@id\"\n        },\n        \"context\": {\n          \"@id\": \"saphana:instanceContext\",\n          \"@type\": \"@id\"\n        },\n        \"parameters\": {\n          \"@id\": \"saphana:instanceConfiguration\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"last_operation\": {\n          \"@id\": \"saphana:lastOperation\",\n          \"@type\": \"@id\"\n        },\n        \"connectionEndpoints\": {\n          \"@id\": \"saphana:connectionEndpoints\",\n          \"@type\": \"@id\"\n        },\n        \"alerts\": {\n          \"@id\": \"saphana:alerts\",\n          \"@container\": \"@set\"\n        },\n        \"metrics\": {\n          \"@id\": \"saphana:instanceMetrics\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"InstanceContext\": {\n      \"@id\": \"saphana:InstanceContext\",\n      \"@context\": {\n        \"subaccount_id\": {\n          \"@id\": \"saphana:subaccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organization_guid\": {\n          \"@id\": \"saphana:organizationGuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"space_guid\": {\n          \"@id\": \"saphana:spaceGuid\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"instance_name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n          \"@id\": \"saphana:region\",\n          \"@type\": \"xsd:string\"\n        },\n        \"landscapeLabel\": {\n          \"@id\": \"saphana:landscapeLabel\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"InstanceConfiguration\": {\n      \"@id\": \"saphana:InstanceConfiguration\",\n      \"@context\": {\n        \"edition\": {\n          \"@id\": \"saphana:edition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"memory\": {\n          \"@id\": \"saphana:memoryGB\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vcpu\": {\n          \"@id\": \"saphana:vcpuCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"storage\": {\n          \"@id\": \"saphana:storageGB\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"whitelistIPs\": {\n          \"@id\"\
  : \"saphana:whitelistIPs\",\n          \"@container\": \"@set\"\n        },\n        \"serviceStopped\": {\n          \"@id\": \"saphana:serviceStopped\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"availabilityZone\": {\n          \"@id\": \"saphana:availabilityZone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slaLevel\": {\n          \"@id\": \"saphana:slaLevel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabledservices\": {\n          \"@id\": \"saphana:enabledServices\",\n          \"@type\": \"@id\"\n        },\n        \"replicaCount\": {\n          \"@id\": \"saphana:replicaCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EnabledServices\": {\n      \"@id\": \"saphana:EnabledServices\",\n      \"@context\": {\n        \"scriptserver\": {\n          \"@id\": \"saphana:scriptServerEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"docstore\": {\n          \"@id\": \"saphana:documentStoreEnabled\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dpserver\": {\n          \"@id\": \"saphana:dataProvisioningServerEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ConnectionEndpoints\": {\n      \"@id\": \"saphana:ConnectionEndpoints\",\n      \"@context\": {\n        \"host\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"saphana:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sqlEndpoint\": {\n          \"@id\": \"saphana:sqlEndpoint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"httpsEndpoint\": {\n          \"@id\": \"saphana:httpsEndpoint\",\n          \"@type\": \"xsd:anyURI\"\n        }\n      }\n    },\n\n    \"LastOperation\": {\n      \"@id\": \"saphana:LastOperation\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"saphana:operationType\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"state\": {\n          \"@id\": \"saphana:operationState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AlertEvent\": {\n      \"@id\": \"saphana:AlertEvent\",\n      \"@context\": {\n        \"alertId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alertRuleId\": {\n          \"@id\": \"saphana:alertRuleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alertName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alertState\": {\n          \"@id\": \"saphana:alertState\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": {\n          \"@id\": \"saphana:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"triggeredAt\": {\n          \"@id\": \"saphana:triggeredAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolvedAt\": {\n          \"@id\": \"saphana:resolvedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"currentValue\": {\n          \"@id\": \"saphana:currentValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"thresholdValue\": {\n          \"@id\": \"saphana:thresholdValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"unit\": {\n          \"@id\": \"saphana:unit\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AlertRule\": {\n      \"@id\": \"saphana:AlertRule\",\n      \"@context\": {\n  \
  \      \"ruleId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ruleName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ruleType\": {\n          \"@id\": \"saphana:ruleType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\": \"saphana:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"severity\": {\n          \"@id\": \"saphana:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metric\": {\n          \"@id\": \"saphana:metric\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thresholdOperator\": {\n          \"@id\": \"saphana:thresholdOperator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thresholdValue\": {\n          \"@id\": \"saphana:thresholdValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"unit\": {\n          \"@id\": \"saphana:unit\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MetricSeries\": {\n      \"@id\": \"saphana:MetricSeries\",\n      \"@context\": {\n        \"metricType\": {\n          \"@id\": \"saphana:metricType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"unit\": {\n          \"@id\": \"saphana:unit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataPoints\": {\n          \"@id\": \"saphana:dataPoints\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"MetricDataPoint\": {\n      \"@id\": \"saphana:MetricDataPoint\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"value\": {\n          \"@id\": \"saphana:value\",\n          \"@type\": \"xsd:double\"\n        },\n        \"min\": {\n          \"\
  @id\": \"saphana:minValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"max\": {\n          \"@id\": \"saphana:maxValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"avg\": {\n          \"@id\": \"saphana:avgValue\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"MeteringValue\": {\n      \"@id\": \"saphana:MeteringValue\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"computeUnitHours\": {\n          \"@id\": \"saphana:computeUnitHours\",\n          \"@type\": \"xsd:double\"\n        },\n        \"storageGB\": {\n          \"@id\": \"saphana:storageGB\",\n          \"@type\": \"xsd:double\"\n        },\n        \"dataLakeCapacityGB\": {\n          \"@id\": \"saphana:dataLakeCapacityGB\",\n          \"@type\": \"xsd:double\"\n        },\n        \"backupStorageGB\": {\n          \"@id\": \"saphana:backupStorageGB\",\n      \
  \    \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"InstanceMapping\": {\n      \"@id\": \"saphana:InstanceMapping\",\n      \"@context\": {\n        \"mappingId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceInstanceId\": {\n          \"@id\": \"saphana:serviceInstanceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"targetSubaccountId\": {\n          \"@id\": \"saphana:targetSubaccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"targetEnvironmentInstanceId\": {\n          \"@id\": \"saphana:targetEnvironmentInstanceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"InstanceMetrics\": {\n      \"@id\": \"saphana:InstanceMetrics\",\n      \"@context\": {\n        \"cpuUsagePercent\": {\n          \"@id\": \"saphana:cpuUsagePercent\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"memoryUsedGB\": {\n          \"@id\": \"saphana:memoryUsedGB\",\n          \"@type\": \"xsd:double\"\n        },\n        \"memoryAllocatedGB\": {\n          \"@id\": \"saphana:memoryAllocatedGB\",\n          \"@type\": \"xsd:double\"\n        },\n        \"diskUsedGB\": {\n          \"@id\": \"saphana:diskUsedGB\",\n          \"@type\": \"xsd:double\"\n        },\n        \"diskAllocatedGB\": {\n          \"@id\": \"saphana:diskAllocatedGB\",\n          \"@type\": \"xsd:double\"\n        },\n        \"activeConnections\": {\n          \"@id\": \"saphana:activeConnections\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalConnections\": {\n          \"@id\": \"saphana:totalConnections\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statementsPerSecond\": {\n          \"@id\": \"saphana:statementsPerSecond\",\n          \"@type\": \"xsd:double\"\n        },\n        \"longRunningStatements\"\
  : {\n          \"@id\": \"saphana:longRunningStatements\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"columnStoreUnloads\": {\n          \"@id\": \"saphana:columnStoreUnloads\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastBackupTimestamp\": {\n          \"@id\": \"saphana:lastBackupTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Error\": {\n      \"@id\": \"saphana:Error\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"saphana:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statusCode\": {\n          \"@id\": \"saphana:httpStatusCode\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-hana/refs/heads/main/json-ld/sap-hana-context.jsonld
tags:
- Analytics
- Cloud
- Database
- Enterprise
- In-Memory
- JSON-LD
- Linked Data
- Semantic Web
---
