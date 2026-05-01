---
api_specs:
- filename: amazon-elastic-load-balancing-openapi.yml
  format: yaml
  label: Elastic Load Balancing v2 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-load-balancing/refs/heads/main/openapi/amazon-elastic-load-balancing-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-elastic-load-balancing-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-load-balancing/refs/heads/main/json-ld/amazon-elastic-load-balancing-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Elastic Load Balancing from Amazon Elastic Load Balancing.
layout: jsonld
name: Amazon Elastic Load Balancing Context
namespaces:
- prefix: elb
  uri: https://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: LoadBalancer
  type: ''
- container: ''
  name: TargetGroup
  type: ''
- container: ''
  name: Listener
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: Action
  type: ''
- container: ''
  name: TargetHealth
  type: ''
property_count: 6
provider_name: Amazon Elastic Load Balancing
provider_slug: amazon-elastic-load-balancing
slug: amazon-elastic-load-balancing-context
source_filename: amazon-elastic-load-balancing-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"elb\": \"https://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"LoadBalancer\": {\n      \"@id\": \"elb:LoadBalancer\",\n      \"@context\": {\n        \"loadBalancerArn\": \"elb:loadBalancerArn\",\n        \"loadBalancerName\": \"schema:name\",\n        \"dnsName\": \"elb:dnsName\",\n        \"canonicalHostedZoneId\": \"elb:canonicalHostedZoneId\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"scheme\": \"elb:scheme\",\n        \"vpcId\": \"elb:vpcId\",\n        \"state\": \"elb:state\",\n        \"type\": \"elb:type\",\n        \"ipAddressType\": \"elb:ipAddressType\",\n        \"availabilityZones\": {\n          \"@id\": \"elb:availabilityZones\",\n          \"@container\"\
  : \"@set\"\n        },\n        \"securityGroups\": {\n          \"@id\": \"elb:securityGroups\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"elb:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TargetGroup\": {\n      \"@id\": \"elb:TargetGroup\",\n      \"@context\": {\n        \"targetGroupArn\": \"elb:targetGroupArn\",\n        \"targetGroupName\": \"schema:name\",\n        \"protocol\": \"elb:protocol\",\n        \"port\": \"elb:port\",\n        \"vpcId\": \"elb:vpcId\",\n        \"targetType\": \"elb:targetType\",\n        \"healthCheckEnabled\": \"elb:healthCheckEnabled\",\n        \"healthCheckProtocol\": \"elb:healthCheckProtocol\",\n        \"healthCheckPort\": \"elb:healthCheckPort\",\n        \"healthCheckPath\": \"elb:healthCheckPath\",\n        \"healthyThresholdCount\": \"elb:healthyThresholdCount\",\n        \"unhealthyThresholdCount\": \"elb:unhealthyThresholdCount\",\n        \"loadBalancerArns\"\
  : {\n          \"@id\": \"elb:loadBalancerArns\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Listener\": {\n      \"@id\": \"elb:Listener\",\n      \"@context\": {\n        \"listenerArn\": \"elb:listenerArn\",\n        \"loadBalancerArn\": \"elb:loadBalancerArn\",\n        \"protocol\": \"elb:protocol\",\n        \"port\": \"elb:port\",\n        \"sslPolicy\": \"elb:sslPolicy\",\n        \"certificates\": {\n          \"@id\": \"elb:certificates\",\n          \"@container\": \"@set\"\n        },\n        \"defaultActions\": {\n          \"@id\": \"elb:defaultActions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Rule\": {\n      \"@id\": \"elb:Rule\",\n      \"@context\": {\n        \"ruleArn\": \"elb:ruleArn\",\n        \"priority\": \"elb:priority\",\n        \"isDefault\": \"elb:isDefault\",\n        \"conditions\": {\n          \"@id\": \"elb:conditions\",\n          \"@container\": \"@set\"\n        },\n        \"actions\"\
  : {\n          \"@id\": \"elb:actions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Action\": {\n      \"@id\": \"elb:Action\",\n      \"@context\": {\n        \"type\": \"elb:actionType\",\n        \"targetGroupArn\": \"elb:targetGroupArn\",\n        \"order\": \"elb:order\",\n        \"redirectConfig\": \"elb:redirectConfig\",\n        \"fixedResponseConfig\": \"elb:fixedResponseConfig\"\n      }\n    },\n\n    \"TargetHealth\": {\n      \"@id\": \"elb:TargetHealth\",\n      \"@context\": {\n        \"state\": \"elb:state\",\n        \"reason\": \"elb:reason\",\n        \"description\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-load-balancing/refs/heads/main/json-ld/amazon-elastic-load-balancing-context.jsonld
tags:
- Amazon Web Services
- High Availability
- Load Balancing
- Networking
- Scalability
- JSON-LD
- Linked Data
- Semantic Web
---
