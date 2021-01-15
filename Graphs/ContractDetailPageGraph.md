# Detail page Graphs

<hr>

Endpoint ```GET /api/liquidity-graph-info/``` <br>

| Parameter     | Description        |
| -----------   | -----------        | 
| contract    | Contract Address     |

Example API call: ```curl -X GET -H 'Accept: application/json; indent=4' https://data.unifi.report/api/liquidity-graph-info/?contract=TU2FCnCEaZChdVsifYQmL9WpNoCwDqXACJ```<br>
Response:
```
[
    {
        "datetime": "2021-01-08",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "24195.306728",
        "liquidity_b": "41625.27274",
        "liquidity_a_usd": "1269.6763704750686",
        "liquidity_b_usd": "1269.6765467627597",
        "liquidity_total": "65820.579468",
        "liquidity_total_usd": "2539.3529172378285",
        "buy_volume_usd": "10.487277895695335",
        "sell_volume_usd": "0.0",
        "total_volume_usd": "10.487277895695335"
    },
    {
        "datetime": "2021-01-09",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "24195.306728",
        "liquidity_b": "41625.27274",
        "liquidity_a_usd": "1432.0190741479369",
        "liquidity_b_usd": "1432.0192729760336",
        "liquidity_total": "65820.579468",
        "liquidity_total_usd": "2864.0383471239707",
        "buy_volume_usd": "0.0",
        "sell_volume_usd": "0.0",
        "total_volume_usd": "0.0"
    },
    {
        "datetime": "2021-01-10",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "23803.606596",
        "liquidity_b": "42309.385843",
        "liquidity_a_usd": "1398.4031587593113",
        "liquidity_b_usd": "1398.403897568818",
        "liquidity_total": "66112.992439",
        "liquidity_total_usd": "2796.8070563281294",
        "buy_volume_usd": "51.61324514662071",
        "sell_volume_usd": "28.601828802372918",
        "total_volume_usd": "80.21507394899363"
    },
    {
        "datetime": "2021-01-11",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "23803.606596",
        "liquidity_b": "42309.385843",
        "liquidity_a_usd": "1214.6971717668039",
        "liquidity_b_usd": "1214.697813520087",
        "liquidity_total": "66112.992439",
        "liquidity_total_usd": "2429.394985286891",
        "buy_volume_usd": "0.0",
        "sell_volume_usd": "0.0",
        "total_volume_usd": "0.0"
    },
    {
        "datetime": "2021-01-12",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "24328.321023",
        "liquidity_b": "41395.636644",
        "liquidity_a_usd": "1183.899450157819",
        "liquidity_b_usd": "1183.8994776764753",
        "liquidity_total": "65723.957667",
        "liquidity_total_usd": "2367.7989278342943",
        "buy_volume_usd": "8.555469578081667",
        "sell_volume_usd": "34.08987127509495",
        "total_volume_usd": "42.64534085317662"
    },
    {
        "datetime": "2021-01-13",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "25033.818067",
        "liquidity_b": "40227.770154",
        "liquidity_a_usd": "1202.6843653281953",
        "liquidity_b_usd": "1202.6844146840178",
        "liquidity_total": "65261.588221",
        "liquidity_total_usd": "2405.3687800122134",
        "buy_volume_usd": "0.0",
        "sell_volume_usd": "36.65440658737242",
        "total_volume_usd": "36.65440658737242"
    },
    {
        "datetime": "2021-01-14",
        "smart_contract": "TS7NC6BKsFwbkJk7TZZS636YNJWuRvBDg9",
        "liquidity_a": "25911.152568",
        "liquidity_b": "38864.322359",
        "liquidity_a_usd": "1176.3595907651772",
        "liquidity_b_usd": "1176.3596889614848",
        "liquidity_total": "64775.474927",
        "liquidity_total_usd": "2352.719279726662",
        "buy_volume_usd": "0.0",
        "sell_volume_usd": "74.46893195151823",
        "total_volume_usd": "74.46893195151823"
    }
]
```