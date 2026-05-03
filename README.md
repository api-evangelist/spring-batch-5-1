# Spring Batch 5.1

Spring Batch 5.1 is the latest major release of the enterprise batch processing framework for the Spring ecosystem. It provides reusable functions for processing large volumes of data including logging, transaction management, job processing statistics, job restart, skip, and resource management. Version 5.1 introduces Micrometer-based metrics, virtual thread support (Java 21), and enhanced chunk-oriented processing with improved fault tolerance.

- **URL:** https://spring.io/projects/spring-batch
- **Type:** Open Source
- **Tags:** Batch Processing, Data Processing, Enterprise, ETL, Java, Job Scheduling, Spring Framework

## APIs

### Spring Batch 5.1 Core API

Core framework API for Spring Batch 5.1 including job configuration, chunk-oriented processing, step execution, job repository, and fault tolerance features including retry and skip policies.

- [Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/)
- [API Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/api/)
- [GitHub Repository](https://github.com/spring-projects/spring-batch)
- [Getting Started Guide](https://spring.io/guides/gs/batch-processing/)
- [Samples](https://github.com/spring-projects/spring-batch/tree/main/spring-batch-samples)
- [Release Notes](https://github.com/spring-projects/spring-batch/releases/tag/5.1.0)
- [Maven Central](https://mvnrepository.com/artifact/org.springframework.batch/spring-batch-core/5.1.0)

### Spring Batch 5.1 Infrastructure API

ItemReader, ItemWriter, ItemProcessor implementations for flat files, XML, JSON, JPA, JDBC, MongoDB, and remote chunking/partitioning.

- [Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/readersAndWriters.html)

### Spring Batch 5.1 Integration API

Spring Integration support for remote partitioning, remote chunking, and message-driven batch processing.

- [Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/spring-batch-integration.html)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spring Batch 5.1 Actuator API | [openapi/spring-batch-51-openapi.yml](openapi/spring-batch-51-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spring Batch 5.1 Rules | [rules/spring-batch-51-rules.yml](rules/spring-batch-51-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Spring Batch 5.1 Actuator API | [capabilities/shared/spring-batch-51-actuator.yaml](capabilities/shared/spring-batch-51-actuator.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Batch Job Monitoring | Monitor job executions, metrics, and health | [capabilities/batch-job-monitoring.yaml](capabilities/batch-job-monitoring.yaml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Job Execution | [json-schema/spring-batch-51-job-execution-schema.json](json-schema/spring-batch-51-job-execution-schema.json) |
| Job Parameters | [json-schema/spring-batch-51-job-parameters-schema.json](json-schema/spring-batch-51-job-parameters-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Job Execution Domain Model | [json-structure/spring-batch-51-job-execution-structure.json](json-structure/spring-batch-51-job-execution-structure.json) |

## JSON-LD Contexts

| Context | File |
|---------|------|
| Spring Batch 5.1 | [json-ld/spring-batch-5-1-context.jsonld](json-ld/spring-batch-5-1-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Application Health | [examples/spring-batch-51-get-health-example.json](examples/spring-batch-51-get-health-example.json) |
| List Job Executions | [examples/spring-batch-51-list-job-executions-example.json](examples/spring-batch-51-list-job-executions-example.json) |
| Get Metric Value | [examples/spring-batch-51-get-metric-example.json](examples/spring-batch-51-get-metric-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spring Batch 5.1 Domain Terms | [vocabulary/spring-batch-5-1-vocabulary.yml](vocabulary/spring-batch-5-1-vocabulary.yml) |

## Common Resources

- [Blog](https://spring.io/blog/category/spring-batch)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-batch)
- [GitHub Issues](https://github.com/spring-projects/spring-batch/issues)
- [GitHub Discussions](https://github.com/spring-projects/spring-batch/discussions)
- [Contributing Guidelines](https://github.com/spring-projects/spring-batch/blob/main/CONTRIBUTING.md)
- [License](https://github.com/spring-projects/spring-batch/blob/main/LICENSE)
