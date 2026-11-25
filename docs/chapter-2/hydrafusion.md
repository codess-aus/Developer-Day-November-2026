# Advanced runtime orchestration with HydraFusion

![Slide: Advanced runtime orchestration with HydraFusion. A model picker listing Auto, HydraFusion (Preview), and several other models.](../assets/17-hydrafusion.png){ .slide loading=lazy }

HydraFusion (preview) delivers frontier intelligence through runtime orchestration. It creates a full execution plan, choosing from models across multiple providers to draft, critique and revise, or cascade to more powerful models to complete your task.

## Latest updates

- It is a research preview in VS Code, the GitHub Copilot app and Copilot CLI. It appears in the model picker but orchestrates several models rather than being one.
- HydraFusion Max adds frontier capability for the most demanding tasks.
- It tailors reasoning effort per step: medium for drafts and high for review.
- Critique uses tools to inspect the actual workspace, with parallel critic models. Cascade can add a judging step that requests a repair only when needed.
- It is available on Copilot Pro, Pro+, Business and Enterprise. Business and Enterprise administrators must enable preview features.

For production work, GitHub's generally available [Copilot Fusion](../chapter-1/copilot-fusion.md) is the related option.

Sources: [HydraFusion in VS Code and the GitHub Copilot app](https://github.blog/changelog/2026-09-30-hydrafusion-in-vs-code-and-the-github-copilot-app/), [HydraFusion updates and new Max option](https://github.blog/changelog/2026-10-14-hydrafusion-updates-and-new-max-option/)
