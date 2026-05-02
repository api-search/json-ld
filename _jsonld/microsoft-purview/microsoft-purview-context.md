---
api_specs:
- filename: microsoft-purview-catalog-openapi.yml
  format: yaml
  label: Microsoft Purview Catalog API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-catalog-openapi.yml
- filename: microsoft-purview-scanning-openapi.yml
  format: yaml
  label: Microsoft Purview Scanning API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-scanning-openapi.yml
- filename: microsoft-purview-account-openapi.yml
  format: yaml
  label: Microsoft Purview Account API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-account-openapi.yml
- filename: microsoft-purview-data-map-openapi.yml
  format: yaml
  label: Microsoft Purview Data Map API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-data-map-openapi.yml
- filename: microsoft-purview-metadata-policies-openapi.yml
  format: yaml
  label: Microsoft Purview Metadata Policies API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-metadata-policies-openapi.yml
- filename: microsoft-purview-workflow-openapi.yml
  format: yaml
  label: Microsoft Purview Workflow API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-workflow-openapi.yml
- filename: microsoft-purview-unified-catalog-openapi.yml
  format: yaml
  label: Microsoft Purview Unified Catalog API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-unified-catalog-openapi.yml
- filename: microsoft-purview-data-quality-openapi.yml
  format: yaml
  label: Microsoft Purview Data Quality API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-data-quality-openapi.yml
- filename: microsoft-purview-ediscovery-openapi.yml
  format: yaml
  label: Microsoft Purview eDiscovery API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-ediscovery-openapi.yml
- filename: microsoft-purview-information-protection-openapi.yml
  format: yaml
  label: Microsoft Purview Information Protection API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-information-protection-openapi.yml
- filename: microsoft-purview-data-security-governance-openapi.yml
  format: yaml
  label: Microsoft Purview Data Security and Governance API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-data-security-governance-openapi.yml
- filename: microsoft-purview-records-management-openapi.yml
  format: yaml
  label: Microsoft Purview Records Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/openapi/microsoft-purview-records-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-purview-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/json-ld/microsoft-purview-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Purview from Microsoft Purview.
layout: jsonld
name: Microsoft Purview Context
namespaces:
- prefix: purview
  uri: https://purview.azure.com/vocab#
- prefix: atlas
  uri: https://atlas.apache.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: dqv
  uri: http://www.w3.org/ns/dqv#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
properties:
- container: ''
  name: AtlasEntity
  type: ''
- container: ''
  name: AtlasGlossaryTerm
  type: ''
- container: ''
  name: AtlasGlossaryCategory
  type: ''
- container: ''
  name: AtlasGlossary
  type: ''
- container: ''
  name: AtlasClassification
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: Scan
  type: ''
- container: ''
  name: ScanResult
  type: ''
- container: ''
  name: AtlasLineageInfo
  type: ''
- container: ''
  name: AtlasRelationship
  type: ''
- container: ''
  name: PurviewAccount
  type: ''
- container: ''
  name: SensitivityLabel
  type: ''
- container: ''
  name: RetentionLabel
  type: ''
- container: ''
  name: MetadataPolicy
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: DataQualityScore
  type: ''
- container: ''
  name: BusinessDomain
  type: ''
- container: ''
  name: DataProduct
  type: ''
- container: ''
  name: EdiscoveryCase
  type: ''
property_count: 19
provider_name: Microsoft Purview
provider_slug: microsoft-purview
slug: microsoft-purview-context
source_filename: microsoft-purview-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"purview\": \"https://purview.azure.com/vocab#\",\n    \"atlas\": \"https://atlas.apache.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"dqv\": \"http://www.w3.org/ns/dqv#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n\n    \"AtlasEntity\": {\n      \"@id\": \"purview:AtlasEntity\",\n      \"@context\": {\n        \"guid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"typeName\": {\n          \"@id\": \"purview:typeName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"qualifiedName\"\
  : {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:maintainer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"purview:entityStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedBy\": {\n          \"@id\": \"purview:updatedBy\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"classifications\": {\n          \"@id\": \"purview:hasClassification\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": {\n          \"@id\": \"purview:hasLabel\",\n          \"@container\": \"@set\"\n        },\n        \"meanings\": {\n          \"@id\": \"purview:hasGlossaryTermAssignment\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"collectionId\": {\n          \"@id\": \"purview:belongsToCollection\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AtlasGlossaryTerm\": {\n      \"@id\": \"purview:GlossaryTerm\",\n      \"@context\": {\n        \"guid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"skos:prefLabel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shortDescription\": {\n          \"@id\": \"skos:definition\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"longDescription\": {\n          \"@id\": \"skos:note\",\n          \"@type\": \"xsd:string\"\n        },\n        \"abbreviation\": {\n          \"@id\": \"skos:altLabel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"purview:termStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"categories\": {\n          \"@id\": \"skos:broader\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"synonyms\": {\n          \"@id\": \"skos:exactMatch\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"antonyms\": {\n          \"@id\": \"purview:antonym\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"seeAlso\": {\n          \"@id\": \"skos:related\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"assignedEntities\"\
  : {\n          \"@id\": \"purview:appliedToEntity\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AtlasGlossaryCategory\": {\n      \"@id\": \"purview:GlossaryCategory\",\n      \"@context\": {\n        \"guid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"skos:prefLabel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shortDescription\": {\n          \"@id\": \"skos:definition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentCategory\": {\n          \"@id\": \"skos:broader\",\n          \"@type\": \"@id\"\n        },\n        \"childrenCategories\": {\n          \"@id\": \"skos:narrower\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"terms\": {\n          \"@id\": \"skos:hasTopConcept\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n \
  \       }\n      }\n    },\n\n    \"AtlasGlossary\": {\n      \"@id\": \"purview:Glossary\",\n      \"@context\": {\n        \"guid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shortDescription\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"dcterms:language\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AtlasClassification\": {\n      \"@id\": \"purview:Classification\",\n      \"@context\": {\n        \"typeName\": {\n          \"@id\": \"purview:classificationType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entityGuid\": {\n          \"@id\": \"purview:classifiedEntity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"propagate\": {\n          \"@id\": \"purview:propagates\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"dcat:DataService\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"kind\": {\n          \"@id\": \"purview:dataSourceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endpoint\": {\n          \"@id\": \"dcat:endpointURL\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Scan\": {\n      \"@id\": \"purview:Scan\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"kind\": {\n          \"@id\": \"purview:scanKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scanRulesetName\": {\n          \"@id\": \"purview:usesScanRuleset\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ScanResult\": {\n      \"@id\": \"purview:ScanResult\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"purview:scanStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"assetsDiscovered\": {\n          \"@id\": \"purview:assetsDiscovered\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"assetsClassified\": {\n          \"@id\": \"purview:assetsClassified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AtlasLineageInfo\": {\n      \"@id\": \"purview:LineageInfo\",\n      \"@context\": {\n        \"baseEntityGuid\": {\n          \"@id\": \"purview:lineageRoot\",\n          \"@type\": \"xsd:string\"\n   \
  \     },\n        \"lineageDirection\": {\n          \"@id\": \"purview:lineageDirection\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineageDepth\": {\n          \"@id\": \"purview:lineageDepth\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"relations\": {\n          \"@id\": \"prov:wasDerivedFrom\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AtlasRelationship\": {\n      \"@id\": \"purview:Relationship\",\n      \"@context\": {\n        \"guid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"typeName\": {\n          \"@id\": \"purview:relationshipType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"end1\": {\n          \"@id\": \"purview:sourceEntity\",\n          \"@type\": \"@id\"\n        },\n        \"end2\": {\n          \"@id\": \"purview:targetEntity\",\n          \"@type\": \"@id\"\n        },\n        \"status\"\
  : {\n          \"@id\": \"purview:relationshipStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PurviewAccount\": {\n      \"@id\": \"purview:Account\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"provisioningState\": {\n          \"@id\": \"purview:provisioningState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SensitivityLabel\": {\n      \"@id\": \"purview:SensitivityLabel\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sensitivity\": {\n          \"@id\": \"purview:sensitivityOrder\",\n          \"\
  @type\": \"xsd:integer\"\n        },\n        \"isActive\": {\n          \"@id\": \"purview:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasProtection\": {\n          \"@id\": \"purview:hasProtection\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"RetentionLabel\": {\n      \"@id\": \"purview:RetentionLabel\",\n      \"@context\": {\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"retentionTrigger\": {\n          \"@id\": \"purview:retentionTrigger\",\n          \"@type\": \"xsd:string\"\n        },\n        \"behaviorDuringRetentionPeriod\": {\n          \"@id\": \"purview:retentionBehavior\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actionAfterRetentionPeriod\": {\n          \"@id\": \"purview:postRetentionAction\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MetadataPolicy\": {\n      \"@id\": \"purview:MetadataPolicy\"\
  ,\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"purview:Workflow\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isEnabled\": {\n          \"@id\": \"purview:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"DataQualityScore\": {\n      \"@id\": \"dqv:QualityMeasurement\",\n      \"@context\": {\n        \"overallScore\": {\n          \"@id\": \"dqv:value\",\n          \"@type\": \"xsd:float\"\n        },\n        \"assetId\": {\n          \"@id\": \"dqv:computedOn\",\n        \
  \  \"@type\": \"xsd:string\"\n        },\n        \"evaluatedAt\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BusinessDomain\": {\n      \"@id\": \"purview:BusinessDomain\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentDomainId\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"DataProduct\": {\n      \"@id\": \"dcat:Dataset\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"businessDomainId\": {\n          \"@id\": \"\
  purview:belongsToBusinessDomain\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"EdiscoveryCase\": {\n      \"@id\": \"purview:EdiscoveryCase\",\n      \"@context\": {\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"purview:caseStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/json-ld/microsoft-purview-context.jsonld
tags:
- Compliance
- Data Catalog
- Data Classification
- Data Governance
- Data Loss Prevention
- Information Protection
- JSON-LD
- Linked Data
- Semantic Web
---
