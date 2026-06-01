<p align="left">
<img src="../assets/CSAL_logo.png" width="400">
</p>

# CyberSecAuto Labs (CSAL)

**[CyberSecAuto Labs](https://cybersecauto-labs.org)** is an open-source initiative building trustworthy AI-assisted systems, security automation, and controlled developer workflows.

As AI systems and automation become increasingly integrated into engineering and security operations, CSAL explores approaches that prioritize transparency, auditability, interoperability, and operator control.

We build practical tools that help humans make better decisions through automation, structured data, and explainable assistance rather than opaque autonomy.

## Projects

### [OpenVAS MCP Server](https://github.com/CyberSecAuto-Labs/OpenVAS-MCP)

> Self-hosted MCP server providing AI agents with structured access to OpenVAS / Greenbone.
>
> - No telemetry
> - Credential isolation between clients and the scanner
> - Raw scan data returned without transformation
>
> A thin, auditable bridge. Analysis and reporting belong in the agent or in higher-level platforms.

### [netaudit](https://github.com/CyberSecAuto-Labs/netaudit)

> Network egress auditing for test execution.
>
> Define allowed outbound connections, run your tests, and get a clear pass/fail report.
>
> - Detect unintended external calls
> - Prevent data exfiltration during execution
> - Enforce network behavior policies in CI/CD
>
> Make network behavior explicit, testable, and auditable.

### [aimd](https://github.com/CyberSecAuto-Labs/aimd) (🚧 WIP)

> Manage AI context files (CLAUDE.md, AGENTS.md, .cursor/rules) as private overlays that stay out of your project repository.
>
> - Keep valuable context invisible to teammates and shared repositories
> - Sync AI workflows across machines without exposing personal or client-specific notes
> - Own your data using a standard Git remote you control
>
> For developers who depend on AI tooling but cannot commit the context that makes it effective.

### AiAVM (coming soon)

> Self-hosted vulnerability triage engine built on DefectDojo.
>
> Deterministic logic scores and prioritizes findings. A local LLM explains the decisions — it never makes them.
>
> - Know what to fix first, with an auditable reason why
> - AI-generated context grounded in real data, not hallucinations
> - Vulnerability data and inference stay on your infrastructure
>
> Security decisions remain deterministic, transparent, and reviewable.

---

## Research Focus

- Trustworthy AI-assisted systems
- Security automation and orchestration
- Deterministic decision engines
- Auditable software execution
- Local-first AI workflows
- Machine-readable security data pipelines

---

## Philosophy

Modern software increasingly relies on AI systems, automated workflows, and external services. As these systems become more capable, transparency and control become more important.

CSAL builds tools around a simple principle:

> AI may assist, but critical decisions must remain understandable, auditable, and under the operator's control.

Across our projects we favor:

- Deterministic decision making over opaque AI judgement
- Local ownership of data and infrastructure
- Explicit trust boundaries
- Auditable behavior and outputs
- Open standards and interoperability
- Composable tools that integrate into existing workflows

AI should improve operator effectiveness, not replace accountability.

---

Maintained by engineers exploring the future of trustworthy AI-assisted systems, security automation, and controlled developer workflows.
