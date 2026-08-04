# Sarvam AI (sarvam-ai)

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

Sarvam AI is India's full-stack sovereign AI platform building large language models, speech, and translation systems for Indian languages. The Sarvam API serves chat completions (Sarvam-M / Sarvam-30B / Sarvam-105B), speech-to-text (Saaras / Saarika), text-to-speech (Bulbul), translation (Mayura / Sarvam-Translate), transliteration, and language identification across 10-22 Indic languages via a REST interface using an api-subscription-key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sarvam-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sarvam-ai/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Speech to Text
- Text to Speech
- Translation
- Indian Languages

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Sarvam AI Chat Completions (LLM) API

OpenAI-style chat completions over Sarvam's Indic LLMs (Sarvam-M, Sarvam-30B, Sarvam-105B) with streaming, tool use, reasoning effort, and wiki-grounding for Indian-language reasoning and conversation.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/chat/chat-completions](https://docs.sarvam.ai/api-reference-docs/chat/chat-completions)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/api-guides-tutorials/chat-completion/overview)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/chat/chat-completions)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [AsyncAPI](asyncapi/sarvam-ai-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Sarvam AI Speech-to-Text API

Multipart audio transcription for Indian languages using the Saaras and Saarika speech-recognition models, with auto language detection, word timestamps, and speaker diarization.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/speech-to-text/transcribe](https://docs.sarvam.ai/api-reference-docs/speech-to-text/transcribe)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Speech to Text
- Transcription
- ASR

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/endpoints/speech-to-text)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/speech-to-text/transcribe)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Sarvam AI Speech-to-Text Translate API

Transcribes Indic-language audio and translates the result into English in a single multipart request using the Saaras family of models.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/speech-to-text/translate](https://docs.sarvam.ai/api-reference-docs/speech-to-text/translate)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Speech to Text
- Translation
- ASR

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/endpoints/speech-to-text)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/speech-to-text/translate)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Sarvam AI Text-to-Speech API

Natural-voice speech synthesis for Indian languages using the Bulbul models (v2 and v3) with 30+ speakers, configurable pace, pitch, sample rate, and multiple output audio codecs, billed per 10,000 characters.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/text-to-speech/convert](https://docs.sarvam.ai/api-reference-docs/text-to-speech/convert)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Text to Speech
- Audio
- Bulbul

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/endpoints/text-to-speech)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/text-to-speech/convert)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Sarvam AI Translate API

Text translation across Indian languages using Mayura (12 languages, multiple tones) and Sarvam-Translate (all 22 scheduled languages), with tone modes, output-script control, and numeral formatting.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/text/translate](https://docs.sarvam.ai/api-reference-docs/text/translate)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Translation
- Text
- Mayura

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/endpoints/translate)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/text/translate)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Sarvam AI Transliterate API

Converts text between scripts while preserving the same language, with spoken-form conversion and international or native numeral formatting.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/text/transliterate](https://docs.sarvam.ai/api-reference-docs/text/transliterate)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Transliteration
- Script Conversion

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/endpoints/transliterate)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/text/transliterate)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Sarvam AI Language Identification API

Automatically detects the language and script of input text, returning BCP-47 language and script codes for routing to the appropriate Indic-language model.

- **Human URL:** [https://docs.sarvam.ai/api-reference-docs/text/identify-language](https://docs.sarvam.ai/api-reference-docs/text/identify-language)
- **Base URL:** `https://api.sarvam.ai`

#### Tags

- Language Identification
- Detection

#### Properties

- [Documentation](https://docs.sarvam.ai/api-reference-docs/endpoints/text-lid)
- [API Reference](https://docs.sarvam.ai/api-reference-docs/text/identify-language)
- [OpenAPI](openapi/sarvam-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sarvam-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Common Properties

- [GitHub Organization](https://github.com/sarvamai)
- [LinkedIn](https://www.linkedin.com/company/sarvam-ai)
- [Website](https://www.sarvam.ai)
- [Documentation](https://docs.sarvam.ai/api-reference-docs/introduction)
- [Plans](plans/sarvam-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/sarvam-ai-rate-limits.yml)
- [Fin Ops](finops/sarvam-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
