
<p align="center">
  <img src="bigLogo.png" alt="Senserva" width="600"/>
</p>

# Siemserva

**Microsoft Entra ID Security Scanner**

One scan covers every user, device, app, role, and policy in your Entra ID tenant — with compliance mapping, AI-enhanced remediation reports, and agentic remediation script generation.

<p align="center">
  <!-- Beta Badge -->
  <a href="../../discussions">
    <img src="https://img.shields.io/badge/Status-Beta-EB7726?style=for-the-badge&logo=rocket&logoColor=white" alt="Beta"/>
  </a>
  &nbsp;
  <!-- Website -->
  <a href="https://siemserva.senserva.com/">
    <img src="https://img.shields.io/badge/Website-siemserva.senserva.com-46C2CB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Siemserva Website"/>
  </a>
  &nbsp;
  <!-- MISA Member Badge -->
  <a href="https://www.senserva.com/misa">
    <img src="https://img.shields.io/badge/Microsoft-MISA%20Member-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="MISA Member"/>
  </a>
  &nbsp;
  <!-- Microsoft Security Excellence Awards -->
  <a href="https://www.senserva.com/press">
    <img src="https://img.shields.io/badge/Microsoft%20Security-ISV%20of%20the%20Year%20Finalist%202024-7B2D8E?style=for-the-badge&logo=microsoft&logoColor=white" alt="Security ISV of the Year Finalist"/>
  </a>
  &nbsp;
  <!-- Azure Marketplace -->
  <a href="https://marketplace.microsoft.com/en-us/product/saas/senservallc.senserva-siemserva?tab=Overview">
    <img src="https://img.shields.io/badge/Azure-Marketplace-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure Marketplace"/>
  </a>
</p>

<p align="center">
  Senserva is a member of the <strong>Microsoft Intelligent Security Association (MISA)</strong> &mdash; invited by Microsoft for deep integration with Microsoft Sentinel, Entra ID, and Intune. Finalist for <strong>Security ISV of the Year</strong> at the 2024 Microsoft Security Excellence Awards.
</p>

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

**AI-Powered Analysis** — context-aware insights, remediation recommendations, and executable PowerShell script generation. Direct streaming via the Anthropic Claude API, or copy-paste friendly for any AI tool.

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
| Windows (x64) | `.exe` standalone, code-signed |

Linux and macOS releases are planned for a future version.

The Windows binary is code-signed with **Azure Trusted Signing** (publisher: **Senserva**). See the release notes for details on SmartScreen and signature verification.

Call Siemserva --help for all options. Call Siemserva --full-help to open the full HTML help guide in your browser.

You must use the --full parameter to get all the features.  And be sure to install the Claude API, it makes a big difference.

---

## Quick Start

1. Download the binary for your platform from [Releases](../../releases)
2. Register a Microsoft Entra ID app with read-only Graph API permissions ([setup guide coming soon](#))
3. Run: `siemserva --tenantids YOUR_TENANT_ID`
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

**Product website:** [https://siemserva.senserva.com/](https://siemserva.senserva.com/)
