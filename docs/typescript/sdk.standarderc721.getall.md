---
slug: /sdk.standarderc721.getall
title: StandardErc721.getAll() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# StandardErc721.getAll() method

Get All Minted NFTs

## Example

```javascript
const nfts = await contract.getAll();
console.log(nfts);
```

**Signature:**

```typescript
getAll(queryParams?: QueryAllParams): Promise<NFT[]>;
```

## Parameters

| Parameter   | Type                                      | Description                                                             |
| ----------- | ----------------------------------------- | ----------------------------------------------------------------------- |
| queryParams | [QueryAllParams](./sdk.queryallparams.md) | <i>(Optional)</i> optional filtering to only fetch a subset of results. |

**Returns:**

Promise&lt;[NFT](./sdk.nft.md)\[\]&gt;

The NFT metadata for all NFTs queried.

## Remarks

Get all the data associated with every NFT in this contract.

By default, returns the first 100 NFTs, use queryParams to fetch more.
