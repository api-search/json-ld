---
class_count: 18
classes:
- Project
- UserList
- User
- CalculatedMetricList
- ReportSuite
- SegmentList
- ProjectList
- CalculatedMetric
- ReportResponse
- ReportRequest
- ReportSuiteList
- Metric
- DateRangeList
- Dimension
- Segment
- name
- description
- email
context_file: json-ld/adobe-experience-cloud-analytics-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-analytics-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud Analytics Api from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Analytics Api Context
namespaces:
- prefix: aec
  uri: https://developer.adobe.com/schema/
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
  name: owner
  type: reference
- container: ''
  name: modified
  type: dateTime
- container: set
  name: content
  type: string
- container: ''
  name: loginId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: admin
  type: boolean
- container: ''
  name: totalElements
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: ''
  name: rsid
  type: string
- container: ''
  name: polarity
  type: string
- container: ''
  name: definition
  type: reference
- container: ''
  name: currency
  type: string
- container: ''
  name: timezone
  type: integer
- container: ''
  name: calendarType
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: firstPage
  type: boolean
- container: ''
  name: lastPage
  type: boolean
- container: ''
  name: numberOfElements
  type: integer
- container: set
  name: rows
  type: string
- container: ''
  name: itemId
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: data
  type: decimal
- container: set
  name: globalFilters
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: dateRange
  type: string
- container: ''
  name: metricContainer
  type: reference
- container: set
  name: metrics
  type: string
- container: ''
  name: dimension
  type: string
- container: ''
  name: settings
  type: reference
- container: ''
  name: limit
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: segmentable
  type: boolean
property_count: 34
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-analytics-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aec\": \"https://developer.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Project\": \"aec:Project\",\n    \"UserList\": \"aec:UserList\",\n    \"User\": \"aec:User\",\n    \"CalculatedMetricList\": \"aec:CalculatedMetricList\",\n    \"ReportSuite\": \"aec:ReportSuite\",\n    \"SegmentList\": \"aec:SegmentList\",\n    \"ProjectList\": \"aec:ProjectList\",\n    \"CalculatedMetric\": \"aec:CalculatedMetric\",\n    \"ReportResponse\": \"aec:ReportResponse\",\n    \"ReportRequest\": \"aec:ReportRequest\",\n    \"ReportSuiteList\": \"aec:ReportSuiteList\",\n    \"Metric\": \"aec:Metric\",\n    \"DateRangeList\": \"aec:DateRangeList\",\n    \"Dimension\": \"aec:Dimension\",\n    \"Segment\": \"aec:Segment\",\n    \"id\": {\n      \"@id\": \"aec:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\":\
  \ \"schema:name\",\n    \"description\": \"schema:description\",\n    \"owner\": {\n      \"@id\": \"aec:owner\",\n      \"@type\": \"@id\"\n    },\n    \"modified\": {\n      \"@id\": \"aec:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"content\": {\n      \"@id\": \"aec:content\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loginId\": {\n      \"@id\": \"aec:loginId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"firstName\": {\n      \"@id\": \"aec:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"aec:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"admin\": {\n      \"@id\": \"aec:admin\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"totalElements\": {\n      \"@id\": \"aec:totalElements\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"aec:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  rsid\": {\n      \"@id\": \"aec:rsid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"polarity\": {\n      \"@id\": \"aec:polarity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definition\": {\n      \"@id\": \"aec:definition\",\n      \"@type\": \"@id\"\n    },\n    \"currency\": {\n      \"@id\": \"aec:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"aec:timezone\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"calendarType\": {\n      \"@id\": \"aec:calendarType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aec:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstPage\": {\n      \"@id\": \"aec:firstPage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastPage\": {\n      \"@id\": \"aec:lastPage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"numberOfElements\": {\n      \"@id\": \"aec:numberOfElements\",\n      \"@type\": \"xsd:integer\"\n    },\n \
  \   \"rows\": {\n      \"@id\": \"aec:rows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemId\": {\n      \"@id\": \"aec:itemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aec:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"aec:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"globalFilters\": {\n      \"@id\": \"aec:globalFilters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aec:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateRange\": {\n      \"@id\": \"aec:dateRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricContainer\": {\n      \"@id\": \"aec:metricContainer\",\n      \"@type\": \"@id\"\n    },\n    \"metrics\": {\n      \"@id\": \"aec:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimension\": {\n\
  \      \"@id\": \"aec:dimension\",\n      \"@type\": \"xsd:string\"\n    },\n    \"settings\": {\n      \"@id\": \"aec:settings\",\n      \"@type\": \"@id\"\n    },\n    \"limit\": {\n      \"@id\": \"aec:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"aec:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"segmentable\": {\n      \"@id\": \"aec:segmentable\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-analytics-api-context.jsonld
tags:
- Analytics
- Customer Experience
- Digital Marketing
- Personalization
- Campaign Management
- Journey Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
