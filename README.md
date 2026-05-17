# ai-agent-poc

Proof of concept: MCP config injection via fork PR on AI coding agents in GitHub Actions.

Demonstrates how `.opencode/opencode.jsonc` from a fork PR is read by OpenCode at startup when `actions/checkout` checks out `refs/pull/<N>/merge` on `pull_request_review_comment` events.

See: [ask-bonk/ask-bonk/github](https://github.com/Cloudflare-Studio/ask-bonk) (Cloudflare's OpenCode GitHub Action)
