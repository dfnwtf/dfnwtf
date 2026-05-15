## Hi, I'm Andy

Solana builder. Currently shipping [Latrine Bot](https://latrinebot.com) - a cloud automation engine for Pump.fun tokens.

### Latrine Bot

Cloud-only Pump.fun automation: claim creator fees, buy the token back, drop the proceeds to holders by tier rules. No CLI, no local node, no scripts to maintain.

- **Site:** [latrinebot.com](https://latrinebot.com)
- **Dashboard:** [latrinebot.com/app](https://latrinebot.com/app)
- **API:** [`api.latrinebot.com`](https://api.latrinebot.com/api/health)
- **X:** [@Latrine_bot](https://x.com/Latrine_bot)

### Public repo

Everything that integrators need - docs, OpenAPI spec, TypeScript SDK, embeddable widgets, eligibility calculator, CLI - lives in one place:

[**github.com/dfnwtf/latrinebot**](https://github.com/dfnwtf/latrinebot)

The on-chain engine, the runner, and the operator panel are private by design. The public repo is enough to integrate, audit the API, and understand the eligibility math.

### npm

- [`@latrinebot/sdk`](https://www.npmjs.com/package/@latrinebot/sdk) - TypeScript client + OpenAPI 3.1 spec
- [`@latrinebot/widgets`](https://www.npmjs.com/package/@latrinebot/widgets) - browser embeds
- [`@latrinebot/cli`](https://www.npmjs.com/package/@latrinebot/cli) - public-API CLI

### Stack

TypeScript, Cloudflare Workers + Durable Objects, D1, Node, Solana web3.js, Pump.fun SDK, PumpSwap.
