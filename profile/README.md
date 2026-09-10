<div align="center">

<img src="https://raw.githubusercontent.com/AxiomNode-lab/.github/de1060baabcc1177aa83d698f165efbcba21479f/profile/assets/axiomnode-banner.png" alt="AxiomNode" width="100%" />

<br />

# AxiomNode

### Software engineering, security, and developer infrastructure.

<p>
  <a href="https://github.com/AxiomNode-lab"><img src="https://img.shields.io/badge/GitHub-AxiomNode-181717?logo=github" alt="GitHub" /></a>
  <a href="https://github.com/AxiomNode-lab/AxiomGuard"><img src="https://img.shields.io/badge/Featured-AxiomGuard-2f81f7?logo=github" alt="AxiomGuard" /></a>
  <a href="https://github.com/AxiomNode-lab/DevDoctor"><img src="https://img.shields.io/badge/Featured-DevDoctor-0969da" alt="DevDoctor" /></a>
  <img src="https://img.shields.io/badge/Open%20Source-Built%20in%20Public-2ea44f" alt="Open Source" />
</p>

**We build focused software for real operational problems — with an emphasis on security, reliability, clarity, and maintainability.**

</div>

---

## What AxiomNode builds

AxiomNode is a software engineering studio focused on turning practical problems into well-engineered tools, infrastructure, and products.

Our work spans the full engineering lifecycle: problem definition, architecture, implementation, testing, documentation, release, and continuous improvement.

| Area | Focus |
| --- | --- |
| **Security Engineering** | Defensive controls, security primitives, validation, privacy-aware tooling, and auditable behavior. |
| **Developer Tooling** | CLI applications, automation, diagnostics, reusable packages, and workflows that remove engineering friction. |
| **Infrastructure & Automation** | Reliable developer infrastructure, operational tooling, integrations, and repeatable workflows. |
| **Product Engineering** | Turning strong technical foundations into software that is usable, testable, and maintainable. |

## Selected work

### 🛡️ [AxiomGuard](https://github.com/AxiomNode-lab/AxiomGuard)

**Security building blocks for modern Node.js and TypeScript services.**

AxiomGuard provides focused primitives for API keys, signed webhooks and replay protection, browser request policy, idempotency, SSRF-aware outbound requests, rate limiting, secure cookies, CSRF, CORS, defensive headers, environment validation, secret-safe logging, and repository secret scanning. It is framework-neutral at the core and includes adapters for Express, Fastify, Hono, and Redis-backed deployments.

```bash
npm install @axiomnode-lab/guard
```

> **Design principle:** security controls should be explicit, testable, and clear about their boundaries.

### 🩺 [DevDoctor](https://github.com/AxiomNode-lab/DevDoctor)

**Diagnose Linux developer workstations before changing them.**

DevDoctor inspects installed tooling, identifies missing or broken development dependencies, explains PATH and package-manager conflicts, compares project requirements with the local toolchain, and produces preview-first repair or installation plans. Its diagnostic workflows are designed to be read-only by default and avoid guessing when system ownership or policy is ambiguous.

```bash
python -m pip install "git+https://github.com/AxiomNode-lab/DevDoctor.git"
devdoctor check --profile devops
```

---

## Engineering approach

```text
Understand the problem
        ↓
Define a clear scope
        ↓
Design the simplest sound solution
        ↓
Implement with explicit boundaries
        ↓
Test normal and failure paths
        ↓
Document behavior and limitations
        ↓
Ship, observe, improve
```

We optimize for software that can be understood, tested, operated, and improved by someone other than its original author.

### Principles

- **Clarity over complexity** — interfaces and behavior should be easy to understand.
- **Evidence over claims** — tests, documentation, and measurable behavior support technical decisions.
- **Safe changes by default** — destructive or mutating actions should be explicit and reviewable.
- **Focused dependencies** — minimize unnecessary supply-chain and maintenance surface where practical.
- **Operational quality matters** — logging, diagnostics, release processes, and failure handling are part of the product.
- **Documentation ships with the code** — good engineering includes explaining how and why something works.

---

## Open source

We publish selected work when it is ready to be useful outside the team. Public repositories are developed with readable documentation, reproducible workflows, issue tracking, code review, and clear security boundaries.

Contributions can take many forms: fixing a bug, improving a test, tightening documentation, improving developer experience, or proposing a focused change backed by a real use case.

<p align="center">
  <a href="https://github.com/orgs/AxiomNode-lab/repositories"><strong>Explore repositories</strong></a>
  ·
  <a href="https://github.com/orgs/AxiomNode-lab/people"><strong>Meet the team</strong></a>
  ·
  <a href="https://github.com/AxiomNode-lab/AxiomGuard"><strong>Explore AxiomGuard</strong></a>
</p>

---

<details>
<summary><strong>🇹🇷 Türkçe</strong></summary>

<br />

**AxiomNode**, güvenlik, yazılım mühendisliği ve geliştirici altyapısı alanlarında pratik problemleri çözen araçlar ve yazılımlar geliştiren bir mühendislik stüdyosudur.

Çalışmalarımız; problem tanımı ve mimariden geliştirme, test, dokümantasyon, yayınlama ve sürekli iyileştirmeye kadar tüm mühendislik sürecini kapsar.

Önceliklerimiz; güvenlik mühendisliği, geliştirici araçları, otomasyon, altyapı, güvenilirlik ve sürdürülebilir ürün geliştirmedir.

**Açık, test edilebilir, bakımı yapılabilir ve sınırları net yazılım geliştirmeyi hedefliyoruz.**

</details>

<details>
<summary><strong>🇸🇾 العربية</strong></summary>

<br />

**AxiomNode** استوديو هندسة برمجيات يركّز على بناء أدوات ومنتجات وحلول بنية تحتية للمشكلات التقنية العملية، مع اهتمام خاص بالأمان والموثوقية وقابلية الصيانة.

نغطي دورة العمل كاملة من تعريف المشكلة وتصميم المعمارية، إلى التطوير والاختبار والتوثيق والإصدار والتحسين المستمر.

تشمل مجالاتنا هندسة الأمن، أدوات المطورين، الأتمتة والبنية التحتية، وتطوير المنتجات البرمجية.

**نؤمن بالوضوح، والاختبار، والحدود التقنية الصريحة، وبناء البرمجيات التي يمكن تشغيلها وصيانتها بثقة.**

</details>

---

<div align="center">

### Build with purpose · Engineer with evidence · Ship with confidence

<sub>© AxiomNode · Software engineering, security, and open source.</sub>

</div>
