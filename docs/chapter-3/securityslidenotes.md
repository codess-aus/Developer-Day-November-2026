

## Slide 1: Agentic security for every developer

Balance: 15 min slides / 25 mins demo (one guest demo)

https://github.com/octodemo/agentic-security-for-every-developer/blob/main/DEMO_NOTES.md

## Slide 2: Where humans & agents build software together

TALK: [this is our mission, securing tens of thousand of enterprises and open-source projects; but it’s gotten a lot more challenging recently…]

## Slide 3: Agentic security for every developer

TALK: [we notice a pace gap, even with ever more disclosed vulnerabilities and highly engaged maintainers, automated attacks have collapsed the time to exploit. Now attacks often precede disclosure; this is the challenge we must rise to, let me share what we’re doing about it]

Source: https://www.stackhawk.com/blog/time-to-exploit-negative/

## Slide 4: developers

TALK: [these are our core pillars <explain each>; the foundation trusted by millions of developers, maintainers and researchers – keeping their pull requests and repos secure. But to overcome the pace gap, we realized security can’t wait for code to make it from dev environment to PR – it might already be too late….]

## Slide 5: Agentic security for every developer

TALK: [we realized we needed to deliver security that adapt to every stage of the agentic development loop, help developers prevent issues, and remediate where they work. We can’t just ship an IDE plugin and call it a day, we needed to look at every single surface developers interact with <walk through them and what they mean>.  All of these surfaces gain new security capabilities we’re announcing or expanding today. In the rest of this session, I want to walk you through every single one, all of which you can use _today_. Let’s jump in….]

## Slide 6: Agent loop

Copilot cloud agent's security validation does not require a GitHub Secret Protection, GitHub Code Security, or GitHub Advanced Security license.
- CodeQL is used to identify code security issues.
- Newly introduced dependencies are checked against the GitHub Advisory Database for malware advisories, and for any CVSS-rated High or Critical vulnerabilities.
- Secret scanning is used to detect sensitive information such as API keys, tokens, and other secrets.

## Slide 7: DEMO

DEMO: agent loop secure ai checks

## Slide 8: Agentic Development Environment

You can now use AI Scan to find vulnerabilities across your whole repository, not just in pull request changes. It covers languages and frameworks that CodeQL doesn’t support and finds issues that rule-based analysis can miss in languages CodeQL already covers.
- An agentic code scanner explores your repository and focuses on the code most likely to contain vulnerabilities. Each scan runs within a fixed time budget, which keeps its cost bounded.
- When both AI Scan and CodeQL are scanning the same repository, AI Scan skips issues that CodeQL already reports.
- On rescans, AI Scan keeps existing findings open if it detects them again and only reports new findings.

## Slide 9: DEMO

DEMO: CLI, IDE and Copilot Security Extension

## Slide 10: PR & REPO AI SCANNING

Agentic autofix remediates alerts by working across your codebase the way a developer would: it explores relevant files, proposes a fix, and reruns CodeQL to confirm the fix closes the alert before opening a pull request for your review.

## Slide 11: DEMO

DEMO: PR AI Scanning, PR XPIA scanning (guest demo from Ying, enters stage for demo, then leaves at the end of this demo section), back to Pierre for repo scanning

DEMO: Repo scanning standard and deep

## Slide 12: Agentic Autofix

Screenshot will change

## Slide 13: DEMO

DEMO: Let’s fix all those vulns we just found – demo agentic Autofix with memories and bulk remediation

## Slide 14: Agentic security for every developer

(Links not yet ready)

Closing & CTA

## Slide 15

_No notes._

## Slide 16

_No notes._
````
