---
api_specs:
- filename: swagger.json
  format: json
  label: OpenShift REST API
  slug: openshift-rest-api
  spec_type: OpenAPI
  url: https://api.openshift.com/api/swagger.json
class_count: 0
classes: []
context_file: json-ld/openshift-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/json-ld/openshift-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openshift from OpenShift.
layout: jsonld
name: Openshift Context
namespaces:
- prefix: openshift
  uri: https://docs.openshift.com/ns/
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Route
  type: ''
- container: ''
  name: RouteTargetReference
  type: ''
- container: ''
  name: TLSConfig
  type: ''
- container: ''
  name: Build
  type: ''
- container: ''
  name: BuildConfig
  type: ''
- container: ''
  name: BuildSource
  type: ''
- container: ''
  name: BuildStrategy
  type: ''
- container: ''
  name: BuildStatus
  type: ''
- container: ''
  name: DeploymentConfig
  type: ''
- container: ''
  name: DeploymentStrategy
  type: ''
- container: ''
  name: DeploymentConfigStatus
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: ProjectRequest
  type: ''
- container: ''
  name: ObjectMeta
  type: ''
- container: ''
  name: Container
  type: ''
- container: ''
  name: Service
  type: ''
property_count: 16
provider_name: OpenShift
provider_slug: openshift
slug: openshift-context
source_filename: openshift-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"openshift\": \"https://docs.openshift.com/ns/\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Route\": {\n      \"@id\": \"openshift:Route\",\n      \"@context\": {\n        \"host\": \"schema:url\",\n        \"path\": \"openshift:routePath\",\n        \"subdomain\": \"openshift:subdomain\",\n        \"to\": {\n          \"@id\": \"openshift:routeTarget\",\n          \"@type\": \"@id\"\n        },\n        \"alternateBackends\": {\n          \"@id\": \"openshift:alternateBackends\",\n          \"@container\": \"@set\"\n        },\n        \"port\": \"openshift:routePort\",\n        \"tls\": \"openshift:tlsConfig\",\n        \"wildcardPolicy\": \"openshift:wildcardPolicy\",\n        \"status\": \"openshift:routeStatus\"\n      }\n    },\n\n    \"RouteTargetReference\"\
  : {\n      \"@id\": \"openshift:RouteTargetReference\",\n      \"@context\": {\n        \"kind\": \"openshift:targetKind\",\n        \"name\": \"schema:name\",\n        \"weight\": \"openshift:trafficWeight\"\n      }\n    },\n\n    \"TLSConfig\": {\n      \"@id\": \"openshift:TLSConfig\",\n      \"@context\": {\n        \"termination\": \"openshift:tlsTermination\",\n        \"certificate\": \"openshift:tlsCertificate\",\n        \"key\": \"openshift:tlsKey\",\n        \"caCertificate\": \"openshift:caCertificate\",\n        \"destinationCACertificate\": \"openshift:destinationCACertificate\",\n        \"insecureEdgeTerminationPolicy\": \"openshift:insecureEdgeTerminationPolicy\"\n      }\n    },\n\n    \"Build\": {\n      \"@id\": \"openshift:Build\",\n      \"@context\": {\n        \"source\": \"openshift:buildSource\",\n        \"strategy\": \"openshift:buildStrategy\",\n        \"output\": \"openshift:buildOutput\",\n        \"triggeredBy\": {\n          \"@id\": \"openshift:triggeredBy\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"serviceAccount\": \"openshift:serviceAccount\",\n        \"completionDeadlineSeconds\": \"openshift:completionDeadline\",\n        \"status\": \"openshift:buildStatus\"\n      }\n    },\n\n    \"BuildConfig\": {\n      \"@id\": \"openshift:BuildConfig\",\n      \"@context\": {\n        \"source\": \"openshift:buildSource\",\n        \"strategy\": \"openshift:buildStrategy\",\n        \"output\": \"openshift:buildOutput\",\n        \"triggers\": {\n          \"@id\": \"openshift:buildTriggers\",\n          \"@container\": \"@set\"\n        },\n        \"runPolicy\": \"openshift:runPolicy\",\n        \"serviceAccount\": \"openshift:serviceAccount\",\n        \"successfulBuildsHistoryLimit\": \"openshift:successfulBuildsHistoryLimit\",\n        \"failedBuildsHistoryLimit\": \"openshift:failedBuildsHistoryLimit\"\n      }\n    },\n\n    \"BuildSource\": {\n      \"@id\": \"openshift:BuildSource\",\n      \"@context\": {\n       \
  \ \"type\": \"openshift:sourceType\",\n        \"git\": \"openshift:gitSource\",\n        \"dockerfile\": \"openshift:dockerfileContent\",\n        \"contextDir\": \"openshift:contextDirectory\",\n        \"sourceSecret\": \"openshift:sourceSecret\"\n      }\n    },\n\n    \"BuildStrategy\": {\n      \"@id\": \"openshift:BuildStrategy\",\n      \"@context\": {\n        \"type\": \"openshift:strategyType\",\n        \"sourceStrategy\": \"openshift:sourceStrategy\",\n        \"dockerStrategy\": \"openshift:dockerStrategy\",\n        \"customStrategy\": \"openshift:customStrategy\"\n      }\n    },\n\n    \"BuildStatus\": {\n      \"@id\": \"openshift:BuildStatus\",\n      \"@context\": {\n        \"phase\": \"openshift:phase\",\n        \"cancelled\": \"openshift:isCancelled\",\n        \"message\": \"schema:description\",\n        \"reason\": \"openshift:statusReason\",\n        \"startTimestamp\": {\n          \"@id\": \"openshift:startTimestamp\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"completionTimestamp\": {\n          \"@id\": \"openshift:completionTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": \"openshift:durationNanos\",\n        \"outputDockerImageReference\": \"openshift:outputImageReference\"\n      }\n    },\n\n    \"DeploymentConfig\": {\n      \"@id\": \"openshift:DeploymentConfig\",\n      \"@context\": {\n        \"replicas\": \"openshift:replicas\",\n        \"selector\": \"openshift:labelSelector\",\n        \"template\": \"openshift:podTemplate\",\n        \"strategy\": \"openshift:deploymentStrategy\",\n        \"triggers\": {\n          \"@id\": \"openshift:deploymentTriggers\",\n          \"@container\": \"@set\"\n        },\n        \"minReadySeconds\": \"openshift:minReadySeconds\",\n        \"revisionHistoryLimit\": \"openshift:revisionHistoryLimit\",\n        \"paused\": \"openshift:isPaused\",\n        \"test\": \"openshift:isTest\",\n        \"status\": \"openshift:deploymentConfigStatus\"\
  \n      }\n    },\n\n    \"DeploymentStrategy\": {\n      \"@id\": \"openshift:DeploymentStrategy\",\n      \"@context\": {\n        \"type\": \"openshift:strategyType\",\n        \"rollingParams\": \"openshift:rollingParams\",\n        \"recreateParams\": \"openshift:recreateParams\",\n        \"customParams\": \"openshift:customParams\",\n        \"activeDeadlineSeconds\": \"openshift:activeDeadline\"\n      }\n    },\n\n    \"DeploymentConfigStatus\": {\n      \"@id\": \"openshift:DeploymentConfigStatus\",\n      \"@context\": {\n        \"latestVersion\": \"openshift:latestVersion\",\n        \"observedGeneration\": \"openshift:observedGeneration\",\n        \"replicas\": \"openshift:currentReplicas\",\n        \"updatedReplicas\": \"openshift:updatedReplicas\",\n        \"availableReplicas\": \"openshift:availableReplicas\",\n        \"unavailableReplicas\": \"openshift:unavailableReplicas\",\n        \"readyReplicas\": \"openshift:readyReplicas\",\n        \"conditions\": {\n   \
  \       \"@id\": \"openshift:conditions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"openshift:Project\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"openshift:projectStatus\",\n        \"phase\": \"openshift:phase\"\n      }\n    },\n\n    \"ProjectRequest\": {\n      \"@id\": \"openshift:ProjectRequest\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"ObjectMeta\": {\n      \"@id\": \"k8s:ObjectMeta\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"openshift:namespace\",\n        \"uid\": \"schema:identifier\",\n        \"resourceVersion\": \"openshift:resourceVersion\",\n        \"generation\": \"openshift:generation\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n   \
  \       \"@type\": \"xsd:dateTime\"\n        },\n        \"deletionTimestamp\": {\n          \"@id\": \"openshift:deletionTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"openshift:labels\",\n        \"annotations\": \"openshift:annotations\",\n        \"ownerReferences\": {\n          \"@id\": \"openshift:ownerReferences\",\n          \"@container\": \"@set\"\n        },\n        \"finalizers\": {\n          \"@id\": \"openshift:finalizers\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Container\": {\n      \"@id\": \"k8s:Container\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"image\": \"schema:image\",\n        \"command\": \"openshift:command\",\n        \"args\": \"openshift:args\",\n        \"env\": {\n          \"@id\": \"openshift:environmentVariables\",\n          \"@container\": \"@set\"\n        },\n        \"ports\": {\n          \"@id\": \"openshift:containerPorts\",\n          \"\
  @container\": \"@set\"\n        },\n        \"resources\": \"openshift:resourceRequirements\",\n        \"imagePullPolicy\": \"openshift:imagePullPolicy\"\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"k8s:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"openshift:namespace\",\n        \"selector\": \"openshift:labelSelector\",\n        \"ports\": {\n          \"@id\": \"openshift:servicePorts\",\n          \"@container\": \"@set\"\n        },\n        \"clusterIP\": \"openshift:clusterIP\",\n        \"type\": \"openshift:serviceType\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/json-ld/openshift-context.jsonld
tags:
- CI/CD
- Cloud Native
- Containers
- DevOps
- Enterprise
- Kubernetes
- PaaS
- JSON-LD
- Linked Data
- Semantic Web
---
