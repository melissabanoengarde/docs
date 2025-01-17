---
slug: /sdk.smartcontract.call
title: SmartContract.call() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# SmartContract.call() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Call any function on this contract

## Example

```javascript
// read functions will return the data from the contract
const myValue = await contract.call("myReadFunction");
console.log(myValue);

// write functions will return the transaction receipt
const tx = await contract.call("myWriteFunction", arg1, arg2);
const receipt = tx.receipt;

// Optionally override transaction options
await contract.call("myWriteFunction", arg1, arg2, {
 gasLimit: 1000000, // override default gas limit
 value: ethers.utils.parseEther("0.1"), // send 0.1 ether with the contract call
};
```

**Signature:**

```typescript
call(functionName: string, ...args: unknown[] | [...unknown[], CallOverrides]): Promise<any>;
```

## Parameters

| Parameter    | Type                                                 | Description                      |
| ------------ | ---------------------------------------------------- | -------------------------------- |
| functionName | string                                               | the name of the function to call |
| args         | unknown\[\] &#124; \[...unknown\[\], CallOverrides\] | the arguments of the function    |

**Returns:**

Promise&lt;any&gt;
