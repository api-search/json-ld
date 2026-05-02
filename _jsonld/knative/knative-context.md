---
api_specs:
- filename: knative-serving-api-openapi.yml
  format: yaml
  label: Knative Serving API
  slug: knative-serving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/openapi/knative-serving-api-openapi.yml
- filename: knative-eventing-api-openapi.yml
  format: yaml
  label: Knative Eventing API
  slug: knative-eventing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/openapi/knative-eventing-api-openapi.yml
class_count: 2
classes:
- name
- description
context_file: json-ld/knative-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/json-ld/knative-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Knative from Knative.
layout: jsonld
name: Knative Context
namespaces:
- prefix: knative
  uri: https://knative.dev/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/
- prefix: cloudevents
  uri: https://cloudevents.io/vocab#
- prefix: cncf
  uri: https://www.cncf.io/projects/
properties:
- container: ''
  name: Service
  type: ''
- container: ''
  name: Revision
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Configuration
  type: ''
- container: ''
  name: DomainMapping
  type: ''
- container: ''
  name: Broker
  type: ''
- container: ''
  name: Trigger
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: ApiServerSource
  type: ''
- container: ''
  name: PingSource
  type: ''
- container: ''
  name: SinkBinding
  type: ''
- container: ''
  name: TrafficTarget
  type: ''
- container: ''
  name: DeliverySpec
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
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 21
provider_name: Knative
provider_slug: knative
slug: knative-context
source_filename: knative-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"knative\": \"https://knative.dev/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/\",\n    \"cloudevents\": \"https://cloudevents.io/vocab#\",\n    \"cncf\": \"https://www.cncf.io/projects/\",\n\n    \"Service\": {\n      \"@id\": \"knative:Service\",\n      \"@context\": {\n        \"spec\": \"knative:serviceSpec\",\n        \"status\": \"knative:serviceStatus\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"latestReadyRevisionName\": \"knative:latestReadyRevisionName\",\n        \"latestCreatedRevisionName\": \"knative:latestCreatedRevisionName\",\n        \"traffic\": {\n          \"@id\":\
  \ \"knative:trafficTargets\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Knative Service\",\n      \"rdfs:comment\": \"A Knative Service that manages the full lifecycle of a serverless workload including Routes, Configurations, and Revisions.\",\n      \"skos:broader\": \"k8s:custom-resources\",\n      \"skos:exactMatch\": \"schema:SoftwareApplication\"\n    },\n\n    \"Revision\": {\n      \"@id\": \"knative:Revision\",\n      \"@context\": {\n        \"containerConcurrency\": \"knative:containerConcurrency\",\n        \"timeoutSeconds\": \"knative:timeoutSeconds\",\n        \"containers\": {\n          \"@id\": \"knative:containers\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Knative Revision\",\n      \"rdfs:comment\": \"An immutable snapshot of application code and configuration. Revisions are the autoscaled units of execution in Knative Serving.\",\n      \"skos:broader\": \"knative:Service\",\n      \"\
  skos:related\": \"schema:SoftwareSourceCode\"\n    },\n\n    \"Route\": {\n      \"@id\": \"knative:Route\",\n      \"@context\": {\n        \"traffic\": {\n          \"@id\": \"knative:trafficTargets\",\n          \"@container\": \"@set\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      },\n      \"rdfs:label\": \"Knative Route\",\n      \"rdfs:comment\": \"A Knative Route that maps network endpoints to Revisions and manages percentage-based traffic distribution.\",\n      \"skos:broader\": \"knative:Service\"\n    },\n\n    \"Configuration\": {\n      \"@id\": \"knative:Configuration\",\n      \"@context\": {\n        \"template\": \"knative:revisionTemplate\",\n        \"latestReadyRevisionName\": \"knative:latestReadyRevisionName\"\n      },\n      \"rdfs:label\": \"Knative Configuration\",\n      \"rdfs:comment\": \"Maintains the desired state for a deployment. Each update to the Configuration creates a new immutable\
  \ Revision.\",\n      \"skos:broader\": \"knative:Service\"\n    },\n\n    \"DomainMapping\": {\n      \"@id\": \"knative:DomainMapping\",\n      \"@context\": {\n        \"ref\": {\n          \"@id\": \"knative:serviceRef\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      },\n      \"rdfs:label\": \"Knative DomainMapping\",\n      \"rdfs:comment\": \"Associates a custom domain name with a Knative Service with automatic TLS certificate provisioning.\",\n      \"skos:broader\": \"knative:Service\"\n    },\n\n    \"Broker\": {\n      \"@id\": \"knative:Broker\",\n      \"@context\": {\n        \"delivery\": \"knative:deliverySpec\",\n        \"address\": {\n          \"@id\": \"knative:brokerAddress\",\n          \"@type\": \"@id\"\n        }\n      },\n      \"rdfs:label\": \"Knative Broker\",\n      \"rdfs:comment\": \"Collects a pool of CloudEvents and routes them to matching Triggers. Brokers\
  \ are the central hub in the Knative Eventing Broker-Trigger pattern.\",\n      \"skos:broader\": \"cloudevents:EventBroker\"\n    },\n\n    \"Trigger\": {\n      \"@id\": \"knative:Trigger\",\n      \"@context\": {\n        \"broker\": {\n          \"@id\": \"knative:triggerBroker\",\n          \"@type\": \"@id\"\n        },\n        \"filter\": \"knative:eventFilter\",\n        \"subscriber\": {\n          \"@id\": \"knative:subscriberDestination\",\n          \"@type\": \"@id\"\n        },\n        \"delivery\": \"knative:deliverySpec\"\n      },\n      \"rdfs:label\": \"Knative Trigger\",\n      \"rdfs:comment\": \"Subscribes to events from a Broker with optional CloudEvent attribute filters and routes matching events to a subscriber destination.\",\n      \"skos:broader\": \"cloudevents:EventSubscription\"\n    },\n\n    \"Channel\": {\n      \"@id\": \"knative:Channel\",\n      \"@context\": {\n        \"channelTemplate\": \"knative:channelTemplate\",\n        \"delivery\": \"knative:deliverySpec\"\
  ,\n        \"address\": {\n          \"@id\": \"knative:channelAddress\",\n          \"@type\": \"@id\"\n        }\n      },\n      \"rdfs:label\": \"Knative Channel\",\n      \"rdfs:comment\": \"A generic pub/sub channel that fans CloudEvents out to all Subscriptions. Backed by configurable implementations such as InMemoryChannel or KafkaChannel.\",\n      \"skos:broader\": \"cloudevents:EventChannel\"\n    },\n\n    \"Subscription\": {\n      \"@id\": \"knative:Subscription\",\n      \"@context\": {\n        \"channel\": {\n          \"@id\": \"knative:subscribedChannel\",\n          \"@type\": \"@id\"\n        },\n        \"subscriber\": {\n          \"@id\": \"knative:subscriberDestination\",\n          \"@type\": \"@id\"\n        },\n        \"reply\": {\n          \"@id\": \"knative:replyDestination\",\n          \"@type\": \"@id\"\n        },\n        \"delivery\": \"knative:deliverySpec\"\n      },\n      \"rdfs:label\": \"Knative Subscription\",\n      \"rdfs:comment\": \"Routes\
  \ events from a Channel to a subscriber destination, independently of other Subscriptions to the same Channel.\",\n      \"skos:broader\": \"cloudevents:EventSubscription\"\n    },\n\n    \"ApiServerSource\": {\n      \"@id\": \"knative:ApiServerSource\",\n      \"@context\": {\n        \"resources\": {\n          \"@id\": \"knative:watchedResources\",\n          \"@container\": \"@set\"\n        },\n        \"sink\": {\n          \"@id\": \"knative:eventSink\",\n          \"@type\": \"@id\"\n        },\n        \"mode\": \"knative:sourceMode\"\n      },\n      \"rdfs:label\": \"Knative ApiServerSource\",\n      \"rdfs:comment\": \"Watches Kubernetes API server events for specified resource types and emits them as CloudEvents to a sink.\",\n      \"skos:broader\": \"knative:EventSource\",\n      \"skos:related\": \"k8s:events\"\n    },\n\n    \"PingSource\": {\n      \"@id\": \"knative:PingSource\",\n      \"@context\": {\n        \"schedule\": \"schema:repeatFrequency\",\n        \"sink\"\
  : {\n          \"@id\": \"knative:eventSink\",\n          \"@type\": \"@id\"\n        },\n        \"data\": \"schema:text\",\n        \"timezone\": \"schema:temporalCoverage\"\n      },\n      \"rdfs:label\": \"Knative PingSource\",\n      \"rdfs:comment\": \"Emits CloudEvents on a cron schedule with a configurable payload. Used for periodic workflows and scheduled tasks.\",\n      \"skos:broader\": \"knative:EventSource\"\n    },\n\n    \"SinkBinding\": {\n      \"@id\": \"knative:SinkBinding\",\n      \"@context\": {\n        \"subject\": {\n          \"@id\": \"knative:bindingSubject\",\n          \"@type\": \"@id\"\n        },\n        \"sink\": {\n          \"@id\": \"knative:eventSink\",\n          \"@type\": \"@id\"\n        },\n        \"ceOverrides\": \"knative:cloudEventOverrides\"\n      },\n      \"rdfs:label\": \"Knative SinkBinding\",\n      \"rdfs:comment\": \"Augments a PodSpecable workload by injecting the sink URI as K_SINK, enabling existing workloads to send CloudEvents.\"\
  ,\n      \"skos:broader\": \"knative:EventSource\"\n    },\n\n    \"TrafficTarget\": {\n      \"@id\": \"knative:TrafficTarget\",\n      \"@context\": {\n        \"revisionName\": \"knative:targetRevision\",\n        \"percent\": {\n          \"@id\": \"schema:percentile\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tag\": \"dcterms:title\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      },\n      \"rdfs:label\": \"Traffic Target\",\n      \"rdfs:comment\": \"A percentage-based traffic routing target pointing to a Knative Revision.\"\n    },\n\n    \"DeliverySpec\": {\n      \"@id\": \"knative:DeliverySpec\",\n      \"@context\": {\n        \"deadLetterSink\": {\n          \"@id\": \"knative:deadLetterSink\",\n          \"@type\": \"@id\"\n        },\n        \"retry\": {\n          \"@id\": \"knative:retryCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"backoffPolicy\": \"knative:backoffPolicy\"\
  ,\n        \"backoffDelay\": \"knative:backoffDelay\",\n        \"timeout\": \"knative:deliveryTimeout\"\n      },\n      \"rdfs:label\": \"Delivery Spec\",\n      \"rdfs:comment\": \"Configuration for event delivery retries and dead-letter sinks in Knative Eventing.\"\n    },\n\n    \"apiVersion\": {\n      \"@id\": \"k8s:apiVersion\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Kubernetes API group and version identifier.\"\n    },\n    \"kind\": {\n      \"@id\": \"k8s:resourceKind\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Kubernetes resource type identifier.\"\n    },\n    \"metadata\": {\n      \"@id\": \"k8s:objectMeta\",\n      \"rdfs:comment\": \"Standard Kubernetes object metadata.\"\n    },\n    \"spec\": {\n      \"@id\": \"k8s:resourceSpec\",\n      \"rdfs:comment\": \"Desired state specification for the Kubernetes resource.\"\n    },\n    \"status\": {\n      \"@id\": \"k8s:resourceStatus\",\n      \"rdfs:comment\": \"Observed state and\
  \ conditions of the Kubernetes resource.\"\n    },\n    \"name\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/json-ld/knative-context.jsonld
tags:
- Auto-Scaling
- Cloud Native
- Event-Driven
- Graduated
- Kubernetes
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
