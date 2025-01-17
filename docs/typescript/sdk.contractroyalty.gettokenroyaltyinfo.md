---
slug: /sdk.contractroyalty.gettokenroyaltyinfo
title: ContractRoyalty.getTokenRoyaltyInfo() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# ContractRoyalty.getTokenRoyaltyInfo() method

Gets the royalty recipient and BPS (basis points) of a particular token

## Example

```javascript
const royaltyInfo = await contract.royalties.getDefaultRoyaltyInfo();
```

**Signature:**

```typescript
getTokenRoyaltyInfo(tokenId: BigNumberish): Promise<{
        seller_fee_basis_points: number;
        fee_recipient: string;
    }>;
```

## Parameters

| Parameter | Type         | Description |
| --------- | ------------ | ----------- |
| tokenId   | BigNumberish |             |

**Returns:**

Promise&lt;{ seller_fee_basis_points: number; fee_recipient: string; }&gt;

- The royalty recipient and BPS
