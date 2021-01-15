# Total Volume and Liquidity

<hr>

Endpoint `GET /api/total-volume-liquidity/`

| Parameter     | Description        |
| -----------   | -----------        | 
| blockchain    | Blockchain name    |

Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/total-volume-liquidity/?blockchain=Tron```<br>
Response:
```
[
    {
        "datetime": "2021-01-08",
        "blockchain": "Tron",
        "liquidity": "477103.87080234004",
        "volume": "27357.84099199856"
    },
    {
        "datetime": "2021-01-09",
        "blockchain": "Tron",
        "liquidity": "534032.4774134799",
        "volume": "9893.330604148287"
    },
    {
        "datetime": "2021-01-10",
        "blockchain": "Tron",
        "liquidity": "504145.66731176997",
        "volume": "10063.582271850983"
    },
    {
        "datetime": "2021-01-11",
        "blockchain": "Tron",
        "liquidity": "447441.5838297001",
        "volume": "8924.637704482973"
    },
    {
        "datetime": "2021-01-12",
        "blockchain": "Tron",
        "liquidity": "446188.76798518",
        "volume": "3564.184480485333"
    },
    {
        "datetime": "2021-01-13",
        "blockchain": "Tron",
        "liquidity": "462752.1685596601",
        "volume": "8876.958822521816"
    },
    {
        "datetime": "2021-01-14",
        "blockchain": "Tron",
        "liquidity": "472199.0167375599",
        "volume": "1672.292931642252"
    }
]
```