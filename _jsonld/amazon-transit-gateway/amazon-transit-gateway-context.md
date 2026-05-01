---
api_specs:
- filename: amazon-transit-gateway-openapi.yml
  format: yaml
  label: Amazon Transit Gateway REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/openapi/amazon-transit-gateway-openapi.yml
class_count: 7
classes:
- name
- description
- url
- identifier
- dateCreated
- dateModified
- status
context_file: json-ld/amazon-transit-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/json-ld/amazon-transit-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Transit Gateway from Amazon Transit Gateway.
layout: jsonld
name: Amazon Transit Gateway Context
namespaces:
- prefix: ec2
  uri: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
properties:
- container: ''
  name: provider
  type: schema:Organization
- container: ''
  name: TransitGateway
  type: ''
- container: ''
  name: TransitGatewayAttachment
  type: ''
- container: ''
  name: TransitGatewayRouteTable
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 5
provider_name: Amazon Transit Gateway
provider_slug: amazon-transit-gateway
slug: amazon-transit-gateway-context
source_filename: amazon-transit-gateway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ec2\": \"https://docs.aws.amazon.com/AWSEC2/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"status\": \"schema:status\",\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"TransitGateway\": {\n      \"@id\": \"ec2:API_CreateTransitGateway.html\",\n      \"@context\": {\n        \"TransitGatewayId\": \"schema:identifier\",\n        \"TransitGatewayArn\": \"schema:identifier\",\n        \"State\": \"schema:status\",\n        \"Description\": \"schema:description\",\n        \"OwnerId\": \"ec2:OwnerId\",\n        \"CreationTime\": \"schema:dateCreated\"\n      }\n    },\n    \"\
  TransitGatewayAttachment\": {\n      \"@id\": \"ec2:API_CreateTransitGatewayVpcAttachment.html\",\n      \"@context\": {\n        \"TransitGatewayAttachmentId\": \"schema:identifier\",\n        \"TransitGatewayId\": \"ec2:TransitGatewayId\",\n        \"VpcId\": \"ec2:VpcId\",\n        \"State\": \"schema:status\",\n        \"CreationTime\": \"schema:dateCreated\"\n      }\n    },\n    \"TransitGatewayRouteTable\": {\n      \"@id\": \"ec2:API_CreateTransitGatewayRouteTable.html\",\n      \"@context\": {\n        \"TransitGatewayRouteTableId\": \"schema:identifier\",\n        \"TransitGatewayId\": \"ec2:TransitGatewayId\",\n        \"State\": \"schema:status\",\n        \"CreationTime\": \"schema:dateCreated\"\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"ec2:Tag\",\n      \"@context\": {\n        \"Key\": \"schema:name\",\n        \"Value\": \"schema:value\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/json-ld/amazon-transit-gateway-context.jsonld
tags:
- Cloud Networking
- Network Hub
- Networking
- Transit Gateway
- VPC
- JSON-LD
- Linked Data
- Semantic Web
---
