---
api_specs:
- filename: iis-administration-api.yml
  format: yaml
  label: IIS Administration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-windows-server/refs/heads/main/openapi/iis-administration-api.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-windows-server-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-windows-server/refs/heads/main/json-ld/microsoft-windows-server-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Windows Server from Microsoft Windows Server.
layout: jsonld
name: Microsoft Windows Server Context
namespaces:
- prefix: iis
  uri: https://learn.microsoft.com/en-us/iis-administration/api/
- prefix: ms
  uri: https://learn.microsoft.com/en-us/windows-server/
properties:
- container: ''
  name: WebSite
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: ApplicationPool
  type: ''
property_count: 3
provider_name: Microsoft Windows Server
provider_slug: microsoft-windows-server
slug: microsoft-windows-server-context
source_filename: microsoft-windows-server-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"iis\": \"https://learn.microsoft.com/en-us/iis-administration/api/\",\n    \"ms\": \"https://learn.microsoft.com/en-us/windows-server/\",\n    \"WebSite\": {\n      \"@id\": \"iis:sites\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"id\": \"https://schema.org/identifier\",\n        \"physical_path\": {\n          \"@id\": \"iis:sites#physical_path\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"key\": {\n          \"@id\": \"iis:sites#key\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"status\": {\n          \"@id\": \"iis:sites#status\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"server_auto_start\": {\n          \"@id\": \"iis:sites#server_auto_start\",\n          \"@type\": \"https://schema.org/Boolean\"\n        },\n        \"enabled_protocols\": {\n          \"@id\": \"iis:sites#enabled_protocols\"\
  ,\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"limits\": {\n          \"@id\": \"iis:sites#limits\",\n          \"@context\": {\n            \"connection_timeout\": {\n              \"@id\": \"iis:sites#connection_timeout\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"max_bandwidth\": {\n              \"@id\": \"iis:sites#max_bandwidth\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"max_connections\": {\n              \"@id\": \"iis:sites#max_connections\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"max_url_segments\": {\n              \"@id\": \"iis:sites#max_url_segments\",\n              \"@type\": \"https://schema.org/Integer\"\n            }\n          }\n        },\n        \"bindings\": {\n          \"@id\": \"iis:sites#bindings\",\n          \"@container\": \"@list\",\n          \"@context\": {\n            \"protocol\"\
  : {\n              \"@id\": \"iis:sites#binding_protocol\",\n              \"@type\": \"https://schema.org/Text\"\n            },\n            \"binding_information\": {\n              \"@id\": \"iis:sites#binding_information\",\n              \"@type\": \"https://schema.org/Text\"\n            },\n            \"ip_address\": {\n              \"@id\": \"iis:sites#ip_address\",\n              \"@type\": \"https://schema.org/Text\"\n            },\n            \"port\": {\n              \"@id\": \"iis:sites#port\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"hostname\": {\n              \"@id\": \"iis:sites#hostname\",\n              \"@type\": \"https://schema.org/Text\"\n            },\n            \"require_sni\": {\n              \"@id\": \"iis:sites#require_sni\",\n              \"@type\": \"https://schema.org/Boolean\"\n            },\n            \"certificate\": {\n              \"@id\": \"iis:sites#certificate\",\n              \"@context\"\
  : {\n                \"name\": \"https://schema.org/name\",\n                \"id\": \"https://schema.org/identifier\",\n                \"issued_by\": {\n                  \"@id\": \"iis:sites#cert_issued_by\",\n                  \"@type\": \"https://schema.org/Text\"\n                },\n                \"subject\": {\n                  \"@id\": \"iis:sites#cert_subject\",\n                  \"@type\": \"https://schema.org/Text\"\n                },\n                \"thumbprint\": {\n                  \"@id\": \"iis:sites#cert_thumbprint\",\n                  \"@type\": \"https://schema.org/Text\"\n                },\n                \"valid_to\": {\n                  \"@id\": \"iis:sites#cert_valid_to\",\n                  \"@type\": \"https://schema.org/DateTime\"\n                }\n              }\n            }\n          }\n        },\n        \"application_pool\": {\n          \"@id\": \"iis:application-pools\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"\
  Application\": {\n      \"@id\": \"iis:applications\",\n      \"@context\": {\n        \"location\": {\n          \"@id\": \"iis:applications#location\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"path\": {\n          \"@id\": \"iis:applications#path\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"id\": \"https://schema.org/identifier\",\n        \"physical_path\": {\n          \"@id\": \"iis:applications#physical_path\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"enabled_protocols\": {\n          \"@id\": \"iis:applications#enabled_protocols\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"website\": {\n          \"@id\": \"iis:sites\",\n          \"@type\": \"@id\"\n        },\n        \"application_pool\": {\n          \"@id\": \"iis:application-pools\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"ApplicationPool\": {\n      \"@id\": \"iis:application-pools\"\
  ,\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"id\": \"https://schema.org/identifier\",\n        \"status\": {\n          \"@id\": \"iis:application-pools#status\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"auto_start\": {\n          \"@id\": \"iis:application-pools#auto_start\",\n          \"@type\": \"https://schema.org/Boolean\"\n        },\n        \"pipeline_mode\": {\n          \"@id\": \"iis:application-pools#pipeline_mode\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"managed_runtime_version\": {\n          \"@id\": \"iis:application-pools#managed_runtime_version\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"enable_32bit_win64\": {\n          \"@id\": \"iis:application-pools#enable_32bit_win64\",\n          \"@type\": \"https://schema.org/Boolean\"\n        },\n        \"queue_length\": {\n          \"@id\": \"iis:application-pools#queue_length\",\n   \
  \       \"@type\": \"https://schema.org/Integer\"\n        },\n        \"cpu\": {\n          \"@id\": \"iis:application-pools#cpu\",\n          \"@context\": {\n            \"limit\": {\n              \"@id\": \"iis:application-pools#cpu_limit\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"limit_interval\": {\n              \"@id\": \"iis:application-pools#cpu_limit_interval\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"action\": {\n              \"@id\": \"iis:application-pools#cpu_action\",\n              \"@type\": \"https://schema.org/Text\"\n            }\n          }\n        },\n        \"process_model\": {\n          \"@id\": \"iis:application-pools#process_model\",\n          \"@context\": {\n            \"idle_timeout\": {\n              \"@id\": \"iis:application-pools#idle_timeout\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"max_processes\"\
  : {\n              \"@id\": \"iis:application-pools#max_processes\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"pinging_enabled\": {\n              \"@id\": \"iis:application-pools#pinging_enabled\",\n              \"@type\": \"https://schema.org/Boolean\"\n            },\n            \"ping_interval\": {\n              \"@id\": \"iis:application-pools#ping_interval\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"idle_timeout_action\": {\n              \"@id\": \"iis:application-pools#idle_timeout_action\",\n              \"@type\": \"https://schema.org/Text\"\n            }\n          }\n        },\n        \"identity\": {\n          \"@id\": \"iis:application-pools#identity\",\n          \"@context\": {\n            \"identity_type\": {\n              \"@id\": \"iis:application-pools#identity_type\",\n              \"@type\": \"https://schema.org/Text\"\n            },\n            \"username\": {\n\
  \              \"@id\": \"iis:application-pools#username\",\n              \"@type\": \"https://schema.org/Text\"\n            },\n            \"load_user_profile\": {\n              \"@id\": \"iis:application-pools#load_user_profile\",\n              \"@type\": \"https://schema.org/Boolean\"\n            }\n          }\n        },\n        \"recycling\": {\n          \"@id\": \"iis:application-pools#recycling\",\n          \"@context\": {\n            \"disable_overlapped_recycle\": {\n              \"@id\": \"iis:application-pools#disable_overlapped_recycle\",\n              \"@type\": \"https://schema.org/Boolean\"\n            },\n            \"periodic_restart\": {\n              \"@id\": \"iis:application-pools#periodic_restart\",\n              \"@context\": {\n                \"time_interval\": {\n                  \"@id\": \"iis:application-pools#restart_time_interval\",\n                  \"@type\": \"https://schema.org/Integer\"\n                },\n                \"private_memory\"\
  : {\n                  \"@id\": \"iis:application-pools#restart_private_memory\",\n                  \"@type\": \"https://schema.org/Integer\"\n                },\n                \"request_limit\": {\n                  \"@id\": \"iis:application-pools#restart_request_limit\",\n                  \"@type\": \"https://schema.org/Integer\"\n                }\n              }\n            }\n          }\n        },\n        \"rapid_fail_protection\": {\n          \"@id\": \"iis:application-pools#rapid_fail_protection\",\n          \"@context\": {\n            \"enabled\": {\n              \"@id\": \"iis:application-pools#rfp_enabled\",\n              \"@type\": \"https://schema.org/Boolean\"\n            },\n            \"interval\": {\n              \"@id\": \"iis:application-pools#rfp_interval\",\n              \"@type\": \"https://schema.org/Integer\"\n            },\n            \"max_crashes\": {\n              \"@id\": \"iis:application-pools#rfp_max_crashes\",\n              \"@type\"\
  : \"https://schema.org/Integer\"\n            }\n          }\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-windows-server/refs/heads/main/json-ld/microsoft-windows-server-context.jsonld
tags:
- Datacenter
- Enterprise
- Infrastructure
- Microsoft
- Operating System
- Server Management
- Windows Server
- Windows Server 2025
- JSON-LD
- Linked Data
- Semantic Web
---
