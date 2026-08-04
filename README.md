# Runway (runway)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Runway is an applied AI research company that builds generative AI tools for creative professionals. Their developer platform provides APIs for video generation, image generation, real-time conversational avatar experiences, media uploads, and audio synthesis powered by advanced generative models including Gen-4, Gen-4 Turbo, Gen-4.5, Gen-4 Aleph, Veo 3.1, Act Two, and GWM-1 (General World Model). The API uses asynchronous task processing with Bearer token authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Video Generation
- Image Generation
- Artificial Intelligence
- Machine Learning
- Generative AI
- Avatars
- Characters
- WebRTC
- Creative Tools

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Runway Video Generation API

The Runway Video Generation API allows developers to generate videos from text prompts, images, or existing videos using Gen-4, Gen-4 Turbo, Gen-4.5, Gen-4 Aleph, Veo 3.1, and Veo 3.1 Fast models. Supports text-to-video, image-to-video, video-to-video, character performance (Act Two), lip sync (28+ languages), video upscale, frame interpolation, and sound effect generation. Tasks are processed asynchronously with polling via task ID. Authentication via Bearer token plus X-Runway-Version header set to 2024-11-06.

- **Human URL:** [https://docs.dev.runwayml.com/api/](https://docs.dev.runwayml.com/api/)
- **Base URL:** `https://api.dev.runwayml.com/v1`

#### Tags

- Video Generation
- Artificial Intelligence
- Machine Learning
- Text To Video
- Image To Video
- Generative AI
- Gen-4

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api/)
- [OpenAPI](openapi/runway-video-generation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runway-video-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-video-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/runway-rules.yml)

### Runway Image Generation API

The Runway Image Generation API provides text-to-image generation using the Gen-4 Image and Gemini 3 Pro Image models. Accepts text prompts up to 1000 characters and supports multiple aspect ratios. Also includes task status polling. Uses the same asynchronous task pattern and Bearer token authentication as the video API. As of April 2026, Gemini 3 Pro Image supports up to 5,500-character prompts and 14 reference images.

- **Human URL:** [https://docs.dev.runwayml.com/api/](https://docs.dev.runwayml.com/api/)
- **Base URL:** `https://api.dev.runwayml.com/v1`

#### Tags

- Image Generation
- Artificial Intelligence
- Machine Learning
- Text To Image
- Generative AI
- Gen-4

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api/)
- [OpenAPI](openapi/runway-image-generation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runway-image-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-image-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/runway-rules.yml)

### Runway Characters API

The Runway Characters API enables developers to build real-time conversational avatars powered by GWM-1 (Runway's General World Model). Avatars are fully custom conversational video agents created from a single reference image with no fine-tuning. Supports photorealistic or animated styles, human or non-human appearances. Manages avatars, real-time WebRTC sessions (max 5 minutes), and knowledge documents (up to 50,000 tokens per avatar). Authentication via Bearer token.

- **Human URL:** [https://docs.dev.runwayml.com/characters/](https://docs.dev.runwayml.com/characters/)
- **Base URL:** `https://api.dev.runwayml.com/v1`

#### Tags

- Avatars
- Characters
- Conversational AI
- Real Time
- WebRTC
- Video Agents
- Generative AI
- GWM-1

#### Properties

- [Documentation](https://docs.dev.runwayml.com/characters/)
- [OpenAPI](openapi/runway-characters-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runway-characters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-characters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/runway-characters-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Spectral  Rules](rules/runway-rules.yml)

### Runway Python SDK

The Runway Python SDK provides a convenient Python library for interacting with the Runway API. Supports Python 3.8+ with type annotations compatible with MyPy. Includes automatic retries, best-practice error handling, and type safety to simplify integration of Runway's video and image generation capabilities into Python applications.

- **Human URL:** [https://docs.dev.runwayml.com/api-details/sdks/](https://docs.dev.runwayml.com/api-details/sdks/)

#### Tags

- Python
- SDK
- Libraries
- Artificial Intelligence
- Video Generation

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api-details/sdks/)
- [GitHub Repository](https://github.com/runwayml/sdk-python)
- [Postman Collection](collections/runway-characters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-characters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/runway-image-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-image-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/runway-video-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-video-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runway Node.js SDK

The Runway Node.js SDK provides a JavaScript and TypeScript library for integrating with the Runway API. Supports Node.js 18+ with TypeScript bindings, automatic retries, and best-practice error handling. Install via npm, yarn, or pnpm.

- **Human URL:** [https://docs.dev.runwayml.com/api-details/sdks/](https://docs.dev.runwayml.com/api-details/sdks/)

#### Tags

- Node.js
- JavaScript
- TypeScript
- SDK
- Libraries
- Video Generation

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api-details/sdks/)
- [GitHub Repository](https://github.com/runwayml/sdk-node)
- [Postman Collection](collections/runway-characters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-characters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/runway-image-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-image-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/runway-video-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runway-video-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/runwayml)
- [Portal](https://docs.dev.runwayml.com/)
- [Documentation](https://docs.dev.runwayml.com/api/)
- [Website](https://runwayml.com/)
- [Developer  Portal](https://dev.runwayml.com/)
- [Privacy Policy](https://runwayml.com/privacy-policy)
- [Terms of Service](https://runwayml.com/terms-of-use)
- [Blog](https://runwayml.com/blog)
- [Login](https://app.runwayml.com/)
- [GitHub Organization](https://github.com/runwayml)
- [Changelog](https://docs.dev.runwayml.com/api-details/api_changelog/)
- [Vocabulary](vocabulary/runway-vocabulary.yml)
- [JSON-LD](json-ld/runway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [M C P Server](https://github.com/runwayml/runway-api-mcp-server)
- [Agent Skill](https://github.com/runwayml/runway-characters-meeting-skill)
- [L L Ms Txt](https://docs.dev.runwayml.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
