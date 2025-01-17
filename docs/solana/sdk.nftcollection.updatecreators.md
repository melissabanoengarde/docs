---
slug: /sdk.nftcollection.updatecreators
title: NFTCollection.updateCreators() method
hide_title: true
displayed_sidebar: solana
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# NFTCollection.updateCreators() method

Update the creators of the collection

**Signature:**

```typescript
updateCreators(creators: CreatorInput[], updateAll?: boolean): Promise<TransactionResult[]>;
```

## Parameters

| Parameter | Type                                      | Description                                                                            |
| --------- | ----------------------------------------- | -------------------------------------------------------------------------------------- |
| creators  | [CreatorInput](./sdk.creatorinput.md)\[\] | the creators to update                                                                 |
| updateAll | boolean                                   | <i>(Optional)</i> whether or not to retroactively update the creators of all past NFTs |

**Returns:**

Promise&lt;TransactionResult\[\]&gt;
