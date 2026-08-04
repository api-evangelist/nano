# Nano

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
