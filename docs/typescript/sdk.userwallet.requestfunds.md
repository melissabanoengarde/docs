---
slug: /sdk.userwallet.requestfunds
title: UserWallet.requestFunds() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# UserWallet.requestFunds() method

Request funds from a running local node to the currently connected wallet

**Signature:**

```typescript
requestFunds(amount: Amount): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type                      | Description                                       |
| --------- | ------------------------- | ------------------------------------------------- |
| amount    | [Amount](./sdk.amount.md) | the amount in native currency (in ETH) to request |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;
