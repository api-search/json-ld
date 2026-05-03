---
class_count: 6
classes:
- CybersecurityAdvisory
- MalwareSample
- ThreatActor
- description
- name
- title
context_file: json-ld/us-cyber-command-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-ld/us-cyber-command-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Cyber Command from US Cyber Command.
layout: jsonld
name: Us Cyber Command Context
namespaces:
- prefix: uscybercom
  uri: https://www.cybercom.mil/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: actor_id
  type: string
- container: ''
  name: advisory_id
  type: string
- container: ''
  name: advisory_url
  type: reference
- container: set
  name: alternative_names
  type: string
- container: ''
  name: cisa_url
  type: reference
- container: set
  name: cvEs
  type: string
- container: ''
  name: date_shared
  type: date
- container: ''
  name: file_name
  type: string
- container: ''
  name: file_type
  type: string
- container: ''
  name: first_observed
  type: date
- container: set
  name: iocs
  type: reference
- container: set
  name: issuing_agencies
  type: string
- container: set
  name: malware_families
  type: string
- container: ''
  name: malware_family
  type: string
- container: ''
  name: malware_type
  type: string
- container: ''
  name: md5
  type: string
- container: ''
  name: mitre_group_id
  type: string
- container: ''
  name: nation_state
  type: string
- container: ''
  name: nation_state_sponsor
  type: string
- container: ''
  name: primary_motivation
  type: string
- container: ''
  name: publication_date
  type: date
- container: ''
  name: sha1
  type: string
- container: ''
  name: sha256
  type: string
- container: ''
  name: sponsoring_agency
  type: string
- container: set
  name: targeted_sectors
  type: string
- container: ''
  name: threat_actor
  type: string
- container: ''
  name: tlp_level
  type: string
- container: set
  name: ttps
  type: string
- container: ''
  name: virustotal_url
  type: reference
property_count: 29
provider_name: US Cyber Command
provider_slug: us-cyber-command
slug: us-cyber-command-context
source_filename: us-cyber-command-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uscybercom\": \"https://www.cybercom.mil/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CybersecurityAdvisory\": \"uscybercom:CybersecurityAdvisory\",\n    \"MalwareSample\": \"uscybercom:MalwareSample\",\n    \"ThreatActor\": \"uscybercom:ThreatActor\",\n    \"actor_id\": {\n      \"@id\": \"uscybercom:actor_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advisory_id\": {\n      \"@id\": \"uscybercom:advisory_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advisory_url\": {\n      \"@id\": \"uscybercom:advisory_url\",\n      \"@type\": \"@id\"\n    },\n    \"alternative_names\": {\n      \"@id\": \"uscybercom:alternative_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cisa_url\": {\n      \"@id\": \"uscybercom:cisa_url\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"cvEs\": {\n      \"@id\": \"uscybercom:cvEs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date_shared\": {\n      \"@id\": \"uscybercom:date_shared\",\n      \"@type\": \"xsd:date\"\n    },\n    \"description\": \"schema:description\",\n    \"file_name\": {\n      \"@id\": \"uscybercom:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file_type\": {\n      \"@id\": \"uscybercom:file_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"first_observed\": {\n      \"@id\": \"uscybercom:first_observed\",\n      \"@type\": \"xsd:date\"\n    },\n    \"iocs\": {\n      \"@id\": \"uscybercom:iocs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"issuing_agencies\": {\n      \"@id\": \"uscybercom:issuing_agencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"malware_families\": {\n      \"@id\": \"uscybercom:malware_families\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"malware_family\": {\n      \"@id\": \"uscybercom:malware_family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"malware_type\": {\n      \"@id\": \"uscybercom:malware_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"md5\": {\n      \"@id\": \"uscybercom:md5\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mitre_group_id\": {\n      \"@id\": \"uscybercom:mitre_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nation_state\": {\n      \"@id\": \"uscybercom:nation_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nation_state_sponsor\": {\n      \"@id\": \"uscybercom:nation_state_sponsor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primary_motivation\": {\n      \"@id\": \"uscybercom:primary_motivation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publication_date\": {\n      \"@id\": \"uscybercom:publication_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"sha1\": {\n      \"@id\"\
  : \"uscybercom:sha1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sha256\": {\n      \"@id\": \"uscybercom:sha256\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sponsoring_agency\": {\n      \"@id\": \"uscybercom:sponsoring_agency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targeted_sectors\": {\n      \"@id\": \"uscybercom:targeted_sectors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threat_actor\": {\n      \"@id\": \"uscybercom:threat_actor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": \"schema:name\",\n    \"tlp_level\": {\n      \"@id\": \"uscybercom:tlp_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ttps\": {\n      \"@id\": \"uscybercom:ttps\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virustotal_url\": {\n      \"@id\": \"uscybercom:virustotal_url\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-ld/us-cyber-command-context.jsonld
tags:
- Cybersecurity
- Federal Government
- Military
- Threat Intelligence
- Defense
- JSON-LD
- Linked Data
- Semantic Web
---
