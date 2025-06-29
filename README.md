# mcp

## Description

Repo for organizing MCP.

## Guidelines

- Whenever possible, use a pre-built package. However, will occassionally need to download source.

## Local testing

### mcp-inspector

`DANGEROUSLY_OMIT_AUTH=true HOST=0.0.0.0 MCP_PROXY_FULL_ADDRESS=http://vm-code:6274 ALLOWED_ORIGINS=http://vm-code:6274 npx @modelcontextprotocol/inspector`
- Navigate to `$HOST:6274`
- Can then configure command and args via the UI (i.e. command=`npx` and args are `-y @modelcontextprotocol/filesystem .`
