---
slug: /sdk.contractdeployer.deployreleasedcontract
title: ContractDeployer.deployReleasedContract() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# ContractDeployer.deployReleasedContract() method

Deploy any released contract by its name

**Signature:**

```typescript
deployReleasedContract(releaserAddress: string, contractName: string, constructorParams: any[], version?: string, options?: DeployOptions): Promise<string>;
```

## Parameters

| Parameter         | Type                                    | Description                                    |
| ----------------- | --------------------------------------- | ---------------------------------------------- |
| releaserAddress   | string                                  | the address of the releaser                    |
| contractName      | string                                  | the name of the contract to deploy             |
| constructorParams | any\[\]                                 | the constructor params to pass to the contract |
| version           | string                                  | <i>(Optional)</i>                              |
| options           | [DeployOptions](./sdk.deployoptions.md) | <i>(Optional)</i>                              |

**Returns:**

Promise&lt;string&gt;
