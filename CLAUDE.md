# CLAUDE.md

## Workflow

After pushing a feature branch, automatically:

1. Open a pull request against `main` using the GitHub MCP tools.
2. Post a self-review on the PR as a review comment (use `mcp__github__pull_request_review_write` with `event: COMMENT`) covering: what changed, trade-offs, non-blocking suggestions, and a brief verification note.

Do this without waiting to be asked, once the push succeeds.
