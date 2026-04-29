---
class_count: 1
classes:
- InputData
context_file: json-ld/adyen-terminal-input-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-input-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Input Data from Adyen.
layout: jsonld
name: Adyen Terminal Input Data Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Device
  type: string
- container: ''
  name: InfoQualify
  type: string
- container: ''
  name: InputCommand
  type: string
- container: ''
  name: NotifyCardInputFlag
  type: boolean
- container: ''
  name: MaxInputTime
  type: integer
- container: ''
  name: ImmediateResponseFlag
  type: boolean
- container: ''
  name: MinLength
  type: integer
- container: ''
  name: MaxLength
  type: integer
- container: ''
  name: MaxDecimalLength
  type: integer
- container: ''
  name: WaitUserValidationFlag
  type: boolean
- container: ''
  name: DefaultInputString
  type: string
- container: ''
  name: DefaultLayoutString
  type: string
- container: ''
  name: StringMask
  type: string
- container: ''
  name: FromRightToLeftFlag
  type: boolean
- container: ''
  name: MaskCharactersFlag
  type: boolean
- container: ''
  name: BeepKeyFlag
  type: boolean
- container: ''
  name: GlobalCorrectionFlag
  type: boolean
- container: ''
  name: DisableCancelFlag
  type: boolean
- container: ''
  name: DisableCorrectFlag
  type: boolean
- container: ''
  name: DisableValidFlag
  type: boolean
- container: ''
  name: MenuBackFlag
  type: boolean
property_count: 21
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-input-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InputData\": \"adyen:InputData\",\n    \"Device\": {\n      \"@id\": \"adyen:Device\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InfoQualify\": {\n      \"@id\": \"adyen:InfoQualify\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputCommand\": {\n      \"@id\": \"adyen:InputCommand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotifyCardInputFlag\": {\n      \"@id\": \"adyen:NotifyCardInputFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"MaxInputTime\": {\n      \"@id\": \"adyen:MaxInputTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ImmediateResponseFlag\": {\n      \"@id\": \"adyen:ImmediateResponseFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"MinLength\": {\n      \"@id\": \"adyen:MinLength\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaxLength\": {\n      \"@id\": \"adyen:MaxLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaxDecimalLength\": {\n      \"@id\": \"adyen:MaxDecimalLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"WaitUserValidationFlag\": {\n      \"@id\": \"adyen:WaitUserValidationFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DefaultInputString\": {\n      \"@id\": \"adyen:DefaultInputString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultLayoutString\": {\n      \"@id\": \"adyen:DefaultLayoutString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StringMask\": {\n      \"@id\": \"adyen:StringMask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FromRightToLeftFlag\": {\n      \"@id\": \"adyen:FromRightToLeftFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"MaskCharactersFlag\": {\n      \"@id\": \"adyen:MaskCharactersFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"BeepKeyFlag\": {\n      \"\
  @id\": \"adyen:BeepKeyFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"GlobalCorrectionFlag\": {\n      \"@id\": \"adyen:GlobalCorrectionFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DisableCancelFlag\": {\n      \"@id\": \"adyen:DisableCancelFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DisableCorrectFlag\": {\n      \"@id\": \"adyen:DisableCorrectFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DisableValidFlag\": {\n      \"@id\": \"adyen:DisableValidFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"MenuBackFlag\": {\n      \"@id\": \"adyen:MenuBackFlag\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-input-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
