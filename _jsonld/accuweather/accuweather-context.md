---
api_specs:
- filename: accuweather-openapi-original.yml
  format: yaml
  label: AccuWeather API
  slug: accuweather-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/accuweather/refs/heads/main/openapi/accuweather-openapi-original.yml
class_count: 47
classes:
- AdData
- AdInfo
- AdPageInfo
- Ad
- AirQuality
- AutocompleteLocation
- Bid
- ConfidenceQuantity
- ConfidenceRange
- CurrentConditions
- DailyForecast
- DailyIndex
- DeviceInfo
- EventConfidence
- ExtendedForecastInformation
- FavoriteLocation
- HalfDayForecast
- HourlyForecast
- IndexDay
- LandmarkReference
- LocationSettingsInfo
- MinuteCastForecast
- MinuteCastMinute
- OrtbContent
- OrtbData
- OrtbPublisher
- OrtbSegment
- OrtbSite
- PageInfo
- Partner
- Pollutant
- Polygon
- PrebidTimeoutOutVars
- PrecipitationSummary
- QuantityRangeEstimate
- RainePageView
- RecentLocation
- SessionInfo
- StormPosition
- Storm
- UserInfo
- UserNetwork
- UTMInfo
- UVIndex
- WeatherInfo
- name
- url
context_file: json-ld/accuweather-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/accuweather/refs/heads/main/json-ld/accuweather-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Accuweather from AccuWeather.
layout: jsonld
name: Accuweather Context
namespaces:
- prefix: acw
  uri: https://developer.accuweather.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accuId
  type: integer
- container: ''
  name: activityType
  type: string
- container: ''
  name: adDivId
  type: string
- container: ''
  name: adInfo
  type: string
- container: ''
  name: adPageInfo
  type: string
- container: ''
  name: adSlots
  type: string
- container: ''
  name: adUnitCode
  type: string
- container: ''
  name: adminCode
  type: string
- container: ''
  name: ads
  type: string
- container: ''
  name: airQuality
  type: string
- container: ''
  name: apparentTempImperial
  type: decimal
- container: ''
  name: awxTimeout
  type: integer
- container: ''
  name: basin
  type: string
- container: ''
  name: basinId
  type: string
- container: ''
  name: basinSlug
  type: string
- container: ''
  name: bidder
  type: string
- container: set
  name: bidders
  type: string
- container: ''
  name: bot
  type: boolean
- container: ''
  name: brand
  type: string
- container: ''
  name: bundleId
  type: string
- container: ''
  name: bundleUrl
  type: string
- container: ''
  name: buyItNowSkipGoogleAdManager
  type: boolean
- container: ''
  name: campaign
  type: string
- container: set
  name: categories
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: categoryColor
  type: string
- container: ''
  name: ceiling
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: cloudCover
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: color
  type: string
- container: ''
  name: concentration
  type: string
- container: ''
  name: conditions
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: context
  type: string
- container: ''
  name: cookie3p
  type: string
- container: set
  name: coordinates
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: date
  type: dateTime
- container: ''
  name: dateTime
  type: string
- container: ''
  name: dateTimeLabel
  type: string
- container: ''
  name: dateTimeLabelShort
  type: string
- container: ''
  name: day
  type: string
- container: ''
  name: dayOfWeek
  type: string
- container: ''
  name: dayOfWeekAbbreviated
  type: string
- container: set
  name: days
  type: string
- container: ''
  name: dbz
  type: decimal
- container: ''
  name: device
  type: string
- container: ''
  name: deviceClass
  type: string
- container: ''
  name: dewPoint
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: disableInitialAdLoad
  type: boolean
- container: ''
  name: displayAmount
  type: string
- container: ''
  name: displayDate
  type: string
- container: ''
  name: displayHighTemperature
  type: string
- container: ''
  name: displayLowTemperature
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: displayRealFeel
  type: string
- container: ''
  name: displayRealFeelShade
  type: string
- container: ''
  name: displayTemperature
  type: string
- container: ''
  name: displayTime
  type: string
- container: ''
  name: distance
  type: string
- container: ''
  name: dma
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: dominantPollutant
  type: string
- container: ''
  name: end
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
- container: ''
  name: epoch
  type: integer
- container: ''
  name: epochEndDate
  type: integer
- container: ''
  name: epochStartDate
  type: integer
- container: ''
  name: event
  type: string
- container: ''
  name: eventKey
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: extended
  type: string
- container: ''
  name: extensions
  type: string
- container: ''
  name: forecastRanges
  type: string
- container: ''
  name: fullDayOfWeek
  type: string
- container: ''
  name: globalAdConfig
  type: string
- container: ''
  name: governmentId
  type: integer
- container: ''
  name: gptEnableSingleRequest
  type: boolean
- container: ''
  name: gptLazyLoading
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: gusts
  type: string
- container: ''
  name: hasAlert
  type: boolean
- container: ''
  name: hasPrivacyPolicy
  type: boolean
- container: ''
  name: hazardStatement
  type: string
- container: ''
  name: high
  type: string
- container: ''
  name: higher
  type: string
- container: ''
  name: humidity
  type: string
- container: ''
  name: humidityValue
  type: integer
- container: ''
  name: ice
  type: string
- container: ''
  name: icon
  type: integer
- container: ''
  name: iconCode
  type: integer
- container: ''
  name: iconPhrase
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: index
  type: decimal
- container: ''
  name: indexName
  type: string
- container: ''
  name: indexType
  type: string
- container: ''
  name: indoorHumidity
  type: string
- container: ''
  name: indoorHumidityCategory
  type: string
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: isBefore7PM
  type: boolean
- container: ''
  name: isBuyItNow
  type: boolean
- container: ''
  name: isCurrent
  type: boolean
- container: ''
  name: isDayLight
  type: boolean
- container: ''
  name: isDayTime
  type: boolean
- container: ''
  name: isFuture
  type: boolean
- container: ''
  name: isHistorical
  type: boolean
- container: ''
  name: isMarked
  type: boolean
- container: ''
  name: isOptimizedForMobile
  type: boolean
- container: ''
  name: isPeak
  type: boolean
- container: ''
  name: isPrebidDisabled
  type: boolean
- container: ''
  name: javascriptBody
  type: string
- container: ''
  name: javascriptHead
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: keywords
  type: string
- container: ''
  name: landmark
  type: string
- container: set
  name: landmarkReferences
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: level
  type: string
- container: ''
  name: likely
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: localDate
  type: dateTime
- container: ''
  name: localDayOfWeek
  type: string
- container: ''
  name: localEnd
  type: dateTime
- container: ''
  name: localStart
  type: dateTime
- container: ''
  name: localTime
  type: string
- container: ''
  name: localizedStartDate
  type: string
- container: ''
  name: localizedStatus
  type: string
- container: ''
  name: locationKey
  type: string
- container: ''
  name: locationSettingsInfo
  type: string
- container: ''
  name: locationType
  type: string
- container: ''
  name: logo
  type: string
- container: ''
  name: longDisplayDate
  type: string
- container: ''
  name: longName
  type: string
- container: ''
  name: longPhrase
  type: string
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: low
  type: string
- container: ''
  name: lower
  type: string
- container: ''
  name: maximumSustainedWind
  type: string
- container: ''
  name: maximumSustainedWindValue
  type: decimal
- container: ''
  name: maximumWindGust
  type: string
- container: ''
  name: maximumWindGustValue
  type: decimal
- container: ''
  name: medium
  type: string
- container: ''
  name: minimumPressure
  type: string
- container: ''
  name: minute
  type: integer
- container: ''
  name: minuteCastForecast
  type: string
- container: set
  name: minutes
  type: string
- container: ''
  name: network
  type: string
- container: ''
  name: night
  type: string
- container: ''
  name: now
  type: string
- container: ''
  name: numberOfAlerts
  type: integer
- container: ''
  name: offset
  type: string
- container: ''
  name: ortbConfig
  type: string
- container: ''
  name: overallIndex
  type: decimal
- container: ''
  name: overallPlumeLabsIndex
  type: decimal
- container: ''
  name: page
  type: string
- container: set
  name: pageCategories
  type: string
- container: ''
  name: pageUrl
  type: string
- container: ''
  name: params
  type: string
- container: ''
  name: partner
  type: string
- container: ''
  name: past12Hours
  type: string
- container: ''
  name: past18Hours
  type: string
- container: ''
  name: past24Hours
  type: string
- container: ''
  name: past3Hours
  type: string
- container: ''
  name: past6Hours
  type: string
- container: ''
  name: past9Hours
  type: string
- container: ''
  name: pastHour
  type: string
- container: ''
  name: peakPosition
  type: string
- container: ''
  name: phrase
  type: string
- container: ''
  name: platform
  type: string
- container: set
  name: pollutants
  type: string
- container: set
  name: position
  type: decimal
- container: ''
  name: postalCode
  type: string
- container: ''
  name: ppid
  type: string
- container: ''
  name: prebidTimeout
  type: integer
- container: ''
  name: precip
  type: string
- container: ''
  name: precipSummary
  type: string
- container: ''
  name: precipitation
  type: string
- container: ''
  name: precipitationType
  type: string
- container: ''
  name: pressure
  type: string
- container: ''
  name: probability
  type: integer
- container: ''
  name: productQuality
  type: string
- container: ''
  name: publisher
  type: string
- container: ''
  name: rain
  type: string
- container: ''
  name: realFeel
  type: string
- container: ''
  name: realFeelPhrase
  type: string
- container: ''
  name: realFeelShade
  type: string
- container: ''
  name: realFeelShadePhrase
  type: string
- container: ''
  name: realFeelShadeValue
  type: decimal
- container: ''
  name: realFeelValue
  type: decimal
- container: ''
  name: referrer
  type: string
- container: ''
  name: referrerUrl
  type: string
- container: ''
  name: region
  type: string
- container: set
  name: sectionCategories
  type: string
- container: set
  name: segments
  type: string
- container: ''
  name: session
  type: string
- container: ''
  name: shortDateShortTimeLabel
  type: string
- container: ''
  name: shortDayOfWeek
  type: string
- container: ''
  name: siteName
  type: string
- container: ''
  name: slot
  type: string
- container: ''
  name: snow
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sourceRelationship
  type: string
- container: ''
  name: speed
  type: string
- container: ''
  name: start
  type: dateTime
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: startEpoch
  type: integer
- container: ''
  name: stationCode
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusIcon
  type: string
- container: ''
  name: statusIconString
  type: string
- container: ''
  name: statusName
  type: string
- container: ''
  name: stormLink
  type: string
- container: set
  name: stormPositions
  type: string
- container: ''
  name: summary60
  type: string
- container: set
  name: supportedDataSets
  type: string
- container: ''
  name: supportsEventConfidence
  type: boolean
- container: ''
  name: supportsMinuteCast
  type: boolean
- container: ''
  name: temperature
  type: string
- container: ''
  name: temperatureValue
  type: decimal
- container: ''
  name: term
  type: string
- container: ''
  name: test
  type: string
- container: ''
  name: testVariant
  type: string
- container: ''
  name: throughput
  type: string
- container: ''
  name: thunderstormProbability
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: unitType
  type: integer
- container: ''
  name: updatedStormName
  type: string
- container: ''
  name: upr
  type: decimal
- container: ''
  name: user
  type: string
- container: ''
  name: uspString
  type: string
- container: ''
  name: utm
  type: string
- container: ''
  name: uv
  type: string
- container: ''
  name: value
  type: decimal
- container: ''
  name: version
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: weather
  type: string
- container: ''
  name: wind
  type: string
- container: ''
  name: windDegrees
  type: decimal
- container: ''
  name: windDirection
  type: string
- container: ''
  name: windSpeedImperial
  type: decimal
- container: ''
  name: windValue
  type: decimal
- container: ''
  name: year
  type: integer
property_count: 250
provider_name: AccuWeather
provider_slug: accuweather
slug: accuweather-context
source_filename: accuweather-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acw\": \"https://developer.accuweather.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdData\": \"acw:AdData\",\n    \"AdInfo\": \"acw:AdInfo\",\n    \"AdPageInfo\": \"acw:AdPageInfo\",\n    \"Ad\": \"acw:Ad\",\n    \"AirQuality\": \"acw:AirQuality\",\n    \"AutocompleteLocation\": \"acw:AutocompleteLocation\",\n    \"Bid\": \"acw:Bid\",\n    \"ConfidenceQuantity\": \"acw:ConfidenceQuantity\",\n    \"ConfidenceRange\": \"acw:ConfidenceRange\",\n    \"CurrentConditions\": \"acw:CurrentConditions\",\n    \"DailyForecast\": \"acw:DailyForecast\",\n    \"DailyIndex\": \"acw:DailyIndex\",\n    \"DeviceInfo\": \"acw:DeviceInfo\",\n    \"EventConfidence\": \"acw:EventConfidence\",\n    \"ExtendedForecastInformation\": \"acw:ExtendedForecastInformation\",\n    \"FavoriteLocation\": \"acw:FavoriteLocation\",\n    \"\
  HalfDayForecast\": \"acw:HalfDayForecast\",\n    \"HourlyForecast\": \"acw:HourlyForecast\",\n    \"IndexDay\": \"acw:IndexDay\",\n    \"LandmarkReference\": \"acw:LandmarkReference\",\n    \"LocationSettingsInfo\": \"acw:LocationSettingsInfo\",\n    \"MinuteCastForecast\": \"acw:MinuteCastForecast\",\n    \"MinuteCastMinute\": \"acw:MinuteCastMinute\",\n    \"OrtbContent\": \"acw:OrtbContent\",\n    \"OrtbData\": \"acw:OrtbData\",\n    \"OrtbPublisher\": \"acw:OrtbPublisher\",\n    \"OrtbSegment\": \"acw:OrtbSegment\",\n    \"OrtbSite\": \"acw:OrtbSite\",\n    \"PageInfo\": \"acw:PageInfo\",\n    \"Partner\": \"acw:Partner\",\n    \"Pollutant\": \"acw:Pollutant\",\n    \"Polygon\": \"acw:Polygon\",\n    \"PrebidTimeoutOutVars\": \"acw:PrebidTimeoutOutVars\",\n    \"PrecipitationSummary\": \"acw:PrecipitationSummary\",\n    \"QuantityRangeEstimate\": \"acw:QuantityRangeEstimate\",\n    \"RainePageView\": \"acw:RainePageView\",\n    \"RecentLocation\": \"acw:RecentLocation\",\n    \"SessionInfo\"\
  : \"acw:SessionInfo\",\n    \"StormPosition\": \"acw:StormPosition\",\n    \"Storm\": \"acw:Storm\",\n    \"UserInfo\": \"acw:UserInfo\",\n    \"UserNetwork\": \"acw:UserNetwork\",\n    \"UTMInfo\": \"acw:UTMInfo\",\n    \"UVIndex\": \"acw:UVIndex\",\n    \"WeatherInfo\": \"acw:WeatherInfo\",\n    \"accuId\": {\n      \"@id\": \"acw:accuId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activityType\": {\n      \"@id\": \"acw:activityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adDivId\": {\n      \"@id\": \"acw:adDivId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adInfo\": {\n      \"@id\": \"acw:adInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adPageInfo\": {\n      \"@id\": \"acw:adPageInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adSlots\": {\n      \"@id\": \"acw:adSlots\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adUnitCode\": {\n      \"@id\": \"acw:adUnitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adminCode\": {\n     \
  \ \"@id\": \"acw:adminCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ads\": {\n      \"@id\": \"acw:ads\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airQuality\": {\n      \"@id\": \"acw:airQuality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apparentTempImperial\": {\n      \"@id\": \"acw:apparentTempImperial\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"awxTimeout\": {\n      \"@id\": \"acw:awxTimeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"basin\": {\n      \"@id\": \"acw:basin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basinId\": {\n      \"@id\": \"acw:basinId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basinSlug\": {\n      \"@id\": \"acw:basinSlug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bidder\": {\n      \"@id\": \"acw:bidder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bidders\": {\n      \"@id\": \"acw:bidders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bot\": {\n  \
  \    \"@id\": \"acw:bot\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"brand\": {\n      \"@id\": \"acw:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundleId\": {\n      \"@id\": \"acw:bundleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundleUrl\": {\n      \"@id\": \"acw:bundleUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buyItNowSkipGoogleAdManager\": {\n      \"@id\": \"acw:buyItNowSkipGoogleAdManager\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"campaign\": {\n      \"@id\": \"acw:campaign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categories\": {\n      \"@id\": \"acw:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"acw:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryColor\": {\n      \"@id\": \"acw:categoryColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ceiling\": {\n      \"@id\": \"acw:ceiling\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"city\": {\n      \"@id\": \"acw:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudCover\": {\n      \"@id\": \"acw:cloudCover\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"acw:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"color\": {\n      \"@id\": \"acw:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"concentration\": {\n      \"@id\": \"acw:concentration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conditions\": {\n      \"@id\": \"acw:conditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"acw:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"acw:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cookie3p\": {\n      \"@id\": \"acw:cookie3p\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coordinates\": {\n      \"@id\": \"acw:coordinates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"country\": {\n      \"@id\": \"acw:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"acw:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"acw:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"acw:date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateTime\": {\n      \"@id\": \"acw:dateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateTimeLabel\": {\n      \"@id\": \"acw:dateTimeLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateTimeLabelShort\": {\n      \"@id\": \"acw:dateTimeLabelShort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"day\": {\n      \"@id\": \"acw:day\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayOfWeek\": {\n      \"@id\": \"acw:dayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayOfWeekAbbreviated\": {\n      \"@id\": \"acw:dayOfWeekAbbreviated\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"days\": {\n      \"@id\": \"acw:days\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbz\": {\n      \"@id\": \"acw:dbz\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"device\": {\n      \"@id\": \"acw:device\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceClass\": {\n      \"@id\": \"acw:deviceClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dewPoint\": {\n      \"@id\": \"acw:dewPoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"acw:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disableInitialAdLoad\": {\n      \"@id\": \"acw:disableInitialAdLoad\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"displayAmount\": {\n      \"@id\": \"acw:displayAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayDate\": {\n      \"@id\": \"acw:displayDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayHighTemperature\": {\n      \"@id\": \"acw:displayHighTemperature\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"displayLowTemperature\": {\n      \"@id\": \"acw:displayLowTemperature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"acw:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayRealFeel\": {\n      \"@id\": \"acw:displayRealFeel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayRealFeelShade\": {\n      \"@id\": \"acw:displayRealFeelShade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayTemperature\": {\n      \"@id\": \"acw:displayTemperature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayTime\": {\n      \"@id\": \"acw:displayTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distance\": {\n      \"@id\": \"acw:distance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dma\": {\n      \"@id\": \"acw:dma\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"acw:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dominantPollutant\"\
  : {\n      \"@id\": \"acw:dominantPollutant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"acw:end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"acw:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"epoch\": {\n      \"@id\": \"acw:epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"epochEndDate\": {\n      \"@id\": \"acw:epochEndDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"epochStartDate\": {\n      \"@id\": \"acw:epochStartDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"event\": {\n      \"@id\": \"acw:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventKey\": {\n      \"@id\": \"acw:eventKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"acw:eventName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extended\": {\n      \"@id\": \"acw:extended\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extensions\": {\n      \"@id\": \"acw:extensions\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastRanges\": {\n      \"@id\": \"acw:forecastRanges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullDayOfWeek\": {\n      \"@id\": \"acw:fullDayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"globalAdConfig\": {\n      \"@id\": \"acw:globalAdConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"governmentId\": {\n      \"@id\": \"acw:governmentId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gptEnableSingleRequest\": {\n      \"@id\": \"acw:gptEnableSingleRequest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"gptLazyLoading\": {\n      \"@id\": \"acw:gptLazyLoading\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"acw:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gusts\": {\n      \"@id\": \"acw:gusts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasAlert\": {\n      \"@id\": \"acw:hasAlert\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasPrivacyPolicy\"\
  : {\n      \"@id\": \"acw:hasPrivacyPolicy\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hazardStatement\": {\n      \"@id\": \"acw:hazardStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"high\": {\n      \"@id\": \"acw:high\",\n      \"@type\": \"xsd:string\"\n    },\n    \"higher\": {\n      \"@id\": \"acw:higher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"humidity\": {\n      \"@id\": \"acw:humidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"humidityValue\": {\n      \"@id\": \"acw:humidityValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ice\": {\n      \"@id\": \"acw:ice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icon\": {\n      \"@id\": \"acw:icon\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"iconCode\": {\n      \"@id\": \"acw:iconCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"iconPhrase\": {\n      \"@id\": \"acw:iconPhrase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"acw:id\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"acw:index\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"indexName\": {\n      \"@id\": \"acw:indexName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indexType\": {\n      \"@id\": \"acw:indexType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indoorHumidity\": {\n      \"@id\": \"acw:indoorHumidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indoorHumidityCategory\": {\n      \"@id\": \"acw:indoorHumidityCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isActive\": {\n      \"@id\": \"acw:isActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isBefore7PM\": {\n      \"@id\": \"acw:isBefore7PM\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isBuyItNow\": {\n      \"@id\": \"acw:isBuyItNow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isCurrent\": {\n      \"@id\": \"acw:isCurrent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDayLight\": {\n      \"@id\": \"\
  acw:isDayLight\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDayTime\": {\n      \"@id\": \"acw:isDayTime\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFuture\": {\n      \"@id\": \"acw:isFuture\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isHistorical\": {\n      \"@id\": \"acw:isHistorical\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isMarked\": {\n      \"@id\": \"acw:isMarked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isOptimizedForMobile\": {\n      \"@id\": \"acw:isOptimizedForMobile\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPeak\": {\n      \"@id\": \"acw:isPeak\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrebidDisabled\": {\n      \"@id\": \"acw:isPrebidDisabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"javascriptBody\": {\n      \"@id\": \"acw:javascriptBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"javascriptHead\": {\n      \"@id\": \"acw:javascriptHead\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"key\": {\n      \"@id\": \"acw:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"acw:keywords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"landmark\": {\n      \"@id\": \"acw:landmark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"landmarkReferences\": {\n      \"@id\": \"acw:landmarkReferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"acw:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"acw:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"level\": {\n      \"@id\": \"acw:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"likely\": {\n      \"@id\": \"acw:likely\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"acw:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localDate\": {\n      \"@id\": \"acw:localDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"localDayOfWeek\"\
  : {\n      \"@id\": \"acw:localDayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localEnd\": {\n      \"@id\": \"acw:localEnd\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"localStart\": {\n      \"@id\": \"acw:localStart\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"localTime\": {\n      \"@id\": \"acw:localTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedStartDate\": {\n      \"@id\": \"acw:localizedStartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedStatus\": {\n      \"@id\": \"acw:localizedStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationKey\": {\n      \"@id\": \"acw:locationKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationSettingsInfo\": {\n      \"@id\": \"acw:locationSettingsInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationType\": {\n      \"@id\": \"acw:locationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logo\": {\n      \"@id\": \"acw:logo\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"longDisplayDate\": {\n      \"@id\": \"acw:longDisplayDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longName\": {\n      \"@id\": \"acw:longName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longPhrase\": {\n      \"@id\": \"acw:longPhrase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longitude\": {\n      \"@id\": \"acw:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"low\": {\n      \"@id\": \"acw:low\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lower\": {\n      \"@id\": \"acw:lower\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumSustainedWind\": {\n      \"@id\": \"acw:maximumSustainedWind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumSustainedWindValue\": {\n      \"@id\": \"acw:maximumSustainedWindValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maximumWindGust\": {\n      \"@id\": \"acw:maximumWindGust\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumWindGustValue\": {\n\
  \      \"@id\": \"acw:maximumWindGustValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"medium\": {\n      \"@id\": \"acw:medium\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumPressure\": {\n      \"@id\": \"acw:minimumPressure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minute\": {\n      \"@id\": \"acw:minute\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minuteCastForecast\": {\n      \"@id\": \"acw:minuteCastForecast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minutes\": {\n      \"@id\": \"acw:minutes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"network\": {\n      \"@id\": \"acw:network\",\n      \"@type\": \"xsd:string\"\n    },\n    \"night\": {\n      \"@id\": \"acw:night\",\n      \"@type\": \"xsd:string\"\n    },\n    \"now\": {\n      \"@id\": \"acw:now\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfAlerts\": {\n      \"@id\": \"acw:numberOfAlerts\",\n   \
  \   \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"acw:offset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ortbConfig\": {\n      \"@id\": \"acw:ortbConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallIndex\": {\n      \"@id\": \"acw:overallIndex\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"overallPlumeLabsIndex\": {\n      \"@id\": \"acw:overallPlumeLabsIndex\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"page\": {\n      \"@id\": \"acw:page\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageCategories\": {\n      \"@id\": \"acw:pageCategories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageUrl\": {\n      \"@id\": \"acw:pageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"params\": {\n      \"@id\": \"acw:params\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partner\": {\n      \"@id\": \"acw:partner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"past12Hours\": {\n      \"\
  @id\": \"acw:past12Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"past18Hours\": {\n      \"@id\": \"acw:past18Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"past24Hours\": {\n      \"@id\": \"acw:past24Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"past3Hours\": {\n      \"@id\": \"acw:past3Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"past6Hours\": {\n      \"@id\": \"acw:past6Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"past9Hours\": {\n      \"@id\": \"acw:past9Hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pastHour\": {\n      \"@id\": \"acw:pastHour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peakPosition\": {\n      \"@id\": \"acw:peakPosition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phrase\": {\n      \"@id\": \"acw:phrase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"acw:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pollutants\": {\n      \"@id\":\
  \ \"acw:pollutants\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"acw:position\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"postalCode\": {\n      \"@id\": \"acw:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ppid\": {\n      \"@id\": \"acw:ppid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prebidTimeout\": {\n      \"@id\": \"acw:prebidTimeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"precip\": {\n      \"@id\": \"acw:precip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precipSummary\": {\n      \"@id\": \"acw:precipSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precipitation\": {\n      \"@id\": \"acw:precipitation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"precipitationType\": {\n      \"@id\": \"acw:precipitationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pressure\": {\n      \"@id\": \"acw:pressure\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"probability\": {\n      \"@id\": \"acw:probability\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"productQuality\": {\n      \"@id\": \"acw:productQuality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publisher\": {\n      \"@id\": \"acw:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rain\": {\n      \"@id\": \"acw:rain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realFeel\": {\n      \"@id\": \"acw:realFeel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realFeelPhrase\": {\n      \"@id\": \"acw:realFeelPhrase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realFeelShade\": {\n      \"@id\": \"acw:realFeelShade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realFeelShadePhrase\": {\n      \"@id\": \"acw:realFeelShadePhrase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realFeelShadeValue\": {\n      \"@id\": \"acw:realFeelShadeValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"realFeelValue\"\
  : {\n      \"@id\": \"acw:realFeelValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"referrer\": {\n      \"@id\": \"acw:referrer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referrerUrl\": {\n      \"@id\": \"acw:referrerUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"acw:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sectionCategories\": {\n      \"@id\": \"acw:sectionCategories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segments\": {\n      \"@id\": \"acw:segments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"session\": {\n      \"@id\": \"acw:session\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortDateShortTimeLabel\": {\n      \"@id\": \"acw:shortDateShortTimeLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortDayOfWeek\": {\n      \"@id\": \"acw:shortDayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteName\": {\n\
  \      \"@id\": \"acw:siteName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slot\": {\n      \"@id\": \"acw:slot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snow\": {\n      \"@id\": \"acw:snow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"acw:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceRelationship\": {\n      \"@id\": \"acw:sourceRelationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"speed\": {\n      \"@id\": \"acw:speed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"acw:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startDate\": {\n      \"@id\": \"acw:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startEpoch\": {\n      \"@id\": \"acw:startEpoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stationCode\": {\n      \"@id\": \"acw:stationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"acw:status\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"statusIcon\": {\n      \"@id\": \"acw:statusIcon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusIconString\": {\n      \"@id\": \"acw:statusIconString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusName\": {\n      \"@id\": \"acw:statusName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stormLink\": {\n      \"@id\": \"acw:stormLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stormPositions\": {\n      \"@id\": \"acw:stormPositions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary60\": {\n      \"@id\": \"acw:summary60\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedDataSets\": {\n      \"@id\": \"acw:supportedDataSets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportsEventConfidence\": {\n      \"@id\": \"acw:supportsEventConfidence\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"supportsMinuteCast\": {\n      \"\
  @id\": \"acw:supportsMinuteCast\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"temperature\": {\n      \"@id\": \"acw:temperature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"temperatureValue\": {\n      \"@id\": \"acw:temperatureValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"term\": {\n      \"@id\": \"acw:term\",\n      \"@type\": \"xsd:string\"\n    },\n    \"test\": {\n      \"@id\": \"acw:test\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testVariant\": {\n      \"@id\": \"acw:testVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"throughput\": {\n      \"@id\": \"acw:throughput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thunderstormProbability\": {\n      \"@id\": \"acw:thunderstormProbability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"acw:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"acw:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"\
  @id\": \"acw:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"acw:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitType\": {\n      \"@id\": \"acw:unitType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updatedStormName\": {\n      \"@id\": \"acw:updatedStormName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upr\": {\n      \"@id\": \"acw:upr\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"url\": \"schema:url\",\n    \"user\": {\n      \"@id\": \"acw:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uspString\": {\n      \"@id\": \"acw:uspString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utm\": {\n      \"@id\": \"acw:utm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uv\": {\n      \"@id\": \"acw:uv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"acw:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"version\": {\n      \"@id\": \"acw:version\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"visibility\": {\n      \"@id\": \"acw:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weather\": {\n      \"@id\": \"acw:weather\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wind\": {\n      \"@id\": \"acw:wind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windDegrees\": {\n      \"@id\": \"acw:windDegrees\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"windDirection\": {\n      \"@id\": \"acw:windDirection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windSpeedImperial\": {\n      \"@id\": \"acw:windSpeedImperial\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"windValue\": {\n      \"@id\": \"acw:windValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"year\": {\n      \"@id\": \"acw:year\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/accuweather/refs/heads/main/json-ld/accuweather-context.jsonld
tags:
- Weather
- Forecasts
- Meteorology
- Location Services
- Air Quality
- Storms
- JSON-LD
- Linked Data
- Semantic Web
---
