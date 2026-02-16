# v0-mcp — Tasks

## Core MCP Server ✅
- [x] MCP server via `@modelcontextprotocol/sdk` v1.26.0 (stdio transport)
- [x] 4 MCP tools: `v0_generate_ui`, `v0_generate_from_image`, `v0_chat_complete`, `v0_setup_check`
- [x] v0 API integration via OpenAI-compatible client
- [x] Model support: `v0-1.5-md`, `v0-1.5-lg`, `v0-1.0-md`
- [x] Zod input validation
- [x] Winston structured logging
- [x] Error handling with retry/backoff
- [x] Environment config (V0_API_KEY, V0_BASE_URL, etc.)
- [x] CI/CD via GitHub Actions

## Known Issues ⬜
- [ ] Re-enable Jest unit tests in CI (temporarily disabled)
- [ ] Fix TypeScript/ESLint issues in test suite

## Improvements ⬜
- [ ] Local image support (file paths / base64, not just URLs)
- [ ] Conversation/session persistence across tool calls
- [ ] NPM publish / distributable package
- [ ] Support newer v0 models as they release
- [ ] `npx`-based zero-install usage
