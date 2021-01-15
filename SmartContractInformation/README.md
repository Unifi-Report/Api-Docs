# List Smart Contracts (Data of today)

<hr>

Endpoint `GET /api/smart-contract-balances/`

| Parameter     | Description        |
| -----------   | -----------        | 
| blockchain    | Blockchain name    |
| contract      | Contract Address   |
| pair          | Swap pair          |
| sort          | Sort by volume, liquidity, price or blockchain |

| sort parameter options | description | 
| ---- | --- | 
| volume | Sorts by volume |
| volume_desc | Sorts by descending volume | 
| liquidity | Sorts by liquidity |
| liquidity_desc | Sorts by descending liquidity | 
| price | Sorts by price |
| price_desc | Sorts by descending price | 
| blockchain | Sorts by blockchain |
| blockchain_desc | Sorts by descending blockchain | 


Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/smart-contract-balances/?contract=TUxqQp2qXUx7hT2F6Zx4hy85n8o9L9bzM9```<br>
Response:
```

{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "datetime": "2021-01-14",
            "icon": "https://icon-service.unifi.report/icon_trc20?token=TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
            "nativeIcon": "https://icon-service.unifi.report/icon_trc20?token=trx",
            "token_a": "UP",
            "liquidity_a": "71238.37",
            "token_b": "TRX",
            "liquidity_b": "1822422.25",
            "total_liquidity": "111711.48",
            "price_native_token": "0.79616681",
            "token_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
            "contract_address": "TUxqQp2qXUx7hT2F6Zx4hy85n8o9L9bzM9",
            "trading_pair": "UP-TRX",
            "blockchain": "Tron",
            "native_token_price_usd": "0.03017624",
            "volume": "275.3",
            "volume_usd": "219.18",
            "link": "https://tronscan.org/#/contract/TUxqQp2qXUx7hT2F6Zx4hy85n8o9L9bzM9/code",
            "liquidity_change_percentage": "0.94",
            "volume_change_percentage": "-89.11",
            "volume_usd_change_percentage": "-89.01",
            "price_change": "0.91",
            "transaction_count": "23",
            "transaction_change_percentage": "-25.81"
        }
    ]
}
```