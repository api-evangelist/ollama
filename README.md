# Ollama (ollama)

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
