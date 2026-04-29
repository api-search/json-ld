---
class_count: 8
classes:
- AsmIncident
- AssetInternetExposure
- AttackSurfaceRule
- AuditLog
- ExposedService
- Filter
- OwnedIpRange
- SortOrder
context_file: json-ld/palo-alto-cortex-xpanse-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xpanse-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cortex Xpanse Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cortex Xpanse Api Context
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
  name: actorEmail
  type: string
- container: ''
  name: actorPrimaryUsername
  type: string
- container: ''
  name: actorType
  type: string
- container: ''
  name: alertCount
  type: integer
- container: set
  name: asmIdList
  type: string
- container: ''
  name: assetName
  type: string
- container: ''
  name: assetType
  type: string
- container: ''
  name: assignedUserMail
  type: string
- container: ''
  name: assignedUserPrettyName
  type: string
- container: ''
  name: attackSurfaceRuleId
  type: string
- container: ''
  name: attackSurfaceRuleName
  type: string
- container: ''
  name: attributionReason
  type: string
- container: set
  name: businessUnits
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: cidr
  type: string
- container: ''
  name: cloudId
  type: string
- container: ''
  name: cloudProvider
  type: string
- container: ''
  name: created
  type: integer
- container: ''
  name: creationTime
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: discoveryType
  type: string
- container: set
  name: domain
  type: string
- container: ''
  name: enabledStatus
  type: string
- container: set
  name: externallyDetectedProviders
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: firstIp
  type: string
- container: ''
  name: incidentId
  type: string
- container: ''
  name: incidentName
  type: string
- container: set
  name: incidentType
  type: string
- container: ''
  name: ip
  type: string
- container: set
  name: ipAddress
  type: string
- container: set
  name: ipv6Address
  type: string
- container: ''
  name: isActive
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: keyword
  type: string
- container: ''
  name: lastIp
  type: string
- container: ''
  name: lastObserved
  type: integer
- container: ''
  name: modificationTime
  type: integer
- container: ''
  name: modified
  type: integer
- container: ''
  name: operator
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: protocol
  type: string
- container: set
  name: provider
  type: string
- container: ''
  name: rangeId
  type: string
- container: ''
  name: rangeSize
  type: integer
- container: ''
  name: reason
  type: string
- container: ''
  name: releaseStatus
  type: string
- container: ''
  name: remediationGuidance
  type: string
- container: ''
  name: resolveComment
  type: string
- container: ''
  name: resolvedBy
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: serviceId
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subType
  type: string
- container: set
  name: tags
  type: reference
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: value
  type: string
property_count: 60
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cortex-xpanse-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AsmIncident\": \"pan:AsmIncident\",\n    \"AssetInternetExposure\": \"pan:AssetInternetExposure\",\n    \"AttackSurfaceRule\": \"pan:AttackSurfaceRule\",\n    \"AuditLog\": \"pan:AuditLog\",\n    \"ExposedService\": \"pan:ExposedService\",\n    \"Filter\": \"pan:Filter\",\n    \"OwnedIpRange\": \"pan:OwnedIpRange\",\n    \"SortOrder\": \"pan:SortOrder\",\n    \"actorEmail\": {\n      \"@id\": \"pan:actor_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorPrimaryUsername\": {\n      \"@id\": \"pan:actor_primary_username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorType\": {\n      \"@id\": \"pan:actor_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertCount\": {\n      \"@id\": \"pan:alert_count\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"asmIdList\": {\n      \"@id\": \"pan:asm_id_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetName\": {\n      \"@id\": \"pan:asset_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetType\": {\n      \"@id\": \"pan:asset_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedUserMail\": {\n      \"@id\": \"pan:assigned_user_mail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedUserPrettyName\": {\n      \"@id\": \"pan:assigned_user_pretty_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attackSurfaceRuleId\": {\n      \"@id\": \"pan:attack_surface_rule_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attackSurfaceRuleName\": {\n      \"@id\": \"pan:attack_surface_rule_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributionReason\": {\n      \"@id\": \"pan:attribution_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessUnits\": {\n      \"\
  @id\": \"pan:business_units\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cidr\": {\n      \"@id\": \"pan:cidr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudId\": {\n      \"@id\": \"pan:cloud_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudProvider\": {\n      \"@id\": \"pan:cloud_provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"pan:created\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"creationTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discoveryType\": {\n      \"@id\": \"pan:discovery_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"pan:domain\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"enabledStatus\": {\n      \"@id\": \"pan:enabled_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externallyDetectedProviders\": {\n      \"@id\": \"pan:externally_detected_providers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"field\": {\n      \"@id\": \"pan:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstIp\": {\n      \"@id\": \"pan:first_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentId\": {\n      \"@id\": \"pan:incident_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentName\": {\n      \"@id\": \"pan:incident_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentType\": {\n      \"@id\": \"pan:incident_type\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip\": {\n      \"@id\": \"pan:ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"pan:ip_address\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ipv6Address\": {\n      \"@id\": \"pan:ipv6_address\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isActive\": {\n      \"@id\": \"pan:is_active\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"pan:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyword\": {\n      \"@id\": \"pan:keyword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastIp\": {\n      \"@id\": \"pan:last_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastObserved\": {\n      \"@id\": \"pan:last_observed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modificationTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modified\": {\n      \"@id\": \"pan:modified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"operator\": {\n      \"@id\": \"pan:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"pan:port\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocol\": {\n      \"@id\": \"pan:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"pan:provider\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeId\": {\n      \"@id\": \"pan:range_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeSize\": {\n      \"@id\": \"pan:range_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reason\": {\n      \"@id\": \"pan:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releaseStatus\": {\n      \"@id\": \"pan:release_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediationGuidance\": {\n      \"@id\": \"pan:remediation_guidance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolveComment\": {\n      \"@id\": \"pan:resolve_comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedBy\": {\n      \"@id\": \"pan:resolved_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  result\": {\n      \"@id\": \"pan:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceId\": {\n      \"@id\": \"pan:service_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"pan:service_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"pan:service_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"pan:sub_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xpanse-api-context.jsonld
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
