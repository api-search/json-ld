---
api_specs:
- filename: oracle-goldengate-rest-api-openapi.yml
  format: yaml
  label: Oracle GoldenGate REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/openapi/oracle-goldengate-rest-api-openapi.yml
- filename: oracle-goldengate-big-data-rest-api-openapi.yml
  format: yaml
  label: Oracle GoldenGate for Big Data REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/openapi/oracle-goldengate-big-data-rest-api-openapi.yml
- filename: oracle-goldengate-veridata-rest-api-openapi.yml
  format: yaml
  label: Oracle GoldenGate Veridata REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/openapi/oracle-goldengate-veridata-rest-api-openapi.yml
- filename: oracle-goldengate-cloud-service-api-openapi.yml
  format: yaml
  label: Oracle GoldenGate Cloud Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/openapi/oracle-goldengate-cloud-service-api-openapi.yml
- filename: oracle-goldengate-stream-analytics-rest-api-openapi.yml
  format: yaml
  label: Oracle GoldenGate Stream Analytics REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/openapi/oracle-goldengate-stream-analytics-rest-api-openapi.yml
- filename: oracle-goldengate-data-streams-rest-api-openapi.yml
  format: yaml
  label: Oracle GoldenGate Data Streams REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/openapi/oracle-goldengate-data-streams-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-goldengate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/json-ld/oracle-goldengate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Goldengate from Oracle GoldenGate.
layout: jsonld
name: Oracle Goldengate Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ogg
  uri: https://docs.oracle.com/en/middleware/goldengate/core/21.3/oggra/
- prefix: oci
  uri: https://docs.oracle.com/en-us/iaas/api/#/en/goldengate/20200407/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Extract
  type: ''
- container: ''
  name: Replicat
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: DistributionPath
  type: ''
- container: ''
  name: DataStream
  type: ''
- container: ''
  name: CredentialAlias
  type: ''
- container: ''
  name: CompareGroup
  type: ''
- container: ''
  name: ComparePair
  type: ''
- container: ''
  name: ComparisonJob
  type: ''
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: Certificate
  type: ''
- container: ''
  name: DeploymentBackup
  type: ''
- container: ''
  name: WorkRequest
  type: ''
- container: ''
  name: User
  type: ''
property_count: 16
provider_name: Oracle GoldenGate
provider_slug: oracle-goldengate
slug: oracle-goldengate-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ogg\": \"https://docs.oracle.com/en/middleware/goldengate/core/21.3/oggra/\",\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/api/#/en/goldengate/20200407/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Deployment\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"status\": \"schema:serverStatus\",\n        \"oggVersion\": \"schema:softwareVersion\",\n        \"deploymentUrl\": \"schema:url\",\n        \"publicIpAddress\": \"schema:identifier\",\n        \"fqdn\": \"schema:url\",\n        \"timeCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeUpdated\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"cpuCoreCount\": {\n          \"@id\": \"schema:processorRequirements\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:category\",\n        \"status\": \"schema:serverStatus\",\n        \"port\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"secure\": {\n          \"@id\": \"schema:isFamilyFriendly\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Extract\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:category\",\n        \"status\": \"schema:actionStatus\",\n        \"description\": \"schema:description\",\n        \"trail\": \"schema:result\",\n        \"lag\": {\n          \"@id\": \"schema:duration\",\n          \"\
  @type\": \"xsd:decimal\"\n        },\n        \"config\": \"schema:documentation\"\n      }\n    },\n\n    \"Replicat\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:category\",\n        \"status\": \"schema:actionStatus\",\n        \"description\": \"schema:description\",\n        \"trail\": \"schema:object\",\n        \"checkpointTable\": \"schema:identifier\",\n        \"lag\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"config\": \"schema:documentation\"\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"schema:EntryPoint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:category\",\n        \"connectionString\": \"schema:url\",\n        \"host\": \"schema:url\",\n        \"port\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"databaseType\"\
  : \"schema:applicationCategory\"\n      }\n    },\n\n    \"DistributionPath\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"source\": \"schema:isBasedOn\",\n        \"target\": \"schema:url\"\n      }\n    },\n\n    \"DataStream\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"source\": \"schema:isBasedOn\",\n        \"target\": \"schema:url\",\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CredentialAlias\": {\n      \"@id\": \"schema:PropertyValue\",\n      \"@context\": {\n        \"domain\"\
  : \"schema:propertyID\",\n        \"alias\": \"schema:name\",\n        \"userid\": \"schema:value\"\n      }\n    },\n\n    \"CompareGroup\": {\n      \"@id\": \"schema:ItemList\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"sourceConnectionId\": \"schema:isBasedOn\",\n        \"targetConnectionId\": \"schema:url\"\n      }\n    },\n\n    \"ComparePair\": {\n      \"@id\": \"schema:ListItem\",\n      \"@context\": {\n        \"sourceSchema\": \"schema:isPartOf\",\n        \"sourceTable\": \"schema:name\",\n        \"targetSchema\": \"schema:isPartOf\",\n        \"targetTable\": \"schema:name\"\n      }\n    },\n\n    \"ComparisonJob\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"schema:actionStatus\",\n        \"startTime\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"timeCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Certificate\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"alias\": \"schema:name\",\n        \"subject\": \"schema:about\",\n        \"issuer\": \"schema:creator\",\n        \"serialNumber\": \"schema:identifier\",\n        \"notBefore\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"notAfter\": {\n     \
  \     \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DeploymentBackup\": {\n      \"@id\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"deploymentId\": \"schema:isPartOf\",\n        \"backupType\": \"schema:category\",\n        \"sizeInBytes\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timeCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WorkRequest\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"operationType\": \"schema:name\",\n        \"status\": \"schema:actionStatus\",\n        \"percentComplete\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"timeAccepted\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"timeFinished\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"username\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"role\": \"schema:jobTitle\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/json-ld/oracle-goldengate-context.jsonld
tags:
- CDC
- Data Integration
- Data Synchronization
- Database
- Enterprise
- Real-Time Replication
- JSON-LD
- Linked Data
- Semantic Web
---
