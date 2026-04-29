---
class_count: 10
classes:
- identifier
- name
- description
- status
- dateCreated
- dateModified
- url
- region
- version
- format
context_file: json-ld/amazon-neptune-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Context
namespaces:
- prefix: neptune
  uri: https://docs.aws.amazon.com/neptune/latest/userguide/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: void
  uri: http://rdfs.org/ns/void#
- prefix: sd
  uri: http://www.w3.org/ns/sparql-service-description#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: NeptuneService
  type: ''
- container: ''
  name: DBCluster
  type: ''
- container: ''
  name: DBInstance
  type: ''
- container: ''
  name: Graph
  type: ''
- container: ''
  name: Vertex
  type: ''
- container: ''
  name: Edge
  type: ''
- container: ''
  name: GremlinQuery
  type: ''
- container: ''
  name: SparqlQuery
  type: ''
- container: ''
  name: OpenCypherQuery
  type: ''
- container: ''
  name: StreamRecord
  type: ''
- container: ''
  name: LoaderJob
  type: ''
- container: ''
  name: MLJob
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: AnalyticsGraph
  type: ''
- container: ''
  name: provider
  type: reference
property_count: 15
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"neptune\": \"https://docs.aws.amazon.com/neptune/latest/userguide/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"void\": \"http://rdfs.org/ns/void#\",\n    \"sd\": \"http://www.w3.org/ns/sparql-service-description#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"NeptuneService\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"serviceName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"provider\": \"schema:provider\",\n        \"url\": \"schema:url\",\n        \"documentation\": \"schema:documentation\"\n     \
  \ }\n    },\n\n    \"DBCluster\": {\n      \"@id\": \"neptune:api-reference-cluster.html\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"status\": \"schema:status\",\n        \"engine\": \"schema:applicationCategory\",\n        \"engineVersion\": \"schema:softwareVersion\",\n        \"endpoint\": \"schema:url\",\n        \"readerEndpoint\": \"schema:url\",\n        \"port\": \"schema:port\",\n        \"storageEncrypted\": \"schema:additionalProperty\",\n        \"deletionProtection\": \"schema:additionalProperty\",\n        \"createTime\": \"schema:dateCreated\",\n        \"members\": \"schema:hasPart\",\n        \"region\": \"schema:areaServed\",\n        \"arn\": \"dcterms:identifier\"\n      }\n    },\n\n    \"DBInstance\": {\n      \"@id\": \"neptune:api-reference-instance.html\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"instanceClass\": \"schema:additionalType\",\n   \
  \     \"status\": \"schema:status\",\n        \"engine\": \"schema:applicationCategory\",\n        \"engineVersion\": \"schema:softwareVersion\",\n        \"endpoint\": \"schema:url\",\n        \"availabilityZone\": \"schema:areaServed\",\n        \"clusterIdentifier\": \"schema:isPartOf\",\n        \"publiclyAccessible\": \"schema:additionalProperty\",\n        \"createTime\": \"schema:dateCreated\",\n        \"arn\": \"dcterms:identifier\"\n      }\n    },\n\n    \"Graph\": {\n      \"@id\": \"void:Dataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"endpoint\": \"void:sparqlEndpoint\",\n        \"triples\": \"void:triples\",\n        \"entities\": \"void:entities\",\n        \"properties\": \"void:properties\",\n        \"classes\": \"void:classes\"\n      }\n    },\n\n    \"Vertex\": {\n      \"@id\": \"rdf:Resource\",\n      \"@context\": {\n        \"vertexId\": \"schema:identifier\",\n        \"label\"\
  : \"rdfs:label\",\n        \"properties\": \"schema:additionalProperty\"\n      }\n    },\n\n    \"Edge\": {\n      \"@id\": \"rdf:Property\",\n      \"@context\": {\n        \"edgeId\": \"schema:identifier\",\n        \"label\": \"rdfs:label\",\n        \"source\": \"schema:source\",\n        \"target\": \"schema:target\",\n        \"properties\": \"schema:additionalProperty\"\n      }\n    },\n\n    \"GremlinQuery\": {\n      \"@id\": \"neptune:access-graph-gremlin.html\",\n      \"@context\": {\n        \"queryString\": \"schema:query\",\n        \"queryLanguage\": {\n          \"@id\": \"schema:programmingLanguage\",\n          \"@type\": \"@id\"\n        },\n        \"result\": \"schema:result\"\n      }\n    },\n\n    \"SparqlQuery\": {\n      \"@id\": \"sd:Service\",\n      \"@context\": {\n        \"queryString\": \"schema:query\",\n        \"queryLanguage\": {\n          \"@id\": \"schema:programmingLanguage\",\n          \"@type\": \"@id\"\n        },\n        \"endpoint\": \"\
  sd:endpoint\",\n        \"resultFormat\": \"sd:resultFormat\",\n        \"defaultDataset\": \"sd:defaultDataset\"\n      }\n    },\n\n    \"OpenCypherQuery\": {\n      \"@id\": \"neptune:access-graph-opencypher.html\",\n      \"@context\": {\n        \"queryString\": \"schema:query\",\n        \"queryLanguage\": {\n          \"@id\": \"schema:programmingLanguage\",\n          \"@type\": \"@id\"\n        },\n        \"result\": \"schema:result\"\n      }\n    },\n\n    \"StreamRecord\": {\n      \"@id\": \"neptune:streams.html\",\n      \"@context\": {\n        \"commitTimestamp\": \"schema:dateModified\",\n        \"eventId\": \"schema:identifier\",\n        \"operation\": \"schema:actionStatus\",\n        \"data\": \"schema:object\"\n      }\n    },\n\n    \"LoaderJob\": {\n      \"@id\": \"neptune:bulk-load.html\",\n      \"@context\": {\n        \"source\": \"schema:contentUrl\",\n        \"format\": \"schema:encodingFormat\",\n        \"status\": \"schema:actionStatus\",\n        \"\
  loadId\": \"schema:identifier\",\n        \"startTime\": \"schema:startTime\",\n        \"region\": \"schema:areaServed\"\n      }\n    },\n\n    \"MLJob\": {\n      \"@id\": \"neptune:machine-learning.html\",\n      \"@context\": {\n        \"jobId\": \"schema:identifier\",\n        \"status\": \"schema:actionStatus\",\n        \"inputLocation\": \"schema:contentUrl\",\n        \"outputLocation\": \"schema:contentUrl\",\n        \"modelType\": \"schema:additionalType\",\n        \"instanceType\": \"schema:additionalProperty\"\n      }\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"neptune:api-reference-snapshot.html\",\n      \"@context\": {\n        \"snapshotId\": \"schema:identifier\",\n        \"sourceCluster\": \"schema:isPartOf\",\n        \"createTime\": \"schema:dateCreated\",\n        \"status\": \"schema:status\",\n        \"encrypted\": \"schema:additionalProperty\",\n        \"arn\": \"dcterms:identifier\"\n      }\n    },\n\n    \"AnalyticsGraph\": {\n      \"@id\": \"\
  https://docs.aws.amazon.com/neptune-analytics/latest/userguide/what-is-neptune-analytics.html\",\n      \"@context\": {\n        \"graphId\": \"schema:identifier\",\n        \"graphName\": \"schema:name\",\n        \"status\": \"schema:status\",\n        \"provisionedMemory\": \"schema:additionalProperty\",\n        \"endpoint\": \"schema:url\",\n        \"vectorSearchDimension\": \"schema:additionalProperty\",\n        \"createTime\": \"schema:dateCreated\",\n        \"arn\": \"dcterms:identifier\"\n      }\n    },\n\n    \"identifier\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"url\": \"schema:url\",\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"region\": \"schema:areaServed\",\n    \"version\": \"schema:softwareVersion\",\n    \"format\"\
  : \"schema:encodingFormat\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-context.jsonld
tags:
- AWS
- Database
- Graph Database
- Gremlin
- Neptune
- Property Graph
- RDF
- SPARQL
- JSON-LD
- Linked Data
- Semantic Web
---
