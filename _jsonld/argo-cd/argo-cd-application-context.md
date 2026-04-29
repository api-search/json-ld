---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
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
source_filename: argo-cd-application-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"applicationApplicationSyncWindow\": \"argocd:applicationApplicationSyncWindow\",\n    \"applicationFileChunk\": \"argocd:applicationFileChunk\",\n    \"applicationResourceActionParameters\": \"argocd:applicationResourceActionParameters\",\n    \"applicationOperationTerminateResponse\": \"argocd:applicationOperationTerminateResponse\",\n    \"applicationApplicationServerSideDiffResponse\": \"argocd:applicationApplicationServerSideDiffResponse\",\n    \"applicationApplicationResourceResponse\": \"argocd:applicationApplicationResourceResponse\",\n    \"applicationSyncOptions\": \"argocd:applicationSyncOptions\",\n    \"applicationApplicationPatchRequest\": \"argocd:applicationApplicationPatchRequest\",\n    \"applicationManagedResourcesResponse\"\
  : \"argocd:applicationManagedResourcesResponse\",\n    \"applicationApplicationManifestQueryWithFiles\": \"argocd:applicationApplicationManifestQueryWithFiles\",\n    \"applicationApplicationResponse\": \"argocd:applicationApplicationResponse\",\n    \"applicationApplicationSyncRequest\": \"argocd:applicationApplicationSyncRequest\",\n    \"applicationResourceActionRunRequestV2\": \"argocd:applicationResourceActionRunRequestV2\",\n    \"applicationApplicationManifestQueryWithFilesWrapper\": \"argocd:applicationApplicationManifestQueryWithFilesWrapper\",\n    \"applicationApplicationRollbackRequest\": \"argocd:applicationApplicationRollbackRequest\",\n    \"applicationResourceActionsListResponse\": \"argocd:applicationResourceActionsListResponse\",\n    \"applicationLinkInfo\": \"argocd:applicationLinkInfo\",\n    \"applicationLinksResponse\": \"argocd:applicationLinksResponse\",\n    \"applicationLogEntry\": \"argocd:applicationLogEntry\",\n    \"applicationApplicationSyncWindowsResponse\"\
  : \"argocd:applicationApplicationSyncWindowsResponse\",\n    \"duration\": {\n      \"@id\": \"argocd:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"argocd:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manualSync\": {\n      \"@id\": \"argocd:manualSync\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"schedule\": {\n      \"@id\": \"argocd:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chunk\": {\n      \"@id\": \"argocd:chunk\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"value\": {\n      \"@id\": \"argocd:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"argocd:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified\": {\n      \"@id\": \"argocd:modified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"manifest\": {\n      \"@id\": \"argocd:manifest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  appNamespace\": {\n      \"@id\": \"argocd:appNamespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patch\": {\n      \"@id\": \"argocd:patch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patchType\": {\n      \"@id\": \"argocd:patchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"argocd:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checksum\": {\n      \"@id\": \"argocd:checksum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dryRun\": {\n      \"@id\": \"argocd:dryRun\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"infos\": {\n      \"@id\": \"argocd:infos\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifests\": {\n      \"@id\": \"argocd:manifests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prune\": {\n      \"@id\": \"argocd:prune\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resources\": {\n      \"@id\": \"argocd:resources\",\n\
  \      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryStrategy\": {\n      \"@id\": \"argocd:retryStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"argocd:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisions\": {\n      \"@id\": \"argocd:revisions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePositions\": {\n      \"@id\": \"argocd:sourcePositions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strategy\": {\n      \"@id\": \"argocd:strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncOptions\": {\n      \"@id\": \"argocd:syncOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"argocd:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"argocd:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"argocd:namespace\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceActionParameters\": {\n      \"@id\": \"argocd:resourceActionParameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"argocd:resourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"query\": {\n      \"@id\": \"argocd:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"argocd:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"actions\": {\n      \"@id\": \"argocd:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"iconClass\": {\n      \"@id\": \"argocd:iconClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"argocd:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"content\": {\n      \"@id\": \"argocd:content\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"last\": {\n      \"@id\": \"argocd:last\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"podName\": {\n      \"@id\": \"argocd:podName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeStamp\": {\n      \"@id\": \"argocd:timeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeStampStr\": {\n      \"@id\": \"argocd:timeStampStr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeWindows\": {\n      \"@id\": \"argocd:activeWindows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedWindows\": {\n      \"@id\": \"argocd:assignedWindows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canSync\": {\n      \"@id\": \"argocd:canSync\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-application-context.jsonld
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
