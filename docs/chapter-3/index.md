# 3. Secure Delivery with GitHub Advanced Security

How security keeps pace when humans and agents build software together, from the agent loop to enterprise-wide remediation.

- [Securing the Agent-Native Engineering System](agentic-security.md)
- [More vulnerabilities, faster attacks](more-vulnerabilities.md)
- [Developer-friendly; enterprise-grade](enterprise-grade.md)
- [Making security ubiquitous](ubiquitous-security.md)
- [Agents write secure code by default](secure-by-default.md)
- [Collaborate with security agents](collaborate.md)
- [Analyze any language](analyze-any-language.md)
- [Bulk-fix issues](bulk-fix.md)
- [Summary: how to turn it on](summary.md)

## Latest from GitHub

- **Agentic autofix** for code scanning alerts is generally available. It proposes a fix, reruns CodeQL to confirm the alert closes, then opens a pull request. You can assign up to 25 alerts to Copilot at once.
- **AI Scan for repositories** (public preview) finds vulnerabilities across the whole repository, including languages CodeQL does not cover.
- **Security extension for the GitHub Copilot app** (public preview) lets you browse code scanning alerts, then ask Copilot to explain or fix them locally. `/security-review` checks your local changes before you open a pull request.

## Secret scanning

Per GitHub Docs, secret scanning checks your whole Git history on all branches for hardcoded credentials. It also covers issues, pull requests, discussions, wikis and secret gists. Key points:

- Partner secrets are reported to the provider so it can revoke the credential, and do not appear in your repository alerts.
- When an alert fires, rotate the credential straight away. Removing it from history is slow and often unnecessary once it is revoked.
- You can add generic patterns, custom patterns, validity checks, AI-detected secrets and AI-generated regular expressions.
- It runs free on public repositories, and needs GitHub Secret Protection for private and internal organisation repositories.

Source: [Secret scanning](https://docs.github.com/en/code-security/concepts/secret-security/secret-scanning)

Sources: [Agentic autofix for code scanning alerts](https://github.blog/changelog/2026-10-15-agentic-autofix-for-code-scanning-alerts-general-availability/), [AI Scan for repositories](https://github.blog/changelog/2026-10-28-ai-scan-for-repositories-in-public-preview/), [Security extension for the GitHub Copilot app](https://github.blog/changelog/2026-10-28-security-extension-for-the-github-copilot-app/)
