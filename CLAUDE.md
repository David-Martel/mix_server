# mix_server

Project template/scaffold for multi-language MCP servers. Not a production server.

## Current State

Minimal placeholder. `main.py` prints "Hello from mix-server!" with no MCP logic.
No dependencies declared. No `src/` directory created yet.

## Requirements

- Python 3.13+
- uv (package manager)

## To Expand

1. Create `src/mix_server/` package with MCP server implementation
2. Add dependencies to `pyproject.toml` (at minimum: `mcp[cli]`)
3. Replace `main.py` placeholder with server entry point
4. See `reference/mcp-server-dash/` for a complete Python MCP server example
