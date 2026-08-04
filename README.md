# Spring Cloud Config (spring-cloud-config)

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

Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN, or filesystem repositories with support for encryption, decryption, and runtime refresh.

**APIs.json:** [https://spring.io/projects/spring-cloud-config](https://spring.io/projects/spring-cloud-config)

## Tags

- Configuration Management
- Distributed Systems
- Externalized Configuration
- Git
- Java
- Microservices
- Spring
- Spring Cloud

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Spring Cloud Config Server API

HTTP resource-based API for external configuration management. Serves property sources organized by application name, profile, and label (git branch/tag). Supports JSON, YAML, and Java properties formats plus encryption/decryption and webhook-triggered refresh notifications.

- **Human URL:** [https://spring.io/projects/spring-cloud-config](https://spring.io/projects/spring-cloud-config)
- **Base URL:** `http://localhost:8888`

#### Tags

- Configuration
- Configuration Management
- Distributed Systems
- Encryption
- Externalized Configuration
- Git
- Microservices

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-config/reference/server/environment-repository.html)
- [OpenAPI](openapi/spring-cloud-config-server-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-cloud-config-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-config-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/spring-cloud-config-environment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spring-cloud-config-server-configuration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/spring-cloud-config-environment-structure.json)
- [J S O N L D Context](json-ld/spring-cloud-config-context.jsonld)
- [Spectral Rules](rules/spring-cloud-config-rules.yml)

## Common Properties

- [Website](https://spring.io/projects/spring-cloud-config)
- [Documentation](https://docs.spring.io/spring-cloud-config/reference/)
- [Getting Started](https://spring.io/guides/gs/centralized-configuration/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-config)
- [GitHub Organization](https://github.com/spring-cloud)
- [Issues](https://github.com/spring-cloud/spring-cloud-config/issues)
- [Releases](https://github.com/spring-cloud/spring-cloud-config/releases)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud-config)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-config-server)
- [Vocabulary](vocabulary/spring-cloud-config-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
