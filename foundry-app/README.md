# DEX

This is the formula used, from Uniswap V1

```javascript
outputAmount = (outputReserve * inputAmount) / (inputReserve + inputAmount)
outputAmountWithFees = 0.99 * outputAmount
outputAmountWithFees = (outputAmount * 99) / 100
```

Here's a cool [article](https://blog.uniswap.org/uniswap-history) explaining the history of Uniswap
