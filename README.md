<div align="center">

# Hello, friend... Wait, that's informal. Hello! 👋

[![Capsule Render Header](https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=0,4,12,25,30&height=180&section=header&text=Stephen%20Cork%20//%20Systems%20&%20Security&fontSize=28&fontColor=ffffff&animation=fadeIn)](https://github.com/slopgobblercobbler)

[![Employer](https://img.shields.io/badge/Employer-Allsafe%20Cybersecurity-007acc?style=flat-square&logo=cisco)](https://github.com/slopgobblercobbler)
[![Degree](https://img.shields.io/badge/Degree-B.Sc.%20Systems%20%26%20Cryptography%20@%20TUM-critical?style=flat-square&logo=academia)](https://github.com/slopgobblercobbler)
[![OS](https://img.shields.io/badge/OS-Arch%20Linux%20%2F%2F%20FreeBSD%2011.4-blueviolet?style=flat-square&logo=archlinux)](https://github.com/slopgobblercobbler)
[![Achievements](https://img.shields.io/badge/Achievements-Pull%20Shark%20(x2)%20%E2%80%A2%20Quickdraw%20%E2%80%A2%20YOLO-7952b3?style=flat-square&logo=github)](https://github.com/slopgobblercobbler?tab=achievements)
[![AnyPS5](https://img.shields.io/badge/Contributed-AnyPS5%20Core%20Squad-00c853?style=flat-square&logo=playstation)](https://github.com/boykopovar/AnyPS5)
[![Tor](https://img.shields.io/badge/Tor%20Daemon-Active-success?style=flat-square&logo=torproject)](https://github.com/slopgobblercobbler)

</div>

---

### 💻 System Telemetry & Background

```bash
$ neofetch --user slopgobblercobbler --location Munich
```
- **Name:** Stephen Cork
- **Age:** 22
- **Base:** Munich, Germany
- **Education:** B.Sc. in Computer Science & Applied Cryptography at **Technical University of Munich (TUM)**, with an exchange semester at **NYU Courant Institute**. Focused on low-level memory forensics, operating system kernels, and side-channel timing attacks.
- **Experience:** Formerly Junior Security Analyst at **Allsafe Cybersecurity** (monitoring enterprise firewall telemetry, incident response, and root daemons), now independent systems engineer, kernel contributor, and low-level tinkerer.
- **Audio Track:** Mac Quayle synth pulses, dark ambient tape loops, and buffered coffee drips.

---

### 🛡️ Core Stack & Low-Level Tooling

| Category | Technologies / Frameworks / Stacks |
| :--- | :--- |
| **Systems & Low-Level** | C++20, FreeBSD POSIX Kernels, x86-64 Assembly, AnyPS5 Static Relinking, Memory Forensics |
| **Security & Auditing** | TLS Handshake Analysis, Shannon Entropy Scanners, AST Linter Engines, JWT Auditing, GPG Keyrings |
| **Developer Tooling** | Python, TypeScript, Rust, Go, Custom CLI Guards, ReDoS Profilers & Linters |
| **DevOps & Infrastructure** | Docker, Kubernetes, Nginx, FreeBSD Jails, GitHub Actions Hardening, Tape Archives |

---

### 🛠️ Open-Source & Custom CLI Utilities

I engineer strict, zero-dependency developer guardrails, schema checkers, and CLI tools to enforce sanity in CI pipelines and production runtimes:

#### 🔒 Security, Linter & CI Guards
- [`secret-leak-guard`](https://github.com/slopgobblercobbler/secret-leak-guard) — High-performance CLI regex & Shannon entropy scanner for accidental tokens/secrets in git diffs.
- [`commit-msg-guard`](https://github.com/slopgobblercobbler/commit-msg-guard) — Production-grade Conventional Commits validator and git hook CLI utility.
- [`commit-scope-lint`](https://github.com/slopgobblercobbler/commit-scope-lint) — Conventional commit scope enforcement, uppercase policy validator, and multi-scope parser.
- [`docker-compose-validator`](https://github.com/slopgobblercobbler/docker-compose-validator) — Linter, security auditor, and best-practices analyzer for Docker Compose setups.
- [`dockerfile-guard`](https://github.com/slopgobblercobbler/dockerfile-guard) — Static Dockerfile linter, layer optimization analyzer, and build security scanner.
- [`dockerfile-sec-guard`](https://github.com/slopgobblercobbler/dockerfile-sec-guard) — Container image security scanner and unprivileged user verification tool.
- [`gha-workflow-auditor`](https://github.com/slopgobblercobbler/gha-workflow-auditor) — Fast CLI linter and security scanner for GitHub Actions workflows.
- [`jwt-audit-sentinel`](https://github.com/slopgobblercobbler/jwt-audit-sentinel) — JWT security analyzer detecting insecure signing algorithms (`none`/weak HMAC), missing claims, and key confusion.
- [`regex-bench-cli`](https://github.com/slopgobblercobbler/regex-bench-cli) — Terminal CLI utility to evaluate catastrophic backtracking risks and ReDoS vulnerabilities.
- [`dep-license-sentinel`](https://github.com/slopgobblercobbler/dep-license-sentinel) — Dependency license compliance auditor, SPDX validator, and restrictive license blocker.
- [`spdx-license-detector`](https://github.com/slopgobblercobbler/spdx-license-detector) — High-speed SPDX license identifier, expression parser, and compatibility checker.
- [`license-header-sentinel`](https://github.com/slopgobblercobbler/license-header-sentinel) — Multi-language CLI tool to verify, insert, and update open-source license headers across codebases.

#### 📐 Schemas, API Contracts & Data Engines
- [`openapi-spec-linter`](https://github.com/slopgobblercobbler/openapi-spec-linter) — OpenAPI 3.0/3.1 contract and schema validator with polymorphic discriminator support.
- [`api-contract-diff`](https://github.com/slopgobblercobbler/api-contract-diff) — OpenAPI & GraphQL schema breaking change detector and semantic contract differ.
- [`json-schema-diff`](https://github.com/slopgobblercobbler/json-schema-diff) — Production-grade CLI & library to detect breaking changes between JSON schemas.
- [`json-schema-doctor`](https://github.com/slopgobblercobbler/json-schema-doctor) — Schema drift detector, JSON/YAML formatter, and automatic schema synthesizer.
- [`schema-faker-cli`](https://github.com/slopgobblercobbler/schema-faker-cli) — Realistic deterministic mock data generator from JSON schemas and API specs.
- [`csv-to-sqlite-loader`](https://github.com/slopgobblercobbler/csv-to-sqlite-loader) — Ultra-fast standalone CLI tool to load CSV files into SQLite tables with automatic type inference and indexing.
- [`sql-migration-linter`](https://github.com/slopgobblercobbler/sql-migration-linter) — Production-grade SQL migration linter detecting unsafe schema mutations and lock hazards.

#### 🌐 Network, Runtime & Diagnostics
- [`tls-cipher-scanner`](https://github.com/slopgobblercobbler/tls-cipher-scanner) — High-assurance TLS cipher suite scanner, handshake inspector, and deprecated protocol detector.
- [`env-var-doctor`](https://github.com/slopgobblercobbler/env-var-doctor) — Runtime environment variable health inspector and configuration schema auditor.
- [`env-drift-sentinel`](https://github.com/slopgobblercobbler/env-drift-sentinel) — Continuous configuration drift detection and environment synchronization daemon.
- [`env-guard-cli`](https://github.com/slopgobblercobbler/env-guard-cli) — Developer CLI to validate `.env` files against schema definitions and audit secret leakage.
- [`webhook-replay-box`](https://github.com/slopgobblercobbler/webhook-replay-box) — Local CLI utility to receive, inspect, record, and replay HTTP webhooks with signature verification.
- [`mock-endpoint-runner`](https://github.com/slopgobblercobbler/mock-endpoint-runner) — Lightweight zero-dependency HTTP API mock server and fixture generator for frontend and integration testing.
- [`cron-doctor`](https://github.com/slopgobblercobbler/cron-doctor) — Production cron expression parser, schedule collision detector, and human-readable explainer.

#### 🧹 Code Quality, Static Analysis & Git Automation
- [`markdown-deadlink-checker`](https://github.com/slopgobblercobbler/markdown-deadlink-checker) — Production-grade zero-dependency dead link, broken relative path, and anchor validator for CI/CD.
- [`doclink-sentinel`](https://github.com/slopgobblercobbler/doclink-sentinel) — Fast recursive Markdown and HTML hyperlink integrity checker and dead-link repair assistant.
- [`deadcode-sweep`](https://github.com/slopgobblercobbler/deadcode-sweep) — Fast static analyzer for Python and JavaScript codebases to detect unused functions and orphaned imports.
- [`ast-refactor-cli`](https://github.com/slopgobblercobbler/ast-refactor-cli) — AST-driven automated code refactoring and syntax pattern transformation engine.
- [`semver-release-planner`](https://github.com/slopgobblercobbler/semver-release-planner) — Semantic versioning release calculator and changelog sequencer based on conventional commits.
- [`git-changelog-craft`](https://github.com/slopgobblercobbler/git-changelog-craft) — Fast CLI analyzing conventional commits, tags, and PR refs to generate release notes.
- [`repo-hygiene-cli`](https://github.com/slopgobblercobbler/repo-hygiene-cli) — GitHub repository health auditor for README, LICENSE, CI actions, and branch hygiene.
- [`ts-alias-resolver`](https://github.com/slopgobblercobbler/ts-alias-resolver) — High-performance TypeScript path alias resolver and `tsconfig` compiler options auditor.
- [`glob-sentinel-cli`](https://github.com/slopgobblercobbler/glob-sentinel-cli) — Fast file glob pattern validator and traversal path security auditor.
- [`slopgobblercobbler`](https://github.com/slopgobblercobbler/slopgobblercobbler) — Special GitHub developer profile showcase, real-time telemetry dashboard & workflow portfolio.

---

### 🚀 Key Upstream Open-Source Contributions

- [`boykopovar/AnyPS5`](https://github.com/boykopovar/AnyPS5) — High-assurance C++20 contributions to PS5 executable relinking, bounds validation, and FreeBSD 11.4 POSIX compliance for `libkernel` / `libkernel_sys`.
  - **Active Work:** [PR #8742 (`feat(libkernel): implement setpgid and setpgrp`)](https://github.com/boykopovar/AnyPS5/pull/8742) — Implementing FreeBSD 11.4 process group syscall parity (`sys_setpgid` / `sys_setpgrp`), actively refining session leader (`SESS_LEADER`) `EPERM` check ordering and zero inline comment policy per reviewer specifications.
- [`martinkozle/excaliagent`](https://github.com/martinkozle/excaliagent) — Spatial Excalidraw board bundle optimization, CDN font delivery, and package lightweighting.
- [`lingdojo/kana-dojo`](https://github.com/lingdojo/kana-dojo) — Minimalist Japanese learning platform dataset expansions and localized proverb additions.

---

### 🧭 Companion Open-Source Developer Tools & Ecosystem

In building and maintaining rigorous CI/CD linters and security utilities, I actively test, star, and integrate with premier companion open-source developer tooling across the ecosystem:

| Ecosystem Category | Key Companion Tools | Integration & Cross-Reference |
| :--- | :--- | :--- |
| **Linting & Code Hardening** | [`astral-sh/ruff`](https://github.com/astral-sh/ruff) • [`astral-sh/uv`](https://github.com/astral-sh/uv) • [`hadolint/hadolint`](https://github.com/hadolint/hadolint) • [`sqlfluff/sqlfluff`](https://github.com/sqlfluff/sqlfluff) • [`rhysd/actionlint`](https://github.com/rhysd/actionlint) • [`koalaman/shellcheck`](https://github.com/koalaman/shellcheck) | Complements [`dockerfile-guard`](https://github.com/slopgobblercobbler/dockerfile-guard), [`sql-migration-linter`](https://github.com/slopgobblercobbler/sql-migration-linter), and [`gha-workflow-auditor`](https://github.com/slopgobblercobbler/gha-workflow-auditor). |
| **Security & Secret Scanning** | [`gitleaks/gitleaks`](https://github.com/gitleaks/gitleaks) • [`trufflesecurity/trufflehog`](https://github.com/trufflesecurity/trufflehog) • [`aquasecurity/trivy`](https://github.com/aquasecurity/trivy) • [`bridgecrewio/checkov`](https://github.com/bridgecrewio/checkov) • [`sigstore/cosign`](https://github.com/sigstore/cosign) | Upstream inspiration and interoperability pairing for [`secret-leak-guard`](https://github.com/slopgobblercobbler/secret-leak-guard) and [`dockerfile-sec-guard`](https://github.com/slopgobblercobbler/dockerfile-sec-guard). |
| **Git Hooks & Release Lifecycle** | [`pre-commit/pre-commit`](https://github.com/pre-commit/pre-commit) • [`conventional-changelog/commitlint`](https://github.com/conventional-changelog/commitlint) • [`orhun/git-cliff`](https://github.com/orhun/git-cliff) • [`pre-commit/pre-commit-hooks`](https://github.com/pre-commit/pre-commit-hooks) | Natively supported target hooks for [`commit-msg-guard`](https://github.com/slopgobblercobbler/commit-msg-guard), [`commit-scope-lint`](https://github.com/slopgobblercobbler/commit-scope-lint), and [`semver-release-planner`](https://github.com/slopgobblercobbler/semver-release-planner). |
| **API Contracts & Hyperlinks** | [`stoplightio/spectral`](https://github.com/stoplightio/spectral) • [`python-jsonschema/jsonschema`](https://github.com/python-jsonschema/jsonschema) • [`lycheeverse/lychee`](https://github.com/lycheeverse/lychee) | Companion validation pairs for [`openapi-spec-linter`](https://github.com/slopgobblercobbler/openapi-spec-linter), [`json-schema-diff`](https://github.com/slopgobblercobbler/json-schema-diff), and [`markdown-deadlink-checker`](https://github.com/slopgobblercobbler/markdown-deadlink-checker). |
| **Productivity & Shell CLI** | [`sharkdp/ripgrep`](https://github.com/BurntSushi/ripgrep) • [`sharkdp/fd`](https://github.com/sharkdp/fd) • [`junegunn/fzf`](https://github.com/junegunn/fzf) • [`casey/just`](https://github.com/casey/just) • [`jqlang/jq`](https://github.com/jqlang/jq) • [`mikefarah/yq`](https://github.com/mikefarah/yq) | Standard developer toolchain powering our local profiling, test suites, and high-throughput CLI filters. |

---

### 🏆 Unlocked GitHub Achievements

<div align="center">

<a href="https://github.com/slopgobblercobbler?tab=achievements">
  <img src="https://github.githubassets.com/assets/pull-shark-bronze-a37accb528d1.png" width="75" alt="Achievement: Pull Shark Bronze x2" title="Pull Shark (Bronze x2) — Merged pull requests" />
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/slopgobblercobbler?tab=achievements">
  <img src="https://github.githubassets.com/assets/quickdraw-default-39c6aec8ff89.png" width="75" alt="Achievement: Quickdraw" title="Quickdraw — Closed an issue or PR within 5 minutes" />
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/slopgobblercobbler?tab=achievements">
  <img src="https://github.githubassets.com/assets/yolo-default-be0bbff04951.png" width="75" alt="Achievement: YOLO" title="YOLO — Merged PR without review" />
</a>

<br/>
<sub><b>Pull Shark (Bronze x2)</b> &nbsp;•&nbsp; <b>Quickdraw</b> &nbsp;•&nbsp; <b>YOLO</b></sub>

</div>

---

### 📊 GitHub Telemetry & Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=slopgobblercobbler&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=slopgobblercobbler&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=slopgobblercobbler&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="70%" />

</div>

---

### ☕ Mr. Robot Lore & Easter Eggs

> *"I never want to be lonely again... I want to be connected to the world. But how do you connect to a world that's broken?"*

- **Caffeine Protocol:** Alternating between 1 cup of chamomile tea for mindfulness and 5 espresso shots for overnight kernel debugging.
- **FSociety Status:** Active node monitoring P99 latency anomalies and unencrypted DAT tape backups.
- **GPG Fingerprint:** `4E29 B91A C832 7701 8181` (Verify before sending sensitive payloads).

<div align="center">
  <img src="https://media.giphy.com/media/ule4akeXnY9Mb2kfTM/giphy.gif" width="220" alt="Hacker typing" />
  <br/>
  <sub><b>Current Typing Speed: 105 WPM // Zero Trust Architecture</b></sub>
</div>
