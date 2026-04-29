---
class_count: 13
classes:
- Application
- License
- Subscription
- Vendor
- Contract
- User
- Department
- name
- description
- renewalDate
- annualSpend
- createdAt
- updatedAt
context_file: json-ld/cleanshelf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cleanshelf/refs/heads/main/json-ld/cleanshelf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cleanshelf from Cleanshelf.
layout: jsonld
name: Cleanshelf Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: zylo
  uri: https://zylo.com/vocab/
properties: []
property_count: 0
provider_name: Cleanshelf
provider_slug: cleanshelf
slug: cleanshelf-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/cleanshelf/\",\n    \"schema\": \"https://schema.org/\",\n    \"zylo\": \"https://zylo.com/vocab/\",\n    \"Application\": \"schema:SoftwareApplication\",\n    \"License\": \"zylo:SoftwareLicense\",\n    \"Subscription\": \"zylo:SaaSSubscription\",\n    \"Vendor\": \"schema:Organization\",\n    \"Contract\": \"zylo:Contract\",\n    \"User\": \"schema:Person\",\n    \"Department\": \"schema:OrganizationRole\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"renewalDate\": \"zylo:renewalDate\",\n    \"annualSpend\": \"zylo:annualSpend\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cleanshelf/refs/heads/main/json-ld/cleanshelf-context.jsonld
tags:
- Acquired
- License Management
- SaaS Management
- Shadow IT
- SMP
- Software Asset Management
- Spend Optimization
- JSON-LD
- Linked Data
- Semantic Web
---
