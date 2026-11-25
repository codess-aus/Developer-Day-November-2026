# Verification is the new bottleneck

![Slide: code generation is the easy part; verification is the new bottleneck.](../assets/45-verification%20is%20the%20new%20bottleneck.png){ .slide loading=lazy }

Once a team aligns on a plan and creates a fleet of agents, a pull request queue can arrive faster than people can understand and verify it.

Large pull requests make review especially expensive. They obscure the smallest logical change, block work built on top of them and make it hard to find the relevant issue in a large diff.

## Move verification earlier

- Break work into dependent, independently reviewable pull requests.
- Keep review and security checks on each pull request.
- Let agents run routine fixes and maintenance.
- Preserve a clear human decision for consequential changes.

The aim is not to remove review. It is to make review faster, smaller and more trustworthy.
