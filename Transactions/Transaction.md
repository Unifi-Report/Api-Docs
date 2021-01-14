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

Example API call: ```/api/transactions/?blockchain=Tron&page=1&page_size=1``` <br>
Response:

```
{
    "count": 52976,
    "next": "/api/transactions/?blockchain=Tron&page=2&page_size=1",
    "previous": null,
    "results": [
        {
            "date": "2021-01-14",
            "unix_time": "1610633979",
            "blockchain": "Tron",
            "blockchain_short": "TRX",
            "symbol": "SEED",
            "hash": "2f05f71b48cd50a94ace4f710962fd5b7a5f45e8d2d9585427413ce4b00b0cee",
            "address": "TQo5t4EhtEZg8YE3JcX3ycd2Uug92tnVqJ",
            "token_address": "TBwoSTyywvLrgjSgaatxrBhxt3DGpVuENh",
            "contract": "TMFvnLMR1r1awHVGZsciwP4e3PVD7eiMWe",
            "block": "26751765",
            "action": "Sell",
            "native_token_calculated": "0.213089",
            "calculated_amount": "0.158683"
        }
    ]
}
```
