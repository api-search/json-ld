---
api_specs:
- filename: swagger.json
  format: json
  label: Kubernetes API
  slug: kubernetes
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json
class_count: 0
classes: []
context_file: json-ld/kubernetes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/json-ld/kubernetes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kubernetes from Kubernetes.
layout: jsonld
name: Kubernetes Context
namespaces:
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.32/#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: oci
  uri: https://opencontainers.org/schema/1.0/
properties:
- container: ''
  name: Pod
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: StatefulSet
  type: ''
- container: ''
  name: DaemonSet
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Namespace
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: ConfigMap
  type: ''
- container: ''
  name: Secret
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: CronJob
  type: ''
- container: ''
  name: ClusterRole
  type: ''
- container: ''
  name: ClusterRoleBinding
  type: ''
- container: ''
  name: ServiceAccount
  type: ''
- container: ''
  name: HorizontalPodAutoscaler
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: ObjectMeta
  type: ''
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: metadata
  type: ''
- container: ''
  name: spec
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: index
  name: labels
  type: ''
- container: index
  name: annotations
  type: ''
- container: ''
  name: replicas
  type: integer
- container: ''
  name: image
  type: string
- container: set
  name: containers
  type: ''
- container: set
  name: volumes
  type: ''
- container: set
  name: ports
  type: ''
- container: set
  name: env
  type: ''
- container: ''
  name: resources
  type: ''
- container: ''
  name: selector
  type: ''
- container: ''
  name: template
  type: ''
- container: ''
  name: creationTimestamp
  type: dateTime
property_count: 36
provider_name: Kubernetes
provider_slug: kubernetes
slug: kubernetes-context
source_filename: kubernetes-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.32/#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"oci\": \"https://opencontainers.org/schema/1.0/\",\n\n    \"Pod\": {\n      \"@id\": \"k8s:pod-v1-core\",\n      \"@context\": {\n        \"spec\": \"k8s:podspec-v1-core\",\n        \"status\": \"k8s:podstatus-v1-core\",\n        \"metadata\": \"k8s:objectmeta-v1-meta\"\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"k8s:deployment-v1-apps\",\n      \"@context\": {\n        \"spec\": \"k8s:deploymentspec-v1-apps\",\n        \"status\": \"k8s:deploymentstatus-v1-apps\",\n        \"metadata\": \"k8s:objectmeta-v1-meta\"\n      }\n    },\n\n    \"StatefulSet\": {\n      \"@id\": \"\
  k8s:statefulset-v1-apps\",\n      \"@context\": {\n        \"spec\": \"k8s:statefulsetspec-v1-apps\",\n        \"status\": \"k8s:statefulsetstatus-v1-apps\"\n      }\n    },\n\n    \"DaemonSet\": {\n      \"@id\": \"k8s:daemonset-v1-apps\",\n      \"@context\": {\n        \"spec\": \"k8s:daemonsetspec-v1-apps\",\n        \"status\": \"k8s:daemonsetstatus-v1-apps\"\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"k8s:service-v1-core\",\n      \"@context\": {\n        \"spec\": \"k8s:servicespec-v1-core\",\n        \"status\": \"k8s:servicestatus-v1-core\"\n      }\n    },\n\n    \"Namespace\": {\n      \"@id\": \"k8s:namespace-v1-core\",\n      \"@context\": {\n        \"spec\": \"k8s:namespacespec-v1-core\",\n        \"status\": \"k8s:namespacestatus-v1-core\",\n        \"phase\": {\n          \"@id\": \"k8s:namespacestatus-phase-v1-core\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"k8s:node-v1-core\",\n      \"@context\"\
  : {\n        \"spec\": \"k8s:nodespec-v1-core\",\n        \"status\": \"k8s:nodestatus-v1-core\"\n      }\n    },\n\n    \"ConfigMap\": {\n      \"@id\": \"k8s:configmap-v1-core\",\n      \"@context\": {\n        \"data\": \"k8s:configmap-data-v1-core\",\n        \"binaryData\": \"k8s:configmap-binarydata-v1-core\"\n      }\n    },\n\n    \"Secret\": {\n      \"@id\": \"k8s:secret-v1-core\",\n      \"@context\": {\n        \"type\": \"k8s:secret-type-v1-core\",\n        \"data\": \"k8s:secret-data-v1-core\",\n        \"stringData\": \"k8s:secret-stringdata-v1-core\"\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"k8s:job-v1-batch\",\n      \"@context\": {\n        \"spec\": \"k8s:jobspec-v1-batch\",\n        \"status\": \"k8s:jobstatus-v1-batch\"\n      }\n    },\n\n    \"CronJob\": {\n      \"@id\": \"k8s:cronjob-v1-batch\",\n      \"@context\": {\n        \"spec\": \"k8s:cronjobspec-v1-batch\",\n        \"status\": \"k8s:cronjobstatus-v1-batch\",\n        \"schedule\": {\n     \
  \     \"@id\": \"k8s:cronjobspec-schedule-v1-batch\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ClusterRole\": {\n      \"@id\": \"k8s:clusterrole-v1-rbac.authorization.k8s.io\",\n      \"@context\": {\n        \"rules\": \"k8s:policyrule-v1-rbac.authorization.k8s.io\"\n      }\n    },\n\n    \"ClusterRoleBinding\": {\n      \"@id\": \"k8s:clusterrolebinding-v1-rbac.authorization.k8s.io\",\n      \"@context\": {\n        \"roleRef\": \"k8s:roleref-v1-rbac.authorization.k8s.io\",\n        \"subjects\": \"k8s:subject-v1-rbac.authorization.k8s.io\"\n      }\n    },\n\n    \"ServiceAccount\": {\n      \"@id\": \"k8s:serviceaccount-v1-core\",\n      \"@context\": {\n        \"secrets\": \"k8s:serviceaccount-secrets-v1-core\"\n      }\n    },\n\n    \"HorizontalPodAutoscaler\": {\n      \"@id\": \"k8s:horizontalpodautoscaler-v2-autoscaling\",\n      \"@context\": {\n        \"spec\": \"k8s:horizontalpodautoscalerspec-v2-autoscaling\",\n        \"status\": \"k8s:horizontalpodautoscalerstatus-v2-autoscaling\"\
  ,\n        \"minReplicas\": {\n          \"@id\": \"k8s:horizontalpodautoscalerspec-minReplicas-v2-autoscaling\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxReplicas\": {\n          \"@id\": \"k8s:horizontalpodautoscalerspec-maxReplicas-v2-autoscaling\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"k8s:event-v1-events.k8s.io\",\n      \"@context\": {\n        \"eventTime\": {\n          \"@id\": \"k8s:event-eventTime-v1-events.k8s.io\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"action\": \"k8s:event-action-v1-events.k8s.io\",\n        \"reason\": \"k8s:event-reason-v1-events.k8s.io\",\n        \"note\": \"k8s:event-note-v1-events.k8s.io\",\n        \"type\": \"k8s:event-type-v1-events.k8s.io\",\n        \"regarding\": \"k8s:objectreference-v1-core\",\n        \"reportingComponent\": \"k8s:event-reportingComponent-v1-events.k8s.io\"\n      }\n    },\n\n    \"ObjectMeta\": {\n      \"@id\"\
  : \"k8s:objectmeta-v1-meta\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namespace\": {\n          \"@id\": \"k8s:objectmeta-namespace-v1-meta\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceVersion\": {\n          \"@id\": \"k8s:objectmeta-resourceVersion-v1-meta\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generation\": {\n          \"@id\": \"k8s:objectmeta-generation-v1-meta\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deletionTimestamp\": {\n          \"@id\": \"k8s:objectmeta-deletionTimestamp-v1-meta\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": {\n          \"\
  @id\": \"k8s:objectmeta-labels-v1-meta\",\n          \"@container\": \"@index\"\n        },\n        \"annotations\": {\n          \"@id\": \"k8s:objectmeta-annotations-v1-meta\",\n          \"@container\": \"@index\"\n        },\n        \"ownerReferences\": {\n          \"@id\": \"k8s:ownerreference-v1-meta\",\n          \"@container\": \"@set\"\n        },\n        \"finalizers\": {\n          \"@id\": \"k8s:objectmeta-finalizers-v1-meta\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"apiVersion\": {\n      \"@id\": \"k8s:apiversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"k8s:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"k8s:objectmeta-v1-meta\"\n    },\n    \"spec\": {\n      \"@id\": \"k8s:spec\"\n    },\n    \"status\": {\n      \"@id\": \"k8s:status\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n\
  \      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"k8s:labels\",\n      \"@container\": \"@index\"\n    },\n    \"annotations\": {\n      \"@id\": \"k8s:annotations\",\n      \"@container\": \"@index\"\n    },\n    \"replicas\": {\n      \"@id\": \"k8s:replicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"image\": {\n      \"@id\": \"oci:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containers\": {\n      \"@id\": \"k8s:containers\",\n      \"@container\": \"@set\"\n    },\n    \"volumes\": {\n      \"@id\": \"k8s:volumes\",\n      \"@container\": \"@set\"\n    },\n    \"ports\": {\n      \"@id\": \"k8s:ports\",\n      \"@container\": \"@set\"\n    },\n    \"env\": {\n      \"@id\": \"k8s:env\",\n      \"@container\": \"@set\"\n    },\n    \"resources\": {\n      \"@id\": \"k8s:resources\"\n    },\n    \"selector\": {\n      \"@id\": \"k8s:selector\"\n    },\n    \"template\": {\n      \"@id\": \"k8s:template\"\
  \n    },\n    \"creationTimestamp\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/json-ld/kubernetes-context.jsonld
tags:
- Automation
- Cloud Native
- CNCF
- Containers
- Deployment
- Open Source
- Orchestration
- Scaling
- JSON-LD
- Linked Data
- Semantic Web
---
