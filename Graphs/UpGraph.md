# Up Graph data

<hr>

Endpoint ```GET /api/up-graph/``` <br>

| Parameter     | Description        |
| -----------   | -----------        | 
| blockchain    | Blockchain name    |

Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/up-graph/?blockchain=Tron```<br>
Response:
```

[
    {
        "datetime": "2021-01-01",
        "unix_time": "1609542020",
        "redeem_value": "9.418377",
        "redeem_value_usd": "0.25380811870386",
        "market_price": "27.710213",
        "market_price_usd": "0.74673980776234",
        "total_supply": "682816.143402",
        "total_supply_usd": "18400.652339302906",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-02",
        "unix_time": "1609628407",
        "redeem_value": "9.419755",
        "redeem_value_usd": "0.2556922788563",
        "market_price": "26.175099",
        "market_price_usd": "0.71050369278174",
        "total_supply": "683045.244517",
        "total_supply_usd": "18540.757708933023",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-03",
        "unix_time": "1609714828",
        "redeem_value": "9.421512",
        "redeem_value_usd": "0.27779243338392",
        "market_price": "26.183596",
        "market_price_usd": "0.7720209715363601",
        "total_supply": "683342.648795",
        "total_supply_usd": "20148.296498882184",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-04",
        "unix_time": "1609801257",
        "redeem_value": "9.424321",
        "redeem_value_usd": "0.28812938896016005",
        "market_price": "26.163639",
        "market_price_usd": "0.79989988860144",
        "total_supply": "683314.190292",
        "total_supply_usd": "20890.937407229703",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-05",
        "unix_time": "1609887641",
        "redeem_value": "9.42711",
        "redeem_value_usd": "0.27307386984570003",
        "market_price": "26.051078",
        "market_price_usd": "0.7546181897858599",
        "total_supply": "683775.756046",
        "total_supply_usd": "19806.843434536197",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-06",
        "unix_time": "1609974055",
        "redeem_value": "10.37812",
        "redeem_value_usd": "0.31713687414639996",
        "market_price": "25.471929",
        "market_price_usd": "0.7783768102063799",
        "total_supply": "621425.741729",
        "total_supply_usd": "18989.66452941796",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-07",
        "unix_time": "1610060417",
        "redeem_value": "10.383127",
        "redeem_value_usd": "0.32853480569494",
        "market_price": "28.135407",
        "market_price_usd": "0.89023860267654",
        "total_supply": "621815.129259",
        "total_supply_usd": "19674.989304212453",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-08",
        "unix_time": "1610146820",
        "redeem_value": "10.392088",
        "redeem_value_usd": "0.3147664730364",
        "market_price": "28.184995",
        "market_price_usd": "0.8536967228047501",
        "total_supply": "623068.043147",
        "total_supply_usd": "18872.139112281642",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-09",
        "unix_time": "1610233234",
        "redeem_value": "10.39473",
        "redeem_value_usd": "0.355153621491",
        "market_price": "29.55051",
        "market_price_usd": "1.009643410017",
        "total_supply": "623382.367621",
        "total_supply_usd": "21298.918339796423",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-10",
        "unix_time": "1610319694",
        "redeem_value": "10.397785",
        "redeem_value_usd": "0.3413730066262",
        "market_price": "27.398566",
        "market_price_usd": "0.8995310878871199",
        "total_supply": "623809.953484",
        "total_supply_usd": "20480.504202018317",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-11",
        "unix_time": "1610406064",
        "redeem_value": "10.40057",
        "redeem_value_usd": "0.2959422910251",
        "market_price": "27.865776",
        "market_price_usd": "0.79290477258768",
        "total_supply": "624199.777717",
        "total_supply_usd": "17761.248881063937",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-12",
        "unix_time": "1610492424",
        "redeem_value": "10.401892",
        "redeem_value_usd": "0.29842549660968",
        "market_price": "27.668539",
        "market_price_usd": "0.79379765638206",
        "total_supply": "624385.047827",
        "total_supply_usd": "17913.31980503463",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-13",
        "unix_time": "1610578855",
        "redeem_value": "10.408137",
        "redeem_value_usd": "0.31038896366112",
        "market_price": "26.390877",
        "market_price_usd": "0.78702240008352",
        "total_supply": "625260.006027",
        "total_supply_usd": "18646.353837335748",
        "blockchain": "Tron"
    },
    {
        "datetime": "2021-01-14",
        "unix_time": "1610640017",
        "redeem_value": "10.41071",
        "redeem_value_usd": "0.3142518620624",
        "market_price": "26.383897",
        "market_price_usd": "0.7964095398596801",
        "total_supply": "625620.758645",
        "total_supply_usd": "18884.63787283313",
        "blockchain": "Tron"
    }
]
```