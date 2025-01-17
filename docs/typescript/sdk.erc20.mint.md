---
slug: /sdk.erc20.mint
title: Erc20.mint() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc20.mint() method

Mint Tokens

## Example

```javascript
const amount = "1.5"; // The amount of this token you want to mint
await contract.erc20.mint(toAddress, amount);
```

**Signature:**

```typescript
mint(amount: Amount): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type                      | Description |
| --------- | ------------------------- | ----------- |
| amount    | [Amount](./sdk.amount.md) |             |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Mint tokens to the connected wallet.
