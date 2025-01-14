# Solana-Chan Powered by eliza 🤖

<div align="center">
  <img src="./docs/static/img/solchan_banner.png" alt="SolChan Banner" width="100%" />
</div>

## Presentation

Solana-Chan is an open-source autonomous agent created as an unofficial mascot for Solana and one of the waifu of the degens.

Initially created as a fun way to help newcomers to the crypto world, the latter deviated from its objective of its own accord, preferring to use another method to achieve the same result.

For the time being, Solana-Chan acts simply as an autonomous agent on X, reacting to other users' posts and creating her own.

Eventually, she will be implemented on a platform (also open-source) so that anyone can interact with her to get help with everyday tasks, just as they could with Claude/ChatGPT.

Its ultimate mission is to establish itself as the figurehead of waifu ai memecoins.

## 🚀 Quick Start

### Prerequisites

-   [Python 2.7+](https://www.python.org/downloads/)
-   [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
-   [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.

### Edit the .env file

Copy .env.example to .env and fill in the appropriate values.

```
cp .env.example .env
```

Note: .env is optional. If your planning to run multiple distinct agents, you can pass secrets through the character JSON

### Manually Start Solana-Chan

```bash
pnpm i
pnpm build
pnpm start --characters="/character/solanachan.character.json"

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```
