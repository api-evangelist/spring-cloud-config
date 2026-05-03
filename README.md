# Spring Cloud Config

Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN, or filesystem repositories with support for encryption, decryption, and runtime refresh.

**URL:** https://spring.io/projects/spring-cloud-config

## Tags

Configuration Management, Distributed Systems, Externalized Configuration, Git, Java, Microservices, Spring, Spring Cloud

## APIs

### Spring Cloud Config Server API

HTTP resource-based API for external configuration management. Serves property sources organized by application name, profile, and label (git branch/tag). Supports JSON, YAML, and Java properties formats plus encryption/decryption and webhook-triggered refresh notifications.

**Human URL:** https://spring.io/projects/spring-cloud-config  
**Base URL:** http://localhost:8888

**Tags:** Configuration, Configuration Management, Distributed Systems, Encryption, Externalized Configuration, Git, Microservices

**Properties:**
- [Documentation](https://docs.spring.io/spring-cloud-config/reference/server/environment-repository.html)
- [OpenAPI](openapi/spring-cloud-config-server-api.yml)
- [JSON Schema - Environment](json-schema/spring-cloud-config-environment-schema.json)
- [JSON Schema - Server Configuration](json-schema/spring-cloud-config-server-configuration-schema.json)
- [JSON Structure](json-structure/spring-cloud-config-environment-structure.json)
- [JSON-LD Context](json-ld/spring-cloud-config-context.jsonld)
- [Spectral Rules](rules/spring-cloud-config-rules.yml)
- [Naftiko Capability](capabilities/configuration-management.yaml)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-cloud-config-server-api.yml](openapi/spring-cloud-config-server-api.yml) | Config Server HTTP API for configuration retrieval, encryption, and webhook refresh |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-cloud-config-environment-schema.json](json-schema/spring-cloud-config-environment-schema.json) | Config Server environment response schema |
| [spring-cloud-config-server-configuration-schema.json](json-schema/spring-cloud-config-server-configuration-schema.json) | Config Server application properties schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-cloud-config-environment-structure.json](json-structure/spring-cloud-config-environment-structure.json) | Environment and PropertySource structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-cloud-config-context.jsonld](json-ld/spring-cloud-config-context.jsonld) | Spring Cloud Config linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-cloud-config-get-environment-example.json](examples/spring-cloud-config-get-environment-example.json) | Get application configuration for production profile |
| [spring-cloud-config-encrypt-value-example.json](examples/spring-cloud-config-encrypt-value-example.json) | Encrypt a sensitive configuration value |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-cloud-config-rules.yml](rules/spring-cloud-config-rules.yml) | API design rules for Spring Cloud Config conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/configuration-management.yaml](capabilities/configuration-management.yaml) | Configuration management workflow (fetch, encrypt, refresh) |
| [capabilities/shared/spring-cloud-config-server.yaml](capabilities/shared/spring-cloud-config-server.yaml) | Shared Config Server API consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-cloud-config-vocabulary.yml](vocabulary/spring-cloud-config-vocabulary.yml) | Spring Cloud Config domain vocabulary and terminology |

## Common Properties

- [Website](https://spring.io/projects/spring-cloud-config)
- [Documentation](https://docs.spring.io/spring-cloud-config/reference/)
- [Getting Started](https://spring.io/guides/gs/centralized-configuration/)
- [GitHub](https://github.com/spring-cloud/spring-cloud-config)
- [GitHub Organization](https://github.com/spring-cloud)
- [Issues](https://github.com/spring-cloud/spring-cloud-config/issues)
- [Releases](https://github.com/spring-cloud/spring-cloud-config/releases)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud-config)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-config-server)

## Maintainers

**Name:** Kin Lane  
**Email:** kin@apievangelist.com
