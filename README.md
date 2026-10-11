# Awesome Spec-Driven Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for Spec-Driven Development (SDD) - the practice of writing specifications first to guide development, testing, and documentation.

Spec-Driven Development is a methodology where comprehensive specifications are created before implementation begins. This approach ensures better alignment between requirements and delivery, improves code quality, and facilitates better testing and documentation.

## Contents

- [What is Spec-Driven Development?](#what-is-spec-driven-development)
- [API Design](#api-design)
- [Tools](#tools)
- [Languages & Frameworks](#languages--frameworks)
- [Testing](#testing)
- [Documentation](#documentation)
- [Articles & Tutorials](#articles--tutorials)
- [Books](#books)
- [Videos & Talks](#videos--talks)
- [Communities](#communities)
- [Examples](#examples)

## What is Spec-Driven Development?

Spec-Driven Development (SDD) is a development methodology where detailed specifications are written before any implementation begins. These specifications serve as:

- **Single Source of Truth**: All stakeholders refer to the same specification
- **Contract Definition**: Clear interfaces between components and services
- **Test Foundation**: Specifications drive automated testing strategies  
- **Documentation Base**: Living documentation that stays synchronized with code
- **Design Tool**: Forces thinking about design decisions upfront

## API Design

### OpenAPI/Swagger
- [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) - The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to RESTful APIs
- [Swagger Editor](https://editor.swagger.io/) - Online editor for writing OpenAPI specifications
- [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) - Generate API clients, server stubs and documentation from OpenAPI specs
- [Postman](https://www.postman.com/) - API development environment with OpenAPI support

### GraphQL
- [GraphQL](https://graphql.org/) - A query language and runtime for APIs with strong schema definition
- [Apollo Server](https://www.apollographql.com/docs/apollo-server/) - GraphQL server with schema-first development
- [GraphQL Code Generator](https://www.graphql-code-generator.com/) - Generate code from GraphQL schemas

### Other API Specifications
- [AsyncAPI](https://www.asyncapi.com/) - Specification for event-driven APIs
- [JSON Schema](https://json-schema.org/) - Vocabulary for validating JSON documents
- [Protocol Buffers](https://developers.google.com/protocol-buffers) - Language-neutral, platform-neutral extensible mechanism for serializing structured data

## Tools

### Design-First Tools
- [API Blueprint](https://apiblueprint.org/) - High-level API description language
- [Insomnia](https://insomnia.rest/) - API client with design-first workflow
- [RAML](https://raml.org/) - RESTful API Modeling Language
- **[Reqode](https://reqode.com)** - Connects requirements, architecture and tests to give AI coding agents specification context.
- [Stoplight Studio](https://stoplight.io/studio/) - Visual OpenAPI designer

### Code Generation
- [OpenAPI Generator](https://openapi-generator.tech/) - Generate clients, servers, and documentation from OpenAPI specs
- [QuickType](https://quicktype.io/) - Generate types and converters from JSON, schema, and GraphQL
- [JSON Schema to TypeScript](https://github.com/bcherny/json-schema-to-typescript) - Compile JSON Schema to TypeScript type definitions

### Validation & Testing
- [Dredd](https://github.com/apiaryio/dredd) - HTTP API testing framework based on API Blueprint and OpenAPI
- [Prism](https://github.com/stoplightio/prism) - Mock server and validator for OpenAPI specifications
- [OpenAPI Diff](https://github.com/OpenAPITools/openapi-diff) - Compare OpenAPI specifications

## Languages & Frameworks

### JavaScript/TypeScript
- [tRPC](https://trpc.io/) - End-to-end typesafe APIs made easy
- [Zod](https://zod.dev/) - TypeScript-first schema validation with static type inference
- [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript
- [io-ts](https://github.com/gcanti/io-ts) - Runtime type system for IO decoding/encoding

### Python
- [Pydantic](https://pydantic-docs.helpmanual.io/) - Data validation and settings management using Python type annotations
- [FastAPI](https://fastapi.tiangolo.com/) - Modern, fast web framework with automatic API documentation
- [Marshmallow](https://marshmallow.readthedocs.io/) - Object serialization/deserialization library

### Java
- [Spring Boot](https://spring.io/projects/spring-boot) - Framework with excellent OpenAPI integration
- [Bean Validation](https://beanvalidation.org/) - Java specification for validating data

### Go
- [Protocol Buffers for Go](https://developers.google.com/protocol-buffers/docs/gotutorial) - Go tutorial for Protocol Buffers
- [Gin with OpenAPI](https://github.com/swaggo/gin-swagger) - Gin middleware to automatically generate OpenAPI documentation

## Testing

### Contract Testing
- [Pact](https://pact.io/) - Contract testing framework
- [Spring Cloud Contract](https://spring.io/projects/spring-cloud-contract) - Contract-driven development for JVM applications
- [Wiremock](http://wiremock.org/) - Mock server for HTTP-based APIs

### Property-Based Testing
- [QuickCheck](https://hackage.haskell.org/package/QuickCheck) - Property-based testing library for Haskell
- [Hypothesis](https://hypothesis.works/) - Property-based testing for Python
- [fast-check](https://github.com/dubzzz/fast-check) - Property-based testing framework for JavaScript/TypeScript

## Documentation

### Interactive Documentation
- [Swagger UI](https://swagger.io/tools/swagger-ui/) - Interactive API documentation
- [ReDoc](https://github.com/Redocly/redoc) - Beautiful API documentation from OpenAPI specs
- [Stoplight Elements](https://stoplight.io/open-source/elements) - Beautiful, interactive API documentation

### Documentation as Code
- [GitBook](https://www.gitbook.com/) - Documentation platform with API integration
- [Notion](https://www.notion.so/) - All-in-one workspace with API documentation features
- [Confluence](https://www.atlassian.com/software/confluence) - Team workspace with API documentation capabilities

## Articles & Tutorials

- [API Design-First vs Code-First](https://swagger.io/resources/articles/adopting-an-api-first-approach/) - Understanding the design-first approach
- [Contract-First Development](https://martinfowler.com/articles/consumerDrivenContracts.html) - Martin Fowler on Consumer-Driven Contracts
- [Schema-First GraphQL Development](https://www.apollographql.com/blog/graphql/basics/schema-first-vs-code-first-development-graphql/) - Apollo's guide to schema-first GraphQL

## Books

- [Building APIs with Node.js](https://www.apress.com/gp/book/9781484224427) - Comprehensive guide to API development with Node.js
- [API Design Patterns](https://www.manning.com/books/api-design-patterns) - Common patterns for designing web APIs
- [Microservices Patterns](https://www.manning.com/books/microservices-patterns) - Includes patterns for service contracts and API design

## Videos & Talks

- [API Design-First Approach](https://www.youtube.com/watch?v=6kwmW_p_Tig) - Introduction to design-first API development
- [Contract Testing with Pact](https://www.youtube.com/watch?v=MDydAqL4mYE) - Comprehensive guide to contract testing
- [GraphQL Schema Design](https://www.youtube.com/watch?v=pJamhW2xPYw) - Best practices for GraphQL schema design

## Communities

- [OpenAPI Community](https://github.com/OAI/OpenAPI-Specification/discussions) - Discussion forum for OpenAPI specification
- [GraphQL Community](https://graphql.org/community/) - GraphQL community resources and forums
- [API Evangelist](https://apievangelist.com/) - Community focused on API industry and best practices
- [r/webdev](https://www.reddit.com/r/webdev/) - Web development community with API discussions

## Examples

### Sample Projects
- [OpenAPI Petstore](https://github.com/swagger-api/swagger-petstore) - Sample OpenAPI specification and implementation
- [GraphQL Examples](https://github.com/graphql/graphql-js/tree/main/src/__tests__) - GraphQL.js examples and tests
- [tRPC Examples](https://github.com/trpc/trpc/tree/main/examples) - Various tRPC implementation examples

### Real-World APIs
- [GitHub API](https://docs.github.com/en/rest) - Well-documented REST API with OpenAPI specification
- [Stripe API](https://stripe.com/docs/api) - Excellent example of API design and documentation
- [Twilio API](https://www.twilio.com/docs/usage/api) - Clear API documentation and SDKs

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
