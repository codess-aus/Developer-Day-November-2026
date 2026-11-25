# Automate repetitive work, with developers in control

![Slide: Copilot Automations. The Automations page on GitHub showing groups such as issue triage and pull request demos.](../assets/5-automate-repetitive-work-with-developers-in-control.png){ .slide loading=lazy }

**Copilot Automations** automate repetitive development tasks such as issue triage and code review. They use feedback from results to improve outcomes over time.

!!! note "Slide correction"
    The slide labels Copilot Automations as GA. GitHub Docs does not describe it as GA, so this site does not claim it.

**Takeaway:** less time on toil, more time building what matters.

## How it works

- Automations run in the cloud. Start them manually, on a schedule, or in response to an event.
- Automations can be grouped. Members of a group share persistent storage for results, decisions and feedback.
- Copilot can help you build self-improving groups, where some automations do the work and others evaluate outcomes.
- Automations can propose improvements to their own prompts, tools and triggers. You review and approve each proposal.
- Trigger them from the GitHub REST API to connect external systems, and from 24 more events across issues, pull requests, discussions and security alerts.
- Shared automations are visible to everyone with read access and editable by anyone with write access. Their actions are attributed to Copilot, and they keep a change history.
- Available on Copilot Pro, Pro+, Max, Business and Enterprise, in any repository where you have write access.
- Automations are not available in public repositories. The repository must be private or internal, with Copilot cloud agent enabled.
- Shared automations keep working if their creator leaves the team, because they belong to the repository.
- To reduce prompt injection risk, automations ignore events from users without write access by default.

Sources: [Copilot automations](https://docs.github.com/en/copilot/concepts/agent-capabilities/agent-powered-workflows-and-operations/about-automations), [Using automations in the GitHub Copilot app](https://docs.github.com/en/copilot/how-tos/github-copilot-app/using-automations)
