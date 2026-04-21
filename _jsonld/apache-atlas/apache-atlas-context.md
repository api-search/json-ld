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
