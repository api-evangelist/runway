# Runway (runway)
Runway is an applied AI research company that builds generative AI tools for creative professionals. Their developer platform provides APIs for video generation, image generation, and real-time conversational avatar experiences powered by advanced generative models including Gen-4 and Gen-4.5.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Video, Generation, Artificial Intelligence, Machine Learning, Generative AI, Images, Avatars, Characters, WebRTC

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Runway Video Generation API
The Runway Video Generation API allows developers to generate videos from text prompts, images, or existing videos using Runway's Gen-4 and Gen-4.5 models. The API supports text-to-video, image-to-video, and video-to-video generation workflows, producing 5-8 second video clips. Tasks are processed asynchronously, with developers submitting generation requests and polling for results using unique task identifiers. Authentication is handled via Bearer token in the HTTP Authorization header.

**Human URL:** [https://docs.dev.runwayml.com/guides/using-the-api/](https://docs.dev.runwayml.com/guides/using-the-api/)


#### Tags:

 - Video, Generation, Artificial Intelligence, Machine Learning, Text To Video, Image To Video, Generative AI

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api/)
- [OpenAPI](openapi/runway-video-generation-openapi.yml)

### Runway Image Generation API
The Runway Image Generation API provides a text-to-image endpoint that enables developers to generate high-quality images from text prompts using Runway's Gen-4 model. The API accepts text descriptions and produces images as output, allowing integration of AI-powered image generation into applications, products, and platforms. Like the video API, it uses asynchronous task processing and Bearer token authentication.

**Human URL:** [https://runwayml.com/news/introducing-runway-api-for-gen-4-images](https://runwayml.com/news/introducing-runway-api-for-gen-4-images)


#### Tags:

 - Images, Generation, Artificial Intelligence, Machine Learning, Text To Image, Generative AI

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api/)
- [OpenAPI](openapi/runway-image-generation-openapi.yml)

### Runway Characters API
The Runway Characters API enables developers to build real-time conversational avatars powered by GWM-1, Runway's General World Model. Characters are fully custom conversational video agents that can be created from a single image with no fine-tuning required, supporting photorealistic or animated styles, human or non-human appearances. The API uses WebRTC sessions for live conversations with up to 5-minute duration, and includes a Documents API for uploading domain-specific knowledge that avatars can reference during interactions.

**Human URL:** [https://docs.dev.runwayml.com/characters/](https://docs.dev.runwayml.com/characters/)


#### Tags:

 - Avatars, Characters, Conversational AI, Real Time, WebRTC, Video Agents, Generative AI

#### Properties

- [Documentation](https://docs.dev.runwayml.com/characters/)
- [OpenAPI](openapi/runway-characters-openapi.yml)
- [AsyncAPI](asyncapi/runway-characters-asyncapi.yml)

### Runway Python SDK
The Runway Python SDK provides a convenient Python library for interacting with the Runway API. It includes type annotations compatible with MyPy and supports Python 3.8 and above. The SDK can be installed via pip and offers type safety, automatic retries, and best-practice error handling to simplify integration of Runway's video and image generation capabilities into Python applications and workflows.

**Human URL:** [https://docs.dev.runwayml.com/api-details/sdks/](https://docs.dev.runwayml.com/api-details/sdks/)


#### Tags:

 - Python, SDK, Libraries, Artificial Intelligence, Video Generation

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api-details/sdks/)

### Runway Node.js SDK
The Runway Node.js SDK provides a JavaScript and TypeScript library for interacting with the Runway API. It includes TypeScript bindings for type safety and is compatible with Node.js 18 and above. The SDK can be installed via npm, yarn, or pnpm, and provides automatic retries and best-practice error handling to streamline integration of Runway's generative AI capabilities into JavaScript and TypeScript applications.

**Human URL:** [https://docs.dev.runwayml.com/api-details/sdks/](https://docs.dev.runwayml.com/api-details/sdks/)


#### Tags:

 - Node.js, JavaScript, TypeScript, SDK, Libraries, Video Generation

#### Properties

- [Documentation](https://docs.dev.runwayml.com/api-details/sdks/)

## Common Properties

- [Portal](https://docs.dev.runwayml.com/)
- [Documentation](https://docs.dev.runwayml.com/api/)
- [Website](https://runwayml.com/)
- [PrivacyPolicy](https://runwayml.com/privacy-policy)
- [TermsOfService](https://runwayml.com/terms-of-use)
- [Blog](https://runwayml.com/blog)
- [Login](https://app.runwayml.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
