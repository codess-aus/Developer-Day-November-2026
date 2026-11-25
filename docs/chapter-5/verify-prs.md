# Verify every pull request

Stacked pull requests split dependent work into smaller pieces. If the API, index update, map and documentation are separate changes, each one can be reviewed and verified before the next one depends on it.

## Code Quality

![Slide: GitHub Code Quality.](../assets/46-code%20quality.png){ .slide loading=lazy }

GitHub Code Quality holds agent-generated and human-generated code to the same maintainability, reliability and test standards.

## Copilot code review

![Slide: Copilot code review modes.](../assets/47-code%20review.png){ .slide loading=lazy }

Copilot Code Review provides a configurable first-pass review. Lite, Balanced and Max modes let an organization adjust analysis for changes of different complexity.

## Security and policy checks

![Slide: AI scan for pull requests and repositories.](../assets/48-AI%20Scan.png){ .slide loading=lazy }

AI scanning covers pull requests and repositories for languages and framework patterns outside or beyond traditional rule-based analysis.

![Slide: AI secret detection.](../assets/49-AI%20secret%20detection.png){ .slide loading=lazy }

AI secret detection expands beyond structured provider patterns to recognize text that is likely to be secret material.

![Slide: license compliance.](../assets/50-licence%20compliance.png){ .slide loading=lazy }

License compliance checks package changes against the organization's open source license policy.

![Slide: Agentic Autofix.](../assets/51-agentic%20autofix.png){ .slide loading=lazy }

Agentic Autofix proposes a repair for a detected issue and creates or updates a draft change for review.
