---
class_count: 44
classes:
- ConnectedAppliance
- Washer
- Dryer
- Oven
- Refrigerator
- AirConditioner
- Dishwasher
- applianceId
- modelNumber
- serialNumber
- machineState
- cycleType
- timeRemaining
- spinSpeed
- waterTemperature
- soilLevel
- washAndGoTankFill
- wrinkleShield
- iceMode
- quickCool
- sixthSense
- dashReplenishment
- name
- description
- brand
- model
- manufacturer
- url
- category
- Product
- HouseholdAppliance
- IndividualProduct
- WashingMachine
- Microwave
- targetTemperature
- temperature
- energyConsumption
- identifier
- dateCreated
- IoTDevice
- SmartHome
- MatterSupport
- VoiceControl
- RemoteControl
context_file: json-ld/whirlpool-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/json-ld/whirlpool-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Whirlpool from Whirlpool Corporation.
layout: jsonld
name: Whirlpool Context
namespaces:
- prefix: whirlpool
  uri: https://www.whirlpoolcorp.com/vocab#
- prefix: matter
  uri: https://csa-iot.org/developer-resource/matter/vocab#
properties: []
property_count: 0
provider_name: Whirlpool Corporation
provider_slug: whirlpool
slug: whirlpool-context
source_filename: whirlpool-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"whirlpool\": \"https://www.whirlpoolcorp.com/vocab#\",\n    \"matter\": \"https://csa-iot.org/developer-resource/matter/vocab#\",\n\n    \"ConnectedAppliance\": \"whirlpool:ConnectedAppliance\",\n    \"Washer\": \"whirlpool:Washer\",\n    \"Dryer\": \"whirlpool:Dryer\",\n    \"Oven\": \"whirlpool:Oven\",\n    \"Refrigerator\": \"whirlpool:Refrigerator\",\n    \"AirConditioner\": \"whirlpool:AirConditioner\",\n    \"Dishwasher\": \"whirlpool:Dishwasher\",\n\n    \"applianceId\": \"whirlpool:applianceId\",\n    \"modelNumber\": \"whirlpool:modelNumber\",\n    \"serialNumber\": \"whirlpool:serialNumber\",\n    \"machineState\": \"whirlpool:machineState\",\n    \"cycleType\": \"whirlpool:cycleType\",\n    \"timeRemaining\": \"whirlpool:timeRemaining\",\n    \"spinSpeed\": \"whirlpool:spinSpeed\",\n    \"waterTemperature\": \"whirlpool:waterTemperature\",\n    \"soilLevel\": \"whirlpool:soilLevel\",\n    \"washAndGoTankFill\"\
  : \"whirlpool:washAndGoTankFill\",\n    \"wrinkleShield\": \"whirlpool:wrinkleShield\",\n    \"iceMode\": \"whirlpool:iceMode\",\n    \"quickCool\": \"whirlpool:quickCool\",\n    \"sixthSense\": \"whirlpool:sixthSense\",\n    \"dashReplenishment\": \"whirlpool:dashReplenishment\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"brand\": \"schema:brand\",\n    \"model\": \"schema:model\",\n    \"serialNumber\": \"schema:serialNumber\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"url\": \"schema:url\",\n    \"category\": \"schema:category\",\n\n    \"Product\": \"schema:Product\",\n    \"HouseholdAppliance\": \"schema:HouseholdAppliance\",\n    \"IndividualProduct\": \"schema:IndividualProduct\",\n\n    \"WashingMachine\": \"schema:WashingMachine\",\n    \"Microwave\": \"schema:Microwave\",\n\n    \"targetTemperature\": \"schema:targetTemperature\",\n    \"temperature\": \"schema:temperature\",\n    \"energyConsumption\": \"schema:energyConsumption\"\
  ,\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n\n    \"IoTDevice\": \"whirlpool:IoTDevice\",\n    \"SmartHome\": \"whirlpool:SmartHome\",\n    \"MatterSupport\": \"matter:MatterSupport\",\n    \"VoiceControl\": \"whirlpool:VoiceControl\",\n    \"RemoteControl\": \"whirlpool:RemoteControl\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/json-ld/whirlpool-context.jsonld
tags:
- Appliances
- Smart Home
- IoT
- Connected Devices
- Fortune 500
- Consumer Electronics
- JSON-LD
- Linked Data
- Semantic Web
---
