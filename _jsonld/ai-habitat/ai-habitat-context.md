---
class_count: 7
classes:
- SimulatorConfig
- AgentConfig
- SensorSpec
- Observation
- Episode
- NavigationGoal
- TaskConfig
context_file: json-ld/ai-habitat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ai-habitat/refs/heads/main/json-ld/ai-habitat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ai Habitat from AI Habitat.
layout: jsonld
name: Ai Habitat Context
namespaces:
- prefix: habitat
  uri: https://aihabitat.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: sceneId
  type: string
- container: ''
  name: agentId
  type: integer
- container: ''
  name: sensorType
  type: string
- container: set
  name: resolution
  type: integer
- container: ''
  name: episodeId
  type: string
- container: set
  name: startPosition
  type: double
- container: set
  name: goals
  type: reference
- container: ''
  name: maxEpisodeSteps
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: radius
  type: double
- container: set
  name: position
  type: double
- container: ''
  name: height
  type: double
- container: ''
  name: enablePhysics
  type: boolean
property_count: 13
provider_name: AI Habitat
provider_slug: ai-habitat
slug: ai-habitat-context
source_filename: ai-habitat-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"habitat\": \"https://aihabitat.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SimulatorConfig\": \"habitat:SimulatorConfig\",\n    \"AgentConfig\": \"habitat:AgentConfig\",\n    \"SensorSpec\": \"habitat:SensorSpec\",\n    \"Observation\": \"habitat:Observation\",\n    \"Episode\": \"habitat:Episode\",\n    \"NavigationGoal\": \"habitat:NavigationGoal\",\n    \"TaskConfig\": \"habitat:TaskConfig\",\n    \"sceneId\": {\n      \"@id\": \"habitat:scene_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentId\": {\n      \"@id\": \"habitat:agent_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sensorType\": {\n      \"@id\": \"habitat:sensor_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"habitat:resolution\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"episodeId\": {\n\
  \      \"@id\": \"habitat:episode_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startPosition\": {\n      \"@id\": \"habitat:start_position\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:double\"\n    },\n    \"goals\": {\n      \"@id\": \"habitat:goals\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"maxEpisodeSteps\": {\n      \"@id\": \"habitat:max_episode_steps\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"habitat:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"radius\": {\n      \"@id\": \"habitat:radius\",\n      \"@type\": \"xsd:double\"\n    },\n    \"position\": {\n      \"@id\": \"habitat:position\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:double\"\n    },\n    \"height\": {\n      \"@id\": \"habitat:height\",\n      \"@type\": \"xsd:double\"\n    },\n    \"enablePhysics\": {\n      \"@id\": \"habitat:enable_physics\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ai-habitat/refs/heads/main/json-ld/ai-habitat-context.jsonld
tags:
- Artificial Intelligence
- Simulation
- Embodied AI
- Robotics
- Computer Vision
- Reinforcement Learning
- Machine Learning
- Open Source
- Research
- JSON-LD
- Linked Data
- Semantic Web
---
