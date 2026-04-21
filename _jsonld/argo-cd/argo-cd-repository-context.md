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
