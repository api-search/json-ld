---
class_count: 0
classes: []
context_file: json-ld/cloudflare-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudflare/refs/heads/main/json-ld/cloudflare-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudflare from Cloudflare.
layout: jsonld
name: Cloudflare Context
namespaces:
- prefix: cf
  uri: https://developers.cloudflare.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Zone
  type: ''
- container: ''
  name: DnsRecord
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: WorkerScript
  type: ''
- container: ''
  name: D1Database
  type: ''
- container: ''
  name: KvNamespace
  type: ''
- container: ''
  name: R2Bucket
  type: ''
- container: ''
  name: Queue
  type: ''
- container: ''
  name: VectorizeIndex
  type: ''
- container: ''
  name: PagesProject
  type: ''
- container: ''
  name: Video
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: AiGateway
  type: ''
property_count: 13
provider_name: Cloudflare
provider_slug: cloudflare
slug: cloudflare-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cf\": \"https://developers.cloudflare.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Zone\": {\n      \"@id\": \"cf:Zone\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"schema:eventStatus\",\n        \"paused\": \"cf:paused\",\n        \"type\": \"schema:additionalType\",\n        \"name_servers\": {\n          \"@id\": \"cf:nameServers\",\n          \"@container\": \"@set\"\n        },\n        \"account\": {\n          \"@id\": \"cf:account\",\n          \"@type\": \"@id\"\n        },\n        \"plan\": {\n          \"@id\": \"cf:plan\",\n          \"@type\": \"@id\"\n        },\n        \"activated_on\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_on\": {\n          \"@id\": \"dcterms:created\",\n\
  \          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified_on\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DnsRecord\": {\n      \"@id\": \"cf:DnsRecord\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"content\": \"schema:value\",\n        \"ttl\": \"cf:ttl\",\n        \"priority\": \"cf:priority\",\n        \"proxied\": \"cf:proxied\",\n        \"comment\": \"dcterms:description\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"zone_id\": {\n          \"@id\": \"cf:zone\",\n          \"@type\": \"@id\"\n        },\n        \"created_on\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified_on\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n    \
  \  }\n    },\n\n    \"Account\": {\n      \"@id\": \"cf:Account\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"created_on\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WorkerScript\": {\n      \"@id\": \"cf:WorkerScript\",\n      \"@context\": {\n        \"tag\": \"schema:version\",\n        \"handlers\": {\n          \"@id\": \"cf:handlers\",\n          \"@container\": \"@set\"\n        },\n        \"compatibility_date\": {\n          \"@id\": \"cf:compatibilityDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"usage_model\": \"cf:usageModel\",\n        \"routes\": {\n          \"@id\": \"cf:routes\",\n          \"@container\": \"@set\"\n        },\n        \"created_on\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified_on\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"D1Database\": {\n      \"@id\": \"cf:D1Database\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"num_tables\": \"cf:tableCount\",\n        \"file_size\": \"schema:contentSize\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"KvNamespace\": {\n      \"@id\": \"cf:KvNamespace\",\n      \"@context\": {\n        \"title\": \"schema:name\"\n      }\n    },\n\n    \"R2Bucket\": {\n      \"@id\": \"cf:R2Bucket\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"location\": \"schema:location\",\n        \"storage_class\": \"cf:storageClass\",\n        \"creation_date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Queue\": {\n      \"@id\": \"cf:Queue\",\n      \"\
  @context\": {\n        \"queue_name\": \"schema:name\",\n        \"created_on\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified_on\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VectorizeIndex\": {\n      \"@id\": \"cf:VectorizeIndex\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"dimensions\": \"cf:dimensions\",\n        \"metric\": \"cf:distanceMetric\"\n      }\n    },\n\n    \"PagesProject\": {\n      \"@id\": \"cf:PagesProject\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"subdomain\": \"cf:subdomain\",\n        \"production_branch\": \"cf:productionBranch\",\n        \"domains\": {\n          \"@id\": \"schema:url\",\n          \"@container\": \"@set\"\n        },\n        \"created_on\": {\n          \"@id\": \"dcterms:created\",\n      \
  \    \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Video\": {\n      \"@id\": \"cf:Video\",\n      \"@context\": {\n        \"thumbnail\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"duration\": \"schema:duration\",\n        \"size\": \"schema:contentSize\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"cf:Image\",\n      \"@context\": {\n        \"filename\": \"schema:name\",\n        \"uploaded\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"variants\": {\n          \"@id\": \"schema:url\",\n          \"@container\": \"@set\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AiGateway\": {\n    \
  \  \"@id\": \"cf:AiGateway\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"cf:slug\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudflare/refs/heads/main/json-ld/cloudflare-context.jsonld
tags:
- AI Gateway
- API Gateway
- Artificial Intelligence
- CDN
- Cloud
- Containers
- DDoS Protection
- DNS
- Edge
- Edge Computing
- Object Storage
- Platform
- Real-Time Communication
- Security
- Serverless
- Web Performance
- JSON-LD
- Linked Data
- Semantic Web
---
