---
slug: /sdk.erc20signaturemintable.mintbatch
title: Erc20SignatureMintable.mintBatch() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc20SignatureMintable.mintBatch() method

Mint any number of generated tokens signatures at once

**Signature:**

```typescript
mintBatch(signedPayloads: SignedPayload20[]): Promise<TransactionResult>;
```

## Parameters

| Parameter      | Type                                            | Description                          |
| -------------- | ----------------------------------------------- | ------------------------------------ |
| signedPayloads | [SignedPayload20](./sdk.signedpayload20.md)\[\] | the array of signed payloads to mint |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Mint multiple token signatures in one transaction. Note that this is only possible for free mints (cannot batch mints with a price attached to it for security reasons)
