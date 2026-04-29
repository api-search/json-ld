---
class_count: 7
classes:
- sys_id
- sys_created_by
- sys_updated_by
- sys_mod_count
- sys_class_name
- sys_domain
- active
context_file: json-ld/servicenow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow from ServiceNow.
layout: jsonld
name: Servicenow Context
namespaces:
- prefix: snow
  uri: https://www.servicenow.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: itsm
  uri: https://www.servicenow.com/ns/itsm/
properties:
- container: ''
  name: Incident
  type: ''
- container: ''
  name: ChangeRequest
  type: ''
- container: ''
  name: ConfigurationItem
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: CatalogRequest
  type: ''
- container: ''
  name: KnowledgeArticle
  type: ''
- container: ''
  name: sys_created_on
  type: dateTime
- container: ''
  name: sys_updated_on
  type: dateTime
property_count: 8
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"snow\": \"https://www.servicenow.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"itsm\": \"https://www.servicenow.com/ns/itsm/\",\n\n    \"Incident\": {\n      \"@id\": \"itsm:Incident\",\n      \"@context\": {\n        \"number\": \"itsm:ticketNumber\",\n        \"short_description\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"state\": \"itsm:state\",\n        \"priority\": \"itsm:priority\",\n        \"severity\": \"itsm:severity\",\n        \"impact\": \"itsm:impact\",\n        \"urgency\": \"itsm:urgency\",\n        \"category\": \"schema:category\",\n        \"subcategory\": \"itsm:subcategory\",\n        \"caller_id\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"@id\"\n        },\n        \"assigned_to\": {\n          \"@id\": \"itsm:assignedTo\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"assignment_group\": {\n          \"@id\": \"itsm:assignmentGroup\",\n          \"@type\": \"@id\"\n        },\n        \"cmdb_ci\": {\n          \"@id\": \"itsm:affectedItem\",\n          \"@type\": \"@id\"\n        },\n        \"business_service\": {\n          \"@id\": \"itsm:businessService\",\n          \"@type\": \"@id\"\n        },\n        \"opened_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolved_at\": {\n          \"@id\": \"itsm:resolvedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closed_at\": {\n          \"@id\": \"itsm:closedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"active\": \"snow:isActive\",\n        \"made_sla\": \"itsm:metSla\"\n      }\n    },\n\n    \"ChangeRequest\": {\n      \"@id\": \"itsm:ChangeRequest\",\n      \"@context\": {\n        \"number\": \"itsm:ticketNumber\",\n        \"short_description\"\
  : \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"itsm:changeType\",\n        \"state\": \"itsm:state\",\n        \"priority\": \"itsm:priority\",\n        \"risk\": \"itsm:riskLevel\",\n        \"impact\": \"itsm:impact\",\n        \"category\": \"schema:category\",\n        \"assigned_to\": {\n          \"@id\": \"itsm:assignedTo\",\n          \"@type\": \"@id\"\n        },\n        \"assignment_group\": {\n          \"@id\": \"itsm:assignmentGroup\",\n          \"@type\": \"@id\"\n        },\n        \"requested_by\": {\n          \"@id\": \"itsm:requestedBy\",\n          \"@type\": \"@id\"\n        },\n        \"cmdb_ci\": {\n          \"@id\": \"itsm:affectedItem\",\n          \"@type\": \"@id\"\n        },\n        \"start_date\": {\n          \"@id\": \"itsm:plannedStart\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end_date\": {\n          \"@id\": \"itsm:plannedEnd\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"opened_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closed_at\": {\n          \"@id\": \"itsm:closedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"approval\": \"itsm:approvalStatus\",\n        \"justification\": \"itsm:justification\",\n        \"implementation_plan\": \"itsm:implementationPlan\",\n        \"backout_plan\": \"itsm:backoutPlan\",\n        \"test_plan\": \"itsm:testPlan\"\n      }\n    },\n\n    \"ConfigurationItem\": {\n      \"@id\": \"itsm:ConfigurationItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"short_description\": \"schema:description\",\n        \"sys_class_name\": \"itsm:ciClass\",\n        \"category\": \"schema:category\",\n        \"operational_status\": \"itsm:operationalStatus\",\n        \"install_status\": \"itsm:installStatus\",\n        \"serial_number\": \"schema:serialNumber\",\n        \"ip_address\": \"snow:ipAddress\",\n\
  \        \"fqdn\": \"snow:fqdn\",\n        \"os\": \"snow:operatingSystem\",\n        \"os_version\": \"snow:operatingSystemVersion\",\n        \"manufacturer\": {\n          \"@id\": \"schema:manufacturer\",\n          \"@type\": \"@id\"\n        },\n        \"model_id\": {\n          \"@id\": \"schema:model\",\n          \"@type\": \"@id\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"@id\"\n        },\n        \"company\": {\n          \"@id\": \"schema:provider\",\n          \"@type\": \"@id\"\n        },\n        \"assigned_to\": {\n          \"@id\": \"itsm:assignedTo\",\n          \"@type\": \"@id\"\n        },\n        \"managed_by\": {\n          \"@id\": \"itsm:managedBy\",\n          \"@type\": \"@id\"\n        },\n        \"owned_by\": {\n          \"@id\": \"schema:owns\",\n          \"@type\": \"@id\"\n        },\n        \"discovery_source\": \"itsm:discoverySource\",\n        \"first_discovered\": {\n          \"@id\"\
  : \"itsm:firstDiscovered\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_discovered\": {\n          \"@id\": \"itsm:lastDiscovered\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"user_name\": \"snow:userName\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"mobile_phone\": \"schema:telephone\",\n        \"title\": \"schema:jobTitle\",\n        \"employee_number\": \"schema:identifier\",\n        \"department\": {\n          \"@id\": \"schema:department\",\n          \"@type\": \"@id\"\n        },\n        \"company\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"@id\"\n        },\n        \"manager\": {\n          \"@id\": \"snow:reportsTo\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"location\": {\n          \"@id\": \"schema:workLocation\",\n          \"@type\": \"@id\"\n        },\n        \"time_zone\": \"snow:timeZone\",\n        \"active\": \"snow:isActive\",\n        \"vip\": \"snow:isVip\",\n        \"photo\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"last_login_time\": {\n          \"@id\": \"snow:lastLoginTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CatalogRequest\": {\n      \"@id\": \"itsm:CatalogRequest\",\n      \"@context\": {\n        \"number\": \"itsm:ticketNumber\",\n        \"request_state\": \"itsm:state\",\n        \"requested_for\": {\n          \"@id\": \"itsm:requestedFor\",\n          \"@type\": \"@id\"\n        },\n        \"opened_by\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"@id\"\n        },\n        \"opened_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"price\": \"schema:price\",\n        \"approval\": \"itsm:approvalStatus\",\n        \"requested_items\": {\n          \"@id\": \"itsm:requestedItems\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"KnowledgeArticle\": {\n      \"@id\": \"schema:Article\",\n      \"@context\": {\n        \"short_description\": \"schema:headline\",\n        \"text\": \"schema:articleBody\",\n        \"topic\": \"schema:about\",\n        \"category\": \"schema:articleSection\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"kb_knowledge_base\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"published\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sys_updated_on\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"view_count\"\
  : \"schema:interactionCount\"\n      }\n    },\n\n    \"sys_id\": \"schema:identifier\",\n    \"sys_created_on\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sys_updated_on\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sys_created_by\": \"dcterms:creator\",\n    \"sys_updated_by\": \"snow:modifiedBy\",\n    \"sys_mod_count\": \"snow:modificationCount\",\n    \"sys_class_name\": \"snow:className\",\n    \"sys_domain\": \"snow:domain\",\n    \"active\": \"snow:isActive\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-context.jsonld
tags:
- Automation
- Cloud Services
- Digital Workflows
- Enterprise Platform
- IT Service Management
- ITSM
- Processes
- T1
- Workflow Automation
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
