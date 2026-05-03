---
api_specs:
- filename: weatherbit-current-weather-openapi-original.yml
  format: yaml
  label: Weatherbit Current Weather API
  slug: weatherbit-current-weather-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/openapi/weatherbit-current-weather-openapi-original.yml
class_count: 32
classes:
- AQCurrentGroup
- AQCurrent
- AQHour
- AQHourly
- CurrentObsGroup
- CurrentObs
- EnergyObsGroupForecast
- EnergyObsGroup
- EnergyObs
- EnergyObsSeries
- Error
- FCMinutelyOb
- FCMinutely
- ForecastAGObj
- ForecastAG
- ForecastDay
- ForecastHour
- ForecastHourly
- Forecast
- HistoryAGObj
- HistoryAG
- HistoryDayObj
- HistoryDay
- HistoryObj
- History
- HistorySubhourlyObj
- HistorySubhourly
- NormalsObj
- Normals
- WeatherAlertGroup
- WeatherAlert
- description
context_file: json-ld/weatherbit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/json-ld/weatherbit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Weatherbit from Weatherbit.
layout: jsonld
name: Weatherbit Context
namespaces:
- prefix: wb
  uri: https://api.weatherbit.io/v2.0/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: cityName
  type: string
- container: ''
  name: stateCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: lat
  type: decimal
- container: ''
  name: lon
  type: decimal
- container: ''
  name: timezone
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: aqi
  type: integer
- container: ''
  name: so2
  type: decimal
- container: ''
  name: no2
  type: decimal
- container: ''
  name: o3
  type: decimal
- container: ''
  name: pm25
  type: decimal
- container: ''
  name: pm10
  type: decimal
- container: ''
  name: ts
  type: decimal
- container: ''
  name: timestampLocal
  type: string
- container: ''
  name: timestampUtc
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: station
  type: string
- container: set
  name: sources
  type: string
- container: ''
  name: vis
  type: integer
- container: ''
  name: rh
  type: integer
- container: ''
  name: dewpt
  type: decimal
- container: ''
  name: windDir
  type: integer
- container: ''
  name: windCdir
  type: string
- container: ''
  name: windCdirFull
  type: string
- container: ''
  name: windSpeed
  type: decimal
- container: ''
  name: temp
  type: decimal
- container: ''
  name: appTemp
  type: decimal
- container: ''
  name: clouds
  type: integer
- container: ''
  name: weather
  type: reference
- container: ''
  name: icon
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: datetime
  type: string
- container: ''
  name: obTime
  type: string
- container: ''
  name: sunrise
  type: string
- container: ''
  name: sunset
  type: string
- container: ''
  name: slp
  type: decimal
- container: ''
  name: pres
  type: decimal
- container: ''
  name: uv
  type: decimal
- container: ''
  name: solarRad
  type: decimal
- container: ''
  name: ghi
  type: decimal
- container: ''
  name: dni
  type: decimal
- container: ''
  name: dhi
  type: decimal
- container: ''
  name: elevAngle
  type: decimal
- container: ''
  name: pod
  type: string
- container: ''
  name: precip
  type: decimal
- container: ''
  name: snow
  type: decimal
- container: ''
  name: thresholdUnits
  type: string
- container: ''
  name: thresholdValue
  type: string
- container: ''
  name: startDate
  type: integer
- container: ''
  name: endDate
  type: integer
- container: ''
  name: stationId
  type: string
- container: ''
  name: cdd
  type: decimal
- container: ''
  name: hdd
  type: decimal
- container: ''
  name: windSpd
  type: decimal
- container: ''
  name: tGhi
  type: decimal
- container: ''
  name: tDhi
  type: decimal
- container: ''
  name: tDni
  type: decimal
- container: ''
  name: sunHours
  type: decimal
- container: ''
  name: date
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: bulkSoilDensity
  type: decimal
- container: ''
  name: dlwrfAvg
  type: decimal
- container: ''
  name: dlwrfMax
  type: decimal
- container: ''
  name: dlwrfNet
  type: decimal
- container: ''
  name: dswrfAvg
  type: decimal
- container: ''
  name: dswrfMax
  type: decimal
- container: ''
  name: dswrfNet
  type: decimal
- container: ''
  name: evapotranspiration
  type: decimal
- container: ''
  name: presAvg
  type: decimal
- container: ''
  name: revisionStatus
  type: string
- container: ''
  name: skinTempAvg
  type: decimal
- container: ''
  name: skinTempMax
  type: decimal
- container: ''
  name: skinTempMin
  type: decimal
- container: ''
  name: soilm010cm
  type: decimal
- container: ''
  name: soilm100200cm
  type: decimal
- container: ''
  name: soilm1040cm
  type: decimal
- container: ''
  name: soilm40100cm
  type: decimal
- container: ''
  name: soilt010cm
  type: decimal
- container: ''
  name: soilt100200cm
  type: decimal
- container: ''
  name: soilt1040cm
  type: decimal
- container: ''
  name: soilt40100cm
  type: decimal
- container: ''
  name: specificHumidity
  type: decimal
- container: ''
  name: temp2mAvg
  type: decimal
- container: ''
  name: vSoilm010cm
  type: decimal
- container: ''
  name: vSoilm100200cm
  type: decimal
- container: ''
  name: vSoilm1040cm
  type: decimal
- container: ''
  name: vSoilm40100cm
  type: decimal
- container: ''
  name: validDate
  type: string
- container: ''
  name: wind10mSpdAvg
  type: decimal
- container: ''
  name: pop
  type: decimal
- container: ''
  name: windGustSpd
  type: decimal
- container: ''
  name: maxTemp
  type: decimal
- container: ''
  name: minTemp
  type: decimal
- container: ''
  name: appMaxTemp
  type: decimal
- container: ''
  name: appMinTemp
  type: decimal
- container: ''
  name: moonPhase
  type: decimal
- container: ''
  name: sunriseTs
  type: integer
- container: ''
  name: sunsetTs
  type: integer
- container: ''
  name: moonriseTs
  type: integer
- container: ''
  name: moonsetTs
  type: integer
- container: ''
  name: maxTempTs
  type: decimal
- container: ''
  name: minTempTs
  type: decimal
- container: ''
  name: maxWindSpd
  type: decimal
- container: ''
  name: maxWindDir
  type: integer
- container: ''
  name: maxWindSpdTs
  type: decimal
- container: ''
  name: maxUv
  type: decimal
- container: ''
  name: precipGpm
  type: decimal
- container: ''
  name: azimuth
  type: decimal
- container: ''
  name: precipRate
  type: decimal
- container: ''
  name: snowRate
  type: decimal
- container: ''
  name: month
  type: decimal
- container: ''
  name: minWindSpd
  type: decimal
- container: ''
  name: title
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: effectiveUtc
  type: string
- container: ''
  name: effectiveLocal
  type: string
- container: ''
  name: expiresUtc
  type: string
- container: ''
  name: expiresLocal
  type: string
- container: ''
  name: uri
  type: string
- container: set
  name: alerts
  type: string
property_count: 121
provider_name: Weatherbit
provider_slug: weatherbit
slug: weatherbit-context
source_filename: weatherbit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wb\": \"https://api.weatherbit.io/v2.0/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AQCurrentGroup\": \"wb:AQCurrentGroup\",\n    \"AQCurrent\": \"wb:AQCurrent\",\n    \"AQHour\": \"wb:AQHour\",\n    \"AQHourly\": \"wb:AQHourly\",\n    \"CurrentObsGroup\": \"wb:CurrentObsGroup\",\n    \"CurrentObs\": \"wb:CurrentObs\",\n    \"EnergyObsGroupForecast\": \"wb:EnergyObsGroupForecast\",\n    \"EnergyObsGroup\": \"wb:EnergyObsGroup\",\n    \"EnergyObs\": \"wb:EnergyObs\",\n    \"EnergyObsSeries\": \"wb:EnergyObsSeries\",\n    \"Error\": \"wb:Error\",\n    \"FCMinutelyOb\": \"wb:FCMinutelyOb\",\n    \"FCMinutely\": \"wb:FCMinutely\",\n    \"ForecastAGObj\": \"wb:ForecastAGObj\",\n    \"ForecastAG\": \"wb:ForecastAG\",\n    \"ForecastDay\": \"wb:ForecastDay\",\n    \"ForecastHour\": \"wb:ForecastHour\",\n    \"ForecastHourly\"\
  : \"wb:ForecastHourly\",\n    \"Forecast\": \"wb:Forecast\",\n    \"HistoryAGObj\": \"wb:HistoryAGObj\",\n    \"HistoryAG\": \"wb:HistoryAG\",\n    \"HistoryDayObj\": \"wb:HistoryDayObj\",\n    \"HistoryDay\": \"wb:HistoryDay\",\n    \"HistoryObj\": \"wb:HistoryObj\",\n    \"History\": \"wb:History\",\n    \"HistorySubhourlyObj\": \"wb:HistorySubhourlyObj\",\n    \"HistorySubhourly\": \"wb:HistorySubhourly\",\n    \"NormalsObj\": \"wb:NormalsObj\",\n    \"Normals\": \"wb:Normals\",\n    \"WeatherAlertGroup\": \"wb:WeatherAlertGroup\",\n    \"WeatherAlert\": \"wb:WeatherAlert\",\n    \"cityName\": {\n      \"@id\": \"wb:city_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"wb:state_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"wb:country_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lat\": {\n      \"@id\": \"wb:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lon\": {\n      \"@id\": \"\
  wb:lon\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"timezone\": {\n      \"@id\": \"wb:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"wb:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aqi\": {\n      \"@id\": \"wb:aqi\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"so2\": {\n      \"@id\": \"wb:so2\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"no2\": {\n      \"@id\": \"wb:no2\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"o3\": {\n      \"@id\": \"wb:o3\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pm25\": {\n      \"@id\": \"wb:pm25\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pm10\": {\n      \"@id\": \"wb:pm10\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ts\": {\n      \"@id\": \"wb:ts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"timestampLocal\": {\n      \"@id\": \"wb:timestamp_local\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestampUtc\":\
  \ {\n      \"@id\": \"wb:timestamp_utc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"wb:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"station\": {\n      \"@id\": \"wb:station\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"wb:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vis\": {\n      \"@id\": \"wb:vis\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rh\": {\n      \"@id\": \"wb:rh\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dewpt\": {\n      \"@id\": \"wb:dewpt\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"windDir\": {\n      \"@id\": \"wb:wind_dir\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"windCdir\": {\n      \"@id\": \"wb:wind_cdir\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windCdirFull\": {\n      \"@id\": \"wb:wind_cdir_full\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windSpeed\": {\n      \"@id\": \"wb:wind_speed\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"temp\": {\n      \"@id\": \"wb:temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"appTemp\": {\n      \"@id\": \"wb:app_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"clouds\": {\n      \"@id\": \"wb:clouds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weather\": {\n      \"@id\": \"wb:weather\",\n      \"@type\": \"@id\"\n    },\n    \"icon\": {\n      \"@id\": \"wb:icon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"wb:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"datetime\": {\n      \"@id\": \"wb:datetime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"obTime\": {\n      \"@id\": \"wb:ob_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunrise\": {\n      \"@id\": \"wb:sunrise\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sunset\": {\n      \"@id\": \"wb:sunset\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"slp\": {\n      \"@id\": \"wb:slp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pres\": {\n      \"@id\": \"wb:pres\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"uv\": {\n      \"@id\": \"wb:uv\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"solarRad\": {\n      \"@id\": \"wb:solar_rad\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ghi\": {\n      \"@id\": \"wb:ghi\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dni\": {\n      \"@id\": \"wb:dni\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dhi\": {\n      \"@id\": \"wb:dhi\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"elevAngle\": {\n      \"@id\": \"wb:elev_angle\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pod\": {\n      \"@id\": \"wb:pod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precip\": {\n      \"@id\": \"wb:precip\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"snow\": {\n      \"@id\": \"wb:snow\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"thresholdUnits\"\
  : {\n      \"@id\": \"wb:threshold_units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thresholdValue\": {\n      \"@id\": \"wb:threshold_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"wb:start_date\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endDate\": {\n      \"@id\": \"wb:end_date\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stationId\": {\n      \"@id\": \"wb:station_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cdd\": {\n      \"@id\": \"wb:cdd\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"hdd\": {\n      \"@id\": \"wb:hdd\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"windSpd\": {\n      \"@id\": \"wb:wind_spd\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tGhi\": {\n      \"@id\": \"wb:t_ghi\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tDhi\": {\n      \"@id\": \"wb:t_dhi\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tDni\": {\n      \"@id\": \"wb:t_dni\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"sunHours\": {\n      \"@id\": \"wb:sun_hours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"date\": {\n      \"@id\": \"wb:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"wb:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bulkSoilDensity\": {\n      \"@id\": \"wb:bulk_soil_density\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dlwrfAvg\": {\n      \"@id\": \"wb:dlwrf_avg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dlwrfMax\": {\n      \"@id\": \"wb:dlwrf_max\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dlwrfNet\": {\n      \"@id\": \"wb:dlwrf_net\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dswrfAvg\": {\n      \"@id\": \"wb:dswrf_avg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dswrfMax\": {\n      \"@id\": \"wb:dswrf_max\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dswrfNet\": {\n      \"@id\": \"wb:dswrf_net\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"evapotranspiration\"\
  : {\n      \"@id\": \"wb:evapotranspiration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"presAvg\": {\n      \"@id\": \"wb:pres_avg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"revisionStatus\": {\n      \"@id\": \"wb:revision_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skinTempAvg\": {\n      \"@id\": \"wb:skin_temp_avg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"skinTempMax\": {\n      \"@id\": \"wb:skin_temp_max\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"skinTempMin\": {\n      \"@id\": \"wb:skin_temp_min\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilm010cm\": {\n      \"@id\": \"wb:soilm_0_10cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilm100200cm\": {\n      \"@id\": \"wb:soilm_100_200cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilm1040cm\": {\n      \"@id\": \"wb:soilm_10_40cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilm40100cm\": {\n      \"@id\": \"wb:soilm_40_100cm\",\n      \"@type\":\
  \ \"xsd:decimal\"\n    },\n    \"soilt010cm\": {\n      \"@id\": \"wb:soilt_0_10cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilt100200cm\": {\n      \"@id\": \"wb:soilt_100_200cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilt1040cm\": {\n      \"@id\": \"wb:soilt_10_40cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"soilt40100cm\": {\n      \"@id\": \"wb:soilt_40_100cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"specificHumidity\": {\n      \"@id\": \"wb:specific_humidity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"temp2mAvg\": {\n      \"@id\": \"wb:temp_2m_avg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vSoilm010cm\": {\n      \"@id\": \"wb:v_soilm_0_10cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vSoilm100200cm\": {\n      \"@id\": \"wb:v_soilm_100_200cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vSoilm1040cm\": {\n      \"@id\": \"wb:v_soilm_10_40cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vSoilm40100cm\"\
  : {\n      \"@id\": \"wb:v_soilm_40_100cm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"validDate\": {\n      \"@id\": \"wb:valid_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wind10mSpdAvg\": {\n      \"@id\": \"wb:wind_10m_spd_avg\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pop\": {\n      \"@id\": \"wb:pop\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"windGustSpd\": {\n      \"@id\": \"wb:wind_gust_spd\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxTemp\": {\n      \"@id\": \"wb:max_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minTemp\": {\n      \"@id\": \"wb:min_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"appMaxTemp\": {\n      \"@id\": \"wb:app_max_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"appMinTemp\": {\n      \"@id\": \"wb:app_min_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"moonPhase\": {\n      \"@id\": \"wb:moon_phase\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sunriseTs\": {\n\
  \      \"@id\": \"wb:sunrise_ts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sunsetTs\": {\n      \"@id\": \"wb:sunset_ts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"moonriseTs\": {\n      \"@id\": \"wb:moonrise_ts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"moonsetTs\": {\n      \"@id\": \"wb:moonset_ts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxTempTs\": {\n      \"@id\": \"wb:max_temp_ts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minTempTs\": {\n      \"@id\": \"wb:min_temp_ts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxWindSpd\": {\n      \"@id\": \"wb:max_wind_spd\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxWindDir\": {\n      \"@id\": \"wb:max_wind_dir\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxWindSpdTs\": {\n      \"@id\": \"wb:max_wind_spd_ts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxUv\": {\n      \"@id\": \"wb:max_uv\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"precipGpm\": {\n\
  \      \"@id\": \"wb:precip_gpm\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"azimuth\": {\n      \"@id\": \"wb:azimuth\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"precipRate\": {\n      \"@id\": \"wb:precip_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"snowRate\": {\n      \"@id\": \"wb:snow_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"month\": {\n      \"@id\": \"wb:month\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minWindSpd\": {\n      \"@id\": \"wb:min_wind_spd\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"title\": {\n      \"@id\": \"wb:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"wb:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveUtc\": {\n      \"@id\": \"wb:effective_utc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveLocal\": {\n      \"@id\": \"wb:effective_local\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresUtc\": {\n      \"@id\": \"wb:expires_utc\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresLocal\": {\n      \"@id\": \"wb:expires_local\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"wb:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alerts\": {\n      \"@id\": \"wb:alerts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/json-ld/weatherbit-context.jsonld
tags:
- Weather
- Forecasting
- Historical Data
- Air Quality
- Alerts
- Agricultural Weather
- JSON-LD
- Linked Data
- Semantic Web
---
