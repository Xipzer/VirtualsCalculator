# AMM Calculator for Virtuals Protocol

This project consists of two notebooks. These notebooks are designed 
to provide examples for the inputs/outputs involved in the dynamical systems
of AMMs and Virtuals' Buyback & Burn Programme.

The outcomes from using these notebooks may be enhanced notion of how blockchain
Automated Market Maker (AMM) systems work (commonly used in on-chain liquidity pools), 
and improved knowledge of trading structure.

_DISCLAIMER: These are educational notebooks and should not be used (in isolation) to develop 
theses for trading the Buyback Programme._

## Config

This project requires Python and Jupyter Notebook, in order to execute.

```shell
pip install jupyter
```

## VIRTUALS PROTOCOL STATIC METRICS (StaticMetrics)
### Usage

The following variables are present within the notebook, allowing you to customise the results of various calculations.

```
ticker = "$MISATO"
```
"ticker" - A static string used to append a given token name to a token output calculation, for clarity.

```
virtuals_price = 3.6
```
"virtuals_price" - A static float used to determine the USD price for outputs involving liquidity and token price.

```
total_supply = 1000000000 # DO NOT CHANGE FOR VIRTUALS PROTOCOL AGENTS
```
"total_supply" - An integer/float that represents the total available supply of a given token.

```
supply_tokens = 49363522
```
"supply_tokens" - An integer/float that represents the value of supply tokens in the LP, at the present moment.

```
liquidity_tokens = 100884
```
"liquidity_tokens" - An integer/float that represents the value of liquidity tokens (VIRTUAL, WETH, USDT ...) in the LP, 
at the present moment.

```
supply_in = 10000000
```
"supply_in" - An integer/float that represents the amount of supply tokens being sold.

```
liquidity_in = 16994
```
"liquidity_in" - An integer/float that represents the amount of liquidity tokens being spent to buy supply tokens.

```
target_liquidity_tokens = 200000
```
"target_liquidity_tokens" - An integer/float representing the designated LP value for metrics to be provided for.

```
buyback_tokens = 690344
```
"buyback_tokens" - An integer/float representing the total liquidity tokens contributed to buybacks, 
for the Virtuals Protocol Buyback Programme.

```
sizing = 250
```
"sizing" - The position size used to calculate the new $VIRTUAL accumulated from the daily buyback profitability.

## VIRTUALS PROTOCOL DYNAMIC METRICS (DynamicMetrics)
### Usage

The following variables are present within the notebook, allowing you to customise the results of various calculations.

```
user_wallet = "0x123..."
```
"user_wallet" - A string representing your personal wallet (public key).

```
agent_token = "0x123..."
```
"agent_token" - A string representing a given token (agent) contract address to be analyzed.

```
liquidity_in = 250
```
"liquidity_in" - An integer/float that represents the amount of liquidity tokens being spent to buy supply tokens.

```
buyback_tokens = 690344
```
"buyback_tokens" - An integer/float representing the total liquidity tokens contributed to buybacks, 
for the Virtuals Protocol Buyback Programme.

```
sizing = 250
```
"sizing" - The position size used to calculate the new $VIRTUAL accumulated from the daily buyback profitability.

###### ~Xipzer