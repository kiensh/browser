# browser

## Playwright MCP

To enable Playwright in Claude Code for a fresh checkout, run this from the repo root with Node.js and Google Chrome installed:

```sh
claude mcp add --scope project playwright -- npx -y @playwright/mcp@latest --browser chrome
```

Open Claude Code in this repo, approve `playwright` if prompted, and use `/mcp` to check its status. The project config (`.mcp.json`) and browser output (`.playwright-mcp/`) stay out of Git.

