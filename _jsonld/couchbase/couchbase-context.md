---
api_specs:
- filename: couchbase-server-rest-api-openapi.yml
  format: yaml
  label: Couchbase Server REST API
  slug: couchbase-server-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-server-rest-api-openapi.yml
- filename: couchbase-query-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Query Service REST API
  slug: couchbase-query-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-query-service-rest-api-openapi.yml
- filename: couchbase-analytics-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Analytics Service REST API
  slug: couchbase-analytics-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-analytics-service-rest-api-openapi.yml
- filename: couchbase-search-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Search Service REST API
  slug: couchbase-search-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-search-service-rest-api-openapi.yml
- filename: couchbase-eventing-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Eventing Service REST API
  slug: couchbase-eventing-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-eventing-service-rest-api-openapi.yml
- filename: couchbase-backup-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Backup Service REST API
  slug: couchbase-backup-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-backup-service-rest-api-openapi.yml
- filename: couchbase-xdcr-rest-api-openapi.yml
  format: yaml
  label: Couchbase XDCR REST API
  slug: couchbase-xdcr-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-xdcr-rest-api-openapi.yml
- filename: couchbase-capella-management-api-openapi.yml
  format: yaml
  label: Couchbase Capella Management API
  slug: couchbase-capella-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-capella-management-api-openapi.yml
- filename: couchbase-capella-app-services-public-api-openapi.yml
  format: yaml
  label: Couchbase Capella App Services Public API
  slug: couchbase-capella-app-services-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-capella-app-services-public-api-openapi.yml
- filename: couchbase-capella-app-services-admin-api-openapi.yml
  format: yaml
  label: Couchbase Capella App Services Admin API
  slug: couchbase-capella-app-services-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-capella-app-services-admin-api-openapi.yml
- filename: couchbase-sync-gateway-public-rest-api-openapi.yml
  format: yaml
  label: Couchbase Sync Gateway Public REST API
  slug: couchbase-sync-gateway-public-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-sync-gateway-public-rest-api-openapi.yml
- filename: couchbase-sync-gateway-admin-rest-api-openapi.yml
  format: yaml
  label: Couchbase Sync Gateway Admin REST API
  slug: couchbase-sync-gateway-admin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-sync-gateway-admin-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/couchbase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/json-ld/couchbase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Couchbase from Couchbase.
layout: jsonld
name: Couchbase Context
namespaces:
- prefix: cb
  uri: https://couchbase.com/ns/
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
  name: Node
  type: ''
- container: ''
  name: Bucket
  type: ''
- container: ''
  name: Scope
  type: ''
- container: ''
  name: Collection
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: SearchIndex
  type: ''
- container: ''
  name: EventingFunction
  type: ''
- container: ''
  name: Replication
  type: ''
- container: ''
  name: BackupRepository
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: SyncGatewayDatabase
  type: ''
property_count: 14
provider_name: Couchbase
provider_slug: couchbase
slug: couchbase-context
source_filename: couchbase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cb\": \"https://couchbase.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Cluster\": {\n      \"@id\": \"cb:Cluster\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"uuid\": \"cb:uuid\",\n        \"nodes\": {\n          \"@id\": \"cb:nodes\",\n          \"@container\": \"@set\"\n        },\n        \"serverGroups\": {\n          \"@id\": \"cb:serverGroups\",\n          \"@container\": \"@set\"\n        },\n        \"version\": \"schema:softwareVersion\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"cb:Node\",\n      \"@context\": {\n        \"hostname\": \"cb:hostname\",\n        \"status\": \"cb:status\",\n        \"clusterMembership\": \"cb:clusterMembership\",\n        \"services\": {\n          \"@id\": \"cb:services\",\n   \
  \       \"@container\": \"@set\"\n        },\n        \"version\": \"schema:softwareVersion\",\n        \"os\": \"schema:operatingSystem\",\n        \"memoryTotal\": \"cb:memoryTotal\",\n        \"memoryFree\": \"cb:memoryFree\"\n      }\n    },\n\n    \"Bucket\": {\n      \"@id\": \"cb:Bucket\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"bucketType\": \"cb:bucketType\",\n        \"ramQuota\": \"cb:ramQuota\",\n        \"replicaNumber\": \"cb:replicaNumber\",\n        \"evictionPolicy\": \"cb:evictionPolicy\",\n        \"conflictResolutionType\": \"cb:conflictResolutionType\",\n        \"durabilityMinLevel\": \"cb:durabilityMinLevel\",\n        \"itemCount\": \"cb:itemCount\",\n        \"scopes\": {\n          \"@id\": \"cb:scopes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Scope\": {\n      \"@id\": \"cb:Scope\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"collections\": {\n          \"@id\": \"cb:collections\"\
  ,\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Collection\": {\n      \"@id\": \"cb:Collection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"maxTTL\": \"cb:maxTTL\"\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"cb:Document\",\n      \"@context\": {\n        \"documentId\": \"dcterms:identifier\",\n        \"revision\": \"cb:revision\",\n        \"expiry\": {\n          \"@id\": \"cb:expiry\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deleted\": \"cb:deleted\",\n        \"channels\": {\n          \"@id\": \"cb:channels\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SearchIndex\": {\n      \"@id\": \"cb:SearchIndex\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"sourceName\": \"cb:sourceName\",\n        \"indexType\": \"cb:indexType\",\n        \"documentCount\": \"cb:documentCount\",\n        \"uuid\": \"cb:uuid\"\n      }\n    },\n\n    \"EventingFunction\"\
  : {\n      \"@id\": \"cb:EventingFunction\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"appcode\": \"cb:appcode\",\n        \"deploymentStatus\": \"cb:deploymentStatus\",\n        \"processingStatus\": \"cb:processingStatus\",\n        \"sourceBucket\": \"cb:sourceBucket\",\n        \"metadataBucket\": \"cb:metadataBucket\"\n      }\n    },\n\n    \"Replication\": {\n      \"@id\": \"cb:Replication\",\n      \"@context\": {\n        \"replicationId\": \"dcterms:identifier\",\n        \"sourceBucket\": \"cb:sourceBucket\",\n        \"targetBucket\": \"cb:targetBucket\",\n        \"targetCluster\": {\n          \"@id\": \"cb:targetCluster\",\n          \"@type\": \"@id\"\n        },\n        \"replicationType\": \"cb:replicationType\",\n        \"compressionType\": \"cb:compressionType\",\n        \"filterExpression\": \"cb:filterExpression\"\n      }\n    },\n\n    \"BackupRepository\": {\n      \"@id\": \"cb:BackupRepository\",\n      \"@context\": {\n      \
  \  \"name\": \"schema:name\",\n        \"planName\": \"cb:planName\",\n        \"state\": \"cb:state\",\n        \"archive\": {\n          \"@id\": \"cb:archive\",\n          \"@type\": \"@id\"\n        },\n        \"backups\": {\n          \"@id\": \"cb:backups\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"cb:User\",\n      \"@context\": {\n        \"username\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"domain\": \"cb:domain\",\n        \"roles\": {\n          \"@id\": \"cb:roles\",\n          \"@container\": \"@set\"\n        },\n        \"channels\": {\n          \"@id\": \"cb:channels\",\n          \"@container\": \"@set\"\n        },\n        \"disabled\": \"cb:disabled\"\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"cb:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"organizationId\": \"dcterms:identifier\"\
  ,\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"cb:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"projectId\": \"dcterms:identifier\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SyncGatewayDatabase\": {\n      \"@id\": \"cb:SyncGatewayDatabase\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"bucket\": \"cb:bucket\",\n        \"syncFunction\": \"cb:syncFunction\",\n        \"importFilter\": \"cb:importFilter\",\n        \"state\": \"cb:state\",\n        \"deltaSyncEnabled\": \"cb:deltaSyncEnabled\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/json-ld/couchbase-context.jsonld
tags:
- Analytics
- App Services
- Backup
- Capella
- Cloud
- Database
- DBaaS
- Eventing
- Full-Text Search
- Gateway
- JSON
- Mobile
- NoSQL
- Replication
- SQL++
- Sync
- Vector Search
- XDCR
- JSON-LD
- Linked Data
- Semantic Web
---
