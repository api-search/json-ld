---
class_count: 24
classes:
- applicationApplicationSyncWindow
- applicationFileChunk
- applicationResourceActionParameters
- applicationOperationTerminateResponse
- applicationApplicationServerSideDiffResponse
- applicationApplicationResourceResponse
- applicationSyncOptions
- applicationApplicationPatchRequest
- applicationManagedResourcesResponse
- applicationApplicationManifestQueryWithFiles
- applicationApplicationResponse
- applicationApplicationSyncRequest
- applicationResourceActionRunRequestV2
- applicationApplicationManifestQueryWithFilesWrapper
- applicationApplicationRollbackRequest
- applicationResourceActionsListResponse
- applicationLinkInfo
- applicationLinksResponse
- applicationLogEntry
- applicationApplicationSyncWindowsResponse
- name
- version
- description
- url
context_file: json-ld/argo-cd-application-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-application-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Application from Argo CD.
layout: jsonld
name: Argo Cd Application Context
namespaces:
- prefix: argocd
  uri: https://argoproj.github.io/schema/argo-cd/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: duration
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: manualSync
  type: boolean
- container: ''
  name: schedule
  type: string
- container: ''
  name: chunk
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: modified
  type: boolean
- container: ''
  name: manifest
  type: string
- container: ''
  name: appNamespace
  type: string
- container: ''
  name: patch
  type: string
- container: ''
  name: patchType
  type: string
- container: ''
  name: project
  type: string
- container: ''
  name: checksum
  type: string
- container: ''
  name: dryRun
  type: boolean
- container: set
  name: infos
  type: string
- container: set
  name: manifests
  type: string
- container: ''
  name: prune
  type: boolean
- container: set
  name: resources
  type: string
- container: ''
  name: retryStrategy
  type: string
- container: ''
  name: revision
  type: string
- container: set
  name: revisions
  type: string
- container: set
  name: sourcePositions
  type: string
- container: ''
  name: strategy
  type: string
- container: ''
  name: syncOptions
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: namespace
  type: string
- container: set
  name: resourceActionParameters
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: id
  type: integer
- container: set
  name: actions
  type: string
- container: ''
  name: iconClass
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: last
  type: boolean
- container: ''
  name: podName
  type: string
- container: ''
  name: timeStamp
  type: string
- container: ''
  name: timeStampStr
  type: string
- container: set
  name: activeWindows
  type: string
- container: set
  name: assignedWindows
  type: string
- container: ''
  name: canSync
  type: boolean
property_count: 43
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-application-context
tags:
- Continuous Delivery
- Containers
- Deployment
- GitOps
- Kubernetes
- CNCF
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
