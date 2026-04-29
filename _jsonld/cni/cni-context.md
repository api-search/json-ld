---
class_count: 0
classes: []
context_file: json-ld/cni-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cni/refs/heads/main/json-ld/cni-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cni from Container Network Interface (CNI).
layout: jsonld
name: Cni Context
namespaces:
- prefix: cni
  uri: https://www.cni.dev/vocabulary#
- prefix: k8s
  uri: https://kubernetes.io/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: NetworkConfig
  type: ''
- container: ''
  name: NetworkConfigList
  type: ''
- container: ''
  name: Result
  type: ''
- container: ''
  name: Interface
  type: ''
- container: ''
  name: IPConfig
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: DNS
  type: ''
- container: ''
  name: IPAM
  type: ''
- container: ''
  name: PortMapping
  type: ''
- container: ''
  name: BandwidthConfig
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 11
provider_name: Container Network Interface (CNI)
provider_slug: cni
slug: cni-context
source_filename: cni-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cni\": \"https://www.cni.dev/vocabulary#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"NetworkConfig\": {\n      \"@id\": \"cni:NetworkConfig\",\n      \"@context\": {\n        \"cniVersion\": \"cni:specVersion\",\n        \"name\": \"schema:name\",\n        \"type\": \"cni:pluginType\",\n        \"ipMasq\": \"cni:ipMasquerade\",\n        \"ipam\": \"cni:ipamConfiguration\",\n        \"dns\": \"cni:dnsConfiguration\",\n        \"capabilities\": \"cni:pluginCapabilities\",\n        \"runtimeConfig\": \"cni:runtimeConfiguration\",\n        \"prevResult\": \"cni:previousResult\"\n      }\n    },\n\n    \"NetworkConfigList\": {\n      \"@id\": \"cni:NetworkConfigList\",\n      \"@context\": {\n        \"cniVersion\": \"cni:specVersion\",\n        \"name\": \"schema:name\"\
  ,\n        \"disableCheck\": \"cni:disableCheck\",\n        \"disableGC\": \"cni:disableGarbageCollection\",\n        \"plugins\": {\n          \"@id\": \"cni:plugins\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Result\": {\n      \"@id\": \"cni:Result\",\n      \"@context\": {\n        \"cniVersion\": \"cni:specVersion\",\n        \"interfaces\": {\n          \"@id\": \"cni:networkInterfaces\",\n          \"@container\": \"@set\"\n        },\n        \"ips\": {\n          \"@id\": \"cni:ipAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"routes\": {\n          \"@id\": \"cni:networkRoutes\",\n          \"@container\": \"@set\"\n        },\n        \"dns\": \"cni:dnsConfiguration\"\n      }\n    },\n\n    \"Interface\": {\n      \"@id\": \"cni:NetworkInterface\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"mac\": \"cni:macAddress\",\n        \"mtu\": \"cni:mtu\",\n        \"sandbox\": {\n          \"@id\": \"\
  cni:networkNamespace\",\n          \"@type\": \"@id\"\n        },\n        \"pciID\": \"cni:pciDeviceID\"\n      }\n    },\n\n    \"IPConfig\": {\n      \"@id\": \"cni:IPAddress\",\n      \"@context\": {\n        \"address\": \"cni:cidrAddress\",\n        \"gateway\": {\n          \"@id\": \"cni:gatewayAddress\",\n          \"@type\": \"@id\"\n        },\n        \"interface\": \"cni:interfaceIndex\"\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"cni:NetworkRoute\",\n      \"@context\": {\n        \"dst\": {\n          \"@id\": \"cni:destinationNetwork\",\n          \"@type\": \"@id\"\n        },\n        \"gw\": {\n          \"@id\": \"cni:nextHopGateway\",\n          \"@type\": \"@id\"\n        },\n        \"mtu\": \"cni:routeMTU\"\n      }\n    },\n\n    \"DNS\": {\n      \"@id\": \"cni:DNSConfig\",\n      \"@context\": {\n        \"nameservers\": {\n          \"@id\": \"cni:nameservers\",\n          \"@container\": \"@set\"\n        },\n        \"domain\": \"cni:defaultDomain\"\
  ,\n        \"search\": {\n          \"@id\": \"cni:searchDomains\",\n          \"@container\": \"@set\"\n        },\n        \"options\": {\n          \"@id\": \"cni:resolverOptions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"IPAM\": {\n      \"@id\": \"cni:IPAMConfig\",\n      \"@context\": {\n        \"type\": \"cni:ipamPluginType\",\n        \"subnet\": \"cni:subnetCIDR\",\n        \"rangeStart\": \"cni:rangeStartIP\",\n        \"rangeEnd\": \"cni:rangeEndIP\",\n        \"gateway\": {\n          \"@id\": \"cni:gatewayAddress\",\n          \"@type\": \"@id\"\n        },\n        \"routes\": {\n          \"@id\": \"cni:networkRoutes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PortMapping\": {\n      \"@id\": \"cni:PortMapping\",\n      \"@context\": {\n        \"containerPort\": \"cni:containerPort\",\n        \"hostPort\": \"cni:hostPort\",\n        \"protocol\": \"cni:networkProtocol\",\n        \"hostIP\": {\n        \
  \  \"@id\": \"cni:hostBindAddress\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"BandwidthConfig\": {\n      \"@id\": \"cni:BandwidthConfig\",\n      \"@context\": {\n        \"ingressRate\": \"cni:ingressRateBps\",\n        \"ingressBurst\": \"cni:ingressBurstBits\",\n        \"egressRate\": \"cni:egressRateBps\",\n        \"egressBurst\": \"cni:egressBurstBits\"\n      }\n    },\n\n    \"Error\": {\n      \"@id\": \"cni:PluginError\",\n      \"@context\": {\n        \"code\": \"cni:errorCode\",\n        \"msg\": \"schema:description\",\n        \"details\": \"cni:errorDetails\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cni/refs/heads/main/json-ld/cni-context.jsonld
tags:
- Cloud Native
- Containers
- Incubating
- Kubernetes
- Networking
- Plugins
- JSON-LD
- Linked Data
- Semantic Web
---
