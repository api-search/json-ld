---
api_specs:
- filename: adobe-analytics-api-openapi.yml
  format: yaml
  label: Adobe Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/openapi/adobe-analytics-api-openapi.yml
- filename: adobe-analytics-bulk-data-insertion-api-openapi.yml
  format: yaml
  label: Adobe Analytics Bulk Data Insertion API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/openapi/adobe-analytics-bulk-data-insertion-api-openapi.yml
- filename: adobe-analytics-livestream-asyncapi.yml
  format: yaml
  label: Adobe Analytics Livestream API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/asyncapi/adobe-analytics-livestream-asyncapi.yml
- filename: adobe-analytics-data-repair-api-openapi.yml
  format: yaml
  label: Adobe Analytics Data Repair API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/openapi/adobe-analytics-data-repair-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/adobe-analytics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/json-ld/adobe-analytics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Analytics from Adobe Analytics.
layout: jsonld
name: Adobe Analytics Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: ReportRequest
  type: ''
- container: ''
  name: ReportFilter
  type: ''
- container: ''
  name: MetricContainer
  type: ''
- container: ''
  name: ReportMetric
  type: ''
- container: ''
  name: ReportSettings
  type: ''
- container: ''
  name: ReportResponse
  type: ''
- container: ''
  name: ReportRow
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: SegmentCreate
  type: ''
- container: ''
  name: SegmentList
  type: ''
- container: ''
  name: CalculatedMetric
  type: ''
- container: ''
  name: CalculatedMetricCreate
  type: ''
- container: ''
  name: CalculatedMetricList
  type: ''
- container: ''
  name: Metric
  type: ''
- container: ''
  name: Dimension
  type: ''
- container: ''
  name: ReportSuite
  type: ''
- container: ''
  name: ReportSuiteList
  type: ''
- container: ''
  name: Annotation
  type: ''
- container: ''
  name: AnnotationCreate
  type: ''
- container: ''
  name: DateRange
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Owner
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 23
provider_name: Adobe Analytics
provider_slug: adobe-analytics
slug: adobe-analytics-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ReportRequest\": {\n      \"@id\": \"ns:ReportRequest\",\n      \"@context\": {\n        \"rsid\": {\n          \"@id\": \"ns:rsid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"locale\": {\n          \"@id\": \"ns:locale\",\n          \"@type\": \"xsd:string\"\n        },\n        \"globalFilters\": \"ns:globalFilters\",\n        \"metricContainer\": {\n          \"@id\": \"ns:metricContainer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dimension\": {\n          \"@id\": \"ns:dimension\",\n          \"@type\": \"xsd:string\"\n        },\n        \"settings\": {\n          \"@id\": \"ns:settings\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statistics\": \"ns:statistics\"\n      }\n    },\n    \"ReportFilter\": {\n      \"@id\": \"ns:ReportFilter\",\n      \"@context\": {\n     \
  \   \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateRange\": {\n          \"@id\": \"ns:dateRange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"segmentId\": {\n          \"@id\": \"ns:segmentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dimension\": {\n          \"@id\": \"ns:dimension\",\n          \"@type\": \"xsd:string\"\n        },\n        \"itemId\": {\n          \"@id\": \"ns:itemId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"MetricContainer\": {\n      \"@id\": \"ns:MetricContainer\",\n      \"@context\": {\n        \"metrics\": \"ns:metrics\",\n        \"metricFilters\": \"ns:metricFilters\"\n      }\n    },\n    \"ReportMetric\": {\n      \"@id\": \"ns:ReportMetric\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columnId\": {\n          \"@id\": \"ns:columnId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"filters\": \"ns:filters\",\n        \"sort\": {\n          \"@id\": \"ns:sort\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ReportSettings\": {\n      \"@id\": \"ns:ReportSettings\",\n      \"@context\": {\n        \"limit\": {\n          \"@id\": \"ns:limit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"page\": {\n          \"@id\": \"ns:page\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nonesBehavior\": {\n          \"@id\": \"ns:nonesBehavior\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ReportResponse\": {\n      \"@id\": \"ns:ReportResponse\",\n      \"@context\": {\n        \"totalPages\": {\n          \"@id\": \"ns:totalPages\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberOfElements\": {\n          \"@id\": \"ns:numberOfElements\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rows\": \"ns:rows\"\
  ,\n        \"columns\": \"ns:columns\",\n        \"summaryData\": \"ns:summaryData\"\n      }\n    },\n    \"ReportRow\": {\n      \"@id\": \"ns:ReportRow\",\n      \"@context\": {\n        \"itemId\": {\n          \"@id\": \"ns:itemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data\": \"ns:data\"\n      }\n    },\n    \"Segment\": {\n      \"@id\": \"ns:Segment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rsid\": {\n          \"@id\": \"ns:rsid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"ns:owner\",\n    \
  \      \"@type\": \"xsd:string\"\n        },\n        \"definition\": \"ns:definition\",\n        \"modified\": {\n          \"@id\": \"ns:modified\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tags\": \"ns:tags\"\n      }\n    },\n    \"SegmentCreate\": {\n      \"@id\": \"ns:SegmentCreate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rsid\": {\n          \"@id\": \"ns:rsid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"definition\": \"ns:definition\"\n      }\n    },\n    \"SegmentList\": {\n      \"@id\": \"ns:SegmentList\",\n      \"@context\": {\n        \"content\": \"ns:content\",\n        \"totalElements\": {\n          \"@id\": \"ns:totalElements\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalPages\": {\n          \"\
  @id\": \"ns:totalPages\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberOfElements\": {\n          \"@id\": \"ns:numberOfElements\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"CalculatedMetric\": {\n      \"@id\": \"ns:CalculatedMetric\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rsid\": {\n          \"@id\": \"ns:rsid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"ns:owner\",\n          \"@type\": \"xsd:string\"\n        },\n        \"definition\": \"ns:definition\",\n        \"modified\": {\n          \"@id\": \"ns:modified\",\n          \"@type\": \"xsd:string\"\n        },\n   \
  \     \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CalculatedMetricCreate\": {\n      \"@id\": \"ns:CalculatedMetricCreate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rsid\": {\n          \"@id\": \"ns:rsid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"definition\": \"ns:definition\",\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CalculatedMetricList\": {\n      \"@id\": \"ns:CalculatedMetricList\",\n      \"@context\": {\n        \"content\": \"ns:content\",\n        \"totalElements\": {\n          \"@id\": \"ns:totalElements\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalPages\": {\n   \
  \       \"@id\": \"ns:totalPages\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"Metric\": {\n      \"@id\": \"ns:Metric\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"extraTitleInfo\": {\n          \"@id\": \"ns:extraTitleInfo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Dimension\": {\n      \"@id\": \"ns:Dimension\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ReportSuite\": {\n      \"@id\": \"ns:ReportSuite\",\n      \"@context\": {\n        \"rsid\": {\n          \"@id\": \"ns:rsid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timezoneZoneinfo\": {\n\
  \          \"@id\": \"ns:timezoneZoneinfo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ReportSuiteList\": {\n      \"@id\": \"ns:ReportSuiteList\",\n      \"@context\": {\n        \"content\": \"ns:content\",\n        \"totalElements\": {\n          \"@id\": \"ns:totalElements\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalPages\": {\n          \"@id\": \"ns:totalPages\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"Annotation\": {\n      \"@id\": \"ns:Annotation\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n  \
  \      \"dateRange\": {\n          \"@id\": \"ns:dateRange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rsids\": \"ns:rsids\",\n        \"color\": {\n          \"@id\": \"ns:color\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AnnotationCreate\": {\n      \"@id\": \"ns:AnnotationCreate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateRange\": {\n          \"@id\": \"ns:dateRange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rsids\": \"ns:rsids\",\n        \"color\": {\n          \"@id\": \"ns:color\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"DateRange\": {\n      \"@id\": \"ns:DateRange\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"definition\": {\n          \"@id\": \"ns:definition\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"ns:Tag\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"components\": \"ns:components\"\n      }\n    },\n    \"Owner\": {\n      \"@id\": \"ns:Owner\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:integer\"\n        },\n    \
  \    \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"login\": {\n          \"@id\": \"ns:login\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"errorCode\": {\n          \"@id\": \"ns:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errorDescription\": {\n          \"@id\": \"ns:errorDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errorId\": {\n          \"@id\": \"ns:errorId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/json-ld/adobe-analytics-context.jsonld
tags:
- Adobe
- Analytics
- Business Intelligence
- Customer Intelligence
- Digital Marketing
- Marketing
- Web Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
