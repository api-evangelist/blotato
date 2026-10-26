# Blotato (blotato)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
