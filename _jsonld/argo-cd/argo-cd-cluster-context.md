---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"clusterDexConfig\": \"argocd:clusterDexConfig\",\n    \"clusterSettings\": \"argocd:clusterSettings\",\n    \"clusterOIDCConfig\": \"argocd:clusterOIDCConfig\",\n    \"clusterSettingsPluginsResponse\": \"argocd:clusterSettingsPluginsResponse\",\n    \"clusterHelp\": \"argocd:clusterHelp\",\n    \"clusterGoogleAnalyticsConfig\": \"argocd:clusterGoogleAnalyticsConfig\",\n    \"clusterConnector\": \"argocd:clusterConnector\",\n    \"clusterPlugin\": \"argocd:clusterPlugin\",\n    \"clusterClusterID\": \"argocd:clusterClusterID\",\n    \"clusterClusterResponse\": \"argocd:clusterClusterResponse\",\n    \"connectors\": {\n      \"@id\": \"argocd:connectors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"additionalUrls\": {\n      \"@id\": \"argocd:additionalUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appLabelKey\": {\n      \"@id\": \"argocd:appLabelKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appsInAnyNamespaceEnabled\": {\n      \"@id\": \"argocd:appsInAnyNamespaceEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"configManagementPlugins\": {\n      \"@id\": \"argocd:configManagementPlugins\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controllerNamespace\": {\n      \"@id\": \"argocd:controllerNamespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dexConfig\": {\n      \"@id\": \"argocd:dexConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"execEnabled\": {\n      \"@id\": \"argocd:execEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"googleAnalytics\": {\n      \"@id\": \"argocd:googleAnalytics\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"help\": {\n      \"@id\": \"argocd:help\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hydratorEnabled\": {\n      \"@id\": \"argocd:hydratorEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"impersonationEnabled\": {\n      \"@id\": \"argocd:impersonationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"installationID\": {\n      \"@id\": \"argocd:installationID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kustomizeOptions\": {\n      \"@id\": \"argocd:kustomizeOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kustomizeVersions\": {\n      \"@id\": \"argocd:kustomizeVersions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oidcConfig\": {\n      \"@id\": \"argocd:oidcConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passwordPattern\": {\n      \"@id\": \"argocd:passwordPattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plugins\": {\n      \"@id\": \"argocd:plugins\",\n      \"@container\": \"\
  @set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceOverrides\": {\n      \"@id\": \"argocd:resourceOverrides\",\n      \"@type\": \"@id\"\n    },\n    \"statusBadgeEnabled\": {\n      \"@id\": \"argocd:statusBadgeEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"statusBadgeRootUrl\": {\n      \"@id\": \"argocd:statusBadgeRootUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncWithReplaceAllowed\": {\n      \"@id\": \"argocd:syncWithReplaceAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"trackingMethod\": {\n      \"@id\": \"argocd:trackingMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uiBannerContent\": {\n      \"@id\": \"argocd:uiBannerContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uiBannerPermanent\": {\n      \"@id\": \"argocd:uiBannerPermanent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"uiBannerPosition\": {\n      \"@id\": \"argocd:uiBannerPosition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uiBannerURL\"\
  : {\n      \"@id\": \"argocd:uiBannerURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uiCssURL\": {\n      \"@id\": \"argocd:uiCssURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"userLoginsDisabled\": {\n      \"@id\": \"argocd:userLoginsDisabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cliClientID\": {\n      \"@id\": \"argocd:cliClientID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientID\": {\n      \"@id\": \"argocd:clientID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enablePKCEAuthentication\": {\n      \"@id\": \"argocd:enablePKCEAuthentication\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"idTokenClaims\": {\n      \"@id\": \"argocd:idTokenClaims\",\n      \"@type\": \"@id\"\n    },\n    \"issuer\": {\n      \"@id\": \"argocd:issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"scopes\": {\n      \"@id\": \"argocd:scopes\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"binaryUrls\": {\n      \"@id\": \"argocd:binaryUrls\",\n      \"@type\": \"@id\"\n    },\n    \"chatText\": {\n      \"@id\": \"argocd:chatText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chatUrl\": {\n      \"@id\": \"argocd:chatUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"anonymizeUsers\": {\n      \"@id\": \"argocd:anonymizeUsers\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"trackingID\": {\n      \"@id\": \"argocd:trackingID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argocd:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"argocd:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-cluster-context.jsonld
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
