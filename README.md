# Telos Block Producer Registration & Rotation for Top 21 BP

### Network

Testnet

### Account

`telosxgotest`


### Block Producer registration 

#### Regproducer command

```shell
cleos -u https://telos-testnet.eosphere.io system regproducer telosxgotest EOS6bT7S7uwCB8nqaEpRtLymm47nvpuvtHHXUgzKL7sFMLjvZknxj https://telos.gofree.pro 8989
```

#### Telos Transaction of regproducer command

Transaction ID: 79eb36789ef4ef043eb4d105e6492cc22e4b031577df754e7e311b469df533d6

https://eosauthority.com/transaction/79eb36789ef4ef043eb4d105e6492cc22e4b031577df754e7e311b469df533d6?network=telostest


Transaction Data:

```
{
  "producer": "telosxgotest",
  "producer_key": "PUB_K1_6bT7S7uwCB8nqaEpRtLymm47nvpuvtHHXUgzKL7sFMLk1Aoyy2",
  "url": "https://telos.gofree.pro",
  "location": 8989
}
```

#### Telos Produce

https://api.telos.net/v1/docs/index.html#/testnet/get_v1_testnet_produce__bpAccount_

BP account to add to rotation = telosxgotest

```
curl -X GET "https://api.telos.net/v1/testnet/produce/telosxgotest" -H "accept: application/json"
```

#### Telos Check Rotation Schedule

##### Way 1

https://api.telos.net/v1/docs/index.html#/testnet/get_v1_testnet_rotation_schedule

```
curl -X GET "https://api.telos.net/v1/testnet/rotation_schedule" -H "accept: application/json")
```
##### Way 2

http://testnet.telos.net/v2/history/get_schedule

```json
{
    "query_time_ms": 98.657,
    "timestamp": "2022-07-07T15:03:24.000",
    "block_num": 181118370,
    "version": 25828,
    "producers": [
        {
            "producer_name": "theteloscrew",
            "block_signing_key": "PUB_K1_7iwV7UbgPGAbJiDNTKzdznrmr3xTurVmRoERSrGveEekzrBc7y",
            "legacy_key": "EOS7iwV7UbgPGAbJiDNTKzdznrmr3xTurVmRoERSrGveEem25FgPt"
        },
        {
            "producer_name": "telosindiabp",
            "block_signing_key": "PUB_K1_7JxMFPmNEULcRtZLSoD8Sst86p137JiWd7xVaoo5JVs8FiSiB1",
            "legacy_key": "EOS7JxMFPmNEULcRtZLSoD8Sst86p137JiWd7xVaoo5JVs8LGkvbD"
        },
        {
            "producer_name": "blockbastrds",
            "block_signing_key": "PUB_K1_7i15hVWpcEMhFisZdiWNJAogjNsDJGDvrqtGYVfPfmHVLj9wCj",
            "legacy_key": "EOS7i15hVWpcEMhFisZdiWNJAogjNsDJGDvrqtGYVfPfmHVN8erEN"
        },
        {
            "producer_name": "bp.yknot",
            "block_signing_key": "PUB_K1_8CuSTRG2c8kxTpmnaGKLSsBG6eBY4kyZrsxoN1yrFrPPLyGGp7",
            "legacy_key": "EOS8CuSTRG2c8kxTpmnaGKLSsBG6eBY4kyZrsxoN1yrFrPPPpm6HL"
        },
        {
            "producer_name": "cryptolions1",
            "block_signing_key": "PUB_K1_7bLioNJeJWTcpXdcK7rLSv54AuQ3wyYHcwi647hBNkZs8Q8ZEf",
            "legacy_key": "EOS7bLioNJeJWTcpXdcK7rLSv54AuQ3wyYHcwi647hBNkZs933NHa"
        },
        {
            "producer_name": "bigirontest1",
            "block_signing_key": "PUB_K1_5ZkoKgXZquq4uGz6D7x46etKuv9FVu4YuLxjwTnXw2ExvevkTR",
            "legacy_key": "EOS5ZkoKgXZquq4uGz6D7x46etKuv9FVu4YuLxjwTnXw2Ey3AWM78"
        },
        {
            "producer_name": "dappetizerbp",
            "block_signing_key": "PUB_K1_8A4j4pCsPZwsCJwNqL8mYZXyGWFgEMuAgkmVtK8JAjujQMxSk7",
            "legacy_key": "EOS8A4j4pCsPZwsCJwNqL8mYZXyGWFgEMuAgkmVtK8JAjujVYxCtX"
        },
        {
            "producer_name": "nation.tlos",
            "block_signing_key": "PUB_K1_6Fat9KYfu22yxWJuwjXeWKhCnFxj4GaCQJ7pwjLwpU8XviGn3q",
            "legacy_key": "EOS6Fat9KYfu22yxWJuwjXeWKhCnFxj4GaCQJ7pwjLwpU8XxVzjyi"
        },
        {
            "producer_name": "telosculture",
            "block_signing_key": "PUB_K1_5fBSwHdojfqEwgbkMbXvA7EWDCfvW67wq8r1Bi5aMMWXUFsMCb",
            "legacy_key": "EOS5fBSwHdojfqEwgbkMbXvA7EWDCfvW67wq8r1Bi5aMMWXW7xrQ5"
        },
        {
            "producer_name": "cryptobloksx",
            "block_signing_key": "PUB_K1_8KedPLLDaMEb842TqSD1f6ibTE2Dv5KmcnJquNKW5mJpNiRwfV",
            "legacy_key": "EOS8KedPLLDaMEb842TqSD1f6ibTE2Dv5KmcnJquNKW5mJpUXiA6r"
        },
        {
            "producer_name": "gbiotestnet1",
            "block_signing_key": "PUB_K1_5i18g3iNRha2mjNAu6QrTwKAigXVDVGLxSg7zXK5tBVdy8E7aw",
            "legacy_key": "EOS5i18g3iNRha2mjNAu6QrTwKAigXVDVGLxSg7zXK5tBVe2Ey93F"
        },
        {
            "producer_name": "kainosblkpro",
            "block_signing_key": "PUB_K1_873Kgzu6hQnxyXFzvP5iDJpmbpxJPgEJvfe5wczNaWLQ57ag6T",
            "legacy_key": "EOS873Kgzu6hQnxyXFzvP5iDJpmbpxJPgEJvfe5wczNaWLQ5W1bVN"
        },
        {
            "producer_name": "nodenodeorg1",
            "block_signing_key": "PUB_K1_4v61yubhr7A7VhB7vGb6CMXCaaucz3w7SKMfYipCD6NPTokVhh",
            "legacy_key": "EOS4v61yubhr7A7VhB7vGb6CMXCaaucz3w7SKMfYipCD6NPZwjknQ"
        },
        {
            "producer_name": "pandabloks",
            "block_signing_key": "PUB_K1_7XDXRX9gton3J37jDke7CbSHghzp5a4KrjfkJKHxXR1MLUwoVq",
            "legacy_key": "EOS7XDXRX9gton3J37jDke7CbSHghzp5a4KrjfkJKHxXR1MRyxNVH"
        },
        {
            "producer_name": "bp.boid",
            "block_signing_key": "PUB_K1_7c9DJqf55QgPFkawXAy7xe1Z2ok9e97AiKGJt2DaUWQ1s7Lw6o",
            "legacy_key": "EOS7c9DJqf55QgPFkawXAy7xe1Z2ok9e97AiKGJt2DaUWQ1sax6e8"
        },
        {
            "producer_name": "telosuknodes",
            "block_signing_key": "PUB_K1_7Ffjbj2vQ64YkBieyB5qMUcv4MQze2YzNypsq6uCQYT6fVaxiK",
            "legacy_key": "EOS7Ffjbj2vQ64YkBieyB5qMUcv4MQze2YzNypsq6uCQYT6iHovCb"
        },
        {
            "producer_name": "telosarabia1",
            "block_signing_key": "PUB_K1_7joDqL9aJbRWJZJgZxkSobxWwMJke3Ku2a9ssxaBv2RxZCbGYX",
            "legacy_key": "EOS7joDqL9aJbRWJZJgZxkSobxWwMJke3Ku2a9ssxaBv2Rxcf2cPp"
        },
        {
            "producer_name": "amsterdam",
            "block_signing_key": "PUB_K1_5czbkWLVZR4nb1YwrJfNWdyC8hdeTXgX2fP73bbxmz3Rn9jfLj",
            "legacy_key": "EOS5czbkWLVZR4nb1YwrJfNWdyC8hdeTXgX2fP73bbxmz3RrniMHV"
        },
        {
            "producer_name": "votedutcheos",
            "block_signing_key": "PUB_K1_7LcjYvZRUoVeupeYCyKyVYh7ZH3xPfD6kvsc4P5Gi1BmNe1CJj",
            "legacy_key": "EOS7LcjYvZRUoVeupeYCyKyVYh7ZH3xPfD6kvsc4P5Gi1BmQWFty5"
        },
        {
            "producer_name": "telosdacnode",
            "block_signing_key": "PUB_K1_7d8q5VabCyECzn21iEh8zeciPBXyZjGKXJ76DtwecUFMxUxUsy",
            "legacy_key": "EOS7d8q5VabCyECzn21iEh8zeciPBXyZjGKXJ76DtwecUFMyoGnFT"
        },
        {
            "producer_name": "telosxgotest",
            "block_signing_key": "PUB_K1_6bT7S7uwCB8nqaEpRtLymm47nvpuvtHHXUgzKL7sFMLjuWRutK",
            "legacy_key": "EOS6bT7S7uwCB8nqaEpRtLymm47nvpuvtHHXUgzKL7sFMLjvZknxj"
        }
    ]
}
```

https://telos.gofree.pro/

https://telos.gofree.pro/bp.json

```json
{
    "producer_account_name": "",
    "org": {
        "candidate_name": "",
        "website": "",
        "code_of_conduct": "",
        "ownership_disclosure": "",
        "email": "",
        "github_user": "",
        "chain_resources": "",
        "other_resources": [],
        "branding": {
            "logo_256": "",
            "logo_1024": "",
            "logo_svg": ""
        },
        "location": {
            "name": "",
            "country": "",
            "latitude": 0,
            "longitude": 0
        },
        "social": {
            "keybase": "",
            "telegram": "",
            "twitter": "",
            "github": "",
            "youtube": "",
            "facebook": "",
            "hive": "",
            "reddit": "",
            "wechat": ""
        }
    },
    "nodes": [
        {
            "location": {
                "name": "",
                "country": "",
                "latitude": 0,
                "longitude": 0
            },
            "full": false,
            "node_type": "producer",
            "p2p_endpoint": "",
            "api_endpoint": "",
            "ssl_endpoint": ""
        },
        {
            "location": {
                "name": "",
                "country": "",
                "latitude": 0,
                "longitude": 0
            },
            "full": true,
            "node_type": "seed",
            "p2p_endpoint": "",
            "api_endpoint": "",
            "ssl_endpoint": ""
        },
        {
            "location": {
                "name": "",
                "country": "",
                "latitude": 0,
                "longitude": 0
            },
            "full": true,
            "node_type": "query",
            "p2p_endpoint": "",
            "api_endpoint": "",
            "ssl_endpoint": "",
            "features": [
                "chain_api"
            ]
        }
    ]
}
```


https://api.telostest.gofree.pro/

```json
{
    "server_version": "26a4d285",
    "chain_id": "1eaa0824707c8c16bd25145493bf062aecddfeb56c736f6ba6397f3195f33c9f",
    "head_block_num": 181112414,
    "last_irreversible_block_num": 181112088,
    "last_irreversible_block_id": "0acb8d181cb6abc4b6d388984e9a1220bc13f4ee79015098c00a6d241722aeaf",
    "head_block_id": "0acb8e5e9758941f5546021b697a1451a4a0af8018f4a0f5b63676323f712acc",
    "head_block_time": "2022-07-07T14:13:43.000",
    "head_block_producer": "blockbastrds",
    "virtual_block_cpu_limit": 200000000,
    "virtual_block_net_limit": 1048576000,
    "block_cpu_limit": 199900,
    "block_net_limit": 1048576,
    "server_version_string": "v2.1.0",
    "fork_db_head_block_num": 181112414,
    "fork_db_head_block_id": "0acb8e5e9758941f5546021b697a1451a4a0af8018f4a0f5b63676323f712acc",
    "server_full_version_string": "v2.1.0-26a4d285d0be1052d962149e431eb81500782991",
    "last_irreversible_block_time": "2022-07-07T14:10:59.500"
}
```

### Known resources

https://app.telos.net/testnet/rotation

https://eosauthority.com/?network=telostest


