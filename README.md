# ThriveDesk MCP

Official remote MCP server for [ThriveDesk](https://www.thrivedesk.com), the AI help desk for ecommerce and SaaS teams.

Search, reply, tag, assign and report on your ThriveDesk conversations from Claude, ChatGPT, Cursor, VS Code, Cline, Gemini CLI or any MCP client.

## Server

- URL: `https://mcp.thrivedesk.com`
- Transport: Streamable HTTP
- Auth: OAuth (your normal ThriveDesk sign-in, no API key)
- Plan: ThriveDesk Standard or Unlimited

## Connect

Claude Code:

```
claude mcp add --transport http thrivedesk https://mcp.thrivedesk.com
```

Cursor, VS Code and other `mcp.json` clients:

```json
{ "mcpServers": { "thrivedesk": { "url": "https://mcp.thrivedesk.com" } } }
```

Gemini CLI:

```
gemini extensions install https://github.com/thrivedesk/thrivedesk-mcp
```

Then approve the connection on the ThriveDesk page that opens: pick a workspace and a Read-only, Standard or Full access preset.

## What it can do

28 actions across conversations, contacts, inboxes, live chat, knowledge base, saved replies, notifications, reports and attachments. Full list and permissions: https://help.thrivedesk.com/en/mcp

## Support

help@thrivedesk.com · https://help.thrivedesk.com/en
