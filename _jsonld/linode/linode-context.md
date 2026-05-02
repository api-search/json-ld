---
api_specs:
- filename: linode-api-v4-openapi.yml
  format: yaml
  label: Linode API V4
  slug: api-v4
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/openapi/linode-api-v4-openapi.yml
class_count: 0
classes: []
context_file: json-ld/linode-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/json-ld/linode-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Linode from linode.
layout: jsonld
name: Linode Context
namespaces:
- prefix: linode
  uri: https://api.linode.com/v4/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: LinodeInstance
  type: ''
- container: ''
  name: Domain
  type: ''
- container: ''
  name: DomainRecord
  type: ''
- container: ''
  name: Volume
  type: ''
- container: ''
  name: NodeBalancer
  type: ''
- container: ''
  name: LKECluster
  type: ''
- container: ''
  name: Firewall
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: VPC
  type: ''
- container: ''
  name: ObjectStorageBucket
  type: ''
- container: ''
  name: Region
  type: ''
- container: ''
  name: StackScript
  type: ''
property_count: 12
provider_name: linode
provider_slug: linode
slug: linode-context
source_filename: linode-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"linode\": \"https://api.linode.com/v4/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"LinodeInstance\": {\n      \"@id\": \"linode:LinodeInstance\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"region\": \"linode:region\",\n        \"type\": \"linode:type\",\n        \"image\": \"linode:image\",\n        \"status\": \"schema:serverStatus\",\n        \"ipv4\": \"linode:ipv4\",\n        \"ipv6\": \"linode:ipv6\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"\
  hypervisor\": \"linode:hypervisor\",\n        \"watchdog_enabled\": \"linode:watchdogEnabled\"\n      }\n    },\n\n    \"Domain\": {\n      \"@id\": \"linode:Domain\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"domain\": \"schema:name\",\n        \"type\": \"linode:zoneType\",\n        \"status\": \"schema:serverStatus\",\n        \"soa_email\": \"schema:email\",\n        \"description\": \"schema:description\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DomainRecord\": {\n      \"@id\": \"linode:DomainRecord\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"type\": \"linode:recordType\",\n        \"name\": \"schema:name\",\n\
  \        \"target\": \"linode:target\",\n        \"priority\": \"linode:priority\",\n        \"weight\": \"linode:weight\",\n        \"port\": \"linode:port\",\n        \"ttl_sec\": \"linode:ttlSec\"\n      }\n    },\n\n    \"Volume\": {\n      \"@id\": \"linode:Volume\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"status\": \"schema:serverStatus\",\n        \"size\": \"schema:contentSize\",\n        \"region\": \"linode:region\",\n        \"linode_id\": \"linode:linodeId\",\n        \"filesystem_path\": \"linode:filesystemPath\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"NodeBalancer\": {\n      \"@id\": \"\
  linode:NodeBalancer\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"region\": \"linode:region\",\n        \"hostname\": \"schema:url\",\n        \"ipv4\": \"linode:ipv4\",\n        \"ipv6\": \"linode:ipv6\",\n        \"client_conn_throttle\": \"linode:clientConnThrottle\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"LKECluster\": {\n      \"@id\": \"linode:LKECluster\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"region\": \"linode:region\",\n        \"k8s_version\": \"schema:softwareVersion\",\n        \"status\": \"schema:serverStatus\",\n        \"created\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Firewall\": {\n      \"@id\": \"linode:Firewall\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"status\": \"schema:serverStatus\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"linode:Database\",\n      \"@context\": {\n        \"id\": \"linode:id\"\
  ,\n        \"label\": \"schema:name\",\n        \"engine\": \"linode:engine\",\n        \"type\": \"linode:type\",\n        \"region\": \"linode:region\",\n        \"status\": \"schema:serverStatus\",\n        \"cluster_size\": \"linode:clusterSize\",\n        \"port\": \"linode:port\",\n        \"ssl_connection\": \"linode:sslConnection\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VPC\": {\n      \"@id\": \"linode:VPC\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"region\": \"linode:region\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ObjectStorageBucket\": {\n      \"@id\": \"linode:ObjectStorageBucket\",\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"region\": \"linode:region\",\n        \"hostname\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"objects\": \"linode:objectCount\",\n        \"size\": \"schema:contentSize\"\n      }\n    },\n\n    \"Region\": {\n      \"@id\": \"linode:Region\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"country\": \"schema:addressCountry\",\n        \"status\": \"schema:serverStatus\",\n        \"capabilities\": {\n          \"@id\": \"linode:capabilities\",\n          \"@container\": \"@set\"\n        },\n        \"site_type\": \"linode:siteType\"\n      }\n    },\n\
  \n    \"StackScript\": {\n      \"@id\": \"linode:StackScript\",\n      \"@context\": {\n        \"id\": \"linode:id\",\n        \"label\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"username\": \"schema:author\",\n        \"script\": \"schema:text\",\n        \"is_public\": \"schema:isAccessibleForFree\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/json-ld/linode-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
