# API Endpoints

## API Status

This endpoint retrieves the API endpoint status.

{% swagger src="../.gitbook/assets/openapi_collection.yml" path="/p/ping" method="get" %}
[openapi_collection.yml](../.gitbook/assets/openapi_collection.yml)
{% endswagger %}

***

## Supported Chains

This endpoint retrieves the list of supported crypto networks.

{% swagger src="../.gitbook/assets/openapi_collection.yml" path="/p/chain/list" method="get" %}
[openapi_collection.yml](../.gitbook/assets/openapi_collection.yml)
{% endswagger %}

***

## Token Balances

This endpoint retrieves the wallet token balances

{% swagger src="../.gitbook/assets/openapi_collection.yml" path="/p/balance/token/list" method="get" %}
[openapi_collection.yml](../.gitbook/assets/openapi_collection.yml)
{% endswagger %}

***

## DeFi Portfolio Positions

This endpoint retrieves the DeFi position of a specific wallet

{% swagger src="../.gitbook/assets/openapi_collection.yml" path="/p/balance/defi-position/list" method="get" %}
[openapi_collection.yml](../.gitbook/assets/openapi_collection.yml)
{% endswagger %}

***

## Wallet Transactions

This endpoints retrieves the transaction history of a specific wallet

{% swagger src="../.gitbook/assets/openapi_collection.yml" path="/p/transaction/list" method="get" %}
[openapi_collection.yml](../.gitbook/assets/openapi_collection.yml)
{% endswagger %}

