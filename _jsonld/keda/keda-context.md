---
api_specs:
- filename: keda-metrics-api-openapi.yml
  format: yaml
  label: KEDA Metrics API
  slug: keda-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/openapi/keda-metrics-api-openapi.yml
- filename: keda-cloud-events-asyncapi.yml
  format: yaml
  label: KEDA CloudEventSource API
  slug: keda-cloud-event-source-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/asyncapi/keda-cloud-events-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/keda-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/json-ld/keda-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Keda from KEDA.
layout: jsonld
name: Keda Context
namespaces:
- prefix: keda
  uri: https://keda.sh/vocab#
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
properties:
- container: ''
  name: ScaledObject
  type: hydra:Class
- container: ''
  name: ScaledJob
  type: hydra:Class
- container: ''
  name: TriggerAuthentication
  type: hydra:Class
- container: ''
  name: ClusterTriggerAuthentication
  type: hydra:Class
- container: ''
  name: scaleTargetRef
  type: reference
- container: ''
  name: jobTargetRef
  type: reference
- container: list
  name: triggers
  type: reference
- container: ''
  name: trigger
  type: hydra:Class
- container: ''
  name: triggerType
  type: string
- container: ''
  name: authenticationRef
  type: reference
- container: ''
  name: pollingInterval
  type: integer
- container: ''
  name: cooldownPeriod
  type: integer
- container: ''
  name: minReplicaCount
  type: integer
- container: ''
  name: maxReplicaCount
  type: integer
- container: ''
  name: idleReplicaCount
  type: integer
- container: ''
  name: metricType
  type: string
- container: ''
  name: fallback
  type: reference
- container: ''
  name: scalingStrategy
  type: reference
- container: list
  name: secretTargetRef
  type: reference
- container: ''
  name: podIdentity
  type: reference
- container: ''
  name: hashiCorpVault
  type: reference
- container: ''
  name: azureKeyVault
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
property_count: 27
provider_name: KEDA
provider_slug: keda
slug: keda-context
source_filename: keda-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://keda.sh/vocab#\",\n    \"keda\": \"https://keda.sh/vocab#\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n\n    \"ScaledObject\": {\n      \"@id\": \"keda:ScaledObject\",\n      \"@type\": \"hydra:Class\",\n      \"rdfs:comment\": \"A custom resource that defines the mapping between an event source and a Kubernetes workload to be autoscaled.\",\n      \"rdfs:subClassOf\": { \"@id\": \"k8s:CustomResourceDefinition\" }\n    },\n    \"ScaledJob\": {\n      \"@id\": \"keda:ScaledJob\",\n      \"@type\": \"hydra:Class\",\n      \"rdfs:comment\": \"A custom resource that creates Kubernetes Jobs\
  \ in response to event-driven triggers.\",\n      \"rdfs:subClassOf\": { \"@id\": \"k8s:CustomResourceDefinition\" }\n    },\n    \"TriggerAuthentication\": {\n      \"@id\": \"keda:TriggerAuthentication\",\n      \"@type\": \"hydra:Class\",\n      \"rdfs:comment\": \"A custom resource that defines authentication parameters for event source triggers.\",\n      \"rdfs:subClassOf\": { \"@id\": \"k8s:CustomResourceDefinition\" }\n    },\n    \"ClusterTriggerAuthentication\": {\n      \"@id\": \"keda:ClusterTriggerAuthentication\",\n      \"@type\": \"hydra:Class\",\n      \"rdfs:comment\": \"A cluster-scoped variant of TriggerAuthentication available across all namespaces.\",\n      \"rdfs:subClassOf\": { \"@id\": \"keda:TriggerAuthentication\" }\n    },\n\n    \"scaleTargetRef\": {\n      \"@id\": \"keda:scaleTargetRef\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Reference to the Kubernetes workload resource to be scaled.\",\n      \"rdfs:range\": { \"@id\": \"k8s:ObjectReference\"\
  \ }\n    },\n    \"jobTargetRef\": {\n      \"@id\": \"keda:jobTargetRef\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Template for the Kubernetes Job to be created by event triggers.\",\n      \"rdfs:range\": { \"@id\": \"k8s:JobSpec\" }\n    },\n    \"triggers\": {\n      \"@id\": \"keda:triggers\",\n      \"@type\": \"@id\",\n      \"@container\": \"@list\",\n      \"rdfs:comment\": \"Collection of event-driven trigger definitions that provide scaling metrics.\"\n    },\n    \"trigger\": {\n      \"@id\": \"keda:Trigger\",\n      \"@type\": \"hydra:Class\",\n      \"rdfs:comment\": \"An event source trigger that provides metrics for autoscaling decisions.\"\n    },\n    \"triggerType\": {\n      \"@id\": \"keda:triggerType\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"The type of event source scaler (e.g., kafka, rabbitmq, prometheus, aws-sqs-queue).\"\n    },\n    \"authenticationRef\": {\n      \"@id\": \"keda:authenticationRef\",\n      \"@type\": \"\
  @id\",\n      \"rdfs:comment\": \"Reference to a TriggerAuthentication or ClusterTriggerAuthentication resource.\",\n      \"rdfs:range\": { \"@id\": \"keda:TriggerAuthentication\" }\n    },\n\n    \"pollingInterval\": {\n      \"@id\": \"keda:pollingInterval\",\n      \"@type\": \"xsd:integer\",\n      \"rdfs:comment\": \"Interval in seconds between trigger metric queries.\",\n      \"schema:unitCode\": \"SEC\"\n    },\n    \"cooldownPeriod\": {\n      \"@id\": \"keda:cooldownPeriod\",\n      \"@type\": \"xsd:integer\",\n      \"rdfs:comment\": \"Period in seconds to wait after the last active trigger before scaling to minimum.\",\n      \"schema:unitCode\": \"SEC\"\n    },\n    \"minReplicaCount\": {\n      \"@id\": \"keda:minReplicaCount\",\n      \"@type\": \"xsd:integer\",\n      \"rdfs:comment\": \"Minimum number of workload replicas.\",\n      \"rdfs:subPropertyOf\": { \"@id\": \"schema:minValue\" }\n    },\n    \"maxReplicaCount\": {\n      \"@id\": \"keda:maxReplicaCount\",\n\
  \      \"@type\": \"xsd:integer\",\n      \"rdfs:comment\": \"Maximum number of workload replicas.\",\n      \"rdfs:subPropertyOf\": { \"@id\": \"schema:maxValue\" }\n    },\n    \"idleReplicaCount\": {\n      \"@id\": \"keda:idleReplicaCount\",\n      \"@type\": \"xsd:integer\",\n      \"rdfs:comment\": \"Number of replicas when there are no active triggers (below minReplicaCount).\"\n    },\n\n    \"metricType\": {\n      \"@id\": \"keda:metricType\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"The type of HPA metric: AverageValue, Value, or Utilization.\",\n      \"rdfs:seeAlso\": { \"@id\": \"k8s:MetricSpec\" }\n    },\n    \"fallback\": {\n      \"@id\": \"keda:fallback\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Fallback configuration used when a scaler cannot retrieve metrics.\"\n    },\n    \"scalingStrategy\": {\n      \"@id\": \"keda:scalingStrategy\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Strategy controlling how job counts are calculated\
  \ from metrics.\"\n    },\n\n    \"secretTargetRef\": {\n      \"@id\": \"keda:secretTargetRef\",\n      \"@type\": \"@id\",\n      \"@container\": \"@list\",\n      \"rdfs:comment\": \"References to Kubernetes Secrets providing authentication credentials.\",\n      \"rdfs:range\": { \"@id\": \"k8s:SecretKeySelector\" }\n    },\n    \"podIdentity\": {\n      \"@id\": \"keda:podIdentity\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Cloud provider pod identity configuration for workload authentication.\"\n    },\n    \"hashiCorpVault\": {\n      \"@id\": \"keda:hashiCorpVault\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"HashiCorp Vault integration for secret retrieval.\",\n      \"rdfs:seeAlso\": { \"@id\": \"https://www.vaultproject.io/\" }\n    },\n    \"azureKeyVault\": {\n      \"@id\": \"keda:azureKeyVault\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Azure Key Vault integration for secret retrieval.\",\n      \"rdfs:seeAlso\": { \"@id\": \"https://azure.microsoft.com/services/key-vault/\"\
  \ }\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/json-ld/keda-context.jsonld
tags:
- Autoscaling
- CNCF
- Event-Driven
- Graduated
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
