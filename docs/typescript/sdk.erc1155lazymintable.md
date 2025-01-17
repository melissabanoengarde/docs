---
slug: /sdk.erc1155lazymintable
title: Erc1155LazyMintable class
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc1155LazyMintable class

**Signature:**

```typescript
export declare class Erc1155LazyMintable implements DetectableFeature
```

**Implements:** DetectableFeature

## Constructors

| Constructor                                                                                    | Modifiers | Description                                                             |
| ---------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------- |
| [(constructor)(erc1155, contractWrapper, storage)](./sdk.erc1155lazymintable._constructor_.md) |           | Constructs a new instance of the <code>Erc1155LazyMintable</code> class |

## Properties

| Property                                                                | Modifiers | Type                                                                                     | Description                                 |
| ----------------------------------------------------------------------- | --------- | ---------------------------------------------------------------------------------------- | ------------------------------------------- |
| [claim](./sdk.erc1155lazymintable.claim.md)                             |           | ERC1155Claimable &#124; undefined                                                        |                                             |
| [claimWithConditions](./sdk.erc1155lazymintable.claimwithconditions.md) |           | Erc1155ClaimableWithConditions &#124; undefined                                          | Claim tokens and configure claim conditions |
| [featureName](./sdk.erc1155lazymintable.featurename.md)                 |           | "ERC1155LazyMintableV2"                                                                  |                                             |
| [revealer](./sdk.erc1155lazymintable.revealer.md)                       |           | [DelayedReveal](./sdk.delayedreveal.md)&lt;BaseDelayedRevealERC1155&gt; &#124; undefined | Delayed reveal                              |

## Methods

| Method                                                                | Modifiers | Description                                        |
| --------------------------------------------------------------------- | --------- | -------------------------------------------------- |
| [lazyMint(metadatas, options)](./sdk.erc1155lazymintable.lazymint.md) |           | Create a batch of NFTs to be claimed in the future |
