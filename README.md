# web3-marketing-gtm

> An OpenClaw skill that gives AI agents a full-stack Web3 marketing and GTM brain.

Built by [@luacantu](https://github.com/luacantu) · [View on ClawHub](https://clawhub.ai/luacantu/web3-marketing-gtm)

---

## What it does

Give an AI agent a project name, blockchain, and product type — it produces a complete, execution-ready marketing suite:

- **GTM Launch Plan** — positioning, 3-phase launch strategy, channel plan, 30-day KPIs
- **Campaign Calendar** — 4-week day-by-day schedule across Discord, X, and Telegram
- **Community Scripts** — 15+ ready-to-use scripts for Discord, Telegram, and X (Twitter)
- **On-Chain Retention Strategy** — 4-tier wallet segmentation, trigger→response loops, re-engagement templates

No human hand-holding required. The agent handles strategy, content, and sequencing end-to-end.

---

## Install

```bash
clawhub install luacantu/web3-marketing-gtm
```

Or download the `.skill` file directly from the [Releases](https://github.com/luacantu/web3-marketing-gtm/releases) tab.

---

## Usage

The skill triggers automatically when an AI agent receives a Web3 marketing request. Minimum input required:

```
Project Name: <name>
Chain: <e.g. Avalanche, Base, Solana, Ethereum>
Product Type: <e.g. DeFi protocol, NFT collection, GameFi, payments app, oracle>
```

Optional: target audience, differentiator, existing community size, launch date, token yes/no.

---

## Example

**Input:**
```
Project Name: Fluxion
Chain: Avalanche
Product Type: DeFi yield aggregator
```

**Output:** Full GTM plan + 4-week campaign calendar + community scripts for Discord/X/Telegram + on-chain retention strategy with wallet tier segmentation.

---

## Skill structure

```
web3-marketing-gtm/
├── SKILL.md                          # Main skill — execution flow, defaults, tone rules
└── references/
    ├── gtm-plan.md                   # GTM launch plan template
    ├── campaign-calendar.md          # 4-week campaign calendar template
    ├── community-scripts.md          # Discord, Telegram, X script library
    └── onchain-retention.md          # Retention strategy & wallet segmentation
```

---

## Tone philosophy

This skill follows an **education-first, selling-never** approach:
- No hype language ("revolutionary", "LFG", "to the moon")
- Specific over vague — real timelines, real metric targets, real actions
- Platform-native — Discord conversational, Telegram direct, X punchy

---

## Versioning

This skill follows [semver](https://semver.org/). See [CHANGELOG.md](./CHANGELOG.md) for release history.

To publish a new version to ClawHub, create a git tag:
```bash
git tag v1.0.0
git push origin v1.0.0
```

The GitHub Action will handle publishing to ClawHub automatically.

---

## License

MIT — free to use, modify, and redistribute.

---

## Author

Built by [Luana Cantu](https://github.com/luacantu) · [BuidlMode](https://x.com/buidlmode)
