---
api_specs:
- filename: solcast-openapi.yml
  format: yaml
  label: Solcast API
  slug: solcast
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/openapi/solcast-openapi.yml
class_count: 0
classes: []
context_file: json-ld/solcast-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-ld/solcast-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solcast from Solcast.
layout: jsonld
name: Solcast Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: unit
  uri: http://qudt.org/vocab/unit/
- prefix: time
  uri: http://www.w3.org/2006/time#
- prefix: solcast
  uri: https://docs.solcast.com.au/#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: RadiationAndWeatherEstimated
  type: reference
- container: ''
  name: PvPowerEstimated
  type: reference
- container: ''
  name: SoilingEstimated
  type: reference
- container: ''
  name: AggregationDataPoint
  type: reference
- container: ''
  name: PvPowerSite
  type: reference
- container: ''
  name: period_end
  type: dateTime
- container: ''
  name: period
  type: string
- container: ''
  name: ghi
  type: decimal
- container: ''
  name: ghi10
  type: decimal
- container: ''
  name: ghi90
  type: decimal
- container: ''
  name: ebh
  type: decimal
- container: ''
  name: dni
  type: decimal
- container: ''
  name: dhi
  type: decimal
- container: ''
  name: clearsky_ghi
  type: decimal
- container: ''
  name: clearsky_ebh
  type: decimal
- container: ''
  name: clearsky_dni
  type: decimal
- container: ''
  name: clearsky_dhi
  type: decimal
- container: ''
  name: air_temp
  type: decimal
- container: ''
  name: cloud_opacity
  type: decimal
- container: ''
  name: wind_speed_10m
  type: decimal
- container: ''
  name: wind_direction_10m
  type: decimal
- container: ''
  name: relative_humidity
  type: decimal
- container: ''
  name: surface_pressure
  type: decimal
- container: ''
  name: precipitable_water
  type: decimal
- container: ''
  name: azimuth
  type: decimal
- container: ''
  name: zenith
  type: decimal
- container: ''
  name: elevation
  type: decimal
- container: ''
  name: snow_depth
  type: decimal
- container: ''
  name: snow_water_equivalent
  type: decimal
- container: ''
  name: snow_soiling_rooftop
  type: decimal
- container: ''
  name: pv_estimate
  type: decimal
- container: ''
  name: pv_estimate10
  type: decimal
- container: ''
  name: pv_estimate90
  type: decimal
- container: ''
  name: pv_power_rooftop
  type: decimal
- container: ''
  name: pv_power_advanced
  type: decimal
- container: ''
  name: soiling_loss
  type: decimal
- container: ''
  name: cleanliness
  type: decimal
- container: ''
  name: resource_id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: capacity
  type: decimal
- container: ''
  name: ac_capacity
  type: decimal
- container: ''
  name: dc_capacity
  type: decimal
- container: ''
  name: tilt
  type: decimal
- container: ''
  name: azimuth_panel
  type: decimal
- container: ''
  name: install_date
  type: date
- container: ''
  name: loss_factor
  type: decimal
- container: ''
  name: tracking_type
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: collection_id
  type: string
- container: ''
  name: aggregation_id
  type: string
- container: set
  name: estimated_actuals
  type: ''
- container: set
  name: forecasts
  type: ''
- container: set
  name: pv_power_sites
  type: ''
property_count: 56
provider_name: Solcast
provider_slug: solcast
slug: solcast-context
source_filename: solcast-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"unit\": \"http://qudt.org/vocab/unit/\",\n    \"time\": \"http://www.w3.org/2006/time#\",\n    \"solcast\": \"https://docs.solcast.com.au/#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"RadiationAndWeatherEstimated\": {\n      \"@id\": \"solcast:RadiationAndWeatherEstimated\",\n      \"@type\": \"@id\"\n    },\n    \"PvPowerEstimated\": {\n      \"@id\": \"solcast:PvPowerEstimated\",\n      \"@type\": \"@id\"\n    },\n    \"SoilingEstimated\": {\n      \"@id\": \"solcast:SoilingEstimated\",\n      \"@type\": \"@id\"\n    },\n    \"AggregationDataPoint\": {\n      \"@id\": \"solcast:AggregationDataPoint\",\n      \"@type\": \"@id\"\n    },\n    \"PvPowerSite\": {\n      \"@id\": \"solcast:PvPowerSite\",\n      \"@type\": \"@id\"\n    },\n\n    \"period_end\"\
  : {\n      \"@id\": \"time:hasEnd\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"period\": {\n      \"@id\": \"time:hasDuration\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"ghi\": {\n      \"@id\": \"solcast:globalHorizontalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"ghi10\": {\n      \"@id\": \"solcast:globalHorizontalIrradiance10thPercentile\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"ghi90\": {\n      \"@id\": \"solcast:globalHorizontalIrradiance90thPercentile\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"ebh\": {\n      \"@id\": \"solcast:beamHorizontalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"dni\": {\n      \"@id\": \"solcast:directNormalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n \
  \     \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"dhi\": {\n      \"@id\": \"solcast:diffuseHorizontalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"clearsky_ghi\": {\n      \"@id\": \"solcast:clearSkyGlobalHorizontalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"clearsky_ebh\": {\n      \"@id\": \"solcast:clearSkyBeamHorizontalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"clearsky_dni\": {\n      \"@id\": \"solcast:clearSkyDirectNormalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n    \"clearsky_dhi\": {\n      \"@id\": \"solcast:clearSkyDiffuseHorizontalIrradiance\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:W-PER-M2\" }\n    },\n\n    \"air_temp\"\
  : {\n      \"@id\": \"schema:temperature\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG_C\" }\n    },\n    \"cloud_opacity\": {\n      \"@id\": \"solcast:cloudOpacity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"wind_speed_10m\": {\n      \"@id\": \"solcast:windSpeedAt10m\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:M-PER-SEC\" }\n    },\n    \"wind_direction_10m\": {\n      \"@id\": \"solcast:windDirectionAt10m\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG\" }\n    },\n    \"relative_humidity\": {\n      \"@id\": \"schema:humidity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"surface_pressure\": {\n      \"@id\": \"solcast:surfacePressure\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:HectoPA\" }\n    },\n    \"precipitable_water\": {\n      \"@id\": \"solcast:precipitableWater\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\"\
  : { \"@id\": \"unit:KiloGM-PER-M2\" }\n    },\n\n    \"azimuth\": {\n      \"@id\": \"solcast:solarAzimuth\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG\" }\n    },\n    \"zenith\": {\n      \"@id\": \"solcast:solarZenith\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG\" }\n    },\n    \"elevation\": {\n      \"@id\": \"solcast:solarElevation\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG\" }\n    },\n\n    \"snow_depth\": {\n      \"@id\": \"solcast:snowDepth\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:M\" }\n    },\n    \"snow_water_equivalent\": {\n      \"@id\": \"solcast:snowWaterEquivalent\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:KiloGM-PER-M2\" }\n    },\n    \"snow_soiling_rooftop\": {\n      \"@id\": \"solcast:snowSoilingRooftop\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"pv_estimate\"\
  : {\n      \"@id\": \"solcast:pvEstimate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pv_estimate10\": {\n      \"@id\": \"solcast:pvEstimate10thPercentile\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pv_estimate90\": {\n      \"@id\": \"solcast:pvEstimate90thPercentile\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pv_power_rooftop\": {\n      \"@id\": \"solcast:pvPowerRooftop\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:KiloW\" }\n    },\n    \"pv_power_advanced\": {\n      \"@id\": \"solcast:pvPowerAdvanced\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:KiloW\" }\n    },\n\n    \"soiling_loss\": {\n      \"@id\": \"solcast:soilingLoss\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cleanliness\": {\n      \"@id\": \"solcast:panelCleanliness\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"resource_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"capacity\": {\n      \"@id\": \"solcast:systemCapacity\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:KiloW\" }\n    },\n    \"ac_capacity\": {\n      \"@id\": \"solcast:acCapacity\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:KiloW\" }\n    },\n    \"dc_capacity\": {\n      \"@id\": \"solcast:dcCapacity\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:KiloW\" }\n    },\n    \"tilt\": {\n      \"@id\": \"solcast:panelTilt\",\n      \"@type\": \"xsd:decimal\",\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG\" }\n    },\n    \"azimuth_panel\": {\n      \"@id\": \"solcast:panelAzimuth\",\n      \"@type\": \"xsd:decimal\"\
  ,\n      \"qudt:hasUnit\": { \"@id\": \"unit:DEG\" }\n    },\n    \"install_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"loss_factor\": {\n      \"@id\": \"solcast:systemLossFactor\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tracking_type\": {\n      \"@id\": \"solcast:trackingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"collection_id\": {\n      \"@id\": \"solcast:aggregationCollectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregation_id\": {\n      \"@id\": \"solcast:aggregationId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"estimated_actuals\": {\n      \"@id\": \"solcast:estimatedActuals\",\n      \"@container\": \"@set\"\n    },\n    \"forecasts\": {\n      \"@id\": \"solcast:forecasts\"\
  ,\n      \"@container\": \"@set\"\n    },\n    \"pv_power_sites\": {\n      \"@id\": \"solcast:pvPowerSites\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-ld/solcast-context.jsonld
tags:
- Solar
- Energy
- Forecasting
- Irradiance
- Weather
- Renewable Energy
- PV Power
- JSON-LD
- Linked Data
- Semantic Web
---
