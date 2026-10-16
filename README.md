# Awesome-Supply-Chain-Security

## Top Supply Chain Security Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Software Composition Analysis, SBOM Governance & Malicious Package Detection*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Supply Chain Security**. These tools help organizations secure their software development lifecycle — scanning dependencies for vulnerabilities, detecting malicious packages before ingestion, generating compliant SBOMs, and providing audit-ready evidence for frameworks like NIST SSDF, SLSA, and the EU Cyber Resilience Act.



**Examples** include Snyk, Checkmarx, Sonatype Nexus, JFrog Xray, Aqua Security, Mend.io, Veracode, Legit Security, Apiiro, and Black Duck (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, read-only endpoint scanning, and transparent supply chain verification — ideal for security teams prioritizing data sovereignty, developers auditing their local development environments, and organizations that need verifiable evidence without relying solely on commercial SaaS platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Snyk](https://snyk.io/)**  

  **The broad developer-first platform covering SCA, container, IaC, and code scanning.** Large vulnerability database with strong IDE and pull-request integration makes it a common default and easy to adopt . Gartner recognizes Snyk in the Software Supply Chain Security market . **Watch-outs**: Cost at scale and alert volume are recurring critiques; SBOM and build-provenance features are less central than its scanning capabilities .



- **[Checkmarx](https://checkmarx.com/)**  

  **Consolidated enterprise AppSec platform with expanded supply chain capabilities.** Checkmarx One includes Software Composition Analysis, **Malicious Package Protection**, **Secrets Detection** identifying 170+ secret types, **Repository Health** scoring across a dozen factors (code quality, dependency management, CI/CD best practices), AI Security, and Container Security . Named a Leader in the **2026 Gartner Magic Quadrant for Software Supply Chain Security** . **GCC-scale deployment** with centralized governance, IDE-native feedback (VS Code, JetBrains, Cursor, Windsurf), and SBOM/AIBOM generation ready for enterprise compliance .



- **[Sonatype Nexus One](https://www.sonatype.com/)**  

  **AI-native DevSecOps platform and system of record for software artifacts**, launched November 2025 . Built on 15+ years of curated OSS intelligence from Maven Central and OSS Index, with ML-driven analysis of **270 million open source components**. Claims **70% more open source vulnerabilities** detected than alternative sources, **10x faster insights** than the National Vulnerability Database, and **30% faster mean time to remediate**. Features **AI Visibility and Governance** for AI/ML models, **Malware Defense** with continuous behavioral analysis, **Dependency Management** automation, **SBOM Governance**, and secure artifact management. Trusted by 70% of the Fortune 100 . Nexus Repository has a **free Community Edition** for small teams; Pro adds HA and SSO; Pro+ adds automated malware quarantine, license policy enforcement, and **AI Agent and MCP Dependency Control** .



- **[JFrog Xray](https://jfrog.com/xray/)**  

  **Intelligent automated security and compliance for software supply chains** integrated with JFrog Artifactory . Features **enhanced Software Composition Analysis**, contextual CVE prioritization, secrets detection, IaC security, and unified artifact security management with hybrid cloud support . **JFrog Connect integration** automatically scans edge device update content for vulnerabilities, displaying CVE severities in update flows and runs with drill-down to specific vulnerabilities. CVEs refresh every 24 hours for 30 days after flow creation and 90 days after deployment .



- **[Aqua Security](https://www.aquasec.com/)**  

  **Leader and Forward Mover in the GigaOm Radar for Software Supply Chain Security** (Maturity/Platform Play quadrant) . Excels at **container image security scanning** via **Aqua Trivy**, the world's most comprehensive vulnerability scanner, plus automated security testing, supply chain mapping, and visualization . **Enterprise-grade detection** for compromised NPM packages via custom vulnerability identifiers (`AQUA-NPM-MALWARE`, `AQUA-MCP-*`) and integration with the **OpenSSF Malicious Packages Database** (`MAL-YYYY-XXXXX`). Provides both detection and **blocking** capabilities via Assurance Policies .



- **[Mend.io](https://www.mend.io/)**  

  **Unified governance for the software you write and the AI you build.** One of the first platforms to pioneer **Software Composition Analysis** at enterprise scale, now expanded to SCA, SAST, secrets detection, and reachability analysis . **AI-focused capabilities**: Continuous AI behavioral testing with **1,000+ concurrent tests** per build, runtime in-application protection with **80% reduction in MTTR**, and a single evidence layer that reduced an open source audit from a week to **15 minutes** . Features SBOM/AI-BOM generation and shadow dependency detection. Independent from model providers .



- **[Veracode](https://www.veracode.com/)**  

  **Leader and Fast Mover in the GigaOm Radar for Software Supply Chain Security** (Maturity/Platform Play quadrant) . Headline innovation is **Package Firewall** — a preventive control that blocks malicious and risky packages **before they enter the development environment**, integrating with Azure Artifacts, NPM, PyPI, Maven, Nexus, and Artifactory . While traditional SCA identifies vulnerabilities in packages already in use, Package Firewall stops threats at ingestion. Platform includes SAST, DAST, SCA, Container Security, **Veracode Fix** (AI-generated code fixes), Malicious Package Detection, and penetration testing. Added **OAuth-based SSO** across IDE plugins in 2025 .



- **[Legit Security](https://www.legitsecurity.com/)**  

  **Agentic AppSec platform purpose-built to secure AI-powered development.** Features **VibeGuard** for securing AI-generated code, coding agents (Claude, Cursor), and workflows at creation time — before reaching production . **AI-powered prioritization** with contextual risk scoring across dozens of factors, AI-based secrets scanning, and AI-generated remediation guidance embedded in pull requests . Partnership with Sweet Security delivers **end-to-end security from IDE to cloud runtime**, correlating code findings with runtime exposure to prioritize truly exploitable risk .



- **[Apiiro](https://apiiro.com/)**  

  **Named a Leader in the 2026 Gartner Magic Quadrant for Software Supply Chain Security** . Introduced the **SDLC System of Record (SoR)** — a single source of truth across pull requests, branches, pipelines, build jobs, and artifacts, consolidating evidence, control adherence, violations, and audit-ready reporting . **Cross-framework compliance mapping** out-of-the-box to ISO 27001, SOC2, NIST 800-53, NIST SSDF, CIS v8, and SLSA Levels 1-3. Eliminates spreadsheets and manual evidence gathering for compliance audits.



- **[Black Duck](https://www.blackduck.com/)**  

  **Comprehensive software supply chain security solutions** for identifying and managing risks throughout the application lifecycle . Detects, tracks, and manages open source dependencies in source code, files, containers, and artifacts. Generates **SPDX and CycloneDX SBOMs** containing open source, proprietary, and commercial dependencies with customizable fields for industry, regulatory, or customer requirements. Helps prepare for **SSDF self-attestation** and aligns with NTIA and FDA SBOM requirements .



## Open-Source GitHub Projects



- **[Bumblebee](https://github.com/perplexityai/bumblebee)**  

  **Read-only supply chain scanner for developer endpoints** by Perplexity AI. Single static binary, Go 1.25+, zero non-stdlib dependencies. Answers a focused question: **when an advisory names a package or version, do any matches exist on this machine right now?** Features three scan profiles — `baseline` (global package roots), `project` (specific dev folders), and `deep` (explicit `--root` paths including `$HOME` for incident response) . **Reads only lockfiles, package-manager install metadata, extension manifests, and MCP JSON configs** — no package manager execution, no source-file reads. **MCP host configs parsed but credentials/env values never emitted** . **Coverage**: npm/pnpm/Yarn/Bun, PyPI, Go modules, RubyGems, Composer, **MCP configs** (Claude Desktop, Cursor, Gemini CLI, Claude Code), **agent skills** (skills.sh lock files), **editor extensions** (VS Code, Cursor, Windsurf, VSCodium), **browser extensions** (Chromium, Firefox), and Homebrew . Includes `bumblebee selftest` with embedded fake fixtures for verification. **MIT-licensed** and designed for supply-chain incident response on macOS/Linux .



- **[Trivy](https://github.com/aquasecurity/trivy)**  

  **The world's most comprehensive vulnerability scanner** for containers, filesystems, and Git repositories. Detects vulnerabilities in OS packages and language-specific dependencies (npm, pip, Go, Ruby, etc.). The foundation for Aqua Trivy in commercial platforms. Apache 2.0 licensed.



- **[OpenSSF Scorecard](https://github.com/ossf/scorecard)**  

  **Automated security health metrics for open source projects.** Scores repositories against supply chain security best practices including Branch-Protection, Code-Review, Maintained, Dangerous-Workflow, Token-Permissions, Pinned-Dependencies, Vulnerabilities, Signed-Releases, SAST, and Fuzzing. Each check returns a 0-10 score with weighted aggregate. JSON output for CI/CD gating.



- **[Syft](https://github.com/anchore/syft)**  

  **CLI tool and library for generating Software Bills of Materials (SBOMs)** from container images and filesystems. Supports SPDX, CycloneDX, and Syft JSON formats. Apache 2.0 licensed. The foundation for Grype vulnerability scanning.



- **[Grype](https://github.com/anchore/grype)**  

  **Vulnerability scanner for container images and filesystems** that pairs with Syft. Scans SBOMs or directories directly against vulnerability databases. Apache 2.0 licensed.



- **[Dependency-Track](https://github.com/DependencyTrack/dependency-track)**  

  **Intelligent Component Analysis platform** that identifies and reduces risk in the software supply chain. Consumes SBOMs and continuously monitors components for vulnerabilities. Features policy enforcement, portfolio auditing, and license compliance. Apache 2.0 licensed.



- **[cdxgen](https://github.com/CycloneDX/cdxgen)**  

  **CycloneDX SBOM generator** for multiple languages and package managers. Creates AI/ML BOMs for models, datasets, and services. Apache 2.0 licensed.



- **[Sigstore](https://github.com/sigstore)**  

  **Digital signing and verification for software artifacts.** Includes Cosign (container signing), Fulcio (certificate authority for identity-based signing), and Rekor (immutable transparency log). The foundation for SLSA provenance verification. Apache 2.0 licensed.



- **[SLSA Framework](https://github.com/slsa-framework/slsa)**  

  **Supply-chain Levels for Software Artifacts** — a security framework with increasing levels of tamper resistance. The SLSA specification provides guidelines for securing build pipelines and verifying artifact provenance.



- **[OpenVEX](https://github.com/openvex)**  

  **Vulnerability Exploitability eXchange** specification and tooling for communicating the status of vulnerabilities in software components. Complements SBOMs by providing machine-readable exploitability assessments.



- **[OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck)**  

  **Software Composition Analysis tool** that detects publicly disclosed vulnerabilities in project dependencies. Supports Java, .NET, JavaScript, Python, and Ruby. Identifies CPE identifiers for dependency correlation with NVD data. Apache 2.0 licensed.



### Additional Strong Open-Source Options



- **Ecosystem Security Specs** — Community-driven security specifications for package managers and ecosystems.

- **pip-audit** — Python dependency vulnerability scanner using the PyPI Advisory Database.

- **npm audit** — Built-in npm dependency vulnerability scanner.

- **cargo-audit** — Rust dependency vulnerability scanner using the RustSec Advisory Database.

- **govulncheck** — Go vulnerability scanner using the Go Vulnerability Database.



**Frameworks for building custom systems**: Combine **Bumblebee** for read-only local endpoint supply chain scanning including MCP and agent skill inventories, **Trivy** or **Grype** + **Syft** for container and filesystem vulnerability scanning, **Dependency-Track** for continuous SBOM-based monitoring, **Sigstore** for artifact signing and provenance verification, and **OpenSSF Scorecard** for open source project health assessment — to build a complete self-hosted supply chain security stack with verifiable evidence.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Supply chain security tools differ significantly in scan scope, deployment model, and evidence philosophy. **Bumblebee reads only metadata and never executes package managers** — it answers "is this machine exposed?" rather than "is this package vulnerable?" . **Commercial platforms like Veracode Package Firewall prevent malicious packages from entering the development environment** — a fundamentally different control point than post-ingestion SCA . **Alert volume and remediation load are real operational risks** — reachability-based platforms reduce noise by focusing on exploitable paths . **SBOM generation is table stakes for compliance** — but a complete SBOM without continuous monitoring provides limited ongoing protection .

- Self-hosted open-source solutions require proper vulnerability database updates, integration with existing CI/CD pipelines, and ongoing monitoring of scan results.



---



**Made for security engineers, DevSecOps teams, application security architects, and developers building supply chain security platforms.**  

Let's make software supply chain security more open, verifiable, and evidence-based.
