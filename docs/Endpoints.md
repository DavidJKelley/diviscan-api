Example results

# info

```json
{
    "result": {
        "version": 3000600,
        "protocolversion": 70912,
        "walletversion": 61000,
        "balance": 11999800.99966137,
        "zerocoinbalance": 0,
        "blocks": 47491,
        "timeoffset": -1,
        "connections": 6,
        "proxy": "",
        "difficulty": 0.00121325,
        "testnet": false,
        "moneysupply": 2534368189.992846,
        "zDIVsupply": {
            "1": 0,
            "5": 0,
            "10": 0,
            "50": 0,
            "100": 0,
            "500": 0,
            "1000": 0,
            "5000": 0,
            "total": 0
        },
        "keypoololdest": 1526425609,
        "keypoolsize": 1001,
        "paytxfee": 0,
        "relayfee": 0.0001,
        "staking status": "Staking Not Active",
        "errors": ""
    },
    "error": null,
    "id": 28400
}
```

# tx
```json
{
    "result": {
        "amount": -100,
        "fee": -0.00002259,
        "confirmations": 2096,
        "bcconfirmations": 2096,
        "blockhash": "0000017fab9ce62e889d91a2a5ed3adf9468791cb217969428b41f171034485a",
        "blockindex": 1,
        "blocktime": 1529428616,
        "txid": "a302ef3f4d586cd4b6c894784f72d0332462d627c5d1fd2ffbe98aedddd47e9f",
        "walletconflicts": [],
        "time": 1529428441,
        "timereceived": 1529428441,
        "details": [
            {
                "account": "",
                "address": "DQ3eZ2jRdxzWMPVUWrUaXZvkjkPg1ddUjd",
                "category": "send",
                "amount": -100,
                "vout": 1,
                "fee": -0.00002259
            }
        ],
        "hex": "0100000001262b988ef46fa828e4b299b3feca6e38260a21e71780d2d0c0b0e98847d3e5d0000000006a4730440220410acf211c94984519d41ef30c1713daa0dbeb8c260f54d0b075aa08230a3898022046471be55aebda0a65b94d377482f64f9c7965ad37996d475438d64e9934f07101210259ceffbf87d852f7e38941ed5a341d462bb5e71bf49a80edefa322595d3e2b7fffffffff0259c65aa6130900001976a9140897ffdd3f76081242a5edaed5eb43de8ec7972188ac00e40b54020000001976a914cf629e13d3e054f8ef1d4c7b6eae6f2f96b4e15788ac00000000"
    },
    "error": null,
    "id": 68915
}
```

# getreceived
```json
{
    "result": 15000000,
    "error": null,
    "id": 69135
}
```

# listreceived
```json
{
    "result": [
        {
            "address": "DBzaSo2RFNLvLRjgfbYyAywX5efcycwwiF",
            "account": "api",
            "amount": 15000000,
            "confirmations": 18629,
            "bcconfirmations": 18629,
            "txids": [
                "06a03d135ba8eb2c6fa5b5c76a670b37febc5882e47733afa873b4f5eda1d0e8",
                "edbb6be02e1252c3393fdfe5538d6c40f56c2214e6a3f0052ee67c9c52c9d7a1"
            ]
        },
        {
            "address": "D7JjFuw1n1HtpdfbGuEuXSUQiUnQQVzbJc",
            "account": "beta-two",
            "amount": 15000000,
            "confirmations": 48053,
            "bcconfirmations": 48053,
            "txids": [
                "a5da0432c646da138c739829e11acfa62e8555f7435204d9689d98e2f9e8ceb8"
            ]
        },
        {
            "address": "DTaqHUjKUSDe2SsiwgBUsisQUx5no9U298",
            "account": "alloc->remotenode",
            "amount": 10000000,
            "confirmations": 18626,
            "bcconfirmations": 18626,
            "txids": [
                "5984c3b065a983c8f15017d58892e17a52a010fe09d98b71740f88e69f05d0a5"
            ]
        }
    ],
    "error": null,
    "id": 35281
}
```