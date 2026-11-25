# Try it: the Modernize CLI

The modernization agent is delivered through the Modernize CLI, which gives a unified CLI and TUI experience for modernizing Java and .NET applications.

## Install

```bash
# macOS (Homebrew cask)
brew tap microsoft/modernize https://github.com/microsoft/modernize-cli
brew trust microsoft/modernize
brew install --cask modernize

# Windows (winget)
winget install GitHub.Copilot.modernization.agent
```

Requirements: Git, GitHub CLI 2.45.0 or later, and a GitHub Copilot subscription on any plan (Free, Pro, Pro+, Business or Enterprise).

## Use it

```bash
gh auth login   # authenticate first
modernize       # opens the interactive menu
```

The menu walks through **Assess**, **Plan**, **Execute** and **Upgrade**. Each step is also a command:

| Command | What it does |
|---------|--------------|
| `modernize assess` | Analyses the application and writes an assessment report (HTML by default). Accepts repeatable `--source` for several repositories. |
| `modernize plan create <prompt>` | Creates a modernization plan from a natural language goal. |
| `modernize plan execute` | Runs the tasks in the plan. |
| `modernize upgrade <target>` | Plan and execute in one command, for example `.NET 10` or `Java 17`. Defaults to the latest LTS. |

Add `--delegate cloud` to hand an assessment to the Cloud Coding Agent, and `--no-tty` for headless runs.

Source: [microsoft/modernize-cli](https://github.com/microsoft/modernize-cli)
