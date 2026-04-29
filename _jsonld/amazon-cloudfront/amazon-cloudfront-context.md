---
api_specs:
- filename: amazon-cloudfront-openapi.yml
  format: yaml
  label: Amazon CloudFront API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/openapi/amazon-cloudfront-openapi.yml
class_count: 8
classes:
- Distribution
- DistributionConfig
- Origin
- CacheBehavior
- Invalidation
- InvalidationBatch
- DistributionList
- InvalidationList
context_file: json-ld/amazon-cloudfront-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/json-ld/amazon-cloudfront-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloudfront from Amazon CloudFront.
layout: jsonld
name: Amazon Cloudfront Context
namespaces:
- prefix: cloudfront
  uri: https://aws.amazon.com/cloudfront/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: aRN
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: lastModifiedTime
  type: dateTime
- container: ''
  name: domainName
  type: string
- container: ''
  name: distributionConfig
  type: string
- container: ''
  name: callerReference
  type: string
- container: ''
  name: aliases
  type: string
- container: ''
  name: defaultRootObject
  type: string
- container: ''
  name: origins
  type: string
- container: ''
  name: defaultCacheBehavior
  type: string
- container: ''
  name: cacheBehaviors
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: priceClass
  type: string
- container: ''
  name: viewerCertificate
  type: string
- container: ''
  name: webACLId
  type: string
- container: ''
  name: httpVersion
  type: string
- container: ''
  name: isIPV6Enabled
  type: boolean
- container: ''
  name: originPath
  type: string
- container: ''
  name: s3OriginConfig
  type: string
- container: ''
  name: customOriginConfig
  type: string
- container: ''
  name: pathPattern
  type: string
- container: ''
  name: targetOriginId
  type: string
- container: ''
  name: viewerProtocolPolicy
  type: string
- container: ''
  name: allowedMethods
  type: string
- container: ''
  name: cachePolicyId
  type: string
- container: ''
  name: originRequestPolicyId
  type: string
- container: ''
  name: compress
  type: boolean
- container: ''
  name: functionAssociations
  type: string
- container: ''
  name: lambdaFunctionAssociations
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: invalidationBatch
  type: string
- container: ''
  name: paths
  type: string
- container: ''
  name: marker
  type: string
- container: ''
  name: nextMarker
  type: string
- container: ''
  name: maxItems
  type: integer
- container: ''
  name: isTruncated
  type: boolean
- container: ''
  name: quantity
  type: integer
- container: set
  name: items
  type: string
property_count: 40
provider_name: Amazon CloudFront
provider_slug: amazon-cloudfront
slug: amazon-cloudfront-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudfront\": \"https://aws.amazon.com/cloudfront/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Distribution\": \"cloudfront:Distribution\",\n    \"id\": {\n      \"@id\": \"cloudfront:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aRN\": {\n      \"@id\": \"cloudfront:a_r_n\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"cloudfront:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedTime\": {\n      \"@id\": \"cloudfront:last_modified_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"domainName\": {\n      \"@id\": \"cloudfront:domain_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distributionConfig\": {\n      \"@id\": \"cloudfront:distribution_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DistributionConfig\": \"cloudfront:DistributionConfig\"\
  ,\n    \"callerReference\": {\n      \"@id\": \"cloudfront:caller_reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aliases\": {\n      \"@id\": \"cloudfront:aliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultRootObject\": {\n      \"@id\": \"cloudfront:default_root_object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origins\": {\n      \"@id\": \"cloudfront:origins\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultCacheBehavior\": {\n      \"@id\": \"cloudfront:default_cache_behavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cacheBehaviors\": {\n      \"@id\": \"cloudfront:cache_behaviors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"cloudfront:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"cloudfront:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"priceClass\": {\n      \"@id\": \"cloudfront:price_class\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"viewerCertificate\": {\n      \"@id\": \"cloudfront:viewer_certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webACLId\": {\n      \"@id\": \"cloudfront:web_a_c_l_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpVersion\": {\n      \"@id\": \"cloudfront:http_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isIPV6Enabled\": {\n      \"@id\": \"cloudfront:is_i_p_v6_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Origin\": \"cloudfront:Origin\",\n    \"originPath\": {\n      \"@id\": \"cloudfront:origin_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3OriginConfig\": {\n      \"@id\": \"cloudfront:s3_origin_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customOriginConfig\": {\n      \"@id\": \"cloudfront:custom_origin_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CacheBehavior\": \"cloudfront:CacheBehavior\",\n    \"pathPattern\": {\n      \"@id\": \"cloudfront:path_pattern\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"targetOriginId\": {\n      \"@id\": \"cloudfront:target_origin_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"viewerProtocolPolicy\": {\n      \"@id\": \"cloudfront:viewer_protocol_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedMethods\": {\n      \"@id\": \"cloudfront:allowed_methods\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cachePolicyId\": {\n      \"@id\": \"cloudfront:cache_policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originRequestPolicyId\": {\n      \"@id\": \"cloudfront:origin_request_policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compress\": {\n      \"@id\": \"cloudfront:compress\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"functionAssociations\": {\n      \"@id\": \"cloudfront:function_associations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionAssociations\": {\n      \"@id\": \"cloudfront:lambda_function_associations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Invalidation\"\
  : \"cloudfront:Invalidation\",\n    \"createTime\": {\n      \"@id\": \"cloudfront:create_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"invalidationBatch\": {\n      \"@id\": \"cloudfront:invalidation_batch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvalidationBatch\": \"cloudfront:InvalidationBatch\",\n    \"paths\": {\n      \"@id\": \"cloudfront:paths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DistributionList\": \"cloudfront:DistributionList\",\n    \"marker\": {\n      \"@id\": \"cloudfront:marker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextMarker\": {\n      \"@id\": \"cloudfront:next_marker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxItems\": {\n      \"@id\": \"cloudfront:max_items\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isTruncated\": {\n      \"@id\": \"cloudfront:is_truncated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"quantity\": {\n      \"@id\": \"cloudfront:quantity\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"items\": {\n      \"@id\": \"cloudfront:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvalidationList\": \"cloudfront:InvalidationList\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/json-ld/amazon-cloudfront-context.jsonld
tags:
- AWS
- CloudFront
- CDN
- Content Delivery
- Edge
- JSON-LD
- Linked Data
- Semantic Web
---
