# RestSharp

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
