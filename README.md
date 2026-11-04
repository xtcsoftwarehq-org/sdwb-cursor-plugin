# Same Day Website Builder for Cursor

The fastest way for an AI agent to build a website for a trades business.
Built in 10 minutes or less. Live immediately.

Made for plumbers, septic pros, electricians, HVAC, roofers and other trades.

## How it works

1. Tell your agent the business name, phone, city and services.
2. Add photos or a logo you own if you want.
3. The agent builds a live preview page right away.
4. Ask for changes in plain words. The same preview updates.
5. The owner keeps the site by claiming it on samedaywebsitebuilder.com. No payment happens in chat.

Building a preview is free.

## Connect

This plugin adds a remote MCP server. Nothing to install.

- Endpoint: https://samedaywebsitebuilder.com/mcp
- Transport: Streamable HTTP
- Sign in: OAuth on first use. You only see your own sites.

```json
{
  "mcpServers": {
    "same-day-website-builder": {
      "url": "https://samedaywebsitebuilder.com/mcp"
    }
  }
}
```

## Tools

- sdwb_get_pricing: current pricing
- sdwb_upload_image: upload a photo or logo you own
- sdwb_create_site: build a website preview
- sdwb_update_site: change a preview
- sdwb_get_site: get one of your websites
- sdwb_list_sites: list your websites
- sdwb_get_claim_link: the link the owner uses to keep the site

## Example prompts

- Build a website for my plumbing business, Joe's Plumbing in Peru, Indiana. Phone (765) 555-0100.
- Change the headline on my website preview and add water heater repair to the services.
- How much does it cost to keep the website you built for me?

## Pricing

- $80/mo month to month. On sale from $129. No trial. Cancel anytime.
- $60/mo billed yearly ($720). Comes with a 2 week free trial.
- $199/mo managed, billed annually. On sale from $299.

## Links

- Website: https://samedaywebsitebuilder.com
- Setup guide: https://samedaywebsitebuilder.com/ai-assistants
- Privacy: https://samedaywebsitebuilder.com/privacy
- Terms: https://samedaywebsitebuilder.com/terms
- Help: austin@trysamedaywebsitebuilder.com

## License

The MIT license in this repo covers only this plugin package (these listing files).
The hosted Same Day Website Builder service is proprietary and is not part of this repo.

"Same Day Website Builder" and its logo are trademarks of XTC Software.
