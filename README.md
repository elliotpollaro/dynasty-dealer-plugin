# Dynasty Dealer for Grok Bot and Cursor

<img src="assets/logo.png" alt="Dynasty Dealer" width="96" align="right">

[Dynasty Dealer](https://www.dynastydealer.com/trade-calculator/superflex) values dynasty fantasy football players and rookie picks on a 0 to 10,000 scale, built from real Sleeper trades blended with community votes. This plugin connects Grok Bot and Cursor to Dynasty Dealer's hosted MCP server, so you can ask about dynasty trades in plain language.

## What it can do

| Tool | What it does |
|---|---|
| `evaluate_trade` | Grades a trade: each side's value, plus a link that opens the same trade in the Dynasty Dealer calculator |
| `get_player_values` | What players and rookie picks are worth, in Superflex or 1QB, with or without TE premium |
| `get_dynasty_rankings` | Dynasty rankings, overall, by position or for rookie picks |
| `get_trade_market` | What a player or pick actually fetched in recent real Sleeper trades |
| `get_account` | Which Dynasty Dealer plan your signed-in account has |

Every tool is read-only.

## Try it

- "Is Bijan Robinson for Ja'Marr Chase and a 2027 1st fair in superflex?"
- "Top 10 superflex dynasty rankings"
- "What's a 2027 1st worth in 1QB?"
- "What did Brock Bowers get traded for recently?"

## Signing in

No account is needed for any of the questions above. Sign in with your Dynasty Dealer account to use what your plan includes: with Premium, rankings go past the top 50 and trade lookups show six recent examples instead of two.

Sign-in uses OAuth 2.1 with PKCE. The connection can see which plan your account has. It cannot change your account, your leagues or your billing.

## What is in this repository

This repository is the plugin package only: the manifest (`.cursor-plugin/plugin.json`), the server address (`mcp.json`) and the logo. The MCP server runs at `https://www.dynastydealer.com/mcp/grok` and is operated by Dynasty Dealer.

## Links

- Setup for ChatGPT, Claude, Grok and Gemini: https://www.dynastydealer.com/ai-assistants
- Privacy policy (section 7 covers AI assistants): https://www.dynastydealer.com/privacy-policy
- Terms of service: https://www.dynastydealer.com/terms-of-service
- Support: elliot@dynastydealer.com

## License

The plugin package in this repository is MIT licensed (see [LICENSE](LICENSE)). Dynasty Dealer's data and service are covered by its [terms of service](https://www.dynastydealer.com/terms-of-service).
