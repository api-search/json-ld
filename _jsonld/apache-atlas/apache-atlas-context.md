---
class_count: 11
classes:
- AtlasLineageInfo
- AtlasEntityWithExtInfo
- AtlasEntitiesWithExtInfo
- AtlasRelationship
- AtlasSearchResult
- AtlasGlossary
- AtlasTypesDef
- AtlasErrorResponse
- EntityMutationResponse
- EntityWithExtInfo
- AtlasEntity
context_file: json-ld/apache-atlas-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-atlas/refs/heads/main/json-ld/apache-atlas-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Atlas from Apache Atlas.
layout: jsonld
name: Apache Atlas Context
namespaces:
- prefix: atlas
  uri: https://atlas.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: baseEntityGuid
  type: string
- container: ''
  name: lineageDirection
  type: string
- container: ''
  name: lineageDepth
  type: integer
- container: ''
  name: guidEntityMap
  type: string
- container: ''
  name: relations
  type: string
- container: ''
  name: entity
  type: string
- container: ''
  name: referredEntities
  type: string
- container: ''
  name: entities
  type: string
- container: ''
  name: guid
  type: string
- container: ''
  name: typeName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: end1
  type: string
- container: ''
  name: end2
  type: string
- container: ''
  name: queryType
  type: string
- container: ''
  name: searchParameters
  type: string
- container: ''
  name: approximateCount
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: longDescription
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: termCount
  type: integer
- container: ''
  name: entityDefs
  type: string
- container: ''
  name: classificationDefs
  type: string
- container: ''
  name: enumDefs
  type: string
- container: ''
  name: relationshipDefs
  type: string
- container: ''
  name: businessMetadataDefs
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: guidAssignments
  type: string
- container: ''
  name: mutatedEntities
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: labels
  type: string
- container: ''
  name: classifications
  type: string
property_count: 34
provider_name: Apache Atlas
provider_slug: apache-atlas
slug: apache-atlas-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"atlas\": \"https://atlas.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AtlasLineageInfo\": \"atlas:AtlasLineageInfo\",\n    \"baseEntityGuid\": {\n      \"@id\": \"atlas:baseEntityGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineageDirection\": {\n      \"@id\": \"atlas:lineageDirection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineageDepth\": {\n      \"@id\": \"atlas:lineageDepth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"guidEntityMap\": {\n      \"@id\": \"atlas:guidEntityMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relations\": {\n      \"@id\": \"atlas:relations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AtlasEntityWithExtInfo\": \"atlas:AtlasEntityWithExtInfo\",\n    \"entity\": {\n      \"@id\": \"atlas:entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referredEntities\": {\n      \"\
  @id\": \"atlas:referredEntities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AtlasEntitiesWithExtInfo\": \"atlas:AtlasEntitiesWithExtInfo\",\n    \"entities\": {\n      \"@id\": \"atlas:entities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AtlasRelationship\": \"atlas:AtlasRelationship\",\n    \"guid\": {\n      \"@id\": \"atlas:guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"typeName\": {\n      \"@id\": \"atlas:typeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"atlas:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end1\": {\n      \"@id\": \"atlas:end1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end2\": {\n      \"@id\": \"atlas:end2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AtlasSearchResult\": \"atlas:AtlasSearchResult\",\n    \"queryType\": {\n      \"@id\": \"atlas:queryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"searchParameters\": {\n      \"@id\": \"atlas:searchParameters\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"approximateCount\": {\n      \"@id\": \"atlas:approximateCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AtlasGlossary\": \"atlas:AtlasGlossary\",\n    \"name\": {\n      \"@id\": \"atlas:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortDescription\": {\n      \"@id\": \"atlas:shortDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longDescription\": {\n      \"@id\": \"atlas:longDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"atlas:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"termCount\": {\n      \"@id\": \"atlas:termCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AtlasTypesDef\": \"atlas:AtlasTypesDef\",\n    \"entityDefs\": {\n      \"@id\": \"atlas:entityDefs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classificationDefs\": {\n      \"@id\": \"atlas:classificationDefs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enumDefs\"\
  : {\n      \"@id\": \"atlas:enumDefs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipDefs\": {\n      \"@id\": \"atlas:relationshipDefs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessMetadataDefs\": {\n      \"@id\": \"atlas:businessMetadataDefs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AtlasErrorResponse\": \"atlas:AtlasErrorResponse\",\n    \"requestId\": {\n      \"@id\": \"atlas:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"atlas:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"atlas:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityMutationResponse\": \"atlas:EntityMutationResponse\",\n    \"guidAssignments\": {\n      \"@id\": \"atlas:guidAssignments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mutatedEntities\": {\n      \"@id\": \"atlas:mutatedEntities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityWithExtInfo\"\
  : \"atlas:EntityWithExtInfo\",\n    \"AtlasEntity\": \"atlas:AtlasEntity\",\n    \"attributes\": {\n      \"@id\": \"atlas:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"atlas:labels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classifications\": {\n      \"@id\": \"atlas:classifications\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-atlas/refs/heads/main/json-ld/apache-atlas-context.jsonld
tags:
- Apache
- Big Data
- Compliance
- Data Governance
- Data Lineage
- Hadoop
- Metadata
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
