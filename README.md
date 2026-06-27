# Blotato (blotato)

Blotato is an AI content-creation and social-media publishing platform. Its REST API lets automation and AI-agent builders upload media, publish posts to many platforms (TikTok, Instagram, YouTube, X/Twitter, LinkedIn, Facebook, Threads, Bluesky, Pinterest), generate AI videos and visuals from templates, and track publishing status, with an authenticated MCP server for AI agents.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/blotato/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/blotato/refs/heads/main/apis.yml)

## Tags

- Social Media
- Publishing
- AI Content
- Automation
- Content Creation

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Blotato Media Upload API

Uploads media to Blotato by passing a publicly accessible URL or base64-encoded image data and returns a hosted media URL to use when publishing posts. Supports files up to 200MB, with a presigned-upload flow for local files.

- **Human URL:** [https://help.blotato.com/api/api-reference/upload-media-v2-media](https://help.blotato.com/api/api-reference/upload-media-v2-media)
- **Base URL:** `https://backend.blotato.com/v2`

#### Tags

- Media
- Upload
- Images
- Video

#### Properties

- [Documentation](https://help.blotato.com/api/api-reference/upload-media-v2-media)
- [API Reference](https://help.blotato.com/api/api-reference/upload-media-v2-media)
- [OpenAPI](openapi/blotato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blotato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blotato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blotato Posts Publishing API

Publishes or schedules posts to Twitter/X, Instagram, LinkedIn, Facebook, TikTok, Pinterest, Threads, Bluesky, and YouTube with text, media, and platform-specific options, returning a postSubmissionId whose status is polled via a follow-up request.

- **Human URL:** [https://help.blotato.com/api/api-reference/publish-post](https://help.blotato.com/api/api-reference/publish-post)
- **Base URL:** `https://backend.blotato.com/v2`

#### Tags

- Posts
- Publishing
- Social Media
- Scheduling

#### Properties

- [Documentation](https://help.blotato.com/api/api-reference/publish-post)
- [API Reference](https://help.blotato.com/api/api-reference/publish-post)
- [OpenAPI](openapi/blotato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blotato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blotato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blotato AI Content API

Generates AI videos and visuals from templates - list available templates, create a video or image creation from a template plus inputs, and poll the creation until it is done to retrieve the resulting media or image URLs.

- **Human URL:** [https://help.blotato.com/api/start](https://help.blotato.com/api/start)
- **Base URL:** `https://backend.blotato.com/v2`

#### Tags

- AI Content
- Video
- Visuals
- Templates

#### Properties

- [Documentation](https://help.blotato.com/api/start)
- [OpenAPI](openapi/blotato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blotato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blotato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blotato Accounts API

Retrieves the current user and their connected social accounts - returning the accountId values (and LinkedIn/Facebook subaccounts and Pinterest boards) required when publishing posts.

- **Human URL:** [https://help.blotato.com/api/start](https://help.blotato.com/api/start)
- **Base URL:** `https://backend.blotato.com/v2`

#### Tags

- Accounts
- Users
- Connections

#### Properties

- [Documentation](https://help.blotato.com/api/start)
- [OpenAPI](openapi/blotato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blotato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blotato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Blotato-Inc)
- [LinkedIn](https://www.linkedin.com/company/blotato)
- [Website](https://www.blotato.com/)
- [Documentation](https://help.blotato.com/api/start)
- [Plans](plans/blotato-plans-pricing.yml)
- [Rate Limits](rate-limits/blotato-rate-limits.yml)
- [Fin Ops](finops/blotato-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
