---
api_specs:
- filename: nasa-apod-openapi.yml
  format: yaml
  label: NASA Astronomy Picture of the Day (APOD) API
  slug: apod
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-apod-openapi.yml
- filename: nasa-mars-rover-photos-openapi.yml
  format: yaml
  label: NASA Mars Rover Photos API
  slug: mars-rover-photos
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-mars-rover-photos-openapi.yml
- filename: nasa-neo-openapi.yml
  format: yaml
  label: NASA NeoWs (Near Earth Object Web Service) API
  slug: neo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-neo-openapi.yml
- filename: nasa-donki-openapi.yml
  format: yaml
  label: NASA DONKI (Space Weather) API
  slug: donki
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-donki-openapi.yml
- filename: nasa-epic-openapi.yml
  format: yaml
  label: NASA EPIC (Earth Polychromatic Imaging Camera) API
  slug: epic
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-epic-openapi.yml
- filename: nasa-nasa-image-and-video-library-openapi.yml
  format: yaml
  label: NASA Image and Video Library API
  slug: image-and-video-library
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-nasa-image-and-video-library-openapi.yml
class_count: 35
classes:
- ApodImage
- RoverPhoto
- Rover
- Camera
- NearEarthObject
- CloseApproach
- CoronalMassEjection
- SolarFlare
- GeomagneticStorm
- EpicImage
- title
- explanation
- date
- earth_date
- url
- hdurl
- img_src
- media_type
- copyright
- name
- landing_date
- launch_date
- status
- nasa_jpl_url
- is_potentially_hazardous_asteroid
- close_approach_date
- orbiting_body
- startTime
- endTime
- peakTime
- classType
- sourceLocation
- caption
- identifier
- centroid_coordinates
context_file: json-ld/nasa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/json-ld/nasa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nasa from NASA.
layout: jsonld
name: Nasa Context
namespaces:
- prefix: nasa
  uri: https://api.nasa.gov/
- prefix: neo
  uri: https://api.nasa.gov/neo/rest/v1/
- prefix: donki
  uri: https://api.nasa.gov/DONKI/
- prefix: apod
  uri: https://api.nasa.gov/planetary/apod/
- prefix: marsRover
  uri: https://api.nasa.gov/mars-photos/api/v1/
- prefix: epic
  uri: https://api.nasa.gov/EPIC/api/
properties: []
property_count: 0
provider_name: NASA
provider_slug: nasa
slug: nasa-context
source_filename: nasa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"nasa\": \"https://api.nasa.gov/\",\n    \"neo\": \"https://api.nasa.gov/neo/rest/v1/\",\n    \"donki\": \"https://api.nasa.gov/DONKI/\",\n    \"apod\": \"https://api.nasa.gov/planetary/apod/\",\n    \"marsRover\": \"https://api.nasa.gov/mars-photos/api/v1/\",\n    \"epic\": \"https://api.nasa.gov/EPIC/api/\",\n    \"ApodImage\": \"nasa:ApodImage\",\n    \"RoverPhoto\": \"marsRover:RoverPhoto\",\n    \"Rover\": \"marsRover:Rover\",\n    \"Camera\": \"marsRover:Camera\",\n    \"NearEarthObject\": \"neo:NearEarthObject\",\n    \"CloseApproach\": \"neo:CloseApproach\",\n    \"CoronalMassEjection\": \"donki:CoronalMassEjection\",\n    \"SolarFlare\": \"donki:SolarFlare\",\n    \"GeomagneticStorm\": \"donki:GeomagneticStorm\",\n    \"EpicImage\": \"epic:EpicImage\",\n    \"title\": \"schema:name\",\n    \"explanation\": \"schema:description\",\n    \"date\": \"schema:dateCreated\",\n    \"earth_date\": \"schema:dateCreated\"\
  ,\n    \"url\": \"schema:url\",\n    \"hdurl\": \"schema:contentUrl\",\n    \"img_src\": \"schema:contentUrl\",\n    \"media_type\": \"schema:encodingFormat\",\n    \"copyright\": \"schema:copyrightHolder\",\n    \"name\": \"schema:name\",\n    \"landing_date\": \"schema:startDate\",\n    \"launch_date\": \"schema:startDate\",\n    \"status\": \"schema:status\",\n    \"nasa_jpl_url\": \"schema:url\",\n    \"is_potentially_hazardous_asteroid\": \"schema:warning\",\n    \"close_approach_date\": \"schema:dateCreated\",\n    \"orbiting_body\": \"schema:about\",\n    \"startTime\": \"schema:startDate\",\n    \"endTime\": \"schema:endDate\",\n    \"peakTime\": \"schema:dateModified\",\n    \"classType\": \"schema:category\",\n    \"sourceLocation\": \"schema:spatialCoverage\",\n    \"caption\": \"schema:caption\",\n    \"identifier\": \"schema:identifier\",\n    \"centroid_coordinates\": \"schema:geo\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/json-ld/nasa-context.jsonld
tags:
- Government
- Science
- Space
- JSON-LD
- Linked Data
- Semantic Web
---
