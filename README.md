# Netpractice 42Bangkok

## About

## Guide
read my full guide in google slide
[Netpractice 42Bangkok guide]

## My learning resource


## Concept
1. Client ip do not overlap to other
2. Switch need to connect client in same subnet
3. Router can connect between subnet
4. route table is configured from source ip to destination with CIDR (0.0.0.0/0)
5. Private ip do not access internet
    - from `10.0.0.0` to `10.255.255.255`
    - from `172.16.0.0` to `172.31.255.255`
    - from `192.168.0.0` to `192.168.255.255`
6. Do not set local ip
    - from `127.0.0.1` to `127.255.255.254`

## Step to solve problem
1. Check CIDR or Subnet mask
2. Check specific client ip that is assigned
3. calculate available ip range in subnet
4. Config route table follow by problem goals

## How to pass the evaluation

1. Memorize CIDR table
2. Practice level 6 to 10 from thinking to muscle memory

## CIDR Sheet table

|     | Address |  Host |     Netmask     |
|-----|:-------:|:-----:|:---------------:|
| /30 |    4    |    2  | 255.255.255.252 |
| /29 |    8    |    6  | 255.255.255.248 |
| /28 |   16    |   14  | 255.255.255.240 |
| /27 |   32    |   30  | 255.255.255.224 |
| /26 |   64    |   62  | 255.255.255.192 |
| /25 |  128    |  126  | 255.255.255.128 |
| /24 |  256    |  254  | 255.255.255.0   |
| /18 |  16384  | 16382 | 255.255.192.0   |
| /16 |  65536  | 65534 | 255.255.0.0     |


---

## Challenge ya self

I would like to provide a hint for every level

### Levels
<dl>
<details>
<summary>Level 6</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/level6hint.png" alt="hint-level-6">
</details>

<details>
<summary>Level 7</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/level7hint.png" alt="hint-level-7">
</details>

<details>
<summary>Level 8</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/level8hint.png" alt="hint-level-8">
</details>

<details>
<summary>Level 9</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/level9hint.png" alt="hint-level-9">
</details>

<details>
<summary>Level 10</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/level10hint.png" alt="hint-level-10">
</details>
</dl>

<div style="width: 50%; min-width: 480px">
    <img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/woff-tifa-burn.gif" alt="burn-ya-point">
</div>

<!-- Link -->
[Netpractice 42Bangkok guide]: https://https://docs.google.com/presentation/d/e/2PACX-1vSHNDVR-drtwoUsNS-kfkYPyMKcTXB4X2i4kHyJlbCmz9thSo0-7GWev9-wIfE3HKHIS_bv5XJn2GCP/pub?start=false&loop=false&delayms=3000