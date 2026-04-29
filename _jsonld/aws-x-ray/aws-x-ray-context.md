---
api_specs:
- filename: aws-x-ray-openapi.yml
  format: yaml
  label: AWS X-Ray
  slug: aws-x-ray
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-x-ray/refs/heads/main/openapi/aws-x-ray-openapi.yml
class_count: 19
classes:
- BatchGetTracesResult
- Trace
- GetTraceSummariesResult
- TraceSummary
- ServiceId
- GetServiceGraphResult
- Service
- EdgeStatistics
- ServiceStatistics
- HistogramEntry
- TimeSeriesServiceStatistics
- Group
- GroupSummary
- SamplingRule
- SamplingRuleRecord
- EncryptionConfig
- InsightSummary
- Insight
- Tag
context_file: json-ld/aws-x-ray-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-x-ray/refs/heads/main/json-ld/aws-x-ray-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws X Ray from AWS X-Ray.
layout: jsonld
name: Aws X Ray Context
namespaces:
- prefix: xray
  uri: https://docs.aws.amazon.com/xray/latest/api/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: AWS X-Ray
provider_slug: aws-x-ray
slug: aws-x-ray-context
source_filename: aws-x-ray-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xray\": \"https://docs.aws.amazon.com/xray/latest/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchGetTracesResult\": \"xray:BatchGetTracesResult\",\n    \"Trace\": \"xray:Trace\",\n    \"GetTraceSummariesResult\": \"xray:GetTraceSummariesResult\",\n    \"TraceSummary\": \"xray:TraceSummary\",\n    \"ServiceId\": \"xray:ServiceId\",\n    \"GetServiceGraphResult\": \"xray:GetServiceGraphResult\",\n    \"Service\": \"xray:Service\",\n    \"EdgeStatistics\": \"xray:EdgeStatistics\",\n    \"ServiceStatistics\": \"xray:ServiceStatistics\",\n    \"HistogramEntry\": \"xray:HistogramEntry\",\n    \"TimeSeriesServiceStatistics\": \"xray:TimeSeriesServiceStatistics\",\n    \"Group\": \"xray:Group\",\n    \"GroupSummary\": \"xray:GroupSummary\",\n    \"SamplingRule\": \"xray:SamplingRule\",\n    \"SamplingRuleRecord\": \"xray:SamplingRuleRecord\",\n    \"EncryptionConfig\"\
  : \"xray:EncryptionConfig\",\n    \"InsightSummary\": \"xray:InsightSummary\",\n    \"Insight\": \"xray:Insight\",\n    \"Tag\": \"xray:Tag\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-x-ray/refs/heads/main/json-ld/aws-x-ray-context.jsonld
tags:
- AWS
- Debugging
- Distributed Tracing
- Microservices
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
