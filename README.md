# Chiaro plugin for Cursor and Grok Bot

SOC 2 for solo founders, done in your AI tool.

This plugin connects Cursor and Grok Bot to Chiaro. Your AI can then scope your SOC 2, collect
evidence from the tools you already use, help you fix what is missing, and take you to the audit
when you are ready.

## What's in it

| Component | What it does |
|---|---|
| MCP server (`mcp.json`) | Connects to Chiaro's hosted server at `https://mcp.chiarohq.com/mcp`. You sign in with your browser, so there is no API key to copy. |
| Skill (`skills/chiaro-soc2`) | Tells your AI how to start (`get_status` first) and the ground rules: you approve every command and every submission. |

## Install

**Cursor.** Open the Marketplace, search for Chiaro, and add it. When the Chiaro server asks you to
sign in, finish in your browser.

**Grok Bot.** Open Settings, then Plugins. Search for Chiaro, choose Add, and finish signing in with
your browser.

New to Chiaro? You can create an account on the sign-in screen.

Then ask your AI: "Start my SOC 2 readiness check with Chiaro."

## Data and privacy

- The plugin connects to one endpoint, `https://mcp.chiarohq.com/mcp`.
- It contains no credentials. Your sign-in is held by the app you connect from.
- Chiaro never logs in to your systems and never receives your passwords or keys. Your AI runs any
  commands on your side, with your approval, and evidence reaches Chiaro only when you approve
  submitting or uploading it.
- Privacy policy: https://chiarohq.com/privacy

## Support

Email hello@chiarohq.com or visit https://chiarohq.com.

## License

MIT. See [LICENSE](LICENSE).
