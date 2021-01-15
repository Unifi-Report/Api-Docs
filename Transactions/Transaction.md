# List Transactions

<hr>

Endpoint `GET /api/transactions/`

| Parameter     | Description        |  
| -----------   | -----------        |
| page          | Page number        |
| page_size     | Page size up to 50 |
| contract      | Contract Address   |
| user_account  | User Address       |
| blockchain    | Blockchain name    |
| hash          | Transaction Hash   |

Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/transactions/?blockchain=Tron``` <br>
Response:

```
{
    "count": 52976,
    "next": "/api/transactions/?blockchain=Tron&page=2&page_size=1",
    "previous": null,
    "results": [
        {
            "date": "2021-01-14",
            "unix_time": "1610626419",
            "blockchain": "Tron",
            "blockchain_short": "TRX",
            "symbol": "SOUL",
            "hash": "0fd953483cdd5735f33e95c3c7971394b66ff71e478c2c76bd7ef5f189a8b8ba",
            "address": "TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ",
            "token_address": "THXm85dwyCSTNPq8h1JDPth2vuTcwtXyBb",
            "network_fee": "201186",
            "contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
            "block": "26749248",
            "action": "Sell",
            "native_token_calculated": "1348.464853",
            "calculated_amount": "877.334501"
        },
    ]
}
```
