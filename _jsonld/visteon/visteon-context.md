---
api_specs:
- filename: visteon-phoenix-openapi.yml
  format: yaml
  label: Visteon Phoenix API
  slug: phoenix-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/openapi/visteon-phoenix-openapi.yml
class_count: 39
classes:
- VehicleData
- AudioStatus
- NavigationRoute
- Location
- MediaTrack
- Display
- Call
- speed
- fuelLevel
- odometer
- engineRunning
- gearPosition
- address
- latitude
- longitude
- name
- description
- id
- temperature
- fanSpeed
- isAcOn
- isPlaying
- activeSource
- volume
- isMuted
- isConnected
- signalStrength
- batteryLevel
- eta
- distanceRemaining
- timeRemaining
- isActive
- title
- artist
- album
- duration
- resolution
- orientation
- brightness
context_file: json-ld/visteon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/json-ld/visteon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Visteon from Visteon.
layout: jsonld
name: Visteon Context
namespaces:
- prefix: visteon
  uri: https://developer.visteon.com/phoenix/
- prefix: auto
  uri: https://schema.org/
properties:
- container: ''
  name: hvac
  type: ''
- container: ''
  name: destination
  type: auto:Place
property_count: 2
provider_name: Visteon
provider_slug: visteon
slug: visteon-context
source_filename: visteon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"visteon\": \"https://developer.visteon.com/phoenix/\",\n    \"auto\": \"https://schema.org/\",\n\n    \"VehicleData\": \"auto:Vehicle\",\n    \"AudioStatus\": \"visteon:AudioStatus\",\n    \"NavigationRoute\": \"auto:Trip\",\n    \"Location\": \"auto:Place\",\n    \"MediaTrack\": \"auto:MusicRecording\",\n    \"Display\": \"visteon:Display\",\n    \"Call\": \"visteon:Call\",\n\n    \"speed\": \"auto:speed\",\n    \"fuelLevel\": \"visteon:fuelLevel\",\n    \"odometer\": \"auto:mileageFromOdometer\",\n    \"engineRunning\": \"visteon:engineRunning\",\n    \"gearPosition\": \"visteon:gearPosition\",\n    \"address\": \"auto:streetAddress\",\n    \"latitude\": \"auto:latitude\",\n    \"longitude\": \"auto:longitude\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"@id\",\n\n    \"hvac\": {\n      \"@id\": \"visteon:hvac\"\n    },\n    \"temperature\": \"auto:temperature\"\
  ,\n    \"fanSpeed\": \"visteon:fanSpeed\",\n    \"isAcOn\": \"visteon:isAcOn\",\n    \"isPlaying\": \"visteon:isPlaying\",\n    \"activeSource\": \"visteon:activeSource\",\n    \"volume\": \"visteon:volume\",\n    \"isMuted\": \"visteon:isMuted\",\n    \"isConnected\": \"visteon:isConnected\",\n    \"signalStrength\": \"visteon:signalStrength\",\n    \"batteryLevel\": \"visteon:batteryLevel\",\n    \"destination\": {\n      \"@id\": \"auto:itinerary\",\n      \"@type\": \"auto:Place\"\n    },\n    \"eta\": \"auto:arrivalTime\",\n    \"distanceRemaining\": \"visteon:distanceRemaining\",\n    \"timeRemaining\": \"visteon:timeRemaining\",\n    \"isActive\": \"visteon:isActive\",\n    \"title\": \"schema:name\",\n    \"artist\": \"schema:artist\",\n    \"album\": \"schema:inAlbum\",\n    \"duration\": \"schema:duration\",\n    \"resolution\": \"visteon:resolution\",\n    \"orientation\": \"visteon:orientation\",\n    \"brightness\": \"visteon:brightness\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/json-ld/visteon-context.jsonld
tags:
- Automotive
- Connected Car
- Infotainment
- IoT
- JSON-LD
- Linked Data
- Semantic Web
---
