---
class_count: 44
classes:
- WorkloadSpecification
- ScoreFile
- ScoreImplementation
- Container
- ContainerImage
- Service
- Resource
- ResourceProvisioner
- name
- description
- version
- url
- license
- apiVersion
- workloadName
- annotations
- container
- containerImage
- command
- args
- variables
- files
- volumes
- resources
- livenessProbe
- readinessProbe
- servicePort
- protocol
- targetPort
- resourceType
- resourceClass
- resourceId
- resourceParams
- resourceOutput
- platform
- dockerCompose
- kubernetes
- helmChart
- cloudRun
- scoreCompose
- scoreK8s
- scoreGo
- cncfSandbox
- openSource
context_file: json-ld/score-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/json-ld/score-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Score from Score.
layout: jsonld
name: Score Context
namespaces:
- prefix: score
  uri: https://score.dev/ontology/
- prefix: cncf
  uri: https://www.cncf.io/ontology/
- prefix: oci
  uri: https://opencontainers.org/ontology/
properties:
- container: ''
  name: githubOrg
  type: reference
property_count: 1
provider_name: Score
provider_slug: score
slug: score-context
source_filename: score-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"score\": \"https://score.dev/ontology/\",\n    \"cncf\": \"https://www.cncf.io/ontology/\",\n    \"oci\": \"https://opencontainers.org/ontology/\",\n\n    \"WorkloadSpecification\": \"score:WorkloadSpecification\",\n    \"ScoreFile\": \"score:ScoreFile\",\n    \"ScoreImplementation\": \"score:Implementation\",\n    \"Container\": \"oci:Container\",\n    \"ContainerImage\": \"oci:Image\",\n    \"Service\": \"schema:SoftwareApplication\",\n    \"Resource\": \"score:Resource\",\n    \"ResourceProvisioner\": \"score:ResourceProvisioner\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": \"schema:url\",\n    \"license\": \"schema:license\",\n\n    \"apiVersion\": \"score:apiVersion\",\n    \"workloadName\": \"schema:name\",\n    \"annotations\": \"schema:additionalProperty\",\n\n    \"container\": \"score:Container\",\n    \"containerImage\"\
  : \"oci:imageReference\",\n    \"command\": \"score:command\",\n    \"args\": \"score:args\",\n    \"variables\": \"score:environmentVariables\",\n    \"files\": \"score:mountedFiles\",\n    \"volumes\": \"score:volumes\",\n    \"resources\": \"score:resources\",\n    \"livenessProbe\": \"score:livenessProbe\",\n    \"readinessProbe\": \"score:readinessProbe\",\n\n    \"servicePort\": \"schema:port\",\n    \"protocol\": \"schema:protocol\",\n    \"targetPort\": \"score:targetPort\",\n\n    \"resourceType\": \"score:resourceType\",\n    \"resourceClass\": \"score:resourceClass\",\n    \"resourceId\": \"score:resourceId\",\n    \"resourceParams\": \"score:resourceParams\",\n    \"resourceOutput\": \"score:resourceOutput\",\n\n    \"platform\": \"score:TargetPlatform\",\n    \"dockerCompose\": \"score:DockerComposePlatform\",\n    \"kubernetes\": \"score:KubernetesPlatform\",\n    \"helmChart\": \"score:HelmPlatform\",\n    \"cloudRun\": \"score:CloudRunPlatform\",\n\n    \"scoreCompose\"\
  : \"score:ScoreComposeImplementation\",\n    \"scoreK8s\": \"score:ScoreK8sImplementation\",\n    \"scoreGo\": \"score:ScoreGoLibrary\",\n\n    \"cncfSandbox\": \"cncf:SandboxProject\",\n    \"openSource\": \"schema:isAccessibleForFree\",\n    \"githubOrg\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/json-ld/score-context.jsonld
tags:
- Platform Engineering
- Cloud Native
- CNCF
- Workload Specification
- Kubernetes
- Docker
- Developer Experience
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
