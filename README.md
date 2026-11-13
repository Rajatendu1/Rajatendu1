<p align="center"><img src="assets/header.svg" alt="Rajatendu Dey - Backend engineer: distributed systems, auth and identity, AI-powered applications" width="100%" /></p>

<p align="center">
  <a href="https://rajatendu-dey.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-rajatendu--dey.vercel.app-9de8d0?style=flat-square&labelColor=080e19" alt="Portfolio" /></a>
  <a href="https://llmgate-demo.vercel.app"><img src="https://img.shields.io/badge/LLMGATE-live%20demo-7cc7ff?style=flat-square&labelColor=080e19" alt="llmgate live demo" /></a>
  <a href="https://actas-rajatendu.vercel.app"><img src="https://img.shields.io/badge/ACTAS-live%20demo-a5b5ff?style=flat-square&labelColor=080e19" alt="actas live demo" /></a>
  <img src="https://img.shields.io/badge/OPEN%20TO%20WORK-Bangalore%20%2F%20remote-f0a35e?style=flat-square&labelColor=080e19" alt="Open to work: Bangalore or remote" />
</p>

<p align="center">
  <a href="#projects-tested-and-live">Projects</a> ·
  <a href="#open-source-merged-upstream">Open source</a> ·
  <a href="#evidence-with-receipts">Evidence</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#contact">Contact</a>
</p>

Backend engineer building distributed backend systems, authentication and identity infrastructure, and AI-powered applications. Formerly SDE II at AWS (UnifiedAuth) and an engineer at HSBC; previously a machine learning intern at HighRadius.

<a id="projects-tested-and-live"></a>
<p align="center"><img src="assets/section-projects.svg" alt="Projects, tested and live" width="100%" /></p>

<table>
<tr>
<td width="50%"><a href="https://github.com/Rajatendu1/llmgate"><img src="assets/card-llmgate.svg" width="100%" alt="llmgate: OpenAI-compatible LLM gateway. Explore the repository." /></a></td>
<td width="50%"><a href="https://github.com/Rajatendu1/actas"><img src="assets/card-actas.svg" width="100%" alt="actas: delegation tokens for AI agents. Explore the repository." /></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/Rajatendu1/equity-research-agent"><img src="assets/card-vigilant.svg" width="100%" alt="Vigilant: AI-assisted Indian equity research. Explore the repository." /></a></td>
<td width="50%"><a href="https://github.com/Rajatendu1/engineering-portfolio"><img src="assets/card-portfolio.svg" width="100%" alt="Engineering portfolio. Explore the repository." /></a></td>
</tr>
</table>

**llmgate** - routing, failover, streaming, per-key rate limits and usage metering behind one `/v1/chat/completions` endpoint. **[Live demo →](https://llmgate-demo.vercel.app)** · **[Source →](https://github.com/Rajatendu1/llmgate)**

**actas** - an RFC 8693 token-exchange reference implementation where permissions can only shrink down a delegation chain, with DPoP-style sender constraints and a hash-chained audit log. **[Live demo →](https://actas-rajatendu.vercel.app)** · **[Source →](https://github.com/Rajatendu1/actas)**

**Vigilant** - turns an Indian stock name into a structured, evidence-backed investment view. **[Source →](https://github.com/Rajatendu1/equity-research-agent)**

Both live demos are tested working prototypes, not production services. llmgate keys reach the simulated providers only; two real free-tier Groq models sit behind explicit buttons.

<a id="open-source-merged-upstream"></a>
<p align="center"><img src="assets/section-oss.svg" alt="Open source, merged upstream" width="100%" /></p>

Merged upstream:

- **[authlib #1031](https://github.com/authlib/authlib/pull/1031)** - fixed default-port handling for IPv6 hosts in OAuth 1.0a signature base-string URIs, with regression tests across IPv4/IPv6 and default, non-default and missing ports. Merged 10 Nov 2026.
- **[gookit/goutil #316](https://github.com/gookit/goutil/pull/316)** - `timex` now decodes JSON strings before parsing dates: escaped timestamps decode correctly, numbers can no longer be misread as dates, and `0`/`1` no longer cause a slice-bounds panic. Merged 12 Nov 2026.


Selected issues and ongoing contributions:

- **[graphql/graphql-js #5002](https://github.com/graphql/graphql-js/pull/5002)** - adds `hideSuggestions` support when building and extending schemas. Pull request open.
- **[msgspec/msgspec #1342](https://github.com/msgspec/msgspec/pull/1342)** - preserves and validates typed `TypedDict` extra items. Pull request open.
- **[microsoft/pyright #12010](https://github.com/microsoft/pyright/pull/12010)** - fixes stale CLI watch diagnostics after file deletion. Pull request open.
- **[graphql-python/graphene #1612](https://github.com/graphql-python/graphene/pull/1612)** - fixes enum construction after registering an enum named `type`. Pull request open.
- **[pytorch/pytorch #204781](https://github.com/pytorch/pytorch/issues/204781)** - reported that `torch._numpy.pad` silently crops input for a negative `pad_width`. Issue open.
- **[facelessuser/wcmatch #278](https://github.com/facelessuser/wcmatch/issues/278)** - reported that REALPATH glob matching rejects a symlink path returned by `glob`. Issue open.

Further patches open upstream across Python, Rust, JavaScript and TypeScript projects.

<a id="evidence-with-receipts"></a>
<p align="center"><img src="assets/section-evidence.svg" alt="Evidence, with receipts" width="100%" /></p>

| Project | Verified | Checks |
| --- | --- | --- |
| llmgate | 11 Nov 2026 | **274** pytest cases, **61** local end-to-end HTTP checks, a JavaScript smoke gate, plus Docker image and Compose smoke checks in CI |
| actas | 11 Nov 2026 | **48** pytest cases, **17** integration checks, **26** process checks, plus desktop and mobile browser workflows (new post-recovery checks; the original development suite was not recovered) |

**[Full evidence notes →](https://files.instinct.com/2b6sxnm5u1fv-rajatendu-dey-engineering-portfolio)**

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,typescript,javascript,go,docker,redis,postgres,aws,githubactions,vercel&theme=dark" alt="Python, TypeScript, JavaScript, Go, Docker, Redis, Postgres, AWS, GitHub Actions, Vercel" />
</p>

## GitHub

<p align="center"><img src="assets/github-snapshot.svg" alt="GitHub snapshot: 14 followers, 41 public repos, 20 owned non-fork, 17 stars. Verified 12 Nov 2026." width="100%" /></p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Rajatendu1&hide_border=true&background=080e19&ring=9de8d0&fire=f0a35e&currStreakLabel=9de8d0&sideLabels=a7b8ce&dates=5b7186&currStreakNum=edf3ff&sideNums=edf3ff" alt="GitHub streak" />
</p>

## How these were built

The projects and patches above were designed and built by Instinct, my AI assistant, working at my direction.

<a id="contact"></a>

## Contact

Open to backend, platform and AI-infrastructure roles, Bangalore or remote.

**[Portfolio →](https://rajatendu-dey.vercel.app)**
