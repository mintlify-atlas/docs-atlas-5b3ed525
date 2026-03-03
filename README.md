# Caddy Defender Documentation

This repository contains the documentation for Caddy Defender, a powerful middleware plugin for Caddy that allows you to block or manipulate requests based on IP addresses.

## Features

- Block or manipulate requests from specific IP ranges
- Predefined IP ranges for AI services (OpenAI, DeepSeek, GitHub Copilot)
- Multiple response strategies (block, custom, drop, garbage, redirect, tarpit, rate-limit)
- Support for custom CIDR ranges and whitelist functionality
- High-performance IP matching using Balanced ART routing table

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the following command at the root of the documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing Changes

Changes pushed to the main branch are automatically deployed to production.

## Links

- [GitHub Repository](https://github.com/JasonLovesDoggo/caddy-defender)
- [Mintlify Documentation](https://mintlify.com/docs)
