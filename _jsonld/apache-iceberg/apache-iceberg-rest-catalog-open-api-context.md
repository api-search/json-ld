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
