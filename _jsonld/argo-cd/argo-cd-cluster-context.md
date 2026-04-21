---
class_count: 12
classes:
- clusterDexConfig
- clusterSettings
- clusterOIDCConfig
- clusterSettingsPluginsResponse
- clusterHelp
- clusterGoogleAnalyticsConfig
- clusterConnector
- clusterPlugin
- clusterClusterID
- clusterClusterResponse
- url
- name
context_file: json-ld/argo-cd-cluster-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-cluster-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Cluster from Argo CD.
layout: jsonld
name: Argo Cd Cluster Context
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
  name: connectors
  type: string
- container: set
  name: additionalUrls
  type: string
- container: ''
  name: appLabelKey
  type: string
- container: ''
  name: appsInAnyNamespaceEnabled
  type: boolean
- container: set
  name: configManagementPlugins
  type: string
- container: ''
  name: controllerNamespace
  type: string
- container: ''
  name: dexConfig
  type: string
- container: ''
  name: execEnabled
  type: boolean
- container: ''
  name: googleAnalytics
  type: string
- container: ''
  name: help
  type: string
- container: ''
  name: hydratorEnabled
  type: boolean
- container: ''
  name: impersonationEnabled
  type: boolean
- container: ''
  name: installationID
  type: string
- container: ''
  name: kustomizeOptions
  type: string
- container: set
  name: kustomizeVersions
  type: string
- container: ''
  name: oidcConfig
  type: string
- container: ''
  name: passwordPattern
  type: string
- container: set
  name: plugins
  type: string
- container: ''
  name: resourceOverrides
  type: reference
- container: ''
  name: statusBadgeEnabled
  type: boolean
- container: ''
  name: statusBadgeRootUrl
  type: string
- container: ''
  name: syncWithReplaceAllowed
  type: boolean
- container: ''
  name: trackingMethod
  type: string
- container: ''
  name: uiBannerContent
  type: string
- container: ''
  name: uiBannerPermanent
  type: boolean
- container: ''
  name: uiBannerPosition
  type: string
- container: ''
  name: uiBannerURL
  type: string
- container: ''
  name: uiCssURL
  type: string
- container: ''
  name: userLoginsDisabled
  type: boolean
- container: ''
  name: cliClientID
  type: string
- container: ''
  name: clientID
  type: string
- container: ''
  name: enablePKCEAuthentication
  type: boolean
- container: ''
  name: idTokenClaims
  type: reference
- container: ''
  name: issuer
  type: string
- container: set
  name: scopes
  type: string
- container: ''
  name: binaryUrls
  type: reference
- container: ''
  name: chatText
  type: string
- container: ''
  name: chatUrl
  type: string
- container: ''
  name: anonymizeUsers
  type: boolean
- container: ''
  name: trackingID
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
property_count: 42
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-cluster-context
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
