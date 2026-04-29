
<p align="center">
  <img src="bigLogo.png" alt="Senserva" width="600"/>
</p>

# Siemserva

**The biggest risks are the ones you don't know about.** Siemserva works continuously to find them, plus many other issues, helps you fix them, and gives auditors what they need on the first pass.

Senserva's Security Context Graph, Analysis and Recommendations, combined with Senserva's Trustworthy AI, provide continuous security assurance and remediation for Microsoft 365, Intune, and Entra ID.

## Questions and Support

Please use **[Issues](../../issues)** for bug reports and feature requests, and **[Discussions](../../discussions)** for questions, ideas, and Q&A. Keeping the conversation in the open lets everyone share ideas and answers, and helps the next person who runs into the same thing.

## A note from the Senserva Team

**Built with care. Used with confidence.**

*We had a blast building Siemserva, and we hope you have just as much fun putting it to work. Go find the risks no one else can.*

*Happy hunting,*
*The Senserva Team*

## Why Siemserva

- **600+ hourly checks and log reviews** tied to compliance standards. Easily integrates with the tools you already run.
- **Senserva Trustworthy AI** turns raw findings into rich reports and time-saving remediation.
- **Built for Claude.** MCP server for Claude Desktop and Claude Code, or call Claude (or any AI) from inside Siemserva.
- **Industrial strength.** Continuous, scalable, audit-ready.

## Pricing

**Siemserva is free up to 100 users.** Beyond that, $99/month covers unlimited users in your tenant.

| Tier | Users | Price |
|------|-------|-------|
| Free | Up to 100 | $0 |
| Standard | Unlimited | $99/month |
| MVP / MISA | Unlimited | Free |
| 501(c)(3) Non-Profit | Unlimited | Free |

> Microsoft MVPs, Microsoft Intelligent Security Association (MISA) members, and registered 501(c)(3) non-profits get Siemserva free at every tier. If you qualify, email [info@senserva.com](mailto:info@senserva.com) with your MVP profile, MISA membership, or IRS determination letter to activate.
> 
## Try It Out

Running it is the best way to learn. Grab the latest release and download the zip for your platform.

### Run

```bash
# macOS
./siemserva-osx-arm64 --accept-eula --tenantids <your-tenant-id>

# Windows
siemserva-win-x64.exe --accept-eula --tenantids <your-tenant-id>
```

On macOS, make the binary executable first:

```bash
chmod +x siemserva-*
```

…or use the included `run-siemserva.sh` helper.

### Getting Help

| Command | What it does |
|---|---|
| *(no parameters)* | Interactive setup guide |
| `-?` | Basic parameters |
| `--full-help` | Detailed help files |

### Demo Mode

> [!TIP]
> **Not ready to scan a real tenant?** Run `siemserva-osx-arm64` or `siemserva-win-x64` with no parameters to launch demo mode — a realistic database with **1000+ users** baked in.

Demo mode works with both **Claude (as an MCP)** and **Siemserva** directly. See `SiemservaEvaluationGuide.pdf` for a walkthrough of the demo data.

It's also great for training. If you can, run it with **Claude Desktop** — it's the best way to explore the data Siemserva produces.

> [!NOTE]
> **Please Star and Follow Us** The team loves it and appreciates you for doing it!
> 
> [![GitHub stars](https://img.shields.io/github/stars/Senserva/Siemserva-Releases?style=social)](https://github.com/Senserva/Siemserva-Releases/stargazers) [![GitHub watchers](https://img.shields.io/github/watchers/Senserva/Siemserva-Releases?style=social)](https://github.com/Senserva/Siemserva-Releases/watchers)

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

---

## What Is Siemserva?

Your Microsoft Entra ID tenant has hundreds of security settings. Conditional Access policies, privileged roles, app registrations, device compliance, email security, MFA enforcement — each one a potential gap an attacker can exploit.

Siemserva audits **all of them** in a single scan. No agents to deploy. No complex setup. Just run it and see what needs fixing.

---

## Key Features

**600+ Security Checks across 15+ domains** — Identity & MFA, Conditional Access (What-If API, 14-day sign-in replay, 30-point coverage matrix), Privileged Access & PIM, Application Security, Endpoint & Intune (120+ policy settings vs. baselines), Email Security, M365 Workloads (SharePoint, Teams, OneDrive, Exchange), Azure Subscriptions, Logging & Detection, AI & Agent Security (Copilot Agent identity discovery), and more. All mapped to 31 MCSB controls and 81 SCuBA codes.

**Live Interactive Dashboard** — full-screen terminal dashboard where findings stream in real time as the scan runs. Severity-coded, searchable, with drill-down details and compliance context on every finding. Delta view shows net-new issues since your last scan.

**SIEM Mode** — continuous monitoring with scheduled scan cycles, multi-tenant support, and automated email alerts for new Critical and High findings.

**Agentic AI-Powered Analysis** — context-aware insights, remediation recommendations, and production-ready PowerShell script generation (press P on any finding). Full Scan Analysis for executive and technical summaries, Context-Sensitive Q&A in natural language, and Security Insights on any tab. Direct streaming via the Anthropic Claude API, or copy-paste friendly for any AI tool. Grounded in 170+ engineer-authored remediation guides.

**Compliance Mapping** — every finding maps to Microsoft Cloud Security Benchmark (MCSB v2, 31 controls) and CISA SCuBA (81 control codes across 7 product families) with evidence links, justifications, and timestamped assessment-ready evidence. Real pass/fail status per control.

**Six AI-Enhanced HTML Report Types** — Detailed, Compliance, Business Focused Review, Remediation, Audit, and Portfolio. Self-contained HTML with embedded charts, risk heatmaps, and compliance scorecards. One keystroke (Ctrl+R), no dependencies — opens in any browser, prints to PDF.

**Scan, Pipe, Automate** — split into two composable halves: --scan outputs NDJSON, --reporter consumes any NDJSON source. Full headless pipeline, multi-source dashboard merging, and Maester connector included. Query the SQLite graph database (79 edge types, 341 tables) in C#, Python, or PowerShell.

**No Agents Required** — read-only access via Microsoft Graph API. Nothing to install on your tenant. All data stays local — no security data transmitted to Senserva or any third party.

**Multi-Tenant Support** — scan and monitor multiple Entra ID tenants in a single operation. Portfolio cross-tenant reports for MSPs and MSSPs with portfolio-level risk scoring.

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

**Product website:** [https://siemserva.senserva.com/](https://senserva.com/)
