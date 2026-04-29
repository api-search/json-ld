---
class_count: 8
classes:
- Alarm
- ApplicationUsage
- LANNetwork
- PathRule
- QoSRule
- Site
- SiteMetric
- WANInterface
context_file: json-ld/palo-alto-prisma-sd-wan-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-sd-wan-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Sd Wan Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Sd Wan Api Context
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
  name: acknowledged
  type: boolean
- container: ''
  name: acknowledgedAt
  type: dateTime
- container: ''
  name: acknowledgedBy
  type: string
- container: ''
  name: address
  type: reference
- container: ''
  name: adminState
  type: string
- container: set
  name: appFilters
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: avgLatencyMs
  type: decimal
- container: ''
  name: bandwidthLimitDown
  type: decimal
- container: ''
  name: bandwidthLimitUp
  type: decimal
- container: ''
  name: bytesDown
  type: integer
- container: ''
  name: bytesUp
  type: integer
- container: ''
  name: city
  type: string
- container: ''
  name: clearedAt
  type: dateTime
- container: ''
  name: cost
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: dhcpEnabled
  type: boolean
- container: ''
  name: direction
  type: string
- container: ''
  name: dscpClass
  type: string
- container: ''
  name: elementClusterRole
  type: string
- container: ''
  name: elementId
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: interfaceName
  type: string
- container: ''
  name: jitterMs
  type: integer
- container: ''
  name: label
  type: string
- container: ''
  name: labelId
  type: string
- container: ''
  name: latencyMs
  type: integer
- container: ''
  name: latitude
  type: double
- container: ''
  name: linkBwDown
  type: decimal
- container: ''
  name: linkBwUp
  type: decimal
- container: ''
  name: location
  type: reference
- container: ''
  name: longitude
  type: double
- container: ''
  name: lqmEnabled
  type: boolean
- container: ''
  name: message
  type: string
- container: ''
  name: metricType
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: network
  type: string
- container: ''
  name: packetLossPct
  type: decimal
- container: ''
  name: postCode
  type: string
- container: set
  name: preferredPaths
  type: reference
- container: ''
  name: priority
  type: integer
- container: ''
  name: raisedAt
  type: dateTime
- container: ''
  name: sessions
  type: integer
- container: ''
  name: severity
  type: string
- container: ''
  name: siteId
  type: string
- container: ''
  name: siteName
  type: string
- container: ''
  name: slaThreshold
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: street
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: value
  type: decimal
- container: ''
  name: vlanId
  type: integer
property_count: 59
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-sd-wan-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alarm\": \"pan:Alarm\",\n    \"ApplicationUsage\": \"pan:ApplicationUsage\",\n    \"LANNetwork\": \"pan:LANNetwork\",\n    \"PathRule\": \"pan:PathRule\",\n    \"QoSRule\": \"pan:QoSRule\",\n    \"Site\": \"pan:Site\",\n    \"SiteMetric\": \"pan:SiteMetric\",\n    \"WANInterface\": \"pan:WANInterface\",\n    \"acknowledged\": {\n      \"@id\": \"pan:acknowledged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"acknowledgedAt\": {\n      \"@id\": \"pan:acknowledged_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledgedBy\": {\n      \"@id\": \"pan:acknowledged_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"pan:address\",\n      \"@type\": \"@id\"\n    },\n    \"adminState\": {\n      \"\
  @id\": \"pan:admin_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appFilters\": {\n      \"@id\": \"pan:app_filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avgLatencyMs\": {\n      \"@id\": \"pan:avg_latency_ms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"bandwidthLimitDown\": {\n      \"@id\": \"pan:bandwidth_limit_down\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"bandwidthLimitUp\": {\n      \"@id\": \"pan:bandwidth_limit_up\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"bytesDown\": {\n      \"@id\": \"pan:bytes_down\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bytesUp\": {\n      \"@id\": \"pan:bytes_up\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"city\": {\n      \"@id\": \"pan:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clearedAt\": {\n      \"@id\": \"pan:cleared_at\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"cost\": {\n      \"@id\": \"pan:cost\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"country\": {\n      \"@id\": \"pan:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dhcpEnabled\": {\n      \"@id\": \"pan:dhcp_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"direction\": {\n      \"@id\": \"pan:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dscpClass\": {\n      \"@id\": \"pan:dscp_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elementClusterRole\": {\n      \"@id\": \"pan:element_cluster_role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elementId\": {\n      \"@id\": \"pan:element_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"\
  @type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interfaceName\": {\n      \"@id\": \"pan:interface_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jitterMs\": {\n      \"@id\": \"pan:jitter_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"label\": {\n      \"@id\": \"pan:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labelId\": {\n      \"@id\": \"pan:label_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latencyMs\": {\n      \"@id\": \"pan:latency_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"latitude\": {\n      \"@id\": \"pan:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"linkBwDown\": {\n      \"@id\": \"pan:link_bw_down\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"linkBwUp\": {\n      \"@id\": \"pan:link_bw_up\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"location\": {\n      \"@id\": \"pan:location\",\n      \"@type\": \"@id\"\n    },\n    \"\
  longitude\": {\n      \"@id\": \"pan:longitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lqmEnabled\": {\n      \"@id\": \"pan:lqm_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"message\": {\n      \"@id\": \"pan:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricType\": {\n      \"@id\": \"pan:metric_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"pan:network\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packetLossPct\": {\n      \"@id\": \"pan:packet_loss_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"postCode\": {\n      \"@id\": \"pan:post_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferredPaths\": {\n      \"@id\": \"pan:preferred_paths\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"priority\": {\n      \"@id\": \"pan:priority\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"raisedAt\": {\n      \"@id\": \"pan:raised_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sessions\": {\n      \"@id\": \"pan:sessions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteId\": {\n      \"@id\": \"pan:site_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteName\": {\n      \"@id\": \"pan:site_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slaThreshold\": {\n      \"@id\": \"pan:sla_threshold\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"pan:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"pan:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vlanId\": {\n      \"@id\": \"pan:vlan_id\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-sd-wan-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
