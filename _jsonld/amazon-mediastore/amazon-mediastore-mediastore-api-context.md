---
api_specs:
- filename: amazon-mediastore-openapi-original.yml
  format: yaml
  label: Amazon MediaStore API
  slug: mediastore-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/openapi/amazon-mediastore-openapi-original.yml
class_count: 83
classes:
- Origin
- MaxAgeSeconds
- PolicyNotFoundException
- AllowedHeaders
- TimeStamp
- InternalServerError
- ContainerNotFoundException
- MethodName
- PaginationToken
- TagResourceOutput
- Tag
- DescribeContainerOutput
- Header
- ListContainersInput
- MetricPolicy
- TagValue
- TagKey
- GetMetricPolicyInput
- PutMetricPolicyOutput
- DeleteLifecyclePolicyOutput
- StopAccessLoggingOutput
- DeleteContainerPolicyOutput
- PutLifecyclePolicyInput
- TagList
- DeleteContainerInput
- ListTagsForResourceInput
- ContainerName
- ContainerAccessLoggingEnabled
- ContainerList
- GetMetricPolicyOutput
- CorsPolicy
- ListTagsForResourceOutput
- LimitExceededException
- ContainerStatus
- CorsPolicyNotFoundException
- CorsRule
- DeleteCorsPolicyOutput
- GetContainerPolicyOutput
- GetLifecyclePolicyOutput
- PutContainerPolicyInput
- DeleteContainerOutput
- GetCorsPolicyInput
- DeleteLifecyclePolicyInput
- PutCorsPolicyOutput
- ContainerListLimit
- PutCorsPolicyInput
- LifecyclePolicy
- ExposeHeaders
- DeleteMetricPolicyOutput
- MetricPolicyRule
- StopAccessLoggingInput
- AllowedOrigins
- AllowedMethods
- DeleteMetricPolicyInput
- DeleteCorsPolicyInput
- MetricPolicyRules
- CreateContainerOutput
- GetLifecyclePolicyInput
- UntagResourceInput
- StartAccessLoggingOutput
- GetCorsPolicyOutput
- ListContainersOutput
- PutLifecyclePolicyOutput
- PutContainerPolicyOutput
- Endpoint
- DeleteContainerPolicyInput
- ContainerPolicy
- PutMetricPolicyInput
- CreateContainerInput
- DescribeContainerInput
- TagResourceInput
- ContainerLevelMetrics
- Container
- ContainerInUseException
- UntagResourceOutput
- ObjectGroupName
- StartAccessLoggingInput
- TagKeyList
- ObjectGroup
- ContainerARN
- GetContainerPolicyInput
- creationTime
- name
context_file: json-ld/amazon-mediastore-mediastore-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/json-ld/amazon-mediastore-mediastore-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Mediastore Mediastore Api from Amazon MediaStore.
layout: jsonld
name: Amazon Mediastore Mediastore Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: container
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: containerLevelMetrics
  type: string
- container: ''
  name: metricPolicyRules
  type: string
- container: ''
  name: containerName
  type: string
- container: ''
  name: lifecyclePolicy
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: metricPolicy
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: allowedOrigins
  type: string
- container: ''
  name: allowedMethods
  type: string
- container: ''
  name: allowedHeaders
  type: string
- container: ''
  name: maxAgeSeconds
  type: string
- container: ''
  name: exposeHeaders
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: corsPolicy
  type: string
- container: ''
  name: objectGroup
  type: string
- container: ''
  name: objectGroupName
  type: string
- container: ''
  name: tagKeys
  type: string
- container: ''
  name: containers
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: accessLoggingEnabled
  type: string
property_count: 27
provider_name: Amazon MediaStore
provider_slug: amazon-mediastore
slug: amazon-mediastore-mediastore-api-context
source_filename: amazon-mediastore-mediastore-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Origin\": \"pan:Origin\",\n    \"MaxAgeSeconds\": \"pan:MaxAgeSeconds\",\n    \"PolicyNotFoundException\": \"pan:PolicyNotFoundException\",\n    \"AllowedHeaders\": \"pan:AllowedHeaders\",\n    \"TimeStamp\": \"pan:TimeStamp\",\n    \"InternalServerError\": \"pan:InternalServerError\",\n    \"ContainerNotFoundException\": \"pan:ContainerNotFoundException\",\n    \"MethodName\": \"pan:MethodName\",\n    \"PaginationToken\": \"pan:PaginationToken\",\n    \"TagResourceOutput\": \"pan:TagResourceOutput\",\n    \"Tag\": \"pan:Tag\",\n    \"DescribeContainerOutput\": \"pan:DescribeContainerOutput\",\n    \"Header\": \"pan:Header\",\n    \"ListContainersInput\": \"pan:ListContainersInput\",\n    \"MetricPolicy\": \"pan:MetricPolicy\",\n    \"TagValue\"\
  : \"pan:TagValue\",\n    \"TagKey\": \"pan:TagKey\",\n    \"GetMetricPolicyInput\": \"pan:GetMetricPolicyInput\",\n    \"PutMetricPolicyOutput\": \"pan:PutMetricPolicyOutput\",\n    \"DeleteLifecyclePolicyOutput\": \"pan:DeleteLifecyclePolicyOutput\",\n    \"StopAccessLoggingOutput\": \"pan:StopAccessLoggingOutput\",\n    \"DeleteContainerPolicyOutput\": \"pan:DeleteContainerPolicyOutput\",\n    \"PutLifecyclePolicyInput\": \"pan:PutLifecyclePolicyInput\",\n    \"TagList\": \"pan:TagList\",\n    \"DeleteContainerInput\": \"pan:DeleteContainerInput\",\n    \"ListTagsForResourceInput\": \"pan:ListTagsForResourceInput\",\n    \"ContainerName\": \"pan:ContainerName\",\n    \"ContainerAccessLoggingEnabled\": \"pan:ContainerAccessLoggingEnabled\",\n    \"ContainerList\": \"pan:ContainerList\",\n    \"GetMetricPolicyOutput\": \"pan:GetMetricPolicyOutput\",\n    \"CorsPolicy\": \"pan:CorsPolicy\",\n    \"ListTagsForResourceOutput\": \"pan:ListTagsForResourceOutput\",\n    \"LimitExceededException\"\
  : \"pan:LimitExceededException\",\n    \"ContainerStatus\": \"pan:ContainerStatus\",\n    \"CorsPolicyNotFoundException\": \"pan:CorsPolicyNotFoundException\",\n    \"CorsRule\": \"pan:CorsRule\",\n    \"DeleteCorsPolicyOutput\": \"pan:DeleteCorsPolicyOutput\",\n    \"GetContainerPolicyOutput\": \"pan:GetContainerPolicyOutput\",\n    \"GetLifecyclePolicyOutput\": \"pan:GetLifecyclePolicyOutput\",\n    \"PutContainerPolicyInput\": \"pan:PutContainerPolicyInput\",\n    \"DeleteContainerOutput\": \"pan:DeleteContainerOutput\",\n    \"GetCorsPolicyInput\": \"pan:GetCorsPolicyInput\",\n    \"DeleteLifecyclePolicyInput\": \"pan:DeleteLifecyclePolicyInput\",\n    \"PutCorsPolicyOutput\": \"pan:PutCorsPolicyOutput\",\n    \"ContainerListLimit\": \"pan:ContainerListLimit\",\n    \"PutCorsPolicyInput\": \"pan:PutCorsPolicyInput\",\n    \"LifecyclePolicy\": \"pan:LifecyclePolicy\",\n    \"ExposeHeaders\": \"pan:ExposeHeaders\",\n    \"DeleteMetricPolicyOutput\": \"pan:DeleteMetricPolicyOutput\",\n\
  \    \"MetricPolicyRule\": \"pan:MetricPolicyRule\",\n    \"StopAccessLoggingInput\": \"pan:StopAccessLoggingInput\",\n    \"AllowedOrigins\": \"pan:AllowedOrigins\",\n    \"AllowedMethods\": \"pan:AllowedMethods\",\n    \"DeleteMetricPolicyInput\": \"pan:DeleteMetricPolicyInput\",\n    \"DeleteCorsPolicyInput\": \"pan:DeleteCorsPolicyInput\",\n    \"MetricPolicyRules\": \"pan:MetricPolicyRules\",\n    \"CreateContainerOutput\": \"pan:CreateContainerOutput\",\n    \"GetLifecyclePolicyInput\": \"pan:GetLifecyclePolicyInput\",\n    \"UntagResourceInput\": \"pan:UntagResourceInput\",\n    \"StartAccessLoggingOutput\": \"pan:StartAccessLoggingOutput\",\n    \"GetCorsPolicyOutput\": \"pan:GetCorsPolicyOutput\",\n    \"ListContainersOutput\": \"pan:ListContainersOutput\",\n    \"PutLifecyclePolicyOutput\": \"pan:PutLifecyclePolicyOutput\",\n    \"PutContainerPolicyOutput\": \"pan:PutContainerPolicyOutput\",\n    \"Endpoint\": \"pan:Endpoint\",\n    \"DeleteContainerPolicyInput\": \"pan:DeleteContainerPolicyInput\"\
  ,\n    \"ContainerPolicy\": \"pan:ContainerPolicy\",\n    \"PutMetricPolicyInput\": \"pan:PutMetricPolicyInput\",\n    \"CreateContainerInput\": \"pan:CreateContainerInput\",\n    \"DescribeContainerInput\": \"pan:DescribeContainerInput\",\n    \"TagResourceInput\": \"pan:TagResourceInput\",\n    \"ContainerLevelMetrics\": \"pan:ContainerLevelMetrics\",\n    \"Container\": \"pan:Container\",\n    \"ContainerInUseException\": \"pan:ContainerInUseException\",\n    \"UntagResourceOutput\": \"pan:UntagResourceOutput\",\n    \"ObjectGroupName\": \"pan:ObjectGroupName\",\n    \"StartAccessLoggingInput\": \"pan:StartAccessLoggingInput\",\n    \"TagKeyList\": \"pan:TagKeyList\",\n    \"ObjectGroup\": \"pan:ObjectGroup\",\n    \"ContainerARN\": \"pan:ContainerARN\",\n    \"GetContainerPolicyInput\": \"pan:GetContainerPolicyInput\",\n    \"key\": {\n      \"@id\": \"pan:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"container\": {\n      \"@id\": \"pan:container\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"pan:max_results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerLevelMetrics\": {\n      \"@id\": \"pan:container_level_metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricPolicyRules\": {\n      \"@id\": \"pan:metric_policy_rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerName\": {\n      \"@id\": \"pan:container_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecyclePolicy\": {\n      \"@id\": \"pan:lifecycle_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"pan:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricPolicy\": {\n      \"@id\": \"pan:metric_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"\
  pan:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedOrigins\": {\n      \"@id\": \"pan:allowed_origins\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedMethods\": {\n      \"@id\": \"pan:allowed_methods\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedHeaders\": {\n      \"@id\": \"pan:allowed_headers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAgeSeconds\": {\n      \"@id\": \"pan:max_age_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exposeHeaders\": {\n      \"@id\": \"pan:expose_headers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"pan:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"corsPolicy\": {\n      \"@id\": \"pan:cors_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectGroup\": {\n      \"@id\": \"pan:object_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectGroupName\": {\n      \"@id\": \"pan:object_group_name\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"tagKeys\": {\n      \"@id\": \"pan:tag_keys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containers\": {\n      \"@id\": \"pan:containers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"pan:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": \"schema:dateCreated\",\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessLoggingEnabled\": {\n      \"@id\": \"pan:access_logging_enabled\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/json-ld/amazon-mediastore-mediastore-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
