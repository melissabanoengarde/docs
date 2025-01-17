---
slug: /sdk.erc20.burn
title: Erc20.burn() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc20.burn() method

Burn Tokens

## Example

```javascript
// The amount of this token you want to burn
const amount = 1.2;

await contract.erc20.burn(amount);
```

**Signature:**

```typescript
burn(amount: Amount): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type                      | Description |
| --------- | ------------------------- | ----------- |
| amount    | [Amount](./sdk.amount.md) |             |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Burn tokens held by the connected wallet
