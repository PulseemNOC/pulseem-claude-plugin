# Pulseem for Claude

Pulseem is a marketing automation platform for email, SMS, WhatsApp and landing pages. This plugin connects Claude to your Pulseem account through the official Pulseem (PulsyAI) remote MCP server, so you can ask Claude in plain language to work with your campaigns, contacts and reports.

## What you can do

- Look up campaigns, groups and contacts in your Pulseem account
- Review campaign performance and delivery reports
- Prepare and manage email, SMS and WhatsApp campaigns
- Get guidance on Pulseem screens and operations

## Setup

1. Install the plugin from the Claude directory.
2. When Claude first uses a Pulseem tool, sign in with your Pulseem account to authorize access.
3. Ask Claude something like: "Show me last week's email campaigns and their open rates."

## What this plugin runs and sends

This plugin contains no local code. It only declares one remote MCP server:

- `https://site.pulseem.co.il/pulsyai/mcp/` — operated by Pulseem.

Requests you make in Claude that use Pulseem tools are sent to that server, which acts on your Pulseem account with the permissions you granted when signing in. The plugin does not send data to any other destination.

## Privacy

Data is processed by Pulseem under the Pulseem privacy policy: https://site.pulseem.com/privacy-policy/

## Support

Contact Pulseem support at support@pulseem.com or visit https://www.pulseem.co.il.

## License

MIT
