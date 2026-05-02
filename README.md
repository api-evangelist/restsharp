# RestSharp

RestSharp is a simple REST and HTTP API client library for .NET that wraps HttpClient with a fluent API for making HTTP requests with automatic serialization and deserialization of request and response bodies. Used by developers building .NET applications that consume REST APIs. Apache-2.0 licensed, .NET Foundation project with 9,800+ GitHub stars.

**Website:** [https://restsharp.dev/](https://restsharp.dev/)
**GitHub:** [https://github.com/restsharp/RestSharp](https://github.com/restsharp/RestSharp)
**NuGet:** [https://www.nuget.org/packages/RestSharp](https://www.nuget.org/packages/RestSharp)
**Current Version:** 114.0.0 (released March 2026)

## Library

### RestSharp .NET Client Library

A fluent .NET HTTP client library supporting JSON, XML, and CSV serialization, OAuth1/OAuth2/JWT/Basic authentication, async operations, multipart file uploads, and comprehensive parameter management.

- **Documentation:** [https://restsharp.dev/docs/intro/](https://restsharp.dev/docs/intro/)
- **GitHub:** [https://github.com/restsharp/RestSharp](https://github.com/restsharp/RestSharp)
- **License:** Apache-2.0
- **Target Frameworks:** .NET 8.0, .NET Standard 2.0, .NET Framework 4.7.1

## Common Properties

| Type | URL |
|------|-----|
| Website | https://restsharp.dev/ |
| Documentation | https://restsharp.dev/docs/intro/ |
| GitHub Organization | https://github.com/restsharp |
| NuGet Package | https://www.nuget.org/packages/RestSharp |
| License | Apache-2.0 |
| Issue Tracker | https://github.com/restsharp/RestSharp/issues |

## Artifacts

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/restsharp-rest-client-options-schema.json](json-schema/restsharp-rest-client-options-schema.json) | RestClientOptions configuration schema |
| [json-schema/restsharp-rest-request-schema.json](json-schema/restsharp-rest-request-schema.json) | RestRequest object schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/restsharp-rest-client-options-structure.json](json-structure/restsharp-rest-client-options-structure.json) | RestClientOptions field reference |
| [json-structure/restsharp-rest-request-structure.json](json-structure/restsharp-rest-request-structure.json) | RestRequest field reference |

### JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/restsharp-context.jsonld](json-ld/restsharp-context.jsonld) | JSON-LD context for RestSharp library vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/restsharp-get-request-example.json](examples/restsharp-get-request-example.json) | Simple typed GET request |
| [examples/restsharp-post-json-example.json](examples/restsharp-post-json-example.json) | POST JSON body with typed response |
| [examples/restsharp-bearer-auth-example.json](examples/restsharp-bearer-auth-example.json) | Bearer token authentication setup |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/restsharp-vocabulary.yml](vocabulary/restsharp-vocabulary.yml) | Domain vocabulary for RestSharp classes, methods, and concepts |

## Quick Start

```bash
dotnet add package RestSharp
```

```csharp
var options = new RestClientOptions("https://api.example.com");
var client = new RestClient(options);
var request = new RestRequest("/users/{id}");
request.AddUrlSegment("id", 42);
var user = await client.GetAsync<User>(request);
```

## Maintainers

- **Kin Lane** — kin@apievangelist.com
