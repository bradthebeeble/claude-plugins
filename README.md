# bradthebeeble's Claude Code Plugins

A plugin marketplace for [Claude Code](https://claude.com/claude-code).

## Setup

Run this command **inside Claude Code** to add the marketplace:

```
/plugin marketplace add bradthebeeble/claude-plugins
```

## Available Plugins

### mcp-macos-cua

macOS Computer Use Agent — full GUI automation via screenshots, clicks, typing, accessibility, and AppleScript.

**Install as Claude Code plugin** (includes `/cua` skill + auto-permissions):

```
/plugin install mcp-macos-cua@bradthebeeble-plugins
```

**Or use as standalone MCP server** with any agent (Cursor, Windsurf, Claude Desktop, etc.) — add to your MCP config:

```json
{
  "mcpServers": {
    "cua": {
      "command": "npx",
      "args": ["-y", "mcp-macos-cua"]
    }
  }
}
```

See the [mcp-macos-cua README](https://github.com/bradthebeeble/mcp-macos-cua) for full documentation, prerequisites, and system prompt for non-plugin usage.
