# Account Page Graph data

<hr>

Endpoint `GET /api/account-page-graph/`

| Parameter     | Description        |
| -----------   | -----------        | 
| blockchain    | Blockchain name    |

Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/account-page-graph/?blockchain=Tron```<br>
Response:

```
[
    {
        "date": "2021-01-04",
        "blockchain": "Tron",
        "blockchain_active_traders": "69",
        "blockchain_total_traders": "989"
    },
    {
        "date": "2021-01-05",
        "blockchain": "Tron",
        "blockchain_active_traders": "53",
        "blockchain_total_traders": "991"
    },
    {
        "date": "2021-01-06",
        "blockchain": "Tron",
        "blockchain_active_traders": "53",
        "blockchain_total_traders": "997"
    },
    {
        "date": "2021-01-07",
        "blockchain": "Tron",
        "blockchain_active_traders": "60",
        "blockchain_total_traders": "1005"
    },
    {
        "date": "2021-01-08",
        "blockchain": "Tron",
        "blockchain_active_traders": "67",
        "blockchain_total_traders": "1009"
    },
    {
        "date": "2021-01-09",
        "blockchain": "Tron",
        "blockchain_active_traders": "65",
        "blockchain_total_traders": "1013"
    },
    {
        "date": "2021-01-10",
        "blockchain": "Tron",
        "blockchain_active_traders": "53",
        "blockchain_total_traders": "1016"
    },
    {
        "date": "2021-01-11",
        "blockchain": "Tron",
        "blockchain_active_traders": "52",
        "blockchain_total_traders": "1020"
    },
    {
        "date": "2021-01-12",
        "blockchain": "Tron",
        "blockchain_active_traders": "56",
        "blockchain_total_traders": "1026"
    },
    {
        "date": "2021-01-13",
        "blockchain": "Tron",
        "blockchain_active_traders": "49",
        "blockchain_total_traders": "1027"
    },
    {
        "date": "2021-01-14",
        "blockchain": "Tron",
        "blockchain_active_traders": "43",
        "blockchain_total_traders": "1031"
    }
]
```