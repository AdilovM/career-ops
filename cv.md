# Miras Adilov

miras9191@gmail.com | 213-245-4720 | linkedin.com/in/Miras-Adilov/

---

## Professional Summary

Senior escalations engineer with 6+ years across software engineering and enterprise product support. Final escalation point for DocLink, an enterprise document management platform with desktop, web, cloud and ERP-integration surfaces. Own Priority 1 customer cases from first report through root cause, fix and verified release. Build support tooling on Claude (Claude Code, Claude Agent SDK) that triages and investigates cases while keeping a human approval on every customer-facing action. Read source code, logs, network captures and SQL, and explain what I find in plain language to customers, support consultants and executives.

---

## Technical Skills

**Support & Escalation:** Case lifecycle management (Dynamics 365 CRM), Priority 1 incident handling, defect reproduction, root cause analysis, customer runbooks with rollback, executive and customer communication, support team training

**Authentication & Infrastructure:** Windows Authentication / Kerberos, Azure AD (Entra ID), SSO, OAuth2 client credentials, certificate authentication, TLS/HTTPS, IIS, enterprise networking, on-premises and cloud deployments

**Diagnostics:** Browser network captures (HAR) and developer tools, IIS failed-request traces, SQL Server Profiler, application log analysis, API testing (Postman), Datadog

**AI / LLM:** Claude Code (skills, plugins, managed settings), Claude Agent SDK, agent guardrails and human-in-the-loop design, sandboxed agent execution

**Programming & Scripting:** C#, .NET, Python, TypeScript / JavaScript, SQL, PowerShell, Bash; FastAPI, ASP.NET Web API, Angular, React, Node.js

**Tools & Cloud:** Git, Azure DevOps (pull requests, pipelines), Microsoft Azure, Docker, Jenkins

**Languages:** English, Russian, Kazakh (fluent)

---

## Work Experience

### Beyond Limits — Senior Escalations Engineer (DocLink)
*Jan 2023 – Present*

- Serve as the final technical escalation point for DocLink across web, desktop, cloud and ERP integrations (Dynamics GP, Dynamics 365 F&O), carrying 40+ active escalated cases at a time, about a quarter of them Priority 1, with an average first response under 2 hours.
- Work each escalation through an environment, then configuration, then code sequence, and have authored code fixes for 40+ customer cases across three repositories (C#/.NET, Angular, SQL), backed by QA test matrices and field-test builds for customer sites.
- Troubleshoot enterprise authentication with customer IT and security vendors: traced a year-old Windows Authentication failure to a Kerberos double hop using IIS failed-request traces and delivered a script pack and runbook with rollback; supported a certificate-authentication rollout that restored web login for a customer after a month-long Priority 1 outage.
- Settle disputed diagnoses with evidence: used a 65,000-event SQL Profiler trace to show the database was idle during gateway timeouts, and a 27 MB browser network capture to expose a server error hidden inside an HTTP 200 response.
- Traced a Priority 1 cloud data-loss case under CEO-level escalation to a transient network failure being read as a missing folder, wrote the fix, and ran a two-hour working session with the account owner from a prepared runbook.
- Analyzed a year of escalations (326 cases) and showed that more than half needed no code change; turned that into a 17-point escalation checklist and a 39-slide training for the support organization, plus SQL Profiler, TLS and HTTPS guides.
- Designed and built an AI case-automation system on Claude Code: 27 skills and a Python/FastAPI service over the Dynamics 365 API (OAuth2, 11 endpoints) that fetch cases, check them against a completeness gate, investigate, and draft notes. Read-only work runs unattended; emails, pull requests and status changes are queued for human approval. In one month, 934 scheduled runs triaged 164 cases.
- Co-built DocLink Whisperer, an AI first-pass analyst that runs Claude in a sandboxed container against customer diagnostic packages: led the CRM data-source integration (the production connector is ported from my service), designed a repro-readiness gate that sends source-quoted questions back to the submitter, and ran support training, a feedback survey and demos for the rollout.
- Audited AI-assisted development across three repositories for the CTO (no test, lint or coverage step in any CI pipeline; five overlapping AI instruction systems) and turned the findings into 46 action items across 7 workstreams, each with a done-when criterion and an owning department.
- Prepared and delivered the rollout demo and adoption plan for an internal Claude Code plugin marketplace (shared PR-review and QA-handoff standards) to developers at three experience levels.

### PennyMac Loan Services — Software Engineer
*Apr 2020 – Jan 2023*

- Developed and maintained Indexing and Retrieval web services for an internal cloud-based Document Management System used by 6,000+ employees globally.
- Co-developed an automatic loan approval ASP.NET Core application with a team of five that processed 20K+ applications and auto-approved ~11% within three months of release; built internal REST API microservice endpoints.
- Integrated third-party APIs (DocuSign, Google Drive) and developed document workflow and distribution stamp components supporting digital signing and compliance.
- Automated deployment with Jenkins and Docker, reducing deployment time and improving reliability; built a Datadog dashboard for application analytics.

---

## Education

**University of Southern California** — BS, Mechanical – Petroleum Engineering
*Aug 2012 – May 2016*

**Hack Reactor** — Advanced Software Engineering Immersive Program
*Feb 2020 – Nov 2020*

---

## Languages

English (fluent), Russian (fluent), Kazakh (fluent)
