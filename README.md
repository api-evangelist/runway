# Runway (runway)
Runway is an applied AI research company that builds generative AI tools for creative professionals. Their developer platform provides APIs for video generation, image generation, real-time conversational avatar experiences, media uploads, and audio synthesis powered by advanced generative models including Gen-4, Gen-4 Turbo, Gen-4.5, Gen-4 Aleph, Veo 3.1, Act Two, and GWM-1 (General World Model). The API uses asynchronous task processing with Bearer token authentication.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Video Generation, Image Generation, Artificial Intelligence, Machine Learning, Generative AI, Avatars, Characters, WebRTC, Creative Tools

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-02

## APIs

### Runway Video Generation API
The Runway Video Generation API allows developers to generate videos from text prompts, images, or existing videos using Gen-4, Gen-4 Turbo, Gen-4.5, Gen-4 Aleph, Veo 3.1, and Veo 3.1 Fast models. Supports text-to-video, image-to-video, video-to-video, character performance (Act Two), lip sync (28+ languages), video upscale, frame interpolation, and sound effect generation. Tasks are processed asynchronously with polling via task ID.

**Human URL:** [https://docs.dev.runwayml.com/api/](https://docs.dev.runwayml.com/api/)

#### Tags:

 - Video Generation, Artificial Intelligence, Machine Learning, Text To Video, Image To Video, Generative AI, Gen-4

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api/)
- [OpenAPI](openapi/runway-video-generation-openapi.yml)

### Runway Image Generation API
The Runway Image Generation API provides text-to-image generation using the Gen-4 Image and Gemini 3 Pro Image models. Accepts text prompts up to 1000 characters and supports multiple aspect ratios. Uses the same asynchronous task pattern and Bearer token authentication as the video API. As of April 2026, Gemini 3 Pro Image supports up to 5,500-character prompts and 14 reference images.

**Human URL:** [https://docs.dev.runwayml.com/api/](https://docs.dev.runwayml.com/api/)

#### Tags:

 - Image Generation, Artificial Intelligence, Machine Learning, Text To Image, Generative AI, Gen-4

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api/)
- [OpenAPI](openapi/runway-image-generation-openapi.yml)

### Runway Characters API
The Runway Characters API enables developers to build real-time conversational avatars powered by GWM-1 (Runway's General World Model). Avatars are fully custom conversational video agents created from a single reference image with no fine-tuning. Supports photorealistic or animated styles, human or non-human appearances. Manages avatars, real-time WebRTC sessions (max 5 minutes), and knowledge documents (up to 50,000 tokens per avatar).

**Human URL:** [https://docs.dev.runwayml.com/characters/](https://docs.dev.runwayml.com/characters/)

#### Tags:

 - Avatars, Characters, Conversational AI, Real Time, WebRTC, Video Agents, Generative AI, GWM-1

#### Properties

- [Documentation](https://docs.dev.runwayml.com/characters/)
- [OpenAPI](openapi/runway-characters-openapi.yml)
- [AsyncAPI](asyncapi/runway-characters-asyncapi.yml)

### Runway Python SDK
The Runway Python SDK provides a convenient Python library for interacting with the Runway API. Supports Python 3.8+ with type annotations compatible with MyPy. Includes automatic retries, best-practice error handling, and type safety.

**Human URL:** [https://docs.dev.runwayml.com/api-details/sdks/](https://docs.dev.runwayml.com/api-details/sdks/)

#### Tags:

 - Python, SDK, Libraries, Artificial Intelligence, Video Generation

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api-details/sdks/)
- [GitHub Repository](https://github.com/runwayml/sdk-python)

### Runway Node.js SDK
The Runway Node.js SDK provides a JavaScript and TypeScript library for the Runway API. Supports Node.js 18+ with TypeScript bindings and automatic retries. Install via npm, yarn, or pnpm.

**Human URL:** [https://docs.dev.runwayml.com/api-details/sdks/](https://docs.dev.runwayml.com/api-details/sdks/)

#### Tags:

 - Node.js, JavaScript, TypeScript, SDK, Libraries, Video Generation

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api-details/sdks/)
- [GitHub Repository](https://github.com/runwayml/sdk-node)

## Spectral Rules

- [Runway API Rules](rules/runway-rules.yml)

## Capabilities

### Shared Definitions

- [Runway Video Generation](capabilities/shared/runway-video-generation.yaml)
- [Runway Image Generation](capabilities/shared/runway-image-generation.yaml)
- [Runway Characters](capabilities/shared/runway-characters.yaml)

### Workflow Capabilities

- [Generative Media Production](capabilities/generative-media-production.yaml) — Video generation, image generation, character animation, lip sync, video enhancement, sound effects, and conversational avatars (17 tools)

## JSON Schema

- [Runway Avatar Schema](json-schema/runway-avatar-schema.json)
- [Runway Task Schema](json-schema/runway-task-schema.json)

## JSON Structure

- [Runway Task Structure](json-structure/runway-task-structure.json)

## JSON-LD

- [Runway Context](json-ld/runway-context.jsonld)

## Examples

- [Create Video Example](examples/runway-create-video-example.json)
- [Create Avatar Example](examples/runway-create-avatar-example.json)

## Vocabulary

- [Runway Generative AI Platform Vocabulary](vocabulary/runway-vocabulary.yml)

## Common Properties

- [Portal](https://docs.dev.runwayml.com/)
- [Documentation](https://docs.dev.runwayml.com/api/)
- [Website](https://runwayml.com/)
- [Developer Portal](https://dev.runwayml.com/)
- [Privacy Policy](https://runwayml.com/privacy-policy)
- [Terms Of Service](https://runwayml.com/terms-of-use)
- [Blog](https://runwayml.com/blog)
- [Login](https://app.runwayml.com/)
- [GitHub Organization](https://github.com/runwayml)
- [Changelog](https://docs.dev.runwayml.com/api-details/api_changelog/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
