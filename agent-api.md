# Agent API prompt

Paste this into your coding agent before your track prompt, if the build gives an AI agent its own wallet. That's most builds in the defi, privacy, business, swarms, security and agents tracks.

```text
My build gives an AI agent its own wallet. Use the NEAR Intents Agent API for it:

1. Install the Agent API skills: npx skills add NEAR-Intents-Agent-API/skills
2. Create an API key in the partner dashboard (https://partners.demo.agentsonintents.com/dashboard) and put it in .env.
3. Base URL: https://api.demo.agentsonintents.com. Read the docs (https://docs-production-7968.up.railway.app/integration/agent-api/overview) for endpoints; never guess them.
4. The wallet enforces a policy signed by the owner: allowed assets and destinations, a USD budget, time windows and an emergency stop. Once I sign it, the agent acts on its own inside those rules, gas-free, with no signature per transaction.
5. Demo notice: the API keys are temporary and will be rotated after the demo period. Don't rely on them for continued access.
```

## What it covers

Each agent gets its own wallet on NEAR Intents without the owner ever handing over root keys. It can swap, transfer and withdraw from a public balance or a private Confidential Intents balance, and every execution runs in an attested TEE with a proof you can check without trusting the operator.

- [Quickstart](https://docs-production-7968.up.railway.app/integration/agent-api/quickstart/introduction): a funded agent that swaps, transfers and withdraws in 30 minutes
- [Examples](https://github.com/NEAR-Intents-Agent-API/examples), [SDK](https://github.com/NEAR-Intents-Agent-API/sdk-typescript) and [skills](https://github.com/NEAR-Intents-Agent-API/skills) repos
