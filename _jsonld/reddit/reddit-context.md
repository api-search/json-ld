---
api_specs:
- filename: reddit-data-api-openapi.yml
  format: yaml
  label: Reddit Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/openapi/reddit-data-api-openapi.yml
- filename: reddit-ads-api-openapi.yml
  format: yaml
  label: Reddit Ads API
  slug: ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/openapi/reddit-ads-api-openapi.yml
- filename: reddit-embeds-openapi.yml
  format: yaml
  label: Reddit Embeds (oEmbed)
  slug: embeds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/openapi/reddit-embeds-openapi.yml
class_count: 0
classes: []
context_file: json-ld/reddit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/json-ld/reddit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reddit from Reddit.
layout: jsonld
name: Reddit Context
namespaces:
- prefix: reddit
  uri: https://www.reddit.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
properties:
- container: ''
  name: Subreddit
  type: ''
- container: ''
  name: Post
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: AdCampaign
  type: ''
- container: ''
  name: AdGroup
  type: ''
- container: ''
  name: Ad
  type: ''
property_count: 7
provider_name: Reddit
provider_slug: reddit
slug: reddit-context
source_filename: reddit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"reddit\": \"https://www.reddit.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n\n    \"Subreddit\": {\n      \"@id\": \"reddit:Subreddit\",\n      \"@context\": {\n        \"display_name\": \"schema:name\",\n        \"title\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"public_description\": \"schema:abstract\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"subscribers\": \"schema:memberCount\",\n        \"created_utc\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"subreddit_type\": \"reddit:subredditType\",\n        \"over18\": \"reddit:isNSFW\",\n        \"lang\": \"schema:inLanguage\",\n        \"icon_img\"\
  : {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"banner_img\": {\n          \"@id\": \"reddit:bannerImage\",\n          \"@type\": \"@id\"\n        },\n        \"rules\": {\n          \"@id\": \"reddit:rules\",\n          \"@container\": \"@set\"\n        },\n        \"moderators\": {\n          \"@id\": \"reddit:moderators\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Post\": {\n      \"@id\": \"reddit:Post\",\n      \"@context\": {\n        \"title\": \"schema:headline\",\n        \"selftext\": \"schema:articleBody\",\n        \"author\": \"schema:author\",\n        \"subreddit\": \"sioc:has_container\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"permalink\": {\n          \"@id\": \"reddit:permalink\",\n          \"@type\": \"@id\"\n        },\n        \"score\": \"reddit:score\",\n        \"upvote_ratio\": \"reddit:upvoteRatio\",\n        \"num_comments\"\
  : \"schema:commentCount\",\n        \"created_utc\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"edited\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"is_self\": \"reddit:isSelfPost\",\n        \"is_video\": \"reddit:isVideo\",\n        \"over_18\": \"reddit:isNSFW\",\n        \"spoiler\": \"reddit:isSpoiler\",\n        \"stickied\": \"reddit:isStickied\",\n        \"locked\": \"reddit:isLocked\",\n        \"archived\": \"reddit:isArchived\",\n        \"link_flair_text\": \"reddit:flairText\",\n        \"domain\": \"reddit:linkDomain\",\n        \"thumbnail\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"reddit:Comment\",\n      \"@context\": {\n        \"body\": \"schema:text\",\n        \"author\": \"schema:author\",\n        \"link_id\": \"sioc:reply_of\",\n     \
  \   \"parent_id\": \"reddit:parentId\",\n        \"subreddit\": \"sioc:has_container\",\n        \"score\": \"reddit:score\",\n        \"created_utc\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"edited\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"permalink\": {\n          \"@id\": \"reddit:permalink\",\n          \"@type\": \"@id\"\n        },\n        \"depth\": \"reddit:depth\",\n        \"is_submitter\": \"reddit:isSubmitter\",\n        \"stickied\": \"reddit:isStickied\",\n        \"locked\": \"reddit:isLocked\",\n        \"distinguished\": \"reddit:distinguished\",\n        \"replies\": {\n          \"@id\": \"sioc:has_reply\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"reddit:Account\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"link_karma\": \"reddit:linkKarma\",\n   \
  \     \"comment_karma\": \"reddit:commentKarma\",\n        \"created_utc\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"icon_img\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"has_verified_email\": \"reddit:hasVerifiedEmail\",\n        \"is_gold\": \"reddit:isPremium\",\n        \"is_mod\": \"reddit:isModerator\",\n        \"over_18\": \"reddit:isOver18\"\n      }\n    },\n\n    \"AdCampaign\": {\n      \"@id\": \"reddit:AdCampaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"reddit:campaignStatus\",\n        \"objective\": \"reddit:campaignObjective\",\n        \"daily_budget_micro\": \"reddit:dailyBudgetMicro\",\n        \"lifetime_budget_micro\": \"reddit:lifetimeBudgetMicro\",\n        \"start_time\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"end_time\": {\n          \"@id\"\
  : \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AdGroup\": {\n      \"@id\": \"reddit:AdGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"campaign_id\": \"reddit:campaignId\",\n        \"status\": \"reddit:adGroupStatus\",\n        \"bid_strategy\": \"reddit:bidStrategy\",\n        \"targeting\": \"reddit:targeting\"\n      }\n    },\n\n    \"Ad\": {\n      \"@id\": \"reddit:Ad\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"reddit:adStatus\",\n        \"click_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"review_status\": \"reddit:reviewStatus\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/json-ld/reddit-context.jsonld
tags:
- Advertising
- Communities
- Content
- Social Media
- Social News
- JSON-LD
- Linked Data
- Semantic Web
---
