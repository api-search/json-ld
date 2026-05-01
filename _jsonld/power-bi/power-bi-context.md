---
api_specs:
- filename: powerbi.json
  format: json
  label: Power BI REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/powerbi/data-plane/Microsoft.PowerBI/stable/v1.0/powerbi.json
class_count: 0
classes: []
context_file: json-ld/power-bi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/power-bi/refs/heads/main/json-ld/power-bi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Power Bi from Power BI.
layout: jsonld
name: Power Bi Context
namespaces:
- prefix: powerbi
  uri: https://learn.microsoft.com/rest/api/power-bi/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Table
  type: ''
- container: ''
  name: Column
  type: ''
- container: ''
  name: Measure
  type: ''
- container: ''
  name: Relationship
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Dashboard
  type: ''
- container: ''
  name: Tile
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: GroupUser
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: Datasource
  type: ''
- container: ''
  name: Refresh
  type: ''
- container: ''
  name: Import
  type: ''
property_count: 15
provider_name: Power BI
provider_slug: power-bi
slug: power-bi-context
source_filename: power-bi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"powerbi\": \"https://learn.microsoft.com/rest/api/power-bi/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Dataset\": {\n      \"@id\": \"powerbi:Dataset\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"addRowsAPIEnabled\": \"powerbi:addRowsAPIEnabled\",\n        \"configuredBy\": \"powerbi:configuredBy\",\n        \"isRefreshable\": \"powerbi:isRefreshable\",\n        \"isEffectiveIdentityRequired\": \"powerbi:isEffectiveIdentityRequired\",\n        \"isEffectiveIdentityRolesRequired\": \"powerbi:isEffectiveIdentityRolesRequired\",\n        \"isOnPremGatewayRequired\": \"powerbi:isOnPremGatewayRequired\",\n        \"targetStorageMode\": \"powerbi:targetStorageMode\",\n        \"defaultMode\": \"powerbi:defaultMode\",\n        \"createdDate\": {\n          \"\
  @id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"contentProviderType\": \"powerbi:contentProviderType\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createReportEmbedURL\": {\n          \"@id\": \"powerbi:createReportEmbedURL\",\n          \"@type\": \"@id\"\n        },\n        \"qnaEmbedURL\": {\n          \"@id\": \"powerbi:qnaEmbedURL\",\n          \"@type\": \"@id\"\n        },\n        \"tables\": {\n          \"@id\": \"powerbi:tables\",\n          \"@container\": \"@set\"\n        },\n        \"relationships\": {\n          \"@id\": \"powerbi:relationships\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Table\": {\n      \"@id\": \"powerbi:Table\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"columns\": {\n          \"@id\": \"powerbi:columns\",\n          \"@container\": \"@set\"\n        },\n        \"measures\": {\n\
  \          \"@id\": \"powerbi:measures\",\n          \"@container\": \"@set\"\n        },\n        \"rows\": {\n          \"@id\": \"powerbi:rows\",\n          \"@container\": \"@list\"\n        },\n        \"isHidden\": \"powerbi:isHidden\"\n      }\n    },\n\n    \"Column\": {\n      \"@id\": \"powerbi:Column\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"dataType\": \"powerbi:dataType\",\n        \"formatString\": \"powerbi:formatString\",\n        \"sortByColumn\": \"powerbi:sortByColumn\",\n        \"dataCategory\": \"powerbi:dataCategory\",\n        \"isHidden\": \"powerbi:isHidden\",\n        \"summarizeBy\": \"powerbi:summarizeBy\"\n      }\n    },\n\n    \"Measure\": {\n      \"@id\": \"powerbi:Measure\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"expression\": \"powerbi:daxExpression\",\n        \"formatString\": \"powerbi:formatString\",\n        \"description\": \"dcterms:description\",\n        \"isHidden\": \"powerbi:isHidden\"\
  \n      }\n    },\n\n    \"Relationship\": {\n      \"@id\": \"powerbi:Relationship\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"fromTable\": \"powerbi:fromTable\",\n        \"fromColumn\": \"powerbi:fromColumn\",\n        \"toTable\": \"powerbi:toTable\",\n        \"toColumn\": \"powerbi:toColumn\",\n        \"crossFilteringBehavior\": \"powerbi:crossFilteringBehavior\"\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"powerbi:Report\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"datasetId\": \"powerbi:datasetId\",\n        \"reportType\": \"powerbi:reportType\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"embedUrl\": {\n          \"@id\": \"powerbi:embedUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n       \
  \   \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedBy\": \"powerbi:modifiedBy\",\n        \"createdBy\": \"powerbi:createdBy\",\n        \"pages\": {\n          \"@id\": \"powerbi:pages\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"powerbi:Page\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"order\": \"schema:position\"\n      }\n    },\n\n    \"Dashboard\": {\n      \"@id\": \"powerbi:Dashboard\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"isReadOnly\": \"powerbi:isReadOnly\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"embedUrl\": {\n          \"@id\": \"powerbi:embedUrl\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"dataClassification\": \"powerbi:dataClassification\",\n        \"tiles\": {\n          \"@id\": \"powerbi:tiles\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Tile\": {\n      \"@id\": \"powerbi:Tile\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"subTitle\": \"schema:alternateName\",\n        \"embedUrl\": {\n          \"@id\": \"powerbi:embedUrl\",\n          \"@type\": \"@id\"\n        },\n        \"reportId\": \"powerbi:reportId\",\n        \"datasetId\": \"powerbi:datasetId\",\n        \"rowSpan\": \"powerbi:rowSpan\",\n        \"colSpan\": \"powerbi:colSpan\"\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"powerbi:Group\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"isReadOnly\": \"powerbi:isReadOnly\",\n        \"isOnDedicatedCapacity\": \"powerbi:isOnDedicatedCapacity\",\n        \"capacityId\": \"powerbi:capacityId\"\
  ,\n        \"type\": \"powerbi:workspaceType\",\n        \"state\": \"powerbi:workspaceState\"\n      }\n    },\n\n    \"GroupUser\": {\n      \"@id\": \"powerbi:GroupUser\",\n      \"@context\": {\n        \"emailAddress\": \"schema:email\",\n        \"displayName\": \"schema:name\",\n        \"identifier\": \"@id\",\n        \"groupUserAccessRight\": \"powerbi:accessRight\",\n        \"principalType\": \"powerbi:principalType\"\n      }\n    },\n\n    \"Gateway\": {\n      \"@id\": \"powerbi:Gateway\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"powerbi:gatewayType\",\n        \"publicKey\": \"powerbi:publicKey\",\n        \"gatewayAnnotation\": \"powerbi:annotation\"\n      }\n    },\n\n    \"Datasource\": {\n      \"@id\": \"powerbi:Datasource\",\n      \"@context\": {\n        \"datasourceType\": \"powerbi:datasourceType\",\n        \"connectionDetails\": \"powerbi:connectionDetails\",\n        \"datasourceId\": \"@id\"\
  ,\n        \"gatewayId\": \"powerbi:gatewayId\"\n      }\n    },\n\n    \"Refresh\": {\n      \"@id\": \"powerbi:Refresh\",\n      \"@context\": {\n        \"requestId\": \"@id\",\n        \"refreshType\": \"powerbi:refreshType\",\n        \"startTime\": {\n          \"@id\": \"powerbi:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"powerbi:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"powerbi:refreshStatus\"\n      }\n    },\n\n    \"Import\": {\n      \"@id\": \"powerbi:Import\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"importState\": \"powerbi:importState\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"reports\": {\n \
  \         \"@id\": \"powerbi:reports\",\n          \"@container\": \"@set\"\n        },\n        \"datasets\": {\n          \"@id\": \"powerbi:datasets\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/power-bi/refs/heads/main/json-ld/power-bi-context.jsonld
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Analysis
- Reporting
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
