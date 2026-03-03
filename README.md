# Siemserva

**Microsoft Entra ID Security Scanner**

One scan covers every user, device, app, role, and policy in your Entra ID tenant — with compliance mapping, AI-enhanced remediation reports, and agentic remediation script generation.

---

## Beta Testers Wanted

We are actively looking for beta testers. If you manage Microsoft Entra ID tenants and want early access to Siemserva, we want to hear from you.

**What you get:**
- Early access before the public release
- Direct line to the engineering team — your feedback shapes the product
- Full product free for 1 year when v1.0 ships

**What we're looking for:**
- Entra ID administrators, security engineers, or MSPs managing one or more tenants
- Any tenant size — from small orgs to large enterprises

**Interested?** Reach out at [support@senserva.com](mailto:support@senserva.com) or start a conversation in [Discussions](../../discussions).

---

## What Is Siemserva?

Your Microsoft Entra ID tenant has hundreds of security settings. Conditional Access policies, privileged roles, app registrations, device compliance, email security, MFA enforcement — each one a potential gap an attacker can exploit.

Siemserva audits **all of them** in a single scan. No agents to deploy. No complex setup. Just run it and see what needs fixing.

---

## Key Features

**580+ Security Checks** across 15 domains — Identity Management, Conditional Access, Privileged Access, Application Security, Endpoint Security, Email Security, M365 Workloads, and more.

**Live Interactive Dashboard** — findings stream in real time as the scan runs. Severity-coded, searchable, with drill-down details and compliance context on every finding.

**SIEM Mode** — continuous monitoring with scheduled scan cycles, multi-tenant support, and automated email alerts for new Critical and High findings.

**AI-Powered Analysis** — context-aware insights, remediation recommendations, and executable PowerShell script generation. Works with any AI provider via copy-paste, or directly via API integration.

**Compliance Mapping** — every finding maps to **Microsoft Cloud Security Benchmark (MCSB v2)** and **CISA SCuBA** controls with evidence links and justifications.

**Self-Contained HTML Reports** — four report types (Detailed, Compliance, Business Review, Remediation) with embedded charts, risk heatmaps, and compliance scorecards. No dependencies — opens in any browser, prints to PDF.

**No Agents Required** — read-only access via Microsoft Graph API. Nothing to install on your tenant.

**Multi-Tenant Support** — scan and monitor multiple Entra ID tenants in a single operation.

**Cross-Platform** — runs on Windows, Linux, and macOS.

---

## Download

Download the latest release from the [Releases](../../releases) page.

| Platform | Format |
|----------|--------|
| Windows (x64) | `.exe` standalone |
| (future) Linux (x64) | Binary — `chmod +x siemserva` then run |
| (future) macOS (x64/arm64) | Binary — `chmod +x siemserva` then run |

Windows releases are **code-signed** with Azure Trusted Signing.

Call Siemserva --help for all options.
Call Siemserva --full-help to open the full HTML help guide in your browser.

---

## Quick Start

1. Download the binary for your platform from [Releases](../../releases)
2. Register a Microsoft Entra ID app with read-only Graph API permissions ([setup guide coming soon](#))
3. Run: `siemserva --tenant-id YOUR_TENANT_ID`
4. Review findings in the live dashboard and generate reports with **Ctrl+R**

---

## System Requirements

- Windows 10+, Linux (x64), or macOS (x64/arm64)
- Microsoft Entra ID tenant with a registered app (read-only Graph API permissions)
- Internet connection for Microsoft Graph API access

---

## Feedback & Support

| Channel | Use for |
|---------|---------|
| [Report a Bug](../../issues/new) | Crashes, scan errors, report rendering issues, unexpected behavior |
| [Request a Feature](../../issues/new) | New checks, report improvements, dashboard features |
| [Discussions](../../discussions) | Questions, ideas, general conversation |
| [support@senserva.com](mailto:support@senserva.com) | Direct support from the Senserva team |

We prefer public issues and discussions so that other users can benefit from the conversation. Only use email for reports that would reveal confidential information about your organization.

**When reporting issues:** Include your Siemserva version (`siemserva --version` or the About tab) and platform. Do not share tenant IDs, user names, or other personally identifiable information.

---

## About Senserva

Siemserva is built by [Senserva](https://senserva.com), a security company focused on Microsoft Entra ID protection. We build tools that make enterprise identity security accessible, actionable, and thorough.
