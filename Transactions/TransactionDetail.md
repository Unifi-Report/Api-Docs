# Detail transaction

<hr>

Endpoint `GET /api/transaction-detail/`

| Parameter     | Description        | Required |
| -----------   | -----------        | :---: |
| hash          | Transaction hash   |  :heavy_check_mark: |

Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/transaction-detail/?hash=2f05f71b48cd50a94ace4f710962fd5b7a5f45e8d2d9585427413ce4b00b0cee``` <br>
Response: 
```
[
    {
        "date": "2021-01-14",
        "unix_time": "1610626419",
        "blockchain": "Tron",
        "blockchain_short": "TRX",
        "symbol": "SEED",
        "hash": "0fd953483cdd5735f33e95c3c7971394b66ff71e478c2c76bd7ef5f189a8b8ba",
        "address": "TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ",
        "token_address": "TBwoSTyywvLrgjSgaatxrBhxt3DGpVuENh",
        "network_fee": "201186",
        "contract": "TMFvnLMR1r1awHVGZsciwP4e3PVD7eiMWe",
        "block": "26749248",
        "action": "Sell",
        "native_token_calculated": "1.362085",
        "calculated_amount": "1.014331",
        "subtransactions": [
            {
                "from_address": "TMFvnLMR1r1awHVGZsciwP4e3PVD7eiMWe",
                "to_address": "TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ",
                "contract_address": "TBwoSTyywvLrgjSgaatxrBhxt3DGpVuENh",
                "calculated_amount": "1.014331",
                "token": "SEED"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TMFvnLMR1r1awHVGZsciwP4e3PVD7eiMWe",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.000457",
                "token": "UP"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TB5wAYNuMqM92aoRQbvNmDmJaNtq8wLy3v",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.000457",
                "token": "UP"
            },
            {
                "from_address": "TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ",
                "to_address": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
                "contract_address": "THXm85dwyCSTNPq8h1JDPth2vuTcwtXyBb",
                "calculated_amount": "877.334501",
                "token": "SOUL"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.457926",
                "token": "UP"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TB5wAYNuMqM92aoRQbvNmDmJaNtq8wLy3v",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.457926",
                "token": "UP"
            }
        ]
    },
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
        "calculated_amount": "877.334501",
        "subtransactions": [
            {
                "from_address": "TMFvnLMR1r1awHVGZsciwP4e3PVD7eiMWe",
                "to_address": "TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ",
                "contract_address": "TBwoSTyywvLrgjSgaatxrBhxt3DGpVuENh",
                "calculated_amount": "1.014331",
                "token": "SEED"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TMFvnLMR1r1awHVGZsciwP4e3PVD7eiMWe",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.000457",
                "token": "UP"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TB5wAYNuMqM92aoRQbvNmDmJaNtq8wLy3v",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.000457",
                "token": "UP"
            },
            {
                "from_address": "TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ",
                "to_address": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
                "contract_address": "THXm85dwyCSTNPq8h1JDPth2vuTcwtXyBb",
                "calculated_amount": "877.334501",
                "token": "SOUL"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.457926",
                "token": "UP"
            },
            {
                "from_address": "T9yD14Nj9j7xAB4dbGeiX9h8unkKHxuWwb",
                "to_address": "TB5wAYNuMqM92aoRQbvNmDmJaNtq8wLy3v",
                "contract_address": "TJ93jQZibdB3sriHYb5nNwjgkPPAcFR7ty",
                "calculated_amount": "0.457926",
                "token": "UP"
            }
        ]
    }
]
```