# From planning meeting to pull request

The traditional flow often starts with a meeting, then moves through Slack, issue creation, clarification and documentation before anyone opens a repository.

In 4th Coffee's new flow, the team:

1. Starts in a Copilot session after the meeting.
2. Adds transcripts, observability data and business context.
3. Checks assumptions and shares a quick mock-up.
4. Refines the idea with the team.
5. Uses Copilot to create issues with titles and acceptance criteria.

!!! tip "For more than a few minutes of work"
    Record context and decisions where they can be reused. Architecture Decision Records and similar documents can capture the decision, alternatives and consequences alongside the change.

When the issues open in GitHub or Azure Boards, automation can triage them, estimate the likely size and identify areas of the codebase. Low-complexity work can be assigned directly to Copilot; the team focuses on defining and refining the more complex work.

The goal is not to remove the meeting or planning. It is to turn the result of a conversation into executable, reviewed work instead of losing it between tools.
