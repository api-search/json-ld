---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: AWS EC2 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/ec2/2016-11-15/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: AWS VPC API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/ec2/2016-11-15/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: AWS EKS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/eks/2018-08-23/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Google Compute Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/compute/v1/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Google Kubernetes Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/container/v1/openapi.yaml
- filename: resources.json
  format: json
  label: Azure Resource Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/resources/resource-manager/Microsoft.Resources/stable/2023-07-01/resources.json
- filename: managedClusters.json
  format: json
  label: Azure AKS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/containerservice/resource-manager/Microsoft.ContainerService/aks/stable/2024-01-01/managedClusters.json
- filename: DigitalOcean-public.v2.yaml
  format: yaml
  label: DigitalOcean API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/digitalocean/openapi/main/specification/DigitalOcean-public.v2.yaml
class_count: 21
classes:
- id
- name
- description
- provider
- region
- availabilityZone
- status
- type
- cpu
- memory
- storage
- networking
- gpu
- tags
- vpcId
- subnetId
- privateIp
- publicIp
- securityGroups
- createdAt
- terminatedAt
context_file: json-ld/scalable-infrastructure-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/json-ld/scalable-infrastructure-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Infrastructure from Scalable Infrastructure.
layout: jsonld
name: Scalable Infrastructure Context
namespaces:
- prefix: infra
  uri: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-ld/scalable-infrastructure-context.jsonld#
- prefix: aws
  uri: https://docs.aws.amazon.com/ns/
- prefix: k8s
  uri: https://kubernetes.io/ns/
properties:
- container: ''
  name: ComputeInstance
  type: reference
- container: ''
  name: VirtualPrivateCloud
  type: reference
- container: ''
  name: ManagedKubernetesCluster
  type: reference
- container: ''
  name: StorageVolume
  type: reference
- container: ''
  name: InfrastructureStack
  type: reference
- container: ''
  name: LoadBalancer
  type: reference
property_count: 6
provider_name: Scalable Infrastructure
provider_slug: scalable-infrastructure
slug: scalable-infrastructure-context
source_filename: scalable-infrastructure-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"infra\": \"https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-ld/scalable-infrastructure-context.jsonld#\",\n    \"aws\": \"https://docs.aws.amazon.com/ns/\",\n    \"k8s\": \"https://kubernetes.io/ns/\",\n\n    \"ComputeInstance\": {\n      \"@id\": \"infra:ComputeInstance\",\n      \"@type\": \"@id\",\n      \"comment\": \"A cloud virtual machine instance (EC2, GCE, Azure VM, Droplet).\"\n    },\n    \"VirtualPrivateCloud\": {\n      \"@id\": \"infra:VirtualPrivateCloud\",\n      \"@type\": \"@id\",\n      \"comment\": \"An isolated virtual network within a cloud provider.\"\n    },\n    \"ManagedKubernetesCluster\": {\n      \"@id\": \"infra:ManagedKubernetesCluster\",\n      \"@type\": \"@id\",\n      \"comment\": \"A provider-managed Kubernetes control plane and worker node pool.\"\n    },\n    \"StorageVolume\": {\n      \"@id\": \"infra:StorageVolume\"\
  ,\n      \"@type\": \"@id\",\n      \"comment\": \"A block storage volume attachable to compute instances.\"\n    },\n    \"InfrastructureStack\": {\n      \"@id\": \"infra:InfrastructureStack\",\n      \"@type\": \"@id\",\n      \"comment\": \"A named collection of infrastructure resources managed as a unit via IaC.\"\n    },\n    \"LoadBalancer\": {\n      \"@id\": \"infra:LoadBalancer\",\n      \"@type\": \"@id\",\n      \"comment\": \"A cloud load balancer distributing traffic across compute instances.\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"provider\": \"infra:provider\",\n    \"region\": \"infra:region\",\n    \"availabilityZone\": \"infra:availabilityZone\",\n    \"status\": \"schema:status\",\n    \"type\": \"schema:additionalType\",\n    \"cpu\": \"infra:cpu\",\n    \"memory\": \"infra:memory\",\n    \"storage\": \"infra:storage\",\n    \"networking\": \"infra:networking\",\n    \"gpu\": \"infra:gpu\"\
  ,\n    \"tags\": \"schema:keywords\",\n    \"vpcId\": \"infra:vpcId\",\n    \"subnetId\": \"infra:subnetId\",\n    \"privateIp\": \"infra:privateIp\",\n    \"publicIp\": \"schema:ipAddress\",\n    \"securityGroups\": \"infra:securityGroups\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"terminatedAt\": \"schema:endDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/json-ld/scalable-infrastructure-context.jsonld
tags:
- Cloud Infrastructure
- Compute
- DevOps
- Infrastructure as Code
- Kubernetes
- Networking
- Scalability
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
