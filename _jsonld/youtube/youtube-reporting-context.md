---
class_count: 0
classes: []
context_file: json-ld/youtube-reporting-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-reporting-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Youtube Reporting from Youtube.
layout: jsonld
name: Youtube Reporting Context
namespaces:
- prefix: yt
  uri: https://developers.google.com/youtube/v3/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Job
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: ReportType
  type: ''
- container: ''
  name: ListJobsResponse
  type: ''
- container: ''
  name: ListReportsResponse
  type: ''
- container: ''
  name: ListReportTypesResponse
  type: ''
property_count: 6
provider_name: Youtube
provider_slug: youtube
slug: youtube-reporting-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"yt\": \"https://developers.google.com/youtube/v3/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"Job\": {\n      \"@id\": \"yt:Job\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"reportTypeId\": {\n          \"@id\": \"yt:reportTypeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"createTime\": {\n          \"@id\": \"yt:createTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expireTime\": {\n          \"@id\": \"yt:expireTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"systemManaged\": {\n          \"@id\": \"yt:systemManaged\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"Report\": {\n      \"@id\": \"yt:Report\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobId\": {\n          \"@id\": \"yt:jobId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"yt:startTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endTime\": {\n          \"@id\": \"yt:endTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"yt:createTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"yt:downloadUrl\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobExpireTime\": {\n          \"@id\": \"yt:jobExpireTime\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ReportType\": {\n      \"@id\": \"yt:ReportType\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"name\": \"schema:name\",\n        \"systemManaged\": {\n          \"@id\": \"yt:systemManaged\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"deprecateTime\": {\n          \"@id\": \"yt:deprecateTime\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ListJobsResponse\": {\n      \"@id\": \"yt:ListJobsResponse\",\n      \"@context\": {\n        \"jobs\": \"yt:jobs\",\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ListReportsResponse\": {\n      \"@id\": \"yt:ListReportsResponse\",\n      \"@context\": {\n        \"reports\": \"yt:reports\",\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ListReportTypesResponse\": {\n      \"@id\": \"yt:ListReportTypesResponse\",\n      \"@context\": {\n        \"reportTypes\": \"yt:reportTypes\",\n        \"nextPageToken\"\
  : {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-reporting-context.jsonld
tags:
- Google
- Media
- Social
- Streaming
- Video
- Videos
- JSON-LD
- Linked Data
- Semantic Web
---
