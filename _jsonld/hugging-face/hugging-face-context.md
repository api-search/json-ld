---
class_count: 4
classes:
- id
- type
- name
- description
context_file: json-ld/hugging-face-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hugging-face/refs/heads/main/json-ld/hugging-face-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hugging Face from Hugging Face.
layout: jsonld
name: Hugging Face Context
namespaces:
- prefix: hf
  uri: https://huggingface.co/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: ml
  uri: http://ml-schema.org/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sc
  uri: https://schema.org/
- prefix: cr
  uri: http://mlcommons.org/croissant/
properties:
- container: ''
  name: Model
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: InferenceEndpoint
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: author
  type: reference
- container: ''
  name: license
  type: ''
- container: set
  name: keywords
  type: ''
- container: ''
  name: identifier
  type: ''
- container: ''
  name: image
  type: reference
- container: ''
  name: sameAs
  type: reference
property_count: 15
provider_name: Hugging Face
provider_slug: hugging-face
slug: hugging-face-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"hf\": \"https://huggingface.co/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"ml\": \"http://ml-schema.org/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sc\": \"https://schema.org/\",\n    \"cr\": \"http://mlcommons.org/croissant/\",\n\n    \"Model\": {\n      \"@id\": \"hf:Model\",\n      \"@context\": {\n        \"modelId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"pipeline_tag\": {\n          \"@id\": \"hf:pipelineTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"library_name\": {\n          \"@id\": \"hf:libraryName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"downloads\": {\n          \"@id\": \"hf:downloadCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"likes\": {\n          \"@id\": \"hf:likeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"private\": {\n\
  \          \"@id\": \"hf:isPrivate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"gated\": {\n          \"@id\": \"hf:isGated\"\n        },\n        \"sha\": {\n          \"@id\": \"hf:commitSha\",\n          \"@type\": \"xsd:string\"\n        },\n        \"safetensors\": {\n          \"@id\": \"hf:safetensorsInfo\",\n          \"@type\": \"@id\"\n        },\n        \"config\": {\n          \"@id\": \"hf:modelConfig\",\n          \"@type\": \"@id\"\n        },\n        \"spaces\": {\n          \"@id\": \"hf:usedInSpace\",\n          \"@container\": \"@set\"\n        },\n        \"base_model\": {\n          \"@id\": \"hf:baseModel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasets\": {\n          \"@id\": \"hf:trainedOnDataset\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"hf:Dataset\",\n      \"@context\": {\n        \"datasetId\": {\n          \"@id\": \"schema:identifier\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"task_categories\": {\n          \"@id\": \"hf:taskCategory\",\n          \"@container\": \"@set\"\n        },\n        \"size_categories\": {\n          \"@id\": \"hf:sizeCategory\",\n          \"@container\": \"@set\"\n        },\n        \"language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@container\": \"@set\"\n        },\n        \"downloads\": {\n          \"@id\": \"hf:downloadCount\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"likes\": {\n          \"@id\": \"hf:likeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"private\": {\n          \"@id\": \"hf:isPrivate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"gated\": {\n          \"@id\": \"hf:isGated\"\n        },\n        \"splits\": {\n          \"@id\": \"hf:split\",\n          \"@container\": \"@set\"\n        },\n        \"features\": {\n          \"@id\": \"hf:feature\",\n          \"@container\": \"@set\"\n        },\n        \"citation\": {\n          \"@id\": \"schema:citation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"num_rows\": {\n          \"@id\": \"hf:numberOfRows\",\n          \"@type\"\
  : \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"hf:Space\",\n      \"@context\": {\n        \"spaceId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"sdk\": {\n          \"@id\": \"hf:sdk\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sdk_version\": {\n          \"@id\": \"hf:sdkVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"likes\": {\n          \"@id\": \"hf:likeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n      \
  \  },\n        \"models\": {\n          \"@id\": \"hf:usesModel\",\n          \"@container\": \"@set\"\n        },\n        \"datasets\": {\n          \"@id\": \"hf:usesDataset\",\n          \"@container\": \"@set\"\n        },\n        \"runtime\": {\n          \"@id\": \"hf:runtimeStatus\",\n          \"@type\": \"@id\"\n        },\n        \"hardware\": {\n          \"@id\": \"hf:hardware\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"private\": {\n          \"@id\": \"hf:isPrivate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"xsd:string\"\n        },\n        \"duplicated_from\": {\n          \"@id\": \"hf:duplicatedFrom\",\n     \
  \     \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"InferenceEndpoint\": {\n      \"@id\": \"hf:InferenceEndpoint\",\n      \"@context\": {\n        \"endpointName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model\": {\n          \"@id\": \"hf:deployedModel\",\n          \"@type\": \"@id\"\n        },\n        \"provider\": {\n          \"@id\": \"hf:cloudProvider\",\n          \"@type\": \"@id\"\n        },\n        \"region\": {\n          \"@id\": \"hf:cloudRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accelerator\": {\n          \"@id\": \"hf:acceleratorType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"instanceType\": {\n          \"@id\": \"hf:instanceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"hf:endpointState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"securityType\": {\n          \"@id\": \"hf:securityType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minReplica\": {\n          \"@id\": \"hf:minReplica\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxReplica\": {\n          \"@id\": \"hf:maxReplica\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"hf:User\",\n      \"@context\": {\n        \"username\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullname\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"avatarUrl\": {\n          \"@id\": \"schema:image\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"plan\": {\n          \"@id\": \"hf:subscriptionPlan\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organizations\": {\n          \"@id\": \"schema:memberOf\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"hf:Organization\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullname\": {\n          \"@id\": \"schema:legalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isEnterprise\": {\n          \"@id\": \"hf:isEnterprise\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"plan\": {\n          \"@id\": \"hf:subscriptionPlan\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n\
  \      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\"\n    },\n    \"keywords\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"identifier\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"image\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"sameAs\": {\n      \"@id\": \"schema:sameAs\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hugging-face/refs/heads/main/json-ld/hugging-face-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
