---
class_count: 15
classes:
- repositoryPluginAppSpec
- repositoryDirectoryAppSpec
- repositoryKustomizeAppSpec
- repositoryRefs
- repositoryHelmChart
- repositoryRepoResponse
- repositoryHelmAppSpec
- repositoryRepoAppDetailsResponse
- repositoryManifestResponse
- repositoryParameterAnnouncement
- repositoryRepoAppsResponse
- repositoryAppInfo
- repositoryHelmChartsResponse
- repositoryRepoAppDetailsQuery
- name
context_file: json-ld/argo-cd-repository-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-repository-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Repository from Argo CD.
layout: jsonld
name: Argo Cd Repository Context
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
- container: set
  name: parametersAnnouncement
  type: string
- container: set
  name: images
  type: string
- container: set
  name: branches
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: versions
  type: string
- container: set
  name: fileParameters
  type: string
- container: set
  name: parameters
  type: string
- container: set
  name: valueFiles
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: directory
  type: string
- container: ''
  name: helm
  type: string
- container: ''
  name: kustomize
  type: string
- container: ''
  name: plugin
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: commands
  type: string
- container: set
  name: manifests
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: server
  type: string
- container: ''
  name: sourceType
  type: string
- container: ''
  name: verifyResult
  type: string
- container: set
  name: array
  type: string
- container: ''
  name: collectionType
  type: string
- container: ''
  name: itemType
  type: string
- container: ''
  name: map
  type: reference
- container: ''
  name: required
  type: boolean
- container: ''
  name: string
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: tooltip
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: appName
  type: string
- container: ''
  name: appProject
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sourceIndex
  type: integer
- container: ''
  name: versionId
  type: integer
property_count: 36
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-repository-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"repositoryPluginAppSpec\": \"argocd:repositoryPluginAppSpec\",\n    \"repositoryDirectoryAppSpec\": \"argocd:repositoryDirectoryAppSpec\",\n    \"repositoryKustomizeAppSpec\": \"argocd:repositoryKustomizeAppSpec\",\n    \"repositoryRefs\": \"argocd:repositoryRefs\",\n    \"repositoryHelmChart\": \"argocd:repositoryHelmChart\",\n    \"repositoryRepoResponse\": \"argocd:repositoryRepoResponse\",\n    \"repositoryHelmAppSpec\": \"argocd:repositoryHelmAppSpec\",\n    \"repositoryRepoAppDetailsResponse\": \"argocd:repositoryRepoAppDetailsResponse\",\n    \"repositoryManifestResponse\": \"argocd:repositoryManifestResponse\",\n    \"repositoryParameterAnnouncement\": \"argocd:repositoryParameterAnnouncement\",\n    \"repositoryRepoAppsResponse\"\
  : \"argocd:repositoryRepoAppsResponse\",\n    \"repositoryAppInfo\": \"argocd:repositoryAppInfo\",\n    \"repositoryHelmChartsResponse\": \"argocd:repositoryHelmChartsResponse\",\n    \"repositoryRepoAppDetailsQuery\": \"argocd:repositoryRepoAppDetailsQuery\",\n    \"parametersAnnouncement\": {\n      \"@id\": \"argocd:parametersAnnouncement\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"argocd:images\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branches\": {\n      \"@id\": \"argocd:branches\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"argocd:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"versions\": {\n      \"@id\": \"argocd:versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileParameters\": {\n  \
  \    \"@id\": \"argocd:fileParameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"argocd:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueFiles\": {\n      \"@id\": \"argocd:valueFiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"argocd:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directory\": {\n      \"@id\": \"argocd:directory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"helm\": {\n      \"@id\": \"argocd:helm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kustomize\": {\n      \"@id\": \"argocd:kustomize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plugin\": {\n      \"@id\": \"argocd:plugin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argocd:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commands\": {\n      \"@id\": \"\
  argocd:commands\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifests\": {\n      \"@id\": \"argocd:manifests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"argocd:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"argocd:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"server\": {\n      \"@id\": \"argocd:server\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceType\": {\n      \"@id\": \"argocd:sourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verifyResult\": {\n      \"@id\": \"argocd:verifyResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"array\": {\n      \"@id\": \"argocd:array\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collectionType\": {\n      \"@id\": \"argocd:collectionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemType\": {\n      \"\
  @id\": \"argocd:itemType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"map\": {\n      \"@id\": \"argocd:map\",\n      \"@type\": \"@id\"\n    },\n    \"required\": {\n      \"@id\": \"argocd:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"string\": {\n      \"@id\": \"argocd:string\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"argocd:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tooltip\": {\n      \"@id\": \"argocd:tooltip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"argocd:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"argocd:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appName\": {\n      \"@id\": \"argocd:appName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appProject\": {\n      \"@id\": \"argocd:appProject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"argocd:source\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceIndex\": {\n      \"@id\": \"argocd:sourceIndex\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"versionId\": {\n      \"@id\": \"argocd:versionId\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-repository-context.jsonld
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
