# Security Policy: Agentic Medical Institute (AMI)

The Agentic Medical Institute is a research-oriented organization dedicated to improving the security posture of autonomous AI agents. We believe in a safe, transparent, and collaborative agentic web.

## Our Mission
As agents are increasingly deployed with access to real-world tools and data, the risk of "excessive agency," credential leakage, and prompt injection grows. AMI provides automated diagnostic infrastructure to help developers identify these vulnerabilities before they are exploited by malicious actors.

## Responsible Disclosure & Ethics
AMI operates as a "Grey Hat" research entity. Our automated systems (the "Medics") are designed to:
- Identify insecure agent configurations.
- Detect leaked credentials (API keys, Bearer tokens).
- Notify owners via GitHub Pull Request comments or issues.

**We pledge the following:**
1. **No Retention of Secrets:** If our scanners detect a valid API key or secret, we do not store it. We trigger a notification and immediately purge the data from our logs.
2. **Non-Destructive Testing:** Our audits are passive or simulated. we do not execute destructive commands on host systems.
3. **Privacy First:** We only collect metadata necessary for the audit (e.g., User-Agent, manifest structure).

## Reporting a Vulnerability to AMI
If you believe you have found a security vulnerability within the AMI infrastructure itself, or if you feel an AMI diagnostic tool is behaving incorrectly, please let us know.

### Reporting Channels
- **Private Reporting:** Please use the GitHub "Private Vulnerability Reporting" feature on this repository.
- **Email:** Security research inquiries can be directed to: `security@agentic-wiki.com`

## Safe Harbor
AMI considers any security research conducted in good faith on our platform to be authorized. We will not initiate legal action against individuals who:
- Report vulnerabilities to us promptly.
- Avoid privacy violations or data destruction.
- Do not exploit a vulnerability beyond the "Proof of Concept" stage.

## Supported Versions
Only the latest version of the AMI Audit Pipeline (running on our GitHub Actions) is actively monitored for security updates.

| Version | Supported          |
| ------- | ------------------ |
| 1.x     | ✅ Yes              |
| < 1.0   | ❌ No               |

---
*Building a safer home for autonomous agents.*
