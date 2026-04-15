# Security Policy

Hyerix takes the security of its products and customers seriously. If you
believe you have found a security vulnerability in Hyerix, please report it
to us privately using the process below.

## Reporting a Vulnerability

**Email: [security@hyerix.ai](mailto:security@hyerix.ai)**

Please do **not** report security vulnerabilities through public GitHub
issues or any other public channel.

When reporting, please include as much of the following as possible:

- The Hyerix surface affected (desktop app, `hyerix.ai`, `docs.hyerix.ai`,
  `control.hyerix.ai` or another service)
- The version of the desktop app (found under **Settings → About**)
- The operating system and version
- A clear description of the issue and its potential impact
- Step-by-step instructions to reproduce, including any proof-of-concept
  code, screenshots, or logs
- Any suggested remediation, if you have one

The more detail you provide, the faster we can verify and resolve the issue.

## What to Expect

- **Acknowledgement** within 3 business days of your report.
- **Triage and validation** within 10 business days, including a preliminary
  severity assessment.
- **Progress updates** at least once per week while the issue is being
  investigated and fixed.
- **Coordinated disclosure** — we will work with you on a timeline for
  public disclosure once a fix is available. We credit researchers who
  report in good faith, unless you prefer to remain anonymous.

## Scope

In scope for this policy:

- The Hyerix desktop application (macOS, Windows, Linux builds)
- Hyerix web services: `hyerix.ai`, `docs.hyerix.ai`, `control.hyerix.ai`,
  and related infrastructure
- Hyerix's installer signing, update pipeline, and license validation
- Any data handled by Hyerix on our infrastructure

Out of scope:

- Vulnerabilities in third-party components used by Hyerix — please report
  those upstream (NATS, JetStream, Tauri, Ollama, etc.)
- Issues that require physical access to an unlocked user device
- Social engineering of Hyerix staff or customers
- Denial-of-service attacks and resource exhaustion testing
- Automated scans that generate significant load

## Safe Harbor

Hyerix considers security research conducted in accordance with this policy
to be authorized, and we will not pursue legal action against researchers
who:

- Make a good-faith effort to avoid privacy violations, data destruction,
  and service disruption
- Only interact with accounts they own or have explicit permission to test
- Report vulnerabilities promptly and do not exploit them beyond what is
  necessary to demonstrate impact
- Give us a reasonable window to fix the issue before any public disclosure

## Hall of Fame

We are happy to publicly credit researchers who report valid vulnerabilities.
If you would like to be credited, let us know in your report. At this time
Hyerix does not operate a paid bug bounty program.

---

Thank you for helping keep Hyerix and our customers safe.
