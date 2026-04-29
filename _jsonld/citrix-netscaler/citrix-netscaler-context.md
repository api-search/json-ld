---
api_specs:
- filename: citrix-netscaler-nitro-openapi.yml
  format: yaml
  label: Citrix ADC (NetScaler) NITRO API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix-netscaler/refs/heads/main/openapi/citrix-netscaler-nitro-openapi.yml
class_count: 0
classes: []
context_file: json-ld/citrix-netscaler-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/citrix-netscaler/refs/heads/main/json-ld/citrix-netscaler-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Citrix Netscaler from Citrix NetScaler.
layout: jsonld
name: Citrix Netscaler Context
namespaces:
- prefix: ns
  uri: https://developer-docs.netscaler.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: LbVserver
  type: ''
- container: ''
  name: CsVserver
  type: ''
- container: ''
  name: NsConfig
  type: ''
- container: ''
  name: LbVserverServiceBinding
  type: ''
- container: ''
  name: CsVserverCsPolicyBinding
  type: ''
- container: ''
  name: LbVserverStats
  type: ''
- container: ''
  name: SystemFile
  type: ''
property_count: 7
provider_name: Citrix NetScaler
provider_slug: citrix-netscaler
slug: citrix-netscaler-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ns\": \"https://developer-docs.netscaler.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"LbVserver\": {\n      \"@id\": \"ns:LbVserver\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"servicetype\": \"ns:servicetype\",\n        \"ipv46\": {\n          \"@id\": \"ns:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"ns:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lbmethod\": \"ns:lbmethod\",\n        \"backuplbmethod\": \"ns:backuplbmethod\",\n        \"persistencetype\": \"ns:persistencetype\",\n        \"timeout\": {\n          \"@id\": \"ns:persistenceTimeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"clttimeout\": {\n          \"@id\": \"ns:clientTimeout\",\n          \"@type\": \"\
  xsd:integer\"\n        },\n        \"state\": \"ns:adminState\",\n        \"curstate\": \"ns:operationalState\",\n        \"effectivestate\": \"ns:effectiveState\",\n        \"comment\": \"dcterms:description\",\n        \"td\": {\n          \"@id\": \"ns:trafficDomain\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cookiename\": \"ns:cookieName\",\n        \"redirecturl\": {\n          \"@id\": \"ns:redirectUrl\",\n          \"@type\": \"@id\"\n        },\n        \"health\": {\n          \"@id\": \"ns:healthPercentage\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalservices\": {\n          \"@id\": \"ns:totalServices\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"activeservices\": {\n          \"@id\": \"ns:activeServices\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statechangetimesec\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"connfailover\": \"ns:connectionFailover\"\
  ,\n        \"appflowlog\": \"ns:appFlowLogging\"\n      }\n    },\n\n    \"CsVserver\": {\n      \"@id\": \"ns:CsVserver\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"servicetype\": \"ns:servicetype\",\n        \"ipv46\": {\n          \"@id\": \"ns:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"ns:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"td\": {\n          \"@id\": \"ns:trafficDomain\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"state\": \"ns:adminState\",\n        \"curstate\": \"ns:operationalState\",\n        \"precedence\": \"ns:precedence\",\n        \"casesensitive\": \"ns:caseSensitive\",\n        \"lbvserver\": {\n          \"@id\": \"ns:defaultLbVserver\",\n          \"@type\": \"@id\"\n        },\n        \"targetlbvserver\": {\n          \"@id\": \"ns:targetLbVserver\",\n          \"@type\": \"@id\"\n        },\n        \"redirecturl\": {\n     \
  \     \"@id\": \"ns:redirectUrl\",\n          \"@type\": \"@id\"\n        },\n        \"comment\": \"dcterms:description\",\n        \"clttimeout\": {\n          \"@id\": \"ns:clientTimeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statechangetimesec\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"cachetype\": \"ns:cacheType\",\n        \"appflowlog\": \"ns:appFlowLogging\"\n      }\n    },\n\n    \"NsConfig\": {\n      \"@id\": \"ns:NsConfig\",\n      \"@context\": {\n        \"ipaddress\": {\n          \"@id\": \"ns:nsipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"netmask\": {\n          \"@id\": \"ns:netmask\",\n          \"@type\": \"xsd:string\"\n        },\n        \"systemtype\": \"ns:systemType\",\n        \"timezone\": \"ns:timezone\",\n        \"maxconn\": {\n          \"@id\": \"ns:maxConnections\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxreq\"\
  : {\n          \"@id\": \"ns:maxRequests\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"httpport\": {\n          \"@id\": \"ns:httpPort\",\n          \"@container\": \"@set\"\n        },\n        \"primaryip\": {\n          \"@id\": \"ns:primaryIp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastconfigchangedtime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastconfigsavetime\": {\n          \"@id\": \"ns:lastSaveTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"configchanged\": {\n          \"@id\": \"ns:hasUnsavedChanges\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"LbVserverServiceBinding\": {\n      \"@id\": \"ns:LbVserverServiceBinding\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:vserverName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"servicename\": {\n          \"@id\": \"ns:serviceName\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"weight\": {\n          \"@id\": \"ns:weight\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"curstate\": \"ns:operationalState\"\n      }\n    },\n\n    \"CsVserverCsPolicyBinding\": {\n      \"@id\": \"ns:CsVserverCsPolicyBinding\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:vserverName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"policyname\": {\n          \"@id\": \"ns:policyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"targetlbvserver\": {\n          \"@id\": \"ns:targetLbVserver\",\n          \"@type\": \"@id\"\n        },\n        \"priority\": {\n          \"@id\": \"ns:priority\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"LbVserverStats\": {\n      \"@id\": \"ns:LbVserverStats\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"ns:operationalState\",\n        \"primaryipaddress\"\
  : {\n          \"@id\": \"ns:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryport\": {\n          \"@id\": \"ns:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vslbhealth\": {\n          \"@id\": \"ns:healthPercentage\",\n          \"@type\": \"xsd:double\"\n        },\n        \"curclntconnections\": {\n          \"@id\": \"ns:clientConnections\",\n          \"@type\": \"xsd:double\"\n        },\n        \"cursrvrconnections\": {\n          \"@id\": \"ns:serverConnections\",\n          \"@type\": \"xsd:double\"\n        },\n        \"tothits\": {\n          \"@id\": \"ns:totalHits\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalrequests\": {\n          \"@id\": \"ns:totalRequests\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalresponses\": {\n          \"@id\": \"ns:totalResponses\",\n          \"@type\": \"xsd:double\"\n        },\n        \"requestsrate\": {\n          \"@id\": \"ns:requestsPerSecond\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"responsesrate\": {\n          \"@id\": \"ns:responsesPerSecond\",\n          \"@type\": \"xsd:double\"\n        },\n        \"cltresponsetimeapdex\": {\n          \"@id\": \"ns:apdexScore\",\n          \"@type\": \"xsd:double\"\n        },\n        \"actsvcs\": {\n          \"@id\": \"ns:activeServices\",\n          \"@type\": \"xsd:double\"\n        },\n        \"inactsvcs\": {\n          \"@id\": \"ns:inactiveServices\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"SystemFile\": {\n      \"@id\": \"ns:SystemFile\",\n      \"@context\": {\n        \"filename\": \"schema:name\",\n        \"filelocation\": \"ns:fileLocation\",\n        \"filesize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"filemodifiedtime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"fileaccesstime\": {\n\
  \          \"@id\": \"dcterms:dateAccepted\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/citrix-netscaler/refs/heads/main/json-ld/citrix-netscaler-context.jsonld
tags:
- API Gateway
- Application Delivery Controller
- Application Security
- Load Balancing
- SSL Offloading
- Traffic Management
- Web Application Firewall
- JSON-LD
- Linked Data
- Semantic Web
---
