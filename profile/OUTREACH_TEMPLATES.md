# Open-Source Outreach Templates

Use these as starting points, not bulk messages. Personalize each note with the recipient's product, a relevant integration, and a specific question. Do not claim adoption, security certification, customer use, or results that you cannot verify.

## 1. Company sponsorship or technical evaluation

**Subject:** Open-source security tooling for Node.js — technical evaluation or sponsorship

Hi [Name/Team],

I'm reaching out from AxiomNode-lab, where we build software engineering, security, and developer-infrastructure tools.

Our project [AxiomGuard](https://github.com/AxiomNode-lab/AxiomGuard) provides modular security building blocks for Node.js and TypeScript services, including webhook verification, API-key utilities, request policies, rate limiting, safer outbound requests, and repository secret scanning.

I noticed [specific product, integration, or engineering topic] at [Company]. I'm interested in whether AxiomGuard could be useful in that workflow, and where its current limitations are.

Would someone on your team be open to trying one focused workflow or sharing technical feedback? We're also exploring sponsorship for clearly scoped work such as integration tests, release reliability, documentation, and security-quality improvements.

Project: https://github.com/AxiomNode-lab/AxiomGuard  
Support priorities: https://github.com/AxiomNode-lab/.github/blob/main/profile/OPEN_SOURCE_SUPPORT.md

If this is relevant, I can send a minimal reproduction or propose a small evaluation with concrete acceptance criteria.

Best,  
AxiomNode-lab  
info@axiomnode.tech

## 2. Maintainer / developer feedback request

Hi [Name],

I saw your work on [specific Node.js / TypeScript / application-security repository or discussion]. I'm building [AxiomGuard](https://github.com/AxiomNode-lab/AxiomGuard), a small security toolkit for backend services.

I'm looking for feedback on one narrow area: [name a feature, integration, or limitation]. Would you be willing to review the example or try it in a small test project? An honest report that the project does not fit your workflow is useful too.

Here's the shortest path to try it: [link to exact guide or example]. Known limitations are documented in [link to the relevant section].

Thanks for considering it — no commitment is expected.

## 3. Open-source funding / grant intake draft

**Project:** AxiomGuard  
**Maintainer organization:** AxiomNode-lab  
**Repository:** https://github.com/AxiomNode-lab/AxiomGuard  
**License:** MIT (verify against the current repository license before submitting)  
**Primary funding use:** [choose a scoped work package]

### Problem and ecosystem relevance

AxiomGuard provides reusable security primitives for Node.js and TypeScript services. A funding application should explain which users or projects depend on the relevant security controls, why the component matters beyond the maintainer's own applications, and what risk or maintenance gap the proposed work addresses.

### Proposed work packages

Choose only the work the team can deliver:

- [ ] Reproducible security regression tests for named controls
- [ ] Framework integration tests for Express, Fastify, Hono, or Fetch runtimes
- [ ] Release and package verification for stable and prerelease channels
- [ ] Threat-model updates and precise security-boundary documentation
- [ ] Independent review of a defined scope, with remediation time
- [ ] Adoption documentation and runnable integration examples

### Evidence required before submission

- [ ] Verified stable and prerelease package versions, tags, and publication dates
- [ ] CI runs and relevant test results
- [ ] Reproducible usage examples and known limitations
- [ ] Evidence of external evaluation or downstream use, where available
- [ ] Work breakdown, hours or cost basis, milestone dates, and acceptance criteria
- [ ] Legal recipient, payment route, and grant-program eligibility confirmed

### Draft outcome statement

We propose to deliver [specific outputs] by [date]. Completion will be demonstrated by [test commands / CI runs / published documentation / review report]. We will report known limitations and unresolved risks, and will not treat application submission as an awarded grant.

## 4. Short public contributor invitation

AxiomGuard is an open-source security toolkit for Node.js and TypeScript services. We're looking for practical feedback, reproducible bug reports, integration tests, and documentation improvements.

Start with the repository and contributing guide:
- https://github.com/AxiomNode-lab/AxiomGuard
- https://github.com/AxiomNode-lab/AxiomGuard/blob/main/CONTRIBUTING.md

Please include your runtime/framework versions and exact reproduction steps when reporting an issue. Security vulnerabilities should follow the repository's security reporting policy rather than be disclosed in a public issue.

## Follow-up discipline

- Personalize the first sentence for every recipient.
- Record date, recipient, relevance, request, reply, and agreed next step in a private tracker.
- Send at most one polite follow-up after a reasonable interval; respect a decline or no-contact request.
- Keep private correspondence, personal details, budgets, and unpublished vulnerability information out of public reports.
