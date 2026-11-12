<p align="center"><img src="./1-header.png" alt="Rajatendu Dey - Backend engineer: distributed systems, auth and identity" width="100%" /></p>

Backend engineer building distributed backend systems, authentication and identity infrastructure, and AI-powered applications. Formerly SDE II at AWS (UnifiedAuth) and an engineer at HSBC; previously a machine learning intern at HighRadius.

## Open source

Merged upstream:

- **[authlib #1031](https://github.com/authlib/authlib/pull/1031)** - fixed default-port handling for IPv6 hosts in OAuth 1.0a signature base-string URIs, with regression tests across IPv4/IPv6 and default, non-default and missing ports. Merged 10 Nov 2026.
- **[gookit/goutil #316](https://github.com/gookit/goutil/pull/316)** - `timex` now decodes JSON strings before parsing dates: escaped timestamps decode correctly, numbers can no longer be misread as dates, and `0`/`1` no longer cause a slice-bounds panic. Merged 12 Nov 2026.

Further patches under review upstream across Python, Rust, JavaScript and TypeScript projects.

## Current projects

### llmgate
**An OpenAI-compatible LLM gateway**

Routing, failover, streaming, per-key rate limits and usage metering behind one `/v1/chat/completions` endpoint.

Verified 11 Nov 2026: **274** pytest cases, **61** local end-to-end HTTP checks, a JavaScript smoke gate, plus Docker image and Compose smoke checks in CI.

**[Live demo →](https://llmgate-demo.vercel.app)** · **[Source →](https://github.com/Rajatendu1/llmgate)** - mint a 24-hour key and call it from your own OpenAI-compatible client. Keys reach the simulated providers only; two real free-tier Groq models sit behind explicit buttons.

---

### actas
**Delegation tokens for AI agents**

A reference implementation of RFC 8693 token exchange, where permissions can only shrink down a delegation chain, with DPoP-style sender constraints and a hash-chained audit log.

Recovery gate passed 11 Nov 2026: **48** pytest cases, **17** integration checks, **26** process checks, plus desktop and mobile browser workflows. These are new post-recovery checks; the original development suite was not recovered.

**[Live demo →](https://actas-rajatendu.vercel.app)** · **[Source →](https://github.com/Rajatendu1/actas)** - includes a policy workbench for what-if policy review.

---

Both are tested working prototypes, not production services. Source is public on GitHub.

**[Full evidence notes →](https://files.instinct.com/2b6sxnm5u1fv-rajatendu-dey-engineering-portfolio)**

## How these were built

The projects and patches above were designed and built by Instinct, my AI assistant, working at my direction.

## Contact

Open to backend, platform and AI-infrastructure roles, Bangalore or remote.

**[Portfolio →](https://rajatendu-dey.vercel.app)**
