---
class_count: 31
classes:
- Sketch
- HyperLogLog
- CountMinSketch
- BloomFilter
- TDigest
- ThetaSketch
- CuckooFilter
- id
- type
- name
- description
- precision
- errorRate
- confidence
- estimate
- upperBound
- lowerBound
- exactResult
- width
- depth
- capacity
- falsePositiveRate
- bitArraySize
- hashFunctions
- quantile
- compression
- theta
- k
- memoryUsage
- itemCount
- serialized
context_file: json-ld/sketches-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sketches/refs/heads/main/json-ld/sketches-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sketches from Sketches.
layout: jsonld
name: Sketches Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sketches
  uri: https://datasketches.apache.org/docs/
- prefix: dbpedia
  uri: http://dbpedia.org/resource/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 2
provider_name: Sketches
provider_slug: sketches
slug: sketches-context
source_filename: sketches-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sketches\": \"https://datasketches.apache.org/docs/\",\n    \"dbpedia\": \"http://dbpedia.org/resource/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Sketch\": \"sketches:Sketch\",\n    \"HyperLogLog\": \"sketches:HyperLogLog\",\n    \"CountMinSketch\": \"sketches:CountMinSketch\",\n    \"BloomFilter\": \"sketches:BloomFilter\",\n    \"TDigest\": \"sketches:TDigest\",\n    \"ThetaSketch\": \"sketches:ThetaSketch\",\n    \"CuckooFilter\": \"sketches:CuckooFilter\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n\n    \"precision\": \"sketches:precision\",\n    \"errorRate\": \"sketches:errorRate\",\n    \"confidence\": \"sketches:confidence\",\n    \"estimate\": \"sketches:estimate\",\n    \"upperBound\": \"sketches:upperBound\",\n    \"lowerBound\": \"sketches:lowerBound\",\n    \"\
  exactResult\": \"sketches:exactResult\",\n\n    \"width\": \"sketches:width\",\n    \"depth\": \"sketches:depth\",\n    \"capacity\": \"sketches:capacity\",\n    \"falsePositiveRate\": \"sketches:falsePositiveRate\",\n    \"bitArraySize\": \"sketches:bitArraySize\",\n    \"hashFunctions\": \"sketches:hashFunctions\",\n\n    \"quantile\": \"sketches:quantile\",\n    \"compression\": \"sketches:compression\",\n    \"theta\": \"sketches:theta\",\n    \"k\": \"sketches:nominalEntries\",\n\n    \"memoryUsage\": \"sketches:memoryUsageBytes\",\n    \"itemCount\": \"sketches:itemCount\",\n    \"serialized\": \"sketches:serializedRepresentation\",\n\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sketches/refs/heads/main/json-ld/sketches-context.jsonld
tags:
- Data Structures
- Probabilistic Algorithms
- Streaming Analytics
- Approximate Query Processing
- Big Data
- Real-Time Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
