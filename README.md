<div align=center >
    <h1>Netpractice</h1>
    <img src="https://raw.githubusercontent.com/viruskizz/viruskizz-myutils/main/badge04-netpractice.png" alt="minishell badge" />
</div>

## _42Bangkok's project_

The **Netpractice** 42 project is a general practical exercise to let you discover networking. You will have to configure small-scale networks. To do so, it will be necessary to understand how TCP/IP addressing works.

You will have to complete 10 levels (i.e. 10 exercises) and turn them in your Git
repository.

## Guide :bookmark_tabs:

Read my full guide in [Netpractice 42Bangkok guide]

### My learning resource
This resource is coverage all knowledge that you should know. It short and good explaination

- [Classless Inter-Domain Routing]
- [Subnet mask sheet]
- [CIDR]
- [Broadcast Address]

## Concept

### Configuration
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

### Step to solve problem
1. Check CIDR or Subnet mask
2. Check specific client ip that is assigned
3. calculate available ip range in subnet
4. Config route table follow by problem goals

### How to pass the evaluation

1. Memorize CIDR table
2. Practice level 6 to 10 from thinking to muscle memory

### CIDR Sheet table

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

## Get started

With these resources you can get through it in every level but it not easy anyway
.
.
~~ Good luck

<div style="width: 50%; min-width: 480px">
    <img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/woff-cloud-fight.gif" alt="challenge-yaself">
</div>

---

## Learn Basic Network :book:

You also can learn basic network config in level 1 - 5

<details>
<summary>Level 1</summary>

Every client need to be set as different ip address.

<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level1solve.png" alt="solve-level-7">
</details>

<details>
<summary>Level 2</summary>
Border ip is cannot be used because it is reserved for network transmission.

<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level2solve.png" alt="solve-level-2">
</details>

<details>
<summary>Level 3</summary>
Border ip is cannot be used because it is reserved for network transmission.

<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level3solve.png" alt="solve-level-3">
</details>

<details>
<summary>Level 4</summary>
Border ip is cannot be used because it is reserved for network transmission.

<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level4solve.png" alt="solve-level-4">
</details>

<details>
<summary>Level 5</summary>
Border ip is cannot be used because it is reserved for network transmission.

<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level5solve.png" alt="solve-level-5">
</details>

---

## Challenge ya self :game_die:

I would like to provide a hint for every level from 6 - 10

<div style="width: 50%; min-width: 480px">
    <img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/woff-sephiroth-burn.gif" alt="challenge-yaself">
</div>

### Hint 

<dl>
<details>
<summary>Level 6</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/hint/level6hint.png" alt="hint-level-6">
</details>

<details>
<summary>Level 7</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/hint/level7hint.png" alt="hint-level-7">
</details>

<details>
<summary>Level 8</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/hint/level8hint.png" alt="hint-level-8">
</details>

<details>
<summary>Level 9</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/hint/level9hint.png" alt="hint-level-9">
</details>

<details>
<summary>Level 10</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/hint/level10hint.png" alt="hint-level-10">
</details>
</dl>

---

## Burn da problem :crossed_swords:

Peek the answer to check your solution and earn your point.

<div style="width: 50%; min-width: 480px">
    <img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/assets/woff-tifa-burn.gif" alt="burn-ya-point">
</div>

### Solution

<details>
<summary>Level 6</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level6solve.png" alt="solve-level-6">
</details>

<details>
<summary>Level 7</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level7solve.png" alt="solve-level-7">
</details>

<details>
<summary>Level 8</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level8solve.png" alt="solve-level-8">
</details>

<details>
<summary>Level 9</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level9solve.png" alt="solve-level-9">
</details>

<details>
<summary>Level 10</summary>
<img src="https://raw.githubusercontent.com/viruskizz/42bangkok-netpractice/main/solve/level10solve.png" alt="solve-level-10">
</details>

<!-- Link -->
[Netpractice 42Bangkok guide]: https://docs.google.com/presentation/d/e/2PACX-1vSHNDVR-drtwoUsNS-kfkYPyMKcTXB4X2i4kHyJlbCmz9thSo0-7GWev9-wIfE3HKHIS_bv5XJn2GCP/pub?start=false&loop=false&delayms=3000
[Classless Inter-Domain Routing]: https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing
[Subnet mask sheet]: https://dnsmadeeasy.com/support/subnet
[CIDR]: https://cidr.xyz/
[Broadcast Address]: https://en.wikipedia.org/wiki/Broadcast_address