---
api_specs:
- filename: amazon-polly-openapi.yml
  format: yaml
  label: Amazon Polly API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-polly/refs/heads/main/openapi/amazon-polly-openapi.yml
class_count: 16
classes:
- GetSpeechSynthesisTaskOutput
- SynthesisTask
- StartSpeechSynthesisTaskInput
- SynthesizeSpeechOutput
- Voice
- LexiconAttributes
- LexiconDescription
- StartSpeechSynthesisTaskOutput
- SynthesizeSpeechInput
- ListLexiconsOutput
- GetLexiconOutput
- Lexicon
- Amazon Polly Speech Synthesis Definition
- PutLexiconInput
- ListSpeechSynthesisTasksOutput
- DescribeVoicesOutput
context_file: json-ld/amazon-polly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-polly/refs/heads/main/json-ld/amazon-polly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Polly from Amazon Polly.
layout: jsonld
name: Amazon Polly Context
namespaces:
- prefix: polly
  uri: https://polly.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Engine
  type: string
- container: ''
  name: LanguageCode
  type: string
- container: ''
  name: LexiconNames
  type: string
- container: ''
  name: OutputFormat
  type: string
- container: ''
  name: OutputS3BucketName
  type: string
- container: ''
  name: OutputS3KeyPrefix
  type: string
- container: ''
  name: SampleRate
  type: string
- container: ''
  name: SnsTopicArn
  type: string
- container: ''
  name: SpeechMarkTypes
  type: string
- container: ''
  name: Text
  type: string
- container: ''
  name: TextType
  type: string
- container: ''
  name: VoiceId
  type: string
- container: ''
  name: AudioStream
  type: string
- container: ''
  name: Gender
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: LanguageName
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: AdditionalLanguageCodes
  type: string
- container: ''
  name: SupportedEngines
  type: string
- container: ''
  name: Alphabet
  type: string
- container: ''
  name: LastModified
  type: string
- container: ''
  name: LexiconArn
  type: string
- container: ''
  name: LexemesCount
  type: string
- container: ''
  name: Size
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: TaskId
  type: string
- container: ''
  name: TaskStatus
  type: string
- container: ''
  name: TaskStatusReason
  type: string
- container: ''
  name: OutputUri
  type: string
- container: ''
  name: CreationTime
  type: string
- container: ''
  name: RequestCharacters
  type: string
- container: ''
  name: Lexicons
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Content
  type: string
- container: ''
  name: SynthesisTasks
  type: string
- container: ''
  name: Voices
  type: string
property_count: 36
provider_name: Amazon Polly
provider_slug: amazon-polly
slug: amazon-polly-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"polly\": \"https://polly.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetSpeechSynthesisTaskOutput\": \"polly:GetSpeechSynthesisTaskOutput\",\n    \"SynthesisTask\": \"polly:SynthesisTask\",\n    \"StartSpeechSynthesisTaskInput\": \"polly:StartSpeechSynthesisTaskInput\",\n    \"Engine\": {\n      \"@id\": \"polly:Engine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LanguageCode\": {\n      \"@id\": \"polly:LanguageCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LexiconNames\": {\n      \"@id\": \"polly:LexiconNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputFormat\": {\n      \"@id\": \"polly:OutputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputS3BucketName\": {\n      \"@id\": \"polly:OutputS3BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"OutputS3KeyPrefix\": {\n      \"@id\": \"polly:OutputS3KeyPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SampleRate\": {\n      \"@id\": \"polly:SampleRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnsTopicArn\": {\n      \"@id\": \"polly:SnsTopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpeechMarkTypes\": {\n      \"@id\": \"polly:SpeechMarkTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Text\": {\n      \"@id\": \"polly:Text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TextType\": {\n      \"@id\": \"polly:TextType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VoiceId\": {\n      \"@id\": \"polly:VoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SynthesizeSpeechOutput\": \"polly:SynthesizeSpeechOutput\",\n    \"AudioStream\": {\n      \"@id\": \"polly:AudioStream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Voice\": \"polly:Voice\",\n    \"Gender\": {\n      \"@id\": \"polly:Gender\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Id\": {\n      \"@id\": \"polly:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LanguageName\": {\n      \"@id\": \"polly:LanguageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"polly:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdditionalLanguageCodes\": {\n      \"@id\": \"polly:AdditionalLanguageCodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedEngines\": {\n      \"@id\": \"polly:SupportedEngines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LexiconAttributes\": \"polly:LexiconAttributes\",\n    \"Alphabet\": {\n      \"@id\": \"polly:Alphabet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModified\": {\n      \"@id\": \"polly:LastModified\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LexiconArn\": {\n      \"@id\": \"polly:LexiconArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LexemesCount\": {\n      \"@id\": \"polly:LexemesCount\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"Size\": {\n      \"@id\": \"polly:Size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LexiconDescription\": \"polly:LexiconDescription\",\n    \"Attributes\": {\n      \"@id\": \"polly:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartSpeechSynthesisTaskOutput\": \"polly:StartSpeechSynthesisTaskOutput\",\n    \"TaskId\": {\n      \"@id\": \"polly:TaskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskStatus\": {\n      \"@id\": \"polly:TaskStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskStatusReason\": {\n      \"@id\": \"polly:TaskStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputUri\": {\n      \"@id\": \"polly:OutputUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"polly:CreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestCharacters\": {\n      \"@id\": \"polly:RequestCharacters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SynthesizeSpeechInput\": \"\
  polly:SynthesizeSpeechInput\",\n    \"ListLexiconsOutput\": \"polly:ListLexiconsOutput\",\n    \"Lexicons\": {\n      \"@id\": \"polly:Lexicons\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"polly:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetLexiconOutput\": \"polly:GetLexiconOutput\",\n    \"Lexicon\": \"polly:Lexicon\",\n    \"Amazon Polly Speech Synthesis Definition\": \"polly:Amazon Polly Speech Synthesis Definition\",\n    \"PutLexiconInput\": \"polly:PutLexiconInput\",\n    \"Content\": {\n      \"@id\": \"polly:Content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListSpeechSynthesisTasksOutput\": \"polly:ListSpeechSynthesisTasksOutput\",\n    \"SynthesisTasks\": {\n      \"@id\": \"polly:SynthesisTasks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeVoicesOutput\": \"polly:DescribeVoicesOutput\",\n    \"Voices\": {\n      \"@id\": \"polly:Voices\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-polly/refs/heads/main/json-ld/amazon-polly-context.jsonld
tags:
- AI
- AWS
- Machine Learning
- Speech Synthesis
- Text-To-Speech
- TTS
- Voice
- SSML
- Neural Engine
- Generative AI
- JSON-LD
- Linked Data
- Semantic Web
---
