---
class_count: 6
classes:
- name
- description
- uid
- namespace
- duration
- status
context_file: json-ld/chaos-mesh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/json-ld/chaos-mesh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chaos Mesh from Chaos Mesh.
layout: jsonld
name: Chaos Mesh Context
namespaces:
- prefix: chaos
  uri: https://chaos-mesh.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: k8s
  uri: https://kubernetes.io/docs/concepts/
- prefix: cncf
  uri: https://www.cncf.io/projects/
properties:
- container: ''
  name: ChaosExperiment
  type: ''
- container: ''
  name: PodChaos
  type: ''
- container: ''
  name: NetworkChaos
  type: ''
- container: ''
  name: IOChaos
  type: ''
- container: ''
  name: StressChaos
  type: ''
- container: ''
  name: HTTPChaos
  type: ''
- container: ''
  name: TimeChaos
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: PodSelector
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: created_at
  type: dateTime
property_count: 12
provider_name: Chaos Mesh
provider_slug: chaos-mesh
slug: chaos-mesh-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chaos\": \"https://chaos-mesh.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"k8s\": \"https://kubernetes.io/docs/concepts/\",\n    \"cncf\": \"https://www.cncf.io/projects/\",\n\n    \"ChaosExperiment\": {\n      \"@id\": \"chaos:ChaosExperiment\",\n      \"@context\": {\n        \"apiVersion\": \"chaos:apiVersion\",\n        \"kind\": \"chaos:chaosKind\",\n        \"metadata\": \"chaos:metadata\",\n        \"spec\": \"chaos:spec\",\n        \"status\": \"chaos:status\"\n      },\n      \"rdfs:label\": \"Chaos Experiment\",\n      \"rdfs:comment\": \"A Chaos Mesh fault injection experiment targeting Kubernetes pods.\",\n      \"rdfs:subClassOf\": { \"@id\": \"k8s:workloads/\" }\n    },\n\n    \"PodChaos\": {\n      \"@id\": \"chaos:PodChaos\",\n    \
  \  \"@context\": {\n        \"action\": \"chaos:podAction\",\n        \"selector\": \"chaos:podSelector\",\n        \"mode\": \"chaos:selectionMode\",\n        \"duration\": \"chaos:duration\",\n        \"containerNames\": {\n          \"@id\": \"chaos:containerNames\",\n          \"@container\": \"@set\"\n        },\n        \"gracePeriod\": {\n          \"@id\": \"chaos:gracePeriod\",\n          \"@type\": \"xsd:integer\"\n        }\n      },\n      \"rdfs:label\": \"Pod Chaos\",\n      \"rdfs:comment\": \"A chaos experiment injecting pod-level faults such as pod-failure, pod-kill, or container-kill.\",\n      \"rdfs:subClassOf\": { \"@id\": \"chaos:ChaosExperiment\" }\n    },\n\n    \"NetworkChaos\": {\n      \"@id\": \"chaos:NetworkChaos\",\n      \"@context\": {\n        \"action\": \"chaos:networkAction\",\n        \"selector\": \"chaos:podSelector\",\n        \"mode\": \"chaos:selectionMode\",\n        \"direction\": \"chaos:networkDirection\",\n        \"duration\": \"chaos:duration\"\
  ,\n        \"delay\": \"chaos:networkDelay\",\n        \"loss\": \"chaos:networkLoss\",\n        \"bandwidth\": \"chaos:networkBandwidth\",\n        \"target\": \"chaos:targetSelector\"\n      },\n      \"rdfs:label\": \"Network Chaos\",\n      \"rdfs:comment\": \"A chaos experiment injecting network faults such as latency, packet loss, corruption, or partition.\",\n      \"rdfs:subClassOf\": { \"@id\": \"chaos:ChaosExperiment\" }\n    },\n\n    \"IOChaos\": {\n      \"@id\": \"chaos:IOChaos\",\n      \"@context\": {\n        \"action\": \"chaos:ioAction\",\n        \"selector\": \"chaos:podSelector\",\n        \"mode\": \"chaos:selectionMode\",\n        \"volumePath\": \"chaos:volumePath\",\n        \"path\": \"chaos:ioPath\",\n        \"methods\": {\n          \"@id\": \"chaos:ioMethods\",\n          \"@container\": \"@set\"\n        },\n        \"delay\": \"chaos:ioDelay\",\n        \"errno\": {\n          \"@id\": \"chaos:ioErrno\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"percent\": {\n          \"@id\": \"chaos:ioPercent\",\n          \"@type\": \"xsd:integer\"\n        }\n      },\n      \"rdfs:label\": \"IO Chaos\",\n      \"rdfs:comment\": \"A chaos experiment injecting I/O faults such as delays, errors, and faults on file system operations.\",\n      \"rdfs:subClassOf\": { \"@id\": \"chaos:ChaosExperiment\" }\n    },\n\n    \"StressChaos\": {\n      \"@id\": \"chaos:StressChaos\",\n      \"@context\": {\n        \"selector\": \"chaos:podSelector\",\n        \"mode\": \"chaos:selectionMode\",\n        \"duration\": \"chaos:duration\",\n        \"stressors\": \"chaos:stressors\",\n        \"containerNames\": {\n          \"@id\": \"chaos:containerNames\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Stress Chaos\",\n      \"rdfs:comment\": \"A chaos experiment injecting CPU or memory stress into selected pods.\",\n      \"rdfs:subClassOf\": { \"@id\": \"chaos:ChaosExperiment\" }\n    },\n\n    \"HTTPChaos\"\
  : {\n      \"@id\": \"chaos:HTTPChaos\",\n      \"@context\": {\n        \"selector\": \"chaos:podSelector\",\n        \"mode\": \"chaos:selectionMode\",\n        \"target\": \"chaos:httpTarget\",\n        \"port\": {\n          \"@id\": \"schema:portNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"method\": \"chaos:httpMethod\",\n        \"path\": \"chaos:httpPath\",\n        \"duration\": \"chaos:duration\",\n        \"abort\": {\n          \"@id\": \"chaos:httpAbort\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"delay\": \"chaos:httpDelay\",\n        \"replace\": \"chaos:httpReplace\",\n        \"patch\": \"chaos:httpPatch\"\n      },\n      \"rdfs:label\": \"HTTP Chaos\",\n      \"rdfs:comment\": \"A chaos experiment injecting faults into HTTP request or response traffic.\",\n      \"rdfs:subClassOf\": { \"@id\": \"chaos:ChaosExperiment\" }\n    },\n\n    \"TimeChaos\": {\n      \"@id\": \"chaos:TimeChaos\",\n      \"@context\": {\n        \"\
  selector\": \"chaos:podSelector\",\n        \"mode\": \"chaos:selectionMode\",\n        \"duration\": \"chaos:duration\",\n        \"timeOffset\": \"chaos:timeOffset\",\n        \"clockIds\": {\n          \"@id\": \"chaos:clockIds\",\n          \"@container\": \"@set\"\n        },\n        \"containerNames\": {\n          \"@id\": \"chaos:containerNames\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Time Chaos\",\n      \"rdfs:comment\": \"A chaos experiment that manipulates the system clock in selected pods to simulate time skew.\",\n      \"rdfs:subClassOf\": { \"@id\": \"chaos:ChaosExperiment\" }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"chaos:Schedule\",\n      \"@context\": {\n        \"schedule\": \"chaos:cronExpression\",\n        \"concurrencyPolicy\": \"chaos:concurrencyPolicy\",\n        \"historyLimit\": {\n          \"@id\": \"chaos:historyLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startingDeadlineSeconds\"\
  : {\n          \"@id\": \"chaos:startingDeadlineSeconds\",\n          \"@type\": \"xsd:integer\"\n        }\n      },\n      \"rdfs:label\": \"Chaos Schedule\",\n      \"rdfs:comment\": \"A recurring chaos experiment schedule using cron expressions to trigger fault injection automatically.\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Action\" }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"chaos:Workflow\",\n      \"@context\": {\n        \"entry\": \"chaos:workflowEntry\",\n        \"templates\": {\n          \"@id\": \"chaos:workflowTemplates\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Chaos Workflow\",\n      \"rdfs:comment\": \"A Chaos Mesh workflow orchestrating multiple chaos experiments in serial or parallel sequences.\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Action\" }\n    },\n\n    \"PodSelector\": {\n      \"@id\": \"chaos:PodSelector\",\n      \"@context\": {\n        \"namespaces\": {\n          \"@id\": \"chaos:targetNamespaces\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"labelSelectors\": \"chaos:labelSelectors\",\n        \"annotationSelectors\": \"chaos:annotationSelectors\",\n        \"fieldSelectors\": \"chaos:fieldSelectors\",\n        \"podPhaseSelectors\": {\n          \"@id\": \"chaos:podPhaseSelectors\",\n          \"@container\": \"@set\"\n        },\n        \"nodeSelectors\": \"chaos:nodeSelectors\",\n        \"pods\": \"chaos:explicitPods\"\n      },\n      \"rdfs:label\": \"Pod Selector\",\n      \"rdfs:comment\": \"Configuration for selecting target pods for chaos injection via labels, namespaces, or explicit names.\"\n    },\n\n    \"Event\": {\n      \"@id\": \"chaos:Event\",\n      \"@context\": {\n        \"namespace\": \"chaos:eventNamespace\",\n        \"name\": \"dcterms:title\",\n        \"kind\": \"chaos:resourceKind\",\n        \"type\": \"chaos:eventType\",\n        \"reason\": \"chaos:eventReason\",\n        \"message\": \"schema:description\",\n        \"created_at\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"object_id\": \"chaos:objectId\"\n      },\n      \"rdfs:label\": \"Chaos Event\",\n      \"rdfs:comment\": \"An event record capturing lifecycle changes and state transitions of chaos experiments.\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Event\" }\n    },\n\n    \"name\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"uid\": \"dcterms:identifier\",\n    \"created_at\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"namespace\": \"chaos:namespace\",\n    \"duration\": \"chaos:duration\",\n    \"status\": \"chaos:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/json-ld/chaos-mesh-context.jsonld
tags:
- Chaos Engineering
- Cloud Native
- CNCF
- Fault Injection
- Kubernetes
- Observability
- Open Source
- Reliability
- Resilience
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
