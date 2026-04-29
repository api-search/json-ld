---
class_count: 119
classes:
- EncryptedKey
- ViewHistoryEntry
- RemoveSchemasUpdate
- DataFile
- BaseUpdate
- RemoteSignResult
- AddSortOrderUpdate
- RemoteSignRequest
- FetchScanTasksRequest
- CounterResult
- AddPartitionSpecUpdate
- PartitionField
- SetExpression
- OAuthTokenResponse
- ListNamespacesResponse
- StatisticsFile
- LoadTableResult
- TableRequirement
- ValueMap
- SetPropertiesUpdate
- OAuthTokenExchangeRequest
- AssertDefaultSpecId
- CatalogConfig
- AsyncPlanningResult
- CreateNamespaceRequest
- AssertTableUUID
- SnapshotReference
- AssertRefSnapshotId
- CreateViewRequest
- TrueExpression
- SortOrder
- RegisterViewRequest
- AddSchemaUpdate
- ContentFile
- SnapshotReferences
- MultiValuedMap
- Snapshot
- BlobMetadata
- UpdateNamespacePropertiesResponse
- CommitTableResponse
- PartitionStatisticsFile
- StructType
- RemoveSnapshotRefUpdate
- UpdateNamespacePropertiesRequest
- CommitTableRequest
- PlanTableScanRequest
- UnaryExpression
- AssertDefaultSortOrderId
- ReportMetricsRequest
- FailedPlanningResult
- AssertViewUUID
- FetchPlanningResult
- ScanReport
- AndOrExpression
- ViewRequirement
- AssertCurrentSchemaId
- SetCurrentSchemaUpdate
- RegisterTableRequest
- AssignUUIDUpdate
- CommitReport
- LoadCredentialsResponse
- SetStatisticsUpdate
- FetchScanTasksResult
- AssertCreate
- SetLocationUpdate
- RemoveSnapshotsUpdate
- FileScanTask
- ScanTasks
- Metrics
- CreateTableRequest
- CompletedPlanningResult
- LoadViewResult
- ViewVersion
- EqualityDeleteFile
- RemoveEncryptionKeyUpdate
- RemoveStatisticsUpdate
- OAuthClientCredentialsRequest
- AddViewVersionUpdate
- RenameTableRequest
- CompletedPlanningWithIDResult
- ListTablesResponse
- AssertLastAssignedFieldId
- PartitionSpec
- AddEncryptionKeyUpdate
- TransformTerm
- SQLViewRepresentation
- CommitViewRequest
- RemovePartitionStatisticsUpdate
- TableMetadata
- AddSnapshotUpdate
- RemovePartitionSpecsUpdate
- SetDefaultSpecUpdate
- SetSnapshotRefUpdate
- StorageCredential
- SortField
- ViewMetadata
- AssertLastAssignedPartitionId
- CommitTransactionRequest
- NotExpression
- CountMap
- SetPartitionStatisticsUpdate
- OAuthError
- StructField
- FalseExpression
- PositionDeleteFile
- TimerResult
- SetCurrentViewVersionUpdate
- SetDefaultSortOrderUpdate
- PlanTableScanResult
- GetNamespaceResponse
- EmptyPlanningResult
- UpgradeFormatVersionUpdate
- ListType
- RemovePropertiesUpdate
- LiteralExpression
- CreateNamespaceResponse
- TableIdentifier
- MapType
- name
context_file: json-ld/apache-iceberg-rest-catalog-open-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/json-ld/apache-iceberg-rest-catalog-open-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Iceberg Rest Catalog Open Api from Apache Iceberg.
layout: jsonld
name: Apache Iceberg Rest Catalog Open Api Context
namespaces:
- prefix: iceberg
  uri: https://iceberg.apache.org/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: string
- container: ''
  name: key-id
  type: string
- container: ''
  name: encrypted-key-metadata
  type: string
- container: ''
  name: encrypted-by-id
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: version-id
  type: integer
- container: ''
  name: timestamp-ms
  type: integer
- container: ''
  name: action
  type: string
- container: set
  name: schema-ids
  type: integer
- container: ''
  name: content
  type: string
- container: ''
  name: first-row-id
  type: integer
- container: ''
  name: column-sizes
  type: string
- container: ''
  name: value-counts
  type: string
- container: ''
  name: null-value-counts
  type: string
- container: ''
  name: nan-value-counts
  type: string
- container: ''
  name: lower-bounds
  type: string
- container: ''
  name: upper-bounds
  type: string
- container: ''
  name: uri
  type: string
- container: ''
  name: headers
  type: string
- container: ''
  name: sort-order
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: plan-task
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: value
  type: integer
- container: ''
  name: spec
  type: string
- container: ''
  name: field-id
  type: integer
- container: ''
  name: source-id
  type: integer
- container: ''
  name: transform
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: term
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: accessToken
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: issuedTokenType
  type: string
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: next-page-token
  type: string
- container: set
  name: namespaces
  type: string
- container: ''
  name: snapshot-id
  type: integer
- container: ''
  name: statistics-path
  type: string
- container: ''
  name: file-size-in-bytes
  type: integer
- container: ''
  name: file-footer-size-in-bytes
  type: integer
- container: set
  name: blob-metadata
  type: string
- container: ''
  name: metadata-location
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: config
  type: reference
- container: set
  name: storage-credentials
  type: string
- container: set
  name: keys
  type: string
- container: ''
  name: updates
  type: reference
- container: ''
  name: grantType
  type: string
- container: ''
  name: requestedTokenType
  type: string
- container: ''
  name: subjectToken
  type: string
- container: ''
  name: subjectTokenType
  type: string
- container: ''
  name: actorToken
  type: string
- container: ''
  name: actorTokenType
  type: string
- container: ''
  name: metadata-file
  type: string
- container: ''
  name: default-spec-id
  type: integer
- container: ''
  name: overrides
  type: reference
- container: ''
  name: defaults
  type: reference
- container: set
  name: endpoints
  type: string
- container: ''
  name: idempotency-key-lifetime
  type: duration
- container: ''
  name: status
  type: string
- container: ''
  name: plan-id
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: max-ref-age-ms
  type: integer
- container: ''
  name: max-snapshot-age-ms
  type: integer
- container: ''
  name: min-snapshots-to-keep
  type: integer
- container: ''
  name: ref
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: view-version
  type: string
- container: ''
  name: order-id
  type: integer
- container: set
  name: fields
  type: string
- container: ''
  name: last-column-id
  type: integer
- container: ''
  name: file-path
  type: string
- container: ''
  name: file-format
  type: string
- container: ''
  name: spec-id
  type: integer
- container: set
  name: partition
  type: string
- container: ''
  name: record-count
  type: integer
- container: ''
  name: key-metadata
  type: string
- container: set
  name: split-offsets
  type: integer
- container: ''
  name: sort-order-id
  type: integer
- container: ''
  name: parent-snapshot-id
  type: integer
- container: ''
  name: sequence-number
  type: integer
- container: ''
  name: manifest-list
  type: string
- container: ''
  name: added-rows
  type: integer
- container: ''
  name: summary
  type: reference
- container: ''
  name: operation
  type: string
- container: ''
  name: schema-id
  type: integer
- container: set
  name: updated
  type: string
- container: set
  name: removed
  type: string
- container: set
  name: missing
  type: string
- container: ''
  name: ref-name
  type: string
- container: set
  name: removals
  type: string
- container: ''
  name: identifier
  type: string
- container: set
  name: requirements
  type: string
- container: set
  name: select
  type: string
- container: ''
  name: filter
  type: string
- container: ''
  name: min-rows-requested
  type: integer
- container: ''
  name: case-sensitive
  type: boolean
- container: ''
  name: use-snapshot-schema
  type: boolean
- container: ''
  name: start-snapshot-id
  type: integer
- container: ''
  name: end-snapshot-id
  type: integer
- container: set
  name: stats-fields
  type: string
- container: ''
  name: default-sort-order-id
  type: integer
- container: ''
  name: report-type
  type: string
- container: ''
  name: table-name
  type: string
- container: set
  name: projected-field-ids
  type: integer
- container: set
  name: projected-field-names
  type: string
- container: ''
  name: metrics
  type: string
- container: ''
  name: left
  type: string
- container: ''
  name: right
  type: string
- container: ''
  name: current-schema-id
  type: integer
- container: ''
  name: overwrite
  type: boolean
- container: ''
  name: statistics
  type: string
- container: set
  name: snapshot-ids
  type: integer
- container: ''
  name: data-file
  type: string
- container: set
  name: delete-file-references
  type: integer
- container: ''
  name: residual-filter
  type: string
- container: set
  name: delete-files
  type: string
- container: set
  name: file-scan-tasks
  type: string
- container: set
  name: plan-tasks
  type: string
- container: ''
  name: partition-spec
  type: string
- container: ''
  name: write-order
  type: string
- container: ''
  name: stage-create
  type: boolean
- container: set
  name: representations
  type: string
- container: ''
  name: default-catalog
  type: string
- container: ''
  name: default-namespace
  type: string
- container: set
  name: equality-ids
  type: integer
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: destination
  type: string
- container: set
  name: identifiers
  type: string
- container: ''
  name: last-assigned-field-id
  type: integer
- container: ''
  name: encryption-key
  type: string
- container: ''
  name: sql
  type: string
- container: ''
  name: dialect
  type: string
- container: ''
  name: format-version
  type: integer
- container: ''
  name: table-uuid
  type: string
- container: ''
  name: last-updated-ms
  type: integer
- container: ''
  name: next-row-id
  type: integer
- container: set
  name: schemas
  type: string
- container: set
  name: partition-specs
  type: string
- container: ''
  name: last-partition-id
  type: integer
- container: set
  name: sort-orders
  type: string
- container: set
  name: encryption-keys
  type: string
- container: set
  name: snapshots
  type: string
- container: ''
  name: refs
  type: string
- container: ''
  name: current-snapshot-id
  type: integer
- container: ''
  name: last-sequence-number
  type: integer
- container: ''
  name: snapshot-log
  type: string
- container: ''
  name: metadata-log
  type: string
- container: set
  name: partition-statistics
  type: string
- container: ''
  name: snapshot
  type: string
- container: set
  name: spec-ids
  type: integer
- container: ''
  name: prefix
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: null-order
  type: string
- container: ''
  name: view-uuid
  type: string
- container: ''
  name: current-version-id
  type: integer
- container: set
  name: versions
  type: string
- container: set
  name: version-log
  type: string
- container: ''
  name: last-assigned-partition-id
  type: integer
- container: set
  name: table-changes
  type: string
- container: ''
  name: child
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: errorDescription
  type: string
- container: ''
  name: errorUri
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: required
  type: boolean
- container: ''
  name: doc
  type: string
- container: ''
  name: initial-default
  type: string
- container: ''
  name: write-default
  type: string
- container: ''
  name: content-offset
  type: integer
- container: ''
  name: content-size-in-bytes
  type: integer
- container: ''
  name: time-unit
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: total-duration
  type: integer
- container: ''
  name: view-version-id
  type: integer
- container: ''
  name: element-id
  type: integer
- container: ''
  name: element
  type: string
- container: ''
  name: element-required
  type: boolean
- container: ''
  name: key
  type: string
- container: ''
  name: value-id
  type: integer
- container: ''
  name: value-required
  type: boolean
property_count: 190
provider_name: Apache Iceberg
provider_slug: apache-iceberg
slug: apache-iceberg-rest-catalog-open-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"iceberg\": \"https://iceberg.apache.org/schema/\",\n    \"schema\": {\n      \"@id\": \"iceberg:schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EncryptedKey\": \"iceberg:EncryptedKey\",\n    \"ViewHistoryEntry\": \"iceberg:ViewHistoryEntry\",\n    \"RemoveSchemasUpdate\": \"iceberg:RemoveSchemasUpdate\",\n    \"DataFile\": \"iceberg:DataFile\",\n    \"BaseUpdate\": \"iceberg:BaseUpdate\",\n    \"RemoteSignResult\": \"iceberg:RemoteSignResult\",\n    \"AddSortOrderUpdate\": \"iceberg:AddSortOrderUpdate\",\n    \"RemoteSignRequest\": \"iceberg:RemoteSignRequest\",\n    \"FetchScanTasksRequest\": \"iceberg:FetchScanTasksRequest\",\n    \"CounterResult\": \"iceberg:CounterResult\",\n    \"AddPartitionSpecUpdate\": \"iceberg:AddPartitionSpecUpdate\",\n    \"PartitionField\": \"iceberg:PartitionField\",\n    \"SetExpression\"\
  : \"iceberg:SetExpression\",\n    \"OAuthTokenResponse\": \"iceberg:OAuthTokenResponse\",\n    \"ListNamespacesResponse\": \"iceberg:ListNamespacesResponse\",\n    \"StatisticsFile\": \"iceberg:StatisticsFile\",\n    \"LoadTableResult\": \"iceberg:LoadTableResult\",\n    \"TableRequirement\": \"iceberg:TableRequirement\",\n    \"ValueMap\": \"iceberg:ValueMap\",\n    \"SetPropertiesUpdate\": \"iceberg:SetPropertiesUpdate\",\n    \"OAuthTokenExchangeRequest\": \"iceberg:OAuthTokenExchangeRequest\",\n    \"AssertDefaultSpecId\": \"iceberg:AssertDefaultSpecId\",\n    \"CatalogConfig\": \"iceberg:CatalogConfig\",\n    \"AsyncPlanningResult\": \"iceberg:AsyncPlanningResult\",\n    \"CreateNamespaceRequest\": \"iceberg:CreateNamespaceRequest\",\n    \"AssertTableUUID\": \"iceberg:AssertTableUUID\",\n    \"SnapshotReference\": \"iceberg:SnapshotReference\",\n    \"AssertRefSnapshotId\": \"iceberg:AssertRefSnapshotId\",\n    \"CreateViewRequest\": \"iceberg:CreateViewRequest\",\n    \"TrueExpression\"\
  : \"iceberg:TrueExpression\",\n    \"SortOrder\": \"iceberg:SortOrder\",\n    \"RegisterViewRequest\": \"iceberg:RegisterViewRequest\",\n    \"AddSchemaUpdate\": \"iceberg:AddSchemaUpdate\",\n    \"ContentFile\": \"iceberg:ContentFile\",\n    \"SnapshotReferences\": \"iceberg:SnapshotReferences\",\n    \"MultiValuedMap\": \"iceberg:MultiValuedMap\",\n    \"Snapshot\": \"iceberg:Snapshot\",\n    \"BlobMetadata\": \"iceberg:BlobMetadata\",\n    \"UpdateNamespacePropertiesResponse\": \"iceberg:UpdateNamespacePropertiesResponse\",\n    \"CommitTableResponse\": \"iceberg:CommitTableResponse\",\n    \"PartitionStatisticsFile\": \"iceberg:PartitionStatisticsFile\",\n    \"StructType\": \"iceberg:StructType\",\n    \"RemoveSnapshotRefUpdate\": \"iceberg:RemoveSnapshotRefUpdate\",\n    \"UpdateNamespacePropertiesRequest\": \"iceberg:UpdateNamespacePropertiesRequest\",\n    \"CommitTableRequest\": \"iceberg:CommitTableRequest\",\n    \"PlanTableScanRequest\": \"iceberg:PlanTableScanRequest\",\n\
  \    \"UnaryExpression\": \"iceberg:UnaryExpression\",\n    \"AssertDefaultSortOrderId\": \"iceberg:AssertDefaultSortOrderId\",\n    \"ReportMetricsRequest\": \"iceberg:ReportMetricsRequest\",\n    \"FailedPlanningResult\": \"iceberg:FailedPlanningResult\",\n    \"AssertViewUUID\": \"iceberg:AssertViewUUID\",\n    \"FetchPlanningResult\": \"iceberg:FetchPlanningResult\",\n    \"ScanReport\": \"iceberg:ScanReport\",\n    \"AndOrExpression\": \"iceberg:AndOrExpression\",\n    \"ViewRequirement\": \"iceberg:ViewRequirement\",\n    \"AssertCurrentSchemaId\": \"iceberg:AssertCurrentSchemaId\",\n    \"SetCurrentSchemaUpdate\": \"iceberg:SetCurrentSchemaUpdate\",\n    \"RegisterTableRequest\": \"iceberg:RegisterTableRequest\",\n    \"AssignUUIDUpdate\": \"iceberg:AssignUUIDUpdate\",\n    \"CommitReport\": \"iceberg:CommitReport\",\n    \"LoadCredentialsResponse\": \"iceberg:LoadCredentialsResponse\",\n    \"SetStatisticsUpdate\": \"iceberg:SetStatisticsUpdate\",\n    \"FetchScanTasksResult\"\
  : \"iceberg:FetchScanTasksResult\",\n    \"AssertCreate\": \"iceberg:AssertCreate\",\n    \"SetLocationUpdate\": \"iceberg:SetLocationUpdate\",\n    \"RemoveSnapshotsUpdate\": \"iceberg:RemoveSnapshotsUpdate\",\n    \"FileScanTask\": \"iceberg:FileScanTask\",\n    \"ScanTasks\": \"iceberg:ScanTasks\",\n    \"Metrics\": \"iceberg:Metrics\",\n    \"CreateTableRequest\": \"iceberg:CreateTableRequest\",\n    \"CompletedPlanningResult\": \"iceberg:CompletedPlanningResult\",\n    \"LoadViewResult\": \"iceberg:LoadViewResult\",\n    \"ViewVersion\": \"iceberg:ViewVersion\",\n    \"EqualityDeleteFile\": \"iceberg:EqualityDeleteFile\",\n    \"RemoveEncryptionKeyUpdate\": \"iceberg:RemoveEncryptionKeyUpdate\",\n    \"RemoveStatisticsUpdate\": \"iceberg:RemoveStatisticsUpdate\",\n    \"OAuthClientCredentialsRequest\": \"iceberg:OAuthClientCredentialsRequest\",\n    \"AddViewVersionUpdate\": \"iceberg:AddViewVersionUpdate\",\n    \"RenameTableRequest\": \"iceberg:RenameTableRequest\",\n    \"CompletedPlanningWithIDResult\"\
  : \"iceberg:CompletedPlanningWithIDResult\",\n    \"ListTablesResponse\": \"iceberg:ListTablesResponse\",\n    \"AssertLastAssignedFieldId\": \"iceberg:AssertLastAssignedFieldId\",\n    \"PartitionSpec\": \"iceberg:PartitionSpec\",\n    \"AddEncryptionKeyUpdate\": \"iceberg:AddEncryptionKeyUpdate\",\n    \"TransformTerm\": \"iceberg:TransformTerm\",\n    \"SQLViewRepresentation\": \"iceberg:SQLViewRepresentation\",\n    \"CommitViewRequest\": \"iceberg:CommitViewRequest\",\n    \"RemovePartitionStatisticsUpdate\": \"iceberg:RemovePartitionStatisticsUpdate\",\n    \"TableMetadata\": \"iceberg:TableMetadata\",\n    \"AddSnapshotUpdate\": \"iceberg:AddSnapshotUpdate\",\n    \"RemovePartitionSpecsUpdate\": \"iceberg:RemovePartitionSpecsUpdate\",\n    \"SetDefaultSpecUpdate\": \"iceberg:SetDefaultSpecUpdate\",\n    \"SetSnapshotRefUpdate\": \"iceberg:SetSnapshotRefUpdate\",\n    \"StorageCredential\": \"iceberg:StorageCredential\",\n    \"SortField\": \"iceberg:SortField\",\n    \"ViewMetadata\"\
  : \"iceberg:ViewMetadata\",\n    \"AssertLastAssignedPartitionId\": \"iceberg:AssertLastAssignedPartitionId\",\n    \"CommitTransactionRequest\": \"iceberg:CommitTransactionRequest\",\n    \"NotExpression\": \"iceberg:NotExpression\",\n    \"CountMap\": \"iceberg:CountMap\",\n    \"SetPartitionStatisticsUpdate\": \"iceberg:SetPartitionStatisticsUpdate\",\n    \"OAuthError\": \"iceberg:OAuthError\",\n    \"StructField\": \"iceberg:StructField\",\n    \"FalseExpression\": \"iceberg:FalseExpression\",\n    \"PositionDeleteFile\": \"iceberg:PositionDeleteFile\",\n    \"TimerResult\": \"iceberg:TimerResult\",\n    \"SetCurrentViewVersionUpdate\": \"iceberg:SetCurrentViewVersionUpdate\",\n    \"SetDefaultSortOrderUpdate\": \"iceberg:SetDefaultSortOrderUpdate\",\n    \"PlanTableScanResult\": \"iceberg:PlanTableScanResult\",\n    \"GetNamespaceResponse\": \"iceberg:GetNamespaceResponse\",\n    \"EmptyPlanningResult\": \"iceberg:EmptyPlanningResult\",\n    \"UpgradeFormatVersionUpdate\": \"iceberg:UpgradeFormatVersionUpdate\"\
  ,\n    \"ListType\": \"iceberg:ListType\",\n    \"RemovePropertiesUpdate\": \"iceberg:RemovePropertiesUpdate\",\n    \"LiteralExpression\": \"iceberg:LiteralExpression\",\n    \"CreateNamespaceResponse\": \"iceberg:CreateNamespaceResponse\",\n    \"TableIdentifier\": \"iceberg:TableIdentifier\",\n    \"MapType\": \"iceberg:MapType\",\n    \"key-id\": {\n      \"@id\": \"iceberg:key-id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encrypted-key-metadata\": {\n      \"@id\": \"iceberg:encrypted-key-metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encrypted-by-id\": {\n      \"@id\": \"iceberg:encrypted-by-id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"iceberg:properties\",\n      \"@type\": \"@id\"\n    },\n    \"version-id\": {\n      \"@id\": \"iceberg:version-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp-ms\": {\n      \"@id\": \"iceberg:timestamp-ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"action\"\
  : {\n      \"@id\": \"iceberg:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schema-ids\": {\n      \"@id\": \"iceberg:schema-ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"content\": {\n      \"@id\": \"iceberg:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"first-row-id\": {\n      \"@id\": \"iceberg:first-row-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"column-sizes\": {\n      \"@id\": \"iceberg:column-sizes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value-counts\": {\n      \"@id\": \"iceberg:value-counts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"null-value-counts\": {\n      \"@id\": \"iceberg:null-value-counts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nan-value-counts\": {\n      \"@id\": \"iceberg:nan-value-counts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lower-bounds\": {\n      \"@id\": \"iceberg:lower-bounds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upper-bounds\"\
  : {\n      \"@id\": \"iceberg:upper-bounds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"iceberg:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"iceberg:headers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sort-order\": {\n      \"@id\": \"iceberg:sort-order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"iceberg:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n      \"@id\": \"iceberg:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"iceberg:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"iceberg:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan-task\": {\n      \"@id\": \"iceberg:plan-task\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"iceberg:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"iceberg:value\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"spec\": {\n      \"@id\": \"iceberg:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"field-id\": {\n      \"@id\": \"iceberg:field-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"source-id\": {\n      \"@id\": \"iceberg:source-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"transform\": {\n      \"@id\": \"iceberg:transform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"iceberg:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"term\": {\n      \"@id\": \"iceberg:term\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"iceberg:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessToken\": {\n      \"@id\": \"iceberg:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"iceberg:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"expiresIn\": {\n      \"@id\": \"iceberg:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"issuedTokenType\": {\n      \"@id\": \"iceberg:issued_token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"iceberg:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"iceberg:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next-page-token\": {\n      \"@id\": \"iceberg:next-page-token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaces\": {\n      \"@id\": \"iceberg:namespaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshot-id\": {\n      \"@id\": \"iceberg:snapshot-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"statistics-path\": {\n      \"@id\": \"iceberg:statistics-path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file-size-in-bytes\": {\n      \"@id\": \"iceberg:file-size-in-bytes\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"file-footer-size-in-bytes\": {\n      \"@id\": \"iceberg:file-footer-size-in-bytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"blob-metadata\": {\n      \"@id\": \"iceberg:blob-metadata\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata-location\": {\n      \"@id\": \"iceberg:metadata-location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"iceberg:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"iceberg:config\",\n      \"@type\": \"@id\"\n    },\n    \"storage-credentials\": {\n      \"@id\": \"iceberg:storage-credentials\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keys\": {\n      \"@id\": \"iceberg:keys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updates\": {\n      \"@id\": \"iceberg:updates\",\n      \"@type\": \"@id\"\n    },\n    \"grantType\": {\n      \"@id\"\
  : \"iceberg:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedTokenType\": {\n      \"@id\": \"iceberg:requested_token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectToken\": {\n      \"@id\": \"iceberg:subject_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectTokenType\": {\n      \"@id\": \"iceberg:subject_token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorToken\": {\n      \"@id\": \"iceberg:actor_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorTokenType\": {\n      \"@id\": \"iceberg:actor_token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata-file\": {\n      \"@id\": \"iceberg:metadata-file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default-spec-id\": {\n      \"@id\": \"iceberg:default-spec-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"overrides\": {\n      \"@id\": \"iceberg:overrides\",\n      \"@type\": \"@id\"\n    },\n    \"defaults\": {\n      \"@id\": \"iceberg:defaults\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"endpoints\": {\n      \"@id\": \"iceberg:endpoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idempotency-key-lifetime\": {\n      \"@id\": \"iceberg:idempotency-key-lifetime\",\n      \"@type\": \"xsd:duration\"\n    },\n    \"status\": {\n      \"@id\": \"iceberg:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan-id\": {\n      \"@id\": \"iceberg:plan-id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"iceberg:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"iceberg:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"max-ref-age-ms\": {\n      \"@id\": \"iceberg:max-ref-age-ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max-snapshot-age-ms\": {\n      \"@id\": \"iceberg:max-snapshot-age-ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"min-snapshots-to-keep\": {\n      \"@id\": \"iceberg:min-snapshots-to-keep\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"ref\": {\n      \"@id\": \"iceberg:ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"iceberg:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"view-version\": {\n      \"@id\": \"iceberg:view-version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order-id\": {\n      \"@id\": \"iceberg:order-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fields\": {\n      \"@id\": \"iceberg:fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last-column-id\": {\n      \"@id\": \"iceberg:last-column-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"file-path\": {\n      \"@id\": \"iceberg:file-path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file-format\": {\n      \"@id\": \"iceberg:file-format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec-id\": {\n      \"@id\": \"iceberg:spec-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  partition\": {\n      \"@id\": \"iceberg:partition\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"record-count\": {\n      \"@id\": \"iceberg:record-count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"key-metadata\": {\n      \"@id\": \"iceberg:key-metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"split-offsets\": {\n      \"@id\": \"iceberg:split-offsets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sort-order-id\": {\n      \"@id\": \"iceberg:sort-order-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parent-snapshot-id\": {\n      \"@id\": \"iceberg:parent-snapshot-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sequence-number\": {\n      \"@id\": \"iceberg:sequence-number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"manifest-list\": {\n      \"@id\": \"iceberg:manifest-list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"added-rows\": {\n      \"@id\": \"iceberg:added-rows\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"summary\": {\n      \"@id\": \"iceberg:summary\",\n      \"@type\": \"@id\"\n    },\n    \"operation\": {\n      \"@id\": \"iceberg:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schema-id\": {\n      \"@id\": \"iceberg:schema-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updated\": {\n      \"@id\": \"iceberg:updated\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"removed\": {\n      \"@id\": \"iceberg:removed\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"missing\": {\n      \"@id\": \"iceberg:missing\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ref-name\": {\n      \"@id\": \"iceberg:ref-name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"removals\": {\n      \"@id\": \"iceberg:removals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\"\
  : \"iceberg:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requirements\": {\n      \"@id\": \"iceberg:requirements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"select\": {\n      \"@id\": \"iceberg:select\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"iceberg:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"min-rows-requested\": {\n      \"@id\": \"iceberg:min-rows-requested\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"case-sensitive\": {\n      \"@id\": \"iceberg:case-sensitive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"use-snapshot-schema\": {\n      \"@id\": \"iceberg:use-snapshot-schema\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"start-snapshot-id\": {\n      \"@id\": \"iceberg:start-snapshot-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"end-snapshot-id\": {\n      \"@id\": \"iceberg:end-snapshot-id\",\n      \"@type\":\
  \ \"xsd:integer\"\n    },\n    \"stats-fields\": {\n      \"@id\": \"iceberg:stats-fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default-sort-order-id\": {\n      \"@id\": \"iceberg:default-sort-order-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"report-type\": {\n      \"@id\": \"iceberg:report-type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table-name\": {\n      \"@id\": \"iceberg:table-name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projected-field-ids\": {\n      \"@id\": \"iceberg:projected-field-ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projected-field-names\": {\n      \"@id\": \"iceberg:projected-field-names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"iceberg:metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"left\": {\n      \"@id\": \"iceberg:left\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"right\": {\n      \"@id\": \"iceberg:right\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current-schema-id\": {\n      \"@id\": \"iceberg:current-schema-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"overwrite\": {\n      \"@id\": \"iceberg:overwrite\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"statistics\": {\n      \"@id\": \"iceberg:statistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshot-ids\": {\n      \"@id\": \"iceberg:snapshot-ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data-file\": {\n      \"@id\": \"iceberg:data-file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delete-file-references\": {\n      \"@id\": \"iceberg:delete-file-references\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"residual-filter\": {\n      \"@id\": \"iceberg:residual-filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delete-files\": {\n      \"@id\": \"iceberg:delete-files\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file-scan-tasks\": {\n      \"@id\": \"iceberg:file-scan-tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan-tasks\": {\n      \"@id\": \"iceberg:plan-tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partition-spec\": {\n      \"@id\": \"iceberg:partition-spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"write-order\": {\n      \"@id\": \"iceberg:write-order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stage-create\": {\n      \"@id\": \"iceberg:stage-create\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"representations\": {\n      \"@id\": \"iceberg:representations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default-catalog\": {\n      \"@id\": \"iceberg:default-catalog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default-namespace\": {\n      \"@id\": \"iceberg:default-namespace\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"equality-ids\": {\n      \"@id\": \"iceberg:equality-ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clientId\": {\n      \"@id\": \"iceberg:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"iceberg:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"iceberg:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"iceberg:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifiers\": {\n      \"@id\": \"iceberg:identifiers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last-assigned-field-id\": {\n      \"@id\": \"iceberg:last-assigned-field-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"encryption-key\": {\n      \"@id\": \"iceberg:encryption-key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sql\": {\n     \
  \ \"@id\": \"iceberg:sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dialect\": {\n      \"@id\": \"iceberg:dialect\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format-version\": {\n      \"@id\": \"iceberg:format-version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"table-uuid\": {\n      \"@id\": \"iceberg:table-uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last-updated-ms\": {\n      \"@id\": \"iceberg:last-updated-ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"next-row-id\": {\n      \"@id\": \"iceberg:next-row-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"schemas\": {\n      \"@id\": \"iceberg:schemas\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partition-specs\": {\n      \"@id\": \"iceberg:partition-specs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last-partition-id\": {\n      \"@id\": \"iceberg:last-partition-id\",\n      \"@type\": \"xsd:integer\"\n   \
  \ },\n    \"sort-orders\": {\n      \"@id\": \"iceberg:sort-orders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryption-keys\": {\n      \"@id\": \"iceberg:encryption-keys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshots\": {\n      \"@id\": \"iceberg:snapshots\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refs\": {\n      \"@id\": \"iceberg:refs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current-snapshot-id\": {\n      \"@id\": \"iceberg:current-snapshot-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"last-sequence-number\": {\n      \"@id\": \"iceberg:last-sequence-number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"snapshot-log\": {\n      \"@id\": \"iceberg:snapshot-log\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata-log\": {\n      \"@id\": \"iceberg:metadata-log\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partition-statistics\"\
  : {\n      \"@id\": \"iceberg:partition-statistics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshot\": {\n      \"@id\": \"iceberg:snapshot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec-ids\": {\n      \"@id\": \"iceberg:spec-ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"prefix\": {\n      \"@id\": \"iceberg:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"iceberg:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"null-order\": {\n      \"@id\": \"iceberg:null-order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"view-uuid\": {\n      \"@id\": \"iceberg:view-uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current-version-id\": {\n      \"@id\": \"iceberg:current-version-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"versions\": {\n      \"@id\": \"iceberg:versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"version-log\": {\n      \"@id\": \"iceberg:version-log\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last-assigned-partition-id\": {\n      \"@id\": \"iceberg:last-assigned-partition-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"table-changes\": {\n      \"@id\": \"iceberg:table-changes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"child\": {\n      \"@id\": \"iceberg:child\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"iceberg:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorDescription\": {\n      \"@id\": \"iceberg:error_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorUri\": {\n      \"@id\": \"iceberg:error_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"iceberg:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"required\": {\n      \"@id\": \"iceberg:required\",\n    \
  \  \"@type\": \"xsd:boolean\"\n    },\n    \"doc\": {\n      \"@id\": \"iceberg:doc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initial-default\": {\n      \"@id\": \"iceberg:initial-default\",\n      \"@type\": \"xsd:string\"\n    },\n    \"write-default\": {\n      \"@id\": \"iceberg:write-default\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content-offset\": {\n      \"@id\": \"iceberg:content-offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"content-size-in-bytes\": {\n      \"@id\": \"iceberg:content-size-in-bytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"time-unit\": {\n      \"@id\": \"iceberg:time-unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"iceberg:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total-duration\": {\n      \"@id\": \"iceberg:total-duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"view-version-id\": {\n      \"@id\": \"iceberg:view-version-id\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"element-id\": {\n      \"@id\": \"iceberg:element-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"element\": {\n      \"@id\": \"iceberg:element\",\n      \"@type\": \"xsd:string\"\n    },\n    \"element-required\": {\n      \"@id\": \"iceberg:element-required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"key\": {\n      \"@id\": \"iceberg:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value-id\": {\n      \"@id\": \"iceberg:value-id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"value-required\": {\n      \"@id\": \"iceberg:value-required\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/json-ld/apache-iceberg-rest-catalog-open-api-context.jsonld
tags:
- ACID
- Analytics
- Apache
- Data Lake
- Lakehouse
- Open Source
- Table Format
- JSON-LD
- Linked Data
- Semantic Web
---
