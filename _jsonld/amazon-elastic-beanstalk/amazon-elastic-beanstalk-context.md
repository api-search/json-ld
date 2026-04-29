---
class_count: 0
classes: []
context_file: json-ld/amazon-elastic-beanstalk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-beanstalk/refs/heads/main/json-ld/amazon-elastic-beanstalk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Elastic Beanstalk from Amazon Elastic Beanstalk.
layout: jsonld
name: Amazon Elastic Beanstalk Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/elasticbeanstalk/
- prefix: eb
  uri: https://docs.aws.amazon.com/elasticbeanstalk/latest/api/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Environment
  type: SoftwareApplication
- container: ''
  name: Application
  type: SoftwareApplication
- container: ''
  name: Tier
  type: Thing
property_count: 3
provider_name: Amazon Elastic Beanstalk
provider_slug: amazon-elastic-beanstalk
slug: amazon-elastic-beanstalk-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/elasticbeanstalk/\",\n    \"eb\": \"https://docs.aws.amazon.com/elasticbeanstalk/latest/api/\",\n    \"Environment\": {\n      \"@id\": \"aws:Environment\",\n      \"@type\": \"SoftwareApplication\",\n      \"@context\": {\n        \"EnvironmentId\": {\n          \"@id\": \"aws:EnvironmentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EnvironmentName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EnvironmentArn\": {\n          \"@id\": \"aws:EnvironmentArn\",\n          \"@type\": \"@id\"\n        },\n        \"ApplicationName\": {\n          \"@id\": \"aws:ApplicationName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"VersionLabel\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SolutionStackName\": {\n          \"@id\":\
  \ \"aws:SolutionStackName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PlatformArn\": {\n          \"@id\": \"aws:PlatformArn\",\n          \"@type\": \"@id\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EndpointURL\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"CNAME\": {\n          \"@id\": \"aws:CNAME\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"DateUpdated\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Status\": {\n          \"@id\": \"schema:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Health\": {\n          \"@id\": \"aws:Health\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  HealthStatus\": {\n          \"@id\": \"aws:HealthStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Application\": {\n      \"@id\": \"aws:Application\",\n      \"@type\": \"SoftwareApplication\",\n      \"@context\": {\n        \"ApplicationArn\": {\n          \"@id\": \"aws:ApplicationArn\",\n          \"@type\": \"@id\"\n        },\n        \"ApplicationName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"DateUpdated\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Versions\": {\n          \"@id\": \"aws:Versions\",\n          \"@type\": \"@id\"\n        },\n        \"ConfigurationTemplates\": {\n\
  \          \"@id\": \"aws:ConfigurationTemplates\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Tier\": {\n      \"@id\": \"aws:Tier\",\n      \"@type\": \"Thing\",\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Type\": {\n          \"@id\": \"aws:TierType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Version\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-beanstalk/refs/heads/main/json-ld/amazon-elastic-beanstalk-context.jsonld
tags:
- Amazon Web Services
- AWS
- Auto Scaling
- Deployment
- Elastic Beanstalk
- PaaS
- Platform As A Service
- Web Applications
- JSON-LD
- Linked Data
- Semantic Web
---
