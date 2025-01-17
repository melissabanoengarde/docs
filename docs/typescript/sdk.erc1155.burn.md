---
slug: /sdk.erc1155.burn
title: Erc1155.burn() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc1155.burn() method

Burn a specified amount of a NFTs

## Example

```javascript
// The token ID to burn NFTs of
const tokenId = 0;
// The amount of the NFT you want to burn
const amount = 2;

const result = await contract.erc1155.burn(tokenId, amount);
```

**Signature:**

```typescript
burn(tokenId: BigNumberish, amount: BigNumberish): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type         | Description          |
| --------- | ------------ | -------------------- |
| tokenId   | BigNumberish | the token Id to burn |
| amount    | BigNumberish | amount to burn       |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Burn the specified NFTs from the connected wallet
