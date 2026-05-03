---
api_specs:
- filename: openstack-keystone-openapi.yml
  format: yaml
  label: OpenStack Identity (Keystone) API
  slug: keystone
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-keystone-openapi.yml
- filename: openstack-nova-openapi.yml
  format: yaml
  label: OpenStack Compute (Nova) API
  slug: nova
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-nova-openapi.yml
class_count: 6
classes:
- id
- name
- description
- created
- updated
- url
context_file: json-ld/openstack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openstack from OpenStack.
layout: jsonld
name: Openstack Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Server
  uri: https://openstack.org/ns#Server
- prefix: Flavor
  uri: https://openstack.org/ns#Flavor
- prefix: Image
  uri: https://openstack.org/ns#Image
- prefix: Project
  uri: https://openstack.org/ns#Project
- prefix: User
  uri: https://openstack.org/ns#User
- prefix: Domain
  uri: https://openstack.org/ns#Domain
- prefix: Token
  uri: https://openstack.org/ns#Token
- prefix: Endpoint
  uri: https://openstack.org/ns#Endpoint
- prefix: Service
  uri: https://openstack.org/ns#Service
- prefix: Volume
  uri: https://openstack.org/ns#Volume
- prefix: Network
  uri: https://openstack.org/ns#Network
- prefix: status
  uri: https://openstack.org/ns#status
- prefix: tenant_id
  uri: https://openstack.org/ns#tenantId
- prefix: user_id
  uri: https://openstack.org/ns#userId
- prefix: domain_id
  uri: https://openstack.org/ns#domainId
- prefix: project_id
  uri: https://openstack.org/ns#projectId
- prefix: flavor
  uri: https://openstack.org/ns#flavor
- prefix: image
  uri: https://openstack.org/ns#image
- prefix: addresses
  uri: https://openstack.org/ns#addresses
- prefix: key_name
  uri: https://openstack.org/ns#keyName
- prefix: security_groups
  uri: https://openstack.org/ns#securityGroups
- prefix: metadata
  uri: https://openstack.org/ns#metadata
- prefix: expires_at
  uri: https://openstack.org/ns#expiresAt
- prefix: issued_at
  uri: https://openstack.org/ns#issuedAt
- prefix: catalog
  uri: https://openstack.org/ns#catalog
- prefix: endpoints
  uri: https://openstack.org/ns#endpoints
- prefix: interface
  uri: https://openstack.org/ns#interface
- prefix: region
  uri: https://openstack.org/ns#region
properties: []
property_count: 0
provider_name: OpenStack
provider_slug: openstack
slug: openstack-context
source_filename: openstack-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://openstack.org/ns#\",\n    \"schema\": \"https://schema.org/\",\n    \"Server\": \"https://openstack.org/ns#Server\",\n    \"Flavor\": \"https://openstack.org/ns#Flavor\",\n    \"Image\": \"https://openstack.org/ns#Image\",\n    \"Project\": \"https://openstack.org/ns#Project\",\n    \"User\": \"https://openstack.org/ns#User\",\n    \"Domain\": \"https://openstack.org/ns#Domain\",\n    \"Token\": \"https://openstack.org/ns#Token\",\n    \"Endpoint\": \"https://openstack.org/ns#Endpoint\",\n    \"Service\": \"https://openstack.org/ns#Service\",\n    \"Volume\": \"https://openstack.org/ns#Volume\",\n    \"Network\": \"https://openstack.org/ns#Network\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"https://openstack.org/ns#status\",\n    \"tenant_id\": \"https://openstack.org/ns#tenantId\",\n    \"user_id\": \"https://openstack.org/ns#userId\",\n    \"domain_id\"\
  : \"https://openstack.org/ns#domainId\",\n    \"project_id\": \"https://openstack.org/ns#projectId\",\n    \"flavor\": \"https://openstack.org/ns#flavor\",\n    \"image\": \"https://openstack.org/ns#image\",\n    \"addresses\": \"https://openstack.org/ns#addresses\",\n    \"key_name\": \"https://openstack.org/ns#keyName\",\n    \"security_groups\": \"https://openstack.org/ns#securityGroups\",\n    \"metadata\": \"https://openstack.org/ns#metadata\",\n    \"created\": \"schema:dateCreated\",\n    \"updated\": \"schema:dateModified\",\n    \"expires_at\": \"https://openstack.org/ns#expiresAt\",\n    \"issued_at\": \"https://openstack.org/ns#issuedAt\",\n    \"catalog\": \"https://openstack.org/ns#catalog\",\n    \"endpoints\": \"https://openstack.org/ns#endpoints\",\n    \"interface\": \"https://openstack.org/ns#interface\",\n    \"region\": \"https://openstack.org/ns#region\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld
tags:
- Cloud Platform
- Infrastructure as a Service
- Open Source
- Virtualization
- Linux Foundation
- JSON-LD
- Linked Data
- Semantic Web
---
