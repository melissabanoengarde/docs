---
slug: /sdk.standarderc20.get
title: StandardErc20.get() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# StandardErc20.get() method

Get the token Metadata (name, symbol, etc...)

## Example

```javascript
const token = await contract.get();
```

**Signature:**

```typescript
get(): Promise<Currency>;
```

**Returns:**

Promise&lt;[Currency](./sdk.currency.md)&gt;

The token metadata
