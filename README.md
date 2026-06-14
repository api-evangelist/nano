# Nano

Nano is a feeless, instant digital currency built on a block-lattice architecture. It provides a JSON-RPC HTTP API for querying accounts, retrieving block information, managing wallets, processing transactions, and interacting with the Nano network. Each account maintains its own blockchain, enabling fast consensus without mining and with zero transaction fees.

## API Overview

The Nano RPC API accepts JSON HTTP POST requests. Developers run their own Nano nodes and interact with the local RPC server (default port 7076). The API is organized into the following categories:

- **Account Operations** - Query balances, history, representatives, and voting weight
- **Block Operations** - Create, query, publish, and confirm blocks; generate proof-of-work
- **Node Operations** - Bootstrap, peer management, telemetry, statistics, and network diagnostics
- **Wallet Operations** - Manage local wallets, send and receive funds (development/testing)
- **Unit Conversion** - Convert between Nano and raw denomination units

## Resources

- [Website](https://nano.org)
- [Documentation](https://docs.nano.org)
- [RPC Protocol Reference](https://docs.nano.org/commands/rpc-protocol/)
- [Integration Guides](https://docs.nano.org/integration-guides/)
- [Living Whitepaper](https://docs.nano.org/living-whitepaper/)
- [Developer Tools](https://hub.nano.org/developer-tools)
- [GitHub](https://github.com/nanocurrency)
- [Release Notes](https://docs.nano.org/releases/current-release-notes/)

## Contact

- Developer Support: integrations@nano.org
- Developer Hub: https://nano.org/en/developers

## Maintainer

[API Evangelist](https://apievangelist.com)
