🛡️ Security Auditor

A security auditing skill for AI agents.

Security Auditor is an AI agent instruction set designed to review source code, identify potential security vulnerabilities, detect exposed secrets, and recommend practical security improvements.

The goal is simple: help developers identify genuine security risks while protecting sensitive information.

✨ Features

- 🔑 Secret Detection — Identify exposed API keys, passwords, tokens, and cryptographic secrets.
- 🔍 Vulnerability Detection — Review code for injection, authentication, authorization, and other common security weaknesses.
- 📦 Dependency Security — Inspect dependency manifests for outdated or potentially vulnerable packages.
- ⚙️ Configuration Review — Identify insecure settings, exposed administrative interfaces, and unsafe configurations.
- 📊 Severity Classification — Classify findings as Critical, High, Medium, Low, or Informational.
- 📝 Security Reports — Generate structured reports with explanations, potential impact, and recommended fixes.
- 🔒 Privacy Protection — Mask sensitive values and avoid exposing credentials.

🔎 What It Checks

Category| Examples
Secrets| API keys, passwords, tokens, private keys
Injection| SQL, Command, NoSQL, Template
Authentication| Password handling, sessions, token validation
Authorization| Permission checks, ownership verification
File Security| Path traversal, unsafe uploads
Network Security| TLS, SSRF, CORS, redirects
Dependencies| Vulnerable and outdated packages
Configuration| Debug mode, permissions, exposed storage
Data Exposure| Sensitive logs, error messages, backups

🚀 Usage

1. Open ""SECURITY-AUDITOR.md"" (SECURITY-AUDITOR.md).
2. Copy its contents or provide the file to an AI coding assistant that supports custom instructions.
3. Ask the assistant to perform a security review of code you own or are authorized to assess.
4. Review the generated findings and recommendations.
5. Apply fixes only after reviewing the proposed changes.

Example prompt:

«Use the Security Auditor instructions to review this project's code for security vulnerabilities, exposed secrets, and insecure configurations. Provide a structured report with severity levels and recommended fixes.»

📋 Report Format

Security findings use the following severity levels:

- 🔴 CRITICAL — Severe security compromise.
- 🟠 HIGH — Serious vulnerability with significant potential impact.
- 🟡 MEDIUM — Meaningful security weakness.
- 🔵 LOW — Minor security issue.
- ⚪ INFORMATIONAL — Security recommendation or hardening opportunity.

Each finding should include its severity, confidence, affected file, location, explanation, potential impact, and recommended fix.

🔐 Security Principles

Security Auditor follows several important principles:

- Never reveal complete secrets in reports.
- Never attempt to use discovered credentials.
- Never send source code or secrets to external services without authorization.
- Never modify files without explicit permission.
- Never invent vulnerability findings.
- Verify suspicious patterns before reporting them.
- Clearly communicate uncertainty and audit limitations.

⚠️ Important Disclaimer

Security Auditor is an AI-assisted review instruction set, not a standalone scanning application or a guarantee of security.

AI-generated findings may be incomplete or incorrect. Always verify important results. A limited code review cannot prove that an application is completely secure.

Only use it to review code and systems you own or are authorized to assess.

📁 Repository Structure

security-auditor/
├── README.md
└── SECURITY-AUDITOR.md

📄 License

No license has been specified yet.

---

Protect secrets. Find real risks. Build safer software.
