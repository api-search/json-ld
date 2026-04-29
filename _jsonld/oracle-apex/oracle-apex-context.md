---
class_count: 5
classes:
- id
- applicationId
- workspaceId
- displayName
- description
context_file: json-ld/oracle-apex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-apex/refs/heads/main/json-ld/oracle-apex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Apex from Oracle APEX.
layout: jsonld
name: Oracle Apex Context
namespaces:
- prefix: apex
  uri: https://docs.oracle.com/en/database/oracle/apex/vocab#
- prefix: ords
  uri: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Application
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Region
  type: ''
- container: ''
  name: PageItem
  type: ''
- container: ''
  name: Button
  type: ''
- container: ''
  name: Process
  type: ''
- container: ''
  name: DynamicAction
  type: ''
- container: ''
  name: RestModule
  type: ''
- container: ''
  name: RestTemplate
  type: ''
- container: ''
  name: RestHandler
  type: ''
- container: ''
  name: RestPrivilege
  type: ''
- container: ''
  name: RestRole
  type: ''
- container: ''
  name: OAuthClient
  type: ''
- container: ''
  name: AutoRestObject
  type: ''
- container: ''
  name: RestDataSource
  type: ''
- container: ''
  name: WebCredential
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: AuthenticationScheme
  type: ''
- container: ''
  name: AuthorizationScheme
  type: ''
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: lastUpdatedOn
  type: dateTime
property_count: 21
provider_name: Oracle APEX
provider_slug: oracle-apex
slug: oracle-apex-context
source_filename: oracle-apex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apex\": \"https://docs.oracle.com/en/database/oracle/apex/vocab#\",\n    \"ords\": \"https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Application\": {\n      \"@id\": \"apex:Application\",\n      \"@context\": {\n        \"applicationId\": \"apex:applicationId\",\n        \"applicationName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"applicationGroup\": \"apex:applicationGroup\",\n        \"workspace\": \"apex:workspace\",\n        \"workspaceId\": \"apex:workspaceId\",\n        \"alias\": \"apex:alias\",\n        \"version\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schema\": \"apex:parsingSchema\",\n        \"applicationStatus\"\
  : \"apex:applicationStatus\",\n        \"buildStatus\": \"apex:buildStatus\",\n        \"language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateFormat\": \"apex:dateFormat\",\n        \"compatibilityMode\": \"apex:compatibilityMode\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdatedBy\": \"apex:lastUpdatedBy\",\n        \"pages\": {\n          \"@id\": \"apex:hasPage\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"apex:Page\",\n      \"@context\": {\n        \"pageId\": \"apex:pageId\",\n        \"pageName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pageAlias\": \"apex:pageAlias\",\n        \"pageGroup\"\
  : \"apex:pageGroup\",\n        \"pageMode\": \"apex:pageMode\",\n        \"pageTemplate\": \"apex:pageTemplate\",\n        \"authorizationScheme\": \"apex:authorizationScheme\",\n        \"regions\": {\n          \"@id\": \"apex:hasRegion\",\n          \"@container\": \"@set\"\n        },\n        \"items\": {\n          \"@id\": \"apex:hasItem\",\n          \"@container\": \"@set\"\n        },\n        \"buttons\": {\n          \"@id\": \"apex:hasButton\",\n          \"@container\": \"@set\"\n        },\n        \"processes\": {\n          \"@id\": \"apex:hasProcess\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Region\": {\n      \"@id\": \"apex:Region\",\n      \"@context\": {\n        \"regionId\": \"apex:regionId\",\n        \"regionName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"regionType\": \"apex:regionType\",\n        \"template\": \"apex:template\",\n        \"displayPosition\": \"apex:displayPosition\"\
  ,\n        \"sourceType\": \"apex:sourceType\",\n        \"source\": \"apex:source\",\n        \"columns\": {\n          \"@id\": \"apex:hasColumn\",\n          \"@container\": \"@set\"\n        },\n        \"subRegions\": {\n          \"@id\": \"apex:hasSubRegion\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PageItem\": {\n      \"@id\": \"apex:PageItem\",\n      \"@context\": {\n        \"itemName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"itemType\": \"apex:itemType\",\n        \"label\": \"apex:label\",\n        \"regionId\": \"apex:regionId\",\n        \"sourceType\": \"apex:sourceType\",\n        \"source\": \"apex:source\",\n        \"isRequired\": \"apex:isRequired\",\n        \"isPrimaryKey\": \"apex:isPrimaryKey\",\n        \"defaultValue\": \"apex:defaultValue\",\n        \"displaySequence\": \"apex:displaySequence\"\n      }\n    },\n\n    \"Button\": {\n      \"@id\": \"apex:Button\",\n\
  \      \"@context\": {\n        \"buttonName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": \"apex:label\",\n        \"buttonAction\": \"apex:buttonAction\",\n        \"buttonPosition\": \"apex:buttonPosition\",\n        \"isHot\": \"apex:isHot\",\n        \"regionId\": \"apex:regionId\"\n      }\n    },\n\n    \"Process\": {\n      \"@id\": \"apex:Process\",\n      \"@context\": {\n        \"processName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processType\": \"apex:processType\",\n        \"processPoint\": \"apex:processPoint\",\n        \"source\": \"apex:source\",\n        \"errorMessage\": \"apex:errorMessage\",\n        \"successMessage\": \"apex:successMessage\"\n      }\n    },\n\n    \"DynamicAction\": {\n      \"@id\": \"apex:DynamicAction\",\n      \"@context\": {\n        \"dynamicActionName\": {\n          \"@id\": \"schema:name\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"event\": \"apex:event\",\n        \"triggeringElementType\": \"apex:triggeringElementType\",\n        \"triggeringElement\": \"apex:triggeringElement\",\n        \"conditionType\": \"apex:conditionType\"\n      }\n    },\n\n    \"RestModule\": {\n      \"@id\": \"ords:RestModule\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"basePath\": {\n          \"@id\": \"ords:basePath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"moduleStatus\": \"ords:moduleStatus\",\n        \"itemsPerPage\": \"ords:itemsPerPage\",\n        \"originsAllowed\": \"ords:originsAllowed\",\n        \"comments\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"templates\": {\n          \"@id\": \"ords:hasTemplate\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RestTemplate\": {\n \
  \     \"@id\": \"ords:RestTemplate\",\n      \"@context\": {\n        \"uriPrefix\": {\n          \"@id\": \"ords:uriPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"moduleId\": \"ords:moduleId\",\n        \"priority\": \"ords:priority\",\n        \"etagType\": \"ords:etagType\",\n        \"comments\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"handlers\": {\n          \"@id\": \"ords:hasHandler\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RestHandler\": {\n      \"@id\": \"ords:RestHandler\",\n      \"@context\": {\n        \"templateId\": \"ords:templateId\",\n        \"method\": {\n          \"@id\": \"ords:httpMethod\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceType\": \"ords:sourceType\",\n        \"source\": \"ords:source\",\n        \"itemsPerPage\": \"ords:itemsPerPage\",\n        \"mimesAllowed\": \"ords:mimesAllowed\",\n        \"comments\"\
  : {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"RestPrivilege\": {\n      \"@id\": \"ords:RestPrivilege\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": \"ords:label\",\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"roles\": {\n          \"@id\": \"ords:hasRole\",\n          \"@container\": \"@set\"\n        },\n        \"patterns\": {\n          \"@id\": \"ords:hasPattern\",\n          \"@container\": \"@set\"\n        },\n        \"modules\": {\n          \"@id\": \"ords:hasModule\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RestRole\": {\n      \"@id\": \"ords:RestRole\",\n      \"@context\": {\n        \"roleName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"privileges\": {\n          \"@id\": \"ords:hasPrivilege\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"OAuthClient\": {\n      \"@id\": \"ords:OAuthClient\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"redirectUri\": {\n          \"@id\": \"ords:redirectUri\",\n          \"@type\": \"@id\"\n        },\n        \"supportEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"supportUri\": {\n          \"@id\": \"ords:supportUri\",\n          \"@type\": \"@id\"\n        },\n        \"privilegeNames\": \"ords:privilegeNames\",\n        \"roleNames\": \"ords:roleNames\",\n        \"allowedOrigins\": \"ords:allowedOrigins\"\n      }\n    },\n\n    \"AutoRestObject\": {\n  \
  \    \"@id\": \"ords:AutoRestObject\",\n      \"@context\": {\n        \"objectName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectAlias\": \"ords:objectAlias\",\n        \"auth\": \"ords:requiresAuth\"\n      }\n    },\n\n    \"RestDataSource\": {\n      \"@id\": \"apex:RestDataSource\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"urlEndpoint\": {\n          \"@id\": \"apex:urlEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"httpMethod\": \"apex:httpMethod\",\n        \"format\": \"apex:format\",\n        \"paginationType\": \"apex:paginationType\",\n        \"credentialName\": \"apex:credentialName\"\n      }\n    },\n\n    \"WebCredential\": {\n      \"@id\": \"apex:WebCredential\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"authenticationType\": \"apex:authenticationType\",\n        \"scope\": \"apex:scope\",\n        \"validForUrls\": \"apex:validForUrls\"\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"apex:Workspace\",\n      \"@context\": {\n        \"workspaceId\": \"apex:workspaceId\",\n        \"workspaceName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primarySchema\": \"apex:primarySchema\",\n        \"applications\": {\n          \"@id\": \"apex:hasApplication\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AuthenticationScheme\": {\n      \"@id\": \"apex:AuthenticationScheme\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schemeType\": \"apex:schemeType\",\n        \"isCurrent\"\
  : \"apex:isCurrent\",\n        \"logoutUrl\": {\n          \"@id\": \"apex:logoutUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AuthorizationScheme\": {\n      \"@id\": \"apex:AuthorizationScheme\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schemeType\": \"apex:schemeType\",\n        \"expression\": \"apex:expression\",\n        \"errorMessage\": \"apex:errorMessage\",\n        \"evaluateOnce\": \"apex:evaluateOnce\"\n      }\n    },\n\n    \"id\": \"apex:id\",\n    \"applicationId\": \"apex:applicationId\",\n    \"workspaceId\": \"apex:workspaceId\",\n    \"displayName\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdatedOn\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-apex/refs/heads/main/json-ld/oracle-apex-context.jsonld
tags:
- APEX
- Cloud
- Database
- Development Platform
- Enterprise
- Generative AI
- Low-Code
- Oracle
- ORDS
- PL/SQL
- REST API
- Web Applications
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
