---
api_specs:
- filename: sitecore-xm-cloud-rest-api-openapi.yml
  format: yaml
  label: Sitecore XM Cloud REST API
  slug: xm-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-xm-cloud-rest-api-openapi.yml
- filename: sitecore-cdp-rest-api-openapi.yml
  format: yaml
  label: Sitecore CDP REST API
  slug: cdp-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-cdp-rest-api-openapi.yml
- filename: sitecore-cdp-stream-api-asyncapi.yml
  format: yaml
  label: Sitecore CDP Stream API
  slug: cdp-stream-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/asyncapi/sitecore-cdp-stream-api-asyncapi.yml
- filename: sitecore-personalize-rest-api-openapi.yml
  format: yaml
  label: Sitecore Personalize REST API
  slug: personalize-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-personalize-rest-api-openapi.yml
- filename: sitecore-content-hub-rest-api-openapi.yml
  format: yaml
  label: Sitecore Content Hub REST API
  slug: content-hub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-content-hub-rest-api-openapi.yml
- filename: sitecore-ordercloud-api-openapi.yml
  format: yaml
  label: Sitecore OrderCloud API
  slug: ordercloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-ordercloud-api-openapi.yml
- filename: sitecore-discover-api-openapi.yml
  format: yaml
  label: Sitecore Discover API
  slug: discover-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-discover-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sitecore-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/json-ld/sitecore-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sitecore from sitecore.
layout: jsonld
name: Sitecore Context
namespaces:
- prefix: sc
  uri: https://www.sitecore.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: Site
  type: ''
- container: ''
  name: SiteCollection
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Guest
  type: ''
- container: ''
  name: GuestIdentifier
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: OrderItem
  type: ''
- container: ''
  name: StreamEvent
  type: ''
- container: ''
  name: ContentHubEntity
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: CommerceProduct
  type: ''
- container: ''
  name: FlowDefinition
  type: ''
- container: ''
  name: DecisionModel
  type: ''
- container: ''
  name: PublishingJob
  type: ''
property_count: 14
provider_name: sitecore
provider_slug: sitecore
slug: sitecore-context
source_filename: sitecore-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sc\": \"https://www.sitecore.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Site\": {\n      \"@id\": \"sc:Site\",\n      \"@context\": {\n        \"id\": \"sc:siteId\",\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"collectionId\": {\n          \"@id\": \"sc:collection\",\n          \"@type\": \"@id\"\n        },\n        \"renderingHost\": {\n          \"@id\": \"sc:renderingHost\",\n          \"@type\": \"@id\"\n        },\n        \"languages\": {\n          \"@id\": \"sc:languages\",\n          \"@container\": \"@set\"\n        },\n        \"sortOrder\": {\n          \"@id\": \"sc:sortOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"SiteCollection\": {\n    \
  \  \"@id\": \"sc:SiteCollection\",\n      \"@context\": {\n        \"id\": \"sc:collectionId\",\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"sites\": {\n          \"@id\": \"sc:hasSite\",\n          \"@container\": \"@set\",\n          \"@type\": \"@id\"\n        },\n        \"sortOrder\": {\n          \"@id\": \"sc:sortOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"sc:Page\",\n      \"@context\": {\n        \"id\": \"sc:pageId\",\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"path\": {\n          \"@id\": \"sc:itemPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"language\": {\n          \"@id\": \"sc:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\"\
  : \"sc:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"templateId\": {\n          \"@id\": \"sc:template\",\n          \"@type\": \"@id\"\n        },\n        \"publishingState\": {\n          \"@id\": \"sc:publishingState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Guest\": {\n      \"@id\": \"sc:Guest\",\n      \"@context\": {\n        \"guestRef\": \"sc:guestRef\",\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"gender\": \"schema:gender\",\n        \"identifiers\": {\n          \"@id\": \"sc:identifiers\",\n          \"@container\": \"@set\"\n        },\n        \"orders\": {\n          \"@id\": \"sc:hasOrder\",\n          \"@container\": \"@set\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n  \
  \        \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"GuestIdentifier\": {\n      \"@id\": \"sc:GuestIdentifier\",\n      \"@context\": {\n        \"provider\": {\n          \"@id\": \"sc:identityProvider\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"sc:identifierValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expiryDate\": {\n          \"@id\": \"sc:identifierExpiry\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"sc:Order\",\n      \"@context\": {\n        \"orderRef\": \"sc:orderRef\",\n        \"referenceId\": {\n          \"@id\": \"sc:externalOrderRef\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"sc:orderStatus\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"sc:currencyCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalPrice\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"orderedAt\": {\n          \"@id\": \"sc:orderedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"OrderItem\": {\n      \"@id\": \"sc:OrderItem\",\n      \"@context\": {\n        \"sku\": {\n          \"@id\": \"schema:sku\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"quantity\": {\n          \"@id\": \"schema:orderQuantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"price\"\
  : {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalPrice\": {\n          \"@id\": \"sc:lineTotal\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"StreamEvent\": {\n      \"@id\": \"sc:StreamEvent\",\n      \"@context\": {\n        \"meta_ref\": \"sc:eventRef\",\n        \"type\": {\n          \"@id\": \"sc:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"channel\": {\n          \"@id\": \"sc:channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"page\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"currency\": {\n          \"@id\": \"sc:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ContentHubEntity\": {\n      \"@id\": \"sc:ContentHubEntity\",\n      \"@context\"\
  : {\n        \"id\": \"sc:entityId\",\n        \"identifier\": {\n          \"@id\": \"sc:entityIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"definitionName\": {\n          \"@id\": \"sc:entityDefinition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cultures\": {\n          \"@id\": \"sc:cultures\",\n          \"@container\": \"@set\"\n        },\n        \"properties\": {\n          \"@id\": \"sc:entityProperties\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"sc:Asset\",\n      \"@context\": {\n        \"id\": \"sc:entityId\",\n        \"identifier\": \"sc:entityIdentifier\"\
  ,\n        \"fileName\": \"schema:name\",\n        \"fileUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"mimeType\": \"schema:encodingFormat\",\n        \"lifecycleState\": {\n          \"@id\": \"sc:lifecycleState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CommerceProduct\": {\n      \"@id\": \"sc:CommerceProduct\",\n      \"@context\": {\n        \"ID\": \"schema:productID\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Active\": {\n          \"@id\": \"sc:active\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"DefaultPriceScheduleID\": {\n          \"@id\": \"sc:priceSchedule\",\n          \"@type\": \"@id\"\n        },\n        \"xp\": {\n          \"@id\": \"sc:extendedProperties\"\n        }\n      }\n    },\n\n    \"FlowDefinition\": {\n      \"@id\": \"sc:FlowDefinition\",\n      \"@context\": {\n        \"ref\": \"sc:flowRef\",\n        \"name\": \"schema:name\",\n        \"type\": {\n          \"@id\": \"sc:flowType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"sc:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"variants\": {\n          \"@id\": \"sc:variants\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DecisionModel\": {\n  \
  \    \"@id\": \"sc:DecisionModel\",\n      \"@context\": {\n        \"ref\": \"sc:modelRef\",\n        \"name\": \"schema:name\",\n        \"status\": {\n          \"@id\": \"sc:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"revision\": {\n          \"@id\": \"sc:revision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"archived\": {\n          \"@id\": \"sc:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"deploymentConfiguration\": {\n          \"@id\": \"sc:deploymentConfiguration\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PublishingJob\": {\n      \"@id\": \"sc:PublishingJob\",\n      \"@context\": {\n        \"id\": \"sc:jobId\",\n        \"status\": {\n          \"@id\": \"sc:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalItems\": {\n         \
  \ \"@id\": \"sc:totalItems\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"processedItems\": {\n          \"@id\": \"sc:processedItems\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"failedItems\": {\n          \"@id\": \"sc:failedItems\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"sc:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/json-ld/sitecore-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
