# Ollama (ollama)

API for running large language models locally.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ollama/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ollama/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence
- Large Language Models
- Models

## Timestamps

- **Created:** 2025-11-19
- **Modified:** 2026-05-19

## APIs

### Ollama API

Ollama provides a REST API for running and managing large language models locally. The API supports text generation, chat completions, embeddings, model management, and streaming responses. It serves as the primary interface for interacting with models running on the Ollama inference engine at localhost:11434.

- **Human URL:** [https://docs.ollama.com/api/introduction](https://docs.ollama.com/api/introduction)
- **Base URL:** `http://localhost:11434/api`

#### Tags

- Inference
- Large Language Models
- Local AI
- Models

#### Properties

- [Documentation](https://docs.ollama.com/)
- [OpenAPI](https://docs.ollama.com/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.ollama.com/api/introduction)
- [Authentication](https://docs.ollama.com/api/authentication)
- [Documentation](https://docs.ollama.com/api/generate)
- [Documentation](https://docs.ollama.com/api/chat)
- [Documentation](https://docs.ollama.com/api/embed)
- [Documentation](https://docs.ollama.com/api/tags)
- [Documentation](https://docs.ollama.com/api/ps)
- [Documentation](https://docs.ollama.com/api/create)
- [Documentation](https://docs.ollama.com/api/pull)
- [Documentation](https://docs.ollama.com/api/push)
- [Documentation](https://docs.ollama.com/api/copy)
- [Documentation](https://docs.ollama.com/api/delete)
- [Documentation](https://docs.ollama.com/api/show)
- [Documentation](https://docs.ollama.com/api/streaming)
- [Documentation](https://docs.ollama.com/api/errors)
- [Documentation](https://docs.ollama.com/api/usage)
- [Documentation](https://docs.ollama.com/api/blobs)
- [Documentation](https://docs.ollama.com/api/version)
- [Postman Collection](collections/ollama-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ollama-openai-compatibility-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-openai-compatibility-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ollama OpenAI Compatibility API

Ollama provides compatibility with parts of the OpenAI API, allowing existing applications built for OpenAI to connect to locally-running models through Ollama. Supported endpoints include chat completions, completions, embeddings, models, and the Responses API.

- **Human URL:** [https://docs.ollama.com/api/openai-compatibility](https://docs.ollama.com/api/openai-compatibility)
- **Base URL:** `http://localhost:11434/v1`

#### Tags

- Chat
- Compatibility
- Large Language Models
- OpenAI

#### Properties

- [Documentation](https://docs.ollama.com/api/openai-compatibility)
- [Blog](https://ollama.com/blog/openai-compatibility)
- [Blog R S S](https://ollama.com/blog/rss.xml)
- [Postman Collection](collections/ollama-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ollama-openai-compatibility-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-openai-compatibility-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ollama Anthropic Compatibility API

Ollama provides compatibility with the Anthropic Messages API, enabling tools like Claude Code to work with locally-running open-source models. Supports messages, streaming, system prompts, tool calling, extended thinking, and vision input.

- **Human URL:** [https://docs.ollama.com/api/anthropic-compatibility](https://docs.ollama.com/api/anthropic-compatibility)
- **Base URL:** `http://localhost:11434`

#### Tags

- Anthropic
- Chat
- Compatibility
- Large Language Models

#### Properties

- [Documentation](https://docs.ollama.com/api/anthropic-compatibility)
- [Blog](https://ollama.com/blog/claude)
- [Postman Collection](collections/ollama-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ollama-openai-compatibility-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-openai-compatibility-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ollama Cloud API

Ollama Cloud provides cloud-hosted inference for large language models, giving access to larger models and faster responses without requiring a powerful local GPU. Cloud models are accessed through the same API interface as local models, with requests encrypted in transit and no storage of prompts or outputs.

- **Human URL:** [https://docs.ollama.com/cloud](https://docs.ollama.com/cloud)
- **Base URL:** `https://ollama.com/api`

#### Tags

- Cloud
- Inference
- Large Language Models

#### Properties

- [Documentation](https://docs.ollama.com/cloud)
- [Getting Started](https://ollama.com/cloud)
- [Pricing](https://ollama.com/pricing)
- [Authentication](https://ollama.com/settings/keys)
- [Models](https://ollama.com/search?c=cloud)
- [Postman Collection](collections/ollama-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ollama-openai-compatibility-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ollama-openai-compatibility-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://ollama.com/)
- [Documentation](https://docs.ollama.com/)
- [F A Q](https://docs.ollama.com/faq)
- [Login](https://signin.ollama.com/?client_id=client_01JX0QMHD43PFFCCNXH82A6K8B&redirect_uri=https%3A%2F%2Follama.com%2Fauth%2Fcallback&authorization_session_id=01KE5QZJQP6W24EJGN9TYDR5K8)
- [Sign Up](https://signin.ollama.com/sign-up?redirect_uri=https%3A%2F%2Follama.com%2Fauth%2Fcallback&authorization_session_id=01KE5QZJQP6W24EJGN9TYDR5K8)
- [Pricing](https://ollama.com/cloud)
- [Git Hub](https://github.com/ollama/ollama)
- [Blog](https://ollama.ai/blog)
- [Models](https://ollama.ai/library)
- [OpenAPI](https://docs.ollama.com/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.ollama.com/quickstart)
- [Authentication](https://docs.ollama.com/api/authentication)
- [Pricing](https://ollama.com/pricing)
- [Downloads](https://ollama.com/download)
- [Models](https://ollama.com/search)
- [Blog](https://ollama.com/blog)
- [Changelog](https://github.com/ollama/ollama/releases)
- [Security](https://github.com/ollama/ollama/security)
- [Python S D K](https://github.com/ollama/ollama-python)
- [Java Script S D K](https://github.com/ollama/ollama-js)
- [Discord](https://discord.gg/ollama)
- [Reddit](https://reddit.com/r/ollama)
- [X (Twitter)](https://twitter.com/ollama)
- [LinkedIn](https://www.linkedin.com/company/ollama)
- [Documentation](https://docs.ollama.com/capabilities/tool-calling)
- [Documentation](https://docs.ollama.com/capabilities/structured-outputs)
- [Documentation](https://docs.ollama.com/capabilities/vision)
- [Documentation](https://docs.ollama.com/capabilities/embeddings)
- [Documentation](https://docs.ollama.com/capabilities/thinking)
- [Documentation](https://docs.ollama.com/capabilities/web-search)
- [Documentation](https://docs.ollama.com/capabilities/streaming)
- [Integrations](https://docs.ollama.com/integrations)
- [Docker](https://docs.ollama.com/docker)
- [Documentation](https://docs.ollama.com/modelfile)
- [C L I](https://docs.ollama.com/cli)
- [Documentation](https://docs.ollama.com/gpu)
- [Troubleshooting](https://docs.ollama.com/troubleshooting)
- [Documentation](https://docs.ollama.com/import)
- [Documentation](https://docs.ollama.com/context-length)
- [Dart  S D K](https://github.com/ollama/ollama-dart)
- [Swift  S D K](https://github.com/ollama/ollama-swift)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/ollama)
- [YouTube](https://www.youtube.com/@Ollama-AI)
- [GitHub Organization](https://github.com/ollama)
- [Issue  Tracker](https://github.com/ollama/ollama/issues)
- [Events](https://ollama.com/events)
- [Go  S D K](https://pkg.go.dev/github.com/ollama/ollama/api)
- [Documentation](https://docs.ollama.com/llms.txt)
- [Documentation](https://docs.ollama.com/linux)
- [Documentation](https://docs.ollama.com/macos)
- [Documentation](https://docs.ollama.com/windows)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
