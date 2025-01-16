# AMM Calculator for Virtuals Protocol

This notebook is designed to provide examples for different metric
outputs that may help to establish a trading structure within Virtuals Protocol.

It may also help to educate on the mechanics of the Automated Market Maker (AMM) formula,
commonly used in on-chain liquidity pools.

_DISCLAIMER: This is an educational notebook and should not be used (in isolation) to develop 
theses for trading the Buyback Programme._

## Config

This project requires Python and Jupyter Notebook, in order to execute.

```shell
pip install jupyter
```

## Usage

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
target_liquidity_tokens
```
"target_liquidity_tokens" - An integer/float representing the designated LP value for metrics to be provided for.

```
buyback_tokens
```
"buyback_tokens" - An integer/float representing the total liquidity tokens contributed to buybacks, 
for the Virtuals Protocol Buyback Programme.

###### ~Xipzer