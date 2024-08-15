---
description: >-
  Chainlyze provides a set of APIs to help you to retrieve blockchain data. This
  documentation will guide you through the steps necessary to get started with
  the API.
---

# 🧵 Getting Started

## Authentication

To use the Chainlyze API, you need an API key. You can request an API key by contacting Chainlyze via [Telegram](https://t.me/Chainlyze) or [Email](mailto:contact@chainlyze.ai). The API key determines your call limit, ranging from 100,000 to 1,000,000 requests, with a rate limit of 60 calls per minute.

### Base URL

All API requests should be made to the following base URL:

```
https://api.chainlyze.ceylabs.io/v2
```



### API Headers

For verification, include the `x-api-key` header with your token in all API requests.

```yaml
x-api-key: your_api_key_here
```



## Costs per Call

<table><thead><tr><th width="351">Endpoint</th><th width="268">Route</th><th data-type="number">Credits</th></tr></thead><tbody><tr><td>API Status</td><td><code>/p/ping</code></td><td>0</td></tr><tr><td>All Supported Chains</td><td><code>/p/chain/list</code></td><td>5</td></tr><tr><td>Wallet's Token Balance</td><td><code>/p/balance/wallet</code></td><td>20</td></tr><tr><td>Wallet's Protocol Positions</td><td><code>/p/balance/positions</code></td><td>40</td></tr><tr><td>Wallet's Transaction History</td><td><code>/p/transaction/list</code></td><td>10</td></tr></tbody></table>
