# Install Same Day Website Builder (for AI agents)

Remote MCP server. Nothing to install or run locally.

1. Add this to the client's MCP config:
```json
{"mcpServers":{"same-day-website-builder":{"url":"https://samedaywebsitebuilder.com/mcp"}}}
```
2. On first use the client opens an OAuth sign-in (OAuth 2.1, dynamic client registration). The user signs in or creates an account at samedaywebsitebuilder.com. No API key.
3. Test it: "Build a website for TEST Joe's Plumbing, (765) 555-0100, Peru IN, drain cleaning and water heaters. I work there."

Rules: confirm the user owns or works for the business. Use only facts the user gives. Quote prices only from sdwb_get_pricing. Payment happens only on samedaywebsitebuilder.com, never in chat.
Docs: https://samedaywebsitebuilder.com/ai-assistants
