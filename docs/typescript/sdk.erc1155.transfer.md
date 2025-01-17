---
slug: /sdk.erc1155.transfer
title: Erc1155.transfer() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc1155.transfer() method

Transfer a single NFT

## Example

```javascript
// Address of the wallet you want to send the NFT to
const toAddress = "{{wallet_address}}";
const tokenId = "0"; // The token ID of the NFT you want to send
const amount = 3; // How many copies of the NFTs to transfer
await contract.erc1155.transfer(toAddress, tokenId, amount);
```

**Signature:**

```typescript
transfer(to: string, tokenId: BigNumberish, amount: BigNumberish, data?: BytesLike): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type         | Description       |
| --------- | ------------ | ----------------- |
| to        | string       |                   |
| tokenId   | BigNumberish |                   |
| amount    | BigNumberish |                   |
| data      | BytesLike    | <i>(Optional)</i> |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Transfer an NFT from the connected wallet to another wallet.
