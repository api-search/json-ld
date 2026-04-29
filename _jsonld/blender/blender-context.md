---
class_count: 11
classes:
- bl_idname
- bl_label
- bl_description
- bl_options
- blender_version_min
- tagline
- maintainer
- license
- addon
- operator
- module
context_file: json-ld/blender-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blender/refs/heads/main/json-ld/blender-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blender from Blender.
layout: jsonld
name: Blender Context
namespaces:
- prefix: blender
  uri: https://www.blender.org/ontology/
- prefix: bpy
  uri: https://docs.blender.org/api/current/
properties: []
property_count: 0
provider_name: Blender
provider_slug: blender
slug: blender-context
source_filename: blender-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"blender\": \"https://www.blender.org/ontology/\",\n    \"bpy\": \"https://docs.blender.org/api/current/\",\n    \"bl_idname\": \"blender:operatorId\",\n    \"bl_label\": \"name\",\n    \"bl_description\": \"description\",\n    \"bl_options\": \"blender:operatorOptions\",\n    \"blender_version_min\": \"blender:minimumVersion\",\n    \"tagline\": \"description\",\n    \"maintainer\": \"maintainer\",\n    \"license\": \"license\",\n    \"addon\": \"blender:addon\",\n    \"operator\": \"blender:operator\",\n    \"module\": \"blender:module\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blender/refs/heads/main/json-ld/blender-context.jsonld
tags:
- 3D
- Animation
- Game Development
- Modeling
- Open Source
- Python
- Rendering
- VFX
- JSON-LD
- Linked Data
- Semantic Web
---
