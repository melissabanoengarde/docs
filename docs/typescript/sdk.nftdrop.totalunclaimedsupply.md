---
slug: /sdk.nftdrop.totalunclaimedsupply
title: NFTDrop.totalUnclaimedSupply() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# NFTDrop.totalUnclaimedSupply() method

Get the unclaimed supply

## Example

```javascript
const unclaimedNFTCount = await contract.totalUnclaimedSupply();
console.log(`NFTs left to claim: ${unclaimedNFTCount}`);
```

**Signature:**

```typescript
totalUnclaimedSupply(): Promise<BigNumber>;
```

**Returns:**

Promise&lt;BigNumber&gt;

the unclaimed supply

## Remarks

Get the number of unclaimed NFTs in this Drop.

\*
