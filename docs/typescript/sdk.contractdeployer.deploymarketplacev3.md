---
slug: /sdk.contractdeployer.deploymarketplacev3
title: ContractDeployer.deployMarketplaceV3() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# ContractDeployer.deployMarketplaceV3() method

Deploys a new Marketplace-V3 contract

## Example

```javascript
const contractAddress = await sdk.deployer.deployMarketplaceV3({
  name: "My Marketplace",
  primary_sale_recipient: "your-address",
});
```

**Signature:**

```typescript
deployMarketplaceV3(metadata: MarketplaceV3ContractDeployMetadata): Promise<string>;
```

## Parameters

| Parameter | Type                                                                                | Description           |
| --------- | ----------------------------------------------------------------------------------- | --------------------- |
| metadata  | [MarketplaceV3ContractDeployMetadata](./sdk.marketplacev3contractdeploymetadata.md) | the contract metadata |

**Returns:**

Promise&lt;string&gt;

the address of the deployed contract

## Remarks

Deploys a Marketplace-V3 contract and returns the address of the deployed contract
