---
slug: /sdk.erc1155.airdrop
title: Erc1155.airdrop() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc1155.airdrop() method

Airdrop multiple NFTs

## Example

```javascript
// The token ID of the NFT you want to airdrop
const tokenId = "0";
// Array of objects of addresses and quantities to airdrop NFTs to
const addresses = [
  {
    address: "0x...",
    quantity: 2,
  },
  {
    address: "0x...",
    quantity: 3,
  },
];
await contract.airdrop(tokenId, addresses);

// You can also pass an array of addresses, it will airdrop 1 NFT per address
const tokenId = "0";
const addresses = ["0x...", "0x...", "0x..."];
await contract.erc1155.airdrop(tokenId, addresses);
```

**Signature:**

```typescript
airdrop(tokenId: BigNumberish, addresses: AirdropInput, data?: BytesLike): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type                                  | Description       |
| --------- | ------------------------------------- | ----------------- |
| tokenId   | BigNumberish                          |                   |
| addresses | [AirdropInput](./sdk.airdropinput.md) |                   |
| data      | BytesLike                             | <i>(Optional)</i> |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Airdrop one or multiple NFTs to the provided wallet addresses.
